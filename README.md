# Microprocessor-Final-Project28
# Akıllı Ev Güvenlik ve Çevresel İzleme İstasyonu
Bu proje, Mikroişlemciler dersi final projesi kapsamında geliştirilen, mikrodenetleyici tabanlı bir entegre güvenlik sistemidir.

##  Proje Amacı
Tek kontrol ünitesi üzerinden evin hem güvenliğini (şifreli giriş) hem de yaşamsal risk faktörlerini (gaz sızıntısı, sıcaklık-nem) eş zamanlı olarak takip etmek ve kritik durumlarda alarm mekanizmasını devreye sokmaktır.

##  Kullanılan Donanım Bileşenleri
- Kontrolcü: ATmega328P tabanlı Mikrodenetleyici
- Giriş: 4x4 Matris Keypad = Kullanıcı şifre girişi için
- Sensörler: - MQ-2 Yanıcı Gaz ve Duman Sensörü
  - DHT11 Dijital Sıcaklık ve Nem Sensörü
- Çıkış: - 16x2 I2C LCD Ekran = Durum bildirimi için
  - SG90 Servo Motor = Elektronik kilit simülasyonu için
  - Aktif Buzzer = Sesli uyarı sistemi için 

##  Teknik Özellikler
- Yazılım Dili: C 
- Mimari: Interrupt tabanlı acil durum yönetimi ve PWM ile motor kontrolü.
- Analiz: Sensör sinyal kararlılığı için LTSpice simülasyonları kullanılacaktır.

##  Proje Durumu
- [x] Donanım bileşenleri belirlendi.
- [ ] Proje mimarisi tasarlandı.
- [ ] Kod geliştirme aşaması (Devam ediyor).
- [ ] Fiziksel montaj ve test.
