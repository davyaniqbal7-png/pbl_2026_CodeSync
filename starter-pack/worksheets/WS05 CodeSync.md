# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 3)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate - Pemetaan SI)** | **SFIA BUSA L1, REQM L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)**

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

- **Nama Kelompok**: CodeSync
- **Objek UMKM Mitra**: Brilian Laundry
- **Phase Lead 3 (Define)**: Davyan Muhamad Iqbal - 2649016074
- **Anggota Tim**:

1\. Eka Laili Rizki Yani

2\. Melicha Thasqee Nasya Afizha

3\. Muhammad Zahwan Abdillah

### **2\. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap _Systems Analysis_, fokus utama tim adalah menentukan **APA (_What_)** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (_How_)** sistem dibangun secara teknis (Marakas & O'Brien, 2013).

- **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:  
  \$\$\\text{"Sebagai \[Peran Pengguna\], Saya ingin \[Kemampuan/Fitur\], Sehingga \[Manfaat Bisnis Nyata\]"}\$\$
- **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

### **3\. Workspace A: Formulasi User Story Fungsional**

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Pencatatan)**

- **Sebagai (_As a_)**: Kasir laundry.
- **Saya ingin (_I want to_)**: _Pencatatan nota penjualan dilakukan secara cepat._
- **Sehingga (_So that_)**: _Tidak perlu mencatat nota secara manual (menggunakan kertas dan tulis tangan) dan transaksi dapat langsung tercatat secara otomatis serta menghindari kesalahan/kehilangan data._

#### **User Story 2 (Proses Laundy)**

- **Sebagai (_As a_)**: _Pemilik laundry_
- **Saya ingin (_I want to_)**: _Tidak ada pakaian pelanggan yang tertukar ataupun hilang._
- **Sehingga (_So that_)**: _Pelanggan tidak merasa cemas akan tertukar atau hilangnya pakaian dan saya tidak perlu mengganti rugi._

#### **User Story 3 (Fitur Pelaporan Keuangan)**

- **Sebagai (_As a_)**: _Pemilik laundry_
- **Saya ingin (_I want to_)**: _Melakukan pengecekan laporan keuangan secara cepat dan lebih teliti._
- **Sehingga (_So that_)**: _Saya tidak perlu kesusahan mengecek secara manual dan menghindari kesalahan penghitungan._

### **4\. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk **User Story 1** (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)**

- **Diberikan (_Given_)**: _Customer memberi pakaian kepada kasir dan memilih katalog harga, menyebut nama serta nomor telpon._
- **Ketika (_When_)**: _Kasir memasukkan data customer ke sistem._
- **Maka (_Then_)**: _Sistem menampilkan dan menyimpan data customer._

#### **Skenario 1B: Penanganan Kesalahan Data / Eror (Exception Path)**

- **Diberikan (_Given_)**: _Customer datang ke laundry untuk mengambil pakaian dan diminta untuk menyebutkan data berupa nama dan nomor telpon, namun customer salah menyebutkan atau lupa data._
- **Ketika (_When_)**: _Kasir mencari data di sistem._
- **Maka (_Then_)**: _Sistem tidak menampilkan data yang dimaksud karena kesalahan data yang disebutkan dari customer._

### **5\. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

- **Tanggal Validasi**: 21/10/2026
- **Narahubung Mitra**: Pemilik
- **Hasil Konfirmasi User Story**:  
  \[ $\surd$\] Seluruh User Story disetujui mitra  
  \[ $\times$\] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

- **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan skenario _Given-When-Then_? \[ \] Ya \[ $\surd$ \] Tidak  
  _(Jika Ya, wajib melampirkan formulir_ **_TPL-07: AI Usage Disclosure & Verification Note_**_)_.

**Tanda Tangan Tim & Pengesahan Dosen**:

- **Phase Lead 3**: Davyan Muhamad Iqbal (Tanggal: 26/10/2026)
- **Dosen Coach**: \_**\_**\_**\_**\_**\_**\_**\__ (Tanggal: \_**\_**\_**\_) \[ \] Approved