# Hackintosh-DellVostro5590-EFI
## EFI for Dell Vostro 5490/5590

Tested on Dell Vostro 5590. It's recommended to update BIOS to the latest versions. I will update this repository regularly with new fixes and updated versions of OpenCore and kexts.

<details>
<summary>Update log</summary>
<br>
  - 13 Apr 2020 - fixed power management and trackpad
<br>
  - 22 May 2020 - updated kexts and OpenCore to version 0.5.8, fixed some minor issues
<br>
  - 10 Jun 2020 - fixed the no audio issue, updated kexts and OpenCore to version 0.5.9, changed SMBIOS to MacBookPro15,4
</details>

macOS Version: Catalina 10.15.5

### Laptop specs
Dell Vostro 5590
```sh
CPU - i5 10210U
GPU - UHD 620
RAM - 12GB
WiFi - Intel WiFi 9462
Audio Codec - Realtek ALC 3204/236
Storage - 250GB SK Hynix SSD NVMe
HID Touchpad device
Standart PS2 keyboard
Goodix fingerprint sensor
```

### Important BIOS settings
```sh
My current BIOS version is 1.6.0
I recommend you to restore the default BIOS settings before proceeding
UEFI Boot Path Security - Never
Integrated NIC - Enabled
SATA Operation - AHCI
USB Configuration - Enable USB Boot Support must be checked
Disable EcoPower (Optional)
Absolute - Disable Absolute
TPM 2.0 Security On - OFF
Intel SGX - Disabled
Enable Secure Boot - OFF
Secure Boot Mode - Deployed Mode
Intel Virtualization Technology - ON
VT for Direct I/O - OFF
```

### Working
```sh
- Booting/Shutdown/Restart
- Speed Step
- Native power management
- Graphics acceleration 
- Audio
- Audio fn keys (f1, f2, f3)
- All USB-A ports (mapped)
- LAN
- Battery reporting
- Keyboard
- Touchpad
- Brightness regulation
- Sleep/Wake/Instant On
- NVRAM
```

### Not working (to be fixed)
```sh
- WiFi (to be replaced with DW1560 or DW1820A)
- Bluetooth
- Mic
- Camera
- HDMI
- Fn keys for brightness
- Fingerprint sensor (Goodix fingerprint sensor are not supported by macOS)
```
To fix trackpad click working only on pressing, go to preferences -> trackpad -> point and click -> enable tap to click and silent click.

Keep in mind that you will need to fix some things such as iServices manually.

### Benchmarks (Geekbench)

CPU:
https://browser.geekbench.com/v5/cpu/2474871

Metal:
https://browser.geekbench.com/v5/compute/1047157

OpenCL:
https://browser.geekbench.com/v5/compute/1047149
