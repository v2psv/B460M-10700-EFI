# B460M-10700-EFI

![image](https://github.com/v2psv/B460M-10700-EFI/blob/master/images/info.png)

## Hardware:
- CPU: 10700
- Motherboard: MSI B460M Mortar
- Graphics Card: UHD 630 (iGPU)
- Monitor: LG 4K 60hz
- Memory: DDR4 3200MHZ, 16GB x 2
- SSD: WD Black SN750

## OpenCore Version
- 0.6.1 
(https://github.com/acidanthera/OpenCorePkg)

## OS Version
- Catalina 10.15.7

## What Works
- DP and HDMI. (Works fine on my 4K 60hz monitor with DP port)
- Audio
- USB
- Sleep & Wake up
- Ethernet. You should change speed to 1000baseT in Network -> Ethernet -> Advanced -> Hardware.
- icloud, iMessage, photos, etc.

## What Broken
- no wifi or bluetooth

## Others
- "Show Picker" is set to **False** in Misc->Boot.
- "-v" in "boot-args" is removed.



## Kexts
- [Lilu](https://github.com/acidanthera/Lilu)
- [VirtualSMC](https://github.com/acidanthera/virtualsmc/releases)
- [AppleALC](https://github.com/acidanthera/AppleALC)
- [WhateverGreen](https://github.com/acidanthera/whatevergreen/releases)
- [LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet)
