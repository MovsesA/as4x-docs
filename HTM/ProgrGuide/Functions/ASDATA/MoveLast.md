---
layout: page
title: "AsData/MoveLast"
---


# MoveLast մեթոդ

[См. также](../Asdata.md) [Օրինակ](../../Examples/E_AsData.html) [Применяется к](../Asdata.md)


Նշորդը տեղափոխում է բաց տվյալների աղբյուրի վերջին տողի վրա։ 

Թույլատրվում է կանչել, եթե
* Տվյալների աղբյուրը հիմնված է SQL հարցման վրա և [բացվել է](OpenCursor.html) հետևյալ եղանակներից մեկով՝ [ASOpenStatic, ASOpenKeyset, ASOpenDynamic](../../Constants/const_opencursor_cursortype.html)։ 
* Տվյալների աղբյուրը հիմնված է մասիվի վրա։


## Շարահյուսություն

``` vb
object.MoveLast
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object| Տվյալների աղբյուրի հղում։ |
