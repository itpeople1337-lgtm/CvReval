# CV Ahmad Revaldi Saputra 🚀

CV digital modern dengan animasi canggih, particles effect, dan fitur interaktif yang siap untuk di-deploy ke GitHub Pages.

## 🚀 Live Demo

Setelah di-deploy, CV akan dapat diakses di: `https://itpeople1337-lgtm.github.io/[nama-repository]`

## ✨ Fitur Unggulan

### 🎨 Desain & Animasi
- ✨ Desain ultra-modern dengan gradient background
- 🌟 **Particles.js** - Animated particle background yang interaktif
- 🎭 **AOS (Animate On Scroll)** - Smooth scroll animations
- 💫 Floating profile image animation
- 🎯 Hover effects pada semua elemen
- 📊 Progress bar saat scroll
- ⬆️ Scroll to top button dengan smooth animation

### 📱 Responsive & Performance
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading dengan optimized assets
- 🖨️ Print-friendly untuk export PDF
- 🔍 SEO optimized

### 💼 Konten
- 👤 Profil dengan informasi kontak
- 🎓 Pendidikan SMKN 12 Malang (PPLG 2023-2026)
- 💼 Pengalaman magang di Cendana Teknika & Rakryan
- 💻 Keahlian: Flutter Dev, Android Studio, Web Dev
- 🎯 Tech stack dengan interactive tags
- 🌟 Soft skills showcase
- 📁 **Portfolio section** dengan gambar project
- 🎥 **Video showcase** untuk demo aplikasi
- 📊 **GitHub Stats** real-time dari profile GitHub
- 🔗 Link ke GitHub: https://github.com/itpeople1337-lgtm

## 🛠️ Cara Deploy ke GitHub Pages

### Langkah 1: Buat Repository Baru di GitHub

1. Login ke GitHub
2. Klik tombol **"+"** di pojok kanan atas, pilih **"New repository"**
3. Beri nama repository (contoh: `cv-portfolio` atau `my-cv`)
4. Pilih **Public**
5. Klik **"Create repository"**

### Langkah 2: Upload File ke Repository

**Opsi A: Via GitHub Web Interface (Mudah)**

1. Di halaman repository baru, klik **"uploading an existing file"**
2. Drag & drop atau pilih file:
   - `index.html`
   - `style.css`
   - `README.md`
3. Scroll ke bawah, klik **"Commit changes"**

**Opsi B: Via Git Command Line**

```bash
# Inisialisasi git di folder project
git init

# Tambahkan semua file
git add .

# Commit file
git commit -m "Initial commit: Add CV"

# Tambahkan remote repository (ganti dengan URL repository kamu)
git remote add origin https://github.com/[username]/[nama-repository].git

# Push ke GitHub
git branch -M main
git push -u origin main
```

### Langkah 3: Aktifkan GitHub Pages

1. Di repository GitHub, klik tab **"Settings"**
2. Scroll ke bawah, klik **"Pages"** di menu sebelah kiri
3. Di bagian **"Source"**, pilih:
   - Branch: **main**
   - Folder: **/ (root)**
4. Klik **"Save"**
5. Tunggu beberapa menit, refresh halaman
6. Link CV kamu akan muncul di bagian atas: `https://[username].github.io/[nama-repository]`

## ✏️ Cara Edit CV

### Edit Informasi Pribadi

Buka file `index.html` dan edit bagian berikut:

```html
<!-- Nama dan Title -->
<h1>Ahmad Revaldi Saputra</h1>
<p class="title">Flutter & Web Developer</p>

<!-- Kontak -->
<span>ahmadrevaldi@email.com</span>
<span>+62 xxx xxxx xxxx</span>
<a href="https://github.com/itpeople1337-lgtm" target="_blank" rel="noopener noreferrer" class="contact-link">
    github.com/itpeople1337-lgtm
</a>
```

### Edit Portfolio Projects

Ganti URL gambar dan deskripsi project:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <img src="URL_GAMBAR_KAMU" alt="Project Name">
        <div class="portfolio-overlay">
            <h4>Nama Project</h4>
            <p>Deskripsi singkat project</p>
            <div class="portfolio-tags">
                <span>Tech1</span>
                <span>Tech2</span>
            </div>
        </div>
    </div>
</div>
```

### Edit Video Showcase

Ganti YouTube video ID:

```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID_KAMU"></iframe>
```

### Edit GitHub Stats

Username sudah otomatis menggunakan `itpeople1337-lgtm`. Jika ingin ganti theme:

```html
<!-- Theme options: dark, radical, merko, gruvbox, tokyonight, onedark, cobalt, synthwave, etc -->
<img src="https://github-readme-stats.vercel.app/api?username=itpeople1337-lgtm&show_icons=true&theme=tokyonight">
```

### Edit Pengalaman Magang

Cari section dengan class `timeline-item` dan edit sesuai kebutuhan:

```html
<div class="timeline-item">
    <div class="timeline-header">
        <h3>Nama Perusahaan</h3>
        <span class="date">Tahun</span>
    </div>
    <p class="subtitle">Posisi</p>
    <ul class="experience-list">
        <li>Deskripsi pekerjaan...</li>
    </ul>
</div>
```

### Edit Keahlian

Edit bagian tech stack di `index.html`:

```html
<span class="tag">Flutter</span>
<span class="tag">Dart</span>
<!-- Tambahkan lebih banyak tag sesuai keahlian -->
```

## 🎨 Kustomisasi

### Ubah Warna Theme

Edit file `style.css` di bagian `:root`:

```css
:root {
    --primary-color: #2563eb;    /* Warna utama (biru) */
    --secondary-color: #1e40af;  /* Warna sekunder (biru tua) */
    --accent-color: #3b82f6;     /* Warna aksen (biru terang) */
    --text-dark: #1f2937;        /* Warna teks gelap */
    --text-light: #6b7280;       /* Warna teks terang */
}
```

### Ubah Particles Settings

Edit file `script.js` di bagian `particlesJS` config:

```javascript
particles: {
    number: {
        value: 80,  // Jumlah particles (default: 80)
    },
    color: {
        value: '#ffffff'  // Warna particles
    },
    size: {
        value: 3,  // Ukuran particles
    }
}
```

### Ubah Animation Speed

Edit di `script.js`:

```javascript
AOS.init({
    duration: 800,  // Durasi animasi (ms)
    easing: 'ease-in-out',  // Easing function
    once: true,  // Animasi hanya sekali
    offset: 100  // Offset dari viewport
});
```

## 📱 Preview Lokal

Untuk melihat CV di browser lokal:

1. Buka file `index.html` dengan browser (double-click)
2. Atau gunakan Live Server di VS Code

## 💡 Tips & Tricks

### Konten
- **Update Kontak**: Ganti email dan nomor telepon dengan yang asli
- **Tambah Foto Profil**: Upload foto ke repository dan ganti:
  ```html
  <!-- Dari -->
  <i class="fas fa-user"></i>
  <!-- Menjadi -->
  <img src="foto-profil.jpg" alt="Ahmad Revaldi" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
  ```
- **Ganti Gambar Portfolio**: Upload gambar project kamu atau gunakan Unsplash
- **Embed Video**: Upload video ke YouTube dan ganti video ID

### Deployment
- **Custom Domain**: Bisa gunakan custom domain di GitHub Pages settings
- **HTTPS**: GitHub Pages otomatis menggunakan HTTPS
- **Update**: Setiap push ke repository akan otomatis update website

### Export & Share
- **Export PDF**: Buka CV di browser, tekan `Ctrl+P` (Windows) atau `Cmd+P` (Mac)
- **Share Link**: Bagikan link GitHub Pages ke recruiter atau di LinkedIn
- **QR Code**: Generate QR code dari link CV untuk business card

### Performance
- **Optimize Images**: Compress gambar sebelum upload (gunakan TinyPNG)
- **Lazy Loading**: Sudah built-in untuk gambar portfolio
- **Cache**: Browser akan cache assets untuk loading lebih cepat

### Easter Eggs
- Klik profile image 5x untuk surprise! 🎉
- Cek console browser untuk pesan developer
- Hover dan klik berbagai elemen untuk animasi

## 📄 Struktur File

```
cv_project/
│
├── index.html      # File HTML utama dengan semua konten
├── style.css       # File CSS dengan animasi dan styling modern
├── script.js       # JavaScript untuk particles, AOS, dan interaktivity
└── README.md       # Dokumentasi lengkap (file ini)
```

## 🎯 Fitur JavaScript

### Particles.js
- Background animasi dengan 80 particles
- Interactive hover effect (grab mode)
- Click untuk menambah particles
- Responsive dan retina-ready

### Scroll Animations
- AOS library untuk smooth fade-in effects
- Parallax effect pada header
- Progress bar yang mengikuti scroll position
- Scroll to top button muncul setelah scroll 300px

### Interactive Elements
- Typing effect pada job title
- Hover animations pada skill cards
- Click animations pada tech tags
- Easter egg di profile image (klik 5x!)
- Lazy loading untuk gambar portfolio

### Developer Console
- Custom console message untuk developer
- Link ke GitHub profile

## 🔗 Link & Resources

### Documentation
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Particles.js](https://vincentgarreau.com/particles.js/)
- [AOS - Animate On Scroll](https://michalsnik.github.io/aos/)
- [Font Awesome Icons](https://fontawesome.com/icons)

### Tools
- [CSS Gradient Generator](https://cssgradient.io/)
- [Unsplash - Free Images](https://unsplash.com/)
- [TinyPNG - Image Compression](https://tinypng.com/)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)

### Inspiration
- [Awwwards](https://www.awwwards.com/)
- [Dribbble](https://dribbble.com/)
- [CodePen](https://codepen.io/)

## 🐛 Troubleshooting

### Particles tidak muncul
- Pastikan `script.js` sudah ter-load
- Cek console browser untuk error
- Pastikan koneksi internet aktif (particles.js dari CDN)

### Animasi tidak jalan
- Clear browser cache
- Pastikan AOS library ter-load
- Cek apakah JavaScript enabled di browser

### GitHub Stats tidak muncul
- Pastikan username GitHub benar: `itpeople1337-lgtm`
- Tunggu beberapa saat, API mungkin loading
- Cek apakah repository GitHub public

### Video tidak play
- Pastikan YouTube video ID benar
- Video harus public atau unlisted
- Cek embed settings di YouTube

## 📞 Support & Contribution

### Butuh Bantuan?
- 🐛 Buka issue di repository ini
- 💬 Diskusi di GitHub Discussions
- 📧 Contact via email (lihat di CV)

### Want to Contribute?
- ⭐ Star repository ini jika berguna
- 🍴 Fork dan customize untuk CV kamu sendiri
- 🔧 Submit PR untuk improvements
- 📝 Share feedback dan suggestions

### Credits
Terima kasih kepada:
- [Particles.js](https://github.com/VincentGarreau/particles.js/) by Vincent Garreau
- [AOS](https://github.com/michalsnik/aos) by Michał Sajnóg
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) by Anurag Hazra
- [Font Awesome](https://fontawesome.com/) for amazing icons
- [Unsplash](https://unsplash.com/) for beautiful images

## 🎓 Tech Stack Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Interactive features
- **Particles.js** - Animated background
- **AOS Library** - Scroll animations
- **Font Awesome** - Icons
- **GitHub Pages** - Free hosting

## 📈 Future Enhancements

Idea untuk upgrade CV:
- [ ] Dark mode toggle
- [ ] Multi-language support (ID/EN)
- [ ] Contact form dengan EmailJS
- [ ] Blog section
- [ ] Testimonials slider
- [ ] Download CV as PDF button
- [ ] Visitor counter
- [ ] Live chat widget

---

## 👨‍💻 About

**Dibuat dengan ❤️ untuk Ahmad Revaldi Saputra**

- 🎓 SMKN 12 Malang - PPLG (2023-2026)
- 💼 Flutter & Web Developer
- 🔗 GitHub: [itpeople1337-lgtm](https://github.com/itpeople1337-lgtm)
- 📍 Malang, Jawa Timur

---

**Good luck dengan CV-nya! 🚀**

Jika ada pertanyaan atau butuh bantuan, feel free to open an issue di repository ini!
