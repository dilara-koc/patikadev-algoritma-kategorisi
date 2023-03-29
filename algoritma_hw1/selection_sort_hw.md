Bu ödevde [22, 27, 16, 2, 18, 6] dizisinin Insertion Sort'a göre ve [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre sıralanması istenmektedir. Ayrıca Insertion Sort'a göre sıralanan dizinin Time-Complexity'sinin belirtilmesi ve Big-O gösterimi istenmektedir.

### [22, 27, 16, 2, 18, 6] dizisinin **Insertion Sort (Eklemeli Sıralama)** türüne göre sıralanmasının aşamaları aşağıdaki gibidir:

1. Adım: [22, 27, 16, 2, 18, 6] --> İlk iki sayı olan 22 ve 27'ye bakılmış ve 22<27 olduğundan değişiklik yapılmamıştır.
2. Adım: [22, 16, 27, 2, 18, 6] --> Diğer iki sayı olan 27 ve 16'ya bakılmış 27>16 olduğu için 16 sola kaydırılmıştır.
3. Adım: [16, 22, 27, 2, 18, 6] --> 2. adım sonrası ilk iki sayı olan 22>16 olduğu için 16 tekrar sola kaydırılmıştır.
4. Adım: [16, 22, 2, 27, 18, 6] --> 3 ve 4. sayılar olan 27>2 olduğu için 2 sola kaydırılmıştır.
5. Adım: [16, 2, 22, 27, 18, 6] --> 4. adım sonrası 22>2 olduğu için 2 tekrar sola kaydırılmıştır.
6. Adım: [2, 16, 22, 27, 18, 6] --> 5. adım sonrası 16>2 olduğu için 2 tekrar sola kaydırılmıştır.
7. Adım: [2, 16, 22, 18, 27, 6] --> 4. ve 5. sayılar olan 27 ve 18 karşılaştırılmış 27>18 olduğu için 18 sola kaydırılmıştur.
8. Adım: [2, 16, 18, 22, 27, 6] --> 7. adım sonrası 22>18 olduğu için 18 tekrar sola kaydırılmıştır.
9. Adım: [2, 16, 18, 22, 6, 27] --> 5. ve 6. sayılar olan 6 ve 27 karşılaştırılmış 27>6 olduğundan 6 sola kaydırılmıştır.
10. Adım: [2, 16, 18, 6, 22, 27] --> 9. adım sonrası 22>6 olduğundan 6 tekrar sola kaydırılmıştır.
11. Adım: [2, 16, 6, 18, 22, 27] --> 10. adım sonrası 18>6 olduğundan 6 tekrar sola kaydırılmıştır.
12. Adım: [2, 6, 16, 18, 22, 27] --> 11. adım sonrası 16>6 olduğundan 6 tekrar sola kaydırılmıştır.

Bu adımlar ile elemanların sırasına uygun olarak listeye tek tek eklenmesi gerçekleştirilmiştir.

* Big-O gösterimi 0(n^2)'dir.

* Time-Compexity'ye göre "18" sayısı average case'e dahildir. Eğer en baştaki (en küçük) eleman olsaydı best case olacak ve time-complexity'si O(n) olacaktı. Eğer en sondaki (en büyük) eleman olsaydı worst case olacak ve time-complexity'si O(n^2) olacaktı. 

* 18 sayısı 6 elemanlık sayı dizisinin 4. sırasındaki elemanı olduğundan average case ve time-complexity'si:

> O(n^2)
> =O(6^2)
> =O(36)'dır.

### [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin **Selection Sort (Seçerek Sıralama)** türüne göre sıralanmasının aşamaları aşağıdaki gibidir:

1. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] --> Dizinin en küçük elemanı 2 ile 7 yer değiştirilmiştir.
2. Adım: [2, 3, 5, 8, 7, 9, 4, 15, 6] --> 2. sıra için dizideki 2. en küçük eleman 3 olduğundan değişiklik yapılmamıştır.
3. Adım: [2, 3, 4, 8, 7, 9, 5, 15, 6] --> 3. sıra için dizideki 3. en küçük elaman 4 ile 5'in yeri değiştirilmiştir.
4. Adım: [2, 3, 4, 5, 7, 9, 8, 15, 6] --> 4. sıra için dizideki 4. en küçük eleman 5 ile 8'in yeri değiştirilmiştir.
5. Adım: [2, 3, 4, 5, 6, 9, 8, 15, 7] --> 5. sıra için dizideki 5. en küçük eleman 6 ile 7'nin yeri değiştirilmiştir.
6. Adım: [2, 3, 4, 5, 6, 7, 8, 15, 9] --> 6. sıra için dizideki 6. en küçük eleman 7 ile 9'un yeri değiştirilmiştir.
7. Adım: [2, 3, 4, 5, 6, 7, 8, 15, 9] --> 7. sıra için dizideki 7. en küçük eleman 8 olduğundan değişiklik yapılmamıştır.
8. Adım: [2, 3, 4, 5, 6, 7, 8, 9, 15] --> 8. sıra için dizideki 8. en küçük eleman 9 ile 15'in yeri değiştirilmiştir.

