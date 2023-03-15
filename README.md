
华南金牌B75黑苹果配置（目前以OC引导为主，Clover的引导不再维护）
---

* 主板：华南金牌B75（2019.10.29的BIOS版本）

* CPU：E3 1220 V2

* 内存：金士顿DDR3 1333 2G x 2

* 显卡：迪兰HD7770 酷能+ 1G DC V2（引导参数添加radpg=15，配合WhateverGreen.kext免驱）

* 硬盘：威刚SP580 120G SSD

* MacOS：10.15.7（S1睡眠正常，CPU变频正常）

注意：

1.此主板硬件不支持S3的睡眠模式，目前仅支持S1睡眠模式，S1睡眠正常（仅仅显示器黑屏）。

2.对于有线网卡RTL8111，使用高版本的驱动大概率会有偶发性断流问题，请使用低版本V2.2.1即可：https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/RealtekRTL8111

致谢：Clover和OC引导等内容均搜集于网络，对所有贡献者一并表示感谢！

---

API：https://api.github.com/repos/ic005k/HUANAN-B75/releases/latest

