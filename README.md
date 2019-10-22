# fcitx-rime-flypy

![License-MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Docs-Passing](https://img.shields.io/badge/Docs-Passing-green.svg)

小鹤音形的 fcitx-rime 挂接文件。

虽然小鹤音形官方提供了适用于 Linux 的 rime 挂接文件，
但是挂接文件并没有遵守 Linux 约定俗成的配置风格
(可见官方论坛中的 [这个讨论](https://flypy.com/bbs/forum.php?mod=viewthread&tid=400&extra=page%3D1))，
故产生了这个 Repo。

## 调整/特性

+ 调整默认方案为 flypyplus
+ 调整 flypy 和 flypyplus 方案默认使用繁体
+ 调整 flypy 和 flypyplus 方案只能使用中文
+ 改回 Rime 默认的 punctuator

+ 遵守 Linux 约定俗成的配置风格
+ 统一配置文件中注释与空行的风格 (不能逼死强迫症)

## 如何使用

依次执行下面的命令即可。

+ ``git clone --depth=1 https://github.com/Cool-Pan/fcitx-rime-flypy``
+ ``cd fcitx-rime-flypy``
+ ``bash Restore.sh``

**注意：**

可能仅适用于 fcitx-rime。
