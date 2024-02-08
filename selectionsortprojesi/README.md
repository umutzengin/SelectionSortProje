# PROJE 1
[22,27,16,2,18,6] -> insertion Sort

## Soru 1
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
[22,27,16,2,18,6] 22 ve 27 sıralı,
[22,16,27,2,18,6] 16 ve 27 yer değiştirir,
[16,22,27,2,18,6] 16 ve 22 yer değiştirir,
[16,22,2,27,18,6] 2 ve 27 yer değiştirir,
[16,2,22,27,18,6] 2 ve 22 yer değiştirir,
[2,16,22,27,18,6] 2 ve 16 yer değiştirir,
[2,16,22,18,27,6] 18 ve 27 yer değiştirir,
[2,16,18,22,27,6] 18 ve 22 yer değiştirir,
[2,16,18,22,6,27] 6 ve 27 yer değiştirir,
[2,16,18,6,22,27] 6 ve 22 yer değiştirir,
[2,16,6,18,22,27] 6 ve 18 yer değiştirir,
[2,6,16,18,22,27] 6 ve 16 yer değiştirir.
```
## Soru 2 
Big-O gösterimini yazınız.

| Best | Average | Worst |
| :---: | :---: | :---: |
| O(n) | O(n^2) | O(n^2) |

## Soru 3
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

* Average case: Aradığımız sayının ortada olması
* Worst case: Aradığımız sayının sonda olması
* Best case: Aradığımız sayının dizinin en başında olması.

Cevap: Average Case
## Soru 4
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
```
1.adım [2,3,5,8,7,9,4,15,6]
2.adım [2,3,4,8,7,9,5,15,6]
3.adım [2,3,4,5,7,9,8,15,6]
4.adım [2,3,4,5,6,9,8,15,7]
```