# <ins>Merge Sort</ins>

## Verilen Dizi: [16, 21, 11, 8, 12, 22]

1. Bölme (Split):
Diziyi ikiye bölerek alt dizilere ayırırız.

Sol Dizi: [16, 21, 11]
Sağ Dizi: [8, 12, 22]
Alt Dizi Bölme:
Her bir alt diziyi tekrar ikiye böleriz.

Sol Dizi: [16, 21], [11]
Sağ Dizi: [8, 12], [22]

2. Birleştirme (Merge):
Sıralı alt dizileri birleştirerek yeniden birleştirilmiş sıralı bir dizi oluştururuz.

Sol Dizi: [16, 21] -> [16, 21]
Sağ Dizi: [11]
Sol Dizi: [8, 12] -> [8, 12]
Sağ Dizi: [22]

3. Birleştirme Aşaması:
Sıralı alt dizileri birleştirerek sonuç dizisini elde ederiz.

Sol Dizi: [16, 21]
Sağ Dizi: [11]

Birleştirilmiş Dizi: [11, 16, 21]
Sol Dizi: [8, 12]
Sağ Dizi: [22]

 Birleştirilmiş Dizi: [8, 12, 22]

5. Sonuç:
Son olarak, iki birleştirilmiş alt diziyi birleştirerek sıralanmış sonucu elde ederiz.

Sol Dizi: [11, 16, 21]
Sağ Dizi: [8, 12, 22]
Sonuç Dizi: [8, 11, 12, 16, 21, 22]
Bu şekilde, verilen diziyi Merge Sort algoritması kullanarak sıralamış oluyoruz. 


# <ins>Big-O gösterimi</ins>

### O(n log n)