# Ara Rapor

## 1. Proje Konusu (Kısa)
Işık ve sıcaklık seviyelerine bağlı olarak çalışan, perdeyi otomatik olarak açıp kapatabilen bir akıllı kontrol sistemi.

## 2. Özet (Kısa)
Bu proje kapsamında, iç ortamda sıcaklık ve ışık sensörleri kullanılarak, bir servo motor ile perde kontrolü sağlanmaktadır. Bu sayede güneş ışığına ve sıcaklığa bağlı olarak perdelerin otomatik açılıp kapanması hedeflenmektedir. Şu ana kadar devre şeması hazırlanmış, Proteus simülasyonu yapılmış ve sistemin temel işlevselliği test edilmiştir.

## 3. Kullanılan Yöntemler
- **Donanım:** Arduino UNO, SG90 servo motor, DHT11 sıcaklık sensörü, LDR ışık sensörü, breadboard, jumper kablolar.
- **Yazılım:** Arduino IDE ile C/C++ dili kullanılarak kodlama yapılmıştır.
- **Simülasyon:** Proteus programı kullanılarak devre testi gerçekleştirilmiştir.
- **Test:** Gerçek ortamda sensör değerleri alınmış ve motorun dönmesi sağlanmıştır.

## 4. Yapılan Çalışmalar ve Görselleri
- Işık ve sıcaklık sensörleri Arduino’ya bağlandı.
- Servo motor ile perde kontrolü yapacak temel algoritma geliştirildi.
- Proteus programı ile devre simülasyonu hazırlandı.
- Devre başarıyla çalıştırıldı ve servo motora sinyal gönderildi.

**Görsel 1: Proteus Devre Simülasyonu**  
![Proteus Devre Simülasyonu](Figure/devre5.jpg)


**Görsel 2: Gerçek Devre Bağlantısı**  
![Gerçek Devre](Figure/devre1.jpg)
![Gerçek Devre](Figure/devre2.jpg)
![Gerçek Devre](Figure/devre3.jpg)
![Gerçek Devre](Figure/devre4.jpg)


## 5. Elde Edilen Sonuçlar
- Sensörlerden alınan veriler doğru bir şekilde okunmaktadır.
- Arduino üzerinden servo motor kontrolü sağlanmıştır.
- Proteus ortamında yapılan simülasyon, gerçek devre davranışıyla uyumlu şekilde çalışmaktadır.
- Sistem temel fonksiyonlarını başarıyla gerçekleştirmektedir.

## 6. Karşılaşılan Sorunlar ve Çözümler
| Sorun | Çözüm |
|------|-------|
| Proteus’ta servo motorun tam simülasyonu yapılamadı | Benzer işlevselliği sağlayacak komponentlerle devre simüle edildi |
| DHT11 veri kararsızlığı | Kodda ortalama alma ve gecikme stratejileriyle daha doğru sonuçlar elde edildi |
| Servo motorun dönüş açısının sınırlı olması | Servo motorun içindeki sınırlayıcı çıkıntı sökülecek şekilde plan yapıldı |

## 7. Projenin Devamında Yapılacaklar
- Servo motorun 360 derece dönebilmesi için iç modifikasyon yapılacaktır.
- Küçük bir perde maketi hazırlanacak ve sistem bu maket üzerine monte edilecektir.
- Servo motorun dönme yönü ve açısı perde sistemine göre yeniden ayarlanacaktır.
- Proje kasası ve estetik görünüm tamamlanacak.
- (Opsiyonel) Bluetooth veya Wi-Fi modülü ile mobil kontrol özelliği eklenecek.

