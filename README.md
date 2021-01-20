# SDB16

这里有SDB16键盘的 说明书，固件下载，讨论，技术支持。

If you prefer English, please read [README_EN.md](https://github.com/wangyiwei2015/SDB16/blob/main/README_EN.md).

<br>

## 固件烧录指南

**1** 前往[Releases](https://github.com/wangyiwei2015/SDB16/releases)下载相应的固件（名称见包装盒）；

**2** 下载并打开[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/latest)，检查MCU为*ATmega32u4*，载入下载的固件HEX；

**3** 连接SDB16键盘，轻按RST按钮，等待QMK Toolbox识别到DFU模式的设备；

**4** 点击*Clear EEPROM*初始化键盘；

**5** 点击*Flash*完成烧录；

**6** 重新连接键盘，即可使用。

  

## 常见问题

如果按键相应不符合预期，请检查以下内容：

- 键帽安装位置，应与包装盒上一致
- 烧录的固件应与包装盒提示的一致
- 烧录前使用Clear初始化
- 烧录过程中软件内无报错

如果无法连接设备，请检查以下内容：

- 安装了USB驱动程序
- 使用带数据传输功能的USB-C线缆
- 线缆与接口完好

关于USB驱动：ATmega32u4/Arduino Leonardo兼容（Windows中安装Arduino IDE可自动解决驱动问题，因为Arduino Leonardo与本产品使用相同的MCU，含USB功能）。

  

## 提交问题/反馈Bugs

请转到[issues](https://github.com/wangyiwei2015/SDB16/issues)页面提交和讨论您的问题。

  

## 更多帮助

如需技术支持或其他帮助，欢迎发邮件联系我们：

CEO/销售：[NextB](mailto://)

设计/工艺：[casteil](mailto://)

硬件/功能：[wyw](mailto://wangyw.dev@outlook.com)

