1.Soru
  [22,27,16,2,18,6] -> Insertion Sort
  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1.Cevap
  - İlk eleman (22) zaten tek başına sıralıdır 22∣27,16,2,18,6
  - 27, 22'nin ardından doğru sıradadır 22,27∣16,2,18,6
  - 16, sıralı dizinin (22, 27) içine yerleştirilir 16,22,27∣2,18,6
  - 2, sıralı dizinin doğru yerine yerleştirilir 2,16,22,27∣18,6
  - 18, sıralı dizinin doğru yerine yerleştirilir 2,16,18,22,27∣6
  - 6, sıralı dizinin doğru yerine yerleştirilir 2,6,16,18,22,27
2.Soru
  Big-O gösterimini yazınız.
2.Cevap
  - n=6 (Dizinin eleman sayısı). 27 için 1, 16 için 2, 2 için 3, 18 için 4, 6 için 5 Toplam 15 işlem ve buda O(n^2)
3.Soru
  Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  1).Average case: Aradığımız sayının ortada olması
  2).Worst case: Aradığımız sayının sonda olması
  3).Best case: Aradığımız sayının dizinin en başında olması.
3.Cevap
  Average case: Aradığımız sayının ortada olması
4.Soru
  [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
4.Cevap
  - en küçük eleman olan 2 sayısı ilk sıradaki 7 sayısı ile yer değiştirir [2|,3,5,8,7,9,4,15,6]
  - kalan en küçük sayı 3 olduğu için sıra bozulmayacak [2,3|,5,8,7,9,4,15,6]
  - 4 sayısı 5 ile yeri değişecek [2,3,4|,8,7,9,5,15,6]
  - 5 sayısıyla 8 değişecek [2,3,4,5|,7,9,8,15,6]
