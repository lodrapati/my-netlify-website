# My Netlify Website

Website portfolio modern yang siap di-deploy ke Netlify dengan HTML, CSS, dan JavaScript murni.

## 📋 Fitur

✨ **Responsive Design** - Desain yang sempurna di semua ukuran layar
🎨 **Modern UI** - Interface yang indah dan user-friendly
⚡ **Fast Performance** - Performa yang cepat dan optimal
🔒 **Secure Headers** - Security best practices sudah diterapkan
📱 **Mobile Optimized** - Dioptimalkan untuk perangkat mobile
🎯 **Smooth Animations** - Animasi yang halus dan menarik

## 📁 Struktur File

```
my-netlify-website/
├── index.html          # File HTML utama
├── styles.css          # Styling CSS
├── script.js           # JavaScript untuk interaktivitas
├── netlify.toml        # Konfigurasi Netlify
├── .gitignore          # File yang diabaikan Git
└── README.md           # File dokumentasi ini
```

## 🚀 Cara Deploy ke Netlify

### Metode 1: Melalui GitHub (Recommended)

1. **Fork atau Clone Repository ini**
   ```bash
   git clone https://github.com/lodrapati/my-netlify-website.git
   cd my-netlify-website
   ```

2. **Push ke GitHub Repository Anda**
   ```bash
   git push origin main
   ```

3. **Connect ke Netlify**
   - Buka [netlify.com](https://www.netlify.com/)
   - Login atau daftar akun baru
   - Klik "Add new site" → "Import an existing project"
   - Pilih GitHub dan authorize
   - Pilih repository ini
   - Netlify akan otomatis mendeploy!

### Metode 2: Manual Upload

1. **Compress file ini menjadi ZIP**
2. **Di Netlify, drag & drop folder ke deploy area**

## 💻 Pengembangan Lokal

### Menggunakan Local Server (Python)
```bash
python -m http.server 8000
```
Lalu buka http://localhost:8000 di browser.

### Menggunakan Live Server (VS Code)
1. Install extension "Live Server"
2. Klik kanan pada index.html
3. Pilih "Open with Live Server"

## 📝 Kustomisasi

### Edit Konten HTML
Buka `index.html` dan ubah:
- Nama di section hero
- Deskripsi di section about
- Project cards di section projects
- Social links di section contact

### Ubah Styling
Edit `styles.css` untuk mengubah:
- Warna (modify color values)
- Font (change font-family)
- Spacing (modify padding/margin)
- Animations (adjust animation properties)

### Tambah Fungsionalitas
Edit `script.js` untuk menambah:
- Event listeners baru
- API calls
- Form handling
- Analytics tracking

## 🔧 Konfigurasi Netlify

File `netlify.toml` sudah dikonfigurasi dengan:
- Security headers (X-Frame-Options, CSP, etc)
- Cache optimization untuk static assets
- URL rewrites untuk SPA
- Redirect rules

## 📱 Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## 📊 Performance Tips

1. **Optimize Images** - Gunakan format WebP untuk faster loading
2. **Minify CSS/JS** - Gunakan build tools untuk production
3. **Lazy Loading** - Implement untuk images yang tidak terlihat
4. **DNS Prefetch** - Add untuk external resources

## 🐛 Troubleshooting

### Deploy gagal?
- Check apakah file sudah di-push ke GitHub
- Pastikan `netlify.toml` sudah ada
- Lihat build logs di Netlify dashboard

### Website tidak responsive?
- Clear browser cache (Ctrl+Shift+Delete)
- Check viewport meta tag di HTML
- Test di DevTools responsive mode

## 📞 Support

Jika ada pertanyaan atau bug, silakan buat issue di repository ini.

## 📄 License

Free to use dan modify untuk project personal atau commercial.

## 🙏 Credits

Dibuat dengan ❤️ menggunakan HTML, CSS, dan JavaScript murni.

---

**Happy Coding! 🎉**
