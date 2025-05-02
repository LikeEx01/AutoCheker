# Auto WordPress Chaker

## Deskripsi
**Auto WordPress Chaker** adalah alat untuk memeriksa login ke situs WordPress secara otomatis dan mengkategorikan login yang berhasil. Alat ini menggunakan teknik brute force untuk memeriksa kredensial pengguna di berbagai situs WordPress dan menyimpan hasilnya dalam file terpisah berdasarkan kategori.


## Fitur Utama
- Cek login otomatis ke WordPress
- Kategorisasi login yang berhasil (WooCommerce, WP File Manager, dll)
- Menyimpan hasil login ke file yang berbeda
- Mendukung banyak thread untuk mempercepat proses

## Persyaratan
- Python 3.x
- Pustaka `requests`
- Platform: Windows, Linux, atau MacOS

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan proyek ini:

1. Clone repositori:
    ```bash
    https://github.com/RidXploit403/AutoCheker.git
    ```

2. Pindah ke direktori proyek:
    ```bash
    cd AutoCheker
    ```

3. Instal pustaka yang dibutuhkan:
    ```bash
    pip install requests
    ```

## Penggunaan

Setelah instalasi selesai, ikuti langkah-langkah berikut untuk menjalankan alat ini:

1. Jalankan skrip dengan perintah berikut:
    ```bash
    python AutoCheker.py
    ```

2. Masukkan file yang berisi URL dan kredensial situs WordPress yang akan diperiksa.

3. Tentukan jumlah thread yang diinginkan untuk mempercepat proses.

4. Hasil login yang berhasil akan disimpan dalam file seperti `loginSuccess.txt`, `WooCommerce.txt`, dan `wpfilemanager.txt`.

## Output
Setelah menjalankan skrip, hasil login yang berhasil akan disimpan dalam file sebagai berikut:

- `loginSuccess.txt`: Menyimpan Valid Request.
- `WooCommerce.txt`: Menyimpan login WooCommerce.
- `wpfilemanager.txt`: Menyimpan login WP File Manager.
- `plugin-install.txt`: Menyimpan login untuk menginstal plugin.

## Lisensi
Proyek ini dilisensikan di bawah [Lisensi MIT](https://opensource.org/licenses/MIT).

## Penafian
> **Peringatan:** Gunakan hanya untuk tujuan pendidikan dan peretasan etis! Alat ini hanya untuk digunakan dalam pengujian penetrasi yang sah dan dengan izin eksplisit dari pemilik situs.

## Badge
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Kontak
Jika Anda memiliki pertanyaan atau masalah, jangan ragu untuk membuka [issue](https://github.com/username/repo/issues) di GitHub atau hubungi saya di [email@example.com](mailto:t.me/TempeSec1337).

## Terima Kasih
Terima kasih telah menggunakan **Auto WordPress Chaker**. Semoga proyek ini bermanfaat untuk pengujian keamanan situs WordPress Anda!

[GitHub Repo](https://github.com/username/repo)
