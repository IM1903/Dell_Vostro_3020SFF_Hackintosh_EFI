# Vostro 3020 Small Form Factor-Hackintosh-EFI


| Parts    | Name                                                 |
| -------- | ---------------------------------------------------- |
| CPU      | Intel Core i5-12/13400（ UHD730 iGPU not working ） |
| Mobo     | Dell 8VX12 ( OEM, Intel B660 chipset, LGA1700 )      |
| RAM      | DDR4 16Gx2 ( Hynix HMA82GU6DJR8N-XN )               |
| Drive    | UNIC UNSPC1T0ALNM                                   |
| GPU      | AMD Radeon RX560 768SP 2GB D5 with 4 mini-DP         |
| Ethernet | Realtek RTL8168H                                    |
| Wi-Fi    | Intel AX210 160MHz                                   |
| Version  | 14.4 Sonoma                                          |

## What's working

1. Booting
2. hardware acceleration (requires supported GPUs)
3. Ethernet (requires RealtekRTL8111.kext)
4. Wi-Fi (replace the stock realtek WiFi card with a boardcom or Intel card, then AirportItlwm will work)
5. Bluetooth (Intel only, as only IntelBluetoothFirmware.kext and IntelBTPatcher.kext are installed)

## What doesn't work

1. iServices ( generate your own usable S/N)
2. Apple Pay ( contact [tcook@apple.com](mailto://tcook@apple.com) if you can get it to work)
3. hibernation ( can't wake up 9/10 )

Translated with DeepL.com (free version)

## Screenshot

![1734775042595](images/README/1734775042595.png)
