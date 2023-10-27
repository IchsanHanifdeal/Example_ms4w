# UTS: Menampilkan SHP Senapelan dengan MS4W, HTML, CSS, JS, dan Google Maps API

Proyek ini bertujuan untuk menampilkan data geospasial dalam format SHP (Shapefile) dari wilayah Senapelan menggunakan MS4W (MapServer for Windows), HTML, CSS, JavaScript, dan Google Maps API.

## Prasyarat

Sebelum Anda dapat menjalankan proyek ini, pastikan Anda telah menginstal perangkat lunak berikut:

- **MS4W (MapServer for Windows)**: MS4W adalah lingkungan pengembangan untuk peta web yang berjalan di platform Windows. Anda dapat mengunduhnya [di sini](https://ms4w.com/).

- **Kunci API Google Maps**: Anda memerlukan kunci API Google Maps yang valid. Dapatkan kunci API Anda [di sini](https://developers.google.com/maps/gmp-get-started).

## Cara Menggunakan Proyek

1. **Unduh Proyek**: Unduh proyek ini ke komputer Anda atau kloning repositori ini menggunakan Git.

2. **Konfigurasi MS4W**:
   - Instal MS4W dan ikuti instruksi yang diberikan di situs web MS4W.
   - Letakkan data SHP Senapelan Anda di direktori proyek.

3. **Konfigurasi Kunci API Google Maps**:
   - Gantilah `'YOUR_API_KEY'` di berkas HTML (`index.html`) dengan kunci API Google Maps yang Anda dapatkan.

4. **Memastikan Data SHP yang Benar**:
   - Pastikan data SHP Anda sesuai dengan wilayah Senapelan dan sesuai dengan konfigurasi lapisan peta dalam berkas proyek.

5. **Menjalankan Aplikasi**:
   - Buka berkas `index.html` menggunakan peramban web Anda.

## Struktur Proyek

- `index.html`: Berkas HTML utama yang mengintegrasikan Google Maps API dan menampilkan peta.

- `style.css`: Berkas CSS untuk mengatur tampilan peta dan elemen-elemen lainnya.

- `javascript.js`: Berkas JavaScript yang mengatur logika aplikasi, termasuk pengaturan peta dan lapisan.

- `shp/`: Direktori tempat Anda menyimpan berkas-berkas SHP terkait dengan wilayah Senapelan.

## Kontribusi

Anda dipersilakan untuk berkontribusi pada proyek ini dengan mengirimkan *pull request*. Silakan laporkan *bug* atau saran perbaikan melalui *issues*.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

Semoga proyek ini membantu Anda dalam mengeksplorasi data geospasial dan menampilkan SHP Senapelan menggunakan MS4W, HTML, CSS, JavaScript, dan Google Maps API. Jika Anda memiliki pertanyaan atau memerlukan bantuan lebih lanjut, jangan ragu untuk menghubungi kami.
