# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 3\)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate \- Problem Framing) & S-03.1 (Intermediate \- Pemetaan SI)** \| **SFIA BUSA L1, REQM L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design \- TPL-02)**

---

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

* **Nama Kelompok**: CodeSync  
* **Objek UMKM Mitra**: Brilian Laundry  
* **Phase Lead 3 (Define)**: Davyan Muhamad Iqbal \- 2649016074  
* **Anggota Tim**:  
  1\. Eka Laili Rizki Yani  
  2\. Melicha Thasqee Nasya Afizha  
  3\. Muhammad Zahwan Abdillah

---

### **2\. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap *Systems Analysis*, fokus utama tim adalah menentukan **APA (*What*)** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (*How*)** sistem dibangun secara teknis (Marakas & O'Brien, 2013).

* **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:  
  \$\$\\text{"Sebagai \[Peran Pengguna\], Saya ingin \[Kemampuan/Fitur\], Sehingga \[Manfaat Bisnis Nyata\]"}\$\$  
* **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

---

### **3\. Workspace A: Formulasi User Story Fungsional**

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Pencatatan)**

* **Sebagai (*As a*)**: Kasir laundry.  
    
* **Saya ingin (*I want to*)**: *Pencatatan nota penjualan dilakukan secara cepat.*

* **Sehingga (*So that*)**: *Tidak perlu mencatat nota secara manual (menggunakan kertas dan tulis tangan) dan transaksi dapat langsung tercatat secara otomatis serta menghindari kesalahan/kehilangan data.*


#### **User Story 2 (Proses Laundy)**

* **Sebagai (*As a*)**: *Pemilik laundry*  
    
* **Saya ingin (*I want to*)**: *Tidak ada pakaian pelanggan yang tertukar ataupun hilang.*

* **Sehingga (*So that*)**: *Pelanggan tidak merasa cemas akan tertukar atau hilangnya pakaian dan saya tidak perlu mengganti rugi.*

#### **User Story 3 (Fitur Pelaporan Keuangan)**

* **Sebagai (*As a*)**: *Pemilik laundry*  
    
* **Saya ingin (*I want to*)**: *Melakukan pengecekan laporan keuangan secara cepat dan lebih teliti.*

* **Sehingga (*So that*)**: *Saya tidak perlu kesusahan mengecek secara manual dan menghindari kesalahan penghitungan.*

---

### **4\. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk **User Story 1** (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)**

* **Diberikan (*Given*)**: *Customer memberi pakaian kepada kasir dan memilih katalog harga, menyebut nama serta nomor telpon.*  
    
* **Ketika (*When*)**: *Kasir memasukkan data customer ke sistem.*

* **Maka (*Then*)**: *Sistem menampilkan dan menyimpan data customer.*

#### **Skenario 1B: Penanganan Kesalahan Data / Eror (Exception Path)**

* **Diberikan (*Given*)**: *Customer datang ke laundry untuk mengambil pakaian dan diminta untuk menyebutkan data berupa nama dan nomor telpon, namun customer salah menyebutkan atau lupa data.*  
    
* **Ketika (*When*)**: *Kasir mencari data di sistem.* 

* **Maka (*Then*)**: *Sistem tidak menampilkan data yang dimaksud karena kesalahan data yang disebutkan dari customer.*

---

### **5\. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

* **Tanggal Validasi**: 21/10/2026  
* **Narahubung Mitra**: Pemilik  
* **Hasil Konfirmasi User Story**:  
  \[ $√$\] Seluruh User Story disetujui mitra  
  \[ $\times$\] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):  
    
  ---

---

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

* **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan skenario *Given-When-Then*? \[ \] Ya  \[ $√$ \] Tidak  
  *(Jika Ya, wajib melampirkan formulir **TPL-07: AI Usage Disclosure & Verification Note**)*.

**Tanda Tangan Tim & Pengesahan Dosen**:

* **Phase Lead 3**: Davyan Muhamad Iqbal 26/10/2026 : ![][image1]  
* **Dosen Coach**: Imam Azhari, S.Si.,M.Cs. (Tanggal: \_\_\_\_\_\_\_\_\_\_)  \[ \] Approved

[image1]: <data:image/png;base64,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>