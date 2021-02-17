## 该EFI适用于：macOS Big Sur Version 11.2.1


OC引导

#### 一、机型配置信息

| 硬件          | 型号                            |
| ------------- | ------------------------------- |
| CPU           | ryzen 2600x                     |
| 主板          | MSI b450m                       |
| 内存          | 阿斯加特登灯条8GBx2（默频2400） |
| 显卡          | RX580 8GB 2306sp                |
| 无线网卡+蓝牙 | Broadcom BCM94360CD             |



#### 二、功能测试

| 项目      | 成果                                          |
| --------- | --------------------------------------------- |
| 版本      | Mac OS Big Sur 11.2.1                         |
| 声音      | 3.5mm接口OK，蓝牙耳机OK，HDMI音频输出无法找到 |
| 麦克风    | OK                                          |
| WIFI      | OK                                            |
| 蓝牙      | OK                                            |
| 睡眠/唤醒 | OK                                            |
|           |                                               |



#### 三、问题记录

- 声卡：频繁拉动右上角音量条会导致声卡驱动崩溃，重启后正常。无法输出到HDMI音频设备（无法找到HDMI音频设备）
- 蓝牙：WIFI连接2.4Ghz网络时，蓝牙受干扰严重（声音断断续续），WIFI连接5.0Ghz时蓝牙表现正常



#### 四、安装建议

- 安装`Broadcom BCM94360CD`，可正常使用WIFI和蓝牙



