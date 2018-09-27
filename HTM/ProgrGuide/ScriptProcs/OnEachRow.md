﻿<html>
<head>
<title>Системное событие OnEachRow</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Событие OnEachRow<br>
<br>
</font></strong><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <a href="../Examples/E_OnEachRow.html">Пример</a>&nbsp; <a
href="../Defs/Data.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется для каждой строки 
источника данных, при его открытии. Происходит при открытии источника данных 
методом <a href="../Functions/ASDATA/OpenCursor.html">OpenCursor</a>,&nbsp;передвижении 
текущей строчки в источнике данных методами <a
href="../Functions/ASDATA/MoveFirst.html">MoveFirst</a>, <a
href="../Functions/ASDATA/MoveNext.html">MoveNext</a>, <a
href="../Functions/ASDATA/MoveLast.html">MoveLast</a>, а также при обновлении 
формы прокрутки папок методом <a
href="../Functions/FrmPttel/Update.html">Update</a>. Обработчик события удобен 
для получения значений виртуальных колонок в источнике данных, у которых в 
описании опция <a href="../Defs/Data.html">Source</a>=1. Данное событие 
выполняется после выполнения событий <a href="OnOpen.html">OnOpen</a>
и <a href="Valid_Data.html">Valid</a>. Последовательность генерации системных 
событий для источника данных приведена здесь <a href="Events_Sequence_Data.html"><img
src="../../../IMAGES/More.gif" width="12" height="12" alt="More.gif (304 bytes)"
border="0"></a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>OnEachRow</strong>()<br>
<em>&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p class="label">&nbsp;</p>
</body>
</html>