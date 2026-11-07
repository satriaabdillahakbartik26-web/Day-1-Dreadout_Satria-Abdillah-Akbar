# Day 1 Workshop: Building with AI, Managing Change with GitHub

**Nama Lengkap:** Satria Abdillah Akbar

**Kelompok:** Dreadout

**Tanggal Kegiatan:** Sabtu, 7 November 2026

---

## 📌 Deskripsi Repository
Repository ini dibuat sebagai tempat penyimpanan, pengelolaan, dan dokumentasi resmi seluruh materi, catatan pembelajaran, serta tugas harian dari kegiatan workshop Day 1.

---

## 🎯 Tujuan Repository
* Sebagai media penyimpanan (*storage*) dan publikasi dokumentasi proyek workshop secara daring melalui GitHub.
  
* Melatih pengelolaan dan penerapan kontrol versi (*version control*) proyek menggunakan alur kerja Git & GitHub.
  
* Mendokumentasikan materi *Prompt Engineering* dan integrasi alur kerja pengembangan aplikasi berbasis AI secara terstruktur.

---

## 📝 Dokumentasi Kegiatan Workshop Day 1

### 1. Rangkuman Materi Workshop
Materi workshop Day 1 mengusung tema **"Building with AI, Managing Change with GitHub"** yang disampaikan oleh Nugi Farhan (Senior Product Designer). Pembahasan terbagi menjadi beberapa topik utama:

#### A. Prompt Engineering
* **Definisi**: Cara merancang instruksi atau masukan agar model AI memberikan jawaban yang tepat, relevan, akurat, dan layak digunakan.
* **Struktur Prompt yang Baik**:
  1. **Role**: Menentukan peran yang harus dijalankan oleh AI.
  2. **Task**: Menjelaskan tugas utama atau tujuan yang ingin dicapai.
  3. **Context**: Memberikan latar belakang, konteks, batasan, dan instruksi rinci.
  4. **Format**: Menentukan bentuk luaran atau *output* hasil respon.
* **Manfaat Prompt Engineering**: Meningkatkan performa model AI, mengurangi bias dan respon yang tidak layak, meningkatkan kontrol dan *predictability*, serta memberikan pengalaman penggunaan yang lebih baik.

#### B. Git & GitHub
* **Git**: Sistem *Version Control System* (VCS) terdistribusi lokal ciptaan Linus Torvalds (2005) yang digunakan untuk melacak dan mengelola setiap perubahan pada file atau kode.
* **GitHub**: Platform berbasis web (*cloud*) yang digunakan untuk menyimpan repository Git secara daring dan mendukung kolaborasi antar pengembang.
* **Alur Kerja Git (Git Workflow)**:
  1. *Working Directory*: Area salinan versi proyek yang sedang dikerjakan secara lokal.
  2. *Staging Area*: Area penampungan sementara (*index*) untuk menandai perubahan yang akan dimasukkan ke commit berikutnya.
  3. *Git Directory / Repository*: Tempat penyimpanan metadata dan *database* seluruh riwayat perubahan proyek.
* **Perintah Dasar Git & GitHub**:
  * `git init`: Menginisialisasi repository lokal baru.
  * `git add .`: Memindahkan seluruh perubahan file ke *staging area*.
  * `git commit -m "pesan"`: Menyimpan riwayat perubahan dari *staging area* ke repository lokal.
  * `git remote add origin <url>`: Menghubungkan repository lokal dengan repository remote di GitHub.
  * `git push origin main`: Mengunggah hasil commit dari branch lokal ke GitHub.
  * `git pull origin main`: Mengambil dan menggabungkan pembaruan dari GitHub ke repository lokal.
* **Pengaturan & Autentikasi**:
  * Pengaturan identitas pengguna (`git config --global user.name` & `user.email`).
  * Integrasi lingkungan pengembangan menggunakan VS Code.
  * Konfigurasi autentikasi aman ke GitHub menggunakan SSH Key (algoritma Ed25519).

#### C. Praktik Pembuatan Proyek (Hands-on)
* Memanfaatkan platform bantu AI (seperti ChatGPT / Claude) menggunakan prompt yang terstruktur untuk menggenerasi kode aplikasi web sederhana *Student Task Planner*.
* Melakukan inisialisasi repository lokal, mengunggah kode awal (*commit & push*), hingga memperbarui repository di GitHub.

---

### 2. Poin-Poin Penting & Pengetahuan Baru
* **Konteks Sangat Menentukan Respon AI**: Pemberian konteks yang detail (*role, task, context, constraints, format*) menghasilkan output kode yang jauh lebih akurat dibanding prompt singkat tanpa latar belakang.
* **Perbedaan Git dan GitHub**: Git bekerja di komputer lokal sebagai pelacak riwayat kode, sedangkan GitHub bekerja di web sebagai media penyimpanan dan kolaborasi tim.
* **Pergerakan File dalam Git**: Memahami perubahan status file dari *Working Directory* $\rightarrow$ *Staging Area* (`git add`) $\rightarrow$ *Repository* (`git commit`).
* **Autentikasi Kriptografi SSH**: Penggunaan kunci Ed25519 untuk mengamankan pertukaran data antara komputer lokal dan akun GitHub tanpa perlu memasukkan kata sandi secara berulang.

---

### 3. Pendapat Pribadi tentang Day 1 Workshop
Kegiatan workshop Day 1 sangat bermanfaat dan memberikan wawasan teknis yang relevan dengan kebutuhan industri saat ini. Materi diajarkan secara sistematis, mulai dari cara berinteraksi dengan AI secara efektif hingga manajemen kode dengan Git & GitHub. Sesi praktik langsung pembuatan aplikasi *Student Task Planner* membuat pemahaman alur kerja dari perancangan hingga publikasi kode di GitHub menjadi jauh lebih jelas dan mudah diterapkan.
