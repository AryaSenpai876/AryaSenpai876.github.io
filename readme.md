# Dokumentasi website hosting menggunakan github:

Anda dapat menggunakan github untuk menghostingkan website Anda secara gratis.
Berikut caranya:

Menyiapkan repository github dari template:
Untuk membuat repository dari template Anda harus mencari template yang ingin Anda gunakan dari github.
Berikut caranya:
1. Buat akun/login akun github
2. Gunakan fitur search untuk mencari template dan masuk ke repository template tersebut
3. Didalam repository tersebut klik tombol "Use this template" dan Anda akan dialihkan ke menu pembuatan repository
4. Beri nama repository Anda sesuka hati dan akhiri dengan ".github.io"; contoh: aryasenpai876.github.io

`Credit : Nanda Zhafran Mahendra`
`github username : nnavyy`
`https://github.com/nnavyy/personal-web`

## Membuat folder version control di file explorer menggunakan Visual Studio Code:

1. Buka aplikasi Visual Studo Code
2. Install ekstensi git yang diperlukan di menu ekstensi
3. Cari dan install ekstensi "GitHub repositories" dan "GitHub pull request"

## Mengclone repository github:

1. Masuk ke command pallete dan ketik "> Git: Clone"
2. Jika ekstensi Anda sudah terinstall dengan benar, ekstensi git untuk mengclone repository akan muncul dan tekan enter
3. Setelah itu akan muncul pilihan untuk mengclone dari github repository dan tekan enter
4. Ekstensi github akan menanyakan URL yang ingin di clone dan copy paste URL repository Anda dan tekan enter
5. Jika URL ditemukan jendela browse akan muncul. Pilih lokasi yang Anda inginkan untuk menaruh hasil dari clone
6. Setelah proses mengcloning selesai Anda akan ditanyakan untuk membuka folder clone tadi. Jika Anda pilih Open maka Vs Code akan membuka dan menggunakan folder tersebut

# Mengedit isi website dengan VS Code:
Setelah Anda berhasil menyimpan folder clone dan menggunakan folder tersebut Anda sudah dapat mengedit isinya. Anda dapat mengedit warna background, font, menambahkan URL media sosial Anda, dan masih banyak hal lainnya. Dokumentasi ini hanya merubah warna gradient, font, mengganti teks, menambahkan URL media sosial, menambahkan proyek, menampilkan icon tab. Semua ini dilakukan di folder version control yang terbuka di aplikasi Visual Studio Code. Setelah Anda mengedit file atau folder apapun di folder version control. Anda harus menyimpannya dengan menekan tombol `Ctrl + S` dan `Commit and Push` di aplikasi Visual Studio Code pada menu Version Control. Sebelum `Commit and Push` Anda harus menuliskan message commit Anda.

## Mengganti warna background:

1. Buka file style.css
2. Anda dapat mengganti warna dengan mengganti kode hex di bagian "primary-color", "secondary-color", "gradient-1" dan "gradient-2"

## Mengganti font:

1. Buka file style.css
2. Cari bagian body, tambahkan nama font yang Anda inginkan di bagian font-family

## Mengganti teks:

1. Buka file index.html
2. Cari teks yang ingin Anda ganti

## Menambahkan URL media sosial:

1. Buka file index.html
2. Cari div class yang bernama "contact__socials"
3. Di template ini sudah ada beberapa media sosial beserta dengan icon dan linknnya yang sudah ada secara default. Anda hanya harus menambahkan tag baru sesuai formatnya:
```
<a href="link profile media sosial Anda">
  <i class="ri-"icon yang ingin anda pakai"-fill">
  </i>
</a>
```

## Menambahkan proyek:

1. Buka file index.html
2. Cari div class "portofolio__grid"
3. Di template ini sudah ada beberapa projek beserta dengan gambarnya. Anda hanya harus menambahkan tag baru sesuai formatnya:

```
div class="portfolio__card">
  <a href="link project Anda">
    <img src="directory gambar/URL Anda" alt="Opsional, akan menampilkan teks jika gambar Anda gagal dimuat">
  </a>
</div>
```

## Menampilkan icon di tab:
Anda sering melihat bahwa website selalu punya ikon di tab browser Anda. Berikut cara membuat website Anda dapat menampilkan icon:

1. Buka website favicon generator yang dapat memproses gambar Anda dan memberikan embed code
2. Masukkan gambar yang ingin dijadikan sebagai icon
3. Setelah gambar diproses oleh website. Copy paste embed Anda di file index.html
```
<link rel="apple-touch-icon" sizes="57x57" href="/assets/icons/apple-icon-57x57.png">
<link rel="apple-touch-icon" sizes="60x60" href="/assets/icons/apple-icon-60x60.png">
<link rel="apple-touch-icon" sizes="72x72" href="/assets/icons/apple-icon-72x72.png">
<link rel="apple-touch-icon" sizes="76x76" href="/apple-icon-76x76.png">
<link rel="apple-touch-icon" sizes="114x114" href="/assets/icons/apple-icon-114x114.png">
<link rel="apple-touch-icon" sizes="120x120" href="/assets/icons/apple-icon-120x120.png">
<link rel="apple-touch-icon" sizes="144x144" href="/assets/icons/apple-icon-144x144.png">
<link rel="apple-touch-icon" sizes="152x152" href="/assets/icons/apple-icon-152x152.png">
<link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-icon-180x180.png">
<link rel="icon" type="image/png" sizes="192x192"  href="/assets/icons/android-icon-192x192.png">
<link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.png">
<link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.png">
<link rel="manifest" href="/assets/icons/manifest.json">
<meta name="msapplication-TileColor" content="#ffffff">
<meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
<meta name="theme-color" content="#ffffff">
```

# Kesimpulan
Github repository dapat digunakan untuk hosting website secara gratis dan cara untuk mengelolanya sangatlah mudah. Jika Anda ingin menghemat waktu untuk membuat website Anda dapat menggunakan template dari user github. Anda dapat menggunakan aplikasi Visual Studio Code untuk mengelola github repository Anda dengan mengunduh dan menginstall ekstensi github. 
