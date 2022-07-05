# Patika Merge sort

[www.patika.dev](https://patika.dev)

-------------------------------------------------------------------
[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

|Adımlar |Merge Sort |
|:--:|:--:|
| Sol ve sağa böl   |[16,21,11,8,12,22]|
| adım 2                                              |[16,21,11] - [8,12,22]|
| adım 3                                                |[16] - [21,11] - [8] - [12,22]|
| adım 4                                                |[16] - [21] - [11] - [8] - [12] - [22]|
| sıralı olarak birleştir         |[16] - [21,11] - [8] - [12,22]|
| adım 2                                                  |[11,16,21] - [8,12,22]|
| adım 3                                                |[8,11,12,16,21,22]|

2. Big-O gösterimini yazınız.

> O(nlogn)
***
