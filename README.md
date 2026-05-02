# ⚡ Pxelight Futures Simulator

<p align="center">
  <img src="https://img.shields.io/github/license/pxelight/pxelight.github.io?style=for-the-badge&color=blue" alt="License">
  <img src="https://img.shields.io/github/stars/pxelight/pxelight.github.io?style=for-the-badge&color=gold" alt="Stars">
  <img src="https://img.shields.io/github/last-commit/pxelight/pxelight.github.io?style=for-the-badge&color=orange" alt="Last Commit">
</p>

**Pxelight Futures**, kripto para vadeli işlemlerini (futures) gerçek zamanlı piyasa verileriyle deneyimlemek isteyenler için tasarlanmış, tarayıcı tabanlı ve tamamen ücretsiz bir **eğitim simülatörüdür.**

🔗 **Canlı Önizleme:** [pxelight.github.io](https://pxelight.github.io)

---

## 🎯 Projenin Amacı
Kaldıraçlı işlemler, yüksek risk içeren ve öğrenme süreci maliyetli olan bir alandır. Bu proje, kullanıcılara **gerçek para kaybetme riski olmadan**:
- Vadeli işlem terminolojisini (Leverage, Margin, Liquidation, Funding) öğrenme,
- Teknik analiz stratejilerini gerçek zamanlı verilerle test etme,
- Piyasa psikolojisini ve risk yönetimini deneyimleme imkanı sunar.

---

## ✨ Temel Özellikler

- 📉 **Gerçek Zamanlı Veri:** Binance WebSocket API aracılığıyla anlık fiyat ve emir defteri (Order Book) akışı.
- 📊 **Gelişmiş Grafikler:** TradingView kütüphanesi ile kapsamlı teknik analiz araçları.
- ⚙️ **Esnek İşlem Modları:**
    - **İzole & Çapraz (Isolated/Cross)** marjin seçenekleri.
    - **1x - 125x** arası ayarlanabilir kaldıraç.
    - **Limit, Market ve Stop-Limit** emir türleri.
- 📱 **PWA Desteği:** Mobil cihazlara uygulama olarak yüklenebilir (Progressive Web App).
- 🔒 **Gizlilik Odaklı:** Tüm işlemler tarayıcı taraflı (localStorage) çalışır; kişisel veri toplanmaz.

---

## 🛠️ Teknik Altyapı

Bu proje modern web teknolojileri ve finansal API'lar kullanılarak inşa edilmiştir:

- **Frontend:** HTML5, CSS3 (Modern UI/UX), Vanilla JavaScript.
- **Veri Kaynağı:** [Binance API](https://binance-docs.github.io/apidocs/futures/en/) (Fiyat & Depth verileri).
- **Grafik Motoru:** TradingView Lightweight Charts / Widget.
- **Hosting:** GitHub Pages.

---

## 🚀 Yerel Kurulum

Projeyi kendi yerel ortamınızda çalıştırmak isterseniz:

1. Depoyu klonlayın:
   ```bash
   git clone [https://github.com/pxelight/pxelight.github.io.git](https://github.com/pxelight/pxelight.github.io.git)
Proje dizinine gidin:

Bash
cd pxelight.github.io
Herhangi bir yerel sunucu (Live Server vb.) ile index.html dosyasını çalıştırın.

⚠️ Yasal Uyarı
Bu platform yalnızca eğitim amaçlıdır. İçerisinde kullanılan bakiyeler sanaldır ve gerçek finansal değeri yoktur. Burada yapılan işlemler yatırım tavsiyesi niteliği taşımaz.

📫 İletişim & Geri Bildirim
Herhangi bir hata bildirimi veya özellik önerisi için:

E-posta: pxelight@gmail.com

GitHub: @pxelight

© 2026 Pxelight Futures, All Rights Reserved.
