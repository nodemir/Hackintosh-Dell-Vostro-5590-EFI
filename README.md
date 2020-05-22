# Hackintosh-DellVostro5590-EFI
EFI for Dell Vostro 5490/5590

WARNING: Tested only on Dell Vostro 5590! For other models you may need to change some things (for example gpu device-id and ig-platform or SMBIOS). It's recommended to update bios to the latest version. There are still a few things to fix as the sound is the biggest issue for now.

Update log:
- 22.05.2020 - updated kexts and OpenCore to the latest version 0.5.8, fixed some issues


macOS Version: Catalina 10.15.4
It wont work on any older macOS version since 10.15.4 is the first to support intel's 10th generation processors.

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
- WiFi (to be replaced with DW1560 or DW1820A)
- Sound (tried many things, even created a custom layout id and still not working)
- Mic and camera (still haven't tried anything to fix it)
- Bluetooth
- HDMI (still haven't tried anything to fix it)

As far as used the laptop I can tell it's a very good hackbook. It's fast and is working very stable with the last fixes.
I am still working on this EFI so I will update it as soon as I have any progress on it.
