﻿<html>
<head>
<title>Системное событие диалога ClickDropDown</title>
</head>

<body>

<p><font face="Arial"><font size="4"><strong>Событие ClickDropDown<br>
<br>
</strong></font><a href="../scriptstproced.html">См. также</a>&nbsp; <u>Пример</u>&nbsp;
<a href="../Functions/Asustpar.html">Применяется к</a></font></p>

<p class="label"><font face="Arial">В некоторых случаях, при выборе 
значений реквизитов документа типа <a
href="../Types/Tree().html">Tree()</a>, <a href="../Types/FULLTREE().html">
FullTree()</a>, <a
href="../Types/Folder().html">Folder()</a>, <a href="../Types/Ch().html">CH()</a> 
необходимо приводить не весь список одноуровневого дерева или папки, а некоторое 
его отфильтрованное подмножество. В обработчике события нужно создать экземпляр <a href="../Functions/AsModalBrowser.html">
объекта типа произвольный вспомогательный список</a> или
<a href="../Functions/AsTreeModalBrowser.html">объекта типа иерархический 
вспомогательный список</a>, который и будет появляться при нажатии кнопки выбора 
значения реквизита.  </font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial">Sub <strong>ClickDropDown</strong> (</font><em><font face="Arial">objDialog, </font></em><font face="Arial">
<strong style="font-weight: 400"><em>RekvName</em></strong>,
<em>Top</em>, <em>Left</em>, [<em>sValue</em>])</font></p>

<p><font face="Arial">&nbsp;&nbsp; <strong>Select Case</strong> <strong>
RekvName</strong>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>RekvName1</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statements1</em><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>RekvName2</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statements2</em><br>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; . . . . .<br>
</strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Case</strong> <em>RekvNameN</em><br>
<em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; statementsN</em><br>
<strong>&nbsp;&nbsp;&nbsp; End Select&nbsp; </strong>&nbsp;&nbsp; <br>
<br>
End Sub</font></p>

<p><font face="Arial">Синтаксис события <strong>ClickDropDown</strong>
состоит из следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%" height="36"><em><font face="Arial">objDialog</font></em></td>
    <td width="71%" height="36"><font face="Arial">строковое 
	выражение, определяющее переменную, ссылающуюся на экземпляр объекта 
	пользовательского диалога.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Rekv_i</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор реквизита, для которого сгенерировано данное 
	событие.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Top</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Single, 
	определяющее расстояние между верхним краем вспомогательного списка и 
	верхним краем формы документа.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>Left</em></font></td>
    <td width="71%"><font face="Arial">выражение типа Single, 
	определяющее расстояние между левым краем вспомогательного списка и левым 
	краем формы документа.</font></td>
  </tr>
  <tr>
    <td width="29%" height="9"><font face="Arial"><i>sValue</i></font></td>
    <td width="71%" height="9"><font face="Arial">выражение типа 
	Variant, определяющее значение реквизита на данный момент. </font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>statements_i</em></font></td>
    <td width="71%"><font face="Arial">подпрограмма создания ссылки на <a href="../Functions/AsModalBrowser.html">
	объект типа произвольного вспомогательного списка</a> или
    <a href="../Functions/AsTreeModalBrowser.html">объекта типа иерархический 
	вспомогательный список</a>.</font></td>
  </tr>
</table>
</body>
</html>