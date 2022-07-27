# Insertion-Sort-Patika.dev

www.patika.dev

# Proje 1
A) [22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız. 

# B) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

# 1. Aşamalar
[22,27,16,2,18,6]-- n

[2,27,16,22,18,6]-- n-1

[2,6,16,22,18,27]-- n-2

[2,6,16,18,22,27]-- n-3

# 2. Big-O Gösterimi 

Worst Case  n+(n-1)+(n-2)+(n-3)...+1

Average Case O(n²)

Best Case O(n)

# 3. Time Complexity

Best case  [2,6,16,18,22,27]

Worst case [22,27,16,2,18,6]

Averaged case [2,27,16,22,18,6]

# 4. 18 Sayısının Durumu
Küçükten büyüğe sıralandığında 18 ortadadır. Bu yüzden de average case olur.

# B) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. adım [7,3,5,8,2,9,4,15,6]
2. adım [2,3,5,8,7,9,4,15,6]
3. adım [2,3,4,8,7,9,5,15,6]
4. adım [2,3,4,5,7,9,8,15,6] 
