Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Merge Sort
1.adım-ilk önce sıralı olmayan diziyi iki alt diziye ayır.

[16,21,11] [8,12,22]

2.adım-Ayırma işlemini alt diziler en çok iki elemanlı olana kadar devam et
{[16,21],[11]} , {[8,12],[22]}
{[16],[21],[11]} , {[8],[12],[22]}

3.adım-Dizileri küçükten büyüğe doğru sırala
{[16],[21],[11]} , {[8],[12],[22]} 
{[11],[16],[21]} , {[8],[12],[22]}

4.adım-Dizileri  birleştir.
{[11,16],[21]} , {[8,12],[22]}
{[11,16,21]} , {[8,12,22]}
{[11,16,21,8,12,22]}



### Big-O Gösterimi
O(nlogn)'dir.