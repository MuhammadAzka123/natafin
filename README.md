
# NataFin

## Topik
Pengelolaan Keuangan Sehari-hari

## Nama Aplikasi
NataFin

## Deskripsi Aplikasi

NataFin adalah aplikasi web untuk membantu pengguna mengelola keuangan sehari-hari dengan lebih teratur. Aplikasi ini membantu pengguna mencatat pemasukan dan pengeluaran, melihat ringkasan keuangan, serta memantau target tabungan.

Dashboard menampilkan ringkasan pemasukan, pengeluaran, tabungan, sisa saldo, dan daftar transaksi. Halaman tambah transaksi menyediakan formulir untuk mencatat jenis transaksi, kategori, nominal, tanggal, dan keterangan transaksi.

Halaman detail keuangan menampilkan ringkasan keuangan, target tabungan, dan rincian pengeluaran berdasarkan kategori. Struktur aplikasi dikembangkan secara bertahap agar dapat dilanjutkan ke tahap pengembangan fullstack pada minggu berikutnya.

## Alasan Memilih Bootstrap

Bootstrap dipilih karena menyediakan komponen antarmuka siap pakai seperti navbar, card, tabel, form, tombol, dan berbagai utility class. Komponen tersebut membantu mempercepat pengembangan tampilan NataFin sehingga pengerjaan dapat lebih berfokus pada struktur dan kebutuhan aplikasi.

Aplikasi NataFin memiliki beberapa halaman dengan fungsi yang berbeda, sehingga sistem grid Bootstrap menggunakan `container`, `row`, dan `col` membantu mengatur tata letak ringkasan keuangan, tabel, dan formulir. Komponen responsifnya juga membantu menyesuaikan tampilan dari desktop ke perangkat mobile.

Bootstrap digunakan melalui CDN sehingga dapat diterapkan tanpa proses build tambahan pada tahap frontend ini. Penggunaan Bootstrap juga memudahkan pengembangan berikutnya ketika NataFin mulai dihubungkan dengan backend dan database.

## Screenshot

Screenshot setiap tahap pengembangan tersimpan di folder `docs/screenshots`:

- `minggu-2`: struktur HTML tanpa CSS.
- `minggu-3`: styling menggunakan CSS native, dengan tampilan desktop dan mobile.
- `minggu-4`: kerangka tampilan menggunakan Bootstrap, dengan tampilan desktop dan mobile.
