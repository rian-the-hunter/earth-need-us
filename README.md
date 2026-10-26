# Earth Need Us 🌍
### Kenali Iklim, Mulai Aksi

## 1. Tentang Proyek

**Earth Need Us** adalah website edukasi tentang perubahan iklim dan lingkungan yang dibuat sebagai proyek UTS Pemrograman Web.

Website ini mengangkat tema **Aksi Iklim — Perubahan Iklim dan Lingkungan (SDG 13)**. Website bertujuan membantu pengunjung memahami penyebab dan dampak perubahan iklim serta mengenal tindakan sederhana untuk menjaga bumi.

## 2. Tujuan dan Manfaat

Tujuan pembuatan website ini adalah:
- Memberikan informasi dasar tentang perubahan iklim.
- Menjelaskan penyebab dan dampak perubahan iklim terhadap kehidupan.
- Mengenalkan kebiasaan yang dapat membantu mengurangi emisi dan menjaga lingkungan.
- Meningkatkan kepedulian terhadap pentingnya aksi iklim.

Sasaran pengunjung website ini adalah pelajar dan masyarakat umum yang ingin mempelajari perubahan iklim dengan bahasa yang mudah dipahami.

## 3. Teknologi yang Digunakan

Website ini dibuat menggunakan:
- **HTML5** untuk menyusun struktur dan konten halaman.
- **CSS3** untuk mengatur warna, tipografi, tata letak, dan desain responsif.
- **GitHub** untuk menyimpan kode dan berkolaborasi.
- **GitHub Pages** untuk memublikasikan website secara online.

Website tidak menggunakan framework CSS seperti Bootstrap atau Tailwind, sehingga desain dibuat menggunakan CSS sendiri.

## 4. Struktur Halaman Website

Website terdiri dari lima halaman HTML yang saling terhubung.

| File | Deskripsi |
|---|---|
| `index.html` | Halaman beranda yang memperkenalkan Earth Need Us dan topik aksi iklim. |
| `edukasi.html` | Berisi pengertian, penyebab, dan dampak perubahan iklim. |
| `panduan.html` | Berisi panduan tindakan sehari-hari yang lebih ramah lingkungan. |
| `artikel.html` | Berisi bacaan pengantar dan tautan sumber informasi tentang iklim. |
| `tentang.html` | Menjelaskan tujuan website, sasaran pengunjung, anggota kelompok, dan referensi. |
| `style.css` | Mengatur desain visual dan responsivitas seluruh halaman. |

## 5. Penerapan HTML dan CSS

### HTML Semantik

HTML semantik digunakan untuk membentuk struktur halaman yang lebih jelas.

Contoh:
```html
<header class="site-header">
    <a href="index.html" class="logo">Earth Need Us</a>
    <nav aria-label="Navigasi utama">
        <a href="index.html">Beranda</a>
        <a href="edukasi.html">Edukasi</a>
    </nav>
</header>

<main>
    <section>
        <h1>Mengenal Perubahan Iklim</h1>
        <p>Pelajari penyebab dan dampak perubahan iklim.</p>
    </section>
</main>

<footer class="site-footer">
    <p>Earth Need Us — Kenali Iklim, Mulai Aksi.</p>
</footer>
```

Elemen `header`, `nav`, `main`, `section`, dan `footer` digunakan untuk membedakan bagian-bagian utama halaman.

### CSS Flexbox

Flexbox digunakan untuk menyusun elemen secara horizontal atau vertikal, seperti bagian header dan hero.

Contoh:
```css
.site-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 24px;
}
```

### CSS Grid

CSS Grid digunakan untuk menyusun kartu informasi menjadi beberapa kolom.

Contoh:
```css
.feature-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 22px;
}
```

### Media Queries

Media queries digunakan untuk menyesuaikan tata letak dengan ukuran layar yang berbeda.

Contoh:
```css
@media (max-width: 600px) {
    .hero {
        flex-direction: column;
        text-align: center;
    }

    .feature-grid {
        grid-template-columns: 1fr;
    }
}
```

### Navigasi Antarhalaman

Setiap halaman memiliki menu navigasi yang menghubungkan lima halaman utama.

Contoh:
```html
<nav aria-label="Navigasi utama">
    <a href="index.html">Beranda</a>
    <a href="edukasi.html">Edukasi</a>
    <a href="panduan.html">Aksi Nyata</a>
    <a href="artikel.html">Artikel</a>
    <a href="tentang.html">Tentang</a>
</nav>
```

### Responsivitas

Desain dibuat agar dapat menyesuaikan tampilan pada layar laptop, tablet, dan smartphone menggunakan Flexbox, CSS Grid, serta media queries.

Pengujian tampilan perlu dilakukan pada lebar layar:
- Desktop: 1440 piksel
- Tablet: 768 piksel
- Smartphone: 375 piksel

## 6. Referensi Konten

Referensi informasi yang digunakan sebagai bahan pengembangan konten:

1. NASA Climate Change — https://climate.nasa.gov/
2. Intergovernmental Panel on Climate Change (IPCC) — https://www.ipcc.ch/
3. United Nations Climate Action — https://www.un.org/en/climatechange

Tautan di atas merupakan sumber bacaan untuk memahami perubahan iklim. Ringkasan pada website ditulis untuk tujuan edukasi.

## 7. Anggota Kelompok

Lengkapi informasi berikut dengan data anggota kelompok yang sebenarnya.

| No. | Nama | NIM | Tugas |
|---|---|---|---|
| 1 | [Nama anggota 1] | [NIM] | [Tugas] |
| 2 | [Nama anggota 2] | [NIM] | [Tugas] |
| 3 | [Nama anggota 3] | [NIM] | [Tugas] |
| 4 | [Nama anggota 4] | [NIM] | [Tugas] |

## 8. Tautan Proyek

- **Repository GitHub:** [Masukkan URL repository]
- **Website GitHub Pages:** [Masukkan URL website]

## 9. Penutup

Melalui Earth Need Us, kami berharap pengunjung dapat memahami bahwa aksi iklim merupakan tanggung jawab bersama. Perubahan dapat dimulai dari kebiasaan sederhana yang dilakukan secara konsisten untuk mendukung lingkungan yang lebih baik.
