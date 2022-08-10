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
