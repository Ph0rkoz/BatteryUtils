# BatteryUtils Command Line Version

Thinkpad battery charge threshold utils

Exposes ACPI interface for battery controls.

1. Turn off the monitor
2. start charge threshold
3. stop charge threshold
4. Set from command line

This comes courtesy or reddit user /u/vali20

You no longer have to install buggy Lenovo spyware that doesn't even work in the end. It may need the power management driver but that's it.

Run from a  task at windows startup: batteryutils.exe [stop charge] [start charge]
e.g. batteryutils.exe 80 20

On my thinkpad it holds until you remove the battery.

Thanks to all developers: Anyone else, feel free to contribute. Here's to the hope we won't all have to look through years old posts for basic functionality.






N4 version, win10 does not install.Net 3.5 framework can be used directly

N4 版本，win10 不安装.net 3.5 framework可直接使用

This project is licensed under the GPLv3. See COPYING for details.
Copyright 2016-2017 XYUU

目前只支持Thinkpad笔记本设置电池充电阈值，将来可能会支持其他品牌笔记本，等待有兴趣的朋友一起完善。

开发思路见我的[知乎专栏](https://zhuanlan.zhihu.com/p/20706403)
