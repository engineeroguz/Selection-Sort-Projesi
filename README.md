# Selection-Sort-Projesi
Patika_Veri_Bilimi_Proje1
# Selection-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Çözüm :  1. [16,22,27,2,18,6]
         2. [2,16,22,27,18,6]
         3. [2,16,18,22,27,6]
         4. [2,6,16,18,22,27]
          
----------------------------------------------------------------------
Big-O gösterimini yazınız.

Çözüm: lk adımda (n) eleman, ikinci adımda (n-1) eleman, üçüncü adımda (n-2) eleman ile işlem yaparak 1 eleman kalana kadar devam ediyoruz.

Formül--> n+(n-1)+(n-2)+...+1= n(n+1) /2

n^2+n /2 elde ettik. n^2 yi alıyoruz. Sonuç--> O(n^2)

---------------------------------------------------------------------------------------

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Çözüm: 18 sayısı ortada olduğu için avarage case kapsamına girer.

-----------------------------------------------------------------------------
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Çözüm :   --> 1.  [2,3,5,8,7,9,4,15,6] 
          --> 2.  [2,3,4,8,7,9,5,15,6] 
          --> 3.  [2,3,4,5,7,9,8,15,6]
          --> 4.  [2,3,4,5,6,9,8,15,7] 
          
