<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto WordPress Chaker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #4a90e2;  /* Warna biru lembut */
        }
        pre {
            background-color: #2d2d2d;
            color: #f1f1f1;
            padding: 12px;
            border-radius: 6px;
            font-size: 1em;
        }
        .feature-list {
            list-style-type: none;
            padding: 0;
        }
        .feature-list li {
            background: #e8f1f9;
            margin: 5px 0;
            padding: 12px;
            border-radius: 6px;
            font-size: 1em;
            color: #333;
        }
        .requirements, .install, .usage {
            margin-bottom: 20px;
        }
        .output {
            background-color: #d6f5d6;
            border-left: 5px solid #4caf50;
            padding: 15px;
            font-size: 1em;
            color: #333;
        }
        .warning {
            color: #b33c3c;
            background-color: #fffbf2;
            padding: 10px;
            border-radius: 6px;
            font-size: 1em;
        }
        .license {
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 6px;
            font-size: 1em;
        }
        a {
            color: #4a90e2;  /* Link berwarna biru */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <h1>Auto WordPress Chaker</h1>

    <p><strong>Auto WordPress Chaker</strong> adalah alat untuk memeriksa login ke situs WordPress secara otomatis dan mengkategorikan login yang berhasil.</p>

    <h2>Fitur</h2>
    <ul class="feature-list">
        <li>Cek login otomatis ke WordPress.</li>
        <li>Kategorisasi login yang berhasil (WooCommerce, WP File Manager, dll).</li>
        <li>Menyimpan hasil login ke file yang berbeda.</li>
    </ul>

    <h2>Persyaratan</h2>
    <ul class="requirements">
        <li>Python 3.x</li>
        <li>Pustaka <strong>requests</strong></li>
    </ul>

    <h2>Instalasi</h2>
    <p>Ikuti langkah-langkah berikut untuk menginstal dan menyiapkan proyek ini:</p>
    <ol class="install">
        <li>Clone repositori:</li>
        <pre>git clone https://github.com/username/repo.git</pre>
        <li>Pindah ke direktori proyek:</li>
        <pre>cd repo</pre>
        <li>Instal pustaka yang dibutuhkan:</li>
        <pre>pip install requests</pre>
    </ol>

    <h2>Cara Penggunaan</h2>
    <p>Setelah instalasi selesai, jalankan skrip menggunakan perintah berikut:</p>
    <pre>python auto_wordpress_chaker.py</pre>
    <p>Masukkan file yang berisi URL dan kredensial situs WordPress.</p>

    <h2>Output</h2>
    <div class="output">
        Hasil login yang berhasil akan disimpan dalam file seperti <code>loginSuccess.txt</code>.
    </div>

    <h2>Lisensi</h2>
    <p class="license">Proyek ini dilisensikan di bawah Lisensi MIT.</p>

    <h2>Penafian</h2>
    <div class="warning">
        Gunakan hanya untuk tujuan pendidikan dan peretasan etis.
    </div>

</body>
</html>
