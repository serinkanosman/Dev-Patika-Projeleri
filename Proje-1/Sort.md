# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

## Insertion Sort

[22,27,16,2,18,6]

1.adım-Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.

2.adım-[22,27] kıyaslanır ve küçük eleman en başa yazılır.

3.adım-[22,27,16] 3.eleman diğerleriyle kıyaslanır ve küçü olan başa yazılır.
yeni durum:[16,22,27] olur.

4.adım-[16,22,27,2] kıyaslanır ve en küçük elemen en başa yazılır.Yeni durum:[2,16,22,27] olur

5.adım-[2,16,22,27,18] kıyaslanır ve en küçük elemen en başa yazılır.Yeni durum:[2,16,18,22,27] olur

6.adım-[2,16,18,22,27,6]kıyaslanır ve en küçük elemen en başa yazılır.Yeni durum:[2,6,16,18,22,27] olur

7.adım [2,6,16,18,22,27] içerisinde 18 in olduğu indexe bakılır ve ortada olduğu anlaşılır

### Big-O Gösterimi
Karmaşıklığı O(n^2) dir.

### Time Complexity
7.adıma bakılarak "Average Case" olduğu görülür.

## Selection Sort
[7,3,5,8,2,9,4,15,6]
Dizinin ilk elemanını en küçük eleman varsayarak diğer elemanlarla tek tek karşılaştırırız ve daha küçük bir eleman çıkarsa en başa o eleman yazılır.Daha sonra dizinin ikinci elemanı için aynı işlemler yapılarak ikinci küçük eleman yazılır.Bu işlemler her eleman için tekrarlanır.
### İlk 4 adım

1.adım-[7,3,5,8,2,9,4,15,6] içerisindeki en küçük eleman bulunur ve en başa yazılır.Yeni durum:[2,7,3,5,8,9,4,15,6]

2.adım-[2,7,3,5,8,9,4,15,6] içerisindeki en küçük eleman bulunur ve en başa yazılır.Yeni durum:[2,3,7,5,8,9,4,15,6]

3.adım-[2,3,7,5,8,9,4,15,6] içerisindeki en küçük eleman bulunur ve en başa yazılır.Yeni durum:[2,3,4,7,5,8,9,15,6]

4.adım-[2,3,4,7,5,8,9,15,6] içerisindeki en küçük eleman bulunur ve en başa yazılır.Yeni durum:[2,3,4,5,7,8,9,15,6]
