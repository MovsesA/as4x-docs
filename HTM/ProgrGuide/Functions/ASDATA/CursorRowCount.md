---
layout: page
title: "AsData/CursorRowCount"
---


# CursorRowCount հատկություն

[См. также](../Asdata.md) Օրինակ [Применяется к](../Asdata.md)


Վերադարձնում է տողերի քանակը բաց տվյալների աղբյուրի մեջ։  
Ճիշտ տողերի քանակ վերադարձնում է, եթե 
* Տվյալների աղբյուրը հիմնված է SQL հարցման վրա և [բացվել է](OpenCursor.html) տողերի քանակ ցույց տվող եղանակով՝ [ASOpenStatic, ASOpenKeyset, ASOpenDynamic](../../Constants/const_opencursor_cursortype.html)։ 
* Տվյալների աղբյուրը հիմնված է մասիվի վրա։

Մյուս դեպքերում հատկությունը վերադարձնում է -1 արժեք։ 

## Շարահյուսություն

``` vb
object.CursorRowCount
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object| Տվյալների աղբյուրի հղում։  |


## Տվյալի տիպ

Ամբողջ թիվ
