# fcitx|ibus-rime-flypy

![build](https://img.shields.io/badge/build-passing-brightgreen)
![docs](https://img.shields.io/badge/docs-100%25-green)

fcitx|ibus-rime 的小鹤音形挂接文件。

虽然小鹤音形官方提供了适用于 Linux 的 Rime 挂接文件，
但是挂接文件并没有遵守 Linux 约定俗成的配置风格
(可见官方论坛中的 [这个讨论](https://flypy.com/bbs/forum.php?mod=viewthread&tid=400&extra=page%3D1))，
故产生了这个倉庫。

## 调整/特性

+ 调整默认方案为 flypyplus
+ 改回 Rime 默认的 Punctuator
+ 改回 Rime 默认的 Key Binder
+ 配置文件结构遵守 Linux 约定俗成的配置风格
+ 统一配置文件中注释与空行的风格 (不能逼死强迫症)

## 如何使用

按照下面的步驟操作即可。

+ 安裝 fcitx-rime / ibus-rime
+ 在 fcitx / ibus 中添加 RIME (中州韻) 輸入法
+ 結束所有 fcitx / ibus 進程
+ ``git clone --depth=1 https://github.com/Cool-Pan/fcitx-rime-flypy``
+ ``cd fcitx-rime-flypy``
+ 複製配置文件到對應目錄
    + fcitx-rime
        + 可使用自動部署腳本，運行 ``bash Deploy.sh`` 命令即可
        + 複製 rime 文件夾下所有的文件到 ``$HOME/.config/fcitx/rime/`` 目錄下
    + ibus-rime
        + 複製 rime 文件夾下所有的文件到 ``$HOME/.config/ibus/rime/`` 目錄下
+  重新運行 fcitx / ibus 程序
