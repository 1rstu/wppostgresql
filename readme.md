
== Deskripsi ==

PostgreSQL untuk WordPress (PG4WP) memberi Anda kemungkinan untuk menginstal dan menggunakan WordPress dengan database PostgreSQL sebagai backend.
Ini berfungsi dengan mengganti panggilan ke fungsi spesifik MySQL dengan panggilan umum yang memetakannya ke fungsi database lain dan menulis ulang kueri SQL dengan cepat saat diperlukan.

Saat ini, dukungan difokuskan pada PostgreSQL, tetapi database lain dapat ditambahkan dengan mudah dengan menyediakan 'driver' yang sesuai.
Driver MySQL tertutup, yang tidak melakukan "apa-apa".
Jika Anda membutuhkan / menginginkan dukungan untuk database lain, silakan hubungi penulis, menulis driver tidak terlalu sulit jika Anda tahu sedikit tentang SQL dan database yang ingin Anda dukung.

Jika Anda ingin menggunakan plugin ini, Anda harus memperhatikan hal-hal berikut:
- WordPress dengan PG4WP diharapkan lebih lambat daripada WordPress asli dengan MySQL karena PG4WP melakukan banyak penulisan ulang SQL untuk setiap tampilan halaman
- Beberapa plugin WordPress seharusnya berfungsi 'di luar kotak' tetapi banyak plugin tidak berfungsi karena mereka memerlukan kode khusus di PG4WP

Anda seharusnya tidak mengharapkan kode khusus plugin apa pun diintegrasikan ke dalam PG4WP kecuali untuk plugin yang dikirimkan dengan WordPress itu sendiri (seperti Akismet).
PG4WP 2.0 akan memiliki mekanisme untuk menambahkan dukungan plugin.

Versi Wordpress 5.1.1_id
