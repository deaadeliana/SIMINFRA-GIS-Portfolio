# SIMINFRA — Tantangan Teknis dan Solusi Pengembangan

## Latar Belakang Proyek

SIMINFRA merupakan Sistem Informasi Geografis (SIG) berbasis web yang digunakan untuk mendukung visualisasi dan pengelolaan data spasial di Kabupaten Grobogan.

Selama menjalani magang sebagai Web Developer di BAPPERIDA Grobogan, saya terlibat dalam pengembangan dan penyempurnaan sejumlah fitur aplikasi menggunakan CodeIgniter 3, PHP, JavaScript, MySQL, dan Google Maps API.

Pengembangan dilakukan berdasarkan identifikasi permasalahan sistem, analisis kebutuhan, implementasi fitur, serta pengujian fungsional untuk meningkatkan kinerja dan kemudahan penggunaan aplikasi.

## 1. Tantangan Performa Pemuatan Layer Peta

### Permasalahan

Proses pemuatan beberapa layer peta secara berurutan menyebabkan waktu tunggu yang cukup lama, terutama ketika pengguna mengaktifkan beberapa layer secara bersamaan.

Kondisi tersebut dapat memengaruhi responsivitas aplikasi dan mengurangi kenyamanan pengguna ketika berinteraksi dengan peta.

### Solusi Pengembangan

Melakukan pengembangan mekanisme pemuatan layer secara asinkron sehingga beberapa layer dapat diproses tanpa harus menunggu seluruh proses sebelumnya selesai.

Selain itu, diterapkan pembatasan jumlah proses yang berjalan secara bersamaan untuk mengurangi beban pemrosesan pada aplikasi.

### Hasil

Mekanisme pemuatan layer menjadi lebih fleksibel karena beberapa layer dapat diproses secara asinkron. Pendekatan ini ditujukan untuk meningkatkan responsivitas aplikasi ketika pengguna mengaktifkan beberapa layer peta.

## 2. Tantangan Visualisasi dan Legenda Peta

### Permasalahan

Informasi warna dan simbol pada layer peta belum disajikan secara memadai sehingga pengguna mengalami kesulitan dalam memahami representasi data spasial yang ditampilkan.

### Solusi Pengembangan

Mengembangkan tampilan legenda dinamis yang menyesuaikan dengan layer aktif. Legenda digunakan untuk memberikan penjelasan mengenai warna dan simbol pada masing-masing layer.

### Hasil

Pengguna dapat melihat informasi legenda berdasarkan layer yang sedang diaktifkan sehingga informasi geografis lebih mudah dipahami.

## 3. Tantangan Pengelolaan Layer Aktif

### Permasalahan

Pengguna harus menonaktifkan layer satu per satu ketika ingin membersihkan tampilan peta. Selain itu, terlalu banyak layer aktif dapat menyebabkan tampilan peta menjadi kurang jelas.

### Solusi Pengembangan

Mengembangkan fitur Hapus Semua Layer yang memungkinkan pengguna menonaktifkan seluruh layer aktif melalui satu tindakan.

Selain itu, diterapkan pembatasan jumlah layer yang dapat diaktifkan secara bersamaan untuk menjaga keterbacaan informasi pada peta.

### Hasil

Pengelolaan layer menjadi lebih sederhana dan pengguna dapat mengatur tampilan peta dengan lebih mudah.

## 4. Tantangan Pengelolaan Data Administrator

### Permasalahan

Beberapa proses pengelolaan data peta membutuhkan penyempurnaan, khususnya pada validasi formulir, pencarian data, penyaringan berdasarkan kategori, dan penghapusan data.

Penghapusan secara langsung juga memiliki risiko kehilangan data apabila administrator melakukan tindakan yang tidak disengaja.

### Solusi Pengembangan

Melakukan penyempurnaan validasi data, fitur pencarian, dan penyaringan kategori peta.

Selain itu, dikembangkan mekanisme soft delete agar data yang dihapus dapat dipindahkan ke bagian Data Terhapus dan dipulihkan apabila diperlukan.

### Hasil

Proses pengelolaan data menjadi lebih terstruktur, sedangkan mekanisme pemulihan membantu mengurangi risiko kehilangan data akibat penghapusan yang tidak disengaja.

## 5. Tantangan Pengelolaan Metadata Spasial

### Permasalahan

Data spasial memerlukan informasi pendukung untuk menjelaskan identitas, karakteristik, sumber, serta informasi teknis dataset.

Tanpa metadata yang terstruktur, proses identifikasi dan pengelolaan data peta menjadi kurang informatif.

### Solusi Pengembangan

Mengembangkan pengelolaan metadata peta yang mencakup informasi identifikasi dataset, karakteristik spasial, format file, sumber data, dan informasi penanggung jawab.

### Hasil

Metadata membantu menyediakan informasi pendukung yang lebih terstruktur untuk memudahkan identifikasi dan pengelolaan dataset spasial.

## 6. Pengalaman dan Pembelajaran Teknis

Pengembangan SIMINFRA memberikan pengalaman dalam pemeliharaan dan penyempurnaan aplikasi web yang telah berjalan.

Melalui proyek ini, saya memperoleh pengalaman dalam penggunaan arsitektur Model-View-Controller (MVC), pengembangan fitur menggunakan CodeIgniter 3, pengolahan data menggunakan MySQL, implementasi interaksi antarmuka dengan JavaScript, serta integrasi layanan Google Maps API.

Selain implementasi fitur, kegiatan pengembangan juga melibatkan identifikasi permasalahan, debugging, analisis kebutuhan, dan pengujian fungsional.

Pengalaman tersebut membantu meningkatkan pemahaman saya mengenai proses pengembangan aplikasi web berdasarkan kebutuhan pengguna.

## Informasi Repository

Repository ini digunakan sebagai dokumentasi portofolio pribadi yang menjelaskan pengalaman dan kontribusi dalam pengembangan SIMINFRA selama kegiatan magang.

Source code asli, database internal, dan dokumen yang bersifat terbatas tidak dipublikasikan tanpa persetujuan pihak terkait.

---

**Pengembang:** Dea Adeliana Putri

**Peran:** Web Developer Intern

**Instansi:** BAPPERIDA Grobogan

**Teknologi:** PHP · CodeIgniter 3 · JavaScript · MySQL · Google Maps API
