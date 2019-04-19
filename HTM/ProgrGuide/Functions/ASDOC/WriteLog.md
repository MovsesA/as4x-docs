---
layout: page
title: "AsDoc/WriteLog"
---
# WriteLog մեթոդ

[См. также](../Asdoc.md) Օրինակ [Применяется к](../Asdoc.md)


Ավելացնում է նոր գրառում փաստաթղթի պատմության մեջ։ 

Փաստաթղթի կյանքի ընթացքում մի շարք գործողություններ գրանցվում են պատմության մեջ ավտոմատ կերպով, ինչպիսին է փաստաթղթի ստեղծումը կամ խմբագրումը։ Այս մեթոդի միջոցով հնարավոր է ավելացնել լրացուցիչ տողեր։ Այս ֆունկցիայով տող ավելացնելուց [DOCLOG](../../Database/DocLog.html)
աղյուսակում ավելանում է գրառում  "M" կոդով։ 

Եթե այս մեթոդը կանչում ենք Action իրադարձոթյան մշակիչի մեջ, ապա  գրանցումները տվյալների պահոցում կատարվում են մշակիչի ավարտից հետո, իսկ այլ դեպքերում գրանցումը կատարվում է անմիջապես։ 


## Շարահյուսություն

``` vb
object.WriteLog ( sMsg, [nDCRID], [bDCRIDIsISN] )
```

Բաղադրիչներն են՝


| Պարամետր | Նկարագրություն |
|--|--|
| object | Փաստաթուղթ օբյեկտի հղում։ |
| sMsg | Փաստաթղթի պատմությունում ավելացվող հաղորդագրություն։  |
| nDCRID | Փոփոխման հայտի  համարը(DocChangeRequest) կամ հիմքային փաստաթղթի ներքին նույնականացման համար։ |
| bDCRIDIsISN | True արժեքը ցույց է տալիս, որ `nDCRID`-ը փոփոխման հայտի համար է,  False արժեքը՝ հիմքային փաստաթղթի ներքին նույնականացման համար։ |

## Նկատառումներ
Փաստաթղթի պատմությունում ավելացնելով գրառումներ, համակարգը ավտոմատ կերպով հիշում է փաստաթղթի ընթացիկ վիճակը։ 
 