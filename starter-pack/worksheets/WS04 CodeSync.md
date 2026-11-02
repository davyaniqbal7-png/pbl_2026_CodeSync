# **WS04: Problem Identification & Scope**

**Mata Kuliah**: Konsep Sistem Informasi (KSI)  
**Kerangka Kerja**: Project-Based Learning (PBL) Level 1  
**Fase Learning Spine**: **Fase 2 — Frame (Problem Discovery & Scope)**  
**Minggu / Alokasi Waktu**: Minggu 2 / 14 Jam Belajar  
**Sub-CPMK / SFIA**: S-01.1 (Introduce - Problem Framing) | SFIA BUSA L1 (_Business Analysis_), IRMG L1  
**Penanggung Jawab Fase**: **Phase Lead 2 (Frame — Mahasiswa B)**  
**Keterkaitan Deliverable**: Sumber Utama Penyusunan **Deliverable D1 (Problem Brief - TPL-01)**

## **1\. Identifikasi Tim & Objek Proyek**

| **Elemen Informasi**          | **Rincian Identitas Kelompok & Mitra**    |
| ----------------------------- | ----------------------------------------- |
| **Nama Kelompok / Kelas**     | CodeSync / B                              |
| **Phase Lead 2 (Frame - M2)** | Melicha Thasqee Nasya Afizha - 2600016069 |
| **Nama UMKM Mitra Lapangan**  | Brilian Laundry                           |
| **Pemilik / Kontak Mitra**    | Erna                                      |

## **2\. Matriks Problem Framing & Analisis Akar Masalah (Root Cause Analysis)**

Gunakan temuan kuantitatif dari WS03 untuk memisahkan antara **Gejala Permukaan (_Symptoms_)** dan **Akar Masalah Utama (_Root Cause_)** operasional bisnis mitra:

| **No** | **Kategori Observasi**      | **Gejala Permukaan (_Symptoms_)**                     | **Akar Masalah Operasional (_Root Cause_)**                                           | **Bukti Kuantitatif (_Baseline Data_)**                                         |
| ------ | --------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **1**  | **Proses Transaksi Kasir**  | Antrean mengular panjang saat jam sibuk.              | Pencatatan pesanan dan penghitungan total harga masih manual di buku nota.            | Rata-rata waktu transaksi = **5 menit/orang**.                                  |
| **2**  | **Pengelolaan Stok Barang** | Sering kehabisan stok barang populer secara mendadak. | Pengurangan stok tidak dicatat saat transaksi (_As-Is_), rekap stok hanya bulanan.    | Tidak dicatat/direkap oleh pemilik karena pembelian barang disaat stok menipis. |
| **3**  | **Rekapitulasi Keuangan**   | Pemilik usaha lelah merekap penjualan setiap malam.   | Nota kertas harus dihitung ulang dengan kalkulator dan ditulis ke spreadsheet manual. | Durasi rekap harian = **60–90 menit/malam**.                                    |

## **3\. Perumusan Problem Statement Kontekstual**

Berdasarkan analisis di atas, rumuskan **Problem Statement** utama dalam 1–2 paragraf terstruktur.  
_Petunjuk_: Hindari mendefinisikan masalah sebagai _"Mitra belum memiliki aplikasi Python/komputer"_. Definisikan dari hambatan bisnis nyata mitra!

**Rumusan Problem Statement Kelompok**:  
_"Pencatatan transaksi dan inventaris yang masih dilakukan secara manual menggunakan buku kertas nota di Brilian Laundry (kondisi As-Is) menyebabkan bottleneck operasional berupa waktu transaksi kasir yang lambat (90 detik/pelanggan), keterlambatan pemesanan ulang stok akibat selisih stok 12% per bulan, serta waktu rekapitulasi harian pemilik usaha yang memakan waktu hingga 1,5 jam setiap malam. Kondisi ini menghambat efisiensi operasional dan potensi pertumbuhan omzet mitra."_

## **4\. Menetapkan Batasan Sistem (System Boundary / Scope Alignment)**

Untuk mencegah terjadinya pembengkakan fitur (_Scope Creep_) yang membahayakan penyelesaian proyek dalam 1 semester, tentukan secara tegas apa yang **Masuk Cakupan (_In-Scope_)** dan apa yang **Di Luar Cakupan (_Out-of-Scope_)**:

 ┌───────────────────────────────────────────┐

│ SYSTEM BOUNDARY (BATASAN SISTEM) │

│ │

│ \[ IN-SCOPE: Fitur yang Akan Dibangun \] │

│ 1. Pencatatan transaksi kasir berbasis konsol (CLI). │

│ 2. Pengurangan stok otomatis setiap transaksi berhasil. │

│ 3. Pencetakan ringkasan rekapitulasi harian untuk pemilik. │

│ │

│─────────────────────────────────────────── │

│ │

│ \[ OUT-OF-SCOPE: Di Luar Cakupan Proyek \] │

│ 1. Integrasi gateway pembayaran e-wallet / QRIS otomatis. │

│ 2. Fitur penggajian karyawan / manajemen HRD. │

│ 3. Pemesanan stok otomatis ke supplier luar. │ └────────────────────────────────────────────┘

### **Tabel Penegasan Cakupan Proyek (*Scope Alignment Table*)**

| **No** | **Modul / Fitur Sistem**            | **Status Cakupan (_In-Scope / Out-of-Scope_)** | **Alasan Pertimbangan Kelayakan (O'Brien)**                                    |
| ------ | ----------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------------ |
| **1**  | Input Transaksi & Kalkulasi Total   | **IN-SCOPE**                                   | Kelayakan Operasional: Sangat dibutuhkan kasir untuk mempercepat transaksi.    |
| **2**  | Update Stok Otomatis                | **IN-SCOPE**                                   | Kelayakan Teknis: Dapat diimplementasikan dengan logika struktur data Python.  |
| **3**  | Laporan Rekap Harian (Laba/Rugi)    | **IN-SCOPE**                                   | Kelayakan Ekonomi: Memberikan nilai _Value of Information_ bagi pemilik usaha. |
| **4**  | Pembayaran Online / Payment Gateway | **OUT-OF-SCOPE**                               | Keterbatasan waktu 1 semester & kompleksitas API luar di PBL Level 1.          |
| **5**  | Multi-Branch / Banyak Cabang        | **OUT-OF-SCOPE**                               | Mitra saat ini hanya memiliki 1 lokasi usaha operasional.                      |

## **5\. Target Metrik Keberhasilan Solusi (To-Be Targets)**

Tentukan target kuantitatif perbaikan yang ingin dicapai melalui solusi sistem informasi To-Be:

| **Indikator Kinerja**               | **Kondisi As-Is (Baseline)** | **Target To-Be (Expected)** | **Estimasi Persentase Peningkatan**      |
| ----------------------------------- | ---------------------------- | --------------------------- | ---------------------------------------- |
| **Waktu Pelayanan Transaksi Kasir** | 5 menit / pelanggan          | **< 2 menit / pelanggan**   | Peningkatan efisiensi **80%**            |
| **Durasi Rekapitulasi Harian**      | 60–90 menit / malam          | **< 30 menit / malam**      | Penghematan waktu **66,67%**             |
| **Akurasi Pencatatan Stok**         | 10%                          | **Akurasi > 98%**           | Penurunan tingkat kesalahan selisih stok |

## **6\. Refleksi & Lembar Pengesahan Phase Lead**

### **A. Pertanyaan Refleksi Tim**

1. _Bagaimana tim memastikan bahwa batasan proyek yang ditetapkan realistis untuk diselesaikan dalam 16 minggu?_
   - **Jawab**: yaitu dengan menetapkan ruang lingkup secara spesifik, menggunakan metode pengerjaan bertahap, menyusun linimasa dan pembagian tugas yang terukur, serta menyiapkan alokasi waktu cadangan untuk mengantisipasi potensi risiko.
2. _Apakah pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok?_
   - **Jawab**: Ya, pemilik usaha mitra telah menyetujui batasan sistem yang diusulkan oleh kelompok

### **B. Tanda Tangan Pengesahan Phase Lead 2**

Disusun oleh Phase Lead 2 (Frame): \[ Melicha Thasqee Nasya Afizha - 2600016069 \]

```
Tanggal Penyusunan: [ 22/10/2026 ]
Tanda Tangan Phase Lead 2: ![](data:image/png;base64,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)
Diverifikasi oleh Dosen Pengampu / Coach:
Tanggal: [ Tanggal ] | Status Checkpoint: [ APPROVED / REVISION NEEDED ]
```

Catatan Dosen: \_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\__