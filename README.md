# World Robot Olympiad /Future Engineers 359- BAT-X Dosyasıdır.
Bu proje, BAT-X tarafından World Robot Olympiad 2025 için geliştirilmiştir. Robotumuz, belirli görevleri otonom şekilde yerine getirmek üzere programlanmıştır ve LEGO Spike Prime bileşenleri kullanılarak ile inşa edilmiştir.
## Takım Bilgileri

Takım Adı: BATX

Üyeler:

Donanım Tasarımı - Eren Kaynarca

Yazılım Geliştirme - Arda Sami Sevim

Proje Yöneticisi - Emir Üstünsu

Koç - Elif PAKİH
Danışman - Gizem ERDEM GENÇ


Bu proje kategorisine katılmak isteğimiz WRO ya kayıt yaptırdığımızda zaten yıllardır aşina olduğumuz LEGO Technic setleri ile yaptığımız robotları ilk defa bir organizasyonda çalıştırıp deneme ve hatta yarıştırma imkanı bulabilmek bizi çok mutlu etmişti. 
İlk olarak SPIKE içindeki Sürüş Modelini inşa ettik sensörlerimizi de eklediğimizde herşey yolundaydı fakat koç toplantısında Kurallar Dökümanında gözümüzden kaçan sarhoş tekerleğin olmayacağını, robota yön verme durumunu öğrenmek bizi en başa döndürmüştü. 
Bizde takım olarak 
## Kullanılan Bileşenler
LEGO Technic parçaları - Spike Prime Hub ve Sensörleri kullanarak robotumuzu yeniden tasarladık. 
          ##Robotumuzda kullandığımız Hub sensörler ve Bağlantı Noktaları
![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Materyal/Kulland%C4%B1%C4%9F%C4%B1m%C4%B1z%20Ekipman%20ve%20Ba%C4%9Flant%C4%B1%20Noktalar%C4%B1.png)


##Robotumuzun yapım aşamalarına buradan ulaşabilirsiniz.
[Yapım Aşamaları](https://github.com/BAT-X359/BATX-359/tree/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Instruction)


Spike Large Motor kullanarak İleri Yönde Tahrik sistemini elde ettik.
Robotumuzun arka kısmında yer alan ileri yönde tahrik sistemi, açısal hızla çalışan motorun dönme hareketini doğrusal harekete çevirerek robotun ileri yönde hareket etmesini sağlar. Bu sistem, mekanik enerji dönüşümü prensibine dayanır ve açısal momentumu doğrusal itme kuvvetine dönüştürerek robotun dengeli ve kontrollü bir şekilde ilerlemesini mümkün kılar.

![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/%C4%B0leri%20ve%20D%C3%B6n%C3%BC%C5%9F%20Mekanizmalar%C4%B1/%C4%B0leri%20Y%C3%B6nde%20Tahrik%20Sistemi.png)

Şimdi sıra ön dişli için çalışmaktaydı. 
Ön Yönlendirme Sistemi (Kremayer Direksiyon Mekanizması)
Robotumuzun ön yönlendirme sistemi, bir LEGO 1:12 oranındaki siyah pinyon dişlinin, 1x13 LEGO Technic kremayer (gear rack) üzerinde hareket etmesiyle çalışmaktadır. Bu sistem, pinyon dişlinin dönme hareketini doğrusal harekete çevirerek tekerleklerin sağa veya sola yönlendirilmesini sağlar.Kullandığımız mekanizma, otomotiv sistemlerinde de kullanılan kremayer direksiyon kutusu mantığıyla çalışır. Direksiyon simidinden gelen dönme hareketi pinyon dişli aracılığıyla kremayer dişliye aktarılır ve bu doğrusal hareket rotlar aracılığıyla tekerleklere iletilir.
Tasarımda 1x13 kremayer tercih ettik çünkü bu parça, tekerleklere ulaşım açısından daha uygundu. Ancak daha kısa bir kremayer (örneğin 1x6) kullansaydık,daha keskin dönüşler elde edebilirdik fakat bağlantı ve yerleşim sorunları yaşayabilirdik.
![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/%C4%B0leri%20ve%20D%C3%B6n%C3%BC%C5%9F%20Mekanizmalar%C4%B1/Di%C5%9Fli%20Sistem.png)

##Bütün uğraşlarımız sonucu BATX ismini alan romotumuz son halini almıştı.

![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Model/3D.png)

## Robotumuzun Çalışma Mantığı

## Açık Kategori
Robotumuz aşağıdaki adımları izleyerek Açık Kategori görevini yerine getirir:
![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Kod/A%C3%A7%C4%B1k%20Kategori%20Kod.png)

öncelikle kodumuzda motor hızlarımızı belirleyerek ileri doğru sürme hareketini başlatıyoruz. Öndeki Mesafe sensörü 68 cm duvara yaklaşana kadar düz gidiyor duvarı gördüğünde Sol ve Sağ sensörlerde ki duvarların varlığını veya yokluğunu anlayarak saat yönü yada saat yönünün tersine hareket ettiğini anlıyor buna göre ön dişlinin yönünü belirliyor. Belirledikten sonra tekrar ön sensörümüz bir engel algılayana kadar tekrar eder 3 tur tamamlamamız gerektiği için toplamda bu işi 12 kez yaptığımızda başlangıç alanına dönmüş oluyoruz.

Görevin çalışma videosu için [Youtube_Linki](https://www.youtube.com/watch?v=dvVkZ4v6Xsw)

## Engelli Kategori
Robotumuz aşağıdaki adımları izleyerek Engelli Kategori görevini yerine getirir:
![image alt](https://github.com/BAT-X359/BATX-359/blob/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Kod/Engelli%20Kategori%20Kod.png)

öncelikle kodumuzda motoru düz hareketi ile başlıyoruz. Öndeki Mesafe sensörü 35 cm trafik ışıklarına yaklaşana kadar düz gidiyor engele yaklaşmak için 6 cm kalana kadar yavaşça hareket ediyor trafik ışığında gördüğünde Öndeki renk Sensörü ile rengi algılamaya çalışıyor yeşil ise solundan kırmızı ise sağından geçerek dönüş kısmına geçiyor sonra  Sol ve Sağ sensörlerde ki duvarların varlığını veya yokluğunu anlayarak saat yönü yada saat yönünün tersine hareket ettiğini anlıyor buna göre ön dişlinin yönünü belirliyor. Belirledikten sonra tekrar ön sensörümüz bir engel algılayana kadar tekrar eder 3 tur tamamlamamız gerektiği için toplamda bu işi 12 kez yaptığımızda başlangıç alanına dönmüş oluyoruz.

Görevin çalışma videosu için [Youtube_Linki](https://www.youtube.com/watch?v=7Meatvm6HvQ)

Robotumuzda kullandığımız Sensörler ve Hub için daha detaylı bilgi ve Datasheetleri için [tıklayınız](https://github.com/BAT-X359/BATX-359/tree/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Sens%C3%B6rler-Hub)

Robotumuzun fotoğrafları için [tıklayınız](https://github.com/BAT-X359/BATX-359/tree/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Foto%C4%9Fraflar/Robotlar)

Bizi merak ettiyseniz [buradayız](https://github.com/BAT-X359/BATX-359/tree/df465b316d2dc62f2fc8dfc1b1bba2d2353a6c41/Foto%C4%9Fraflar/Tak%C4%B1m)

Sürecimiz boyunca çok çalıştık elimizden gelenin fazlasını yaptık. Bundan sonrası robotumuza kaldı.

Daha bir çok dökümanımız var dökümanlarımızı incelemenizi tavsiye ederiz. 



 

---
