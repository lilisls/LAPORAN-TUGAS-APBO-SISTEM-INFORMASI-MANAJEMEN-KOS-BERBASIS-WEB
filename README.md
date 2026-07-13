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
Pengelola menyimpan data penghuni secara manual menggunakan berkas fisik seperti fotokopi KTP yang ditumpuk di satu tempat. Ketika jumlah penghuni semakin banyak, mencari data satu penghuni saja bisa memakan waktu lama karena harus membuka satu per satu. Belum lagi risiko berkas hilang, rusak terkena air, atau tertukar dengan data penghuni lain.

Sistem digital:
Semua data penghuni tersimpan di database yang terstruktur. Pengelola cukup mengetik nama atau nomor kamar untuk langsung menemukan data yang dicari dalam hitungan detik.

---

# 2. Pembayaran Sewa

Sistem manual:
Pembayaran dicatat di buku tulis dan penghuni mengirim bukti transfer lewat WhatsApp. Pengelola harus mengecek satu per satu chat masuk, lalu mencocokkannya dengan catatan buku secara manual. Jika lupa atau terlewat, bisa terjadi kesalahpahaman antara pengelola dan penghuni soal status pembayaran.

Sistem digital:
Penghuni mengunggah bukti transfer langsung di portal dan status pembayaran langsung berubah secara otomatis. Pengelola tinggal membuka dashboard untuk melihat siapa saja yang sudah dan belum membayar tanpa perlu mengecek WhatsApp satu per satu.


---

# 3. Pengingat Pembayaran

Sistem manual:
Pengelola harus mengingat sendiri siapa yang belum bayar dan menagihnya secara personal. Hal ini sering terasa canggung karena pengelola harus menegur penghuni secara langsung, dan terkadang menagih berulang kali ke orang yang sama.

Sistem digital:
Pengingat pembayaran dikirim otomatis oleh sistem sebelum jatuh tempo. Pengelola tidak perlu lagi menagih secara personal karena sistem yang bertugas mengingatkan, sehingga hubungan antara pengelola dan penghuni tetap nyaman.

---

# 4. Penanganan Keluhan

Sistem manual:
Penghuni menyampaikan keluhan lewat chat WhatsApp yang mudah tenggelam oleh pesan lain. Tidak ada pencatatan resmi, sehingga pengelola bisa saja lupa menindaklanjuti keluhan tertentu. Penghuni pun tidak tahu apakah keluhannya sudah diproses atau belum.

Sistem digital:
Setiap keluhan tercatat sebagai tiket dengan status yang bisa dipantau oleh penghuni secara langsung di portal. Pengelola tidak bisa melewatkan keluhan karena semuanya masuk ke dashboard dan harus ditindaklanjuti satu per satu.

---

# 5. Penyampaian Informasi

Sistem manual:
Informasi penting seperti jadwal kebersihan atau kenaikan harga sewa disampaikan lewat grup WhatsApp. Pesan ini sering tertumpuk oleh obrolan lain dan terlewat oleh penghuni yang jarang membuka grup.

Sistem digital:
Informasi disampaikan lewat fitur notifikasi yang langsung muncul di portal penghuni. Penghuni bisa membuka kembali informasi tersebut kapan saja tanpa khawatir tertumpuk atau terhapus.

# Bagian 3: Skenario Sistem / Use Case

## Pemetaan Aktor & Hak Akses

Berikut adalah pemetaan aktor yang terlibat dalam Sistem Informasi Manajemen Kos beserta hak akses dan fungsionalitasnya yang telah disesuaikan dengan prinsip *Object-Oriented Programming* (OOP):

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola Kos (Admin)** | Memiliki akses penuh terhadap seluruh data operasional sistem melalui autentikasi untuk memicu fungsi manajemen entitas. | * Melakukan `Login` & `Logout`<br>* Kelola Data Penghuni<br>* Kelola Data Kamar (Alokasi Kamar)<br>* Memverifikasi Pembayaran<br>* Memproses Keluhan<br>* Memproses Check-out<br>* Kelola Biaya Operasional<br>* Melihat Laporan Keuangan<br>* Kelola Informasi & Pengumuman |
| **Penghuni Kos (User)** | Memiliki akses terbatas pada manipulasi data pribadi dan pengiriman data objek yang berelasi dengan kamarnya sendiri. | * Melakukan `Login` & `Logout`<br>* Melihat Tagihan<br>* Upload Bukti Pembayaran<br>* Melihat Riwayat Pembayaran<br>* Membuat Keluhan<br>* Melihat Notifikasi & Pengumuman |

---

## Detail Use Case

Setiap skenario di bawah ini dirancang dengan prinsip *Single Responsibility* (Satu Use Case fokus pada aksi aktif dari satu aktor utama):

### 1. Use Case: Kelola Data Penghuni
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Menambahkan, mengubah, atau menghapus data identitas penghuni kos ke dalam database sistem.  
* **Alur Interaksi:**
  1. Admin memilih menu "Kelola Data Penghuni".
  2. Admin memilih opsi "Tambah Penghuni Baru".
  3. Admin menginput data identitas penghuni (Nama, No HP, Kontak Darurat, Username, Password).
  4. Sistem memvalidasi inputan dan menyimpan data objek Penghuni baru.
* **Output / Hasil Akhir:** Objek data penghuni baru berhasil dibuat dan tersimpan.

### 2. Use Case: Kelola Data Kamar (Alokasi Kamar)
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Mengatur informasi kamar dan memetakan penempatan kamar untuk penghuni baru.  
* **Alur Interaksi:**
  1. Admin membuka menu "Kelola Data Kamar".
  2. Admin memilih nomor kamar yang berstatus "Kosong".
  3. Admin mengalokasikan kamar tersebut kepada salah satu ID Penghuni.
  4. Sistem memperbarui atribut status kamar menjadi "Terisi".
* **Output / Hasil Akhir:** Status kamar berubah di dalam sistem dan penempatan kamar terdata.

### 3. Use Case: Upload Bukti Pembayaran
* **Aktor Utama:** Penghuni Kos  
* **Tujuan:** Mengunggah berkas bukti transaksi transfer bank untuk melunasi tagihan kos bulanan.  
* **Alur Interaksi:**
  1. Penghuni memilih menu "Melihat Tagihan".
  2. Penghuni memilih tagihan aktif lalu menekan opsi "Upload Bukti".
  3. Penghuni mengunggah gambar resi transfer dan menekan tombol kirim.
  4. Sistem membuat objek Pembayaran baru dan mengubah status objek Tagihan terkait menjadi "Menunggu Verifikasi".
* **Output / Hasil Akhir:** Objek pembayaran tercipta dan status tagihan terbarui.

### 4. Use Case: Memverifikasi Pembayaran
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Melakukan pengecekan terhadap validitas bukti transfer yang diunggah oleh penghuni kos.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memverifikasi Pembayaran".
  2. Admin memilih data pembayaran yang berstatus "Menunggu Verifikasi".
  3. Admin memeriksa kesesuaian gambar bukti transfer dengan mutasi bank asli.
  4. Admin menekan tombol "Verifikasi Sukses" (atau "Tolak" jika tidak sesuai).
  5. Sistem mengubah status Pembayaran menjadi "Lunas" dan meneruskan pembaruan data ke kelas Laporan Keuangan.
* **Output / Hasil Akhir:** Transaksi dinyatakan sah dan status tagihan berubah menjadi lunas.

### 5. Use Case: Membuat Keluhan
* **Aktor Utama:** Penghuni Kos  
* **Tujuan:** Melaporkan adanya kendala atau kerusakan pada fasilitas kos agar terdata oleh pengelola.  
* **Alur Interaksi:**
  1. Penghuni membuka menu "Membuat Keluhan".
  2. Penghuni mengisi kategori keluhan, deskripsi permasalahan, dan mengunggah foto pendukung.
  3. Sistem membuat objek data Keluhan baru dengan status awal berupa "Pending".
* **Output / Hasil Akhir:** Laporan keluhan baru terdaftar di dalam sistem antrean admin.

### 6. Use Case: Memproses Keluhan
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Merespons, menindaklanjuti, dan memperbarui status penanganan atas keluhan fasilitas yang dikirim oleh penghuni.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memproses Keluhan".
  2. Admin memilih keluhan berstatus "Pending" dan mengubah statusnya menjadi "Sedang Diproses" saat teknisi mulai bekerja.
  3. Setelah perbaikan fasilitas selesai dilakukan, Admin menekan tombol "Selesaikan Keluhan".
  4. Sistem memperbarui status objek Keluhan tersebut menjadi "Selesai".
* **Output / Hasil Akhir:** Siklus hidup objek keluhan ditutup dengan status akhir selesai.

### 7. Use Case: Memproses Check-out
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Menyelesaikan masa sewa penghuni, mengarsipkan data, dan mengosongkan kembali slot kamar.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memproses Check-out".
  2. Admin memilih nama penghuni yang masa sewanya telah berakhir atau mengajukan keluar.
  3. Admin memvalidasi administrasi akhir dan menyelesaikan sewa.
  4. Sistem mengubah status objek Kamar terkait menjadi "Kosong" dan mengarsipkan record Penghuni tersebut.
* **Output / Hasil Akhir:** Kamar kembali berstatus kosong dan siap dialokasikan ulang.

### 8. Use Case: Kelola Biaya Operasional & Keuangan
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Mencatat pengeluaran rutin kos bulanan serta memantau ringkasan neraca laba bersih.  
* **Alur Interaksi:**
  1. Admin membuka menu "Kelola Biaya Operasional".
  2. Admin menginput nominal dan detail pengeluaran kos (misal: listrik, air, gaji penjaga).
  3. Sistem menyimpan data pengeluaran dan secara otomatis memperbarui kalkulasi pada objek Laporan Keuangan.
* **Output / Hasil Akhir:** Data pengeluaran kos tercatat dan terakumulasi ke dalam neraca keuangan.

---

## Diagram Use Case

### Diagram Use Case

Di bawah ini adalah representasi visual dari hubungan interaksi antar aktor terhadap fungsi-fungsi di dalam Sistem Informasi Manajemen Kos:

<img width="307" height="580" alt="USE CASE DIAGRAM - SI MANAJEMEN KOST drawio" src="https://github.com/user-attachments/assets/4f5df610-c4cd-48ed-bea0-b4aa8e12b2f0" />



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

# Sequence Diagram
## 1. Kelola Biaya Operasional (Pengelola)
### Pencatatan dan manajemen pengeluaran operasional kos di luar fasilitas langsung.
Alur Proses:
1. Pengelola memilih menu kelola biaya operasional pada antarmuka sistem.
2. Sistem memuat daftar riwayat pencatatan biaya operasional.
3. Pengelola menginput variabel pengeluaran baru (nama biaya, nominal jumlah, keterangan, dan tanggal).
4. Sistem mengeksekusi penambahan data ke dalam database dan memperbarui tampilan log pengeluaran.
<img width="735" height="515" alt="Pengelola-Kelola Biaya Operasional drawio" src="https://github.com/user-attachments/assets/87e83326-e02d-4b36-b0f0-2f1306885f7b" />

## 2. Memproses Check-out (Pengelola)
### Prosedur administratif penyelesaian masa sewa dan pembebasan kamar penghuni.
Alur Proses:
1. Pengelola memuat data penghuni dan memvalidasi kondisi fisik kamar (inspeksi).
2. Blok Opsional: Jika terdapat kerusakan, pengelola menginput nominal pemotongan uang deposit.
3. Pengelola mengeksekusi proses check-out.
4. Sistem mengarsipkan data penghuni dan mengembalikan status kamar menjadi "KOSONG".
<img width="679" height="470" alt="Pengelola-Memproses Checkout drawio" src="https://github.com/user-attachments/assets/f5c1fab9-6feb-455a-9975-c3ad07b3e1fa" />

## 3. Memproses Keluhan (Pengelola)
### Tindak lanjut pengelola terhadap laporan kendala fasilitas dari penghuni.
Alur Proses:
1. Pengelola membuka daftar keluhan yang berstatus "ANTREAN".
2. Pengelola merespons tiket (status berubah menjadi "DIPROSES") dan meneruskan instruksi ke Teknisi.
3. Teknisi mengeksekusi perbaikan fasilitas.
4. Pengelola menutup tiket keluhan (status berubah menjadi "SELESAI") dan sistem menotifikasi penghuni.
<img width="795" height="594" alt="Pengelola-Memproses Keluhan drawio" src="https://github.com/user-attachments/assets/3863d501-93f2-4931-9a94-d2efa8c994ab" />

## 4. Memverifikasi Pembayaran (Pengelola)
### Proses pengecekan dan validasi bukti pembayaran yang dikirimkan oleh penghuni.
Alur Proses:
1. Sistem menampilkan daftar pembayaran dengan status "MENUNGGU VERIFIKASI".
2. Pengelola memilih dan memverifikasi kesesuaian nominal pada dokumen bukti pembayaran.
3. Blok Alternatif (Validasi): <br> Valid: Status diubah menjadi "LUNAS" dan sistem menerbitkan kuitansi. <br> Tidak Valid: Status dikembalikan ke "BELUM DIBAYAR" dan sistem mengirimkan notifikasi penolakan ke penghuni.
<img width="964" height="825" alt="Pengelola-Memverifikasi Pembayaran drawio" src="https://github.com/user-attachments/assets/0d23655c-28f3-4ea8-b570-1cdf61422194" />

## 5. Kelola Data Kamar (Pengelola)
### Proses pemeliharaan master data kamar termasuk pembaruan ketersediaan, harga, dan fasilitas.
Alur Proses:
1. Pengelola menavigasi ke halaman pengelolaan kamar.
2. Sistem memuat daftar seluruh kamar beserta rincian statusnya.
3. Pengelola memilih kamar dan mengubah detail informasi (tipe kamar, harga, atau status).
4. Sistem menyimpan perubahan ke database dan memperbarui tampilan daftar kamar.
<img width="801" height="420" alt="Pengelola-Kelola Data Kamar drawio" src="https://github.com/user-attachments/assets/36ed79c0-b8dc-4311-b842-0e8188744f46" />

## 6. Kelola Data Penghuni (Pengelola)
### Pencatatan data penghuni baru untuk mengelola informasi penyewa kos.
Alur Proses:
1. Pengelola memuat daftar kamar dengan status "KOSONG".
2. Pengelola menginput data calon penghuni (biodata, deposit, jatuh tempo).
3. Sistem membuat entri data penghuni baru ke dalam database.
4. Sistem mengubah status kamar terkait menjadi "DIHUNI".
<img width="714" height="339" alt="Pengelola-Kelola Data Penghuni drawio" src="https://github.com/user-attachments/assets/d1f8d76c-1bea-4f69-9543-cc806996d0fd" />

## 7. Kelola Informasi & Pengumuman (Pengelola)
### Proses pembuatan dan penyebaran pemberitahuan atau informasi kepada penghuni kos.
Alur Proses:
1. Pengelola membuka menu kelola informasi dan pengumuman.
2. Pengelola memasukkan detail pesan (judul, isi pesan, jenis/target notifikasi).
3. Pengelola memerintahkan sistem untuk mengirimkan informasi.
4. Sistem membuat entri ke entitas Notifikasi dan mendistribusikannya ke portal penghuni yang dituju.
<img width="929" height="335" alt="Pengelola-Kelola Informasi dan Pengumuman drawio" src="https://github.com/user-attachments/assets/d62b0fef-6277-407d-b9f6-88d35496dc6f" />

## 8. Melihat Laporan Keuangan (Pengelola)
### Agregasi data pemasukan dan pengeluaran operasional untuk menghasilkan rekapitulasi keuangan.
Alur Proses:
1. Pengelola meminta sistem generate laporan keuangan berdasarkan parameter periode waktu.
2. Sistem mengambil data pemasukan (tagihan lunas) dan pengeluaran (biaya operasional).
3. Sistem mengalkulasi total pengeluaran dan total pemasukan untuk menghasilkan nilai laba bersih.
4. Sistem merender data keuangan dalam antarmuka grafik.
5. Blok Opsional: Pengelola memicu fungsi export untuk mengunduh laporan dalam format PDF.
<img width="899" height="791" alt="Pengelola-Melihat Laporan Keuangan drawio" src="https://github.com/user-attachments/assets/ed075c5a-1b40-4183-948c-0443a126d385" />

## 9. Login (Pengelola)
### Proses autentikasi untuk memverifikasi hak akses pengelola ke dalam sistem.
Alur Proses:
1. Pengelola membuka halaman login.
2. Pengelola menginput kredensial (username dan password).
3. Sistem memvalidasi data ke dalam entitas Admin.
4. Blok Alternatif: <br> Valid: Sistem mengarahkan ke Dashboard Admin. <br> Tidak Valid: Sistem menolak akses dan menampilkan pesan error.
<img width="716" height="394" alt="Pengelola-Login drawio" src="https://github.com/user-attachments/assets/f18b23e6-a8c3-46f6-85d5-5c75cacf05f9" />

## 10. Login (Penghuni)
### Proses autentikasi untuk memverifikasi hak akses penghuni ke dalam portal kos.
Alur Proses:
1. Penghuni membuka halaman login.
2. Penghuni menginput kredensial (username dan password).
3. Sistem mencocokkan data pada entitas Penghuni.
4. Blok Alternatif: <br> Valid: Sistem mengarahkan ke Dashboard Penghuni. <br> Tidak Valid: Sistem menampilkan peringatan kredensial salah.
<img width="711" height="394" alt="Penghuni-Login drawio" src="https://github.com/user-attachments/assets/162fa7a2-a0d9-434f-981d-76f55ae91289" />

## 11. Melihat Notifikasi & Pengumuman (Penghuni)
### Alur pengecekan informasi, pengingat, atau pesan dari pengelola oleh penghuni.
Alur Proses:
1. Penghuni memilih menu notifikasi pada antarmuka sistem.
2. Sistem mengambil log pengumuman dan notifikasi terbaru yang ditujukan untuk penghuni tersebut.
3. Sistem merender daftar pemberitahuan di layar.
4. Blok Opsional: Penghuni membuka pesan spesifik, lalu sistem menandai status notifikasi menjadi "DIBACA".
<img width="732" height="408" alt="Penghuni-Melihat Notifikasi dan Pengumuman drawio" src="https://github.com/user-attachments/assets/b192e1b6-6f40-4a58-bc03-d1f8fb2e82b4" />

## 12. Membuat Keluhan (Penghuni)
### Mekanisme pengajuan laporan jika terdapat kendala pada fasilitas kos oleh penghuni.
Alur Proses:
1. Penghuni memilih menu pembuatan keluhan.
2. Sistem menampilkan formulir pelaporan.
3. Penghuni mengisi atribut keluhan (kategori, deskripsi) dan mengunggah foto pendukung.
4. Blok Alternatif: <br> Lengkap: Sistem merekam entri tiket baru dan memberikan konfirmasi keberhasilan. <br> Tidak Lengkap: Sistem meminta pengguna melengkapi formulir yang diwajibkan.
<img width="787" height="376" alt="Penghuni-Membuat Keluhan drawio" src="https://github.com/user-attachments/assets/5ee96d77-d92f-4ca3-8ada-c325aa4e7916" />

## 13. Melihat Riwayat Pembayaran (Penghuni)
### Modul bagi penghuni untuk memantau rekam jejak transaksi yang telah diselesaikan.
Alur Proses:
1. Penghuni mengakses menu riwayat pembayaran.
2. Sistem melakukan kueri riwayat transaksi terkait ke database.
3. Blok Alternatif: <br> Tersedia: Sistem merender daftar historis pembayaran. <br> Kosong: Sistem menampilkan pesan bahwa riwayat masih kosong.
4. Blok Opsional: Penghuni memilih riwayat tertentu untuk melihat detail atau mencetak kuitansi.
<img width="788" height="502" alt="Penghuni-Melihat Riwayat Pembayaran drawio" src="https://github.com/user-attachments/assets/cbfa6940-4dd6-4821-bb52-0577496f7579" />

## 14. Upload Bukti Pembayaran (Penghuni)
### Prosedur pengiriman dokumen bukti transfer untuk pelunasan tagihan oleh penghuni.
Alur Proses:
1. Penghuni menekan tombol bayar pada rincian tagihan aktif.
2. Sistem merender antarmuka informasi rekening tujuan ibu kos.
3. Penghuni mengunggah dokumen bukti pembayaran (format JPG/PNG/PDF, maksimal 5MB).
4. Blok Alternatif: <br> Valid: Sistem menyimpan dokumen, mengubah status tagihan menjadi "MENUNGGU VERIFIKASI", dan menampilkan notifikasi sukses. <br> Tidak Valid: Sistem menolak unggahan dan menampilkan peringatan batas ukuran atau format.
<img width="956" height="484" alt="Penghuni-Upload Bukti Pembayaran drawio" src="https://github.com/user-attachments/assets/e6610f14-850b-449a-827e-94595f2e3459" />

## 15. Melihat Tagihan (Penghuni)
### Proses pemuatan rincian tagihan sewa kamar dan beban fasilitas aktif milik penghuni.
Alur Proses:
1. Penghuni memilih menu tagihan pada portal.
2. Sistem mengambil data tagihan aktif berdasarkan identitas penghuni.
3. Blok Alternatif: <br> Ditemukan: Sistem merender rincian biaya (sewa, listrik, air) dan total tagihan. <br> Kosong: Sistem menampilkan pesan tidak ada tagihan aktif.
4. Blok Opsional: Jika status tagihan "BELUM DIBAYAR", sistem memunculkan peringatan kuning batas waktu jatuh tempo.
<img width="776" height="371" alt="Penghuni-Melihat Tagihan drawio" src="https://github.com/user-attachments/assets/baf2e79e-c324-4be9-a575-0b9981578f18" />

---

# State Diagram
<img width="1577" height="1189" alt="APBO - State Diagram-Mix drawio" src="https://github.com/user-attachments/assets/ee8daea0-391c-4163-b502-e182261f299b" />

## 1. Alur Pembayaran
**Tagihan Dibuat**  
Sistem secara otomatis membuat tagihan bulanan untuk setiap penghuni. Status awal tagihan adalah "belum dibayar".

**Menunggu Pembayaran**  
Setelah jatuh tempo tiba, sistem mengirim notifikasi pengingat ke penghuni. Penghuni kemudian melakukan transfer dan mengunggah bukti pembayaran ke portal.

**Menunggu Verifikasi**  
Setelah bukti diunggah, status tagihan berubah otomatis menjadi "menunggu verifikasi". Admin menerima notifikasi dan melakukan pengecekan mutasi rekening.

**Pembayaran Ditolak**  
Jika bukti transfer tidak valid atau nominal tidak sesuai, admin menolak dan mengirim notifikasi alasan ke penghuni. Penghuni bisa mengulang proses upload dari awal.

**Lunas**  
Jika admin memverifikasi pembayaran berhasil, status tagihan berubah menjadi lunas dan sistem menerbitkan kuitansi digital otomatis.

**Riwayat Tersimpan**  
Data pembayaran yang sudah lunas otomatis masuk ke laporan keuangan dan tersimpan sebagai riwayat transaksi penghuni.

## 2. Alur Keluhan
**Keluhan Dibuat**  
Penghuni membuat laporan keluhan baru dengan mengisi kategori kerusakan, deskripsi masalah, dan melampirkan foto bukti kerusakan.

**Antrean**  
Keluhan masuk ke dashboard admin dengan status antrean. Admin melihat dan menilai keluhan untuk kemudian mengalokasikan teknisi yang sesuai.

**Diproses**  
Teknisi yang sudah dialokasikan mulai mengerjakan perbaikan. Status ini memberi tahu penghuni bahwa keluhannya sedang ditangani. Jika teknisi tidak bisa menyelesaikan, admin bisa menarik tiket kembali ke antrean untuk re-alokasi.

**Menunggu Konfirmasi**  
Teknisi selesai mengerjakan perbaikan dan melaporkan hasilnya ke admin. Admin melakukan verifikasi apakah perbaikan sudah benar-benar selesai. Jika belum, tiket dikembalikan ke state Diproses.

**Selesai**  
Admin menutup keluhan/tiket dan penghuni dapat melihat pembaruan status di portal mereka.

## 3. Alur Kamar
**Kosong**  
Kamar dalam kondisi tersedia dan tampil di daftar kamar yang bisa dialokasikan. Admin bisa melihat detail kamar seperti tipe, harga, dan fasilitas.

**Proses Onboarding**  
Admin menginput data lengkap penghuni baru seperti KTP, kontak darurat, durasi sewa, deposit, dan tanggal jatuh tempo. Jika proses dibatalkan, kamar kembali ke status kosong.

**Dihuni**  
Penghuni resmi check-in, status kamar terkunci sehingga tidak bisa dialokasikan ke orang lain. Akun penghuni aktif dan bisa menggunakan semua fitur sistem seperti pembayaran dan pengiriman keluhan.

**Proses Check-out**  
Penghuni mengajukan keluar dan admin melakukan inspeksi akhir kamar. Jika ada kerusakan, admin mencatat potongan dari deposit. Jika penghuni membatalkan check-out, status kamar kembali ke Dihuni.

**Kamar Dikosongkan**  
Proses check-out selesai dieksekusi admin. Data penghuni diarsipkan ke daftar alumni dan deposit dikembalikan atau dipotong sesuai hasil inspeksi.

**Kosong (lagi)**  
Status kamar direset kembali menjadi kosong dan siap untuk dialokasikan ke penghuni berikutnya. Siklus berulang dari awal.

## 4. Alur Notifikasi
**Draft**  
State awal ketika admin membuat notifikasi atau pengingat di dalam sistem. Notifikasi belum dikirimkan ke penghuni, masih dalam tahap penyusunan konten oleh admin.

**Dijadwalkan**  
Notifikasi sudah selesai dibuat dan dijadwalkan untuk dikirim pada waktu tertentu. Misalnya pengingat pembayaran yang dijadwalkan dikirim H-3 sebelum jatuh tempo.

**Dikirim**  
Sistem berhasil mengirimkan notifikasi ke penghuni. Pada state ini notifikasi sudah masuk ke portal penghuni, namun belum tentu sudah dibuka atau dibaca.

**Diterima**  
Notifikasi berhasil diterima di sisi penghuni. State ini mengonfirmasi bahwa pengiriman tidak gagal dan notifikasi sudah tersedia untuk dilihat penghuni.

**Dibaca**  
Penghuni membuka dan membaca notifikasi. State ini penting untuk admin agar bisa memantau apakah informasi atau pengingat sudah benar-benar sampai dan diperhatikan oleh penghuni.

**Kadaluwarsa**  
Jika notifikasi melewati masa berlakunya tanpa dibaca oleh penghuni, maka statusnya berubah menjadi kadaluwarsa. Misalnya pengingat pembayaran yang tidak dibaca padahal sudah lewat jatuh tempo.

## Kesimpulan

Berdasarkan hasil wawancara dan analisis sistem yang sedang berjalan, dapat disimpulkan bahwa pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai permasalahan signifikan, seperti kesulitan dalam pencatatan dan pencarian data penghuni, ketidakefisienan dalam monitoring pembayaran, serta kurang optimalnya komunikasi antara pengelola dan penghuni. Permasalahan ini diperkuat oleh kondisi nyata di lapangan, seperti penggunaan buku tulis dan WhatsApp sebagai media utama, yang terbukti rentan terhadap kesalahan, kehilangan data, serta informasi yang terlewat.

Oleh karena itu, pengembangan sistem informasi manajemen kos berbasis web menjadi solusi yang relevan dan dibutuhkan, dengan mempertimbangkan dua aktor utama yaitu pengelola sebagai admin dan penghuni sebagai user. Sistem ini tidak hanya berfungsi untuk meningkatkan efisiensi pengelolaan data dan operasional kos, tetapi juga memberikan kemudahan akses, transparansi informasi, serta peningkatan kualitas komunikasi. Dengan adanya fitur seperti pencatatan pembayaran otomatis, notifikasi pengingat, serta manajemen keluhan terintegrasi, sistem diharapkan mampu mengatasi permasalahan yang ada sekaligus meningkatkan kualitas layanan kos secara keseluruhan.

# Activity Diagram

## 1.Activity Diagram Pendaftaran Penghuni dan Alokasi Kamar

<img width="741" height="731" alt="1" src="https://github.com/user-attachments/assets/064ac7b7-a231-481f-bf6a-3ca8ca0545cc" />


Activity Diagram ini menjelaskan proses pendaftaran penghuni baru dan alokasi kamar yang dilakukan oleh pengelola kos. Proses dimulai ketika pengelola membuka menu data kamar dan memilih kamar yang masih berstatus kosong. Selanjutnya pengelola menginput data penghuni seperti nama, nomor identitas, nomor telepon, dan informasi pendukung lainnya. Sistem kemudian melakukan pengecekan terhadap kelengkapan data yang dimasukkan. Jika data belum lengkap, sistem akan menampilkan pesan kesalahan dan pengelola diminta melengkapi data terlebih dahulu. Jika data sudah lengkap, sistem menyimpan data penghuni ke dalam database dan mengubah status kamar menjadi dihuni. Setelah proses berhasil, sistem menampilkan notifikasi bahwa pendaftaran penghuni telah berhasil dilakukan dan proses berakhir.

---

## 2.Activity Diagram Pelunasan Tagihan Sewa Bulanan

<img width="821" height="981" alt="2 drawio" src="https://github.com/user-attachments/assets/54ad3ab3-9d2e-419a-90a9-bca95036bfc7" />


Activity Diagram ini menjelaskan proses pembayaran tagihan kos oleh penghuni dan proses verifikasi oleh pengelola. Proses dimulai ketika penghuni masuk ke sistem dan melihat tagihan yang harus dibayar. Selanjutnya penghuni melakukan pembayaran melalui transfer dan mengunggah bukti pembayaran ke dalam sistem. Sistem kemudian menyimpan bukti pembayaran dan mengubah status tagihan menjadi menunggu verifikasi. Pengelola menerima notifikasi adanya pembayaran baru dan melakukan pengecekan terhadap bukti pembayaran yang diunggah. Jika pembayaran tidak sesuai atau bukti pembayaran tidak valid, sistem mengubah status pembayaran menjadi ditolak dan penghuni diminta mengunggah ulang bukti pembayaran. Jika pembayaran valid, sistem mengubah status tagihan menjadi lunas dan menyimpan data pembayaran ke dalam riwayat transaksi. Setelah proses selesai, sistem menampilkan notifikasi bahwa pembayaran berhasil diverifikasi.

---

## 3.Activity Diagram Laporan Keluhan

<img width="955" height="1091" alt="3 drawio" src="https://github.com/user-attachments/assets/3e5cea25-90fb-4a42-b5a7-90e6e99a8611" />


Activity Diagram ini menjelaskan proses penyampaian dan penanganan keluhan yang dilakukan oleh penghuni dan pengelola kos. Proses dimulai ketika penghuni membuka menu keluhan dan mengisi formulir keluhan yang berisi kategori masalah, deskripsi kerusakan, serta foto pendukung apabila diperlukan. Setelah data dikirim, sistem menyimpan laporan keluhan dan mengubah status keluhan menjadi antrean. Pengelola kemudian melihat daftar keluhan yang masuk dan mulai melakukan penanganan terhadap keluhan tersebut. Selama proses penanganan berlangsung, sistem mengubah status keluhan menjadi diproses. Setelah masalah berhasil diselesaikan, pengelola menutup laporan keluhan dan sistem mengubah status menjadi selesai. Selanjutnya sistem mengirimkan notifikasi kepada penghuni bahwa keluhan telah ditangani dan proses berakhir.

---

## 4.Activity Diagram Pengosongan Kamar (Check-Out)

<img width="891" height="761" alt="4 drawio" src="https://github.com/user-attachments/assets/f0d04d83-46de-4c8b-8990-5dde43190b3d" />

Activity Diagram ini menjelaskan proses pengosongan kamar ketika penghuni akan mengakhiri masa sewa. Proses dimulai ketika penghuni mengajukan permohonan check-out kepada pengelola. Selanjutnya pengelola melakukan pemeriksaan kondisi kamar untuk memastikan tidak terdapat kerusakan atau kewajiban yang belum diselesaikan. Jika ditemukan kerusakan, pengelola dapat mencatat biaya perbaikan yang diperlukan. Setelah proses pemeriksaan selesai, pengelola melakukan proses check-out pada sistem. Sistem kemudian mengarsipkan data penghuni dan mengubah status kamar dari dihuni menjadi kosong. Setelah seluruh proses selesai, kamar kembali tersedia untuk digunakan oleh penghuni berikutnya.

---

## 5.Activity Diagram Rekapitulasi Keuangan dan Operasional

<img width="791" height="931" alt="5 drawio" src="https://github.com/user-attachments/assets/29ed1642-6838-404d-b423-1ed6631c42a9" />


Activity Diagram ini menjelaskan proses pembuatan laporan keuangan yang digunakan oleh pengelola kos untuk memantau pemasukan dan pengeluaran. Proses dimulai ketika pengelola membuka menu laporan keuangan pada sistem. Sistem kemudian mengambil data pembayaran penghuni sebagai sumber pemasukan dan data biaya operasional sebagai sumber pengeluaran. Selanjutnya sistem melakukan perhitungan total pemasukan, total pengeluaran, serta laba atau selisih keuangan yang diperoleh. Berdasarkan hasil perhitungan tersebut, sistem menghasilkan laporan keuangan secara otomatis dan menampilkannya kepada pengelola. Pengelola dapat melihat ringkasan laporan maupun mengunduh laporan tersebut sebagai dokumentasi. Setelah laporan berhasil ditampilkan, proses berakhir.

---

### LINK VIDIO PRESENTASI
https://youtu.be/Ht3Yw0b4vEQ?si=3xYI0jfAnSTSZf1V

---
