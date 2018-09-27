﻿<html>
<head>
<title>Системное событие NestedTransaction</title>
</head>

<body>

<p><font size="4" face="Arial"><strong>Событие NestedTransaction<br>
<br>
</strong></font><font face="Arial"><a href="../scriptstproced.html">См. 
также</a>&nbsp; <u>Пример</u>&nbsp; <a href="../Defs/doc.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">Генерируется при использовании 
свойства <a
href="../Functions/ASDOC/NestedTransactions.html">NestedTransactions</a>. 
Последовательность генерации системных событий для документа приведена здесь <a href="Events_Sequence.html"><img
src="../../../IMAGES/More.gif" width="12" height="12" alt="More.gif (304 bytes)"
border="0"></a>. </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>NestedTransaction</strong> (ByVal<em>
ArrElement,[byval objRepView</em>])<br>
<em>&nbsp;&nbsp;&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p><font face="Arial"><br>
Синтаксис события <strong>NestedTransaction</strong> состоит из следующих 
частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>ArrElement</em></font></td>
    <td width="71%"><font face="Arial">элемент массива-аргумента 
	свойства <a
    href="../Functions/ASDOC/NestedTransactions.html">NestedTransactions</a>.</font></td>
  </tr>
	<tr>
    <td width="29%"><font face="Arial"><em>objRepView</em></font></td>
    <td width="71%"><font face="Arial">необязательная переменная, 
	ссылающаяся на предварительно созданный экземпляр объекта 
	<a
    href="../Functions/AsRepViewer.html">отчет.</a></font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Примечание<br>
<br>
</b>При обработке данного события желательно производить проводки, вызывая 
функцию <a href="../Functions/Functions/AccManagement/CreateFact.html">CreateFact</a> 
и метод <a
href="../Functions/ASDOC/StoreFact.html">StoreFact</a>. Нежелательно в 
обработчике данного события сохранять документ методом <a href="../Functions/ASDOC/Store.html">
Store</a>.</font></p>
</body>
</html>