### LOG CORE DUMMY TEALINUXOS X


##### Proses Unpack    
 File iso 18.04 akan dijadikan core dummy TealinuxOS X. Alat menggunakan UCK. Prosesnya sebagai berikut
```bash
$ sudo uck-remaster-unpack-iso namafile.iso
$ sudo uck-remaster-unpack-rootfs 
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
 Atau dengan cara instan berikut 
```bash
$ apt remove --purge xfce4-dict atril atril-common firefox firefox-locale-en xul-ext-ubufox gigolo gparted libreoffice-common gnome-mines mousepad xfce4-notes xfce4-notes-plugin orage parole pidgin-data pidgin-otr gnome-sudoku thunderbird transmission-common xfburn ristretto sgt-launcher sgt-puzzles
```
##### Daftar Install 
**Office**
- Libre Office
- File Roller + Rar (Plugin)
- Evince
- Gedit


**Multimedia**
- VLC
- Inkscape
- Brasero

**Development**
- Code::Blocks
- VS Code

**Internet**
- Firefox
- Transmision

**Tea Software**
- Theme Swithcer
- Tea maker + Tea installer
- Lapor Hama
- Modularitea

**Utilitas**
- Workrave
- Redshift
- Gdebi (Installer)
- Gnome Task Manager

**Compiler+ToolsDev**
- Git
- Curl
- Npm
- Open JDK 8 / 9
- gcc
- build-essential

ada tambahan ? 
add gksu https://askubuntu.com/questions/1030054/how-to-install-an-application-that-requires-gksu-package-on-ubuntu-18-04/1030066
