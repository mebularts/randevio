# Randevio — Klinik Randevu & Yönetim Sistemi 🏥📅

Randevio; klinikler ve sağlık merkezleri için **online randevu** altyapısı, **şube/hekim bazlı planlama** ve **yönetim panelini** tek bir akışta birleştiren PHP tabanlı bir çözümdür.  
Modern arayüz + modüler yaklaşım ile “ihtiyacın kadar aç, ihtiyacın kadar kullan” mantığına uygun ilerler.

---

## 🔗 Hızlı Bağlantılar

- **Demo:** https://randevio.mebularts.com.tr/
- **Admin:** https://randevio.mebularts.com.tr/login.php  
  **admin@admin.com | 123456** *(demo hesabı — üretimde mutlaka değiştirin)*
- **WhatsApp:** https://wa.me/12513160268
- **Telegram:** https://t.me/mebularts

---

## ✨ Öne Çıkanlar

- ✅ **Online randevu akışı:** Şube → Hekim/Branş → Uygun saat → Randevu
- ✅ **Çoklu şube yönetimi:** Şube bazlı iletişim, adres/harita, operasyon düzeni
- ✅ **Hekim & branş planlama:** Program/slot mantığına uygun genişletilebilir yapı
- ✅ **CMS içerik yönetimi:** Anasayfa bölümleri (Hero, Hakkımızda, Hizmetler, SSS vb.) yönetilebilir
- ✅ **Çoklu dil (i18n):** TR/EN/DE/AR gibi diller; aç/kapa yaklaşımı
- ✅ **Rol bazlı erişim & güvenlik:** Yetkilendirme, CSRF koruması, audit yaklaşımı
- ✅ **Modüler mimari:** İhtiyaca göre ödeme/abonelik, envanter, entegrasyon gibi alanlar opsiyonel ilerletilebilir

---

## 🧩 Modüler Yapı (Örnek)

Aşağıdaki liste örnektir; kapsam paketlere göre genişletilebilir:

### 1) Randevu & Klinik Akış
- Randevu yönetimi
- Şube/hekim/branş planlama
- Hasta kayıt / profil
- Bildirim altyapısı (SMS/WhatsApp) *(opsiyonel)*

### 2) Ödeme & Abonelik *(opsiyonel)*
- Sağlayıcı seçimi: **Stripe / iyzico / PayTR**
- Paket/abonelik mantığı (aylık/3-6-12) *(opsiyonel)*
- Webhook + ödeme doğrulama *(opsiyonel)*

### 3) Stok & Envanter *(opsiyonel)*
- Sarf/ürün stok takibi
- Depo/şube bazlı hareketler
- Raporlama & uyarılar

### 4) Entegrasyonlar
- Harita / yol tarifi
- E-posta bildirimleri
- e-Nabız *(opsiyonel)*
- Kurumsal ihtiyaçlara göre özel API entegrasyonları

---

## 🧪 Demo Kullanım Notları

- Demo ortamı inceleme amaçlıdır. **Gerçek kişisel veri girmeyin.**
- Admin hesabı herkese açık olduğundan üretim mantığında değerlendirmeyin.
- Üretim kullanımında şifreler ve kritik ayarlar mutlaka özelleştirilmelidir.

---

## 📦 Satın Alma, Teslimat & Kurulum

- 💰 **Kampanya Fiyatı:** ~~6.000₺~~ **3.500₺**
- 📦 **Teslimat:** Satın alım sonrası **tam kaynak kod + kurulum dokümantasyonu + temel yönergeler/örnekler** teslim edilir.
- 🔧 **Kurulum Hizmeti (Opsiyonel):** **+600₺**  
  *(Sunucuya kurulum, DB import, temel ayarlar, yayına alma kontrolü.)*

> Özelleştirme talepleri (tema/renk/logo, yeni modül, entegrasyon, raporlar) ihtiyaç analizine göre ayrıca planlanır.

---

## 🛠️ Teknik Gereksinimler (Genel)

Bu bölüm, kurulum teslimat paketindeki dokümantasyonla birlikte netleştirilir:

- PHP **8.0+**
- MySQL **5.7+ / 8.0+**
- Apache veya Nginx
- HTTPS önerilir (özellikle admin paneli için)

---

## 🔒 Güvenlik Önerileri

- ✅ Admin şifresini ilk iş değiştirin
- ✅ HTTPS aktif edin
- ✅ Yedekleme planı oluşturun (DB + uploads)
- ✅ Rol/yetki yapısını üretim kullanımına göre yapılandırın

---

## 📣 İletişim

Teklif, kurulum veya demo ile ilgili sorular için:

- WhatsApp: https://wa.me/12513160268
- Telegram: https://t.me/mebularts

---

## 📄 Lisans / Kullanım

**Kaynak kod, satın alan kişiye teslim edilir** ve kullanım koşulları teslimat sırasında netleştirilir.

—  
**mebularts**
