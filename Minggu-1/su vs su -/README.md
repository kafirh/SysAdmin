# su vs su - 🛰️

    Nama		: Moch. Irham Kafi Billah
    NRP		    : 3122600009
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Administrasi Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

#

<div class="image-container" align="center">
    <img src="assets/Screenshot 2024-02-21 164359.png" alt="" width="70%">
</div>

Perintah su dan su - adalah perintah yang digunakan di sistem Linux untuk beralih ke akun pengguna lain. Namun, ada perbedaan penting antara keduanya:

### 1. 'su'
su: Ini singkatan dari "switch user" atau "substitute user". Ketika Anda menggunakan perintah su tanpa opsi tambahan, Anda akan beralih ke akun pengguna lain tetapi lingkungan lingkungan (environment) saat ini (termasuk variabel lingkungan seperti PATH, HOME, dan lain-lain) tidak akan berubah. Ini berarti bahwa Anda akan menggunakan shell baru dengan hak akses pengguna yang ditentukan, tetapi tetap menggunakan konfigurasi lingkungan dari pengguna saat ini.

### 2. 'su -'
su -: Ini juga "switch user", tetapi dengan opsi -, yang juga dikenal sebagai "login shell". Ketika Anda menggunakan perintah su -, Anda akan beralih ke akun pengguna lain dan lingkungan saat ini akan dihapus dan digantikan dengan lingkungan pengguna yang baru. Ini termasuk variabel lingkungan, direktori kerja (biasanya ke direktori home baru), dan setting lain yang biasanya diatur saat pengguna tersebut masuk ke dalam sistem.

### 3. perbedaan
Jadi, perbedaan utama antara su dan su - terletak pada apakah lingkungan saat ini tetap atau digantikan dengan lingkungan pengguna yang baru. Biasanya, jika Anda ingin sepenuhnya beralih ke pengguna lain dengan semua konfigurasi dan lingkungan yang sesuai, Anda akan menggunakan su -.