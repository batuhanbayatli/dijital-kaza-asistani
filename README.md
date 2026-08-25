# 🚗 Dijital Kaza Asistanı // Akıllı Triyaj & Hasar Bildirim Motoru
> **bGroup // SigortamRahat × DATEX Tasarım**  
> *Sigorta Acenteleri İçin Serverless, KVKK Dostu, Canlı GPS Konum ve Fotoğraf Entegrasyonlu Mobil Kaza Rehberi*

<p align="left">
  <a href="https://dijital-kaza-asistani.vercel.app/"><img src="https://img.shields.io/badge/Canlı%20Demo-Vercel-2563eb?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Canlı Demo"></a>
  <img src="https://img.shields.io/badge/Ecosystem-bGroup-0f172a?style=for-the-badge" alt="bGroup">
  <img src="https://img.shields.io/badge/Partners-SigortamRahat%20%C3%97%20DATEX-2563eb?style=for-the-badge" alt="Marka İş Birliği">
  <img src="https://img.shields.io/badge/Architecture-Serverless%20%2F%20SPA-059669?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/License-MIT-10b981?style=for-the-badge" alt="License">
</p>

---

## 📌 Proje Özeti

**Dijital Kaza Asistanı**, trafik kazası anında müşterilerin yaşadığı panik ortamında hak kaybı yaşamalarını önlemek, süreci adım adım yönlendirmek ve eksiksiz hasar verisini acenteye ulaştırmak için geliştirilmiş **sunucusuz (Serverless & Client-Side)** bir mobil web uygulamasıdır[cite: 1, 3].

Uygulama; can güvenliği triyajından başlayarak çevre güvenliği, kamera ile olay yeri fotoğraflama, interaktif kaza tutanağı doldurma rehberi ve tek tıkla canlı GPS koordinatlı WhatsApp hasar bildirimi süreçlerini sıfır veri kaybıyla yürütür[cite: 3].

---

## ✨ Öne Çıkan Özellikler

* 🚑 **Acil Durum & Can Güvenliği Triyajı:** Kazazedeyi sakinleştirir; yaralanma durumunda doğrudan 112 Acil Yardım hattını aratır.
* 📸 **Entegre Kamera Erişimi:** Web tarayıcısı üzerinden doğrudan arka kamerayı tetikleyerek plaka, fren izi ve 4 köşe fotoğraflarının doğru çekilmesini sağlar[cite: 3].
* 📝 **İnteraktif Tutanak Rehberi (Modal):** Sayfa yenilenmeden açılan rehber; polis çağrılması gereken istisnai halleri ve örnek doldurulmuş tutanak görselini (`ornek.jpg`) barındırır[cite: 2, 3].
* 📍 **Canlı Geolocation & WhatsApp Köprüsü:** Tek tuşla kazanın gerçekleştiği enlem ve boylamı Google Maps bağlantısına çevirip acentenin WhatsApp hattına iletir[cite: 3].
* 🔒 **%100 KVKK & Gizlilik Uyumlu (Serverless):** Hiçbir veritabanı kaydı tutulmaz. Tüm işlemler istemci cihazında gerçekleşir[cite: 1, 3].
* 🔗 **Acente Link Üretici (`olustur.html`):** Acentelerin kayıt olmadan sadece telefon numaralarını girerek kendilerine özel bağlantı üretmelerine olanak tanır[cite: 2, 3].

---

## 🛠️ Teknoloji Yığını

* **Arayüz / Tasarım:** Mobile-First Responsive HTML5, Tailwind CSS[cite: 3]
* **İkonografi:** Lucide Icons CDN
* **Web API'leri:** Geolocation API (GPS), HTML5 Media Capture API (`capture="environment"`), URLSearchParams[cite: 3]
* **Mantık & Triyaj Motoru:** Vanilla ES6+ JavaScript (State-in-URL mimarisi)[cite: 3]
* **Dağıtım / CI-CD:** Vercel Edge Network

---

## 🚀 Yerel Kurulum ve Çalıştırma

```bash
# Repoyu klonlayın
git clone [https://github.com/batuhanbayatli/dijital-kaza-asistani.git](https://github.com/batuhanbayatli/dijital-kaza-asistani.git)

# Proje dizinine geçin
cd dijital-kaza-asistani

# index.html veya olustur.html dosyasını tarayıcınızda açın!
