# 🔧 Tekno Çözüm

**Telefon ve Bilgisayar Sorunlarınıza Hızlı ve Pratik Çözümler**

Teknoloji kullanıcılarının karşılaştığı yaygın sorunlara adım adım çözümler sunan bilgilendirici bir web sitesi.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/KULLANICI_ADINIZ/tekno-cozum)

## 🌟 Özellikler

- ✅ **12 Farklı Sorun Çözümü** (6 telefon + 6 bilgisayar)
- ✅ **Adım Adım Rehberler** - Her sorun için detaylı çözüm adımları
- ✅ **Arama Fonksiyonu** - Sorunları hızlıca bulun
- ✅ **Mobil Uyumlu** - Responsive tasarım
- ✅ **SEO Optimizasyonlu** - Google'da üst sıralarda çıkmak için optimize edildi
- ✅ **Google AdSense Hazır** - Reklam geliri için hazır altyapı
- ✅ **Hızlı ve Hafif** - Vanilla JavaScript, framework yok
- ✅ **Cookie Consent** - GDPR uyumlu çerez bildirimi
- ✅ **Gizlilik Politikası** - AdSense için gerekli yasal sayfalar

## 📱 İçerik Kategorileri

### Telefon Sorunları
1. Telefon Açılmıyor
2. Batarya Hızlı Bitiyor
3. Uygulama Çöküyor
4. Wi-Fi Bağlantı Sorunu
5. Depolama Alanı Dolu
6. Ses Gelmiyor

### Bilgisayar Sorunları
1. Bilgisayar Yavaş Çalışıyor
2. Mavi Ekran Hatası (BSOD)
3. İnternet Bağlantı Sorunu
4. Ekran Görüntüsü Alınamıyor
5. Ses Gelmiyor (PC)
6. USB Tanınmıyor

## 🚀 Canlı Demo

Site yayında: [https://tekno-cozum.vercel.app](https://tekno-cozum.vercel.app)
*(URL'yi kendi domain'inizle güncelleyin)*

## 💻 Teknolojiler

- **HTML5** - Semantik yapı
- **CSS3** - Modern, responsive tasarım
- **JavaScript (Vanilla)** - Framework gerektirmez
- **Vercel** - Hosting ve deployment
- **Google AdSense** - Reklam sistemi (opsiyonel)

## 📦 Kurulum

### 1. Projeyi İndirin

```bash
git clone https://github.com/KULLANICI_ADINIZ/tekno-cozum.git
cd tekno-cozum
```

### 2. Tarayıcıda Açın

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Veya bir yerel sunucu başlatın:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# VS Code Live Server extension
```

Tarayıcıda açın: `http://localhost:8000`

## 🌐 Vercel'e Deploy Etme

### Yöntem 1: Vercel Dashboard (Önerilen)

1. [Vercel](https://vercel.com) hesabı oluşturun
2. "New Project" tıklayın
3. GitHub repository'nizi bağlayın
4. "Deploy" butonuna tıklayın
5. Bitti! 🎉

### Yöntem 2: Vercel CLI

```bash
# Vercel CLI'yi kurun
npm install -g vercel

# Giriş yapın
vercel login

# Deploy edin
vercel

# Production'a deploy
vercel --prod
```

Detaylı rehber için: [VERCEL_DEPLOY.md](VERCEL_DEPLOY.md)

## 💰 Google AdSense Entegrasyonu

Site, Google AdSense için tamamen hazır!

### AdSense Başvurusu İçin:

1. ✅ Kaliteli, orijinal içerik (✓)
2. ✅ Gizlilik politikası sayfası (✓)
3. ✅ İletişim sayfası (✓)
4. ✅ Hakkımızda sayfası (✓)
5. ✅ Mobil uyumlu tasarım (✓)
6. ✅ HTTPS (Vercel otomatik sağlar) (✓)

### AdSense Kodunu Ekleme:

1. Google AdSense'ten onay alın
2. `index.html` dosyasındaki satır 28'i güncelleyin:

```html
<!-- Yorum satırını kaldırın ve kendi kodunuzu ekleyin -->
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

3. `ads.txt` dosyasını güncelleyin:

```
google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0
```

Detaylı rehber için: [ADSENSE_REHBER.md](ADSENSE_REHBER.md)

## 📂 Proje Yapısı

```
tekno-cozum/
│
├── index.html              # Ana sayfa
├── css/
│   └── style.css           # Tüm stiller
├── js/
│   └── app.js             # JavaScript fonksiyonları
├── images/                 # Görseller (opsiyonel)
│
├── robots.txt             # SEO - Arama motorları için
├── sitemap.xml            # SEO - Site haritası
├── ads.txt                # AdSense doğrulama
├── vercel.json            # Vercel yapılandırması
├── .vercelignore          # Vercel'e yüklenmeyecek dosyalar
│
├── README.md              # Bu dosya
├── ADSENSE_REHBER.md      # AdSense başvuru rehberi
├── VERCEL_DEPLOY.md       # Detaylı deployment rehberi
└── deploy-github.ps1      # GitHub'a yükleme scripti (Windows)
```

## 🎨 Özelleştirme

### Renkleri Değiştirme

`css/style.css` dosyasında ana renkleri değiştirin:

```css
/* Ana renkler */
--primary-color: #3498db;    /* Mavi */
--secondary-color: #2c3e50;  /* Koyu gri */
--accent-color: #e74c3c;     /* Kırmızı */
```

### Yeni İçerik Ekleme

`js/app.js` dosyasındaki `problems` objesine yeni sorunlar ekleyin:

```javascript
const problems = {
    phone: [
        {
            title: "Yeni Sorun",
            description: "Sorun açıklaması",
            solution: `<h3>Çözüm Adımları</h3>...`
        }
    ]
};
```

## 📊 SEO İyileştirmeleri

- ✅ Meta açıklamalar
- ✅ Semantik HTML5 etiketleri
- ✅ Sitemap.xml
- ✅ Robots.txt
- ✅ Open Graph etiketleri (sosyal medya paylaşımları için)
- ✅ Mobil uyumlu
- ✅ Hızlı yükleme süresi

## 🔒 Gizlilik ve Güvenlik

- ✅ GDPR uyumlu gizlilik politikası
- ✅ Cookie consent banner
- ✅ LocalStorage kullanımı (çerez tercihleri için)
- ✅ Güvenli dış linkler (`rel="noopener"`)
- ✅ HTTPS (Vercel tarafından sağlanır)

## 📈 Analytics

### Google Analytics Ekleme (Opsiyonel)

`index.html` dosyasının `<head>` bölümüne ekleyin:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! 

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin yeni-ozellik`)
5. Pull Request oluşturun

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 📞 İletişim

- **Website**: https://tekno-cozum.vercel.app
- **Email**: info@teknocozum.com
- **GitHub**: https://github.com/KULLANICI_ADINIZ/tekno-cozum

## ⭐ Destek

Projeyi beğendiyseniz yıldız vermeyi unutmayın! ⭐

---

## 📚 İlgili Kaynaklar

- [Google AdSense Başvuru Rehberi](ADSENSE_REHBER.md)
- [Vercel Deployment Rehberi](VERCEL_DEPLOY.md)
- [Vercel Docs](https://vercel.com/docs)
- [Google AdSense Politikaları](https://support.google.com/adsense/answer/48182)

---

**Made with ❤️ for Turkish tech users**

*Son Güncelleme: 1 Şubat 2026*
