 # [22,27,16,2,18,6] -> Insertion Sort
1. ## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27 I 16,2,18,6]
[22,16,27 I 2,18,6]
__[16,22,27 I 2,18,6]__
[16,22,2,27 I 18,6]
[16,2,22,27 I 18,6]
__[2,16,22,27 I 18,6]__
[2,16,22,18,27 I 6]
__[2,16,18,22,27 I 6]__
[2,16,18,22,6,27]
[2,16,18,6,22,27]
[2,16,6,18,22,27]
__[2,6,16,18,22,27]__

## 2. Big-O gösterimini yazınız.

__O(n2)__

## 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

## 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

__[2,6,16,18,22,27]__

18 sayısı son dizilime göre Average case kapsamındadır.

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

__[3,7 I 5,8,2,9,4,15,6]__
__[3,5,7 I 8,2,9,4,15,6]__
[3,5,7,2  I 8,9,4,15,6]
[3,5,2,7 I 8,9,4,15,6]
[3,5,2,7 I 8,9,4,15,6]
[3,2,5,7 I 8,9,4,15,6]
__[2,3,5,7 I 8,9,4,15,6]__
[2,3,5,7,8,4,9 I 15,6]
[2,3,5,7,4,8,9 I 15,6]
[2,3,5,4,7,8,9 I 15,6]
__[2,3,4,5,7,8,9 I 15,6]__
