# EFI-OpenCore-A456URK
OpenCore 0.6.0 EFI Bootloader for Asus A456URK

### System Properties
- CPU : Intel i5-7200U Kabylake
- Display Card : Intel HD 620 + Nvidia 930MX
- Resolution : 1366 x 768
- RAM : 8GB (4+4) 2133MHz
- Sound : Conexant CX 8050
- Storage : SSD 512 GB + HDD 1TB (both are SATA)
- Ethernet : Realtek RTL 8168
- WiFi + BT : Atheros A9565
- Touchpad : ELAN 1200
- Hackintosh : 10.15.6 Supplementary Update

### Reminder
- __DO AT YOUR OWN RISK__
- Inside config.plist, there is `PlatformInfo > Generic`. I was labeled the `MLB`, `SystemSerialNumber` and `SystemUUID` as __InsertYourOwn__. Please to __insert your own__
- Everything is work except the Nvidia Graphics Card, because Nvidia Optimus is no longer supported since Mojave
- Battery indicator is not hotpached
- In case you update the system (example: 10.15.1 to 10.15.2), please disable the kext that related to __IO80211Family.kext__ and __ATH9KFixup.kext__ first

### Thanks to
[Dortania Tutorial](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#starting-point)
