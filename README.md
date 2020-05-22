# Hackintosh-DellVostro5590-EFI
EFI for Dell Vostro 5490/5590

WARNING: Tested only on Dell Vostro 5590! For other models you may need to change some things (for example gpu device-id and ig-platform or SMBIOS). It's recommended to update bios to the latest version. There are still a few things to fix as the sound is the biggest problem.

macOS Version: Catalina 10.15.4
It wont work on any older macOS versions because 10.15.4 is the first to support intel's 10th generation processors.

Tested configuration:
Dell Vostro 5590
- i5 10210U
- UHD 620
- 12GB RAM
- Intel WiFi 9462
- Realtek ALC 3204/236
- 250GB SK Hynix SSD
- HID Touchpad device

What works:
- Booting/Shutdown/Restart
- Speed Step
- Graphics
- All USB-A ports (mapped) [USB-C not tested]
- LAN
- Battery indication/status
- Keyboard
- Brightness regulation
- Sleep/Wake/Instant On
- Touchpad
- NVRAM

Not working (this is only for now):
- WiFi (it may be supported soon, a new AppleIntelWifi.kext is under work)
- Sound (still trying to figure out which layouts or patches are needed)
- Mic and camera (didn't even try to fix them, mic wont work with AppleALC)
- Bluetooth

As far as used the laptop I can tell it's a very good hackbook. It's fast and is working very stable with the last fixes.
I am still working on this EFI so I will update it as soon as I have any progress on it.
