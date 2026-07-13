# LAPORAN-TUGAS-APBO-SISTEM-INFORMASI-MANAJEMEN-KOS

## Anggota Kelompok 3

| Nama | NPM |
| :--- | :--- |
| Alamanda | 4522210078 |
| Lilis | 4524210051 |
| Ketut Sumantre | 4524210048 |
| Bunga Putri Nuriman | 4524210021 |
| Kornelius Timothy Setiawan | 4524210050 |

---

# Sasaran Pengguna
Sasaran Pengguna dari Sistem Informasi Manajemen Kos Berbasis Web ini terdiri dari dua kelompok utama: Pemilik atau Pengelola Kos sebagai Admin dan Penghuni Kos sebagai User. Sistem ini dirancang untuk memenuhi kebutuhan masing-masing pengguna agar pengelolaan kos lebih efisien dan komunikasi antar pemilik dan prnghuni berjalan lancar. Berikut adalah penjelasan singkat mengenai kedua kelompok pengguna tersebut:

### 1. Pengelola Kos (Admin)
Pengelola kos adalah pihak yang bertanggung jawab atas sistem dan operasional kos. Pengelola juga memiliki pekerjaan utama sehingga dibutuhkan sistem yang lebih efisien.  
Sebagai pengelola, mereka membutuhkan informasi terpusat mengenai pembayaran, data penghuni, dan status kamar agar bisa memantau kos secara efektif tanpa harus mengganggu pekerjaan utama.

### 2. Penghuni Kos (User)
Penghuni kos adalah mahasiswa atau pekerja yang menempati kamar kos. Mereka sudah terbiasa menggunakan smartphone dan membutuhkan kemudahan dalam melakukan pembayaran, mengirim keluhan, dan menerima pengumuman atau notifikasi penting.  
Sistem yang mudah diakses dan transparan akan membantu mereka menjaga kewajiban pembayaran dan komunikasi dengan pemilik kos.

---

# Studi Literatur
Keterbatasan dalam pengelolaan kos yang masih dilakukan secara manual menunjukkan perlunya penerapan sistem yang lebih terintegrasi dan efisien. Oleh karena itu, dilakukan peninjauan terhadap berbagai konsep dan teknologi yang mendukung pengembangan sistem informasi berbasis web. Studi literatur ini digunakan sebagai landasan dalam merancang solusi yang sesuai dengan kebutuhan pengelola maupun penghuni kos.


### 1. Sistem Informasi Manajemen
Sistem Informasi Manajemen merupakan sistem yang digunakan untuk mengelola data dan informasi dalam suatu organisasi agar proses pengambilan keputusan dapat dilakukan dengan lebih efektif.

Pada Sistem Informasi Manajemen Kos, konsep ini diterapkan untuk mengelola data penghuni, kamar, pembayaran, keluhan, serta laporan operasional secara terintegrasi.

> **Referensi:**  [Sistem Informasi Manajemen (2021)](https://ojs.stmikdharmapalariau.ac.id/index.php/repository/article/view/590/340)


### 2. Sistem Berbasis Web
Sistem berbasis web merupakan sistem yang dapat diakses melalui browser menggunakan jaringan internet atau lokal.

Penggunaan sistem berbasis web pada manajemen kos bertujuan agar pengguna dapat mengakses informasi kapan saja tanpa harus melakukan pencatatan secara manual.

Keunggulan sistem berbasis web:

- Mudah diakses.
- Data tersimpan secara terpusat.
- Mempermudah proses pengelolaan informasi.
- Mengurangi penggunaan dokumen fisik.

> **Referensi:**  [Web-based information system for boarding house information (IJSRM, 2024)](https://doi.org/10.18535/ijsrm/v12i03.ec11)

### 3. Basis Data (Database)
Basis data merupakan kumpulan data yang saling berhubungan dan disimpan secara terstruktur sehingga dapat dikelola, diperbarui, dan diakses dengan mudah.

Pada sistem ini, database digunakan untuk menyimpan:

- Data penghuni.
- Data kamar.
- Data pembayaran.
- Data keluhan.
- Data laporan keuangan.

Dengan penggunaan database, proses pencarian dan pengelolaan data menjadi lebih cepat, akurat, dan aman.

> **Referensi:** [Silberschatz, Korth & Sudarshan.  
Database System Concepts.](https://www.mpgcamb.com/wp-content/uploads/2024/12/Abraham-Silberschatz-Henry-F.-Korth-S.-Sudarshan-Database-System-Concepts-McGraw-Hill-Education-2019.pdf)

### 4. Sistem Informasi Pembayaran
Sistem informasi pembayaran merupakan sistem yang digunakan untuk mencatat, memproses, dan mengelola transaksi pembayaran secara terstruktur.

Pada Sistem Informasi Manajemen Kos, fitur pembayaran digunakan untuk:

- Menampilkan tagihan penghuni.
- Mengunggah bukti pembayaran.
- Melakukan verifikasi pembayaran.
- Menyimpan riwayat transaksi.

Sistem ini membantu admin dalam memantau pembayaran secara lebih efektif.

> **Referensi:** [Billing and Payment Systems (Springer, 2023)](https://link.springer.com/chapter/10.1007/978-3-031-39626-7_6#citeas)

### 5. Manajemen Keluhan
Manajemen keluhan merupakan proses pengelolaan laporan atau pengaduan pengguna terhadap suatu layanan.

Dalam sistem manajemen kos, fitur keluhan digunakan untuk membantu penghuni menyampaikan masalah fasilitas.

> **Referensi:**
> [Sistem Informasi Pengaduan Siswa Berbasis Website Dengan Framework Laravel (Josh, 2023)](https://pdfs.semanticscholar.org/cf97/0b30fc094d7c92a0435f36dd309cdc845891.pdf),
> [SISTEM INFORMASI PENGADUAN MASYARAKAT BERBASIS WEBSITE DI DESA PAGARBATU (2025)](https://doi.org/10.69714/s896fk61)

---

# Hasil Wawancara: Sistem Informasi Manajemen Kos

Klik pada masing-masing bagian di bawah ini untuk melihat detail daftar pertanyaan dan jawaban hasil wawancara terkait sistem yang sedang berjalan:

<details>
<summary><b>Bagian 1: Operasional & Manajemen Inventaris Kamar</b></summary>

1. **Bagaimana sistem pengelolaan kos saat ini berjalan?**
   > "Saat ini masih sepenuhnya manual, hanya mengandalkan WhatsApp untuk komunikasi dan buku tulis untuk pencatatan."

2. **Berapa jumlah kamar dan penghuni kos saat ini?**
   > "Total tersedia 20 kamar. Saat ini terisi 18 kamar dengan total penghuni sebanyak 18 orang."

3. **Apa saja kendala utama yang sering dihadapi dalam mengurus operasional kos?**
   > "Kendala utama adalah manajemen penagihan biaya bulanan dan menangani keluhan fasilitas. Karena faktor usia, pengelola sering kali lupa terhadap detail keluhan yang masuk."

4. **Bagaimana cara menyimpan dan mengelola data fisik penghuni?**
   > "Data disimpan dalam map fisik yang berisi fotokopi KTP dan Kartu Keluarga."

5. **Apakah pernah mengalami kesulitan atau kehilangan data penghuni?**
   > "Sering kesulitan mencari data karena tercampur dalam satu map dokumen. Bahkan pernah terjadi kehilangan data karena pengelola lupa tempat menyimpannya."
</details>

<details>
<summary><b>Bagian 2: Alur Pembayaran & Keuangan</b></summary>

1. **Bagaimana proses pembayaran kos dilakukan oleh penghuni?**
   > "Sebagian besar melalui transfer manual ke rekening bank atau GoPay, namun masih ada beberapa penghuni yang membayar secara tunai (cash)."

2. **Bagaimana metode pencatatan pembayaran yang digunakan?**
   > "Untuk transfer, penghuni mengirimkan bukti *screenshot* via WhatsApp, lalu saya catat manual di buku. Pembayaran tunai juga langsung dicatat di buku yang sama."

3. **Bagaimana cara Anda memantau status pembayaran setiap bulannya?**
   > "Saya harus mengecek buku catatan satu per satu dan mencocokkannya dengan mutasi di m-banking atau aplikasi GoPay untuk memastikan siapa yang belum bayar."

4. **Apakah sering terjadi keterlambatan pembayaran? Apa alasannya?**
   > "Lumayan sering, sekitar 3 sampai 4 orang setiap bulannya. Alasannya beragam, mulai dari menunggu tanggal gajian, kiriman orang tua yang terlambat, hingga murni karena lupa."
</details>

<details>
<summary><b>Bagian 3: Komunikasi & Penanganan Keluhan</b></summary>

1. **Bagaimana cara penghuni menyampaikan keluhan atau kendala fasilitas?**
   > "Biasanya melalui pesan pribadi di WhatsApp atau menyampaikan secara langsung saat bertemu pengelola."

2. **Apakah ada keluhan yang sering terlewat untuk ditangani?**
   > "Sering sekali. Karena tidak terdokumentasi dengan baik dan faktor usia pengelola, banyak keluhan yang akhirnya terlupakan."

3. **Bagaimana cara pengelola menyampaikan informasi penting kepada seluruh penghuni?**
   > "Kami menggunakan grup WhatsApp khusus penghuni untuk membagikan pengumuman atau informasi penting."

4. **Apakah penyampaian informasi melalui grup tersebut sudah efektif?**
   > "Kurang efektif. Sering kali informasi terlewat karena chat yang menumpuk, grup yang di-*mute* oleh penghuni, atau hanya dibaca sekilas tanpa diperhatikan."
</details>

<details>
<summary><b>Bagian 4: Kebutuhan & Harapan Terhadap Sistem Baru</b></summary>

1. **Apakah sistem digital akan membantu pengelolaan kos sehari-hari?**
   > "Sangat membantu. Sistem manual saat ini sangat tidak efisien. Dengan sistem baru, diharapkan manajemen menjadi lebih rapi dan pengelola tidak perlu mengecek data secara manual satu per satu."

2. **Bagian mana yang paling krusial untuk segera diperbaiki?**
   > "Prioritas utama adalah perbaikan pada sistem pencatatan pembayaran dan digitalisasi manajemen data penghuni."

3. **Bagaimana pendapat Anda mengenai fitur pengingat pembayaran otomatis?**
   > "Itu akan sangat mempermudah kerja kami. Selain lebih praktis, kami tidak perlu lagi merasa sungkan saat harus menagih penghuni satu per satu secara manual."

4. **Preferensi notifikasi seperti apa yang Anda harapkan?**
   > "Untuk penghuni, notifikasi via WhatsApp adalah yang paling efektif. Sedangkan untuk pengelola, saya membutuhkan *dashboard* berbasis web agar bisa melihat rekapitulasi data secara menyeluruh."
</details>

---
## 🎥 Video Dokumentasi

[![Video Dokumentasi](cover/cover.jpeg)](https://youtu.be/RORLaileWqk)

*(Klik gambar di atas untuk memutar video)*

---

# Latar Belakang


Pengelolaan rumah kos ini masih dilakukan secara manual, terutama dalam pencatatan data penyewa, ketersediaan kamar, serta pembayaran sewa. Cara ini berpotensi menimbulkan berbagai permasalahan seperti kesalahan pencatatan, keterlambatan informasi, hingga kesulitan dalam memantau status kamar secara akurat. Di sisi lain, tingginya mobilitas mahasiswa sebagai penyewa kos menuntut adanya akses informasi yang cepat dan praktis terkait ketersediaan kamar, harga, serta fasilitas yang ditawarkan.

Untuk mengatasi permasalahan tersebut, diperlukan sebuah sistem informasi manajemen kos berbasis web yang mampu mengintegrasikan proses pengelolaan data sekaligus memberikan kemudahan akses bagi penyewa sebagai pengguna utama. Sistem ini diharapkan dapat membantu pengelola dalam melakukan pencatatan secara lebih terstruktur dan efisien, serta memungkinkan penyewa memperoleh informasi kos secara real-time tanpa harus datang langsung ke lokasi. Dengan demikian, sistem ini tidak hanya meningkatkan efisiensi pengelolaan, tetapi juga memberikan nilai tambah dalam pelayanan kepada penyewa di lingkungan sekitar kampus.

---

## Bagian 1: Analisis Aktor

# 1. Pengelola Kos (Admin)

Pengelola kos menjadi pihak yang paling berperan dalam sistem ini karena semua kegiatan operasional dipegang oleh pengelola. Dari yang saya lihat, sebagian besar proses masih dilakukan secara manual, sehingga cukup merepotkan jika data sudah banyak.

Tugas dan tanggung jawab:
- Mengelola data penghuni, seperti menambah atau mengubah data
- Mengatur kamar, apakah masih kosong atau sudah terisi
- Mencatat dan mengecek pembayaran dari penghuni
- Melihat laporan keuangan
- Menangani keluhan dari penghuni
- Mengingatkan penghuni terkait pembayaran

---

# 2. Penghuni Kos (User)

Penghuni kos adalah pengguna yang langsung menggunakan sistem ini. Biasanya lebih fokus pada pembayaran dan penyampaian keluhan.

Tugas dan tanggung jawab:
- Melakukan pembayaran kos
- Mengunggah bukti pembayaran
- Mengecek status pembayaran
- Menyampaikan keluhan jika ada masalah
- Menerima informasi atau pengingat dari sistem

---

# 3. Sistem

Sistem berfungsi untuk membantu agar semua proses menjadi lebih rapi dan tidak lagi dilakukan secara manual.

Tugas dan tanggung jawab:
- Mengirim notifikasi otomatis, seperti pengingat pembayaran
- Menyimpan data penghuni dan pembayaran
- Menampilkan data dalam bentuk dashboard
- Menyimpan riwayat pembayaran dan keluhan
- Membantu pencarian data dengan lebih cepat

## Bagian 2: Analisis Perbandingan Sistem

# 1. Manajemen Data Penghuni

Sistem manual:
Data biasanya disimpan dalam bentuk berkas seperti fotokopi KTP. Jika jumlah data sudah banyak, akan sulit dicari karena tercampur.

Sistem digital:
Data disimpan dalam database sehingga lebih rapi dan mudah dicari. Risiko kehilangan data juga lebih kecil.

---

# 2. Pembayaran

Sistem manual:
Pembayaran dicatat di buku, dan bukti pembayaran sering dikirim melalui WhatsApp. Untuk mengecek siapa yang belum bayar harus dilakukan satu per satu.

Sistem digital:
Pembayaran tercatat langsung di sistem. Penghuni dapat mengunggah bukti pembayaran dan statusnya bisa langsung dilihat.

---

# 3. Pengingat Pembayaran

Sistem manual:
Pengelola harus mengingat dan menagih secara manual, dan terkadang merasa tidak enak.

Sistem digital:
Sistem dapat mengirim pengingat otomatis sehingga lebih praktis dan mengurangi keterlambatan.

---

# 4. Keluhan

Sistem manual:
Keluhan disampaikan melalui chat dan tidak selalu tercatat dengan baik.

Sistem digital:
Keluhan tercatat dalam sistem sehingga memiliki riwayat dan lebih mudah ditindaklanjuti.

---

# 5. Penyampaian Informasi

Sistem manual:
Informasi disampaikan melalui grup WhatsApp, namun sering tertumpuk dan terlewat.

Sistem digital:
Informasi lebih teratur dan dapat diakses kembali kapan saja.

---

# Class Diagram
<img width="1050" height="1305" alt="Diagram Class SI Manajemen Kost (APBO) drawio (1)" src="https://github.com/user-attachments/assets/4b827265-92a3-48db-80cd-0492ad0dd50c" />


## Penjelasan Diagram Class

Diagram Class pada Sistem Informasi Manajemen Kos Berbasis Web digunakan untuk menggambarkan struktur data statis, spesifikasi kelas, atribut, fungsi (method), serta hubungan (relationship) antar objek secara terintegrasi. 

Sesuai dengan prinsip enkapsulasi pada Pemrograman Berorientasi Objek (OOP), seluruh atribut diatur sebagai Private (-) untuk mengamankan data internal dari akses langsung luar kelas, sedangkan method/fungsi diatur sebagai Public (+) agar dapat dieksekusi melalui mekanisme pengiriman pesan (message passing) antar-objek di dalam sistem.

---

## Spesifikasi Kelas (Class Definitions)

### 1. Class Admin
Class Admin merepresentasikan entitas pengelola kos yang memegang hak akses masuk untuk memicu eksekusi fungsi pada objek-objek operasional.

* Atribut (Private):
  * - idAdmin : int — Identitas unik sistem untuk admin.
  * - nama : string — Nama lengkap pengelola kos.
  * - username : string — Kredensial unik untuk hak akses masuk admin.
  * - password : string — Kata sandi akun admin (terenkripsi).
  * - noHp : string — Nomor telepon pengelola yang aktif.
* Method (Public):
  * + login() — Memvalidasi kredensial masuk admin ke sistem.
  * + logout() — Mengakhiri sesi akses admin pada sistem.

### 2. Class Penghuni
Class Penghuni merepresentasikan data penyewa kamar kos yang memiliki hak akses terbatas untuk mengelola data pribadinya sendiri.

* Atribut (Private):
  * - idPenghuni : int — Identitas unik sistem untuk penghuni.
  * - nama : string — Nama lengkap penghuni sesuai kartu identitas.
  * - alamat : string — Alamat asal penghuni sesuai KTP.
  * - noHp : string — Nomor telepon seluler penghuni.
  * - email : string — Alamat surat elektronik penghuni.
  * - kontakDarurat : string — Nomor telepon kerabat dekat untuk situasi darurat.
  * - username : string — Kredensial unik akun penghuni.
  * - password : string — Kata sandi keamanan akun penghuni.
  * - tglMasuk : date — Tanggal resmi dimulainya kontrak sewa kamar.
* Method (Public):
  * + login() — Memproses autentikasi masuk penghuni ke platform.
  * + logout() — Mengakhiri sesi akses penghuni pada sistem.

### 3. Class Kamar
Class Kamar bertanggung jawab penuh atas manipulasi data fisik unit kamar kos yang disewakan.

* Atribut (Private):
  * - idKamar : int — Identitas unik untuk tiap unit kamar.
  * - nomorKamar : string — Kode unik atau nomor penanda kamar (misal: A01, B05).
  * - tipeKamar : string — Kategori kelas kamar (misal: Deluxe, Standard, VIP).
  * - harga : double — Nominal tarif biaya sewa per bulan.
  * - status : string — Indikator ketersediaan kamar (misal: Kosong, Terisi, Perbaikan).
  * - fasilitas : string — Daftar inventaris bawaan di dalam kamar.
* Method (Public):
  * + ubahStatus() — Mengubah parameter indikator ketersediaan unit kamar.
  * + tampilInfo() — Menyajikan rincian spesifikasi lengkap data kamar.

### 4. Class Keluhan
Class Keluhan merangkum data dan siklus hidup laporan kerusakan sarana prasarana dari penghuni.

* Atribut (Private):
  * - idKeluhan : int — Nomor tiket unik pengaduan keluhan.
  * - idPenghuni : int — ID penghuni yang mengirimkan laporan.
  * - kategori : string — Jenis area keluhan (misal: Air, Fasilitas Kamar, Fasilitas Umum).
  * - deskripsi : string — Penjelasan kronologi atau detail kerusakan sarana.
  * - foto : string — Jalur penyimpanan (path/URL) file foto bukti kerusakan.
  * - status : string — Status progres pelaporan (misal: Pending, Diproses, Selesai).
  * - tglKeluhan : date — Waktu pengaduan dikirim pertama kali.
* Method (Public):
  * + updateStatus() — Memperbarui alur penanganan keluhan oleh pihak pengelola.
  * + tutupKeluhan() — Mengunci status tiket aduan menjadi selesai jika perbaikan rampung.

### 5. Class Notifikasi
Class Notifikasi berfungsi memproses pembuatan dan pengiriman pesan pengingat otomatis oleh sistem.

* Atribut (Private):
  * - idNotifikasi : int — Identitas unik rekaman notifikasi.
  * - idPenghuni : int — ID penghuni yang dituju.
  * - pesan : string — Teks isi pesan/informasi penting yang dikirimkan.
  * - tanggalKirim : date — Log waktu pengiriman pesan.
  * - jenis : string — Kategori pesan (misal: Peringatan Tagihan, Pengumuman Bersama).
  * - statusBaca : string — Penanda pesan sudah dibaca atau belum oleh penghuni.
* Method (Public):
  * + kirim() — Memicu pengiriman data pesan ke akun tujuan.
  * + tandaiDibaca() — Mengubah status baca pesan dari sisi penghuni.

### 6. Class Tagihan
Class Tagihan bertanggung jawab memantau nilai finansial sewa yang wajib diselesaikan oleh penghuni.

* Atribut (Private):
  * - idTagihan : int — Nomor invoice unik lembar tagihan.
  * - idPenghuni : int — ID penghuni pemilik tagihan.
  * - bulan : string — Periode siklus tagihan bulanan (misal: Oktober 2026).
  * - totalTagihan : double — Jumlah nominal uang yang harus dibayarkan.
  * - jatuhTempo : date — Batas waktu akhir pembayaran sebelum jatuh tempo.
  * - status : string — Kondisi tagihan saat ini (misal: Belum Dibayar, Lunas).
* Method (Public):
  * + generateTagihan() — Menghasilkan lembar objek tagihan baru secara otomatis.
  * + ubahStatus() — Mengubah parameter internal status tagihan.

### 7. Class Pembayaran
Class Pembayaran mencatat pembuktian transaksi keuangan yang diajukan untuk melunasi objek tagihan.

* Atribut (Private):
  * - idPembayaran : int — Identitas unik untuk tiap transaksi masuk.
  * - idTagihan : int — ID tagihan yang akan dilunasi.
  * - tanggalBayar : date — Log tanggal penghuni mengirimkan pembayaran.
  * - jumlah : double — Nominal uang transaksi yang dikirim.
  * - metode : string — Metode transfer (misal: Bank Mandiri, BCA, E-Wallet).
  * - buktiTransfer : string — Jalur berkas gambar/dokumen bukti transfer bank.
  * - status : string — Status validasi (misal: Menunggu Verifikasi, Lunas, Ditolak).
* Method (Public):
  * + uploadBukti() — Menyimpan file tanda transfer dari sisi user ke dalam sistem.
  * + verifikasi() — Mengubah status peninjauan keabsahan dana oleh pengelola.
  * + cetakKuitansi() — Menghasilkan dokumen kuitansi digital resmi berformat cetak.

### 8. Class BiayaOperasional
Class BiayaOperasional berfungsi mencatat semua pengeluaran rutin logistik rumah kos.

* Atribut (Private):
  * - idBiaya : int — Identitas unik pos pengeluaran operasional.
  * - tanggal : date — Tanggal terjadinya pengeluaran kas.
  * - namaBiaya : string — Nama deskripsi alokasi biaya (misal: Gaji Teknisi, Listrik Induk).
  * - jumlah : double — Nominal pengeluaran kas kos.
  * - keterangan : string — Catatan tambahan terkait alokasi pengeluaran.
* Method (Public):
  * + tambahBiaya() — Menambahkan entri record pos pengeluaran operasional baru.
  * + ubahBiaya() — Memperbarui data record pengeluaran yang telah dicatat.

### 9. Class LaporanKeuangan
Class LaporanKeuangan bertanggung jawab memproses akumulasi kalkulasi arus kas kos secara berkala.

* Atribut (Private):
  * - idLaporan : int — Identitas unik berkas laporan keuangan.
  * - periode : string — Rentang jangka laporan (misal: Triwulan I - 2026).
  * - totalPemasukan : double — Akumulasi total dana dari transaksi pembayaran sewa yang sah.
  * - totalPengeluaran : double — Akumulasi total dari seluruh Biaya Operasional.
  * - labaBersih : double — Hasil perhitungan laba bersih (Total Pemasukan - Total Pengeluaran).
* Method (Public):
  * + generateLaporan() — Mengalkulasi secara otomatis data pemasukan dan pengeluaran berkala.
  * + exportPDF() — Mengompilasi ringkasan data laporan keuangan ke format cetak PDF.

---

## Penjelasan Relasi Antar Class

### 1. Relasi Admin dengan Penghuni
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Mengautentikasi / Memvalidasi
* Penjelasan: Satu Admin bertugas mengautentikasi akun atau memvalidasi data registrasi milik banyak penghuni saat pertama kali masuk kos.

### 2. Relasi Admin dengan Kamar
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Mengelola status/info
* Penjelasan: Satu Admin terhubung ke banyak objek Kamar untuk memicu perubahan status ketersediaan atau memperbarui info fasilitas.

### 3. Relasi Admin dengan Keluhan
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Menangani
* Penjelasan: Satu Admin bertanggung jawab memantau dan mengubah status penanganan yang berada di dalam banyak objek Keluhan.

### 4. Relasi Admin dengan LaporanKeuangan
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Membuat & monitoring
* Penjelasan: Satu Admin memicu sistem untuk mengompilasi dan mengunduh berkas yang ada pada objek LaporanKeuangan.

### 5. Relasi Admin dengan BiayaOperasional
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Mencatat & mengelola
* Penjelasan: Satu Admin memasukkan data pengeluaran rutin ke dalam objek BiayaOperasional.

### 6. Relasi Penghuni dengan Kamar
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..0 (atau 1) | Label: Menempati
* Penjelasan: Satu Penghuni secara sah terhubung dengan satu unit Kamar yang ditempatinya. Skala 1..0 menunjukkan kamar bisa kosong atau diisi 1 penghuni.

### 7. Relasi Penghuni dengan Pembayaran
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Melakukan
* Penjelasan: Satu Penghuni dapat menciptakan banyak objek data Pembayaran sepanjang masa tinggal kontrak sewa kos.

### 8. Relasi Penghuni dengan Tagihan
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Memiliki
* Penjelasan: Satu Penghuni memiliki ikatan kepemilikan terhadap banyak lembar objek Tagihan bulanan yang diterbitkan sistem.

### 9. Relasi Penghuni dengan Keluhan
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Membuat
* Penjelasan: Satu Penghuni dapat mencatatkan banyak laporan keluhan sarana prasarana melalui pembuatan objek Keluhan baru.

### 10. Relasi Penghuni dengan Notifikasi
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Menerima
* Penjelasan: Satu Penghuni dapat menerima banyak rekam data pesan dari objek Notifikasi yang dipicu sistem.

### 11. Relasi Tagihan dengan Pembayaran
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..0 (atau 1) | Label: Dibayar melalui
* Penjelasan: Satu lembar objek Tagihan dikaitkan secara penuh dengan satu objek bukti transaksi Pembayaran untuk mengubah parameternya menjadi lunas.

### 12. Relasi LaporanKeuangan dengan Pembayaran
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Mengambil data pemasukan
* Penjelasan: Satu LaporanKeuangan melakukan query penarikan akumulasi nominal data dari banyak objek Pembayaran yang telah berstatus lunas.

### 13. Relasi LaporanKeuangan dengan BiayaOperasional
* Jenis Relasi: Association (Asosiasi) | Multiplisitas: 1 ke 1..* | Label: Mengambil data pengeluaran
* Penjelasan: Satu LaporanKeuangan menarik rekapan total pengeluaran dana dari banyak objek data BiayaOperasional.

---
 
## Kesimpulan

Berdasarkan hasil analisis sistem berjalan, pengelolaan operasional kos secara konvensional (menggunakan media fisik dan aplikasi pesan instan) terbukti rentan terhadap redundansi data, salah catat transaksi keuangan, hingga lambatnya penanganan keluhan fasilitas akibat tidak adanya pusat pelaporan yang terstruktur.

Sebagai solusi, Sistem Informasi Manajemen Kost berbasis web ini dirancang menggunakan pendekatan Analisis dan Perancangan Berorientasi Objek (APBO). Pendekatan ini memisahkan peran sistem secara tegas ke dalam dua aktor utama, yaitu Pengelola (Admin) dan Penghuni Kost, yang saling terhubung melalui protokol keamanan Login.

Melalui arsitektur ini, fungsionalitas sistem tidak lagi berpusat pada kelas aktor secara masif (God Class), melainkan didistribusikan secara modular ke masing-masing objek data yang mandiri (seperti Kamar, Tagihan, Pembayaran, dan Keluhan) yang saling berinteraksi menggunakan metode pengiriman pesan (message passing). Implementasi digital ini diharapkan mampu meniadakan risiko hilangnya arsip data, meningkatkan akurasi rekapitulasi keuangan, serta mengoptimalkan transparansi layanan demi efisiensi bisnis pengelolaan kos secara menyeluruh.

---
