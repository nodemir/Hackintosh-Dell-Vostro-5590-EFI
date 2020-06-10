# Hackintosh-DellVostro5590-EFI
##EFI for Dell Vostro 5490/5590

Tested on Dell Vostro 5590. It's recommended to update BIOS to the latest versions. I will update this repository regularly with new fixes and updated versions of OpenCore and kexts.

<details>
<summary>##Update log</summary>
<br>
  - 13 Apr 2020 - fixed power management and trackpad
  - 22 May 2020 - updated kexts and OpenCore to version 0.5.8, fixed some minor issues
  - 10 Jun 2020 - fixed the no audio issue, updated kexts and OpenCore to version 0.5.9, changed SMBIOS to MacBookPro15,4
</details>

macOS Version: Catalina 10.15.5

###Laptop specs
Dell Vostro 5590
```sh
i5 10210U
UHD 620
12GB RAM
Intel WiFi 9462
Realtek ALC 3204/236
250GB SK Hynix SSD
HID Touchpad device
Standart PS2 keyboard
```

###BIOS settings
My current BIOS version is 1.6.0
| ###Boot Options |
| ------ |
| UEFI Boot Path Security | Never |
| ###System Configuration |
| ------ |
| Integrated NIC | Enabled |
| SATA Operation | AHCI |
| USB Configuration | Enable USB Boot Support should be checked |
| ###Video |
| ------ |
| Disable EcoPower (Optional) |
| ###Security |
| ------ |
| Absolute | Disable Absolute |
| TPM 2.0 Security On | OFF |
| Intel SGX | Disabled |
| ###Secure Boot |
| ------ |
| Enable Secure Boot | OFF |
| Secure Boot Mode | Deployed Mode |
| ###Wireless |
| ------ |
| Disable WLAN and Bluetooth if you still haven't replaced the card to save some battery life |
| Virtualization |
| ------ |
| Intel Virtualization Technology | ON |
| VT for Direct I/O | OFF |



###Working
```sh
Booting/Shutdown/Restart
Speed Step
Native power management
Graphics acceleration 
Audio
Audio fn keys (f1, f2, f3)
All USB-A ports (mapped)
LAN
Battery reporting
Keyboard
Touchpad
Brightness regulation
Sleep/Wake/Instant On
NVRAM
```

###Not working (to be fixed)
```sh
WiFi (to be replaced with DW1560 or DW1820A)
Bluetooth
Mic
Camera
HDMI
Fn keys for brightness
Fingerprint sensor (Goodix fingerprint sensor are not supported by macOS)
```
