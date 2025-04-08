# Stream-Server
[![English](https://img.shields.io/badge/English-English-orange.svg)](README.md)
[![Spanish](https://img.shields.io/badge/Spanish-Español-orange.svg)](lang/README.es.md)
[![Chinese](https://img.shields.io/badge/Chinese-中文-orange.svg)](lang/README.zh-CN.md)
[![French](https://img.shields.io/badge/French-Français-orange.svg)](lang/README.fr.md)
[![German](https://img.shields.io/badge/German-Deutsch-orange.svg)](lang/README.de.md)
[![Portuguese](https://img.shields.io/badge/Portuguese-Português-orange.svg)](lang/README.pt.md)
[![Japanese](https://img.shields.io/badge/Japanese-日本語-orange.svg)](lang/README.ja.md)
[![Russian](https://img.shields.io/badge/Russian-Русский-orange.svg)](lang/README.ru.md)
[![Korean](https://img.shields.io/badge/Korean-한국어-orange.svg)](lang/README.ko.md)
[![Arabic](https://img.shields.io/badge/Arabic-العربية-orange.svg)](lang/README.ar.md)

> [!WARNING]
> These translations were generated using AI and may contain errors.  
> Feel free to submit corrections via pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)

> [!TIP]
> Skip to my Cheap and Easy Setup by selecting OS above.

---
## What is a Stream-Server
In IRL Streaming you often come in situations where you want to take a short break, for example, to go to the toilet or hide sensitive information. 
You can *End the Livestream* but it will lose you viewers and create a new VOD every time you do it.
The same happens every time you lose all your phone signal or run out of battery.

> [!NOTE]  
> **Everything that happens on the phone affects directly your stream**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

To avoid this, many streamers use a so-called Stream-Server.

They act as a middleman between your phone and the streaming service *(e.g. Twitch, Kick, YouTube)* and can therefore detect any outages of the phone-stream and instead show some funny clips to keep the viewers informed and entertained.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---


# 3 Versions
Which version you choose depends typically on:

**💵 How much money you want to spend**  
**VS**  
**🛠️⌛ How much work and time you want to invest**

---
## Variant A - Hosted Setup
The simplest version is to rent a Stream-Server that combines all [Components](#components) and often offers different levels of support.

- **Known Providers**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Variant B - Mixed Setup
If you have a decent PC and good internet at home, you can move some [Components](#components) to your home PC to "save" monthly costs.
> [!WARNING]
> This requires some technical knowledge and will take multiple hours of setup. Some Support is done by yourself.

- **Known Providers**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), and [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)  
- **Guides**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Variant C - Full Home Setup
You can move all [Components](#components) to your home PC, which cost you now extra Money.
> [!CAUTION]
> This needs **advanced technical knowledge** and all Support/Maintenance is done by yourself.  
> There could be Security Risks, if configured wrong.
- **Network**:  
Public IP, dynDNS, Port-Forwarding, or Firewall settings.
- **Server**:  
Installing & maintaining Docker containers, including changing local settings.
- **Docker-Containers**:  
[All-in-One Container by Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) or [bbox-receiver by Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Components
- **SRTLA Receiver/Endpoints**: Receives multiple SRTLA connections and combines them into an SRT stream.
- **SLS**: Offers the SRT stream by request with a stream ID and includes a status page with connection information (e.g., bitrate).
- **NOALBS**: Switches OBS scenes based on the SLS status page or chat commands and posts info in the connected chat.
- **OBS**: Streaming software on a PC or server that allows conversion between SRT and RTMP and adds a huge amount of customization options.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Wanna help me out?](https://ko-fi.com/naginreed)
