# **WORKBOOK: LEMBAR KERJA MAHASISWA WS06**

## **Success Metrics (BPI/DMAIC) & Pemetaan Komponen SI Awal**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 4\)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate \- Problem Framing) & S-03.1 (Intermediate \- Pemetaan SI)** \| **SFIA BUSA L1, METR L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D1 Final (TPL-01) & D2 Draf (TPL-02)**

---

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

* **Nama Kelompok**: CodeSync  
* **Objek UMKM Mitra**: Brilian Laundry  
* **Phase Lead 3 (Define)**: Davyan Muhamad Iqbal \- 2649016074  
* **Anggota Tim**: 1\. Eka Laili Rizki Yani  
  2\. Melicha Thasqee Nasya Afizha  
  3\. Muhammad Zahwan Abdillah

---

### **2\. Landasan Konseptual: Metrik BPI & Pemetaan 5 Pilar SI**

* **Business Process Improvement (BPI)** mengukur keberhasilan perbaikan proses bisnis melalui dua dimensi utama (Rainer et al., 2014):  
  * **Efisiensi (*Efficiency*)**: Mengukur penghematan sumber daya (*doing things well*), seperti efisiensi waktu siklus transaksi atau reduksi biaya operasional.  
  * **Efektivitas (*Effectiveness*)**: Mengukur pencapaian kualitas/tujuan (*doing the right things*), seperti akurasi data stok, penurunan angka selisih kasir, dan kepuasan pelanggan.  
* **Model 5 Pilar SI O'Brien**: Solusi sistem informasi dipetakan ke dalam pilar *People, Hardware, Software, Data,* dan *Network* (Marakas & O'Brien, 2013).

---

### **3\. Workspace A: Matrik Metrik Keberhasilan Bisnis (DMAIC Six Sigma)**

| Dimensi Metrik | Parameter Kinerja | Kondisi Baseline (As-Is) | Target Solusi (To-Be) | Metode Pengukuran |
| :---- | :---- | :---- | :---- | :---- |
| **Efisiensi (Waktu)** | Durasi pelayanan transaksi per pelanggan | 5 menit | \< 3 menit | Stopwatch sampel 10 transaksi |
| **Efisiensi (Waktu)** | Durasi rekapitulasi harian pemilik | 1,5 jam / malam | 30 menit / malam | Wawancara & uji coba langsung |
| **Efektivitas (Akurasi)** | Tingkat selisih pencatatan stok barang | Tidak ada pencatatan | Dicatat perminggu | Stock opname bulanan |
| **Efektivitas (Kualitas)** | Frekuensi kesalahan hitung nota | 3 kali / minggu | 0 kali / minggu | Audit sampel lembar nota |

---

### **4\. Workspace B: Pemetaan Arsitektur 5 Pilar SI Solusi Awal**

┌────────────────────────────────────────────┐  
│                      PETA 5 PILAR SISTEM INFORMASI                      │  
├────────────────────────────────────────────┤  
│ 1\. PEOPLE RESOURCES (Pengguna & Spesialis)                              │  
│    • Pengguna Akhir: Kasir Brilian Laundry yang mengoperasionalkan perangkat│  
│    • Pengelola Data: Pemilik Brilian Laundry │  
├────────────────────────────────────────────┤  
│ 2\. HARDWARE RESOURCES (Perangkat Mesin & Media)                         │  
│    • Perangkat Fisik Input: Smartphone│  
│    • Perangkat Fisik Output: Smartphone│  
├────────────────────────────────────────────┤  
│ 3\. SOFTWARE RESOURCES (Aplikasi & Prosedur Operational)                 │  
│    • Aplikasi Program: Aplikasi POS kasir │  
│    • Prosedur Pengguna: Prosedur standar operasi bagi kasir untuk memasukkan pesanan, menyimpan data pelanggan laundry, dan nominal harga │  
├────────────────────────────────────────────┤  
│ 4\. DATA RESOURCES (Struktur Data & Basis Data)                          │  
│    • Data Transaksi: ID\_Transaksi, Waktu\_Transaksi, Berat\_Pakaian, Katalog\_Harga, Nominal\_Bayar│  
│    • Data Produk/Stok: Sisa\_Stok\_bahan, │  
├────────────────────────────────────────────┤  
│ 5\. NETWORK RESOURCES (Jaringan Communication & Media)                   │  
│    • Konektivitas: Koneksi internet nirkabel (Wi-Fi) Brilianeau Laundry│  
└────────────────────────────────────────────┘

---

### **5\. Workspace C: Lembar Persetujuan Formal Mitra (Sign-Off)**

Dengan ini, pemilik / manajer UMKM mitra menyatakan setuju atas rumusan kebutuhan fungsional, target metrik keberhasilan, dan batas cakupan sistem yang dirancang oleh tim mahasiswa.

* **Nama UMKM Mitra**: Brillian Laundry  
* **Nama Pemilik / Pengelola**: Erna/Pemilik  
* **Tanggal Persetujuan**: 11/11/2026

**Tanda Tangan Persetujuan Mitra**:

---

---

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

* **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan metrik BPI / diagram 5 pilar SI? \[ \] Ya  \[ √ \] Tidak  
  *(Jika Ya, wajib melampirkan formulir **TPL-07: AI Usage Disclosure & Verification Note**)*.

**Tanda Tangan Tim & Pengesahan Dosen**:

* **Phase Lead 3**: Davyan Muhamad Iqbal 11/11/2026 : ![][image1]  
* **Dosen Coach**: Imam Azhari, S.Si.,M.Cs. (Tanggal: \_\_\_\_\_\_\_\_\_\_)  \[ \] Approved

[image1]: <data:image/png;base64,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>