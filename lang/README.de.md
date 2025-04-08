# Stream-Server
[![English](https://img.shields.io/badge/English-English-orange.svg)](../README.md)
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
> Diese Übersetzungen wurden mit KI generiert und können Fehler enthalten.  
> Gerne können Korrekturen per Pull-Request eingereicht werden.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.de.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.de.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.de.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.de.md)

> [!TIP]
> Springe direkt zu meiner einfachen und günstigen Einrichtung, indem du oben dein Betriebssystem auswählst.

---
## Was ist ein Streaming-Server?

Beim IRL-Streaming gibt es oft Situationen, in denen du eine kurze Pause einlegen möchtest, zum Beispiel um auf die Toilette zu gehen oder sensible Informationen auszublenden.
Du kannst den *Livestream beenden*, aber dadurch verlierst du Zuschauer und erzeugst jedes Mal ein neues VOD.
Das gleiche passiert, wenn dein Telefonsignal vollständig ausfällt oder dein Akku leer ist.

> [!NOTE]
> **Alles, was auf dem Telefon passiert, wirkt sich direkt auf deinen Stream aus.**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

Um dies zu vermeiden, nutzen viele Streamer einen sogenannten Streaming-Server.

Dieser fungiert als Vermittler zwischen deinem Telefon und dem Streaming-Dienst *(z. B. Twitch, Kick, YouTube)* und kann Ausfälle des Telefonstreams erkennen. Stattdessen können dann lustige Clips gezeigt werden, um die Zuschauer informiert und unterhalten zu halten.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3 Versionen
Welche Version du wählst, hängt in der Regel davon ab:

**💵 Wie viel Geld du ausgeben möchtest**  
**VS**  
**🛠️⏳ Wie viel Arbeit und Zeit du investieren möchtest**

---
## Variante A - Gehostete Einrichtung
Die einfachste Version ist das Mieten eines Streaming-Servers, der alle [Komponenten](#komponenten) kombiniert und oft verschiedene Support-Level anbietet.

- **Bekannte Anbieter**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Variante B - Hybride Einrichtung
Wenn du einen leistungsfähigen PC und stabiles Internet zu Hause hast, kannst du einige [Komponenten](#komponenten) auf deinen Heim-PC verschieben, um monatliche Kosten zu sparen.

> [!WARNING]
> Dies erfordert technisches Wissen und mehrere Stunden Einrichtung. Ein Teil des Supports muss selbst übernommen werden.

- **Bekannte Anbieter**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)
- **Anleitung**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.de.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.de.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.de.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.de.md)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Variante C - Vollständige Einrichtung zu Hause
Du kannst alle [Komponenten](#komponenten) auf deinen Heim-PC verschieben, ohne zusätzliche Kosten.

> [!CAUTION]
> Dies erfordert **fortgeschrittene technische Kenntnisse** und die gesamte Wartung/Unterstützung muss selbst durchgeführt werden.  
> Es könnten Sicherheitsrisiken bestehen, wenn die Konfiguration falsch ist.

- **Netzwerk:**  
Öffentliche IP, dynDNS, Portweiterleitung oder Firewall-Einstellungen.
- **Server:**  
Installation und Wartung von Docker-Containern, einschließlich lokaler Anpassungen.
- **Docker-Container:**  
[All-in-One-Container von Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) oder [bbox-receiver von Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Komponenten

- **SRTLA Receiver/Endpoints:** Empfängt mehrere SRTLA-Verbindungen und kombiniert sie zu einem SRT-Stream.
- **SLS:** Bietet den SRT-Stream auf Anfrage mit einer Stream-ID an und zeigt eine Statusseite mit Verbindungsinformationen (z. B. Bitrate).
- **NOALBS:** Wechselt OBS-Szenen basierend auf der SLS-Statusseite oder Chat-Befehlen und postet Informationen in den verbundenen Chat.
- **OBS:** Streaming-Software auf einem PC oder Server, die die Konvertierung zwischen SRT und RTMP ermöglicht und viele Anpassungsmöglichkeiten bietet.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Möchtest du mich unterstützen?](https://ko-fi.com/naginreed)
