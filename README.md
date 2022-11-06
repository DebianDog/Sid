## DebianDog Sid

**Updated 2022-11-06,** ISO replaced (64-bit only), see below for download.
Now the system is "usr-merged" (which is the standard nowadays, e.g. /bin, /lib, /sbin are symlinks)

Updated 2020-11-25, using overlay rather than aufs https://forum.puppylinux.com/viewtopic.php?p=10594#p10594     
Based on the Debian 'sid' branch but **without systemd**.  
It's using special method (taken from **AntiX**) to avoid systemd by replacing systemd with 'elogind'
   
[Forum thread](https://forum.puppylinux.com/viewtopic.php?f=46&t=824)   
**Custom repositories:** [32-bit](https://doglinux.github.io/sidog/i386/) [64-bit](https://doglinux.github.io/sidog/amd64/)  

### Login details:
**root** with password **root**    
**puppy** with password **puppy**

### Iso's available: "full" and "basic"   
**EDIT 2020-11-29:** Discontinued the "basic", ISO's removed
 
**Specifications:**  Updated 2022-11-06             
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/Sid/raw/master/Examples-boot-codes.txt))     
**- Full:**   
Kernel: 6.0.0-2-amd64 (the kernel is separate module)  
Default WM - OpenBox, with Desktop choices (run 'Desktop Manager' to choose):    
- Tint2 panels    
- PcmanFM providing the Desktop and lxpanel    
- Tint2 bottom panel and rox-pinboard providing the Desktop    

Option to switch to JWM window-manager                  
Default File Manager - PcmanFM with option to use rox.        
Default Internet Browser - Firefox-ESR.

### Downloads: (updated "full" ISO to 20221106)
**EDIT 2020-11-29:** Discontinued the "basic", ISO's removed   
Changes and Fixes, see here: https://forum.puppylinux.com/viewtopic.php?p=5509#p5509
- 64-bit [DebianDog-Sid-20221106-usr-merged_amd64-UEFI.iso](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-20221106-usr-merged_amd64-UEFI.iso) / [md5sum](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-20221106-usr-merged_amd64-UEFI.md5)

**Firmware squashfs is included**

**Screenshots:**
 
Openbox with tint2 panels:         
![SCREENSHOT](https://raw.githubusercontent.com/DebianDog/Sid/master/sid-tint2.jpg)        
Openbox with PcmanFM and lxpanel:       
![SCREENSHOT](https://raw.githubusercontent.com/DebianDog/Sid/master/sid-pcmanfm.jpg)   
