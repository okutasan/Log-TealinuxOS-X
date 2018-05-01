### Log Core
 Sukses remove aplikasi pada list.

### Log Build 2
 - Remove xfce-taskmanager
 - install git
 - add plymouth dandelion via script
*testing*
 - plymouth tidak mau muncul
 - solusi mencoba add manual

### Log Build 3
 - Add playmouth manual
 - setting manual
 - jangan lupa update initramfs
 ```update-initramfs -u```
 - jangan lupa buat initrd.lz dan copy ke casper.
*testing*
 - tetap tidak mau
 - back to Core Build

### Log Build 4 
 - unpack core , unpack rootfs
 - remove xfce-taskmanager
 - tambah plymouth
