# fcitx-rime-flypy

![License-MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Docs-Passing](https://img.shields.io/badge/Docs-Passing-green.svg)

小鹤音形 rime 的挂接文件。

虽然小鹤音形官方提供了适用于 Linux 的 rime 挂接文件，
但是挂接文件并没有遵守 Linux 约定俗成的配置风格
(可见官方论坛中的 [这个讨论](https://flypy.com/bbs/forum.php?mod=viewthread&tid=400&extra=page%3D1))，故产生了这个 Repo。

## 调整/特性

+ 调整默认使用 flypyplus 方案
+ 调整 flypy 方案和 flypyplus 方案默认使用英文
+ 调整 flypy 方案默认使用繁体

+ 遵守 Linux 约定俗成的配置风格
+ 统一配置文件中注释与空行的风格 (不能逼死强迫症)

## 如何使用

依次执行下面的命令即可。

+ ``git clone --depth=1 https://github.com/Cool-Pan/fcitx-rime-flypy``
+ ``cd fcitx-rime-flypy``
+ ``bash Restore.sh``

## 许可证

除 rime 文件夹中的内容外，都受 [MIT](LICENSE) 许可证保护。
