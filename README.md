<img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=bang-sahrul-gunawan-cyber&" alt="Termux-Python--Environments" /></p>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=bang-sahrul-gunawan-cyber&label=Profile%20views&color=0e75b6&style=flat" alt="Termux-Python--Environments" /> </p>
<h3 align="left">My Instagram:</h3>
<p align="left">
<a href="https://instagram.com/wes_kadung_rewel" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="wes_kadung_rewel" height="30" width="40" /></a>
</p>

# Setup Install Python ENV
- Siapkan Bahan Dulu Sebelum Install
- Siapkan Kuota Anda
- Siapkan Kopi Bila Perlu
- Siapkan Rokok Biar Gak Gabut :)
- Cara Install Lihat Dibawah Ini

#
- Apakah Butuh Akses Root Bang ?
- Tentu Saja Tidak Butuh Akses Root 99% 

#
- Kenapa Paket Abang Pakai Compress name.tar.gz
- Karena Distribusi Env Pakai Symbolic link
- Permission Nya Beda Setelah Diupload Luar
- Dari Ruang Linux . Symbolic link Sangatlah Penting


# Cara Install Nya Dibawah Ini Copy Saja

[ ] Bagian 1
- Install Python Nya Dulu

```
apt install python python2 -y
```

[ ] Bagian 2
- Buat Directory Baru

```
mkdir PYTHON-ENV
```

[ ] Bagian 3
- Install Nama Env Anda
```
python3 -m venv SahrulGunawan
```

[ ] Bagian 4
- Jalankan Env Python Anda 
```
source SahrulGunawan/bin/deactivate
```

[ ] Bagian 5
- Untuk Menonaktifkan Cukup Ketik (deactivate lalu Enter)

```
deactivate
```

#
[ ] Unduh Files Tar.Gz Lebih Effectif
- Cara Pasangnya Tar Gz Cukuplah Mudah

# Setup Resrstore Project Dalam Folder
- tar -zxf /sdcard/xxxx/env-python.tar.gz -C /data/data/com.termux/files/home --recursive-unlink --preserve-permissions

# Setup Rerstore Project Diluar Folder
- tar -zxf /sdcard/env-python.tar.gz -C /data/data/com.termux/files/home --recursive-unlink --preserve-permissions
- Khusus Diluar Folder Unduhan /sdcard

#
- Kenapa Ada Format Text XXXX . Itu Dalam Folder Yang File Kamu Download
- Setiap Download Pastinya Akan Tersimpan Di Folder Khusus
- Contoh Nya Folder Download
- Yang XXXX tinggal Rename Saja Sesuai Jalur Unduh Folder Kamu
