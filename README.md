# 🔐 Auto WordPress Chaker

## Deskripsi
Auto WordPress Chaker adalah alat untuk memeriksa login ke situs WordPress secara otomatis dan mengkategorikan login yang berhasil berdasarkan fitur yang tersedia. Alat ini berguna untuk auditor keamanan atau peneliti keamanan siber dalam melakukan uji coba brute-force terhadap kredensial situs WordPress yang telah diotorisasi.

## 🎯 Fitur Utama
- ✅ Deteksi otomatis situs WordPress
- 🔐 Otomatis login dengan username & password
- 📁 Kategorisasi hasil login:
  - WooCommerce
  - WP File Manager
  - Plugin Installer
- 🧠 Deteksi login gagal dan menyimpannya
- 🧵 Mendukung multi-thread untuk kecepatan maksimum
- 📡 Header acak dengan berbagai User-Agent
- 🕓 Terproteksi tanggal kadaluarsa (hingga 30 Januari 2026)
- 🔗 Redirect otomatis ke saluran WhatsApp Developer

## 🖥️ Persyaratan Sistem
- Python 3.x
- Pustaka pihak ketiga:
  - requests
  - idna

## 🛠️ Instalasi

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan proyek ini:

1. Clone repositori:
   git clone https://github.com/RidXploit403/AutoCheker.git

2. Pindah ke direktori proyek:
   cd AutoCheker

3. Instal pustaka yang dibutuhkan:
   pip install requests idna

## 🚀 Penggunaan

Setelah instalasi selesai, ikuti langkah-langkah berikut:

1. Jalankan skrip:
   python AutoCheker.py

2. Masukkan path file target dengan format:
   https://site.com/wp-login.php|admin|password

3. Tentukan jumlah thread untuk mempercepat proses:
   Jumlah Thread (misal 10): 20

## 📤 Format Input
File .txt berisi daftar target dalam format:

https://example.com|admin|pass123  
http://blogsite.net/wp-login.php|wpuser|admin@2024

## 📦 Output

Hasil login yang berhasil dan gagal akan disimpan dalam file berikut:

- WooCommerce.txt: Login berhasil dengan plugin WooCommerce
- wpfilemanager.txt: Login berhasil dengan WP File Manager aktif
- plugin-install.txt: Login berhasil dan memiliki akses installasi plugin
- LoginGagal.txt: Login gagal untuk kombinasi url|user|pass

## 🛡️ Lisensi
Proyek ini menggunakan Lisensi MIT (https://opensource.org/licenses/MIT).  
Silakan gunakan dengan bijak dan hanya untuk tujuan yang sah.

## ⚠️ Penafian
Peringatan: Alat ini hanya untuk penetration testing legal dengan izin eksplisit dari pemilik situs. Penggunaan untuk kegiatan yang tidak sah merupakan pelanggaran hukum.

## 🏷️ Badge
[Build Status: Passing]  
[License: MIT]

## 📬 Kontak
Jika Anda memiliki pertanyaan atau saran, silakan buka issue di GitHub:  
https://github.com/RidXploit403/AutoCheker/issues

Atau hubungi via:
- Telegram: https://t.me/TempeSec1337
- Email: tempe@secmail.pro

## 🙏 Terima Kasih
Terima kasih telah menggunakan Auto WordPress Chaker. Semoga bermanfaat untuk membantu pengujian keamanan situs WordPress Anda dengan cara yang aman dan bertanggung jawab.

GitHub Repo: https://github.com/RidXploit403/AutoCheker  
Channel Developer: https://whatsapp.com/channel/0029VaudLHc7YSd9S9c9800c
