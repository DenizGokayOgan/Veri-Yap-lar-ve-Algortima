## Veri Yapıları ve Algoritma
### Selection Sort

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
- Time Complexity: 
Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1-)  Sorting
```
1. [ 22-27-16-2-18-6 ]		
2. [ 2-27-16-22-18-6 ]		
3. [ 2-6-16-22-18-27 ]		
4. [ 2-6-16-18-22-27 ]
``` 

2-) Big-O 
```
O(n^2)
```
3-) Time Complexity:
 ```
Average case:O(n²)
Worst case: O(n²)
Best case:O(n)
 ```
 4-)
  ```
 18 average case kapsamındadır.
 ```
 5-)
 ```

1. [7,3,5,8,2,9,4,15,6]		(n)

2. [2,3,5,8,7,9,4,15,6]		(n-1)

3. [2,3,4,8,7,9,5,15,6]		(n-2)

4. [2,3,4,5,7,9,8,15,6]		(1)
 ``` 
