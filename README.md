NAMA : AGUNG HIKMANTARA

NIM  : 1002250045



Ringkasan Aktivitas Praktikum Administrasi Sistem Linux

Praktikum ini bertujuan untuk membekali peserta dengan pemahaman komprehensif mengenai administrasi sistem operasi Linux melalui implementasi langsung pada lingkungan Kali Linux. Kegiatan diawali dengan identifikasi sistem menggunakan perintah untuk menampilkan informasi inti sistem, meliputi jenis sistem operasi, versi kernel, dan arsitektur perangkat keras. Selanjutnya dilakukan perubahan hostname sistem sesuai dengan ketentuan yang ditetapkan, yang kemudian diverifikasi dan didokumentasikan secara tertulis guna menjaga konsistensi serta keterlacakan perubahan konfigurasi sistem.

Tahapan berikutnya berfokus pada manajemen direktori dan file sebagai aspek fundamental dalam administrasi Linux. Pada tahap ini, dibuat struktur direktori kerja secara hierarkis, dilanjutkan dengan pembuatan dan pengeditan beberapa berkas teks menggunakan editor berbasis terminal. Seluruh berkas diisi dengan konten minimal sesuai ketentuan dan diverifikasi menggunakan perintah penampil isi berkas. Praktikum juga mencakup operasi penyalinan, penggantian nama, dan pemindahan berkas, serta pemeriksaan struktur direktori secara rekursif. Selain itu, dilakukan analisis isi berkas menggunakan berbagai utilitas untuk menampilkan sebagian konten dan menghitung jumlah baris, kata, serta karakter. Pengaturan hak akses berkas diterapkan untuk memahami mekanisme kontrol keamanan berbasis permission pada sistem Linux.

Pada bagian pengolahan teks dan pencarian data, praktikum menitikberatkan pada pemanfaatan utilitas Linux untuk melakukan pencarian pola, penyaringan data, dan ekstraksi informasi terstruktur. Data diformat secara konsisten untuk memudahkan pemrosesan, kemudian dilakukan pengurutan, penghapusan data duplikat, serta penghitungan jumlah entri unik. Penggunaan pipeline diterapkan untuk menggabungkan beberapa perintah dalam satu alur kerja yang efisien. Seluruh perintah yang digunakan didokumentasikan secara sistematis dalam sebuah berkas khusus.

Tahap instalasi dan verifikasi perangkat lunak diawali dengan pembaruan sistem operasi untuk memastikan seluruh paket berada pada versi terkini. Selanjutnya dilakukan instalasi berbagai tools keamanan yang umum digunakan dalam administrasi dan analisis jaringan. Setiap tools yang terinstal diverifikasi keberadaannya serta versinya, dan seluruh proses instalasi dicatat secara rinci, termasuk tanggal dan waktu pemasangan.

Pada aspek jaringan dan konektivitas, dilakukan pengambilan informasi konfigurasi jaringan yang mencakup alamat IP, netmask, dan gateway. Praktikum juga mencakup identifikasi port jaringan yang aktif untuk mengetahui layanan yang berjalan pada sistem. Layanan SSH kemudian diaktifkan dan diuji melalui koneksi jarak jauh dari sistem operasi lain guna memastikan fungsi akses remote berjalan dengan baik. Konfigurasi lanjutan dilakukan melalui pengelolaan layanan sistem, analisis berkas konfigurasi SSH, pengaturan pemetaan nama host lokal, peninjauan konfigurasi jaringan dan DNS, serta penerapan firewall untuk membatasi dan mengamankan lalu lintas jaringan.

Sebagai tahap akhir, dilakukan perbandingan beberapa distribusi Linux untuk memahami perbedaan mendasar dalam manajemen paket, sistem inisialisasi, layanan SSH, dan firewall. Selain itu, disusun daftar perintah yang setara pada berbagai platform Linux sebagai referensi administrasi lintas distribusi. Seluruh hasil praktikum, dokumentasi perintah, serta bukti tangkapan layar dikumpulkan dalam satu struktur direktori terorganisasi sebagai laporan akhir kegiatan.

Kendala dan Solusi

Selama pelaksanaan praktikum, beberapa kendala teknis ditemukan. Kendala utama meliputi kegagalan koneksi SSH akibat kesalahan alamat IP dan layanan SSH yang belum aktif. Permasalahan ini diatasi dengan memverifikasi konfigurasi jaringan, memastikan layanan SSH berjalan, serta membuka port yang diperlukan pada firewall. Kendala lain berupa kesalahan hak akses berkas yang menyebabkan berkas tidak dapat diakses sebagaimana mestinya. Hal ini diselesaikan dengan penyesuaian permission menggunakan perintah yang sesuai. Selain itu, keterbatasan pemahaman awal terhadap beberapa perintah Linux diatasi dengan menjalankan perintah secara bertahap dan memverifikasi setiap keluaran yang dihasilkan sebelum melanjutkan ke tahap berikutnya.

Daftar Tools yang Terinstal

Tools keamanan dan administrasi sistem yang berhasil diinstal dan diverifikasi pada praktikum ini meliputi:

Nmap – digunakan untuk pemindaian jaringan dan port.

Wireshark – digunakan untuk analisis lalu lintas jaringan.

Tcpdump – digunakan untuk pemantauan paket jaringan berbasis terminal.

Aircrack-ng – digunakan untuk pengujian keamanan jaringan nirkabel.

Burp Suite – digunakan untuk analisis dan pengujian keamanan aplikasi web.

OpenSSH – digunakan untuk menyediakan layanan akses jarak jauh yang aman.

UFW Firewall – digunakan untuk pengelolaan aturan firewall pada sistem Linux.
