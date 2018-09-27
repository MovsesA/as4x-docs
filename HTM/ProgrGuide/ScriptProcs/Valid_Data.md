﻿<html>
<head>
<title>Системное событие источника данных Valid</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Событие Valid<br>
<br>
</strong></font><a href="../scriptstproced.html">См. также</a>&nbsp; <a
href="../Examples/E_Valid_Data.html">Пример</a>&nbsp; <a href="../Defs/Data.html">
Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется при загрузке 
источника данных строками из базы данных. Проверяет некоторое условие для каждой 
строки источника данных. Если условие не выполняется, то обрабатываемая строка 
не добавляется в источник данных. Данное событие предотвращает выполнение 
события OnEachRow для тех строк, для которых Valid = False. Т.о. для каждой 
строки перед выполнением события <a href="OnEachRow.html">OnEachRow</a>, 
выполняется <strong>Valid</strong>, который и решает вхождение строчки в 
источник данных.<br>
Последовательность генерации системных событий для источника данных приведена 
здесь <a
href="Events_Sequence_Data.html"><img src="../../../IMAGES/More.gif" width="12" height="12"
alt="More.gif (304 bytes)" border="0"></a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Function <strong>Valid</strong>  ()<br>
<em>&nbsp;&nbsp; statements</em><br>
End Function</font></p>

</body>
</html>