## BootHID Bootloader

目前来说，YDKB的挺多键盘使用的是这个Bootloader，免驱（使用的是系统自带的HIDUSB驱动）。

基本就是按照键盘对应的说明，按指定按键的同时插入USB线，就进入刷固件模式了。



这里说一下如果无法刷的时候，可能的问题。最新的刷固件软件里面已经加入了检测驱动的功能，如果提示驱动错误，按下吧操作:

1.使用zadig（下载地址：http://zadig.akeo.ie），选择好option里面的list all，然后让键盘进入刷机模式。查看如下USB ID为16C0 05DF的设置，对应的Driver是不是HidUsb。这个设置可能显示的是名字HIDBoot，也可能只是USB输入设备。总之看对应的USB ID是下图这个才行。

![](/assets/boothid_driver_01.png)![](/assets/boothid_driver_02.png)

上面两个图都是驱动正常的，如果这里显示的不是HidUSB，比如可能是：

![](/assets/boothid_driver_04.png)

这个驱动是错的，就必须要卸载了。



2.设备管理器里找到设备，非hid的，一般就显示在通用串行总线或者libusb设备等地方。找到，右键点击，选择卸载设备。

![](/assets/boothid_driver_05.png)

同时卸载时选中删除设备驱动

![](/assets/boothid_driver_06.png)

卸载后再去zadig里面查看一下，驱动是否恢复为HidUsb了，如果不是，设备管理器里面刷新一下，继续卸载（比如winusb或libusb驱动安装过多次的情况，就需要多次卸载了，直到卸载干净）。



### 补充说明：

如果还有遇到特殊情况，比如怎么卸载驱动都回不到HidUSB，那就直接联系我远程处理吧。



