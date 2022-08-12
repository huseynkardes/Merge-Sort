# MERGE SORT

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

|Adımlar|Bölünmüş ve Birleştirilmiş Şema|
|:--:|:--:|
| Seçili diziyi sol ve sağ alt dizilere böl   |[16,21,11,8,12,22]|
| Bolum 2                                                |[16,21,11] - [8,12,22]|
| Bolum 3                                                |[16] - [21,11] - [8] - [12,22]|
| Bolum 4                                                |[16] - [21] - [11] - [8] - [12] - [22]|
| Sıralı bir şekilde aynı şekilde birleştirin          |[16] - [21,11] - [8] - [12,22]|
| Birlesim 2                                                 |[11,16,21] - [8,12,22]|
| Birlesim 3                                                 |[8,11,12,16,21,22]|

2. Big-O gösterimini yazınız

> O(nlogn)
