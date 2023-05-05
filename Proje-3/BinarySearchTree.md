Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Binary Search Tree
-Root en üstte bulunan node olarak ifade edilir
-Root'tan küçük nodelar root'un soluna yazılır.
-Root'tan büyük nodelar root'un sağına yazılır.

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] için
1.adım-Root'u 4 olarak belirle.

2.adım-Root'un soluna 4'ten küçük sayıları dallandır.
                     4
                    /     
                   1       
                  /  \    
                 0    3  
                     /    
                    2      
3.adım-Root'un sağına 4'ten büyük sayıları dallandır.
                       4
                         \
                          7
                         / \
                        5   8
                         \ / \
                          6   9
4.adım-Her iki durumu birleştir.
                       4
                    /     \
                   1       7
                  /  \    / \
                 0    3  5   8
                     /    \ / \
                    2      6   9