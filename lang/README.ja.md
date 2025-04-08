# ストリームサーバー (Stream-Server)
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
> これらの翻訳はAIによって生成されており、誤りが含まれる可能性があります。  
> 修正があれば、プルリクエスト（Pull Request）で送信してください。

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ja.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ja.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ja.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ja.md)

> [!TIP]
> 上記のOSを選択して、簡単でお得なセットアップ方法に進んでください。

---
## ストリーミングサーバーとは？

IRL配信では、トイレに行く、機密情報を隠すなど、短い休憩を取りたい場面がよくあります。
*ライブ配信を終了*することもできますが、それでは視聴者を失い、新しいVODが作成されてしまいます。
同じことが、電話の電波が完全に途切れた場合やバッテリーが切れた場合にも起こります。

> [!NOTE]
> **携帯電話で発生するすべてのことが、直接ストリームに影響します**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

これを防ぐため、多くの配信者はストリーミングサーバーを使用します。

ストリーミングサーバーは、携帯電話とストリーミングサービス（Twitch、Kick、YouTube など）の間の仲介役として機能し、電話のストリームが途切れた際に視聴者を退屈させないよう、面白いクリップを再生することができます。

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3つのバージョン
通常、以下の基準でバージョンを選択します：

**💵 どれくらい費用をかけられるか**  
**VS**  
**🛠️⏳ どれくらいの作業と時間を投資できるか**

---
## バージョンA - ホスティング型設定
最も簡単な方法は、すべての[コンポーネント](#コンポーネント)を組み合わせたストリーミングサーバーをレンタルすることです。

- **既知のプロバイダー**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## バージョンB - ハイブリッド設定
自宅に高性能なPCと安定したインターネット環境がある場合は、一部の[コンポーネント](#コンポーネント)をPCに移して、毎月のコストを削減できます。

> [!WARNING]
> これは技術的な知識が必要で、セットアップには数時間かかります。一部のサポート作業は自分で行う必要があります。

- **既知のプロバイダー**  
[Belabox Cloud](https://cloud.belabox.net/)、[IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35)、[IRLServer](https://irlserver.com/)、[AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)

- **ガイド**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ja.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ja.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ja.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ja.md)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## バージョンC - フルローカル設定
すべての[コンポーネント](#コンポーネント)を自宅のPCに移動し、追加コストなしで運用できます。

> [!CAUTION]
> これは **高度な技術知識** が必要で、すべてのサポートとメンテナンスは自己対応になります。
> 設定を誤ると、セキュリティリスクが生じる可能性があります。
<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## コンポーネント

- **SRTLA レシーバー/エンドポイント:** 複数のSRTLA接続を受信し、それらをSRTストリームに統合。
- **SLS:** ストリームIDを指定してSRTストリームを提供し、接続情報（ビットレートなど）を表示するステータスページを提供。
- **NOALBS:** SLSのステータスページやチャットコマンドに基づいてOBSシーンを切り替え、情報をチャットに投稿。
- **OBS:** PCやサーバー上で動作するストリーミングソフトウェアで、SRTとRTMPの変換を可能にし、多くのカスタマイズオプションを提供。

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [サポートしていただけますか？](https://ko-fi.com/naginreed)

