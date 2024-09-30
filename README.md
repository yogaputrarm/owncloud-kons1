<h2 align="center">Instal OpenVPN for Debian</h2>
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيْم

## Bahan
- VM OS Debian 
- Putty [Putty](https://putty.org/)
- ISO OwnCloud [OwnCloud](https://www.turnkeylinux.org/owncloud)]

## Langkah Instalasi
- Buatlah VM baru di virtual box, kemudian masukkan file ISO yang telah di unduh
- Atur adapter network pada vm menggunakan Bridge Adapter
- Lakukan Instalasi OwnCloud dengan install to harddisk
- Kemudian pilih Guided - use entire disk
- Kemudian pilih Finish partitioning and write changes to disk
- Pada menu Debian Installer Live pilih "yes"
- Pada menu Install the GRUB boot loader on a hard disk pilih "yes"
- Kemudian Lakukan "Reboot System"

## Langkah Konfigurasi
- Matikan VM lalu Remove file ISO pada VM, kemudian nyalakan kembali VM
- Atur password untuk akun Root
- Atur password untuk MySQL
- Atur password untuk akun OwnCloud
- Atur domain untuk OwnCloud (sesuai keinginan)
- Setelah Muncul IP dari OwnCloud server, lakukan enter dan masuk menggunakan akun Root
- Buka Putty, lalu remote ip server OwnCloud dan masuk menggunakan akun Root
- lakukan konfigurasi ip pada file OwnCloud di directory

## Buka Server OwnCloud pada Browser 
- Buka IP Server OwnCloud yang kalian dapatkan pada browser

