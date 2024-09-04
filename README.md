x[22,27,16,2,18,6] -> Insertion Sort
1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1-min=2 swap the 2 and 22 ->[2,27,16,22,18,6]
2-min=6 swap the 27 and 6 ->[2,6,16,22,18,27]
3-min=16 we do not make any changes->[2,6,16,22,18,27]
4-min=18 swap the 22 and 18->[2,6,16,18,22,27]

2)Big-O gösterimini yazınız.
In the first step -> n
In the second step -> n-1
In the third step -> n-2
In the forth step -> 1
(n=4) (n(n+1))/2 => o(n^2)

3)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
it is a worst case because we find 18 at the end of the array.

4)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
step 1-> swap 2 and 7 =>[2,3,5,8,7,9,4,15,6]
step 2-> no need swap =>[2,3,5,8,7,9,4,15,6]
step 3-> swap 5 and 4 =>[2,3,4,8,7,9,5,15,6]
step 4-> swap 5 and 8 =>[2,3,4,5,7,9,8,15,6]
