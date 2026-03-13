# 🛒 Tusi Yerli E-Ticaret Sitesi

Bu proje, tamamen **Tusi Programlama Dili** kullanılarak geliştirilmiş, yerli ve milli bir e-ticaret platformu örneğidir.

## ✨ Özellikler

- **Dinamik Ürün Listeleme:** `vt_oku` ile veritabanından ürün çekme.
- **Sipariş Sistemi:** Kullanıcı işlemleri anlık olarak `siparisler.json` dosyasına kaydedilir.
- **Yönetim Paneli:** `/admin` rotası üzerinden gelen siparişleri takip etme.
- **Modern Arayüz:** Gömülü CSS ile temiz ve şık bir kullanıcı deneyimi.
- **Güvenli Çekirdek:** Tusi'nin sandbox korumasıyla güçlendirilmiş altyapı.

## 🚀 Çalıştırma

1. `tusi.exe` veya `node tusi.js` kullanarak projeyi başlatın:
   ```bash
   .\tusi.bat site.tusi
   ```
2. Tarayıcıdan şu adrese gidin:
   👉 **http://localhost:8080**

## 🏗️ Mimari

- **Dil:** Tusi v3.0
- **Veritabanı:** JSON tabanlı TusiDB
- **Web Motoru:** Tusi HTTP Engine

---
*Tusi - Algoritmik Bağımsızlık Yolunda.*
