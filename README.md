# SDB16

这里有SDB16键盘的 说明书，固件下载，讨论，技术支持。

If you prefer English, please read [README_EN.md](https://github.com/wangyiwei2015/SDB16/blob/main/README_EN.md).

<br>

## 最新版本 • 2021-01-27

[更新] Firmware/iPad@0.5.1

[无变化] Firmware/Windows@0.5.0

<br>

## 固件烧录指南

**1** 前往[Releases](https://github.com/wangyiwei2015/SDB16/releases)下载相应的固件（名称见包装盒）；

**2** 下载并打开[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases/latest)，检查MCU为*ATmega32u4*，载入下载的固件HEX；

**3** 连接SDB16键盘，轻按RST按钮，等待QMK Toolbox识别到DFU模式的设备；

**4** 点击*Clear EEPROM*初始化键盘；

**5** 点击*Flash*完成烧录；

**6** 重新连接键盘，即可使用。

<br>

## 常见问题

如果按键响应不符合预期，请检查以下内容：

- 键帽安装位置，应与包装盒上一致
- 烧录的固件应与包装盒提示的一致
- 烧录前使用Clear初始化
- 烧录过程中软件内无报错

如果无法连接设备，请检查以下内容：

- 安装了USB驱动程序
- 使用带数据传输功能的USB-C线缆
- 线缆与接口完好

关于USB驱动：ATmega32u4/Arduino Leonardo兼容

两种安装方式任选：

- 安装QMK Toolbox，根据弹出提示，或手动点击安装驱动
- 安装Arduino IDE，过程中会自动解决驱动问题

<br>

## 提交问题/反馈Bugs

请转到[issues](https://github.com/wangyiwei2015/SDB16/issues)页面提交和讨论您的问题。

<br>

## 更多帮助

如需技术支持或其他帮助，欢迎发邮件联系我们：

(如果不涉及个人信息/隐私，我们还是建议使用 [issues](https://github.com/wangyiwei2015/SDB16/issues))。

CEO/销售：[NextB](mailto://nextbm@163.com)

设计/工艺：[casteil](mailto://1741768232@qq.com)

硬件/功能：[wyw](mailto://wangyw.dev@outlook.com)

