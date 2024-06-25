# Gigabyte B760i AORUS PRO Hackintosh OpenCore EFI

![image](ScreenShot/GigabyteB760iAORUSPRO.jpg)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 1.0.0](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### Hardware

- BIOS Version: F10d  2024-06-06
- Motherboard: Gigabyte B760i AORUS PRO
- CPU: Intel 12th i5-12600KF
- GPU: AMD Radeon RX6950 XT 16GB GDDR6
- Memo: Gloway International 32GB(16GB*2) DDR5-7000 Mhz
- SSD:  aigo P3000Pro  1TB   MacOS Sonoma + Windows 11
- HDA: Realtek ALC897
- LAN: Intel L225-V
- WiFI: Killer(R) Wi-Fi 6E AX211 160MHz

### BIOS

```

Settings
  |-- IO Ports
      |-- Above 4G Decoding: Enabled
      |-- Above 4G MMIO BIOS assignment: Disabled
      |-- Re-Size BAR Support: Disabled
      |-- IOAPIC 24-119 Entries: Disabled
      |-- USB Configuration
          |-- XHCI Hand-off: Enabled 
          |-- Port 60/64 Emulation: Disabled
      |-- SATA Configuration
          |-- SATA Controllers): Enabled 
  |-- Miscellaneous 
      |-- VT-D: Enabled    
Boot 
  |-- CFG Lock: Disabled
  |-- Fast Boot: Disable Link
  |-- CSM Support: Disabled
  |-- Secure Boot
      |-- Secure Boot: Disabled
```

### Notes

 - Use  [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) build your SMBIOS
 - If you want to use a CPU without  Efficient-Core, you must uncheck the option in the config.plist file Kernel--ProvideCurrentCpuinfo
 - Use the Power button to wake up from sleep
 - Intel AX211 WiFi driver [AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases) in this EFI is only applicable to MacOS 14.5 Sonoma. Please download and replace this driver yourself when installing other MacOS versions
 - Intel AX211 Not Supported  Airdrop

### Contact Us 

- QQ Group: 23304408

![image](ScreenShot/QRCode.png)