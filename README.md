# HP-Pavilion-au146tx-efi

[![macOS](https://img.shields.io/badge/macOS-11.6.0-orange)](https://developer.apple.com/documentation/macos-release-notes) [![OpenCore](https://img.shields.io/badge/OpenCore-0.7.6-blue)](https://github.com/acidanthera/OpenCorePkg) 

## 介绍
完美支持bigsur   已经更新到当前最新oc和kext版本   电池电量完美显示，之后无特殊情况不会继续维护

## 基本配置

| 名称     | 型号                    |
| -------- | ----------------------- |
| Model    | 15-au146TX              |
| cpu      | i5 7200U  2.5ghz        |
| 内存     | 海力士8g ddr4 2400MHz   |
| 显卡     | NVIDIA Geforce 940MX    |
| 主板     | 惠普8216 （9D58芯片组） |
| 无线网卡 | 瑞昱RTL810x/8139        |
| 声卡     | 瑞昱声卡                |
| 显示器   | 奇美CMN15C6  15.5寸     |
| 硬盘     | 台电s500 120g ssd       |



## 系统驱动

| 名称                    | 版本                                                         | 描述         |
| ----------------------- | ------------------------------------------------------------ | ------------ |
| AppleALC                | ![](https://img.shields.io/badge/version-1.6.6-informational) | 声卡         |
| Lilu                    | ![](https://img.shields.io/badge/version-1.5.8-informational) | 核心         |
| VoodooPS2Controller     | ![](https://img.shields.io/badge/version-2.2.7-informational) | 触摸板和键盘 |
| WhateverGreen           | ![](https://img.shields.io/badge/version-1.5.5-informational) | 显卡         |
| VirtualSMC              | ![](https://img.shields.io/badge/version-1.2.8-informational) | 核心         |
| SMCProcessor            | ![](https://img.shields.io/badge/version-1.2.8-informational) | 处理器温度   |
| SMCBatteryManager       | ![](https://img.shields.io/badge/version-1.2.8-informational) | 电池驱动     |
| SMCLightSensor.kext     | ![](https://img.shields.io/badge/version-1.2.8-informational) |              |
| USBPorts                |                                                              | usb定制      |
| CPUFriend               | ![](https://img.shields.io/badge/version-1.2.4-informational) |              |
| CPUFriendDataProvider   | ![](https://img.shields.io/badge/version-1.0.0-informational) |              |
| IntelBluetoothInjector  | ![](https://img.shields.io/badge/version-1.1.2-informational) |              |
| IntelBluetoothFirmware  | ![](https://img.shields.io/badge/version-1.1.2-informational) |              |
| IntelMausi              | ![](https://img.shields.io/badge/version-1.0.7-informational) |              |
| XHCI-unsupported        | ![](https://img.shields.io/badge/version-0.9.2-informational) |              |
| USBMap.kext             | ![](https://img.shields.io/badge/version-1.0-informational)  |              |
| CtlnaAHCIPort.kext      | ![](https://img.shields.io/badge/version-341.0.2-informational) |              |
| AirportItlwm.kext       | ![](https://img.shields.io/badge/version-1-informational)    |              |
| itlwm.kext              | ![](https://img.shields.io/badge/version-1.1.0-informational) |              |
| VoodooI2C.kext          | ![](https://img.shields.io/badge/version-2.6.5-informational) |              |
| VoodooI2CSynaptics.kext | ![](https://img.shields.io/badge/version-1-informational)    |              |

## 功能完善度

- [x] 睡眠唤醒
- [x] usb定制
- [x] 电池电量显示（显示充电图标，显示电量百分比）
- [x] 内置喇叭外放
- [x] Wifi 无线连接，蓝牙
- [x] airdrop，接力
- [x] 亮度调节（f1，f2  自行设置快捷键）
- [x] 开盖唤醒
- [x] 盒盖睡眠

  

## 参考链接

https://github.com/At-Rule/Stable-Hackintoh-HP-Pavillion-au620x-i5-7200U-Gtx940MX

https://github.com/kumarayush2104/OC-Hackintosh

