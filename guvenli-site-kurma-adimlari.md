# Yeni Başlayanlar İçin Güvenli Web Sitesi Kurma Adımları

Bu doküman, sıfırdan bir web sitesi kurarken
**en temel güvenlik önlemlerini doğru sırayla** anlatır.

---

## 1️⃣ Güvenli Hosting Seçimi

- Güvenilir ve bilinen firmalar tercih edilmelidir
- Otomatik güncelleme ve yedekleme sunması avantajdır
- SSL sertifikası ücretsiz sunuluyorsa tercih edilmelidir

---

## 2️⃣ SSL (HTTPS) Kurulumu

- Site mutlaka HTTPS üzerinden yayınlanmalıdır
- SSL sertifikası kurulduktan sonra:
  - HTTP istekleri HTTPS’e yönlendirilmelidir

📌 Kullanıcı güveni ve SEO açısından da önemlidir.

---

## 3️⃣ Güçlü Admin Girişi Oluşturma

- Admin kullanıcı adı `admin` olmamalıdır
- En az 10–12 karakterli şifreler kullanılmalıdır
- Harf, rakam ve özel karakter içermelidir

---

## 4️⃣ Admin Panelini Korumak

- Admin panel URL’si gizlenebilir
- IP kısıtlaması uygulanabilir
- CAPTCHA ve giriş deneme limiti eklenmelidir

---

## 5️⃣ Kullanıcı Girdilerini Kontrol Etme

- Formlardan gelen veriler mutlaka filtrelenmelidir
- Direkt veritabanına yazılmamalıdır
- HTML ve JavaScript enjeksiyonlarına dikkat edilmelidir

---

## 6️⃣ Dosya ve Klasör Güvenliği

- Gereksiz dosyalar sunucuda tutulmamalıdır
- `.env` gibi dosyalar dış erişime kapalı olmalıdır
- Upload klasörleri kontrol altında tutulmalıdır

---

## 7️⃣ Güncellemeleri İhmal Etmeme

- CMS kullanılıyorsa (WordPress vb.) düzenli güncelleme yapılmalıdır
- Eklenti ve temalar güncel tutulmalıdır

📌 Güncellenmeyen sistemler saldırılara açıktır.

---

## 8️⃣ Düzenli Yedekleme Alışkanlığı

- Haftalık veya günlük yedek alınmalıdır
- Yedekler farklı bir ortamda saklanmalıdır
- Yedekten geri dönme test edilmelidir

---

## 🎯 Sonuç

Güvenli bir web sitesi:
- Tek seferlik değil
- Sürekli kontrol ve güncelleme gerektirir

Temel önlemler, büyük riskleri engelleyebilir.
