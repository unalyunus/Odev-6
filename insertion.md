Proje 1
-------

[22,27,16,2,18,6] -> Insertion Sort

1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2- Big-O gösterimini yazınız.
3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, 
   Best case: Aradığımız sayının dizinin en başında olması.
4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1)

-> [22,27,16,2,18,6] -> [22,16,27,2,18,6] -> [16,22,27,2,18,6] -> [16,22,2,27,18,6]

-> [16,2,22,27,18,6] -> [2,16,22,27,18,6] -> [2,16,22,18,27,6] -> [2,16,18,22,27,6]

-> [2,16,18,22,6,27] -> [2,16,18,6,22,27] -> [2,16,6,18,22,27] 

-> [2,6,16,18,22,27]


2) O(n^2)

3) Average Case : (n^2) 
   Worst Case   : (n^2)
   Best Case    : (n)
   
4) Avarage Case

------------------------------------------------------------------------------------------

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Adım 1: [3,7,5,8,2,9,4,15,6]
Adım 2: [3,5,7,8,2,9,4,15,6]
Adım 3: [3,5,7,2,8,9,4,15,6]
Adım 4: [3,5,2,7,8,9,4,15,6]


