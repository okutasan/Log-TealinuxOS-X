### LOG CORE DUMMY TEALINUXOS X


##### Proses Unpack    
 File iso 16.04.04 akan dijadikan core dummy TealinuxOS X. Alat menggunakan UCK. Prosesnya sebagai berikut
```bash
$ sudo uck-remaster-unpack-iso namafile.iso
$ sudo uck-remaster-unpack-rootfs 
$ sudo uck-remaster-unpack-initrd
$ sudo uck-remaster-chroot-rootfs
```

