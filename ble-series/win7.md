## BLE蓝牙4.0驱动安装\(针对win7\)

因为win7发布早于蓝牙4.0，且微软一直未更新win7支持蓝牙4.0，所以要使用蓝牙4.0的键盘，必须使用第三方驱动。

大部分人使用的蓝牙4.0适配器应该是CSR8510这个芯片的，淘宝上从10几块到4、50块的价格都有，没太大的区别。

第三方驱动使用千月，淘宝上单机的注册码17.9元。也可以直接买本身有授权的蓝牙适配器。不想花钱的，或者想试一试再花钱的，网上找的一个，可以试试（试后可用也还是建议购买注册，使用会更方便）：

链接: https://pan.baidu.com/s/19rlxeXdvXUlV9MJ5hrQbpw密码: 18vz

首先是安装千月。安装的时候插着蓝牙适配器或者安装完成后都成。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image002.jpg)![](/assets/qy01.jpg)

这个手机助手可以不装

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image004.jpg)![](/assets/qy02.jpg)

安装完成后要求重启。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image006.jpg)![](/assets/qy03.jpg)

从托盘菜单里看到蓝牙图标，要启动的是那个蓝牙4.0低功耗管理。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image008.jpg)![](/assets/qy07.jpg)

然后在其他—HID里，添加设备，并且连接。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image010.jpg)![](/assets/qy08.jpg)

连上后可能不能用。查看设备管理器，这里可能是个问号。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image012.jpg)![](/assets/qy09.jpg)

即使不是问号，如果不能使用，一样右键点击它，选择更新驱动。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image014.jpg)![](/assets/qy10.jpg)

选择“浏览器计算机以查找驱动程序软件”，再选择“从计算机的设备驱动程序列表中选择”。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image016.jpg)![](/assets/qy11.jpg)

然后取消掉下图中的勾，选择列表里红框项。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image018.jpg)![](/assets/qy12.jpg)

会有如下提示，无视就行了。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image020.jpg)![](/assets/qy13.jpg)

直接点击是，然后会安装新的驱动，安装后会提醒需要重启，但其实这时已经可以使用了。当然最好还是再重启一下。

![](file:///C:\Users\drk\AppData\Local\Temp\msohtmlclip1\01\clip_image022.jpg)![](/assets/qy14.jpg)

我测试时因为电脑非常慢，重启后在登录界面，键盘是不可用的，但有其他用户表示登录界面是可以使用的。

进入系统待千月启动好了后，键盘会自动连接上，直接可用无问题。

