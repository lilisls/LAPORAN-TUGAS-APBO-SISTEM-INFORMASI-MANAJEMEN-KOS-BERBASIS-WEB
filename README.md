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

## Kesimpulan

Berdasarkan hasil wawancara dan analisis sistem yang sedang berjalan, dapat disimpulkan bahwa pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai permasalahan signifikan, seperti kesulitan dalam pencatatan dan pencarian data penghuni, ketidakefisienan dalam monitoring pembayaran, serta kurang optimalnya komunikasi antara pengelola dan penghuni. Permasalahan ini diperkuat oleh kondisi nyata di lapangan, seperti penggunaan buku tulis dan WhatsApp sebagai media utama, yang terbukti rentan terhadap kesalahan, kehilangan data, serta informasi yang terlewat.

Oleh karena itu, pengembangan sistem informasi manajemen kos berbasis web menjadi solusi yang relevan dan dibutuhkan, dengan mempertimbangkan dua aktor utama yaitu pengelola sebagai admin dan penghuni sebagai user. Sistem ini tidak hanya berfungsi untuk meningkatkan efisiensi pengelolaan data dan operasional kos, tetapi juga memberikan kemudahan akses, transparansi informasi, serta peningkatan kualitas komunikasi. Dengan adanya fitur seperti pencatatan pembayaran otomatis, notifikasi pengingat, serta manajemen keluhan terintegrasi, sistem diharapkan mampu mengatasi permasalahan yang ada sekaligus meningkatkan kualitas layanan kos secara keseluruhan.
