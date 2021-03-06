# HP EliteBook Folio 1040 G3 Hackintosh EFI

![SS](/screenshot.png)

## Device Specs
- Intel i5-6300U @ 2.40GHz
- Intel HD Graphics 520
- 8GB DDR4 (Memory soldered down)
- Toshiba XG5 256GB NVMe SSD (works also without NVMeFix.kext)
- ALPS I2C HID Touchpad (ALP000D:00 044E:120C)
- 1920x1080@60Hz 14" Display
- HD Audio Codec Conexant CX20724
- Intel Wireless-AC 8265
- Snapdragon X5 LTE Modem

## Things that works
- Keyboard
- Touchpad /w gestures
- Intel WiFi
- Intel Bluetooth
- Battery status
- Speakers
- Graphics
- USB2/3 Ports
- USB-C Port
- Integrated camera
- Microphone
- Sleep
- Mute button
- NO RTC error when booting

## Not tested
- HDMI Port
- Headphone jack
- LTE Modem
- HP 2013 UltraSlim Dockingstation
- HP USB-C/A Universal Dock G2 /w HP USB-C Universal Dock with 4.5 mm and USB Dock Adapter (2UF95AA)
- Smartcard reader

## Not working
- Fingerprint sensor
- WiFi button

## BIOS v1.52 Settings
###### Security
**TPM Embedded Security**
- TPM State -> Unchecked

###### Advanced
**Boot Options**
- Fast Boot -> Unchecked
- CD-ROM Boot -> Unchecked

**Secure Boot Configuration**
- Configure Legacy Support and Secure Boot -> Legacy Support Disable and Secure Boot Disable

**Built-In Device Options**
- Wake On LAN -> Disabled
- Video memory size -> 128 MB

**Power Management Options**
- Wake on USB -> Unckecked