# <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a> 使用指南

[![English](https://img.shields.io/badge/English-English-orange.svg)](README.md)
[![Spanish](https://img.shields.io/badge/Spanish-Español-orange.svg)](README.es.md)
[![Chinese](https://img.shields.io/badge/Chinese-中文-orange.svg)](README.zh-CN.md) 
[![French](https://img.shields.io/badge/French-Français-orange.svg)](README.fr.md) 
[![German](https://img.shields.io/badge/German-Deutsch-orange.svg)](README.de.md) 
[![Portuguese](https://img.shields.io/badge/Portuguese-Português-orange.svg)](README.pt.md) 
[![Japanese](https://img.shields.io/badge/Japanese-日本語-orange.svg)](README.ja.md) 
[![Russian](https://img.shields.io/badge/Russian-Русский-orange.svg)](README.ru.md) 
[![Korean](https://img.shields.io/badge/Korean-한국어-orange.svg)](README.ko.md) 
[![Arabic](https://img.shields.io/badge/Arabic-العربية-orange.svg)](README.ar.md) 

> [!WARNING]  
> 以下翻译由AI生成，可能存在错误。  
> 欢迎通过Pull Request提交修正。

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.zh-CN.md) 
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.zh-CN.md) 
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.zh-CN.md) 

> [!TIP]  
> 如果选错操作系统，请使用上方按钮切换。

> [!IMPORTANT]  
> <details>  
> <summary>点击右上角三横线图标可跳转到指南任意章节</summary>  
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">  
> </details>  

---  
# 基础信息  
本指南描述了一套**经济实惠且简单**的解决方案，适用于：  
- 提升**户外直播**质量  
- 使用**安卓手机**作为直播设备  
- 使用**Windows家用电脑**作为推流终端  

---  
## 方案概览 <a id="overview" />  

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">  

> [!NOTE]  
> 初看可能复杂，但我们将通过图文逐步完成整个配置流程。  

**优势**  
- 👍 仅需手机单网络即可使用  
- 👍 手机网络中断时观众仍能观看视频/片段（1次直播+1次回放）  
- 👍 可添加第二网络提升手机连接稳定性（可选）  
- 👍 WiFi与移动数据切换时直播不会中断  

**劣势**  
- 👎 需额外支付中继服务器月费（10美元）  
- 👎 第二网络会产生额外月费（可选）  
- 👎 首次配置耗时较长  

---  
# 1 - 直播手机配置  

> [!NOTE]  
> 若有多部手机，请选用性能最强/最新款作为直播机  

1.a - 从Google Play商店安装 **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">  

---  
# 2 - SRT/SRTLA中继服务器  

> [!NOTE]  
> 该服务器将两路SRTLA流合并为单路SRT流（参见[方案概览](#overview)）  

> [!IMPORTANT]  
> 此项服务需支付10美元/月  

2.a - 注册[Github](https://github.com/signup)账号（已有账号请直接登录）  
 - 需验证邮箱并通过[登录](https://github.com/login)  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">  

2.b - 登录后访问[Belabox赞助](https://github.com/sponsors/rationalsa)页面  
 - 选择**10美元/月**套餐（含1个SRT/SRTLA中继服务器）  
 - 填写账单信息并设置支付方式（仅支持信用卡/PayPal）  
 - 也可让观众购买[代金券](https://shop.belabox.net/product/belabox-cloud-voucher)  

2.c - 完成赞助或持有代金券后访问[Belabox云平台](https://cloud.belabox.net)  
 - 使用Github账号登录授权  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">  

2.d - 点击顶部**三横线菜单** → **SRT(LA) relays**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">  

2.e - 点击**Add**修改名称，并将**Server**设为最近地理位置  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">  

2.f - 滚动至**Moblin Settings**部分，点击**Add automatically to Moblin**自动配置  

---  
# 3 - 直播手机设置  
3.a - 打开**IRL Pro应用** → 点击左上角**齿轮图标**（设置）  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">  

3.b - 进入**Connections** → 点击**Belabox Cloud**下的**New connection**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">  

3.c - 选择**TWITCH.TV** → 填写用户名和[直播密钥](https://dashboard.twitch.tv/settings/stream) → 保存  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">  

3.d - 返回菜单 → 点击**Streamer**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">  

3.e - 填写Twitch用户名 → 下拉输入[Streamlabs API密钥](https://streamlabs.com/dashboard#/settings/api-settings)（后续修改聊天设置需返回此处）  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">  

3.f - 返回菜单 → 点击**Video**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">  

3.g - 视频参数设置：  
 - **分辨率:** 1920x1080p  
 - **帧率:** 30固定  
 - **比特率匹配分辨率:** 关闭  
 - **比特率:** 4500 kbps  
 - **格式:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">  

3.h - 返回菜单 → **Overlays** → **Web Overlays**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">  

3.i - 添加直播提醒：通过浏览器访问[Streamlabs控制台](https://streamlabs.com/dashboard#/alertbox)复制组件URL  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">  

3.j - 返回IRL Pro添加**New web overlay**：  
 - **名称:** 提醒  
 - **URL:** 粘贴Streamlabs链接  
 - **宽度:** 600  
 - **高度:** 400  
（后续可调整尺寸/位置）  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">  

3.k - 保存后确保提醒功能已开启  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">  

3.l - 返回**主界面**检查**聊天加载**状态，并通过[Alertbox](https://streamlabs.com/dashboard#/alertbox)测试提醒功能  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">  

---  
# 4 - Windows电脑配置  
推荐使用有线连接家庭路由器的普通PC/笔记本，如需专用设备可考虑迷你主机。  
> [!WARNING]  
> 该设备需全程保持**稳定**网络连接，上传带宽≥6Mbps（[测速](https://www.nperf.com)）

## 4.1 OBS
> [!NOTE]  
> 该程序从Relay服务器获取直播流，将其转换回传统的RTMP/h.264标准，并直接推流至Twitch。您可以在此设置视频、文字、音乐等多种内容，以便在重新连接时*为观众提供娱乐。

4.1.a - 为您的系统下载 [OBS Studio](https://obsproject.com/download)  
4.1.b - 安装OBS Studio并启动它。  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - 在自动向导中  
 - 选择“优化为直播”  
 - **分辨率:** 1920x1080  
 - **帧率:** 30  
 - **服务:** Twitch  
 - 连接账户  
 - 在新弹出的窗口中登录  
 - 取消勾选**估算比特率**，手动输入**5900**（*若为Twitch合作伙伴则输入7900*）  
 - 完成向导  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">  

4.1.d - **在OBS中**，于左下角**添加**以下**场景**  
 - 开始  
 - 直播  
 - 低画质  
 - 稍后回来  
 - 结束  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">  

4.1.e - 点击“直播”场景，添加一个**媒体源**，命名为**Belabox Cloud**。  
 - 将弹出一个设置窗口  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">  

4.1.f - 打开 **[Belabox Cloud](https://cloud.belabox.net/#relays)** 页面  
 - 进入**SRT(LA) relays**  
 - 向下滚动至**OBS媒体源设置**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">  

4.1.g - **返回OBS**，**设置相同参数**  
 - 取消勾选“本地文件”  
 - 将网络缓冲设置为1 MB  
 - 从Belabox Cloud页面复制输入  
 - 设置重连延迟为2秒  
 - 勾选“非活动时关闭文件”  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">  

4.1.h - 右键点击**Belabox Cloud**源，选择**变换** > **适应屏幕**（*或选中后按Ctrl+F*）  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">  

4.1.i - 复制（Ctrl+C）**Belabox Cloud**源到**低画质**场景  
4.1.j - 进入右下角**设置** > **音频**，**禁用所有全局音频设备**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">  

4.1.k - 顶部菜单栏点击**工具** > **WebSocket服务器设置**，勾选**启用WebSocket服务器**并点击**确定**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">  

---  
## 4.2 NOALBS  
> [!NOTE]  
> 该程序通过聊天命令控制OBS，并在检测到手机直播流丢失时自动切换场景  

4.2.a - 为您的系统下载 [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)，解压至任意位置（*建议创建“Stream”文件夹并在其中新建“NOALBS”子文件夹*）  
4.2.b - 解压后文件夹应包含以下3个文件：  
 - .env  
 - config.json  
 - noalbs  

4.2.c - 为了让NOALBS响应聊天命令，需授权Twitch账号访问权限。登录Twitch后点击此[链接](https://b3ck.com/twitch/oauth)，选择**Authorize with Twitch**，复制页面生成的完整代码  

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">  
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">  

4.2.d - **用文本编辑器打开.env文件**  
 - 用复制的代码替换全部内容  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">  

 - 保存并关闭文件  

4.2.f - 下载此处的[config.json](../config.json)替换本地文件  
 - **用文本编辑器打开config.json**  
 - 将所有3处*REPLACE_STREAMER_NAME*替换为您的Twitch账号名  

4.2.g - 打开[Belabox Cloud](https://cloud.belabox.net/#relays)页面，进入**SRT(LA) relays**  
 - 滚动至**NOALBSv2配置**  
 - 将*REPLACE_BELLABOX_URL*替换为Belabox页面提供的URL  
 - 将*REPLACE_BELLABOX_INGEST_KEY*替换为URL的最后部分  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">  

4.2.h - 返回OBS的WebSocket设置，点击**显示连接信息**  
 - 复制**服务器密码**  
 - 将*REPLACE_OBS_WEBSOCKET_PASSWORD*替换为复制的密码  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">  

4.2.i - 保存并关闭config.json文件。*详细说明见[NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - 启动**noalbs**程序，界面应如下图所示。错误信息也会在此显示  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">  

4.2.k - 可右键点击noalbs文件选择**创建快捷方式**，将快捷方式拖至桌面便于访问  

---  
# 5 - 美化OBS  
基础设置已完成，但当前场景较为空泛。  
以下说明各场景用途及常见设计建议：  
> [!NOTE]  
> 以下仅为建议，可自由发挥创意。  

**开始**  
- 每次直播启动时显示，直至手机开播  
- 常用视频+音乐作为背景  
- 简单文字如“即将开始...”  

**直播**  
- 手机成功连接OBS后显示  
- 无需额外内容（叠加层应在手机端设置）  

**低画质**  
- 手机连接质量不佳时触发  
- 简单文字提示“低比特率”  

**稍后回来**  
- 手机连接完全中断或主动关闭IRLPro直播时（*隐私保护*）  
- 常用往期录像或精彩片段（推荐使用[VLC媒体播放器](https://www.videolan.org/vlc/)创建“Clips”文件夹并添加VLC媒体源）  
- 简单文字如“稍后回来”  
- 如厕或短暂私聊时可手动切换至此场景  

**结束**  
- 在Twitch聊天输入!end命令触发  
- 类似开始场景的视频+音乐  
- 简单文字“直播结束”  

---  
# 6 - 常规操作流程  
> [!NOTE]  
> **每次**户外直播前需完成以下步骤  

6.a - **启动家中PC**，确保网络畅通且不会自动休眠  
6.b - 在PC上**启动OBS和NOALBS**  
6.c - **前往户外**计划开播地点  
6.d - 在**Twitch聊天输入!start**开始推流  
6.e - **在IRL Pro中点击开播** → 数秒后切换至**直播场景**  
6.f - 若手机停止推流或断连 → 数秒后切换至**稍后回来场景**  
6.g - 手机网络恢复后 → 数秒后自动切回**直播场景**  
6.h - 在IRLPro中手动开始/结束直播以切换`!brb`和`!live`状态  
6.i - **结束直播**可通过连麦他人或聊天命令`!stop`实现  

> [!IMPORTANT]  
> OBS每次场景切换都会在聊天窗口显示提示  

---  
# 7 - 备用网络连接  
> [!NOTE]  
> 此为可选方案，可显著提升直播稳定性（但无法解决无信号区域如深山/隧道的中断问题）  

如[概览](#overview)所示，可为手机配置备用网络以降低直播中断风险：  
- 移动WiFi路由器  
- 另一部开启热点的手机  

> [!IMPORTANT]  
> 强烈建议备用SIM卡使用不同运营商  
> 备用网络将消耗约50%的总流量  

---  
# 8 - 直连Twitch推流  

若中继服务器或家中PC故障，可快速切换回IRL Pro直推模式：  

8.a - 进入**设置** > **连接**，关闭**Belabox**并开启**Twitch**  
<details>  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600">  
</details>  

8.b - 返回**设置** > **视频**，开启**比特率匹配分辨率**，**格式**设为自动  
<details>  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">  
</details>  

---  
# 9 - 更多帮助  
### IRL应用  
加入其[Discord](https://discord.gg/irlpro)  
### OBS  
查阅[官方论坛](https://obsproject.com/forum/)或观看海量YouTube教程  
### NOALBS  
参阅[Github指南](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)及其[Discord](https://discord.gg/efWu5HWM2u)  

---  
## Ko-Fi支持  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [想支持我吗？](https://ko-fi.com/naginreed)
