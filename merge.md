## Soru

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Cevap

Merge Sort---

[16,21,11] [8,12,22]
[16] [21,11] [8,12] [22]
[16] [21] [11] [8] [12] [22]
[16] [11,21] [8,12] [22]
[11,16,21] [8,12,22]
[8,11,12,16,21,22]

## Big-O Gösterimi---
Merge Sort un zaman karmaşıklığı: O(nlogn)