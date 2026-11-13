# SIMINFRA — Dokumentasi Pengembangan Fitur

## Latar Belakang Proyek

SIMINFRA merupakan Sistem Informasi Geografis (SIG) berbasis web yang dikembangkan untuk mendukung visualisasi dan pengelolaan data spasial di Kabupaten Grobogan.

Selama menjalani kegiatan magang sebagai Web Developer di BAPPERIDA Grobogan, saya berkontribusi dalam penyempurnaan fitur yang telah tersedia serta pengembangan fungsionalitas tambahan untuk pengguna umum dan administrator.

Pengembangan dilakukan dengan memperhatikan kebutuhan pengguna, kinerja sistem, kemudahan pengelolaan data, dan peningkatan pengalaman pengguna dalam berinteraksi dengan aplikasi.

## 1. Pengembangan Fitur Peta Interaktif

### Pemuatan Layer Secara Asinkron

Melakukan penyempurnaan mekanisme pemuatan layer peta menggunakan pemrosesan asinkron sehingga beberapa layer spasial dapat diproses tanpa harus menunggu pemuatan layer sebelumnya selesai.

Pengembangan ini juga mencakup pembatasan jumlah proses yang berjalan secara bersamaan untuk menjaga responsivitas aplikasi.

### Pengelolaan Layer Peta

Mengembangkan pengelolaan layer aktif dengan menerapkan batas maksimum jumlah layer yang dapat ditampilkan secara bersamaan.

Selain itu, ditambahkan fitur Hapus Semua Layer untuk memudahkan pengguna menonaktifkan seluruh layer aktif melalui satu tindakan.

### Legenda Peta Dinamis

Mengembangkan tampilan legenda peta yang menyesuaikan dengan layer spasial yang sedang aktif.

Legenda membantu pengguna memahami informasi warna dan simbol yang digunakan dalam visualisasi data geografis.

### Pencarian Lokasi

Melakukan penyempurnaan fitur pencarian lokasi dengan memprioritaskan wilayah Kabupaten Grobogan.

Sistem juga dilengkapi pemberitahuan ketika pengguna memilih lokasi di luar wilayah Kabupaten Grobogan serta menyediakan fitur untuk kembali ke wilayah tersebut.

## 2. Pengembangan Fitur Administrator

### Pengelolaan Data Peta

Melakukan penyempurnaan fitur pengelolaan data peta melalui penambahan pencarian, penyaringan berdasarkan kategori, dan validasi informasi peta.

Pengembangan ini bertujuan memudahkan administrator dalam menemukan, memeriksa, dan mengelola data spasial.

### Penghapusan Sementara dan Pemulihan Data

Mengembangkan mekanisme soft delete yang memungkinkan data peta yang dihapus dipindahkan ke bagian Data Terhapus.

Administrator dapat melihat dan memulihkan data yang telah dihapus sebelum dilakukan penghapusan permanen.

### Pengelolaan Metadata Spasial

Berkontribusi dalam pengembangan fitur pengelolaan metadata untuk mendukung dokumentasi dataset spasial secara terstruktur.

Informasi metadata mencakup identifikasi dataset, deskripsi data, karakteristik spasial, informasi file, sumber data, dan informasi penanggung jawab.

### Penyempurnaan Antarmuka Administrator

Melakukan perbaikan elemen antarmuka administrator, termasuk validasi formulir, navigasi menu, pencarian data, konfirmasi tindakan, dan penyajian informasi untuk mendukung proses pengelolaan peta yang lebih efisien.

## 3. Teknologi yang Digunakan

**Backend**

PHP · CodeIgniter 3

**Frontend**

HTML · CSS · JavaScript · jQuery

**Database**

MySQL

**Teknologi Pemetaan**

Google Maps JavaScript API · GeoJSON

## 4. Metode Pengembangan

Pengembangan SIMINFRA menggunakan pendekatan Rapid Application Development (RAD) yang menekankan proses pengembangan secara bertahap dan penyempurnaan berdasarkan kebutuhan pengguna.

Kegiatan pengembangan mencakup analisis kebutuhan, perancangan sistem, implementasi fitur, pengujian fungsional, serta perbaikan berdasarkan hasil evaluasi.

Pendekatan ini digunakan untuk mendukung proses pengembangan fitur secara iteratif agar sesuai dengan kebutuhan sistem dan pengguna.

## 5. Pengalaman Teknis

Kegiatan magang ini memberikan pengalaman praktis dalam melakukan pemeliharaan, pengembangan, dan penyempurnaan aplikasi web yang telah berjalan.

Proses pengembangan melibatkan penggunaan controller dan view pada CodeIgniter 3, pengelolaan database MySQL, implementasi interaksi antarmuka menggunakan JavaScript, serta pengembangan fitur peta interaktif dengan Google Maps API.

Selain implementasi fitur, kegiatan pengembangan juga melibatkan identifikasi permasalahan, debugging, pengujian fungsional, dan evaluasi terhadap kebutuhan pengguna.

Pengalaman tersebut membantu meningkatkan pemahaman mengenai pengembangan aplikasi berbasis web, khususnya dalam pengelolaan data spasial dan penyempurnaan fungsionalitas sistem.

## Informasi Repository

Repository ini digunakan sebagai dokumentasi portofolio pribadi yang menjelaskan pengalaman dan kontribusi saya dalam pengembangan SIMINFRA selama kegiatan magang di BAPPERIDA Grobogan.

Source code asli, database internal, serta sumber daya proyek yang bersifat terbatas tidak dipublikasikan tanpa persetujuan pihak terkait.

---

**Pengembang:** Dea Adeliana Putri

**Peran:** Web Developer Intern

**Instansi:** BAPPERIDA Grobogan

**Teknologi:** PHP · CodeIgniter 3 · JavaScript · MySQL · Google Maps API
