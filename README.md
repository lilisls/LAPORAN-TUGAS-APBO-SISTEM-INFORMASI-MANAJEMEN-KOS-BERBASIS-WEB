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
Sistem Informasi Manajemen merupakan sistem yang digunakan untuk mengelola dan mengolah data menjadi informasi yang berguna dalam mendukung operasional dan pengambilan keputusan. Dalam pengelolaan kos, sistem ini berperan dalam mengintegrasikan data penyewa, status kamar, serta riwayat pembayaran ke dalam satu sistem yang terstruktur.

Dengan adanya sistem yang terintegrasi, pengelola dapat memantau kondisi kos secara lebih efektif tanpa harus melakukan pencatatan secara manual, sehingga mengurangi risiko kesalahan dan meningkatkan efisiensi pengelolaan.

> **Referensi:**  [Sistem Informasi Manajemen (2021)](https://ojs.stmikdharmapalariau.ac.id/index.php/repository/article/view/590/340)


### 2. Sistem Berbasis Web
Sistem berbasis web merupakan sistem yang dapat diakses melalui browser dengan memanfaatkan jaringan internet, sehingga memungkinkan pengguna memperoleh informasi dengan lebih fleksibel. Dalam pengelolaan kos, sistem ini memberikan kemudahan dalam mengakses informasi terkait ketersediaan kamar, data penyewa, serta transaksi secara real-time.

Penelitian yang dilakukan oleh Zefanya Yulius Kurnia dan Marvin Chandra Wijaya (2024) menunjukkan bahwa penerapan sistem informasi kos berbasis web mampu meningkatkan efisiensi pengelolaan serta mempermudah akses informasi bagi pengguna. Hal ini membuktikan bahwa sistem berbasis web merupakan solusi yang efektif dalam mendukung pengelolaan kos secara modern.

> **Referensi:**  [Web-based information system for boarding house information (IJSRM, 2024)](https://doi.org/10.18535/ijsrm/v12i03.ec11)

### 3. Sistem Pembayaran Digital
Sistem pembayaran digital merupakan mekanisme yang digunakan untuk mendukung proses transaksi secara elektronik, yang mencakup pengelolaan tagihan (invoicing) serta pencatatan pembayaran secara sistematis. Dalam konteks e-business, sistem ini berperan dalam meningkatkan efisiensi transaksi, mempermudah proses pembayaran, serta memastikan keamanan dan keandalan dalam pengelolaan data pembayaran.

> **Referensi:** [Billing and Payment Systems (Springer, 2023)](https://link.springer.com/chapter/10.1007/978-3-031-39626-7_6#citeas)

### 4. Manajemen Keluhan
Manajemen keluhan merupakan proses pengelolaan laporan atau pengaduan dari pengguna terhadap suatu layanan. Penerapan sistem ini memungkinkan segala keluhan dicatat dan diproses secara terstruktur, sehingga memudahkan pengelola dalam melakukan tindak lanjut serta meningkatkan kualitas pelayanan. Selain itu, sistem manajemen keluhan juga membantu menciptakan transparansi dan komunikasi yang lebih efektif antara pengguna dan pengelola.

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

## Bagian 3: Skenario Sistem / Use Case

### Pemetaan Aktor & Hak Akses

Berikut adalah pemetaan aktor yang terlibat dalam Sistem Informasi Manajemen Kos beserta hak akses dan fungsionalitasnya berdasarkan dokumen perancangan resmi:

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola Kos (Admin)** | Memiliki akses penuh terhadap seluruh data dan fitur dalam sistem, termasuk data penghuni, kamar, pembayaran, dan laporan keuangan. | * Mengelola data penghuni<br>* Mengelola data kamar dan status ketersediaan<br>* Memproses check-in dan check-out penghuni<br>* Memverifikasi pembayaran kos<br>* Melihat dashboard dan laporan keuangan<br>* Mengelola dan menanggapi keluhan penghuni<br>* Mengelola informasi dan notifikasi |
| **Penghuni Kos (User)** | Memiliki akses terbatas pada data pribadi dan layanan yang berkaitan dengan kamar yang ditempati. | * Melihat informasi kamar dan tagihan bulanan<br>* Mengunggah bukti pembayaran<br>* Melihat status dan riwayat pembayaran<br>* Mengirim keluhan atau pengaduan fasilitas<br>* Menerima notifikasi dan informasi penting |

---

### Detail Use Case

#### 1. Pendaftaran Penghuni dan Alokasi Kamar
* **Aktor:** Pengelola Kos (Admin)  
* **Tujuan:** Menambahkan data penghuni baru ke dalam sistem dan menetapkan kamar yang akan ditempati.  
* **Alur Interaksi:**
  1. Admin membuka menu manajemen kamar.
  2. Admin memilih kamar yang masih berstatus kosong.
  3. Admin menginput data penghuni, seperti identitas, kontak, durasi sewa, dan tanggal masuk.
  4. Sistem menyimpan data penghuni.
  5. Sistem mengubah status kamar menjadi dihuni.
* **Output / Hasil Akhir:** Data penghuni tersimpan dalam sistem dan kamar berhasil dialokasikan.

#### 2. Pelunasan Tagihan Sewa Bulanan
* **Aktor:** Penghuni Kos dan Pengelola Kos (Admin)  
* **Tujuan:** Memfasilitasi proses pembayaran tagihan kos dan verifikasi pembayaran oleh admin.  
* **Alur Interaksi:**
  1. Penghuni membuka menu tagihan pada sistem.
  2. Penghuni melihat nominal tagihan yang harus dibayar.
  3. Penghuni melakukan pembayaran melalui transfer.
  4. Penghuni mengunggah bukti pembayaran ke sistem.
  5. Sistem mengubah status pembayaran menjadi menunggu verifikasi.
  6. Admin memeriksa bukti pembayaran.
  7. Admin menyetujui atau menolak pembayaran.
* **Output / Hasil Akhir:** Status pembayaran diperbarui dan riwayat pembayaran tersimpan dalam sistem.

#### 3. Laporan Keluhan Fasilitas
* **Aktor:** Penghuni Kos dan Pengelola Kos (Admin)  
* **Tujuan:** Memfasilitasi penghuni dalam menyampaikan keluhan fasilitas agar dapat terdokumentasi dan ditindaklanjuti oleh pengelola.  
* **Alur Interaksi:**
  1. Penghuni membuka menu keluhan.
  2. Penghuni mengisi kategori keluhan dan deskripsi masalah.
  3. Penghuni mengunggah foto pendukung jika diperlukan.
  4. Sistem menyimpan laporan keluhan.
  5. Admin melihat laporan keluhan yang masuk.
  6. Admin menindaklanjuti keluhan dan memperbarui status penanganan.
  7. Keluhan dinyatakan selesai setelah ditangani.
* **Output / Hasil Akhir:** Keluhan tersimpan dalam sistem dan status penanganannya dapat dipantau.

#### 4. Pengosongan Kamar (Check-out)
* **Aktor:** Pengelola Kos (Admin)  
* **Tujuan:** Menyelesaikan masa tinggal penghuni dan mengubah status kamar agar dapat digunakan kembali.  
* **Alur Interaksi:**
  1. Penghuni mengajukan atau menginformasikan rencana check-out kepada admin.
  2. Admin melakukan pemeriksaan kamar.
  3. Admin menyelesaikan administrasi akhir penghuni.
  4. Sistem mengarsipkan data penghuni.
  5. Sistem mengubah status kamar menjadi kosong.
* **Output / Hasil Akhir:** Data penghuni diarsipkan dan status kamar berubah menjadi kosong.

#### 5. Rekapitulasi Keuangan dan Operasional
* **Aktor:** Pengelola Kos (Admin)  
* **Tujuan:** Membantu pengelola mengetahui pemasukan, pengeluaran, dan kondisi keuangan kos secara lebih terstruktur.  
* **Alur Interaksi:**
  1. Admin membuka menu laporan keuangan.
  2. Admin mencatat biaya operasional kos.
  3. Sistem mengambil data pembayaran yang sudah diverifikasi.
  4. Sistem menghitung total pemasukan dan pengeluaran.
  5. Sistem menghasilkan laporan keuangan.
* **Output / Hasil Akhir:** Laporan keuangan dan operasional dapat ditampilkan atau diunduh oleh admin.

---

### Diagram Use Case

Di bawah ini adalah representasi visual dari hubungan interaksi antar aktor terhadap fungsi-fungsi di dalam Sistem Informasi Manajemen Kos:

<img width="772" height="628" alt="Screenshot 2026-06-24 233816" src="https://github.com/user-attachments/assets/51ec9166-cb00-43d4-b024-a163c4089f0c" />


---

### Diagram Class

<img width="1050" height="1306" alt="Diagram Class SI Manajemen Kost (APBO) drawio" src="https://github.com/user-attachments/assets/7606b8c6-b6f2-46c4-b13e-8f123fe359aa" />


---


## Penjelasan Diagram Class

Diagram Class pada Sistem Informasi Manajemen Kos Berbasis Web digunakan untuk menggambarkan struktur data statis, spesifikasi kelas, atribut, fungsi (method), serta hubungan (relationship) antar objek secara terintegrasi. 

Sesuai dengan prinsip enkapsulasi pada Pemrograman Berorientasi Objek (OOP), seluruh atribut diatur sebagai Private untuk mengamankan data internal dari akses langsung luar kelas, sedangkan method/fungsi diatur sebagai Public agar dapat dieksekusi oleh sistem atau antarmuka pengguna (UI).

---

## 1. Class Admin
Class Admin merepresentasikan pengelola kos yang memegang hak akses penuh terhadap sistem untuk mengontrol seluruh aktivitas operasional dan administrasi.

### Atribut (Private)
* idAdmin : int — Identitas unik sistem untuk admin
* nama : string — Nama lengkap pengelola kos
* username : string — Kredensial unik untuk hak akses masuk admin
* password : string — Kata sandi akun admin (terenkripsi)
* noHp : string — Nomor telepon pengelola yang aktif

### Method (Public)
* login() — Memvalidasi kredensial masuk admin ke sistem
* kelolaKamar() — Melakukan operasi CRUD (Create, Read, Update, Delete) pada data kamar
* kelolaPenghuni() — Mengelola data registrasi, profil, dan status tinggal penghuni
* verifikasiBayar() — Memeriksa dan menyetujui validitas bukti pembayaran sewa
* lihatLaporan() — Mengakses visualisasi dashboard dan rekapitulasi keuangan kos
* tanganiKeluhan() — Mengalokasikan atau memperbarui status penanganan laporan kerusakan
* kirimNotifikasi() — Memicu pengiriman pengumuman atau pengingat tagihan ke penghuni

---

## 2. Class Penghuni
Class Penghuni merepresentasikan penyewa kamar kos yang menggunakan sistem secara mandiri untuk mengakses layanan sewa, transaksi, dan pengaduan.

### Atribut (Private)
* idPenghuni : int — Identitas unik sistem untuk penghuni
* nama : string — Nama lengkap penghuni sesuai kartu identitas
* alamat : string — Alamat asal penghuni sesuai KTP
* noHp : string — Nomor telepon seluler penghuni yang dapat dihubungi
* noKTP : string — Nomor Induk Kependudukan (NIK) resmi penyewa
* kontakDarurat : string — Nomor telepon kerabat dekat jika terjadi situasi darurat
* tglMasuk : date — Tanggal resmi dimulainya kontrak sewa kamar
* tglKeluar : date — Tanggal berakhirnya kontrak sewa atau rencana check-out
* username : string — Kredensial unik akun penghuni
* password : string — Kata sandi keamanan akun penghuni

### Method (Public)
* login() — Memproses autentikasi masuk penghuni ke platform
* uploadPembayaran() — Mengirim dan menyimpan berkas digital bukti transfer bank
* kirimKeluhan() — Membuat formulir pengaduan terkait kerusakan fasilitas kos
* lihatTagihan() — Menampilkan rincian nominal tagihan aktif bulan berjalan
* lihatRiwayat() — Mengakses daftar transaksi pembayaran yang pernah dilakukan sebelumnya


---

## 3. Class Kamar
Class Kamar merepresentasikan data fisik entitas unit kamar kos yang disewakan.

### Atribut (Private)
* idKamar : int — Identitas unik untuk tiap unit kamar
* nomorKamar : string — Kode unik atau nomor penanda kamar (misal: A01, B05)
* tipeKamar : string — Kategori kelas kamar (misal: Deluxe, Standard, VIP)
* harga : double — Nominal tarif biaya sewa per bulan
* status : string — Indikator ketersediaan kamar (misal: Kosong, Dihuni, Pemeliharaan)
* fasilitas : string — Daftar inventaris bawaan di dalam kamar

### Method (Public)
* ubahStatus() — Memperbarui indikator ketersediaan unit kamar secara otomatis/manual
* tampilInfo() — Menyajikan rincian spesifikasi lengkap kamar kepada pengguna

---

## 4. Class Keluhan
Class Keluhan digunakan untuk mencatat, menampung, dan melacak status penyelesaian masalah sarana kos yang dikeluhkan pengguna.

### Atribut (Private)
* idKeluhan : int — Nomor tiket unik pengaduan keluhan
* kategori : string — Jenis area keluhan (misal: Air, Fasilitas Kamar, Fasilitas Umum)
* deskripsi : string — Penjelasan kronologi atau detail kerusakan sarana
* foto : string — Jalur penyimpanan (path/URL) file foto bukti kerusakan
* status : string — Status progres pelaporan (misal: Antrean, Diproses, Selesai)
* tanggalKeluhan : date — Waktu (stempel tanggal) pengaduan dikirim pertama kali

### Method (Public)
* buatKeluhan() — Menyimpan data laporan pengaduan baru dari penghuni ke database
* updateStatus() — Memperbarui alur penanganan keluhan oleh pihak pengelola
* tutupKeluhan() — Mengunci status tiket aduan menjadi selesai jika perbaikan rampung

---

## 5. Class Notifikasi
Class Notifikasi berfungsi sebagai mesin pengelola pesan atau pengingat berkala yang dihasilkan oleh sistem.

### Atribut (Private)
* idNotifikasi : int — Identitas unik rekaman notifikasi
* pesan : string — Teks isi pesan/informasi penting yang dikirimkan
* tanggalKirim : datetime — Log waktu pengiriman pesan
* jenis : string — Kategori pesan (misal: Peringatan Tagihan, Pengumuman Bersama)

### Method (Public)
* kirimNotif() — Menyebarkan atau menampilkan pesan notifikasi ke akun tujuan

---

## 6. Class Tagihan
Class Tagihan menyimpan akumulasi nilai finansial berkala yang wajib dilunasi oleh penghuni sesuai siklus sewa.

### Atribut (Private)
* idTagihan : int — Nomor invoice unik lembar tagihan
* bulan : string — Periode siklus tagihan bulanan (misal: Oktober 2026)
* totalTagihan : double — Jumlah nominal uang yang harus dibayarkan
* jatuhTempo : date — Batas waktu akhir pembayaran sebelum dikenai sanksi/teguran
* status : string — Kondisi tagihan saat ini (misal: Belum Dibayar, Lunas)

### Method (Public)
* generateTagihan() — Menghasilkan lembar tagihan otomatis berdasarkan waktu jatuh tempo sewa
* ubahStatus() — Mengubah parameter tagihan menjadi lunas pasca verifikasi admin

---

## 7. Class Pembayaran
Class Pembayaran mencatat seluruh riwayat pembuktian transaksi finansial yang diajukan penghuni sebagai pelunasan tagihan.

### Atribut (Private)
* idPembayaran : int — Identitas unik untuk tiap transaksi masuk
* tanggalBayar : date — Log tanggal penghuni mengirimkan pembayaran
* jumlah : double — Nominal uang tunai/transfer yang didepositkan
* buktiTransfer : string — Jalur berkas gambar/dokumen bukti transfer bank
* statusPembayaran : string — Status validasi transaksi (misal: Menunggu Verifikasi, Disetujui, Ditolak)

### Method (Public)
* uploadBukti() — Mengunggah file tanda transfer dari sisi user
* verifikasi() — Mengubah status peninjauan keabsahan dana oleh admin
* cetakKuitansi() — Menghasilkan dokumen kuitansi digital resmi berformat cetak

---

## 8. Class BiayaOperasional
Class BiayaOperasional berfungsi mencatat arus kas keluar (cash outflow) di luar pengeluaran pribadi penyewa untuk kebutuhan operasional rumah kos.

### Atribut (Private)
* idBiaya : int — Identitas unik pos pengeluaran operasional
* namaBiaya : string — Nama deskripsi alokasi biaya (misal: Tagihan Listrik Induk, Gaji Teknisi)
* tanggal : date — Tanggal terjadinya pengeluaran kas
* jumlah : double — Nominal uang kas kos yang dikeluarkan

### Method (Public)
* tambahBiaya() — Menambahkan pencatatan pos biaya pengeluaran operasional baru

---

## 9. Class LaporanKeuangan
Class LaporanKeuangan berfungsi merekapitulasi seluruh kalkulasi neraca laba-rugi bisnis kos pada jangka waktu berkala.

### Atribut (Private)
* idLaporan : int — Identitas unik berkas laporan keuangan
* periode : string — Rentang jangka laporan (misal: Triwulan I - 2026)
* totalPemasukan : double — Akumulasi dana transaksi pembayaran sewa yang sah/lunas
* totalPengeluaran : double — Akumulasi pengeluaran dari seluruh Biaya Operasional
* labaBersih : double — Hasil perhitungan laba bersih (Total Pemasukan - Total Pengeluaran)

### Method (Public)
* generateLaporan() — Memproses kalkulasi otomatis pemasukan dan pengeluaran berkala
* exportPDF() — Mengompilasi dan mengunduh berkas laporan keuangan ke format cetak PDF

---

## Penjelasan Relasi Antar Class

### 1. Relasi Admin dengan Penghuni
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Penghuni dalam proses pengelolaan data penghuni, seperti menambah, mengubah, dan menghapus data penghuni. Satu admin dapat mengelola banyak penghuni.

### 2. Relasi Admin dengan Kamar
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Kamar dalam pengelolaan status dan informasi kamar kos. Satu admin dapat mengelola banyak kamar.

### 3. Relasi Admin dengan Keluhan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Keluhan dalam proses penanganan dan tindak lanjut laporan penghuni. Satu admin dapat menangani banyak keluhan.

### 4. Relasi Admin dengan LaporanKeuangan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan LaporanKeuangan dalam proses pembuatan dan monitoring laporan keuangan kos. Satu admin dapat membuat banyak laporan keuangan.

### 5. Relasi Penghuni dengan Kamar
* **Jenis Relasi:** One to One (0..1 ke 1)
* **Penjelasan:** Penghuni memiliki hubungan dengan Kamar karena setiap penghuni menempati satu kamar kos. Relasi 0..1 menunjukkan bahwa penghuni bisa belum memiliki kamar atau hanya menempati satu kamar.

### 6. Relasi Penghuni dengan Pembayaran
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Pembayaran karena penghuni dapat melakukan banyak pembayaran selama masa sewa kos.

### 7. Relasi Penghuni dengan Tagihan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Tagihan karena setiap penghuni memiliki beberapa tagihan pembayaran bulanan.

### 8. Relasi Penghuni dengan Keluhan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Keluhan karena penghuni dapat membuat banyak laporan kerusakan atau pengaduan fasilitas.

### 9. Relasi Notifikasi dengan Penghuni
* **Jenis Relasi:** Many to One (*..1)
* **Penjelasan:** Notifikasi memiliki hubungan dengan Penghuni karena sistem dapat mengirim banyak notifikasi kepada satu penghuni, seperti pengingat pembayaran atau informasi penting.

### 10. Relasi Tagihan dengan Pembayaran
* **Jenis Relasi:** One to One (1 ke 0..1)
* **Penjelasan:** Tagihan memiliki hubungan dengan Pembayaran karena satu tagihan hanya dapat dibayar dengan satu pembayaran atau belum dibayar sama sekali.


### 11. Relasi LaporanKeuangan dengan Pembayaran
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** LaporanKeuangan memiliki hubungan dengan Pembayaran karena satu laporan keuangan mengambil data dari banyak transaksi pembayaran sebagai sumber pemasukan.

### 12. Relasi LaporanKeuangan dengan BiayaOperasional
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** LaporanKeuangan memiliki hubungan dengan BiayaOperasional karena satu laporan keuangan mengambil data dari banyak biaya operasional sebagai sumber pengeluaran.

---

## Kesimpulan

Berdasarkan hasil wawancara dan analisis sistem yang sedang berjalan, dapat disimpulkan bahwa pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai permasalahan signifikan, seperti kesulitan dalam pencatatan dan pencarian data penghuni, ketidakefisienan dalam monitoring pembayaran, serta kurang optimalnya komunikasi antara pengelola dan penghuni. Permasalahan ini diperkuat oleh kondisi nyata di lapangan, seperti penggunaan buku tulis dan WhatsApp sebagai media utama, yang terbukti rentan terhadap kesalahan, kehilangan data, serta informasi yang terlewat.

Oleh karena itu, pengembangan sistem informasi manajemen kos berbasis web menjadi solusi yang relevan dan dibutuhkan, dengan mempertimbangkan dua aktor utama yaitu pengelola sebagai admin dan penghuni sebagai user. Sistem ini tidak hanya berfungsi untuk meningkatkan efisiensi pengelolaan data dan operasional kos, tetapi juga memberikan kemudahan akses, transparansi informasi, serta peningkatan kualitas komunikasi. Dengan adanya fitur seperti pencatatan pembayaran otomatis, notifikasi pengingat, serta manajemen keluhan terintegrasi, sistem diharapkan mampu mengatasi permasalahan yang ada sekaligus meningkatkan kualitas layanan kos secara keseluruhan.


# Sequence Diagram
## 1. Pendaftaran Penghuni & Alokasi Kamar (Onboarding)
### Pencatatan data penghuni baru dan pembaruan status ketersediaan kamar.
Alur Proses:
1. Pengelola memuat daftar kamar dengan status "KOSONG".
2. Pengelola menginput data calon penghuni (biodata, deposit, jatuh tempo).
3. Sistem membuat entri data penghuni baru ke dalam database.
4. Sistem mengubah status kamar terkait menjadi "DIHUNI".
<img width="801" height="420" alt="Diagram-Sequence 1-Pendaftaran Penghuni   Alokasi Kamar (Onboarding) drawio" src="https://github.com/user-attachments/assets/6a663758-a6cc-43bd-98e7-3cf79cca90eb" />

## 2. Pelunasan Tagihan Sewa Bulanan
### Mekanisme pembayaran sewa oleh penghuni dan proses validasi oleh pengelola.
Alur Proses:
1. Penghuni memuat detail tagihan dan mengunggah bukti pembayaran.
2. Sistem mengubah status tagihan menjadi "MENUNGGU VERIFIKASI".
3. Pengelola memverifikasi bukti pembayaran.
4. Blok Alternatif (Validasi): <br> Valid: Status diubah menjadi "LUNAS", sistem menerbitkan kuitansi, dan mengirimkannya ke penghuni. <br> Tidak Valid: Status dikembalikan ke "BELUM DIBAYAR" dan sistem mengirimkan notifikasi penolakan ke penghuni.
<img width="964" height="825" alt="Diagram-Sequence 2-Pelunasan Tagihan Sewa Bulanan drawio" src="https://github.com/user-attachments/assets/c734f87f-4445-4f59-b05b-8ad8dcac7a1f" />

## 3. Tiket Laporan Keluhan (Maintenance)
### Alur pengajuan, penugasan, dan penyelesaian kendala fasilitas kamar.
Alur Proses:
1. Penghuni mengirimkan data keluhan (kategori, deskripsi, foto).
2. Sistem mencatat keluhan dengan status awal "ANTREAN".
3. Pengelola merespons tiket (status berubah menjadi "DIPROSES") dan meneruskan instruksi ke Teknisi.
4. Teknisi mengeksekusi perbaikan fasilitas.
5. Pengelola menutup tiket keluhan (status berubah menjadi "SELESAI") dan sistem menotifikasi penghuni.
<img width="795" height="594" alt="Diagram-Sequence 3-Tiket Laporan Keluhan (Maintenance) drawio" src="https://github.com/user-attachments/assets/6c03bd67-2b7c-40d2-95fe-76fd3cae7a9b" />

## 4. Pengosongan Kamar (Proses Check-out)
### Prosedur administratif penyelesaian masa sewa dan pembebasan kamar.
Alur Proses:
1. Pengelola memuat data penghuni dan memvalidasi kondisi fisik kamar (inspeksi).
2. Blok Opsional: Jika terdapat kerusakan, pengelola menginput nominal pemotongan uang deposit.
3. Pengelola mengeksekusi proses check-out.
4. Sistem mengarsipkan data penghuni dan mengembalikan status kamar menjadi "KOSONG".
<img width="679" height="470" alt="Diagram-Sequence 4-Pengosongan Kamar (Proses Check-out) drawio" src="https://github.com/user-attachments/assets/fc8f8c25-bf1f-4958-b929-286fe77f26f1" />

## 5. Rekapitulasi Keuangan & Operasional
### Modul pencatatan pengeluaran rutin dan agregasi laporan keuangan.
Alur Proses:
1. Pengelola menginput data biaya operasional secara berkala (looping).
2. Pengelola meminta generate laporan keuangan berdasarkan parameter periode waktu.
3. Sistem mengalkulasi total pengeluaran dan total pemasukan untuk menghasilkan nilai laba bersih.
4. Sistem merender data keuangan dalam antarmuka grafik.
5. Blok Opsional: Pengelola memicu fungsi export untuk mengunduh laporan dalam format PDF.
<img width="899" height="791" alt="Diagram-Sequence 5-Rekapitulasi Keuangan   Operasional drawio" src="https://github.com/user-attachments/assets/f28e2fde-0c6e-4372-9522-e9f3db386dbc" />

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
