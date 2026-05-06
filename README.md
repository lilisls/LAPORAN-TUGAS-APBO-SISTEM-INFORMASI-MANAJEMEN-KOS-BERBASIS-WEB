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
### [Peran Pengguna 1, misal: Admin/Pengelola]
### [Peran Pengguna 2, misal: User/Pelanggan]

---

# Studi Literatur
### 1. [Topik Literatur 1]
### 2. [Topik Literatur 2]
### 3. [Topik Literatur 3]

---

# Hasil Wawancara: Topik Proyek

---

# Video Dokumentasi / Link Demo

---

# Latar Belakang

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

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola (Admin)** | Kontrol penuh atas properti, data penyewa, dan arus kas keuangan. | • Mengelola ketersediaan unit kamar.<br>• Memproses masuk/keluarnya penghuni.<br>• Memvalidasi bukti bayar & mencatat operasional.<br>• Mengirim notifikasi tunggakan (Broadcast). |
| **Penghuni Kost** | Akses personal ke layanan informasi kamar masing-masing. | • Memantau rincian tagihan bulanan.<br>• Mengunggah resi/bukti pembayaran.<br>• Membuat tiket pengaduan/keluhan fasilitas. |

### Detail Use Case

#### 1. Pendaftaran Penghuni & Alokasi Kamar (Onboarding)
**Aktor**: Pengelola (Admin)  
**Tujuan**: Memasukkan data penyewa baru ke dalam database dan menetapkan unit kamar yang akan ditempati.  
**Alur Interaksi**:
1. Pengelola membuka menu *Manajemen Kamar* dan memfilter unit yang berstatus `[KOSONG]`.
2. Pengelola menginput kelengkapan data diri penyewa (KTP, Kontak darurat).
3. Pengelola menentukan durasi sewa, uang jaminan (deposit), dan tanggal jatuh tempo.

**Output / Hasil Akhir**: Unit kamar terkunci dengan status `[DIHUNI]` dan akun portal untuk penyewa otomatis aktif.

#### 2. Pelunasan Tagihan Sewa Bulanan
**Aktor**: Penghuni & Pengelola  
**Syarat Awal**: Sistem telah menerbitkan *invoice* tagihan berstatus `[BELUM DIBAYAR]`.  
**Alur Interaksi**:
1. Penghuni masuk ke portal, melihat nominal tagihan, lalu melakukan transfer dana.
2. Penghuni melampirkan foto resi transfer ke dalam sistem.
3. Status tagihan otomatis berubah menjadi `[MENUNGGU VERIFIKASI]`.
4. Pengelola menerima peringatan sistem, mengecek mutasi rekening, dan menekan tombol *Verifikasi Lunas*.

**Output / Hasil Akhir**: Sistem menerbitkan kuitansi digital dan riwayat pembayaran penghuni tercatat sukses.

#### 3. Tiket Laporan Keluhan (Maintenance)
**Aktor**: Penghuni & Pengelola  
**Tujuan**: Memfasilitasi pelaporan fasilitas yang rusak (misal: AC bocor, kran mati) agar tidak terlewat oleh pengelola.  
**Alur Interaksi**:
1. Penghuni membuat tiket aduan baru dengan memilih kategori dan melampirkan foto kerusakan.
2. Tiket masuk ke *dashboard* pengelola dengan status `[ANTREAN]`.
3. Pengelola mengalokasikan teknisi/tukang dan mengubah status menjadi `[DIPROSES]`.
4. Setelah masalah teratasi, pengelola menutup tiket aduan tersebut.

**Output / Hasil Akhir**: Status tiket menjadi `[SELESAI]` dan penghuni bisa melihat pembaruannya di portal mereka.

#### 4. Pengosongan Kamar (Proses Check-out)
**Aktor**: Pengelola (Admin)  
**Tujuan**: Menyelesaikan masa sewa penghuni, menangani deposit, dan menyiapkan kamar untuk penyewa berikutnya.  
**Alur Interaksi**:
1. Penghuni mengonfirmasi masa akhir sewa kepada pengelola.
2. Pengelola melakukan inspeksi final kamar. Jika ada kerusakan berat, pengelola mencatat potongan dari uang deposit.
3. Pengelola menekan eksekusi *Check-out* pada profil penghuni.

**Output / Hasil Akhir**: Data penghuni diarsipkan ke daftar *Alumni*, dan status kamar dikembalikan menjadi `[KOSONG]`.

#### 5. Rekapitulasi Keuangan & Operasional
**Aktor**: Pengelola (Admin)  
**Tujuan**: Menghitung laba/rugi bulanan dari bisnis kost.  
**Alur Interaksi**:
1. Pengelola mencatat semua biaya operasional bulanan (Token listrik induk, iuran sampah, biaya perbaikan).
2. Sistem mengakumulasikan total pengeluaran tersebut.
3. Sistem membandingkannya dengan total pemasukan dari sewa kamar bulan itu.

**Output / Hasil Akhir**: Terbentuk grafik atau laporan bersih laba/rugi yang bisa diunduh oleh pengelola.

### Diagram Use Case

<img width="631" height="620" alt="Screenshot 2026-04-29 195457" src="https://github.com/user-attachments/assets/b181a0a0-3c3c-4e8a-88a6-2306ad5d2035" />

---

# Kesimpulan
