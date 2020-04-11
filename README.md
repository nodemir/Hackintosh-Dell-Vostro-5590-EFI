# Hackintosh-DellVostro5590-EFI
EFI for Dell Vostro 5490/5590 and Inspiron 5490/5498/5590/5598 models

WARNING: Tested only on Dell Vostro 5590! For other models you may need to change some things (for example gpu device-id and ig-platform or SMBIOS). It's recommended to update bios to the latest version - 1.5.1. There are still a lot of things to fix so if you don't understand what you are doing better use Windows/Linux or buy a real MacBook!

WARNING: This is an Opencore EFI folder so it wont work with Clover! Booting on those laptops using Clover is quite impossible for now.

macOS Version: Catalina 10.15.4

Tested configuration:
Dell Vostro 5590
- i5 10210U
- UHD 620
- 12GB RAM
- Intel WiFi 9462
- Realtek ALC 3204
- 250GB SK Hynix SSD

What works:
- Booting/Shutdown/Restart
- Speed Step
- Graphics
- All USB-A ports (USB-C not tested)
- LAN
- Battery indication
- Keyboard

Not working (this is only for now):
- WiFi (it may be supported soon, a new AppleIntelWifi.kext is under work)
- Sound (still trying to figure out which layouts or patches are needed)
- Trackpad (it works as an emulated mouse so no gestures)
- Sleep
- Brightness regulation
- Mic and camera (didn't even try to fix them, mic wont work with AppleALC)
- Bluetooth

I am still working on this EFI so I will update it as soon as I have any progress on it.
