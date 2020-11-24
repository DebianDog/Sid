## DebianDog Sid
Updated 2020-11-24, using overlay rather than aufs https://forum.puppylinux.com/viewtopic.php?p=10594#p10594     
Based on the Debian 'sid' branch but **without systemd**.  
It's using special method (taken from **AntiX**) to avoid systemd by replacing systemd with 'elogind'
   
[Forum thread](https://forum.puppylinux.com/viewtopic.php?f=46&t=824)   
**Custom repositories:** [32-bit](https://doglinux.github.io/sidog/i386/) [64-bit](https://doglinux.github.io/sidog/amd64/)  

### Login details:
**root** with password **root**    
**puppy** with password **puppy**

### Iso's available: "full" and "basic"
 
**Specifications:**  Updated 2020-11-24           
Kernel: 5.9.0-3 (the kernel is separate module)  
Choice of Boot Methods: porteus-boot and live-boot v3 (see for options [Here](https://github.com/DebianDog/Sid/raw/master/Examples-boot-codes.txt))     
**- Full:**   
Default WM - OpenBox, with Desktop choices (run 'Desktop Manager' to choose):    
- Tint2 panels    
- PcmanFM providing the Desktop and lxpanel    
- Tint2 bottom panel and rox-pinboard providing the Desktop    

Option to switch to JWM window-manager                  
Default File Manager - PcmanFM with option to use rox.        
Default Internet Browser - Firefox-ESR.
   
**- Basic:**  
Default WM - OpenBox,
Default File Manager and providing Desktop - PcmanFM.
Not much applications installed, only e.g. Firefox, viewnior, leafpad etc.. and system/module tools

### Downloads: (updated "full" ISO's to 20201124)
Changes and Fixes, see here: https://forum.puppylinux.com/viewtopic.php?p=5509#p5509
- Full, 64-bit [DebianDog-Sid-full-20201124-overlay_amd64-UEFI.iso](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-full-20201124-overlay_amd64-UEFI.iso) / [md5sum](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-full-20201124-overlay_amd64-UEFI.md5)
- Full, 32-bit [DebianDog-Sid-full-20201124-overlay_i386-pae-UEFI.iso](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-full-20201124-overlay_i386-pae-UEFI.iso) / [md5sum](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-full-20201124-overlay_i386-pae-UEFI.md5) 
- Basic, 64-bit [DebianDog-Sid-basic-20200920_amd64-UEFI.iso](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-basic-20200920_amd64-UEFI.iso) / [md5sum](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-basic-20200920_amd64-UEFI.md5)   
- Basic, 32-bit [DebianDog-Sid-basic-20200920_i386-pae-UEFI.iso](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-basic-20200920_i386-pae-UEFI.iso) / [md5sum](https://github.com/DebianDog/Sid/releases/download/v0.1/DebianDog-Sid-basic-20200920_i386-pae-UEFI.md5)  
 
Firmware (mostly for wifi): [Firmware squashfs](https://github.com/DebianDog/Sid/releases/download/v0.2/99-firmware-sid.squashfs)

**Screenshots:**
 
Openbox with tint2 panels:         
![SCREENSHOT](https://raw.githubusercontent.com/DebianDog/Sid/master/sid-tint2.jpg)        
Openbox with PcmanFM and lxpanel:       
![SCREENSHOT](https://raw.githubusercontent.com/DebianDog/Sid/master/sid-pcmanfm.jpg)   
