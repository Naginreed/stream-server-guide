# 流媒体服务器
[![English](https://img.shields.io/badge/English-English-orange.svg)](README.md)
[![Spanish](https://img.shields.io/badge/Spanish-Español-orange.svg)](lang/README.es.md)
[![Chinese](https://img.shields.io/badge/Chinese-中文-orange.svg)](lang/README.zh-CN.md)
[![French](https://img.shields.io/badge/French-Français-orange.svg)](lang/README.fr.md)
[![German](https://img.shields.io/badge/German-Deutsch-orange.svg)](lang/README.de.md)
[![Portuguese](https://img.shields.io/badge/Portuguese-Português-orange.svg)](lang/README.pt-BR.md)
[![Japanese](https://img.shields.io/badge/Japanese-日本語-orange.svg)](lang/README.ja.md)
[![Russian](https://img.shields.io/badge/Russian-Русский-orange.svg)](lang/README.ru.md)
[![Korean](https://img.shields.io/badge/Korean-한국어-orange.svg)](lang/README.ko.md)
[![Arabic](https://img.shields.io/badge/Arabic-العربية-orange.svg)](lang/README.ar.md)

> [!WARNING]
> 这些翻译是由 AI 生成的，可能包含错误。
> 欢迎通过 Pull Request 提交更正。

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)

> [!TIP]
> 选择上方的操作系统，跳转到我的简易低成本设置。

---
## 什么是流媒体服务器？

在 IRL 直播中，你经常会遇到需要短暂休息的情况，例如上厕所或隐藏敏感信息。
你可以 *结束直播*，但这会导致观众流失，并且每次都会创建一个新的 VOD。
当你的手机信号完全丢失或电池耗尽时，也会发生同样的情况。

> [!NOTE]
> **手机上的一切都会直接影响你的直播**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

为了避免这些问题，许多主播使用流媒体服务器。

它们充当手机和流媒体服务（如 Twitch、Kick、YouTube）之间的中介，能够检测到手机直播的中断，并播放有趣的片段，让观众保持参与和娱乐。

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3 种版本
你选择的版本通常取决于：

**💵 你愿意花多少钱**  
**VS**  
**🛠️⏳ 你愿意投入多少时间和精力**

---
## 方案 A - 托管服务器
最简单的方法是租用一个包含所有[组件](#components)的流媒体服务器，通常还提供不同级别的支持。

- **已知服务商**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## 方案 B - 混合设置
如果你家里有一台不错的 PC 并且网络稳定，你可以将一些[组件](#components)转移到你的本地 PC，从而“节省”每月的费用。

> [!WARNING]
> 这需要一定的技术知识，并且需要花费多个小时进行设置。一些支持工作需要自己完成。

- **已知服务商**  
[Belabox Cloud](https://cloud.belabox.net/)、[IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35)、[IRLServer](https://irlserver.com/)、[AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## 方案 C - 全本地设置
你可以将所有[组件](#components)转移到你的本地 PC，而无需额外成本。

> [!CAUTION]
> 这需要 **高级技术知识**，所有支持和维护工作都需要自行完成。  
> 如果配置错误，可能会存在安全风险。

- **网络：**  
公网 IP、动态 DNS、端口转发或防火墙设置。
- **服务器：**  
安装和维护 Docker 容器，包括调整本地设置。
- **Docker 容器：**  
[Glowf1sh 的 All-in-One 容器](https://hub.docker.com/r/glowf1sh/srtla-receiver) 或 [Datagutt 的 bbox-receiver](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## 组件介绍

- **SRTLA 接收器/端点：** 接收多个 SRTLA 连接并将其合并为 SRT 流。
- **SLS：** 通过流 ID 请求 SRT 流，并显示连接信息（如比特率）的状态页面。
- **NOALBS：** 根据 SLS 状态页面或聊天命令切换 OBS 场景，并在已连接的聊天中发布信息。
- **OBS：** 运行在 PC 或服务器上的流媒体软件，允许 SRT 和 RTMP 之间的转换，并提供大量自定义选项。

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [想支持我？](https://ko-fi.com/naginreed)

