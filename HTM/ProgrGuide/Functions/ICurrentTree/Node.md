---
layout: page
title: "ICurrentTree/Node"
---


# Node հատկություն

[См. также](../ICurrentTree.md) Օրինակ [Применяется к](../ICurrentTree.md)

Վերադարձնում է պահանջվող հանգույցը հատուկ բազմության տեսքով։

Կարդալու հատկություն։


## Շարահյուսություն

``` vb
object.Node(index).Item(ItemKey)
```
Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object |  Ընթացիկ ծառի հղում։|
| index | հանգույցի ինդեքսը ծառի մեջ, 0-ից մինչև [NodesCount](NodesCount.html)-1. |
| ItemKey | Բանալին արժեքների բազմության մեջ։ |


## Արժեքներ


| Արժեք | Նկարագրություն |
|--|--|
| CODE | Ընտրված հանգույցի կոդը:  |
| NAME | Ընտրված հանգույցի անվանումը։  |
| ENAME | Ընտրված հանգույցի օտար լեզվով անվանումը։  |
| ISN | Ընտրված հանգույցի ներքին նույնականացման համարը։ |
| PARENTCODE | Ընտրված հանգույցի անմիջական ծնողի կոդը։ Միամակարդակ ծառերի դեպքում դատարկ է։ |
| PARENTNAME | Ընտրված հանգույցի անմիջական ծնողի անվանումը։ |
| PARENTISN | Ընտրված հանգույցի անմիջական ծնողի ներքին նույնականացման համարը։|

