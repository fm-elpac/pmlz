# 计划 fmls

fmls-ui (flatpak):
easily connect local devices across many platforms,
include different shape (PC, laptop, handset, tablet, server, router, SBC, TV box, MCU),
different OS (GNU/Linux, Android, OpenWrt, Windows),
different CPU (x86, arm, RISC-V), etc.

胖蚊轻蜘蛛


## 主要 git 仓库

+ fmls: 文档, 核心代码 (包括 CLI)

+ fmls-ui: 图形界面 (vue), 桌面应用 (GNU/Linux, Windows)

+ fmls-apk: Android 应用


## 发布版本

+ flatpak (fmls-ui): 适用于 GNU/Linux 图形桌面 (electronjs)
  (x86_64, aarch64)

+ AUR (fmls): 适用于 ArchLinux (无图形界面) (x86_64)

+ 容器镜像 (fmls): 适用于 GNU/Linux (无图形界面) (x86_64, aarch64)

+ 独立二进制 (fmls): 适用于 GNU/Linux (rv64gc)

+ OpenWrt 软件包 (fmls): 适用于 OpenWrt (x86_64, aarch64)

+ tauri (fmls-ui): 适用于 Windows (x86_64)

+ fmls-apk: 适用于 Android (aarch64)


## avahi-dbus

Avahi D-Bus API binding in pure Rust.

TODO
