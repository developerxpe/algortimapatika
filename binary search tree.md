# <ins>Binary Search Tree</ins>

Verilen Dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Kök Seçimi: Dizinin ilk elemanı olan 7'yi kök olarak seçeriz.

Ağaç Oluşturma: Diğer elemanları kök ile karşılaştırarak ağaca ekleriz.

5, 1, 8, 3, 6, 0, 9, 4, 2 sırasıyla eklenir.
Eleman Ekleme: Elemanlar ağaç yapısına eklenirken Binary Search Tree koşullarını korumaya çalışırız.

5: Kökten küçük olduğu için sol tarafa eklenir.
1: Kökten küçük olduğu için 5'in soluna eklenir.
8: Kökten büyük olduğu için sağ tarafa eklenir.
3: Kökten küçük olduğu için 5'in sol altına eklenir.
6: Kökten büyük olduğu için 5'in sağ altına eklenir.
0: Kökten küçük olduğu için 1'in sol altına eklenir.
9: Kökten büyük olduğu için 8'in sağ altına eklenir.
4: Kökten büyük olduğu için 3'ün sağ altına eklenir.
2: Kökten büyük olduğu için 3'ün sol altına eklenir.
Bu adımları takip ederek verilen diziyi Binary Search Tree olarak oluşturmuş oluruz. Ağacın düzeni, elemanların eklenme sırasına göre şekillenir ve her düğümün solunda kendi değerinden daha küçük düğümler, sağındaysa kendi değerinden daha büyük düğümler bulunur.

# <ins>Big-O</ins>

En kötü durumda (elemanları sırasıyla eklerken ve ağaç dengesi sağlanmazsa): O(n)

Ortalama durumda (elemanları rastgele eklerken veya dengeleyici yapılar kullanıldığında): O(log n)