# 🐳 Laporan Praktikum DevOps - Pertemuan 02
**Nama:** Futri Ayu Reski Amalia  
**NIM:** 105841117623  
**Kelas:** (Isi Kelas Kamu di Sini)

---

## 📝 Deskripsi Tugas
Pada pertemuan ini, saya telah mempraktikkan dasar-dasar Docker, mulai dari manajemen *container*, pembuatan *custom image* melalui `Dockerfile`, hingga orkestrasi sederhana menggunakan `Docker Compose`.

---

## 🚀 Hasil Implementasi

### 1. Docker Basic & Container Management
Menjalankan container Nginx dan memastikan service berjalan dengan baik di port yang ditentukan.

**Bukti Running:**
![Container Running](screenshots/01-container-running.png)
![Nginx Browser](screenshots/02-nginx-browser.png)

### 2. Custom Dockerfile
Membuat image sendiri yang sudah di-bundle dengan file `index.html` custom.

**Proses Build & Hasil Image:**
![Docker Build](screenshots/03-docker-build.png)
![Custom Image](screenshots/04-custom-image.png)

### 3. Docker Compose (Multi-Service)
Otomatisasi deployment menggunakan `docker-compose.yml` untuk mempermudah manajemen layanan.

**Status Service:**
![Compose PS](screenshots/05-compose-ps.png)
![Compose Services](screenshots/06-compose-services.png)

---

## 🧠 Refleksi & Kesimpulan
- **Docker** mempermudah distribusi aplikasi tanpa pusing mikirin perbedaan OS (*It works on my machine!*).
- **Docker Compose** sangat membantu kalau kita punya banyak service yang saling terhubung (misal web + database).
- **Kendala:** Sempat ada kendala di penempatan folder, tapi akhirnya berhasil dirapikan sesuai struktur repositori dosen.

---
*Dibuat dengan ❤️ untuk memenuhi tugas mata kuliah DevOps.*