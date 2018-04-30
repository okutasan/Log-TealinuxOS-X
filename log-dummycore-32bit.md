### LOG CORE DUMMY TEALINUXOS X


##### Proses Unpack    
 File iso 18.04 akan dijadikan core dummy TealinuxOS X. Alat menggunakan UCK. Prosesnya sebagai berikut
```bash
$ sudo uck-remaster-unpack-iso namafile.iso
$ sudo uck-remaster-unpack-rootfs 
$ sudo uck-remaster-unpack-initrd
$ sudo uck-remaster-chroot-rootfs
```
##### Daftar Remove
 Cara remove dengan cara
```bash
$ apt remove --purge namaaplikasi
``` 
 Selesaikan remove aplikasi berikut
```
xfce4-dict 
atril
atril-common
firefox 
firefox-locale-en 
xul-ext-ubufox 
gigolo 
gparted 
libreoffice-common 
gnome-mines 
mousepad 
xfce4-notes 
xfce4-notes-plugin 
orage 
parole 
pidgin-data 
pidgin-otr 
gnome-sudoku 
thunderbird 
transmission-common 
xfburn 
ristretto
sgt-launcher
sgt-puzzles
```
