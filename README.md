# OpenWRT-R619AC

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/Aibx/OpenWRT-R619AC/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/Aibx/OpenWRT-R619AC.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/Aibx/OpenWRT-R619AC.svg?style=flat-square&label=Forks&logo=github)

## 竞斗云Openwrt自动编译

[![GitHub Action (latest by date)](https://img.shields.io/github/workflow/status/Aibx/OpenWRT-R619AC/Build%20OpenWrt?style=for-the-badge&logo=appveyor&label=Build%20Status)](https://github.com/Aibx/OpenWRT-R619AC/actions)
[![GitHub Release (latest by date)](https://img.shields.io/github/v/release/Aibx/OpenWRT-R619AC?style=for-the-badge&label=Download)](https://github.com/Aibx/OpenWRT-R619AC/releases/latest)
- 本项目为竞斗云固件自动编译脚本，每日0:30 UTC(北京时间8:30)和12:30 UTC(北京时间20:30)自动编译，预计3小时完成编译工作
- 内含精选Vssr、SSRPlus、Passwall、京东签到、Clash、Adguard、去广告、迅雷快鸟等绝大多数常用插件，包含仓库内基本全部的主题，每日跟随仓库软件编译
- 如果最新版本不含bin等文件即编译失败，请前往[Releases](https://github.com/Aibx/OpenWRT-R619AC/releases)或[Actions](https://github.com/Aibx/OpenWRT-R619AC/actions)寻找旧版
- Releases仅保留最新14份编译内容,Actions则保留30天内全部的编译内容,Cowtransfer及WeTransfer下载链接有效时长为7天

> 如需IPK文件请前往[Actions](https://github.com/Aibx/OpenWRT-R619AC/actions)内下载文件名含"OpenWrt_bin_p2w_r619ac-128m"的文件

## 更新记录

### V1.0
- 去除argon重复主题，保障编译成功

### V1.1
- 因netgearv2主题手机页面存在错误，退回netgearV1主题

### V1.2
- 修复上游软件包变更导致的编译错误问题,自动删除无用Action

### V1.3
- 修复上游编译环境导致的错误，去除VSSR-PLUS，改为VSSR

## 联动仓库
- [OpenWRT-Packages](https://github.com/Aibx/OpenWRT-Packages)：国内常用OpenWRT软件包集合
- [Lean's OpenWrt](https://github.com/Aibx/Lean-OpenWrt)：Lean的OpenWRT源码仓库，每日自动合并上流推送
- [Lienol's OpenWrt](https://github.com/Aibx/Lienol-OpenWrt)：Lienol的OpenWRT源码仓库，每日自动合并上流推送

