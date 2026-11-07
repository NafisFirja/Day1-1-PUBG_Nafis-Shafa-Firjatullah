# Documentation Day 1: Workshop Project

## Informasi Peserta
- **Nama Lengkap:** Nafis Shafa Firjatullah
- **Program Studi:** D4 Teknik Multimedia dan Jaringan (TMJ)
- **Institusi:** Politeknik Negeri Jakarta (PNJ)

---

## Deskripsi Repository
Repository ini dibuat sebagai tempat penyimpanan, pengelolaan, dan dokumentasi daring resmi selama mengikuti kegiatan **Proyek Workshop (Day 1)**. Repository ini bersifat **Public** agar seluruh proses pembelajaran, penulisan catatan, dan hasil proyek dapat diakses serta ditinjau dengan transparan.

---

## Tujuan Repository
1. Memenuhi tugas individu misi proyek workshop pengelolaan dokumentasi daring berbasis VCS (Version Control System).
2. Mendokumentasikan materi pembelajaran, instruksi prompt, serta konsep Git & GitHub secara terstruktur.
3. Menyimpan riwayat perubahan (*version history*) proyek aplikasi web sederhana secara transparan dan sistematis.
4. Melatih keterampilam pengelolaan proyek software menggunakan GitHub sebagai media publikasi utama.

---

## Dokumentasi Kegiatan Workshop (Day 1)

### 1. Rangkuman Materi Pembelajaran
Dalam sesi Day 1 Workshop yang dibawakan oleh **Nugi Farhan** (Senior Product Designer), materi difokuskan pada dua topik utama: **Building with AI** dan **Managing Change with GitHub**.

#### A. Prompt Engineering & Building with AI
- **Prompt:** Instruksi atau masukan yang diberikan kepada model AI untuk menghasilkan output spesifik.
- **Prinsip Utama:** *Context is key*. Semakin mendalam konteks dan batasan yang diberikan, semakin akurat dan relevan respons yang dihasilkan oleh AI.
- **Struktur Prompt yang Baik:**
  1. **Role:** Menentukan peran/identitas AI (misal: *Web Developer*).
  2. **Task:** Menyebutkan tugas utama yang harus dilakukan.
  3. **Context:** Memberikan gambaran batasan, target pengguna, dan latar belakang proyek.
  4. **Format/Output:** Menentukan bentuk hasil akhir (potongan kode lengkap, penjelasan langkah uji coba, dll).
- **Keuntungan Prompt Engineering:** Meningkatkan kinerja model AI, mengurangi bias/respons ofensif, serta meningkatkan prediktabilitas output.

#### B. Dasar-Dasar Git & Version Control
- **Git:** Sistem Version Control Terdistribusi (DVCS) lokal yang berfungsi mencatat siapa, kapan, dan apa saja perubahan yang terjadi pada file/kode proyek.
- **GitHub:** Platform berbasis web untuk menyimpan repository Git secara online dan memfasilitasi kolaborasi antarpengembang.
- **Tiga Area Utama Git Workflow:**
  1. **Working Directory:** Direktori kerja lokal tempat file dimodifikasi.
  2. **Staging Area (Index):** Area persiapan tempat memilih perubahan file yang akan dimasukkan ke commit berikutnya.
  3. **Git Directory (Repository):** Database Git yang menyimpan seluruh metadata dan commit proyek.

---

### 2. Poin-Poin Penting & Pengetahuan Baru
- **Perbedaan Git & GitHub:** Git adalah *tool* berbasis terminal/lokal untuk pelacakan versi, sedangkan GitHub adalah *hosting service* berbasis web untuk kolaborasi dan *remote backup*.
- **Perintah Dasar Git (Essential Commands):**
  - `git init`: Inisialisasi repository Git baru di folder lokal.
  - `git add .` / `git add -A`: Memindahkan seluruh perubahan file ke *staging area*.
  - `git commit -m "pesan commit"`: Menyimpan snapshot perubahan dari *staging area* ke database repository lokal.
  - `git remote add origin <url>`: Menghubungkan repository lokal dengan repository remote di GitHub.
  - `git push origin main`: Mengunggah commit dari lokal ke branch remote di GitHub.
  - `git pull origin main`: Mengambil dan menggabungkan perubahan terbaru dari remote ke lokal.
- **SSH Authentication Setup:** Mengonfigurasi SSH Key (`ed25519`) pada perangkat dan mendaftarkannya di pengaturan GitHub untuk otentikasi aman tanpa perlu mengetikkan kredensial berulang kali.
- **Pengembangan Berbasis AI:** Memanfaatkan AI (*antigravity/ChatGPT/Claude*) untuk membangun aplikasi web sederhana (seperti *Student Task Planner*) secara efisien melalui instruksi prompt yang terstruktur.

---

### 3. Pendapat Pribadi (Impresi Day 1)
> Sesi workshop hari pertama ini memberikan wawasan yang sangat praktis dan relevan bagi mahasiswa teknik. Penggabungan materi antara *Prompt Engineering* dan penggunaan *Git/GitHub* menjadi kombinasi yang krusial di industri modern saat ini. 
> 
> Pembahasan materi dari pemateri disampaikan secara sistematis, mulai dari fundamental alur kerja *version control* hingga integrasi *AI tool* untuk membantu pembuatan kode proyek secara efisien. Melalui workshop ini, pemahaman saya tentang alur kerja kolaboratif menggunakan Git menjadi jauh lebih terarah dan makin siap diimplementasikan pada proyek-proyek teknis mendatang.