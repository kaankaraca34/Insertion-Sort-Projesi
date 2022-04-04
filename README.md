# Veri Yapıları ve Algoritmalar
###  Insertion-Sort-Projesi 
Insertion Sort Algoritma Ödevi  www.patika.dev

[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 ---

 ###  cevaplar
 ###  1
 ---
    1. 22 | 27 16 2 18 6
    2. 22 27 | 16 2 18 6
    3. 16 22 27 | 2 18 6
    4. 2 16 22 27 | 18 6
    5. 2 16 18 22 27 | 6
    6. 2 6 16 18 22 27 |
    
 ### 2  
 ---
     O(n) = n^2
    
 ### 3  
 ---
    - Best Case
        O(n) -> Dizimizin sıralı olması durumudur.
    - Worst Case
        O(n^2) -> tüm değerleri gezme durumumuz. Dizinin büyükten küçüğe sıralı gelmesi.
    - Average Case
        O(n^2) -> Best Case ile Worst Case olmayan durumların hepsi
 
 ### 4
 ---
 Average case 
 
 ### 5
---
    1. 7 | 3 5 8 2 9 4 15 6
    2. 3 7 | 5 8 2 9 4 15 6
    3. 3 5 7 | 8 2 9 4 15 6
    4. 3 5 7 8 | 2 9 4 15 6
    5. 2 3 5 7 8 | 9 4 15 6
     
