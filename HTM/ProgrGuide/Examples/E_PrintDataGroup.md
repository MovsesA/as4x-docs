﻿<html>
<head>
<title>PrintDataGroup</title>
    <style type="text/css">
        .style1
        {
            font-family: Arial;
            color: #006600;
            font-weight: 700;
        }
        .style2
        {
            font-family: Arial;
        }
        .style3
        {
            font-family: Arial;
            color: #000000;
        }
        .style4
        {
            color: #000000;
        }
        .style9
        {
            font-family: Arial;
            color: #006600;
        }
    </style>
</head>

<body>

<p><font size="3" face="Arial"><strong>Пример использования PrintDataGroup в 
    описании документа</strong></font></p>
    <span class="style1">
    <br />
    &#39; Definition документа</span><p>
        <span class="style2">Name = Products</span><br class="style2" />
        <span class="style2">Caption = &quot;Продукты&quot;</span><br class="style2" />
        <span class="style2">Ecaption = &quot;Products&quot;</span><br class="style2" />
        <br class="style2" />
        <span class="style2">Page {Caption = &quot;Продукты&quot;; Ecaption =&quot;Products&quot;</span><br 
            class="style2" />
        <span class="style2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Rekvizit {Name = Code;&nbsp;&nbsp; Caption = &quot;Код 
        продукта&quot;;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ECaption = &quot;Products 
        code&quot;; Type = Folder(Item, 
        12);};<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Rekvizit {Name = 
        Name;&nbsp; Caption = &quot;Название продукта&quot;;&nbsp; ECaption = &quot;Products name&quot;; 
        Type = C(50);};</span><br class="style2" />
        <span class="style2">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; };</span></p>
    <p>
        <font size="3" face="Arial"><strong>PrintDataGroup </strong></font>
        <span class="style2">{ Name = &quot;<strong>01</strong>&quot;; Caption = &quot;При печати 
        вывести коды продуктов&quot; }; </span>
        <br class="style2" />
        <font size="3" face="Arial"><strong>PrintDataGroup </strong></font>
        <span class="style2">{ Name = &quot;<strong>02</strong>&quot;; Caption = &quot;При печати 
        вывести названия продуктов&quot;; };</span></p>
    <p>
        <br />
        <span class="style1">&#39; Script документа</span></p>
    <p>
        <span class="style3">Public Function TemplateSubstitution(ByVal dctModeDict As Dictionary) As 
        TemplateSubstitution
        </span>
        <br class="style3" />
        <span class="style3">Dim Result As TemplateSubstitution</span><span 
            class="style2"><br class="style4" />
        </span>
        <span class="style3">Dim bPrint<span class="style2">Products</span>Code As Boolean
        <br />
        Dim bPrint<span class="style2">Products</span>Name As Boolean
        <br />
        <br />
&nbsp;&nbsp; <strong>bPrint</strong><span class="style2"><strong>Products</strong></span><strong>Code</strong>&nbsp; 
        = dctModeDict(&quot;<strong>01</strong>&quot;)
        <br />
&nbsp;&nbsp; <strong>bPrint</strong><span class="style2"><strong>Products</strong></span><strong>Name</strong> 
        = dctModeDict(&quot;<strong>02</strong>&quot;)</span></p>
    <p>
        <span class="style3">&nbsp;&nbsp;&nbsp; With Result</span><br class="style3" />
        <span class="style3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; If <strong>
        bPrint</strong><span class="style2"><strong>Products</strong></span><strong>Code</strong>&nbsp; 
        Then</span><br class="style3" />
        <span class="style3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
        .Add &quot;001&quot;, Doc(&quot;Code&quot;)</span><br class="style3" />
        <span class="style3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ElseIf
        </span><span class="style9"><span class="style3"><strong>bPrint</strong><span class="style2"><strong>Products</strong></span><strong>Name</strong> 
        Then</span></span><span class="style2"><br class="style4" />
        </span><span class="style9"><span class="style3">&nbsp;&nbsp;&nbsp;
        </span>
        </span><span class="style3">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; .Add 
        &quot;001&quot;, Doc(&quot;<span class="style2">Name</span>&quot;)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; End If<br />
        &nbsp;&nbsp; End With<br />
&nbsp;&nbsp; Set TemplateSubstitution = Result</span><span class="style2"><br 
            class="style4" />
        </span>
        <span class="style3">End Function</span></p>
    <p>
        &nbsp;</p>
</body>
</html>