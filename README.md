# Veri Yapilari ve Algoritmalar
## Proje 1
### [22,27,16,2,18,6] -> Insertion Sort
#### Soru1: Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- 1.adım: 2 27 16 22 18 6 (en küçük sayıyı bul ve en baştaki ile yer değiştir.)
- 2.adım: 2 6 16 22 18 27 (ikinci en küçük elemanı bul ve yer değiştir.)
- 3.adım: 2 6 16 18 22 27 (16 diğerlerinden küçük old. için değiştirilmez. 4. sayıya geçilir.)
#### Soru2: Big-O gösterimini yazınız.
BigO: O(n^2)
#### Soru3: Time Complexity:
- Average case:  O(36)  (Aradığımız sayının ortada olması)
- Worst case:  O(36)  (Aradığımız sayının sonda olması)
- Best case:  O(6)  (Aradığımız sayının dizinin en başında olması)
#### Soru4: Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Average case
#### Soru5: [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
- 2,3,5,8,7,9,4,15,6
- 2,3,4,8,7,9,5,15,6
- 2,3,4,5,7,9,8,15,6
- 2,3,4,5,6,9,8,15,7
## Proje 2
### [16,21,11,8,12,22] -> Merge Sort
#### Soru1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- 16 21 11 8 12 22   (Bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyoruz.)
-           [16,21,11]                                [8,12,22]
-      [16]           [21,11]                        [8]       [12,22] 
-       [16]    [21]   [11]                        [8]    [12]   [22]   
-      [16]           [11,21]                        [8]       [12,22]
-             [11,16,21]                                [8,12,22]
-                                [8,11,12,16,21,22]
#### Soru2: Big-O gösterimini yazınız.
BigO: O(nlogn)
## Proje 3
### Soru1: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root 6 seçilmiştir.

![Adsız](https://user-images.githubusercontent.com/80748350/142743576-e4581cb4-a11f-4dee-b32a-630df49798c7.png)











