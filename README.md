
# 🌤️ n8n ile Günlük Hava Durumu Telegram Otomasyonu

## 📌 Proje Hakkında

Bu proje, n8n otomasyon platformu kullanılarak geliştirilmiş bir hava durumu bilgilendirme sistemidir.

Sistem, Antalya'nın günlük hava durumu bilgilerini Telegram botu aracılığıyla kullanıcıya otomatik olarak iletir.

## 🎯 Projenin Amacı

Hava durumu bilgilerine kolay ve hızlı erişim sağlamak, günlük bilgilendirme işlemini otomatik hâle getirmek.

## ⚙️ Kullanılan Teknolojiler

- n8n: İş akışı ve otomasyon platformu
- Telegram Bot: Mesaj gönderimi
- Open-Meteo API: Hava durumu verilerinin alınması
- HTTP Request: API bağlantısı
- JavaScript: Verilerin düzenlenmesi

## 🔄 Sistemin Çalışma Mantığı

1. Her gün saat 09.00'da otomasyon tetiklenir.
2. API üzerinden hava durumu bilgileri alınır.
3. Gelen veriler düzenlenir.
4. Hazırlanan mesaj Telegram botu üzerinden gönderilir.
5. Kullanıcı Telegram botuna "hava durumu" yazarak anlık bilgi talep edebilir.

## 📁 Proje Dosyaları

- `workflow.json`: n8n otomasyonunun dışa aktarılan dosyası.
- `proje-raporu.docx`: Projenin detaylı açıklamasını içeren rapor.

## 👨‍💻 Sonuç

Bu proje sayesinde n8n kullanılarak zamanlanmış görevler, API bağlantıları ve Telegram entegrasyonu uygulamalı olarak gerçekleştirilmiştir.
