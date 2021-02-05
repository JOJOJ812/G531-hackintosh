![image](https://github.com/JOJOJ812/G531-hackintosh/blob/master/Picture/macOS_Big_Sur_.jpg)
## 概述

疑问解答加入我的QQ群：678047104

本文是为了让玩家国度系列笔记本电脑尽量完美的使用上 MacOS。


## 适用系统

MacOS Big Sur 11.x  
MacOS Catalina 10.15.x  
MacOS Mojave 10.14.x  
MacOS High Sierra 10.13.6 (17G2112)

## 适用型号
  * G531（魔霸1——4）
  * GU502（幻系列）
  * 枪神系列（1——4）
  * 冰刃系列（1——4）

## 发布

发布OC版本为064（不完整）需自行构建完整的OC文件，GitHub仅提供acpi与config配置文件（请前往：https://github.com/JOJOJ812/G531-hackintosh）

## 需要准备
- 下载好的 MacOS 镜像（支持 macOS High Sierra (10.13.6) - macOS Big Sur 的镜像安装）
- 16GB U盘

## BIOS设置
- 启用UEFI启动。
- 禁用安全启动。
- SATA模式设置为AHCI。

## 正常工作的功能
- UEFI通过 Clover/OC 启动
- 支持任意版本系统OTA升级到最新系统
- 原生USB3.0/USB2.0 
- AppleHDA原生音频，包括耳机
- 原生电源管理
- 电池状态
- 背光控制
- 背光键盘
- 核显驱动（独显已经 hotpatch 屏蔽）
- 有线以太网卡
- Mac App Store正常运行
- CPU变频
- 睡眠唤醒（鼠标，键盘、电源键唤醒均正常）
- 无线网络（你可以使用intel网卡，驱动来自https://github.com/OpenIntelWireless/itlwm/releases）
- 蓝牙（你可以使用intel蓝牙，驱动来自https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases）
- 触控板 （全系支持全手势）
- 随航（有线/无线）

## 不能正常使用的功能
- HDMI ，因为HDMI 端口连接到已禁用的Nvidia卡


## 关于捐赠

如果您认可我的工作，可以通过捐赠支持我后续的更新

| 微信                                                       | 支付宝                                               |
| ---------------------------------------------------------- | ---------------------------------------------------- |
|![image](https://github.com/JOJOJ812/G531-hackintosh/blob/master/Picture/wechatpay.png)|![image](https://github.com/JOJOJ812/G531-hackintosh/blob/master/Picture/ailpay.png)
