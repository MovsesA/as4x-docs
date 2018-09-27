﻿<html>
<head>
<title>Системные параметры</title>
</head>

<body>

<p><font face="Arial"><big>Системные параметры</big></font></p>

<p><font face="Arial">Т.к. эти константы объявлены в системном ядре, 
то нет необходимости в их дополнительном объявлении. Их можно использовать везде 
в скриптах, взамен их значений.</font></p>

<table border="1">
  <tr>
    <td width="20%"><font size="3" face="Arial"><strong>Идентификатор 
	параметра</strong></font></td>
    <td width="20%"><font size="3" face="Arial"><strong>Тип</strong></font></td>
    <td width="60%"><font size="3" face="Arial"><strong>Назначение</strong></font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>OPEREND</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">конец операционного периода</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>OPERSTART</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">начало операционного периода</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>REPEND</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">конец отчетного периода</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>REPSTART</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">начало отчетного периода</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>CHIEFACCTNT</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">ФИО главного бухгалтера</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>CODBANK</strong></font></td>
    <td width="20%"><font face="Arial">C(5)</font></td>
    <td width="60%"><font face="Arial">Код банка</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>ECHIEFACCTNT</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">ФИО главного бухгалтера на 
	иностранном языке</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>EMANAGERNAME</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">ФИО руководителя организации на 
	иностранном языке</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>EMANAGERPOST</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">Должность руководителя 
	организации на иностранном языке</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>MANAGERNAME</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">ФИО руководителя организации</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>MANAGERPOST</strong></font></td>
    <td width="20%"><font face="Arial">C(32)</font></td>
    <td width="60%"><font face="Arial">Должность руководителя 
	организации</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>STARTDATE</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">Дата начала эксплуатации 
	системы</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>ENDDATE</strong></font></td>
    <td width="20%"><font face="Arial">DATE</font></td>
    <td width="60%"><font face="Arial">Дата хранения текущих остатков</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>ACCLIMIT</strong></font></td>
    <td width="20%"><font face="Arial">Boolean</font></td>
    <td width="60%"><font face="Arial">Проверять граничные значения 
	остатка счета</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>BANKS</strong></font></td>
    <td width="20%"><font face="Arial">C(20)</font></td>
    <td width="60%"><font face="Arial">Справочник банков</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>INSCOMPLETE</strong></font></td>
    <td width="20%"><font face="Arial">Boolean</font></td>
    <td width="60%"><font face="Arial">Завершение этапа внедрения 
	системы</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>LANG </strong></font></td>
    <td width="20%"><font face="Arial">N(1,0)</font></td>
    <td width="60%"><font face="Arial">Рабочий язык системы</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>ROUNDTRANS</strong></font></td>
    <td width="20%"><font face="Arial">N(1,0)</font></td>
    <td width="60%"><font face="Arial">Степень округления операций</font></td>
  </tr>
  <tr>
    <td width="20%"><font face="Arial"><strong>SYSISN </strong></font></td>
    <td width="20%"><font face="Arial">NP(10,0)</font></td>
    <td width="60%"><font face="Arial">Внутрисистемный код последнего&nbsp; 
	документа</font></td>
  </tr>
</table>

<blockquote>
</blockquote>

<p><font face="Arial"><br>
</font></p>
</body>
</html>