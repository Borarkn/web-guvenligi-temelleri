# Web Güvenliği Kontrol Listesi

Bu kontrol listesi, bir web sitesinin temel güvenlik önlemlerini
kontrol etmek ve eksikleri tespit etmek amacıyla hazırlanmıştır.

Yeni başlayanlar için **rehber**, geliştiriciler için **hatırlatma** niteliğindedir.

---

## ✅ Sunucu & Altyapı Güvenliği

- [ ] Sunucu işletim sistemi güncel mi?
- [ ] Kullanılmayan servisler kapatıldı mı?
- [ ] Varsayılan kullanıcı adları değiştirildi mi?
- [ ] Sunucuya root erişimi sınırlandırıldı mı?

📌 **Neden önemli?**  
Güncel olmayan sistemler bilinen açıklar nedeniyle kolay hedef haline gelir.

---

## 🔑 Kimlik Doğrulama & Şifreleme

- [ ] Güçlü şifre politikası uygulanıyor mu?
- [ ] Şifreler veritabanında hash’li şekilde saklanıyor mu?
- [ ] Admin girişleri için 2FA var mı?
- [ ] Giriş deneme sayısı sınırlandırıldı mı?

📌 **Zayıf şifreler**, en yaygın saldırı sebeplerinden biridir.

---

## 🔐 HTTPS & Veri Güvenliği

- [ ] SSL sertifikası aktif mi?
- [ ] HTTP → HTTPS yönlendirmesi var mı?
- [ ] Kullanıcı verileri şifreli iletiliyor mu?

📌 **HTTPS olmayan sitelerde** kullanıcı bilgileri dinlenebilir.

---

## 🛑 Girdi Kontrolleri

- [ ] Kullanıcıdan alınan veriler filtreleniyor mu?
- [ ] SQL Injection’a karşı önlem var mı?
- [ ] XSS saldırılarına karşı çıktı temizleniyor mu?

📌 Kullanıcıdan gelen her veri **potansiyel tehdit** olarak görülmelidir.

---

## 👤 Yetkilendirme Kontrolleri

- [ ] Kullanıcı rolleri net tanımlandı mı?
- [ ] Yetkisiz sayfalara erişim engellendi mi?
- [ ] Admin sayfaları gizlendi mi?

📌 Yetkisiz erişim, veri sızıntısına yol açabilir.

---

## 🧾 Loglama & İzleme

- [ ] Hatalar loglanıyor mu?
- [ ] Şüpheli girişler takip ediliyor mu?
- [ ] Log dosyaları dış erişime kapalı mı?

📌 Saldırı sonrası analiz için loglar kritik öneme sahiptir.

---

## 💾 Yedekleme

- [ ] Düzenli yedek alınıyor mu?
- [ ] Yedekler farklı bir ortamda saklanıyor mu?
- [ ] Yedeklerin geri yükleme testi yapıldı mı?

📌 Yedek yoksa, güvenlik de yoktur.
