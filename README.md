# V2T (VPN TO TETHER) FOR ANDROID
V2T adalah sebuah shell untuk memungkinkan menggunakan tethering saat VPN sedang aktif.
Perlu akses root untuk menjalankan shell ini.

Terjemahan?
Hubungi kami : deacecroft@gmail.com

## Membutuhkan 
- ROOT
- Iptables (Setiap Android sudah terinstal)
- [Android Terminal Emulator](https://github.com/jackpal/Android-Terminal-Emulator)

## Cara Install
Unduh dulu "v2t" pada perangkat Android Anda dengan perintah di bawah atau mengunduhnya secara manual melalui browser Anda.
```
wget https://github.com/De4ce/v2t/raw/master/v2t
```
Pindahkan "v2t" ke direktori /system/xbin/ atau /system/bin/ dengan menjalankan perintah di bawah, Anda juga dapat memindahkannya dengan aplikasi pengelola berkas.
```
mv v2t /system/xbin/v2t
```
Ubah perizinan "v2t" melalui perintah di bawah. Jika Anda menggunakan pengelola berkas ubah perizinan menjadi 755 atau rwxr-xr-x.
```
chmod 0755 /system/xbin/v2t
```

## Tidak dapat menginstal?
Mungkin Anda belum me-'mount' "READ WRITE" direktori /system, Anda dapat menjalankan perintah di bawah
```
mount -o remount, rw /system
```
Untuk mengembalikannya
```
mount -o remount, ro /system
```
## Cara Menggunakan
Jalankan Terminal Emulator, lalu ketik perintah di bawah
```
su
v2t
```
