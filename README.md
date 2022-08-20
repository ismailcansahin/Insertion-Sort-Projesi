[22,27,16,2,18,6] -> Insertion Sort

**1-) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

**2-) Big-O gösterimini yazınız.**
n+(n-1)+(n-2)+....+1= n*(n+1)/2=O(n^2)

**3-) Time Complexity:**
1)Average case: Aradığımız sayının ortada olması. 
2)Worst case: Aradığımız sayının sonda olması. 
3)Best case: Aradığımız sayının dizinin en başında olması.

Dizi sıralandıktan sonra 18 sayısı Average Case Kapsamına girmektedir. 

**4-) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

1. Aşama [2,3,5,8,7,9,4,15,6]
2. Aşama [2,3,4,8,7,9,5,15,6]
3. Aşama [2,3,4,5,7,9,8,15,6]
2. Aşama [2,3,4,5,6,9,8,15,7]
