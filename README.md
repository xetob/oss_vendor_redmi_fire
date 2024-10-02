This is oss vendor for redmi 12 (xiaomi-fire)
Support only GSI

changes I made:
-Fixed the problem of sensors that led to soft reboots 
-Deleted miui hyperos files

How to flash:
Reboot fastbootd (adb reboot fastboot)
Flash GSI
Flash Custom vbmeta (fastboot flash vbmeta vbmeta_patched.img)
Flash vendor (fastboot flash vendor vendor.img)
Format data and reboot

if you want to change something yourself just unpack it 