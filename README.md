## [Patika.dev](https://www.patika.dev/tr) Veri Yapıları ve Algoritmalar Binary Search Tree Projesi

## Proje 3

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
#### Örnek: root x'dir. root'un sağında y bulunur. Solunda z bulunur vb.

```
Root 7'dir. 

5 sayısı 7'den küçük olduğu için root'un (7) solunda 5 bulunur.

    7
   /
  5
---------------------------------------------------------------
 1 sayısı 5'ten küçük olduğu için 5'in solunda bulunur.
 
      7
     /
    5
   /
  1
 --------------------------------------------------------------
  8 sayısı 7'den büyük olduğu için 7'nin sağından bulunur.
  
      7
     / \
    5   8
   /
  1
 -------------------------------------------------------------- 
  3 sayısı 1'den büyük olduğu için 3'ün sağında bulunur.
  
         7
       / \
      5   8
     /
    1
     \
      3
--------------------------------------------------------------     
6 sayısı 5'ten büyük olduğu için 5'in sağında bulunur.

        7
       / \
      5   8
     / \
    1   6
     \
      3
--------------------------------------------------------------
0 sayısı 1'den küçük olduğu için 1'in solunda bulunur.

        7
       / \
      5   8
     / \
    1   6
   / \
  0   3
-------------------------------------------------------------- 
9 sayısı 8'den büyük olduğu için 8'in sağında bulunur.

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
--------------------------------------------------------------
4 sayısı 3'ten büyük olduğu için 3'in sağında bulunur. 
  
        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
       \
        4
-------------------------------------------------------------- 
2 sayısı 3'ten küçük olduğu için 3'in solunda bulunur.

        7
       / \
      5   8
     / \   \
    1   6   9
   / \
  0   3
     / \
    2   4
--------------------------------------------------------------
```
