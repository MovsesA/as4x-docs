---
layout: page
title: "AsDoc/FixedValue"
---


# FixedValue հատկություն

[См. также](../Asdoc.md) Օրինակ [Применяется к](../Asdoc.md)

Վերադարձնում կամ նշանակում է դաշտի արժեքի ամրագրված լինելը։ 


## Շարահյուսություն

``` vb
object.FixedValue(rekvName)[=value]
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object | Փաստաթուղթ օբյեկտի հղում։ |
| rekvName | Դաշտի ներքին անուն։|
| value | Նոր արժեք։ |

## Նկատառումներ
Դաշտի արժեքը ամրագրելուց հետո այն այլևս ենթակա չի փոփոխման, ո՛չ ծրագրում, ո՛չ սկրիպտում։ Եթե փորձենք փոխել միջուկը առաջացնում է սխալ։ Ծրագրում այս դաշտը անցնում է միայն կարդալու ռեժիմին։ 

