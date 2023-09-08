# Insertion-Sort-Project

Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
Big-O gösterimini yazınız.
n+(n-1)+(n-2)+(n-3)+(n-4)+1= (n(n+1))/2= n^2 Big-O = n^2

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
Aradığımız sayı dizinin ortasında. Average case.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]


Proje 2(Merge Sort)
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
[16,21,11,8,12,22]
[16,21,11]|---------------[8,12,22]
[16]---[21,11]----------[8]----[12,22]
[16]---[21]--[11]-------[8]---[12]--[22]
[16]----[11,21]---------[8]----[12,22]
[11,16,21]----------------[8,12,22]
[8,11,12,16,21,22]

Big-O gösterimini yazınız.
2^x = n
x = logn
Big-O = O(nlogn)

Proje 3(Binary-Search-Tree)
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Root 7
5 soluna
1 soluna -> 5in soluna
8 sağına
3 soluna -> 5in soluna -> 1in sağına
6 soluna -> 5in sağına
0 soluna -> 5in soluna -> 1in soluna
9 sağına -> 8in sağına
4 soluna -> 5in soluna -> 1in sağına -> 3ün sağına
2 soluna -> 5in soluna -> 1in sağına -> 3ün soluna

          7
         / \
        5   8
       / \    \
      1   6    9
     / \
    0   3
       / \
      2   4
