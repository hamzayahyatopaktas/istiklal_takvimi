# İstiklal Takvimi 📅

**Hicri & Rumi Takvim Editörü** — Progressive Web App (PWA)

> Telefona kurulabilir, çevrimdışı çalışan, APK'ya gerek duymayan web uygulaması.

---

## 🚀 GitHub'a Yükleme ve Yayınlama

### 1. Yeni GitHub Repo Oluştur

1. [github.com/new](https://github.com/new) adresine git
2. Repository adı: `istiklal-takvimi`
3. **Public** seç
4. **Create repository** tıkla

### 2. Dosyaları Yükle

```bash
git init
git add .
git commit -m "İlk yükleme"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/istiklal-takvimi.git
git push -u origin main
```

### 3. GitHub Pages Aç

1. Repo → **Settings** → **Pages**
2. **Source**: `GitHub Actions` seç
3. Otomatik deploy başlar (~1-2 dk)
4. Adresin: `https://KULLANICI_ADIN.github.io/istiklal-takvimi`

---

## 📱 Telefona Kurma (APK Gerekmez!)

### Android (Chrome)
1. Siteyi Chrome'da aç
2. Sağ üst **⋮** → **"Ana ekrana ekle"**
3. **"Yükle"** tıkla → App gibi çalışır ✅

### iOS (Safari)
1. Siteyi Safari'de aç
2. Alt orta **Paylaş** butonu (□↑)
3. **"Ana Ekrana Ekle"**
4. **Ekle** tıkla ✅

### Masaüstü (Chrome/Edge)
1. Adres çubuğunun sağındaki **yükle** ikonuna tıkla
2. Veya **⋮** → **"İstiklal Takvimi'ni yükle"** ✅

---

## ✨ Özellikler

- 🌙 Ay Fazları entegrasyonu (moonphases.co.uk)
- ↩ Geri al (Ctrl+Z)
- 🖋 MaArifRika font (gömülü)
- 📷 Fotoğraf / görsel ekleme
- 🎨 Arka plan & renk özelleştirme
- 💾 PNG olarak dışa aktarma
- 📶 **Çevrimdışı çalışır** (Service Worker)
- 📱 Mobil & masaüstü uyumlu

---

## 📁 Dosya Yapısı

```
istiklal-takvimi/
├── index.html          ← Ana uygulama
├── manifest.json       ← PWA manifest (kurulum bilgisi)
├── sw.js               ← Service Worker (çevrimdışı)
├── maArifRika-Regular.ttf
├── icons/              ← Tüm ikon boyutları
│   ├── icon-192x192.png
│   ├── icon-512x512.png
│   ├── apple-touch-icon.png
│   └── ...
└── .github/
    └── workflows/
        └── deploy.yml  ← Otomatik GitHub Pages deploy
```

---

## 🔧 Yerel Test

```bash
# Python ile basit sunucu
python3 -m http.server 8080
# Sonra: http://localhost:8080
```
