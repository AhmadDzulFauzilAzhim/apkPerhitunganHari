# Aplikasi Perhitungan Hari

Aplikasi **apkPerhitunganHari** adalah program berbasis GUI (Graphical User Interface) yang dibuat dengan Java dan Swing untuk menghitung jumlah hari dalam suatu bulan, memeriksa apakah suatu tahun merupakan tahun kabisat, dan menghitung selisih hari antara dua tanggal yang dipilih.

## Fitur Utama
1. **Menghitung jumlah hari dalam bulan tertentu**  
   - Memilih bulan melalui dropdown (JComboBox).  
   - Memasukkan tahun melalui input spinner (JSpinner).
   
2. **Menentukan apakah tahun adalah tahun kabisat.**

3. **Menampilkan informasi tambahan:**
   - Hari pertama bulan.
   - Hari terakhir bulan.

4. **Menghitung selisih hari antara dua tanggal yang dipilih menggunakan kalender interaktif.**

5. **Fitur reset/hapus untuk mengatur ulang input dan hasil.**

## Prasyarat
- Java Development Kit (JDK) versi 8 atau lebih baru.
- Library eksternal:
  - **JCalendar** (com.toedter.calendar): Komponen kalender untuk Swing.

## Panduan Penggunaan
1. **Hitung jumlah hari dalam bulan tertentu:**
   - Pilih bulan dari dropdown **Pilih Bulan**.
   - Masukkan tahun pada input spinner **Masukkan Tahun**.
   - Klik tombol **Hitung Hari**.
   - Hasil akan menampilkan jumlah hari, apakah tahun kabisat, serta hari pertama dan terakhir bulan.

2. **Hitung selisih hari antara dua tanggal:**
   - Pilih tanggal awal pada kalender pertama.
   - Pilih tanggal akhir pada kalender kedua.
   - Klik tombol **Hitung Hari**.
   - Hasil akan menampilkan selisih hari.

3. **Hapus semua input dan hasil:**
   - Klik tombol **Hapus** untuk mengatur ulang aplikasi.

## Struktur Program
- **`initComponents`**: Inisialisasi semua komponen GUI.
- **`jButton1ActionPerformed`**: Logika utama untuk menghitung jumlah hari, mengecek tahun kabisat, dan menghitung selisih hari.
- **`jButton2ActionPerformed`**: Logika untuk mereset aplikasi.
- **`jCalendar1PropertyChange` & `jComboBox1ActionPerformed`**: Sinkronisasi data antara komponen kalender, bulan, dan tahun.
- **Utility Method:**
  - **`getNamaHariIndonesia`**: Mengubah nama hari menjadi format bahasa Indonesia (Senin, Selasa, dll.).

## Catatan
- Input tahun harus terdiri dari **4 digit**.
- Kalender akan secara otomatis menyesuaikan bulan dan tahun ketika pengguna memilih tanggal.

---

## Pembuat Aplikasi
Ahmad Dzul Fauzil Azhim - 2210010389

## Demo


