# <ins>Insertion Sort</ins>

[22, 27, 16, <span style="color:red"> 2</span>, 18, 6]

Bu Sayı öbeğinde en küçük sayıyı tespit ederim.

[<span style=" color:red">2</span>, 27, 16, 22, 18, 6]

Sonrasında 2. sayı ile 1.sayı karşılaştırırım. 2. sayı 1. sayıdan büyükse yer değiştiririm.

[<span style=" color:red">2</span>, <span style=" color:green">16</span>, <span style=" color:yellow">27</span>, 22, 18, 6]

Sonrasında 3. adımda 3. eleman 2. eleman ile karşılaştırılır. Eğer 3. eleman daha küçükse 2. eleman ile yer değiştirir.

[<span style=" color:red">2</span>, <span style=" color:green">16</span>, <span style=" color:yellow">22</span>, <span style=" color:yellow">27</span>, 18, 6]

tekrar yer değiştirdi.

[<span style=" color:red">2</span>, <span style=" color:red">16</span>, <span style=" color:green">18</span>, <span style=" color:yellow">22</span>, <span style=" color:yellow">27</span>, 6]

tekrar yer değiştirdi.

[<span style=" color:red">2</span>, <span style=" color:green">6</span>,
<span style=" color:red">16</span>, <span style=" color:red">18</span>, <span style=" color:red">22</span>, <span style=" color:red">27</span>,]

Sonucu bu şekilde elde ederim.


# <ins>Big O Not</ins>

[<span style=" color:red">2</span>, <span style=" color:green">6</span>,
<span style=" color:red">16</span>, <span style=" color:red">18</span>, <span style=" color:red">22</span>, <span style=" color:red">27</span>,]

Big-O gösterimi

<span style="color:red"> O(n
2
)</span> 'dir.

# <ins>Time Complexity</ins>
Dizi sıralandıktan sonra 18 sayısı case'lerden hangisinin kapsamına girer?

(Insertion Sort'a göre sıralandı)

1. İşlem [22, 27, 16, 2, 18, 6]

2.  İşlem [2, 27, 16, 22, 18, 6]

3. İşlem [2, 16, 27, 22, 18, 6]

4. İşlem [2, 16, 22, 27, 18, 6]

5. İşlem [2, 16, 18, 22, 27, 6]

6. İşlem [2, 6, 16, 18, 22, 27]


Cevap "
Average Case "


# <ins>Selection Sort</ins>

[7,3,5,8,<span style="color:red"> 2</span>,9,4,15,6]

En küçük eleman seçilir.

[<span style="color:red">2</span>,3,5,8,7,9,4,15,6]

En başa taşınır.

[<span style="color:red">2,3</span>,5,8,7,9,<span style="color:yellow">4</span>,15,6]

Kırmızı renk dışında sayı öbeği taranır ve en küçük olan havuza alınır.

[<span style="color:red">2,3,</span><span style="color:yellow">4</span>,8,7,9,5,15,6]

Daha açıklayıcı olması için bu şekilde sonuna kadar devam eder.






