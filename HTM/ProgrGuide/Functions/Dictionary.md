---
layout: page
title: "Dictionary օբյեկտ"
---


# Dictionary օբյեկտ


Հատկություններն են՝

| Հատկություն | Շարահյուսություն | Նկարագրություն |
|--|--|--|
| CompareMode | object.**CompareMode**[ = compare] | վերադարձնում կամ նշանակում է բանալին համեմատելու ռեժիմը։ 0 արժեքի դեպքում՝ երկուական համեմատություն, 1-ի դեպքում տեքստային ։возвращает/устанавливает режим сравнения строковых ключей объекта Dictionary. При значении 0 производится бинарное сравнение, а при 1 - текстовое сравнение. |
| Count | object<b>.Count</b> | Վերադարձնում է տարրերի քանակը։ возвращает количество элементов в коллекции объекта Dictionary. |
| Item | object.<b>Item(</b>key<b>)</b> [= newitem] | Վերադարձնում կամ նշանակում է հավաքածուի տարրի արժեքը ընտրված բանալիով։  возвращает/устанавливает значение элемента коллекции с указанным ключом. |
| Key | object<b>.Key(</b>key<b>)</b> = newkey | Հավաքածուի տարրի համար նշանակում է բանալու արժեքը։ устанавливает значение ключа для элемента коллекции. |


Մեթոդներն են՝


| Մեթոդ | Շարահյուսություն | Նկարագրություն |
|--|--|--|
| Add | <i>object</i><b>.Add</b> <i>key</i>, <i> 	item</i> | Հավաքածուի մեջ ավելացնում է նոր տարր ընտրված բանալիով և արժեքով։ добавляет новый элемент с указанным ключом и значением в коллекцию. |
| Exists | <i>object</i><b>.Exists(</b><i>key</i><b>)</b> | Վերադարձնում է  **True**, եթե ընտրված բանալին առկա է հավաքածուի մեջ, հակառակ դեպքում՝ **False**։ Возвращает **True**, если указанный ключ существует в коллекции объекта Dictionary, **False** в противном случае. |
| Items | <i>object</i><b>.Items</b> |Վերադարձնում է հավաքածուի տարրերը պարունակող մասիվը։ Возвращает массив, содержащий все элементы коллекции объекта Dictionary. |
| Keys | <i>object</i><b>.Keys</b> | Վերադարձնում է հավաքածուի բանալիները պարունակող մասիվը։ Возвращает массив, содержащий все ключи коллекции объекта Dictionary. |
| Remove | object</i><b>.Remove(</b><i>key</i><b>)</b> | Հավաքածուից ջնձում է ընտրված արժեքով տարրը։ Удаляет из коллекции элемент с указанным ключевым значением. |
| RemoveAll |object. ***RemoveAll*** | Հավաքածուից ջնձում է բոլոր տարրերը։ Удаляет из коллекции все элементы |

