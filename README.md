Bu proje, Python kullanılarak geliştirilmiş basit bir Tic Tac Toe (X-O) oyunudur. Oyun konsol üzerinden oynanır ve kullanıcı O, bilgisayar ise X ile hamle yapar. Tahta başlangıçta 1–9 arasındaki sayılarla temsil edilir ve oyuncu hamlesini bu sayılara karşılık gelen hücreyi seçerek yapar.

Oyun Kuralları

Oyun 3x3'lük kare bir tahtada oynanır.
Oyuncu O, bilgisayar ise X sembolünü kullanır.
Her kare 1’den 9’a kadar numaralandırılmıştır:
Oyuncu hamlesini yapmak için 1–9 arasında bir sayı girer.
Seçilen hücre doluysa oyuncudan başka bir hücre seçmesi istenir.
Her hamleden sonra oyun tahtası tekrar çizilir.
Oyuncu veya bilgisayar, yatay, dikey veya çapraz olarak 3 aynı sembolü yan yana getirirse oyunu kazanır.
Tüm kareler dolu olup kimse kazanmamışsa oyun berabere biter.

Bilgisayarın hamlesi

Bilgisayar boş kareleri tespit eder.
Python’un randrange() fonksiyonunu kullanarak rastgele bir boş kare seçer.
Bu kareye X yerleştirir.

Her hamleden sonra kontrol edilen durumlar:

3 yatay satır

3 dikey sütun

2 çapraz çizgi

Bir oyuncu kendi işaretini bu üçlülerden birine eksiksiz yerleştirirse kazanmış olur.

Oyunu Çalıştırmak İçin
terminal veya komut satırında:

python tic_tac_toe.py

yazarak enter'a basınız.
