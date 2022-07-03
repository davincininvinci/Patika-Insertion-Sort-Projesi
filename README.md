# Patika-Insertion-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

1) Yukarıda verilen dizinin sort'a göre aşamalarını yazınız.
İlk önce en küçük olanı ilk sırada olan sayı ile yer değiştiririz [2,27,16,22,18,6]

Daha sonra 2'den sonra gelen en küçük sayı ile ikinci sayının yerini değiştirilir. [2,6,16,22,18,27]

Aynı şekilde devam edildiğinde; [2,6,16,22,18,27] > 3. sıradaki sayı en küçük olduğu için işlem yapılmadı. [2,6,16,18,22,27] > 18 ile 22 sayılarının yerleri değiştirildi. [2,6,16,18,22,27] > istenilen şekilde dizimiz büyükten küçüğe sıralandı.

2) Big-O gösterimini yazınız. n sayıda elemanımızdan en küçüğü bulmak için n elemanı kontrol ederiz. Daha sonra n-1 elemanı kontrol ederiz. Bu şekilde devam eder n+(n-1)+(n-2)+(n-3).. 1'den n'e kadar olan sayıların toplamından (n(n-1))/2 gelir big-o notation ise O(n^^2) olur. O(6^^2) O(36) big o notation değeri bulunur.

3) Time Complexity Average case aradığımız sayının dizinin ortasında olması, worst case aradağımız sayının sonra olması ve best case ise aranan sayının dizinin başında olmasıdır

Average case: 16,18 Worst case: 27 Beste case: 2

4) Dizi sıralandıktan sonra 18 sayısı average case kapsamına girmektedir.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] [2,3,5,8,7,9,4,15,6] [2,3,4,8,7,9,5,15,6] [2,3,4,5,7,9,8,15,6]
