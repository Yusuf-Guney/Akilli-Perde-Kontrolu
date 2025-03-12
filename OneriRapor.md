# Akıllı Perde Kontrol Sistemi - Öneri Raporu

## Proje Konusu
Bu proje, iç mekanlarda konforu artırmak ve enerji verimliliğini sağlamak amacıyla ışık ve sıcaklık sensörleri kullanarak otomatik olarak açılıp kapanabilen bir perde kontrol sistemini geliştirmeyi amaçlamaktadır. Sistem, çevresel faktörleri analiz ederek perdeyi uygun şekilde konumlandırarak kullanıcı müdahalesini minimuma indirir.

## Proje Hedefleri
- Güneş ışığı ve sıcaklık değişimlerine duyarlı bir perde kontrol mekanizması geliştirmek.
- Kullanıcı müdahalesini en aza indirerek iç mekan konforunu artırmak.
- Enerji verimliliğini artırarak gereksiz ısı kaybını veya güneş ışığı kullanımını optimize etmek.
- Opsiyonel olarak, mobil uygulama ile manuel kontrol özelliği eklemek.

**Başarı Kriterleri:**
- Sensörlerin doğru veri toplaması ve sistemin çevresel değişikliklere uygun tepki vermesi.
- Perdenin belirlenen eşik değerlerine göre otomatik olarak açılması/kapanması.
- Kullanıcı memnuniyetine yönelik testlerde olumlu geri bildirim alınması.

## Tahmini Zaman Çizelgesi

| Hafta | Yapılacak İşlem |
|-------|----------------|
| 1. Hafta | Proje gereksinimlerinin belirlenmesi ve malzeme temini |
| 2. Hafta | Arduino ve bileşenlerin test edilmesi |
| 3. Hafta | Sensörlerin bağlantılarının yapılması ve test edilmesi |
| 4. Hafta | Servo motor kontrolünün gerçekleştirilmesi |
| 5. Hafta | Röle modülü ile perde kontrol mekanizmasının oluşturulması |
| 6. Hafta | Buzzer ile sesli uyarı sisteminin eklenmesi |
| 7. Hafta | Tüm sistemin birleştirilmesi ve yazılım testleri |
| 8. Hafta | Son testler ve proje raporunun hazırlanması |

## Kaynak Planlaması
**Proje Ekibi:**
- Burak TÜRK
- Mustafa Erhan PORTAKAL
- Ömer Faruk KOCAEFE
- Yusuf GÜNEY

### Görev Dağılımı

- **Donanım ve Devre Tasarımı:** Ömer Faruk KOCAEFE, Mustafa Erhan PORTAKAL, Burak TÜRK, Yusuf GÜNEY
- **Yazılım Geliştirme:** Ömer Faruk KOCAEFE, Mustafa Erhan PORTAKAL, Burak TÜRK, Yusuf GÜNEY
- **Test ve Entegrasyon:** Ömer Faruk KOCAEFE, Mustafa Erhan PORTAKAL, Burak TÜRK, Yusuf GÜNEY

**Proje Maliyeti:**
- Arduino UNO Başlangıç Seti: 400 TL
- Servo Motor (SG90/MG995): 50 TL
- LDR Sensör: 50 TL
- DHT11/DHT22 Sıcaklık Sensörü: 100 TL
- **Toplam:** 600 TL

**Kullanılacak Yazılımlar:**
- Arduino IDE
- C++ Programlama Dili

## Risk Analizi
| Risk Faktörü                           | Olası Çözüm              |
|----------------------------------------|--------------------------|
| Sensörlerin yanlış veri okuması        | Sensör kalibrasyonu      |
| Servo motorun çalışmaması              | Alternatif motor denemesi |
| Güç kaynağı yetersizliği               | Harici güç kaynağı kullanımı |
| Yazılım hataları                       | Kod optimizasyonu ve test |

## Ticari Potansiyel
Bu proje, akıllı ev sistemleri ve enerji verimliliği alanlarında geniş bir ticari potansiyele sahiptir. Potansiyel kullanım alanları:
- **Ev otomasyonu**: Kullanıcıların manuel müdahale gerektirmeden konfor sağlaması.
- **Ofis ve ticari alanlar**: Güneş ışığını ve sıcaklığı optimize ederek enerji tasarrufu sağlanması.
- **Otel ve konaklama sektörü**: Konuk konforunu artırarak premium hizmet sunulması.

## Görseller

## Örnek Proje Maketi
![Örnek Proje Maketi](Figure/Maket.png)

## Kullanılacak Malzemeler
### Arduino Set
![Arduino Set](Figure/Ardunio_Set.png)

### Buzzer
![Buzzer](Figure/Buzzer.png)

### Röle
![Röle](Figure/Role.png)

### Servo Motor
![Servo Motor](Figure/Servo_Motor.png)

### Sıcaklık Sensörü
![Sıcaklık Sensörü](Figure/Sıcaklık_Sensoru.png)

