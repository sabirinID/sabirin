# Syahril Dimas Sabirin | Personal Website & Portfolio

Repositori ini berisi kode sumber untuk situs *personal branding* dan portofolio resmi **Syahril Dimas Sabirin, S.Si., Gr.** — seorang Guru Kimia, Mentor Kompetisi Sains, Pengembang Media Belajar Digital, dan Pendiri Aurum Coffee. 

Situs ini dirancang menggunakan HTML, CSS, dan JavaScript murni (*vanilla*) untuk memastikan performa yang ringan dan modifikasi yang mudah.

---

## Struktur Direktori

Berikut adalah penjelasan fungsional dari setiap berkas utama di dalam repositori ini:

| Berkas / Direktori | Deskripsi |
| :--- | :--- |
| `index.html` | Kerangka utama dan seluruh konten teks/semantik halaman situs. |
| `styles.css` | Tata letak dan gaya visual. Menggunakan *design tokens* pada blok `:root` untuk manajemen warna dan tipografi. |
| `script.js` | Logika interaktivitas (*mobile menu toggle*, penanda *active state* pada navigasi, dan fungsi salin *email*). |
| `logo.jpg` & `profile.jpg` | Aset visual untuk identitas utama situs. |
| `CNAME` | Konfigurasi *custom domain* untuk keperluan *deployment* melalui GitHub Pages. |

---

## Panduan Menjalankan Lokal

Situs ini bersifat statis dan tidak memerlukan proses *build*. Anda dapat menjalankannya dengan dua cara:

**Opsi 1: Eksekusi Langsung**
Buka berkas `index.html` secara langsung menggunakan peramban web (*browser*) pilihan Anda.

**Opsi 2: Menggunakan Local Web Server (Direkomendasikan)**
Untuk pengalaman pengembangan yang lebih stabil, jalankan server lokal menggunakan Python melalui terminal/CMD:
```bash
python3 -m http.server 8000 
```
## Referensi
