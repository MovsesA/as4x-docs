﻿<html>
<head>
<title>Описание реквизита</title>
<style type="text/css">
.style1 {
	font-size: large;
}
.style3 {
	font-weight: bold;
	border: 1px solid #C5C5C5;
}
.style9 {
	border-color: #000000;
	border-width: 0;
}
.style10 {
	font-weight: bold;
	border: 0 solid #000000;
}
.style11 {
	border: 1px solid #C5C5C5;
}
    .style13
    {
        font-family: Arial;
    }
    .style14
    {
        font-family: Arial;
        font-size: medium;
    }
</style>
</head>

<body>
<font face="Arial"><strong>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<span class="style1">&nbsp; Описание реквизита&nbsp;&nbsp;&nbsp; </span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<br />

Синтаксис<br />

    <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

    Rekvizit</strong> {<strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Name </strong>=<em> sRekvName</em>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Caption </strong>=<em> sRekvCaption</em>;<strong>
</strong>
    &nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ECaption </strong>=<em> sRekvECaption</em>;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; 
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Type </strong>=<em> sRekvType</em>;
    <strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp; Atributs </strong>=<em> sRekvAtr</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; DisplayAtLeft </strong>=<em> nDisplayAtLeft</em>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; 
<strong>ShowCaption </strong>=<em> nShowCaption</em>;
&nbsp;&nbsp;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<strong>Distance </strong>=<em> nDistance</em>;&nbsp;&nbsp;&nbsp; <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
<strong>CommentLen </strong>=<em> nCommentLen</em>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<strong>ShowType </strong>= <em>sRekvShowType;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
&nbsp;&nbsp;
<strong>&nbsp;DropDown&nbsp; </strong> </em>{ <em><strong>V</strong><span lang="ru"><strong>iewName</strong></span> = sViewName;
    <strong>C</strong><span lang="ru"><strong>ode</strong></span> = s<span lang="ru">View</span>Code<span lang="ru">Col</span>;<strong> Comment</strong></span> = 
    sViewCaptionCol</span>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;paramValue { N</strong><span lang="ru"><strong>ame</strong></span> 
= sParamName1;<strong> V</strong><span lang="ru"><strong>alue</strong></span>= 
sParamValue1;</em>}<em>;<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ............<strong><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</strong><span lang="ru"><strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;paramValue 
    { Name</strong></span> = sParamNameN; <strong>V<span lang="ru">alue</span></strong>= 
sParamValueN;</em>};<em><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</em>};<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; };<br />
&nbsp;</font><table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style10" style="width: 1%">&nbsp;</td>
    <td class="style3" width="29%"><font face="Arial">Параметр</font></td>
    <td class="style11" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><em><font face="Arial">sRekvName</font></em></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее идентификатор реквизита</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><em><font face="Arial">sRekvCaption</font></em></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее заголовок реквизита</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><em><font face="Arial">sRekvECaption</font></em></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее заголовок реквизита на иностранном
    языке</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><em><font face="Arial">sRekvType</font></em></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее <a href="types.html">внутренний тип</a>
    реквизита</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><em><font face="Arial">sRekvAtr</font></em></td>
    <td width="71%" class="style11"><font face="Arial">строковое выражение,
    определяющее атрибуты реквизита. Их может быть
    сразу несколько. Они принимают значения:
    <strong><br />
&nbsp;- R</strong> определяет обязательность заполнения
    данного реквизита,
    <strong><br />
&nbsp;- S</strong> определяет признак вторичного ввода
    данного реквизита, 
    <strong><br />
&nbsp;- C</strong> для типов <a href="Types/Tree().html">Tree</a>, 
	<a href="Types/FULLTREE().html">FullTree</a>, <a href="Types/Folder().html">Folder</a>
    скрывает наименование реквизита после его
    выбора из списка , а для реквизита типа <a href="Types/Date.html">Date</a> показывает рядом наименование
    дня недели,<br />
	<strong>&nbsp;- B</strong> скрывает кнопку выбора из списка, а
    для числовых типов означает показ либо
    калькулятора либо обработки события DropDown,<br />
&nbsp;<b>- I</b> данный реквизит редактировать в режиме Overwrite вместо Insert 
	(только для типа C(x))<strong><br />
&nbsp;- H</strong> скрытый невидимый реквизит, при его
    наличии остальные атрибуты реквизита
    игнорируются,<br />
&nbsp;<strong>- N</strong> в режиме последовательного ввода
    реквизит сохраняет значение из предыдущего
    документа,<br />
	<strong>&nbsp;- U</strong> признак преобразования латинских строчных 
    букв на прописные,<strong><br />
&nbsp;- F</strong> признак использования 
    альтернативного(русского) шрифта для колонки,<br />
	<b>&nbsp;- V </b>отключает проверку реквизита при сохранении документа<b>,<br />
&nbsp;-
	Z </b>В режиме только для чтения<b> </b>Tab/Enter не пропускают этот реквизит,<br />
	<b>
	&nbsp;- P </b>данный реквизит получит фокус при активизации формы документа,<br />
	<b>
	&nbsp;- E </b>отключает проверку наличия вводимого значения в соответствующем списке. Используется для реквизитов типа <a href="Types/Tree().html">Tree</a>, <a href="Types/Tree().html">Folder</a> и <a href="Types/Tree().html">
        AsCource(Numpair)</a>.<br />
	<strong>&nbsp;- T</strong> значение реквизита не сохраняется в бахе данных, 
	заначения таких реквизитов обычно поределяется при загрузке докумета в 
	событии <a href="ScriptProcs/AfterLoad.html">AfterLoad</a>.</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><font face="Arial"><em>nDisplayAtLeft</em></font></td>
    <td width="71%" class="style11"><font face="Arial">необязательное численное 
    выражение, принимающее значения 0,1 или 2.<br />
	По умолчанию принимает значение 0,&nbsp; реквизит будет установлен с новой 
	строки.<br />
	Значение 1 означает, что реквизит будет установлен с<span lang="ru">пра</span>ва от предыдущего реквизита.<span lang="ru">
	<br />
	Если параметр принимает значение 2,то реквизит 
	устанавливается на расстоянии <em>nDistance
	</em>от левого края формы.</span></font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><font face="Arial"><em>nShowCaption</em></font></td>
    <td width="71%" class="style11"><font face="Arial">необязательное численное 
    выражение, принимающее значения 1 или 0, определяющее признак показа 
    заголовка реквизита справа от него. Установка данного признака имеет смысл 
    только при<em> nDisplayAtRight &lt;&gt;0 .</em>По умолчанию принимает значение 0. </font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><font face="Arial"><em>nDistance</em></font></td>
    <td width="71%" class="style11"><font face="Arial">необязательное численное 
    выражение, определяющее величину расстояния реквизита от предыдущего 
    резвизита. По умолчанию принимает значение 100.</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11"><font face="Arial"><em>nCommentLen</em></font></td>
    <td width="71%" class="style11"><font face="Arial">необязательное численное 
    выражение, определяющее длину комментарий для типов
    <a href="Types/Folder().html">Folder()</a>, <a href="Types/Tree().html">Tree()</a> и 
	<a href="Types/FULLTREE().html">FullTree()</a>. По умолчанию 
    принимает значение 32.</font></td>
  </tr>
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em>sRekvShowType</em></font></td>
    <td width="71%" class="style11">
	<span style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">
	необязательное строковое выражение, определяющее </span>
	<span style="mso-fareast-font-family: 'Times New Roman'" 
            class="style14">
	внутренний тип данных р<span lang="ru">еквизита</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">
	</span>
	<span lang="RU" 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">
	при показе.</span><span 
            style="FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'" 
            class="style13">&nbsp;</span><span 
            style="mso-fareast-font-family: 'Times New Roman'" 
            class="style13"><span lang="ru">Используется 
	только с <a href="Types/C().html">символьным типом данных</a> и имеет следующий 
	формат</span>:<span lang="ru"> С(</span></span><span style="FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'"><span 
            style="mso-fareast-font-family: 'Times New Roman'" 
            class="style14">nRowCount * nSymbPerRow<span lang="ru">), 
	где</span> <span lang="ru">nRowCount </span>- <span lang="ru">количество 
	строк при показе, а nSymbPerRow</span> -<span lang="ru"> количество символов 
	в каждой строке.</span></span></span></td>
  </tr>
</table>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"> <em>sViewName</em></font></td>
    <td width="71%" class="style11">
	<font face="Arial">Строковое выражение, определяющее идентификатор вида 
	просмотра<span style="LINE-HEIGHT: 115%; FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA" lang="RU">.</span></font></td>
  </tr>
</table>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"> <em>s<span lang="ru">View</span>Code<span lang="ru">Col</span></em></font></td>
    <td width="71%" class="style11">
	<span style="LINE-HEIGHT: 115%; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA" 
            lang="RU" class="style13">
	Строковое выражение, определяющее идентификатор колонки в виде просмотра.
	</span></td>
  </tr>
</table>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"> <em>s<span lang="ru">ViewCaptionCol</span></em></font></td>
    <td width="71%" class="style11">
	    <span lang="ru"><span class="style13">С</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">троковое 
	выражение, определяющее наименование-заголовок для колонки </span>
	<span style="LINE-HEIGHT: 115%; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU; mso-fareast-language: EN-US; mso-bidi-language: AR-SA" 
            lang="RU" class="style13">
	в виде просмотра.</span></td>
  </tr>
</table>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em>sParamName</em></font></td>
    <td width="71%" class="style11">
	<span style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">
	Строков</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">о</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">е 
	выражени</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">е</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">, 
	определяющ</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">е</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">е 
	идентификатор параметр</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">а</span></span><span lang="en-us"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">
	</span></span><font face="Arial">для подстановки в вид просмотра</font><span lang="en-us"><span style="FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU">.</span></span></td>
  </tr>
</table>

<table cellPadding="5" cols="2" frame="below" rules="rows" class="style9">
  <tr>
    <td class="style11" style="width: 1%">
	<img src="../../IMAGES/pubfield.gif" width="16" height="16" /></td>
    <td width="29%" class="style11">
<font face="Arial"><em>sParamValue</em></font></td>
    <td width="71%" class="style11">
	<span style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">
	Строков</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">о</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">е 
	выражени</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">е</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13"> 
	определяющ</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">е</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13">е 
	значени</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">е</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13"> 
	подставляем</span><span lang="hy"><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style13">ого</span></span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            lang="RU" class="style13"> 
	параметр</span><span 
            style="mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" 
            class="style14"><span lang="hy">а</span><span lang="en-us"> 
	.</span></span></td>
  </tr>
</table>

<p class="MsoNormal">&nbsp;</p>
<p class="label"><b><font face="Arial">Примечание</font></b></p>
<p class="label">
<font face="Arial"> <em>
<strong>DropDown<span lang="ru">&nbsp; </span> </strong><span lang="ru">имеет 
смысл использовать только для реквизитов&nbsp; типа&nbsp; </span></em>
<a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/Progr_Guide/HTM/ProgrGuide/Types/Folder().html">
Folder()</a>,
<a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/Progr_Guide/HTM/ProgrGuide/Types/FULLTREE().html">
FullTree()</a>,
    <a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/Progr_Guide/HTM/ProgrGuide/Types/Tree().html">
    Tree()</a> 
и
<a href="mk:@MSITStore:D:/DEFS/progr_guide.chm::/progr_guide/htm/ProgrGuide/Types/Ch().html">
C<span lang="ru">H</span>()</a>.<span lang="ru"> А также</span><span lang="hy">
</span><span lang="ru">желательно</span><span lang="hy">,</span><span lang="ru"> 
чтобы при использовании </span> <em>
<strong>&nbsp;DropDown<span lang="ru">&nbsp; </span> </strong><span lang="ru">
атрибут соответству</span></em></font><span style="FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" lang="RU">ющего 
реквизита принимал значение - </span><span lang="hy">
    <span style="FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU">
    <font face="Arial">
	<b>V</b></font>.</span></span></p>
<p class="label">
<span style="FONT-FAMILY: 'Arial','sans-serif'; FONT-SIZE: 12pt; mso-fareast-font-family: 'Times New Roman'; mso-ansi-language: RU" lang="RU">&nbsp;</span></p>

</body>

</html>