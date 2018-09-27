﻿<html>
<head>
<title>GridValid</title>
</head>

<body>

<p><font size="3" face="Arial"><strong>Пример события GridValid</strong></font></p>

<p><font face="Arial">Ниже приведен пример обработчика события <strong>
GridValid</strong> из <a
href="../Defs/doc.html">описания документа</a>.<br>
<br>
Sub <strong>GridValid</strong>(ByVal GridSource)<br>
&nbsp;&nbsp;&nbsp; If GridSource.<a href="../Functions/ASDOC/AsGrid/RowCount.html">RowCount</a>=0 
Then Exit Sub<br>
&nbsp;&nbsp;&nbsp; For xCount=GridSource.RowCount-1 to 0 Step -1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; xFirstRow = 0<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For i=1 to xCount<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if 
IIF(ArrDirectIsGrow, GridSource(i,GridCol) &lt; GridSource(xFirstRow,GridCol), _<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
GridSource(i,GridCol) &gt; GridSource(xFirstRow,GridCol)) then xFirstRow=i<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Next<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GridSource.<a
href="../Functions/ASDOC/AsGrid/AddRow.html">AddRow</a><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; For i=0 to GridSource.<a
href="../Functions/ASDOC/AsGrid/ColCount.html">ColCount</a>-1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
GridSource(GridSource.RowCount-1,i) = GridSource(xFirstRow,i)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Next<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GridSource.<a
href="../Functions/ASDOC/AsGrid/RemoveRow.html">RemoveRow</a>(xFirstRow)<br>
&nbsp;&nbsp;&nbsp; Next<br>
&nbsp;&nbsp;&nbsp; If GridRefresh Then GridSource.<a
href="../Functions/ASDOC/AsGrid/Refresh.html">Refresh</a><br>
End Sub<br>
</font></p>
</body>
</html>