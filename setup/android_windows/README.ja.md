# <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a> ガイド

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
> これらの翻訳はAIによって生成されており、誤りが含まれる可能性があります。  
> 修正のプルリクエストを自由に提出してください。

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> 誤ったOSを選択した場合は、上記のボタンを使用してください。

> [!IMPORTANT]  
> <details>
> <summary>右上の3本線を使用してガイドの任意のセクションにジャンプできます</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# 一般情報
このガイドでは、以下のための**安価で簡単な**ソリューションを説明します：
- より良い**IRL**ストリーミング
- **Android**をストリーミング用スマートフォンとして使用
- **Windows**をホームPCとして使用

---
## 概要 <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> 最初は複雑に見えますが、画像付きでステップバイステップでセットアッププロセスを進めます。

**利点**  

- 👍 スマートフォンからの単一のインターネット接続で使用可能
- 👍 スマートフォンの接続が失敗しても、視聴者はビデオ/クリップを視聴可能（1回のストリーム開始と1回のVOD）
- 👍 2つ目のインターネット接続を追加してスマートフォン接続の信頼性を向上可能
- 👍 WiFiとモバイルデータの切り替え時にストリームがオフラインにならない

**欠点**  

- 👎 リレーサーバーの追加月額費用（10 USD）
- 👎 2つ目のインターネット接続の追加月額費用（オプション）
- 👎 初回セットアップに時間がかかる

---
# 1 - ストリーミング用スマートフォン  

> [!NOTE]   
> 複数のスマートフォンがある場合は、最も強力/最新のものをストリーミング用に使用してください。

1.a - Google Playストアから**[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)**をインストール

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - SRT/SRTLAリレー

> [!NOTE]   
> このサーバーは2つのSRTLAストリームを受け取り、[概要](#overview)で示されたように1つのSRTストリームに結合します。

> [!IMPORTANT]   
> このサービスは月額10 USDかかります。

2.a - [Github](https://github.com/signup)でアカウントを作成（既にアカウントがある場合はログインへ）
 - メールアドレスを確認し、[ログイン](https://github.com/login)してください。

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - ログイン後、[Belabox Sponsorship](https://github.com/sponsors/rationalsa)ページを開く  
 - 下にスクロールし、1x SRT/SRTLAリレーサーバーを含む**月額10 USD**のティアを選択
 - 請求情報を入力し、支払い情報を設定（クレジットカードまたはPaypalのみ対応）
 - または、視聴者に複数月分の[バウチャー](https://shop.belabox.net/product/belabox-cloud-voucher)を購入してもらうことも可能。

2.c - スポンサーまたはバウチャーを取得したら、[Belabox Cloud](https://cloud.belabox.net)ページを開き、
 - Githubアカウントでログイン/認証  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - ページ上部の**3本線**を押し、**SRT(LA) relays**を選択

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - **Add**をクリックし、名前を変更。**Server**を**最寄りの場所**に変更

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - **Moblin Settings**までスクロールし、**Add automatically to Moblin**ボタンをタップしてMoblinに正しい情報を自動追加。  

---
# 3 - ストリーミング用スマートフォン
3.a - **IRL Proアプリ**を開き、左上の**歯車アイコン**（設定）をタップ  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - **Connections**に移動し、**Belabox Cloud**が表示されるはずです。**New connection**をタップ。  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - 上部の**TWITCH.TV**をタップし、ユーザー名と[Streamkey](https://dashboard.twitch.tv/settings/stream)を入力して保存  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - メニューに戻り、**Streamer**をタップ

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - **Twitch Username**をタップし、ユーザー名を追加してOK。[Streamlabs API Key](https://streamlabs.com/dashboard#/settings/api-settings)を入力（チャット設定を変更する必要がある場合はここに戻ります）。

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - メニューに戻り、**Video**をタップ

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - **Video**で以下の設定を適用  
 - **解像度:** 1920x1080p  
 - **FPS:** 30固定  
 - **Bitrate matches resolution:** オフ  
 - **ビットレート:** 4500 kbps  
 - **フォーマット:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - メニューに戻り、**Overlays**、次に**Web Overlays**をタップ  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - IRL Proにアラートを追加します。ブラウザでアラートダッシュボードに移動  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox)でウィジェットURLをコピー

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - IRL Proに戻り、**New web overlay**を追加  
 - **名前:** Alerts  
 - **URL:** Streamlabs AlertboxからコピーしたURLを貼り付け  
 - **幅:** 600  
 - **高さ:** 400  
（アラートのサイズや位置が合わない場合は後で変更可能）  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - 保存後、Alertsがオンになっていることを確認。

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - **メインビュー**に戻り、**チャット**が読み込まれていることと**アラート**が**動作している**ことを確認  
 - Streamlabs（テストアラートは[Alertbox](https://streamlabs.com/dashboard#/alertbox)で利用可能）  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - Windows-PC
通常のPCまたはラップトップを使用可能。ホームインターネットルーターに直接接続するのが最適。
 このタスク専用に新しいものを購入する場合は、ミニPCを検討してください。
> [!WARNING]  
> このPCはストリーム中ずっと**安定した**インターネット接続（少なくとも6Mbitのアップロード）が必要 *[Speedtest](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> このプログラムは、リレーサーバーからストリームを受信し、古いRTMP/h.264規格に変換してTwitchに直接配信します。再接続中に視聴者を楽しませるための動画、テキスト、音楽など多くのオプションを設定できます*

4.1.a - お使いのシステムに合わせて **[OBS Studio](https://obsproject.com/download)** をダウンロード  
4.1.b - **OBS Studioをインストール**し、**起動**します。  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - 自動設定ウィザードで  
 - ストリーミング用に最適化  
 - **解像度:** 1920x1080  
 - **FPS:** 30  
 - **サービス:** Twitch  
 - アカウントを接続  
 - 新しく開いたウィンドウでログイン  
 - **ビットレートを自動推定**のチェックを外し、手動で **5900** を入力（*Twitchパートナーの場合は7900*）  
 - ウィザードを**完了**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **OBS**の左下で以下の**シーン**を追加  
 - Start  
 - Live  
 - Low  
 - Brb  
 - End  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Liveシーンをクリックし、**メディアソース**を追加、名前を**Belabox Cloud**に設定  
 - 設定ウィンドウが開きます  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - **[Belabox Cloud](https://cloud.belabox.net/#relays)** ページを開く  
 - **SRT(LA) relays**に移動  
 - **OBS Media Source Settings**が見えるまでスクロール  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **OBSに戻り**、**同じ設定**を適用  
 - ローカルファイルのチェックを外す  
 - ネットワークバッファリングを1 MBに設定  
 - Belabox Cloudページから入力をコピー  
 - 再接続遅延を2秒に設定  
 - 非アクティブ時にファイルを閉じるをチェック  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - **Belabox Cloud**ソースを右クリックし、**変換** > **画面に合わせる**（*またはCTRL+F*）  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - **Belabox Cloud**ソースを**Low**シーンにコピー（*CTRL+C*）  
4.1.j - 右下の**設定**に移動し、**オーディオ**で**すべてのグローバルオーディオデバイスを無効化**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - 上部メニューで**ツール** > **WebSocketサーバー設定**を開き、**WebSocketサーバーを有効化**して**OK**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> このプログラムはチャットコマンドでOBSを制御し、電話からのストリームが検出または切断された場合に自動的にシーンを切り替えます

4.2.a - お使いのシステム用に **[NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** をダウンロードし、任意の場所に解凍（*ストリーム用フォルダ内にNOALBSサブフォルダを作成することを推奨*）  
4.2.b - このフォルダ内に以下の3ファイルがあることを確認  
 - .env  
 - config.json  
 - noalbs  

4.2.c - NOALBSがチャットコマンドに応答するには、Twitchアカウントへのアクセス権が必要です。Twitchにログイン後、**[このリンク](https://b3ck.com/twitch/oauth)** を開き、**Authorize with Twitch**をクリックして表示されたコード全体をコピー  

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **.env**ファイルをテキストエディタで開き  
 - コピーしたデータで全てを置き換え  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - ファイルを保存して閉じる  

4.2.f - ここから[config.json](../config.json)をダウンロードし、ローカルファイルと置き換え  
 - **config.json**をテキストエディタで開き  
 - *REPLACE_STREAMER_NAME*をTwitchアカウント名に3回置換  

4.2.g - **[Belabox Cloud](https://cloud.belabox.net/#relays)** ページを開き、**SRT(LA) relays**に移動  
 - **NOALBSv2 configuration**までスクロール  
 - *REPLACE_BELLABOX_URL*をBelaboxページのURLに置換  
 - *REPLACE_BELLABOX_INGEST_KEY*をURLの最後の部分に置換  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - OBSのWebSocket設定に戻り、**接続情報を表示**をクリック  
 - **サーバーパスワード**をコピー  
 - *REPLACE_OBS_WEBSOCKET_PASSWORD*をコピーしたデータに置換  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - config.jsonを保存して閉じる。*詳細は[NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - **noalbs**プログラムを起動。下図のような画面が表示されます（エラーもここに表示）  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - noalbsファイルを右クリックし、**ショートカットを作成**してデスクトップなどにドラッグすると便利  

---
# 5 - OBSを整える
基本的なセットアップは完了しましたが、シーンが空っぽです。
以下は各シーンの用途と一般的な設定例です。
> [!NOTE]  
> あくまで推奨例です。自由にデザインしてください。

**Start**  
- 配信開始時に表示（電話がライブになるまで）  
- 動画+音楽を背景に使用  
- 「Starting Soon...」などのシンプルなテキスト  

**Live**  
- 電話からOBSに接続されると表示  
- オーバーレイは電話側で設定済みのため追加不要  

**Low**  
- 電話との接続品質が低下した場合  
- 「low bitrate」などのシンプルなテキスト  

**Brb**  
- 電話との接続が完全に切断された場合、またはIRLProで配信を手動停止した場合（プライバシー保護用）  
- 過去のVODやクリップを使用（クリップはVLCメディアソース推奨 *[VLC Media Player](https://www.videolan.org/vlc/)必要*）  
- 「Be right back」テキスト  
- トイレや私用で数分離れる際にも切り替え可能  

**End**  
- Twitchチャットで`!end`と入力すると起動  
- 開始時と同様の動画+音楽  
- 「Ending Stream」テキスト  

---
# 6 - 通常操作  
> [!NOTE]  
> **毎回**のIRL配信前に以下を実行してください  

6.a - 自宅の**PCを起動**し、インターネット接続と自動シャットダウンが無効化されていることを確認  
6.b - PCで**OBS & NOALBSを起動**  
6.c - IRL配信を開始したい場所へ**外出**  
6.d - **Twitchチャット**で`!start`と入力して配信開始  
6.e - **IRL Proで配信開始** → 数秒後に**Liveシーン**に切り替わり  
6.f - 電話の配信停止または接続切断 → 数秒後に**Brbシーン**に切り替わり  
6.g - 電話のインターネット接続回復 → 数秒後に**Liveシーン**に戻る  
6.h - IRLProで手動停止/再開して`!brb`と`!live`を切り替え  
6.i - 誰かをレイドする場合やチャットコマンド`!stop`で**配信を停止**  

> [!IMPORTANT]  
> OBSのシーン切り替え時にチャットにメッセージが表示されます  

---
# 7 - 第2インターネット接続  
> [!NOTE]  
> オプションですが、多くの場合で配信安定性が大幅に向上します。ただし、山奥やトンネルなど電波の届かない場所では効果がありません。  

[概要](#overview)で説明したように、電話用の第2インターネット接続を用意すると配信切断のリスクを軽減できます。  
モバイルWiFiルーターまたは第2の電話をホットスポットとして使用します。  

> [!IMPORTANT]  
> 第2SIMには別の通信事業者を強く推奨します。  
> 第2SIMも全体のデータ通信量の約50%を消費します  

---
# 8 - Twitchに直接配信  

リレーや自宅PCが動作しない場合、IRL Proアプリで簡単に直接配信に切り替えられます。  

8.a - **設定** > **接続**で**Belaboxをオフ**、**Twitchをオン**に切り替え  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - **設定** > **ビデオ**に戻り、**ビットレートを解像度に合わせる**をオン、**フォーマット**を自動に戻す  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - 追加ヘルプ  
### IRLアプリ  
[Discord](https://discord.gg/irlpro)  
### OBS  
[公式フォーラム](https://obsproject.com/forum/)または多数のYouTubeチュートリアルを参照  
### NOALBS  
[Githubガイド](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)と[Discord](https://discord.gg/efWu5HWM2u)  

---
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [支援をご希望ですか？](https://ko-fi.com/naginreed)  