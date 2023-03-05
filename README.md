# Merge-Sort

* İlk olarak her sayı tekbaşına kalana kadar dizi parçalanır.
* Sonra en soldaki iki sayı karşılaştırır ve 16 ve 21 birleştirilir. (küçükten büyüğe şeklinde 16,21)
* En sağdaki iki sayıda aynı şekilde bir işlem gerçekleşir.(12,22)
* 16,21 grubu 11 ile birleşir. 16>11 olduğu  için sıralama 11,16,21 olur.
* 12,22 grubu 8 ile birleşir. 12>8 oduğu için sıralama 8,12,22 olur.
* 11,16,21 ve 8,12,22 grubu birleşir; 
1. 11>8, 8,11,16,21. 
2. 11<12, 16>12, 8,11,12,16,21.
3. 16<22, 21<22, 8,11,12,16,21,22.

-------

* [16,21,11,8,12,22]
* [16,21,11]  [8,12,22]
* [16,21]  [11]  [8]  [12,22]
* [16]  [21]  [11]  [8]  [12]  [22]
* [16,21]  [11]  [8]  [12,22]
* [11,16,21]  [8,12,22]
* [8,11,12,16,21,22]
