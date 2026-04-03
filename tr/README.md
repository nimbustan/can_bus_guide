# CAN Bus Teknik Kılavuzu — Türkçe Edisyon

**Kapsamlı Teknik Referans ve Uygulama Kılavuzu**\
Controller Area Network Protokolleri, Uygulama ve Tanılama

[![Lisans: CC BY-NC-SA 4.0](https://img.shields.io/badge/İçerik-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Lisans: Apache 2.0](https://img.shields.io/badge/Kod-Apache%202.0-orange.svg)](https://www.apache.org/licenses/LICENSE-2.0)

> **152 sayfa** · **17 bölüm** · **66 diyagram** · **90 tablo** · **30+ ISO/SAE standardı**

**Web Sitesi:** [nimbustan.github.io/can_bus_guide/tr/](https://nimbustan.github.io/can_bus_guide/tr/index.html)\
**PDF İndir:** [can_bus_technical_guide_tr.pdf](https://nimbustan.github.io/can_bus_guide/tr/can_bus_technical_guide_tr.pdf)\
**İngilizce Versiyon:** [nimbustan.github.io/can_bus_guide/en/](https://nimbustan.github.io/can_bus_guide/en/can_bus_technical_guide_en.pdf)

---

## Hakkında

Bu kılavuz, CAN Bus teknolojisi için kapsamlı, tek belge halinde bir teknik referanstır. Otomotiv mühendisleri, gömülü sistem geliştiricileri, test mühendisleri ve CAN tabanlı iletişim ağlarıyla çalışan herkes için tasarlanmıştır. Kılavuz, fiziksel katman sinyalizasyonundan uygulama katmanı protokollerine, tanılamadan EMC testlerine ve dosya formatlarına kadar tüm CAN ekosistemini kapsar.

Tüm içerik, gerçek dünya uygulama örnekleri, sinyal düzeyinde diyagramlar ve pratik sorun giderme prosedürleri ile birlikte resmi ISO, SAE ve CiA spesifikasyonlarına dayanmaktadır.

## İçindekiler

### Bölüm I — CAN Temelleri (Bölüm 1–5)

| Bölüm | Başlık                             | Sayfa |
|-------|------------------------------------|-------|
| **1** | CAN Bus'a Giriş                    |    6  |
|  1.1  | Tarihçe ve Gelişim                 |    6  |
|  1.2  | OSI Model Eşlemesi                 |    7  |
|  1.3  | CAN Standartlarına Genel Bakış     |    8  |
| **2** | Fiziksel Katman (ISO 11898-2)      |    9  |
|  2.1  | Diferansiyel Sinyalizasyon         |    9  |
|  2.2  | Bus Sonlandırma                    |   10  |
|  2.3  | Alıcı-Verici Özellikleri           |   11  |
| **3** | Veri Bağlantı Katmanı              |   13  |
|  3.1  | Çerçeve Formatları                 |   13  |
|  3.2  | Bit Zamanlama                      |   15  |
|  3.3  | Senkronizasyon                     |   16  |
| **4** | Hata Yönetimi                      |   17  |
|  4.1  | Hata Türleri                       |   17  |
|  4.2  | TEC ve REC Sayaçları               |   18  |
|  4.3  | Bus Durumları                      |   19  |
|  4.4  | Hata Sınırlama ve Bus-Off Kurtarma |   20  |
| **5** | Ağ Topolojisi                      |   23  |
|  5.1  | Bus Kablolama                      |   23  |
|  5.2  | Stub Uzunlukları                   |   24  |
|  5.3  | Kablo Özellikleri                  |   24  |

### Bölüm II — SAE J1939 (Bölüm 6–8)

| Bölüm | Başlık                                   | Sayfa |
|-------|------------------------------------------|-------|
| **6** | SAE J1939 Protokol Yığını                |   26  |
|  6.1  | 29-bit Tanımlayıcı Yapısı                |   26  |
|  6.2  | PGN Yapısı                               |   27  |
|  6.3  | Adres Talep Etme                         |   30  |
|  6.4  | Fiziksel Katman ve Konnektör Özellikleri |   32  |
|  6.5  | J1939 Belge Yapısı ve İlgili Standartlar |   34  |
|  6.6  | J1939 İstek Mekanizması                  |   36  |
|  6.7  | Tanımlama İstekleri                      |   37  |
| **7** | J1939 Taşıma Protokolü                   |   40  |
|  7.1  | TP.CM ve TP.DT                           |   40  |
|  7.2  | BAM Protokolü                            |   41  |
|  7.3  | Çoklu Paket Mesajları                    |   42  |
| **8** | J1939 Tanılama                           |   45  |
|  8.1  | DTC Yapısı                               |   45  |
|  8.2  | SPN-FMI-OC-CM                            |   45  |
|  8.3  | DM Mesajları                             |   47  |

### Bölüm III — Otomotiv Tanılama (Bölüm 9–10)

| Bölüm  | Başlık                                                | Sayfa |
|--------|-------------------------------------------------------|-------|
| **9**  | Otomotiv Tanılama — OBD-II ve UDS                     |   48  |
|  9.1   | OBD-II Protokolü                                      |   48  |
|  9.2   | UDS Protokolü                                         |   50  |
|  9.3   | Protokol Karşılaştırma                                |   57  |
|  9.4   | Tanılama Protokolü Standartları — OSI Katman Eşlemesi |   59  |
|  9.5   | OBDonUDS ve WWH-OBD — Tanılama Protokolü Evrimi       |   60  |
|  9.6   | OBD-II Mesajlaşma Senaryoları                         |   62  |
|  9.7   | J1939 OBD-II Tanılama (Genişletilmiş 29-bit ID'ler)   |   65  |
|  9.8   | UDS Mesajlaşma Senaryoları                            |   67  |
|  9.9   | UDS Hizmetleri                                        |   73  |
|  9.10  | Oturum Kontrolü                                       |   74  |
|  9.11  | Güvenlik Erişimi                                      |   75  |
| **10** | CAN FD ve CAN XL Evrimi                               |   77  |
|  10.1  | CAN FD Özellikleri                                    |   77  |
|  10.2  | CAN XL Özellikleri                                    |   79  |
|  10.3  | Geçiş Konuları                                        |   82  |

### Bölüm IV — Uygulama ve Test (Bölüm 11–13)

| Bölüm  | Başlık                             | Sayfa |
|--------|------------------------------------|-------|
| **11** | EMC Testi ve Kablo Demeti Tasarımı |   83  |
|  11.1  | ISO 11452 Testi                    |   83  |
|  11.2  | ISO 7637 Geçici Darbeler           |   85  |
|  11.3  | Kablo Demeti Tasarım Kuralları     |   86  |
| **12** | Pratik Uygulama                    |   94  |
|  12.1  | Sistem Mimarisi                    |   94  |
|  12.2  | Bus Yükleme Analizi                |   95  |
|  12.3  | Ağ Geçidi Tasarımı                 |   96  |
| **13** | Sorun Giderme                      |   98  |
|  13.1  | Yaygın Hatalar                     |   98  |
|  13.2  | Tanılama Araçları                  |   99  |
|  13.3  | Saha Hata Ayıklama Prosedürü       |  102  |
|  13.4  | En İyi Uygulamalar                 |  105  |

### Bölüm V — İleri Konular (Bölüm 14–17)

| Bölüm  | Başlık                                  | Sayfa |
|--------|-----------------------------------------|-------|
| **14** | CAN FD ile J1939                        |  106  |
|  14.1  | Multi-PG ve Contained PG'ler            |  106  |
|  14.2  | CAN FD Taşıma Protokolü                 |  108  |
|  14.3  | Ağ Yönetimi ve Fonksiyonel Güvenlik     |  110  |
|  14.4  | J1939-76 Fonksiyonel Güvenlik İletişimi |  112  |
| **15** | CANopen Protokolü                       |  115  |
|  15.1  | Mimari ve İletişim Nesneleri            |  118  |
|  15.2  | SDO ve PDO Hizmetleri                   |  120  |
|  15.3  | Nesne Sözlüğü, EDS ve DCF               |  122  |
| **16** | CAN DBC Dosya Formatı                   |  126  |
|  16.1  | DBC Sözdizimi ve Yapısı                 |  126  |
|  16.2  | Sinyal Çözümleme                        |  128  |
|  16.3  | Gelişmiş DBC Özellikleri                |  129  |
| **17** | CAN Bus Veri Kayıt ve Analiz            |  131  |
|  17.1  | CAN Veri Kaydına Giriş                  |  131  |
|  17.2  | CAN Log Dosya Formatları                |  133  |
|  17.3  | ASAM MDF Standardı                      |  136  |
|  17.4  | CAN Kayıt Donanımı                      |  138  |
|  17.5  | Analiz Yazılımı ve Python Ekosistemi    |  141  |
|  17.6  | Python ile Pratik Analiz                |  144  |
|  17.7  | Format Dönüştürme İş Akışları            |  147  |
|        | **Ek A: Referans Tabloları**            |  150  |
|        | **Kaynakça**                            |  152  |

## Detaylı Konu Başlıkları

### CAN Fiziksel Katman
- Diferansiyel sinyalizasyon (CAN_H / CAN_L), baskın/çekinik durumlar
- Bus sonlandırma: 120Ω yerleşimi, bölünmüş sonlandırma, AC sonlandırma
- Alıcı-verici özellikleri (TJA1050, MCP2551, ISO 11898-2 uyumluluğu)
- Sinyal bütünlüğü: yayılma gecikmesi, ortak mod bastırma, ESD koruması

### CAN Veri Bağlantı Katmanı
- Standart (11-bit) ve Genişletilmiş (29-bit) çerçeve formatları
- Bit doldurma, CRC-15/CRC-17/CRC-21 hesaplamaları
- Bit zamanlama: Sync_Seg, Prop_Seg, Phase_Seg1, Phase_Seg2, SJW
- Arbitrasyon: tahribatsız bit düzeyinde arbitrasyon mekanizması

### Hata Yönetimi
- Beş hata türü: bit, doldurma, CRC, form, ACK hataları
- TEC/REC sayaçları ve durum geçişleri
- Error-Active → Error-Passive → Bus-Off durum makinesi
- Bus-Off kurtarma: otomatik ve kontrollü yeniden başlatma stratejileri

### SAE J1939
- 29-bit ID yapısı: öncelik, PGN, kaynak adresi
- PGN kodlama: PDU Format, PDU Specific, Data Page
- Adres talep etme (ISO 11783-5): NAME yapısı, çekişme çözümü
- Deutsch 9-pin/DT06/HD10 konnektör pin dağılımları
- J1939-21 Taşıma Protokolü: RTS/CTS, BAM, zaman aşımı parametreleri
- Tanılama Mesajları: DM1–DM50+, SPN-FMI hata kodu yapısı

### OBD-II ve UDS Tanılama
- OBD-II: ISO 15765-4, fonksiyonel/fiziksel adresleme, Mode/PID yapısı
- UDS (ISO 14229): 26 hizmet, oturum yönetimi, güvenlik erişimi
- OBDonUDS (SAE J1979-2) ve WWH-OBD (ISO 27145) evrim zaman çizelgesi
- Protokol yığını karşılaştırma: OBD-II ve UDS ve J1939
- NRC (Negatif Yanıt Kodu) referansı: açıklamalarıyla 38 kod

### CAN FD ve CAN XL
- CAN FD: esnek veri hızı, 64 bayta kadar veri yükü, BRS/ESI alanları
- CAN XL: 2048 bayta kadar veri yükü, SDU Type, öncelik tabanlı arbitrasyon
- SIC (Sinyal İyileştirme Yeteneği) alıcı-vericiler
- Geçiş konuları: donanım, yazılım, ağ tasarımı

### EMC Testi ve Kablo Demeti Tasarımı
- ISO 11452 radyan bağışıklık test yöntemleri
- ISO 7637 geçici darbe testi (Darbe 1–5)
- Kablo türleri: UTP, STP, çift ekranlı bükümlü çift
- Yönlendirme kuralları: ayrım mesafeleri, bükülme yarıçapları, konnektör seçimi
- Ekran topraklama stratejileri: tek nokta ve çok nokta

### CANopen
- NMT durum makinesi: Başlatma → Ön-operasyonel → Operasyonel → Durduruldu
- SDO transfer modları: Hızlandırılmış, Segmentli, Blok
- PDO iletişimi: olay güdümlü, zamanlayıcı güdümlü, SYNC güdümlü
- Nesne Sözlüğü yapısı: indeks aralıkları, EDS/DCF dosya formatları
- EMCY, SYNC, TIME, Heartbeat protokol nesneleri

### CAN DBC Dosya Formatı
- Mesaj (BO_) ve sinyal (SG_) sözdizimi
- Sinyal çözümleme: ham → fiziksel değer dönüşüm formülü
- Bayt sırası: Intel (küçük-endian) ve Motorola (büyük-endian)
- Sinyal çoğullama, öznitelikler, değer tanımları
- DBC araç ekosistemi: Vector CANdb++, SavvyCAN, python-can

## Diyagramlar ve Şekiller

Kılavuz, 66 özel üretilmiş teknik diyagram içerir:

- CAN çerçeve yapısı diyagramları (Standart, Genişletilmiş, CAN FD, CAN XL)
- Bus topolojisi ve sonlandırma şemaları
- J1939 29-bit ID bit alanı çözümlemeleri
- Taşıma Protokolü sıra diyagramları (RTS/CTS, BAM)
- OBD-II ve UDS mesaj akış senaryoları
- EMC test kurulumu çizimleri
- Konnektör pin dağılım çizimleri (Deutsch 9-pin, M12, OBD-II)
- Protokol yığını karşılaştırma tabloları
- Hata durum makinesi diyagramları
- Kablo kesit ve yan kesit görünümleri

## Referans Alınan Standartlar

| Standart         | Başlık                                              |
|------------------|-----------------------------------------------------|
| ISO 11898-1:2015 | CAN Veri Bağlantı Katmanı ve Fiziksel Sinyalizasyon |
| ISO 11898-2:2016 | CAN Yüksek Hızlı Fiziksel Katman                    |
| ISO 15765-2      | ISO-TP Taşıma Protokolü                             |
| ISO 15765-4      | CAN Üzerinden OBD-II                                |
| ISO 14229        | UDS — Birleşik Tanılama Hizmetleri                  |
| ISO 27145        | WWH-OBD                                             |
| SAE J1939-21     | J1939 Taşıma Protokolü                              |
| SAE J1939-71     | Araç Uygulama Katmanı                               |
| SAE J1939-73     | J1939 Tanılama                                      |
| SAE J1939-76     | Fonksiyonel Güvenlik İletişimi                      |
| SAE J1979-2      | OBDonUDS                                            |
| CiA 301          | CANopen Uygulama Katmanı                            |
| CiA 611          | CAN XL Veri Bağlantı Katmanı                        |
| ISO 11452        | EMC — Radyan Bağışıklık                             |
| ISO 7637         | EMC — Elektriksel Geçici Darbeler                   |

## Nasıl Kullanılır

### Çevrimiçi Okuma
Etkileşimli web sürümü için [nimbustan.github.io/can_bus_guide/tr/](https://nimbustan.github.io/can_bus_guide/tr/) adresini ziyaret edin. Navigasyon kenar çubuğu, tıklanabilir içindekiler tablosu ve duyarlı düzen mevcuttur.

### PDF İndirme
Çevrimdışı okuma, yazdırma veya açıklama ekleme için [PDF sürümünü](https://nimbustan.github.io/can_bus_guide/tr/can_bus_technical_guide_tr.pdf) indirin (152 sayfa).

### İngilizce Edisyon
Kılavuzun tam İngilizce sürümü [nimbustan.github.io/can_bus_guide/en/](https://nimbustan.github.io/can_bus_guide/en/) adresinde mevcuttur.

## Lisans

| İçerik                                                | Lisans                                                                |
|-------------------------------------------------------|-----------------------------------------------------------------------|
| Kılavuz içeriği (metin, diyagramlar, tablolar, düzen) | [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| Kod örnekleri (CAN başlatma, DBC ayrıştırma)          | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)     |

**Kılavuz içeriği (CC BY-NC-SA 4.0):**
- **Paylaş** — materyali herhangi bir ortam veya formatta kopyalayın ve yeniden dağıtın
- **Uyarla** — materyali yeniden karıştırın, dönüştürün ve üzerine inşa edin
- **Atıf** — uygun kredi vermeniz ve değişiklik yapılıp yapılmadığını belirtmeniz gerekir
- **Ticari Olmayan** — materyali ticari amaçlarla kullanamazsınız
- **Aynı Koşullarla Paylaş** — türev eserler aynı lisans altında dağıtılmalıdır

**Kod örnekleri (Apache 2.0):**
- Kendi projelerinizde (ticari dahil) serbestçe kopyalayabilir, değiştirebilir ve kullanabilirsiniz
- Orijinal telif hakkı bildirimini korumanız ve yapılan değişiklikleri belirtmeniz gerekir

## Sorumluluk Reddi

Bu kılavuz eğitim amaçlı hazırlanmıştır. Yazar, bilgilerin doğruluğu veya eksiksizliği konusunda hiçbir garanti vermez. Kod örnekleri öğretim amaçlı basitleştirilmiştir ve üretimde doğrudan kullanılması önerilmez. Yazar, bu kılavuzun kullanımından kaynaklanan herhangi bir zarardan sorumlu tutulamaz.

ISO 11898, ISO 14229, SAE J1939 ve CAN in Automation (CiA) spesifikasyonları referans olarak kullanılmıştır. Tüm ticari markalar ilgili sahiplerine aittir.

## Yazar

**Murat Mecit KAHRAMANLI**

- GitHub: [@nimbustan](https://github.com/nimbustan)
- Proje: [nimbustan.github.io/can_bus_guide](https://nimbustan.github.io/can_bus_guide/)

---

İlk Baskı: Nisan 2026 — Sürüm 1.0

© 2026 Murat Mecit KAHRAMANLI. Tüm hakları saklıdır.
