# 欢迎使用ydkb

===

## Documentation for ydkb.io

\[TOC\]

## BLE双模快速使用指南

这里介绍如何使用BLE双模

### 驱动安装\(针对win7\)

win7并不支持蓝牙4.0，需要使用第三方驱动，这里以千月为例，千月支持大部分淘宝上卖的廉价csr8510的蓝牙4.0适配器。

### 蓝牙配对

在键盘蓝牙未连接任何的设备，且未关闭蓝牙可发现时，蓝牙就处于可搜索并连接状态。电脑或其他设备搜到键盘蓝牙后，点击它，即可配对连接上。  
ios和mac如果在自带的蓝牙管理里面出现搜不到键盘，请去App Store下载Adafruit Bluefruit LE Connect，使用它搜索并连接键盘。  
如果出现配对或连接异常，包括但不限于无法配对，配对后重新开关电源会连接不上等，可使用键盘的清除已配对（左右Shift+R或自行设置）功能，之后再重新配对。

### 多设备切换

蓝牙与USB切换，可以自己设置一个按键，或者使用左右Shift+U。如果配对了多个蓝牙设备，在不同蓝牙设备之间的主动切换目前不支持，所以要切换从A切换到B，假设当前连接着A，需要关闭A的蓝牙，打开B的蓝牙。

