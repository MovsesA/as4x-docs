﻿<html>
<head>
<title>Системное событие BeforeCommit</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Событие BeforeCommit<br>
<br>
</strong></font><a href="../scriptstproced.html">См. также</a>&nbsp; <u>Пример</u>&nbsp;
<a href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Событие происходит при окончании 
обработки документа непосредственно перед фиксированием транзакции. При 
обработке события гарантированно что документ сохранен в БД. Так документ уже 
записан в БД, при обработке данного события бессмысленно изменять свойстава 
документа, генерировать проводки и т.д.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>BeforeCommit</strong>()&nbsp;&nbsp;<br>
&nbsp;&nbsp; <em>statements</em><br>
End Sub</font></p>
</body>
</html>