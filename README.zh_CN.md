# 技嘉 B760i AORUS PRO 黑苹果 OpenCore EFI

![image](ScreenShot/GigabyteB760iAORUSPRO.jpg)

### [English](https://github.com/hackintosh-club/Gigabyte-B760i-AORUS-PRO-OpenCore)

### OpenCore

[OpenCore 1.0.0](https://github.com/acidanthera/OpenCorePkg)

### 可安装系统

- macOS Monterey 12.x 
- macOS Ventura  13.x 
- macOS Sonoma  14.x 


### 硬件

- BIOS版本: F10d  2024-06-06
- 主  板: Gigabyte B760i AORUS PRO
- 处理器: 英特尔 12代 i5-12600KF
- 独   显: AMD Radeon RX 6950 XT 16GB GDDR6
- 内   存: 光威天策 32GB(16GB*2) DDR5-7000 Mhz
- 固   态: 爱国者 P3000Pro  1TB MacOS Sonoma + Windows 11
- 声   卡: 瑞昱 ALC897
- 有   线: 英特尔 L225-V
- 无   线: 杀手 Killer(R) Wi-Fi 6E AX211 160MHz

### BIOS设置

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



### 注意事项

 - 安装完成后请使用 [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools/releases) 生成自己的三码
 - 如需使用没有小核心的CPU，必须取消勾选配置文件中Kernel--ProvideCurrentCpuinfo选项
 - 请使用电源键进行睡眠唤醒
 - 此EFI中的英特尔无线网卡驱动[AirportItlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases)仅适用于 MacOS 14.5 Sonoma,安装其它版本请自行下载替换此驱动
 - 英特尔无线网卡无法使用隔空投送等功能

### 参考内容

[1.黑苹果安装过程演示](https://hackintosh.club/d/10000060)

[2.英特尔无线网卡WiFi驱动](https://hackintosh.club/d/10000015)

[3.英特尔无线网卡蓝牙驱动](https://hackintosh.club/d/10000017)

[4.我的B站黑苹果教程](https://space.bilibili.com/244390800/video)

[6.黑果之家](https://hackintosh.club)



### 联系我们

- QQ群: 23304408

![image](ScreenShot/QRCode.png)