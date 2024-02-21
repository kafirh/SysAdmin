# SUDO 🛰️

    Nama		: Moch. Irham Kafi Billah
    NRP		    : 3122600009
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Administrasi Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

#

<div class="image-container" align="center">
    <img src="assets/Screenshot 2024-02-21 164906.png" alt="" width="70%">
</div>

Perintah sudo ("superuser do") adalah utilitas di sistem operasi Linux yang memungkinkan pengguna untuk menjalankan perintah dengan hak akses superuser atau hak akses lain yang ditentukan sebelumnya. Perintah ini memberikan fleksibilitas dalam mengelola akses pengguna dan keamanan sistem.

### Fungsi 'sudo'

Berikut adalah beberapa fungsi utama dari sudo:
<ol>
  <li>Pemberian Hak Akses Superuser: sudo memungkinkan pengguna biasa untuk menjalankan perintah dengan hak akses superuser (root). Ini memungkinkan pengguna untuk melakukan tugas-tugas administratif dan mengakses berkas-berkas sistem yang biasanya hanya dapat diakses oleh root.</li>
  <li>Pengawasan Akses Pengguna: Dengan sudo, administrator sistem dapat mengontrol akses pengguna secara lebih terperinci. Mereka dapat menentukan pengguna mana yang diizinkan untuk menjalankan perintah tertentu, menghindari penggunaan akun root secara langsung untuk menjaga keamanan sistem.</li>
  <li>Audit Log: sudo mencatat setiap penggunaan yang berhasil maupun yang gagal dalam log, memberikan jejak audit yang berguna untuk memantau aktivitas pengguna dan potensial penyalahgunaan.</li>
  <li>Keamanan Sistem: Dengan memungkinkan pengguna untuk menjalankan perintah sebagai superuser secara selektif, sudo membantu meningkatkan keamanan sistem dengan mengurangi risiko perubahan yang tidak disengaja atau penyalahgunaan hak akses superuser.</li>
  <li>Privilege Escalation: sudo juga dapat digunakan oleh pengguna yang memiliki hak akses terbatas untuk meningkatkan hak akses mereka sementara untuk menjalankan perintah tertentu yang memerlukan akses superuser.</li>
</ol>

### contoh

Contoh penggunaan umum sudo adalah ketika pengguna ingin menginstal perangkat lunak, mengubah konfigurasi sistem, atau melakukan tugas administratif lainnya yang memerlukan hak akses superuser. Pengguna dapat menggunakan sudo sebelum perintah yang ingin mereka jalankan untuk meminta izin tambahan.