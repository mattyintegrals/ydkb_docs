## Atmel DFU Bootloader

这是AVR一些单片机默认带的Bootloader，也是挺多键盘直接使用的。

使用此Bootloader刷固件是必须安装驱动的，使用zadig，这里为了防止安装错设备，可以使用修改版的Zadig for Atmel DFU，下载址址：[https://pan.baidu.com/s/1sltOsrV](https://pan.baidu.com/s/1sltOsrV) 密码: ek5h



**1.按下刷机按键之后 ，一定要按，从下面列表里，找到 ATm32U4DFU 。\(这一句非常重要，一定要是按了刷机键之后，找到 ATm32U4DFU 再给它安装驱动，因为很重要所以再说一遍。\)**

![](/assets/Atmel_DFU_01.png)

**再次提示一次是按下刷机按键之后，如上图这样的选择，不要选择其他显示的任何东西给装个 winusb 的驱动。不要去选 GH60 或者其他的键盘名，如果选择了还了此驱动，该键盘就不能用了，需要卸载驱动或者换个 USB 接口插。**

![](/assets/Atmel_DFU_02.png)

**正确的选择 ATm32U4DFU 后，点击 Install Driver，安装成功会有提示。**

![](/assets/Atmel_DFU_03.png)

**像上图这样，Driver 处显示为 WinUSB 了，表示安装成功。如果安装不成功，请从来，或者尝试以管理员身份运行 zadig\_2.1.2.exe。**



#### 有的精简系统上可能不支持WinUSB的驱动，那么也可以选择安装LibUSB的驱动，YDKB提供的刷机工具是同时支持libusb和winusb驱动的。

#### 如果有使用多个键盘的，有使用tkg刷机的，建议安装WinUSB驱动，因为tkg的刷固件工具使用的是WinUSB。如果有使用qmk的键盘，那就建议安装LibUSB驱动，qmk的刷固件工具使用的是LibUSB。



