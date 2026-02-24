# 🐳 Praktikum DevOps — Pertemuan 02: Docker Fundamentals

📅 **Pertemuan:** 02  
⏱️ **Durasi:** 2 x 50 menit  
📊 **Tingkat:** Dasar-Menengah  

---

## 🎯 Tujuan Pembelajaran
Setelah menyelesaikan praktikum ini, mahasiswa diharapkan mampu:

| No | Kemampuan yang Dicapai |
|----|-----------------------|
| 1  | Memahami konsep kontainerisasi dan perbedaannya dengan virtualisasi |
| 2  | Menjalankan dan mengelola Docker containers |
| 3  | Membuat Docker image menggunakan Dockerfile |
| 4  | Menggunakan Docker Compose untuk aplikasi multi-container |

---

## 📚 Materi Praktikum

### 1️⃣ Docker vs Virtual Machine
Docker membuat aplikasi berjalan konsisten di semua environment: development, staging, dan production.  
Perbedaan utama:

| Virtual Machine | Container |
|-----------------|----------|
| Berat (GB)      | Ringan (MB) |
| Start dalam menit | Start dalam detik |
| Guest OS & Hypervisor | Berbagi kernel host |
| ❌ Lebih tidak portabel | ✅ Portabel antar environment |

---

### 2️⃣ Arsitektur Docker

**Komponen utama:**

| Komponen         | Fungsi |
|-----------------|--------|
| Docker CLI       | Command line untuk berinteraksi dengan Docker |
| Docker Daemon    | Service yang menjalankan container |
| Docker Image     | Template read-only untuk membuat container |
| Docker Container | Instance yang berjalan dari sebuah image |
| Docker Registry  | Tempat menyimpan dan berbagi images |

---

### 3️⃣ Perintah Docker Dasar

**Manajemen Image:**
```bash
docker pull nginx:latest
docker images
docker rmi nginx:latest
docker search python