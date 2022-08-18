#Binary Search Tree
Binary Search Tree: farklı elemanların diziliş kuralıdır. En üstte bulunan değere root denir.
* elimizdeki değer root değerinden küçükse; root soluna,
* büyükse; root sağına yazılır.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


* ilk değer 7 root olarak seçilir.
* sıradaki değer 5; 7'den küçük olduğu için sola yazılır.

|   | 7 |
| - | - |
| 5 |   |


* 1; 7'den ve 5'ten küçük olduğu için sola yazılır.

|   |   | 7 |
| - | - | - |
|   | 5 |   |
| 1 |   |   |


* 8; 7'den büyüktür. Sağa yazılır.

|   |   | 7 |   |
| - | - | - | - |
|   | 5 |   | 8 |
| 1 |   |   |   |


* 3; 7 ve 5'ten küçük olduğu için bunların soluna, 1 den büyük olduğu için 1'in sağına yazılır.

|   |   |   | 7 |   |
| - | - | - | - | - |
|   |   | 5 |   | 8 |
|   | 1 |   |   |   |
|   |   | 3 |   |   |


* 6; 7'nin solu, 5'in sağına

|   |   |   |   | 7 |   |   |
| - | - | - | - | - | - | - |
|   |   | 5 |   |   |   | 8 |
|   | 1 |   | 6 |   |   |   |
|   |   | 3 |   |   |   |   |


* 0; en sola

|   |   |   |   | 7 |   |   |
| - | - | - | - | - | - | - |
|   |   | 5 |   |   |   | 8 |
|   | 1 |   | 6 |   |   |   |
| 0 |   | 3 |   |   |   |   |


* 9; en sağa

|   |   |   |   | 7 |   |   |   |
| - | - | - | - | - | - | - | - |
|   |   | 5 |   |   |   | 8 |   |
|   | 1 |   | 6 |   |   |   | 9 |
| 0 |   | 3 |   |   |   |   |   |


* 4; 7 ve 5'in solu, 3'ün sağına

|   |   |   |   | 7 |   |   |   |
| - | - | - | - | - | - | - | - |
|   |   | 5 |   |   |   | 8 |   |
|   | 1 |   | 6 |   |   |   | 9 |
| 0 |   | 3 |   |   |   |   |   |
|   |   |   | 4 |   |   |   |   |


* 2; 7, 5, 3'ün soluna yazılır.

|   |   |   |   | 7 |   |   |   |
| - | - | - | - | - | - | - | - |
|   |   | 5 |   |   |   | 8 |   |
|   | 1 |   | 6 |   |   |   | 9 |
| 0 |   | 3 |   |   |   |   |   |
|   | 2 |   | 4 |   |   |   |   |
