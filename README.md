# Auto WordPress Chaker

## Deskripsi
**Auto WordPress Chaker** adalah alat untuk memeriksa login ke situs WordPress secara otomatis dan mengkategorikan login yang berhasil. Alat ini menggunakan teknik brute force untuk memeriksa kredensial pengguna di berbagai situs WordPress dan menyimpan hasilnya dalam file terpisah berdasarkan kategori.

## Fitur Utama
- Cek login otomatis ke WordPress
- Kategorisasi login yang berhasil (WooCommerce, WP File Manager, Plugin Installer)
- Menyimpan hasil login ke file yang berbeda
- Menyimpan login gagal ke file terpisah
- Mendukung multi-thread untuk mempercepat proses
- Header random (User-Agent acak)
- Tersedia waktu kadaluarsa untuk keamanan

## Persyaratan
- Python 3.x
- Pustaka `requests`, `idna`
- Platform: Windows, Linux, atau MacOS

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan proyek ini:

1. Clone repositori:
    ```bash
    git clone https://github.com/RidXploit403/AutoCheker.git
    ```

2. Pindah ke direktori proyek:
    ```bash
    cd AutoCheker
    ```

3. Instal pustaka yang dibutuhkan:
    ```bash
    pip install requests idna
    ```

## Penggunaan

Setelah instalasi selesai, ikuti langkah-langkah berikut untuk menjalankan alat ini:

1. Jalankan skrip dengan perintah berikut:
    ```bash
    python AutoCheker.py
    ```

2. Masukkan file `.txt` yang berisi daftar target dengan format:
    ```
    https://example.com|admin|password
    http://site.com/wp-login.php|user|pass123
    ```

3. Tentukan jumlah thread untuk mempercepat proses (misal: 10 atau 20).

4. Hasil login yang berhasil akan disimpan dalam file seperti `WooCommerce.txt`, `wpfilemanager.txt`, `plugin-install.txt`, sedangkan login gagal disimpan di `LoginGagal.txt`.

## Output

Setelah menjalankan skrip, hasil login akan dikategorikan dan disimpan dalam file berikut:

- `WooCommerce.txt`: Menyimpan login WordPress dengan plugin WooCommerce
- `wpfilemanager.txt`: Menyimpan login WordPress dengan plugin WP File Manager
- `plugin-install.txt`: Menyimpan login WordPress dengan akses ke fitur install plugin
- `LoginGagal.txt`: Menyimpan kombinasi login yang gagal

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).

## Penafian
> **Peringatan:** Gunakan hanya untuk tujuan pendidikan dan pengujian etis! Alat ini hanya boleh digunakan dalam pengujian penetrasi legal dan dengan izin eksplisit dari pemilik situs.

## Badge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Kontak
Jika Anda memiliki pertanyaan atau masalah, silakan buka [issue](https://github.com/RidXploit403/AutoCheker/issues) di GitHub atau hubungi saya:

- Telegram: [@TempeSec1337](https://t.me/TempeSec1337)
- Email: tempe@secmail.pro

## Terima Kasih
Terima kasih telah menggunakan **Auto WordPress Chaker**. Semoga proyek ini bermanfaat untuk pengujian keamanan situs WordPress Anda!

[GitHub Repo](https://github.com/RidXploit403/AutoCheker)
