﻿<html>
<head>
<title>Системное событие опис. диалога _ClickDropDown</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Событие _ClickDropDown<br>
<br>
</strong></font><a href="../Functions/AsDialogEx/ClickDropDownEvent.html">См. 
также</a>&nbsp;
<u>Пример</u>&nbsp; <a href="../Defs/Dialog.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">В некоторых случаях, при выборе 
значений реквизитов диалога типа <a
href="../Types/Tree().html">Tree()</a>, <a href="../Types/FULLTREE().html">
FullTree()</a>, <a
href="../Types/Folder().html">Folder()</a>, необходимо приводить не весь список 
одноуровневого дерева или папки, а некоторое его отфильтрованное подмножество. 
Этого можно достичь в обработчике системного события <strong>_ClickDropDown</strong>, 
если генерация данного события <a href="../Functions/AsDialogEx/ClickDropDownEvent.html">
разрешена</a>
ядром системы. В обработчике события нужно создать экземпляр <a href="../Functions/AsModalBrowser.html">
объекта типа произвольный вспомогательный список</a>, который и будет появляться 
при нажатии кнопки выбора значения реквизита. Т.о. в результате нажатия кнопки 
выбора будет приводиться не папка, указанная в описании реквизита, а 
отфильтрованный вспомогательный список.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <em>ContrName</em><strong>_ClickDropDown()<br>
</strong><em>&nbsp;&nbsp;&nbsp; statements</em><br>
End Sub</font></p>

<p><font face="Arial"><br>
Синтаксис события <strong>ClickDropDown</strong> состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><em><font face="Arial">ContrName</font></em></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита в диалоге, для которого сгенерировано 
	данное событие.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>statements</em></font></td>
    <td width="71%"><font face="Arial">подпрограмма создания ссылки на <a href="../Functions/AsModalBrowser.html">
	объект типа произвольного вспомогательного списка</a>.</font></td>
  </tr>
</table>

<p class="label">&nbsp;</p>

<p>&nbsp;</p>
</body>
</html>