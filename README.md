# Bijak Pecahan (BijakMath)

**Aplikasi pembelajaran web untuk topik Pecahan (Matematik) dalam Bahasa Melayu.**

Bijak Pecahan ialah satu aplikasi pembelajaran sekolah yang membina kefahaman
tentang pecahan melalui video, kuiz, dan permainan interaktif.

🌐 **Live demo:** https://darwisyhakimi1210-bot.github.io/BijakPecahan/

---

## Apa yang Ada Dalam Aplikasi Ini?

| Bahagian | Keterangan |
| --- | --- |
| 🎬 **Pelajaran** | Video pelajaran topik pecahan: pengenalan, pendaraban, pembahagian, campuran, masalah, dan harian. |
| 📝 **Latihan** | Latihan soalan dengan maklum balas serta bunyi betul/salah. |
| 🧠 **Permainan Ingatan** | *Memory card game* — padankan kad bergambar untuk mengukuh kefahaman. |
| 🖐️ **Seret & Lepas** | *Drag & drop* exercise — seret jawapan ke tempat yang betul. |
| 🎯 **Soalan Aneka Pilihan** | Kumpulan soalan objektif dengan kiraan markah. |
| 📊 **Ujian Sumatif** | Ujian penuh dengan markah dan keputusan automatik. |
| 📖 **Refleksi** | Soalan refleksi untuk murid menilai kefahaman sendiri. |
| 🦉 **Mr P** | Watak 3D animasi (burung hantu) yang menjadi penunjuk sepanjang aplikasi. |

Semua kandungan, teks dan audio adalah dalam **Bahasa Melayu**.

---

## Teknologi

- **HTML, CSS & JavaScript** tulen — tiada framework, tiada proses *build*.
- **Three.js** (daripada jsDelivr CDN) untuk render model 3D `Mr P`.
- **Google Fonts – Press Start 2P** untuk gaya *pixel* / retro.
- **Web Audio + `<audio>`** untuk kesan bunyi.
- **AnyFlip** untuk viewer buku teks dalam talian.

Semua halaman adalah *static* — jadi ia boleh dihoskan terus di GitHub Pages,
Netlify, Vercel, atau mana-mana pelayan fail statik.

---

## Struktur Projek

```
BijakPecahan/
├── index.html          # Halaman utama (selamat datang + butang MULA)
├── pelajaran.html      # Halaman pelajaran (video)
├── latihan.html        # Papan latihan (latihan / ujian / permainan)
├── harian.html         # Latihan harian
├── masalah.html        # Latihan berdasarkan masalah
├── pilihan.html        # Soalan anekaa pilihan
├── ingat.html          # Permainan ingatan (memory game)
├── seret.html          # Permainan seret & lepas (drag & drop)
├── refleksi.html       # Soalan refleksi
├── ujian.html          # Ujian sumatif
├── pengenalan.html     # Topik: pengenalan pecahan
├── pendaraban.html     # Topik: pendaraban
├── pembahagian.html    # Topik: pembahagian
├── campuran.html       # Topik: pecahan campuran
├── styles.css          # Gaya perkongsi untuk semua halaman
├── avatar/kai.glb      # Model 3D Mr P (format glTF binary)
├── image/              # Video, gambar, latar belakang
├── sound/              # Fail bunyi (latihan, kesan, latar)
└── .nojekyll           # Melangkau proses Jekyll GitHub Pages
```

---

## Menjalankan Secara Tempatan

Tidak perlu alat khas — mana-mana pelayan statik asas sudah memadai.

**Pilihan 1 — Laragon (Windows):**

1. Letakkan folder ini di `C:\laragon\www\BijakPecahan\`
2. Buka Laragon → klik **Start All**
3. Lawati `http://localhost/BijakPecahan/index.html`

**Pilihan 2 — Python sahaja:**

```bash
cd BijakPecahan
python -m http.server 8000
```

Kemudian buka `http://localhost:8000/`.

> **Nota:** Jangan buka fail HTML dengan *double-click*. WebGL dan modul ES
> (`importmap`) memerlukan fail di-*serve* melalui `http://`, bukan `file://`.

---

## Deployment

Repositori ini dikonfigurasi untuk **GitHub Pages**:

- Sumber: branch `main`, folder `/`
- URL: https://darwisyhakimi1210-bot.github.io/BijakPecahan/

Setiap kali anda `push` ke branch `main`, GitHub Pages akan membina semula
laman web secara automatik.

---

## Catatan

- `image/bukuTeks.pdf` ialah salinan tempatan buku teks (617 MB). Ia **tidak**
  digunakan oleh aplikasi — butang "Buku Teks" membuka viewer **AnyFlip** dalam
  talian. Fail ini dikecualikan daripada git kerana GitHub hadkan saiz fail
  kepada 100 MB.
- Bunyi hanya boleh dimainkan selepas **satu klik** pertama pada halaman,
  mengikut peraturan autoplay browser.

---

_BijakMath — Membuat Pecahan Menyenangkan!_ 🦉
