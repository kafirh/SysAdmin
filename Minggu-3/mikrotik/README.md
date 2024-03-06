# DHCP network -> manual 🛰️

    Nama		: Moch. Irham Kafi Billah
    NRP		    : 3122600009
    Kelas		: 2 D4 Teknik Informatika
    Mata Kuliah	: Administrasi Jaringan
    Dosen Pengampu	: Dr. Ferry Astika Saputra ST, M.Sc

#

### 1. reset config
### 2. buat bridge
### 3. buat port list
### 4. ke ip -> addresses buat adress dengan nama adresses 192.168.88.5/24 networknya 192.168.88.0 interface ether 1
### 5. buat adress lagi dengan adress 192.168.5.1/24 dengan network 192.168.5.0 interface ke bridge 1
### 6. buat address list ke kelompok lain
### 7. ke dhcp server -> dhcp set up-> pilih bridge 1-> adrres 192.168.5.0/24 -> gateway 192.168.5.1 -> dhcp relay 202.9.85.3.
### 8. ke ip -> firewall-> nat buat srcnat dengan src adress 192.168.5.0/24 dengan dst. adresses 0.0.0.0/0 dan ke bagian action dan ganti action ke masquarade
### 9. buka terminal di windows coba ipconfig -> trs ping ke 1.1.1.1
