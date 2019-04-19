---
layout: page
title: "AsDoc/Control"
---


# Control հատկություն

[См. также](../Asdoc.md) Օրինակ [Применяется к](../Asdoc.md)

Վերադարձնում է միջուկում օգտագործված  քոնթրոլի հղումը։ Քոնթրոլը վերադարձվում է միայն, երբ փաստաթղթի պատուհանը հասանելի է և սխալ է առաջացնում հակառակ դեպքում։ 


## Շարահյուսություն

``` vb
object.Control(RekvName)
```
Բաղադրիչներն են՝ 

| Պարամետր | Նկարագրություն |
|--|--|
| object | Փաստաթուղթ օբյեկտի հղում։|
| RekvName |Դաշտի ներքին անուն։ |


Ներքևում բերված հատկությունները հասանելի են Control-ի միջոցով, փաստաթղթի դաշտերի տարբեր տիպերի համար։
Ниже приводятся свойства, доступные через Control, для различных типов реквизитов документа:

### [Folder()](../../Types/Folder().html)


| Հատկություններ | Նկարագրություն |
|--|--|
| AsType | Վերադարձնում կամ նշանակում է դաշտի ներքին տիպը։ Հատկության արժեքի տիպը՝ տող։ |
| Button | Վերադարձնում կամ նշանակում է արժեքի ցանկից ընտրության կոճակի առկայությունը ։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| Caption | Վերադարձնում կամ նշանակում է գլխագիրը։ Հատկության արժեքի տիպը՝ տող։  |
| Comment | Վերադարձնում է թղթապանակի ընտրված տարրի մեկնաբանությունը։ Հատկության արժեքի տիպը՝ տող։ |
| DlinaKey | Վերադարձնում է թղթապանակի տարրի բանալու երկարությունը։ Հատկության արժեքի տիպը՝ ամբողջ թիվ։ |
| Enabled |  Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| FolderID |Վերադարձնում է թղթապանակի ներքին անունը։ Հատկության արժեքի տիպը՝ տող։  |
| ISN | Վերադարձնում կամ նշանակում է թղթապանակի ընտրված տարրի ներքին նույնականացման համարը։ Հատկության արժեքի տիպը՝ ամբողջ թիվ։ |
| Key |  Վերադարձնում կամ նշանակում է ընտրված տարրի բանալու արժեքը։ Հատկության արժեքի տիպը՝ տող։ |
| ReadOnly | Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| ShowName | Վերադարձնում կամ նշանակում է ընտրված դաշտի արժեքի աջից մեկնաբանության ցուցադրման հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| Validate | Վերադարձնում է դաշտում արժեքի սխալ մուտքագրման հայտանիշը։ True-ի դեպքում ակտիվ կմնա այդ դաշտը, մինչ թույլատրելի արժեքի մուտքագրումը։ False-ի դեպքում քոնթրոլը տրվում է հաջորդ դաշտերին։ Հատկության արժեքի տիպը՝ տրամաբանական։  |


### [Tree()](../../Types/Tree().html),[FullTree()](../../Types/FULLTREE().html)


| Հատկություններ | Նկարագրություն |
|--|--|
| AsType | Վերադարձնում կամ նշանակում է դաշտի ներքին տիպը։ Հատկության արժեքի տիպը՝ տող։ |
| Button | Վերադարձնում կամ նշանակում է արժեքի ցանկից ընտրության կոճակի առկայությունը: Հատկության արժեքի տիպը՝ տրամաբանական։  |
| Code | Վերադարձնում կամ նշանակում է ծառի մեջ տարրի բանալին։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| Comment | Վերադարձնում է ծառի ընտրված տարրի մեկնաբանությունը։  Հատկության արժեքի տիպը՝ տող։ |
| Enabled |  Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| ISN | Վերադարձնում կամ նշանակում է ծառի ընտրված տարրի ներքին նույնականացման համարը։ Հատկության արժեքի տիպը՝ ամբողջ թիվ։ |
| Path | Ծառի մեջ վերադարձնում է տարրի ճանապարհը, սկսելով ծառի արմատից։ Հատկության արժեքի տիպը՝ տող։  |
| ReadOnly |  Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական |
| ShowName | Վերադարձնում կամ նշանակում է ընտրված դաշտի արժեքի աջից մեկնաբանության ցուցադրման հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| TreeID | Վերադարձնում է ծառի ներքին անունը։ Հատկության արժեքի տիպը՝ տող։ |
| Validate | Վերադարձնում է դաշտում արժեքի սխալ մուտքագրման հայտանիշը։ True-ի դեպքում ակտիվ կմնա այդ դաշտը, մինչ թույլատրելի արժեքի մուտքագրումը։ False-ի դեպքում քոնթրոլը տրվում է հաջորդ դաշտերին։ Հատկության արժեքի տիպը՝ տրամաբանական։ |


### [AmAcc()](../../Types/Amacc.html)


| Հատկություններ | Նկարագրություն |
|--|--|
| Acc | Վերադարձնում է ներքին հաշվի համարը։ Հատկության արժեքի տիպը՝ տող։  |
| AccName | Վերադարձնում է հաշվի անվանումը։ Հատկության արժեքի տիպը՝ տող։ |
| AsType | Վերադարձնում կամ նշանակում է դաշտի ներքին տիպը։ Հատկության արժեքի տիպը՝ տող։  |
| Bank | Վերադարձնում է բանկի կոդը։ Հատկության արժեքի տիպը՝ տող։ |
| BankName | Վերադարձնում է բանկի անվանումը։ |
| Button | Վերադարձնում կամ նշանակում է ընտրելու կոճակի տեսանելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| Enabled |  Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| FullAcc | Վերադարձնում կամ նշանակում է հաշվի ամբողջական համարը  (բանկի կոդ/հաշիվ)։ Հատկության արժեքի տիպը՝ տող։  |
| ReadOnly | Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| Validate | Վերադարձնում է դաշտում արժեքի սխալ մուտքագրման հայտանիշը։ True-ի դեպքում ակտիվ կմնա այդ դաշտը, մինչ թույլատրելի արժեքի մուտքագրումը։ False-ի դեպքում քոնթրոլը տրվում է հաջորդ դաշտերին։ Հատկության արժեքի տիպը՝ տրամաբանական։  |


[NumPair()](../../Types/NumPair().html)


| Հատկություններ | Նկարագրություն |
|--|--|
| AsType | Վերադարձնում կամ նշանակում է դաշտի ներքին տիպը։ Հատկության արժեքի տիպը՝ տող։ |
| Comment | Վերադարձնում կամ նշանակում է դաշտի մեկնաբանությունը։ Մեկնաբանությունը գտնվում է դաշտի աջ կողմում։ Առավելագույն երկարությունը 10 նիշ է։ Հատկության արժեքի տիպը՝ տող։ |
| Enabled | Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| LabelCaption | Վերադարձնում կամ նշանակում է զույգ դաշտերի միջև գտնվող  բաժանարար տեքստը։ Նրա երկարությունը անսահմանափակ է։ Հատկության արժեքի տիպը՝ տող։ |
| Number1 | Վերադարձնում կամ նշանակում է առաջին թվի արժեքը։ Հատկության արժեքի տիպը՝ Currency։  |
| Number2 | Վերադարձնում կամ նշանակում է երկրորդ թվի արժեքը։ Հատկության արժեքի տիպը՝ Currency։ |
| ReadOnly |Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| Validate |Վերադարձնում է դաշտում արժեքի սխալ մուտքագրման հայտանիշը։ True-ի դեպքում ակտիվ կմնա այդ դաշտը, մինչ թույլատրելի արժեքի մուտքագրումը։ False-ի դեպքում քոնթրոլը տրվում է հաջորդ դաշտերին։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| Value | Վերադարձնում կամ նշանակում է դաշտի արժեքը տողային, օրինակ՝ "485/1": Հատկության արժեքի տիպը՝ տող։ |
| ZeroNumber1 | Վերադարձնում կամ նշանակում է առաջին թվի մեջ զրո արժեք մուտքագրելու թույլտվությունը։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
| ZeroNumber2 | Վերադարձնում կամ նշանակում է երկրորդ թվի մեջ զրո արժեք մուտքագրելու թույլտվությունը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |


Image


| Հատկություններ | Նկարագրություն |
|--|--|
| Enabled |  Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։|
| Picture | Վերադարձնում կամ նշանակում է դաշտի արժեքը բայթ զանգվածի տեսքով։ Հատկության արժեքի տիպը՝ Variant։ |
| ReadOnly |Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |


[CH()](../../Types/Ch().html)


| Հատկություններ | Նկարագրություն |
|--|--|
| AsType | Վերադարձնում կամ նշանակում է դաշտի ներքին տիպը։ Հատկության արժեքի տիպը՝ տող։ |
| Code | Վերադարձնում կամ նշանակում է մեկնաբանությունների ծառի տարրի կոդը։ Հատկության արժեքի տիպը՝ տող։ |
| Comment | Մեկնաբանությունների ծառից վերադարձնում կամ նշանակում է ընտրված տարրի համար մեկնաբանություն։ Հատկության արժեքի տիպը՝ տող։ |
| DlinaKey |Վերադարձնում է մեկնաբանությունների ծառի տարրի բանալու երկարությունը։ Հատկության արժեքի տիպը՝ ամբողջ թիվ։ |
| Enabled | Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։ |
| Label | Վերադարձնում կամ նշանակում է մեկնաբանությունների ծառից ընտրված տարրի Label-ը։ Հատկության արժեքի տիպը՝ տող։ |
| ReadOnly | Վերադարձնում կամ նշանակում է դաշտի խմբագրելի լինելու հայտանիշը։ Հատկության արժեքի տիպը՝ տրամաբանական։|
| TreeID | Վերադարձնում է ծառի ներքին անունը, ընտրված տարրի համար։ Հատկության արժեքի տիպը՝ տող։ |
| Validate |Վերադարձնում է դաշտում արժեքի սխալ մուտքագրման հայտանիշը։ True-ի դեպքում ակտիվ կմնա այդ դաշտը, մինչ թույլատրելի արժեքի մուտքագրումը։ False-ի դեպքում քոնթրոլը տրվում է հաջորդ դաշտերին։ Հատկության արժեքի տիպը՝ տրամաբանական։  |
