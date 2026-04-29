# LAPORAN-TUGAS-APBO-SISTEM-INFORMASI-MANAJEMEN-KOS

## 👥 Anggota Kelompok 3

| Nama | NPM |
| :--- | :--- |
| Alamanda | 4522210078 |
| Lilis | 4524210051 |
| Ketut Sumantre | 4524210048 |
| Bunga Putri Nuriman | 4524210021 |
| Kornelius Timothy Setiawan | 4524210050 |

---

# 🎯 Sasaran Pengguna
Sasaran Pengguna dari Sistem Informasi Manajemen Kos Berbasis Web ini terdiri dari dua kelompok utama: Pemilik atau Pengelola Kos sebagai Admin dan Penghuni Kos sebagai User. Sistem ini dirancang untuk memenuhi kebutuhan masing-masing pengguna agar pengelolaan kos lebih efisien dan komunikasi antar pemilik dan prnghuni berjalan lancar. Berikut adalah penjelasan singkat mengenai kedua kelompok pengguna tersebut:

### 👨‍💼 Pengelola Kos (Admin)
Pengelola kos adalah pihak yang bertanggung jawab atas sistem dan operasional kos. Pengelola juga memiliki pekerjaan utama sehingga dibutuhkan sistem yang lebih efisien.  
Sebagai pengelola, mereka membutuhkan informasi terpusat mengenai pembayaran, data penghuni, dan status kamar agar bisa memantau kos secara efektif tanpa harus mengganggu pekerjaan utama.

### 🧑‍💻 Penghuni Kos (User)
Penghuni kos adalah mahasiswa atau pekerja yang menempati kamar kos. Mereka sudah terbiasa menggunakan smartphone dan membutuhkan kemudahan dalam melakukan pembayaran, mengirim keluhan, dan menerima pengumuman atau notifikasi penting.  
Sistem yang mudah diakses dan transparan akan membantu mereka menjaga kewajiban pembayaran dan komunikasi dengan pemilik kos.

---

# 📑 Studi Literatur
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

# 💬 Hasil Wawancara: Sistem Informasi Manajemen Kos

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

# 📖 Latar Belakang

Pengelolaan rumah kos saat ini masih dilakukan secara manual, terutama dalam pencatatan data penyewa, ketersediaan kamar, serta pembayaran sewa. Cara ini berpotensi menimbulkan berbagai permasalahan seperti kesalahan pencatatan, keterlambatan informasi, hingga kesulitan dalam memantau status kamar secara akurat. Di sisi lain, tingginya mobilitas mahasiswa sebagia penyewa kos menuntut adanya akses informasi yang cepat dan praktis terkait ketersediaan kamar, harga, serta fasilitas yang ditawarkan

Untuk mengatasi permasalahan tersebut, diperlukan sebuah sistem informasi manajemen kos berbasis web yang mampu mengintegrasikan proses pengelolaan data sekaligus memberikan kemudahan akses bagi penyewa sebagai pengguna utama. Sistem ini diharapkan dapat membantu pengelola dalam melakukan pencatatan secara lebih terstruktur dan efisien, serta memungkinkan penyewa memperoleh informasi kos secara real-time tanpa harus datang langsung ke lokasi. Dengan demikian, sistem ini tidak hanya meningkatkan efisiensi pengelolaan, tetapi juga memberikan nilai tambah dalam pelayanan kepada penyewa di lingkungan sekitar kampus.

---

#  📋 Bagian 1: Analisis Aktor

 1. 👨‍💼 Pengelola Kos (Admin)
 
 Aktor utama yang memiliki kontrol penuh terhadap sistem dan operasional kos.

 Tugas & Tanggung Jawab: 
- Mengelola data penghuni (input, update, dan pencarian data)
- Mengelola data kamar (status kosong/terisi)
- Mencatat dan memverifikasi pembayaran kos
- Melihat rekapitulasi keuangan melalui dashboard
- Menanggapi dan mengelola keluhan dari penghuni
- Mengirim atau memantau notifikasi/pengingat pembayaran

2. 🧑‍💻 Penghuni Kos (User)

Aktor yang menggunakan layanan kos dan berinteraksi langsung dengan sistem.

Tugas & Tanggung Jawab:
- Melakukan pembayaran kos (transfer/cash)
- Mengunggah bukti pembayaran
- Melihat status pembayaran (lunas/belum)
- Mengirim keluhan terkait fasilitas kos
- Menerima notifikasi (pengingat pembayaran & informasi penting)

3. 📱 Sistem (Automated System)
Aktor non-manusia yang membantu otomatisasi proses dalam sistem.
 
Tugas & Tanggung Jawab:
- Mengirim notifikasi otomatis (misalnya pengingat pembayaran)
- Menyimpan dan mengelola database penghuni & pembayaran
- Menampilkan dashboard rekap data secara real-time
- Mencatat histori pembayaran dan keluhan
- Membantu memfilter data (siapa yang belum bayar, dll)
---

## ⚖️ Bagian 2: Analisis Perbandingan Sistem

Klik tiap bagian untuk melihat perbandingan sistem lama (manual) dan sistem baru (digital):

<details>
<summary><b>1.  Manajemen Data Penghuni</b></summary>
<br>

* **❌ Sistem Manual:**
    * Data disimpan dalam bentuk fisik (fotokopi KTP & KK)
    * Sulit mencari data karena tercampur dalam satu map
    * Risiko kehilangan data cukup tinggi
* **✅ Sistem Digital:**
    * Data penghuni tersimpan dalam database terpusat
    * Pencarian data cepat dan terstruktur
    * Data lebih aman dan tidak mudah hilang
</details>

<details>
<summary><b>2.  Pencatatan & Monitoring Pembayaran</b></summary>
<br>

* **❌ Sistem Manual:**
    * Pembayaran dicatat di buku tulis
    * Bukti pembayaran hanya berupa screenshot WhatsApp
    * Harus cek satu per satu untuk tahu siapa yang belum bayar
    * Rentan kesalahan pencatatan
* **✅ Sistem Digital:**
    * Pembayaran tercatat otomatis dalam sistem
    * Penghuni upload bukti langsung ke sistem
    * Status pembayaran bisa dilihat secara real-time
    * Tersedia rekap otomatis di dashboard
</details>

<details>
<summary><b>3.  Pengingat Pembayaran</b></summary>
<br>

* **❌ Sistem Manual:**
    * Pengelola harus mengingat dan menagih satu per satu
    * Sering merasa sungkan saat menagih
    * Banyak penghuni telat bayar karena lupa
* **✅ Sistem Digital:**
    * Sistem mengirim notifikasi otomatis (misal via WhatsApp)
    * Pengingat dikirim sebelum jatuh tempo
    * Mengurangi keterlambatan pembayaran
</details>

<details>
<summary><b>4.  Penanganan Keluhan</b></summary>
<br>

* **❌ Sistem Manual:**
    * Keluhan disampaikan via chat atau langsung
    * Tidak terdokumentasi dengan baik
    * Banyak keluhan terlewat atau terlupakan
* **✅ Sistem Digital:**
    * Keluhan dicatat dalam sistem
    * Ada riwayat dan tracking status keluhan
    * Pengelola lebih mudah memantau dan menindaklanjuti
</details>

<details>
<summary><b>5.  Penyampaian Informasi</b></summary>
<br>

* **❌ Sistem Manual:**
    * Menggunakan grup WhatsApp
    * Informasi sering tertumpuk dan terlewat
    * Tidak semua penghuni membaca info
* **✅ Sistem Digital:**
    * Notifikasi langsung ke masing-masing pengguna
    * Informasi lebih terstruktur dan tidak mudah hilang
    * Bisa diakses kembali kapan saja di sistem
</details>
---

## 📌 3. Skenario Sistem (Use Case)

### 👥 Pemetaan Aktor & Hak Akses

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola (Admin)** | Kontrol penuh atas properti, data penyewa, dan arus kas keuangan. | • Mengelola ketersediaan unit kamar.<br>• Memproses masuk/keluarnya penghuni.<br>• Memvalidasi bukti bayar & mencatat operasional.<br>• Mengirim notifikasi tunggakan (Broadcast). |
| **Penghuni Kost** | Akses personal ke layanan informasi kamar masing-masing. | • Memantau rincian tagihan bulanan.<br>• Mengunggah resi/bukti pembayaran.<br>• Membuat tiket pengaduan/keluhan fasilitas. |

---

### 📋 Rincian Alur Sistem (Proses Inti)

#### 1. Pendaftaran Penghuni & Alokasi Kamar (Onboarding)
**Aktor:** Pengelola (Admin)  
**Tujuan:** Memasukkan data penyewa baru ke dalam database dan menetapkan unit kamar yang akan ditempati.  
**Alur Interaksi:**
1. Pengelola membuka menu *Manajemen Kamar* dan memfilter unit yang berstatus `[KOSONG]`.
2. Pengelola menginput kelengkapan data diri penyewa (KTP, Kontak darurat).
3. Pengelola menentukan durasi sewa, uang jaminan (deposit), dan tanggal jatuh tempo.

**Output / Hasil Akhir:** Unit kamar terkunci dengan status `[DIHUNI]` dan akun portal untuk penyewa otomatis aktif.

#### 2. Pelunasan Tagihan Sewa Bulanan
**Aktor:** Penghuni & Pengelola  
**Syarat Awal:** Sistem telah menerbitkan *invoice* tagihan berstatus `[BELUM DIBAYAR]`.  
**Alur Interaksi:**
1. Penghuni masuk ke portal, melihat nominal tagihan, lalu melakukan transfer dana.
2. Penghuni melampirkan foto resi transfer ke dalam sistem.
3. Status tagihan otomatis berubah menjadi `[MENUNGGU VERIFIKASI]`.
4. Pengelola menerima peringatan sistem, mengecek mutasi rekening, dan menekan tombol *Verifikasi Lunas*.

**Output / Hasil Akhir:** Sistem menerbitkan kuitansi digital dan riwayat pembayaran penghuni tercatat sukses.

#### 3. Tiket Laporan Keluhan (Maintenance)
**Aktor:** Penghuni & Pengelola  
**Tujuan:** Memfasilitasi pelaporan fasilitas yang rusak (misal: AC bocor, kran mati) agar tidak terlewat oleh pengelola.  
**Alur Interaksi:**
1. Penghuni membuat tiket aduan baru dengan memilih kategori dan melampirkan foto kerusakan.
2. Tiket masuk ke *dashboard* pengelola dengan status `[ANTREAN]`.
3. Pengelola mengalokasikan teknisi/tukang dan mengubah status menjadi `[DIPROSES]`.
4. Setelah masalah teratasi, pengelola menutup tiket aduan tersebut.

**Output / Hasil Akhir:** Status tiket menjadi `[SELESAI]` dan penghuni bisa melihat pembaruannya di portal mereka.

#### 4. Pengosongan Kamar (Proses Check-out)
**Aktor:** Pengelola (Admin)  
**Tujuan:** Menyelesaikan masa sewa penghuni, menangani deposit, dan menyiapkan kamar untuk penyewa berikutnya.  
**Alur Interaksi:**
1. Penghuni mengonfirmasi masa akhir sewa kepada pengelola.
2. Pengelola melakukan inspeksi final kamar. Jika ada kerusakan berat, pengelola mencatat potongan dari uang deposit.
3. Pengelola menekan eksekusi *Check-out* pada profil penghuni.

**Output / Hasil Akhir:** Data penghuni diarsipkan ke daftar *Alumni*, dan status kamar dikembalikan menjadi `[KOSONG]`.

#### 5. Rekapitulasi Keuangan & Operasional
**Aktor:** Pengelola (Admin)  
**Tujuan:** Menghitung laba/rugi bulanan dari bisnis kost.  
**Alur Interaksi:**
1. Pengelola mencatat semua biaya operasional bulanan (Token listrik induk, iuran sampah, biaya perbaikan).
2. Sistem mengakumulasikan total pengeluaran tersebut.
3. Sistem membandingkannya dengan total pemasukan dari sewa kamar bulan itu.

**Output / Hasil Akhir:** Terbentuk grafik atau laporan bersih laba/rugi yang bisa diunduh oleh pengelola.

---

### 📊 Diagram Use Case
<img width="631" height="620" alt="Screenshot 2026-04-29 195457" src="https://github.com/user-attachments/assets/82f6fced-9841-46b5-9056-f69fd832a4d4" />

---

# Kesimpulan

Berdasarkan hasil wawancara dan analisis, pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai kendala, seperti kesulitan pencatatan data, monitoring pembayaran yang tidak efisien, serta komunikasi yang kurang optimal antara pengelola dan penghuni. Penggunaan media sederhana seperti buku tulis dan WhatsApp terbukti belum mampu mendukung pengelolaan secara efektif.

Oleh karena itu, sistem informasi manajemen kos berbasis web menjadi solusi yang tepat dengan melibatkan pengelola sebagai admin dan penghuni sebagai user. Sistem ini diharapkan dapat meningkatkan efisiensi pengelolaan, mempermudah akses informasi, serta memperbaiki kualitas layanan dan komunikasi secara lebih terstruktur dan real-time.
