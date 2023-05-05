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
 a                    4
 b                   /     
 c                  1       
 d                 /  \    
 e                0    3  
 f                    /    
 g                   2     

3.adım-Root'un sağına 4'ten büyük sayıları dallandır.
 a                      4
 b                       \
 c                        7
 d                       / \
 e                      5   8
 f                       \ / \
 g                        6   9
4.adım-Her iki durumu birleştir.
 a                      4
 b                   /     \
 c                  1       7
 d                 /  \    / \
 e                0    3  5   8
 f                    /    \ / \
 g                   2      6   9