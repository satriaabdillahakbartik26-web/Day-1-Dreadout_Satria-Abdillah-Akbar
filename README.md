# Day 1 Workshop: Building with AI, Managing Change with GitHub[cite: 1, 3]

**Nama Lengkap:** [Nama Lengkap Kamu]  
**Kelompok:** [Nama Kelompok Kamu]  
**Tanggal Kegiatan:** Sabtu, 7 November 2026[cite: 1]  

---

## 📌 Deskripsi Repository
Repository ini dibuat sebagai tempat penyimpanan, pengelolaan, dan dokumentasi resmi seluruh materi, catatan pembelajaran, serta tugas harian dari kegiatan workshop Day 1[cite: 1]. 

---

## 🎯 Tujuan Repository
* Sebagai media penyimpanan (*storage*) dan publikasi dokumentasi proyek workshop secara daring melalui GitHub[cite: 15].
* Melatih pengelolaan dan penerapan kontrol versi (*version control*) proyek menggunakan alur kerja Git & GitHub[cite: 4, 15].
* Mendokumentasikan materi *Prompt Engineering* dan integrasi alur kerja pengembangan aplikasi berbasis AI secara terstruktur[cite: 1, 5, 27].

---

## 📝 Dokumentasi Kegiatan Workshop Day 1

### 1. Rangkuman Materi Workshop
Materi workshop Day 1 mengusung tema **"Building with AI, Managing Change with GitHub"** yang disampaikan oleh Nugi Farhan (Senior Product Designer)[cite: 1, 2, 3]. Pembahasan terbagi menjadi beberapa topik utama:

#### A. Prompt Engineering
* **Definisi**: Cara merancang instruksi atau masukan agar model AI memberikan jawaban yang tepat, relevan, akurat, dan layak digunakan[cite: 5, 6].
* **Struktur Prompt yang Baik**:
  1. **Role**: Menentukan peran yang harus dijalankan oleh AI[cite: 8, 9].
  2. **Task**: Menjelaskan tugas utama atau tujuan yang ingin dicapai[cite: 8, 9].
  3. **Context**: Memberikan latar belakang, konteks, batasan, dan instruksi rinci[cite: 7, 8, 9].
  4. **Format**: Menentukan bentuk luaran atau *output* hasil respon[cite: 8, 9].
* **Manfaat Prompt Engineering**: Meningkatkan performa model AI, mengurangi bias dan respon yang tidak layak, meningkatkan kontrol dan *predictability*, serta memberikan pengalaman penggunaan yang lebih baik[cite: 11].

#### B. Git & GitHub
* **Git**: Sistem *Version Control System* (VCS) terdistribusi lokal ciptaan Linus Torvalds (2005) yang digunakan untuk melacak dan mengelola setiap perubahan pada file atau kode[cite: 13, 15].
* **GitHub**: Platform berbasis web (*cloud*) yang digunakan untuk menyimpan repository Git secara daring dan mendukung kolaborasi antar pengembang[cite: 15].
* **Alur Kerja Git (Git Workflow)**:
  1. *Working Directory*: Area salinan versi proyek yang sedang dikerjakan secara lokal[cite: 14].
  2. *Staging Area*: Area penampungan sementara (*index*) untuk menandai perubahan yang akan dimasukkan ke commit berikutnya[cite: 14].
  3. *Git Directory / Repository*: Tempat penyimpanan metadata dan *database* seluruh riwayat perubahan proyek[cite: 14].
* **Perintah Dasar Git & GitHub**:
  * `git init`: Menginisialisasi repository lokal baru[cite: 16].
  * `git add .`: Memindahkan seluruh perubahan file ke *staging area*[cite: 16, 21].
  * `git commit -m "pesan"`: Menyimpan riwayat perubahan dari *staging area* ke repository lokal[cite: 16].
  * `git remote add origin <url>`: Menghubungkan repository lokal dengan repository remote di GitHub[cite: 17].
  * `git push origin main`: Mengunggah hasil commit dari branch lokal ke GitHub[cite: 17].
  * `git pull origin main`: Mengambil dan menggabungkan pembaruan dari GitHub ke repository lokal[cite: 17].
* **Pengaturan & Autentikasi**:
  * Pengaturan identitas pengguna (`git config --global user.name` & `user.email`)[cite: 18].
  * Integrasi lingkungan pengembangan menggunakan VS Code[cite: 19].
  * Konfigurasi autentikasi aman ke GitHub menggunakan SSH Key (algoritma Ed25519)[cite: 22, 23, 24].

#### C. Praktik Pembuatan Proyek (Hands-on)
* Memanfaatkan platform bantu AI (seperti ChatGPT / Claude) menggunakan prompt yang terstruktur untuk menggenerasi kode aplikasi web sederhana *Student Task Planner*[cite: 26, 27].
* Melakukan inisialisasi repository lokal, mengunggah kode awal (*commit & push*), hingga memperbarui repository di GitHub[cite: 27].

---

### 2. Poin-Poin Penting & Pengetahuan Baru
* **Konteks Sangat Menentukan Respon AI**: Pemberian konteks yang detail (*role, task, context, constraints, format*) menghasilkan output kode yang jauh lebih akurat dibanding prompt singkat tanpa latar belakang[cite: 7, 9].
* **Perbedaan Git dan GitHub**: Git bekerja di komputer lokal sebagai pelacak riwayat kode, sedangkan GitHub bekerja di web sebagai media penyimpanan dan kolaborasi tim[cite: 15].
* **Pergerakan File dalam Git**: Memahami perubahan status file dari *Working Directory* $\rightarrow$ *Staging Area* (`git add`) $\rightarrow$ *Repository* (`git commit`)[cite: 14, 16].
* **Autentikasi Kriptografi SSH**: Penggunaan kunci Ed25519 untuk mengamankan pertukaran data antara komputer lokal dan akun GitHub tanpa perlu memasukkan kata sandi secara berulang[cite: 22, 24].

---

### 3. Pendapat Pribadi tentang Day 1 Workshop
Kegiatan workshop Day 1 sangat bermanfaat dan memberikan wawasan teknis yang relevan dengan kebutuhan industri saat ini. Materi diajarkan secara sistematis, mulai dari cara berinteraksi dengan AI secara efektif hingga manajemen kode dengan Git & GitHub. Sesi praktik langsung pembuatan aplikasi *Student Task Planner* membuat pemahaman alur kerja dari perancangan hingga publikasi kode di GitHub menjadi jauh lebih jelas dan mudah diterapkan[cite: 26, 27].
