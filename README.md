# OpenCore Hackintosh guide for Dell Inspiron 15 5537

### EFI Bootloader files to boot macOS Catalina using OpenCore on Dell Inspiron 5537

## Working OS

Till macOS Big Sur Beta 3 (any previous OS such as Catalina will boot as well)

## What Works


- Audio (Plug, Internal both)
- Microphone
- Graphics (Intel HD 4400)
- HDMI
- Battery
- Touchpad
- USB 
- Ethernet
- Keyboard
- Brightness
- Camera

## Whats broken

- WiFi and Bluetooth (Will work with proper replacement of card)


## Installation

### PS: Its recommended to use external USB mouse during installation, with plugged in charger, 8GB+ USB drive is needed to make bootable usb, and if you are making dual boot, make sure your EFI partition is larger than 400mb+, 500~700mb is recommended 

### Set BIOS settings 
Press `F2` to load BIOS settings. Change the following settings:

- Disk: AHCI
- UEFI Boot: Enabled
- Secure Boot: Disabled

1. Make bootable usb from Olarila from [here](https://www.olarila.com/topic/5794-hackintosh-guide-install-macos-with-olarila-image-step-by-step-install-and-post-install-windows-or-mac)

2. Follow the instructions, use config2.plist for booting

3. Then after following intructions, instead of taking OpenCore folder from Olarila, use mine, you wont need to install OpenCore seperately 

4. Reboot 

6. Reboot, everything should be as fine as it should be

## Some FAQ

### Q. Audio codec name?
A. Realtek ALC3223

### Q. AMD Graphics works?
A. No



### Guide by ©thedeadfish59, cherrypicked resources from various sites 
