﻿<html>
<head>
<title>Suid</title>
</head>

<body>

<p><font size="3" face="Arial"><strong>Пример свойства Suid</strong></font></p>

<p><font face="Arial">Ниже приведен пример подсчета сумм проводок в 
НДЕ и валюте для возвращаемой коллекции проводок.</font></p>

<p><font face="Arial">Set xFact =<a href="../Functions/Functions/AccManagement/LoadFactByObject.html">LoadFactByObject</a>(Accounting, 
ISN, xLastDate, xLastDate, Op)<br>
For i=1 to xFact.Count <br>
&nbsp; nSum=xFact(i).<a href="../Functions/ASFACT/Summa.html">Summa</a><br>
&nbsp; nCurSum=xFact(i).<a href="../Functions/ASFACT/CurSumma.html">CurSumma</a><br>
&nbsp;&nbsp; nSuid = xFact(i)<strong>.Suid</strong><br>
Next </font></p>
</body>
</html>