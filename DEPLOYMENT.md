# 🚀 GitHub Pages Deployment Rehberi

## Adım 1: Repository Oluşturma
1. GitHub'da yeni repository oluşturun
2. Repository adını `marry-me` veya istediğiniz bir isim yapın
3. **Public** olarak ayarlayın (GitHub Pages ücretsiz kullanım için)

## Adım 2: Dosyaları Yükleme
```bash
git init
git add .
git commit -m "Initial commit: Marriage proposal website"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git
git push -u origin main
```

## Adım 3: GitHub Pages Aktifleştirme
1. Repository sayfasında **Settings** sekmesine gidin
2. Sol menüden **Pages** seçin
3. **Source** kısmında **GitHub Actions** seçin
4. Otomatik deployment başlayacak!

## Adım 4: Site URL'ini Alma
- Site URL'i: `https://KULLANICI_ADINIZ.github.io/REPO_ADINIZ/`
- 5-10 dakika içinde aktif olacak

## 🎨 Kişiselleştirme Önerileri

### Fotoğrafları Ekleme
1. Repository'ye `foto1.jpg`, `foto2.jpg`, `foto3.jpg` dosyalarını ekleyin
2. `jariya.html` dosyasında placeholder'ları güncelleyin:
```html
<!-- Bu satırları bulun ve değiştirin -->
<div class="photo-placeholder">
    📷<br>@l10n Our Photo<br>Together
</div>

<!-- Bu şekilde değiştirin -->
<img src="foto1.jpg" alt="Our beautiful memory">
```

### Mesajları Kişiselleştirme
`@l10n` yazan her yeri kendi dilinizde yazın:
- `@l10n My love` → `Aşkım`
- `@l10n YES, I DO!` → `EVET, KABUL EDİYORUM!`
- `@l10n Thank you!` → `Teşekkür ederim!`

### Tarihi Güncelleme
`jariya.html` dosyasında:
```html
<div class="date">
    11 @l10n October 2025 - Ankara
</div>
```

## 🔧 Gelişmiş Özellikler

### Özel Domain Kullanma
1. `CNAME` dosyasını düzenleyin
2. Domain'inizi yazın: `marry-me.yourname.com`
3. Domain sağlayıcınızda GitHub Pages'a yönlendirin

### Google Analytics Ekleme
```html
<!-- jariya.html head kısmına ekleyin -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📱 Test Etme
- Masaüstü browser'da test edin
- Mobil cihazda test edin
- Farklı browser'larda kontrol edin
- Network yavaş olduğunda da test edin

## 🎉 Son Adımlar
1. URL'i eşinizle paylaşın
2. Özel bir zamanda gösterin
3. Hayırlı olsun! 💖

---

**İpucu:** Surprise faktörü için URL'i kısaltın: bit.ly, tinyurl.com gibi servisler kullanabilirsiniz!