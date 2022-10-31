# Merge-Sort-Project-for-Patika.dev

[patika.dev](https://www.patika.dev/tr)

## [16,21,11,8,12,22] -> Merge Sort

## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

            Orijinal Dizim                                                                    Sıralanmış Dizim
           16,21,11,8,12,22                                                                    8,11,12,16,22
         16,21,11   |      8,12,22                                                             |8,11,12,16,22|
     16 |  21,11         8 |  12,22                                                         |11,16,21|  |8,12,22|
    16  |  21  |  11   8   |  12 | 22                                                     16  | 21 | 11 | 8 | 12 | 22 
    Yukarıdan aşağıya doğru parçalanıyor.                                                Aşağıdan yukarı doğru birleştiriliyor.
    
## Big O Gösterimi = O(nlogn)
