# kodluyoruz-veribilimi

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]
2 ile 22 yer değiştirir.
[2,27,16,22,18,6]
6 ile 27 yer değiştirir
[2,6,16,22,18,27]
18 ile 22 yer değiştirir.
[2,6,16,18,22,27]

Big-O gösterimini yazınız.

[2,27,16,22,18,6] ( n )
[2,6,16,22,18,27] (n-1) 
[2,6,16,18,22,27] 1

O(n²) olarak bulunur. 

Time Complexity

Worst Case : O(n²)
Average Case : O(n²)
Best Case : O(n)

Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average Case kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. aşama [2,3,5,8,7,9,4,15,6]
2. aşama [2,3,4,8,7,9,5,15,6]
3. aşama [2,3,4,5,7,9,8,15,6]
4. aşama [2,3,4,5,6,9,8,15,7]
