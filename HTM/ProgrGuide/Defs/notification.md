﻿<html>
<head>
<title>Notification Definition</title>
</head>

<body>

<p><strong><font size="4" face="Arial">Описание оповещения</font></strong></p>

<p class="label"><font face="Arial">Описывается оповещение. Оповещение 
используется для отправки сообщения одним юзером другим. Можно отправить также <a href="doc.html">
документ</a>.</font></p>

<p class="label">&nbsp;</p>

<p class="label"><font face="Arial"><b>Синтаксис</b></font></p>

<p><font face="Arial"><strong>NOTIFICATION</strong>{<strong>Name</strong>=<em>sNotificationName</em>;&nbsp;
<strong><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Caption</strong>=<em>sNotificationCaption</em>;<br>
<strong>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
Color </strong>=
<em>nNotificationColor</em>;<br>
<strong>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
TTL </strong>=
<em>nNotificationTTL</em>;<br>
<strong>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
AWP </strong>=
<em>sNotificationAWP</em>;<br>
<strong>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
TypeAWP </strong>=
<em>sNotificationTypeAWP</em>;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; };<br>
</font></p>

<p><font face="Arial">Синтаксис описания документа состоит из 
следующих частей:</font></p>

<table border="1" cellPadding="5" cols="2" frame="below" rules="rows">
<TBODY>
  <tr vAlign="top">
    <td class="label" width="29%"><font face="Arial"><b>Параметр</b></font></td>
    <td class="label" width="71%"><font face="Arial"><strong>Описание</strong></font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sNotificationName</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее идентификатор оповощения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sNotificationCaption</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее заголовок оповещения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>nNotificationColor</em></font></td>
    <td width="71%"><font face="Arial">числовое выражение, 
	определяющее цвет оповещения.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>nNotificationTTL</em></font></td>
    <td width="71%"><font face="Arial">числовое выражение, 
	определяющее время жизни сообщения в минутах. По умолчанию, сообщение 
	действительно в течении 15 минут.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sNotificationAWP</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее список наименований АРМ-ов, которым посылается оповещение. В 
	списке можно перечеслять любое количество АРМ-ов через запятую. Например - 
	&quot;ADMIN, Account, Chairman&quot;.</font></td>
  </tr>
  <tr>
    <td width="29%"><font face="Arial"><em>sNotificationTypeAWP</em></font></td>
    <td width="71%"><font face="Arial">строковое выражение, 
	определяющее список типов АРМ-ов получателей сообщения. В списке можно 
	перечеслять любое количество типов АРМ-ов через запятую. Например - 
	&quot;+TYPE3,+TYPE5,+TYPE6&quot;.</font></td>
  </tr>
</TBODY>
</table>

<p class="label"><a href="../Defs.html"><font face="Arial">См. также</font></a></p>
</body>
</html>