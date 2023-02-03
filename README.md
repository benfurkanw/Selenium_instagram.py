Programı çalıştırmadan önce terminale "pip install selenium" yazıp selenium kütüphanesini indirin yoksa çalışmaz.

Merhaba programın yapılış amacı sizi takip etmeyen kullanıcıları güvenli yoldan bulabilmeniz.

İnstagram hesabınızda koruyucu(Girişlerde telefon veya maile gelen kodlar) var ise program hata verebilir, programı kullanabilmek için ilk olarak onları kaldırın

Koruyuculardan dolayı sorun çıkmasının sebebi time.sleep() kodlarının koruyuculara göre yazılmaması 

Nadir de olsa programda hatalar oluşabilir, eğer bir hata ile karşılaşırsanız programı kapayıp tekrar çalıştırınız.

Yaşadığınız hatalar neden olabilir;

1- Driver güncel değildir güncelleyiniz
2- Selenium kütüphanesi güncel olmayabilir "pip install selenium --upgrade" yazarak güncelleyebilirsiniz
3- Nadirde olsa Chrome hata verebilir o zamanlar edge driver'ını kurup Choreme yazan yeri Edge yapmanız yeterli olacaktır