# data-structure-project-patikadev

## Selection - Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

a) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

  [22,27,16,2,18,6] -> 
  [22,16,27,2,18,6] -> 
  [16,22,27,2,18,6] -> 
  [16,22,2,27,18,6] -> 
  [16,2,22,27,18,6] -> 
  [2,16,22,27,18,6] -> 
  [2,16,22,18,27,6] -> 
  [2,16,18,22,27,6] -> 
  [2,16,18,22,6,27] -> 
  [2,16,18,6,22,27] -> 
  [2,16,6,18,22,27] -> 
  [2,6,16,18,22,27]

  
b) Big-O gösterimini yazınız.

--> o(n^2)


c) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Aranan sayi ortada oldugu icin : Average Case


d) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,4,15,6] -> 
[2,3,5,8,7,4,15,6] -> 
[2,3,4,8,7,5,15,6] -> 
[2,3,4,5,7,8,15,6]



## Merge Sort

[16,21,11,8,12,22] -> Merge Sort

a) Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
 
 [16,21,11]        -         [8,12,22]  ->
 
 [16,21]      [11]         -        [8,12]     [22] ->
 
 [16]   [21]   [11]        -        [8]     [12]    [22] ->
 
 [16,21]      [11]          -        [8,12]      [22] ->

 [11,16,21]            -                [8,12,22] ->

 Final = [8,11,12,16,21,22]

 
b) Big-O gösterimini yazınız.

--> O(nlogn)


## Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


          7
          |  \
          5   8
          | \   \
          1   6   9
          | \     |
          0   3   9
              | \
              2   4


