# Anleitung für <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

[![Englisch](https://img.shields.io/badge/English-English-orange.svg)](README.md)
[![Spanisch](https://img.shields.io/badge/Spanish-Español-orange.svg)](README.es.md)
[![Chinesisch](https://img.shields.io/badge/Chinese-中文-orange.svg)](README.zh-CN.md)
[![Französisch](https://img.shields.io/badge/French-Français-orange.svg)](README.fr.md)
[![Deutsch](https://img.shields.io/badge/German-Deutsch-orange.svg)](README.de.md)
[![Portugiesisch](https://img.shields.io/badge/Portuguese-Português-orange.svg)](README.pt-BR.md)
[![Japanisch](https://img.shields.io/badge/Japanese-日本語-orange.svg)](README.ja.md)
[![Russisch](https://img.shields.io/badge/Russian-Русский-orange.svg)](README.ru.md)
[![Koreanisch](https://img.shields.io/badge/Korean-한국어-orange.svg)](README.ko.md)
[![Arabisch](https://img.shields.io/badge/Arabic-العربية-orange.svg)](README.ar.md)

> [!WARNING]
> Diese Übersetzungen wurden mit KI erstellt und können Fehler enthalten.  
> Gerne könnt ihr Korrekturen per Pull-Request einreichen.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.de.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.de.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.de.md)

> [!TIP]
> Falls du das falsche Betriebssystem gewählt hast, nutze die Buttons oben.

> [!IMPORTANT]  
> <details>
> <summary>Du kannst die 3 Linien oben rechts benutzen, um zu einem beliebigen Abschnitt der Anleitung zu springen</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# Allgemeine Informationen
Diese Anleitung beschreibt eine **günstige und einfache** Lösung für
- besseres **IRL**-Streaming
- **Android** als Streaming-Telefon
- **Windows** als Heim-PC

---
## Übersicht <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> Anfangs mag das alles kompliziert erscheinen, aber wir gehen den gesamten Einrichtungsprozess Schritt für Schritt mit Bildern *(wenn verfügbar)* durch.

**Vorteile**  

- 👍 Kann mit einer einzigen Internetverbindung vom Telefon genutzt werden
- 👍 Falls die Verbindung vom Telefon ausfällt, können Zuschauer weiterhin Videos/Clips sehen (1x Streamstart und 1x VOD)
- 👍 Eine zweite Internetverbindung kann hinzugefügt werden, um die Telefonverbindung stabiler zu machen
- 👍 Beim Wechsel zwischen WLAN und Mobilem Netz bleibt der Stream online

**Nachteile**  

- 👎 Zusätzliche monatliche Kosten für den Relay-Server (10 USD)
- 👎 Zusätzliche monatliche Kosten für eine zweite Internetverbindung (optional)
- 👎 Ersteinrichtung nimmt etwas Zeit in Anspruch
---
# 1 - Streaming-Telefon  

> [!NOTE]   
> Falls du mehrere Telefone hast, verwende das leistungsstärkste/neuste als Streaming-Telefon.  

1.a - Installiere die **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** App aus dem Google Play Store.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">  

---
# 2 - SRT/SRTLA-Relay

> [!NOTE]  
> Dieser Server nimmt zwei SRTLA-Streams und kombiniert sie zu einem einzigen SRT-Stream, wie in der [Übersicht](#overview) dargestellt.

> [!IMPORTANT]  
> Dieser Dienst kostet 10 USD.

2.a - Erstelle ein Konto bei [GitHub](https://github.com/signup) *(Falls du bereits eines hast, fahre mit der Anmeldung fort).*  
 - Verifiziere deine E-Mail-Adresse und [melde dich an](https://github.com/login).  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">  

2.b - Nach der Anmeldung öffne die [Belabox Sponsorship](https://github.com/sponsors/rationalsa) Seite.  
 - Scrolle nach unten und wähle das **10 USD pro Monat**-Paket, das einen SRT/SRTLA-Relay-Server beinhaltet.  
 - Gib deine Rechnungsdaten ein und hinterlege eine Zahlungsmethode *(nur Kreditkarte oder PayPal werden unterstützt).*  
 - Alternativ können Zuschauer [Gutscheine](https://shop.belabox.net/product/belabox-cloud-voucher) für mehrere Monate kaufen.

2.c - Sobald du gesponsert hast oder einen Gutschein besitzt, öffne die [Belabox Cloud](https://cloud.belabox.net) Seite.  
 - Melde dich mit deinem GitHub-Konto an bzw. autorisiere es.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">  

2.d - Klicke oben auf der Seite auf die **3 Linien** und dann auf **SRT(LA) relays**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">  

2.e - Klicke auf **Hinzufügen**, ändere den Namen und wähle den **nächstgelegenen Server**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">  

2.f - Scrolle nach unten, bis du **Moblin-Einstellungen** siehst, und tippe auf **Automatisch zu Moblin hinzufügen**, um die richtigen Informationen automatisch einzutragen.  

---
# 3 - Streaming-Telefon

3.a - Öffne die **IRL Pro App** und gehe zum **Zahnrad-Symbol** *(Einstellungen)* oben links.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">  

3.b - Gehe zu **Verbindungen**, wo du die **Belabox Cloud** sehen solltest. Tippe auf **Neue Verbindung**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">  

3.c - Tippe oben auf **TWITCH.TV**, gib deinen Benutzernamen und deinen [Streamkey](https://dashboard.twitch.tv/settings/stream) ein und speichere.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">  

3.d - Gehe zurück ins Menü und tippe auf **Streamer**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">  

3.e - Tippe auf **Twitch-Benutzername**, gib deinen Namen ein und bestätige. Scrolle nach unten und trage deinen [Streamlabs API Key](https://streamlabs.com/dashboard#/settings/api-settings) ein. *(Falls du Chat-Einstellungen ändern musst, gehst du erneut hierhin.)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">  

3.f - Gehe zurück ins Menü und tippe auf **Video**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">  

3.g - Gehe zu **Video** und stelle folgende Einstellungen ein:  
 - **Auflösung:** 1920x1080p  
 - **FPS:** 30 feste Rate  
 - **Bitrate an Auflösung anpassen:** Aus  
 - **Bitrate:** 4500 kbps  
 - **Format:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">  

3.h - Gehe zurück ins Menü und tippe auf **Overlays**, dann auf **Web Overlays**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">  

3.i - Um Alerts in IRL Pro hinzuzufügen, öffne das Alerts-Dashboard im Browser:  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) und kopiere die Widget-URL.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">  

3.j - Kehre zurück zu IRL Pro und erstelle ein **Neues Web-Overlay**:  
 - **Name:** Alerts  
 - **URL:** Füge die zuvor kopierte Streamlabs-Alertbox-URL ein  
 - **Breite:** 600  
 - **Höhe:** 400  
*(Falls die Alerts die falsche Größe oder Position haben, kannst du es hier anpassen.)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">  

3.k - Nachdem du gespeichert hast, stelle sicher, dass **Alerts eingeschaltet** ist.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">  

3.l - Kehre zur **Hauptansicht** zurück und überprüfe, ob der **Chat geladen wird** und **Alerts funktionieren**.  
 - Streamlabs *(Test-Alerts sind in der [Alertbox](https://streamlabs.com/dashboard#/alertbox) verfügbar.)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">  

---
# 4 - Windows-PC

Jeder normale PC oder Laptop kann verwendet werden. Am besten wird er direkt per Kabel mit deinem Heimrouter verbunden.  
Falls du einen neuen PC speziell für diesen Zweck kaufen möchtest, solltest du dir Mini-PCs anschauen.

> [!WARNING]  
> Dieser PC muss während des gesamten Streams eine **STABILE** Internetverbindung mit mindestens 6 Mbit Upload haben *[Speedtest](https://www.nperf.com)*.

## 4.1 OBS

> [!NOTE]  
> Dies ist das Programm, das den Stream vom Relay-Server empfängt und ihn zurück in das alte RTMP/h.264-Format konvertiert, um ihn direkt an Twitch zu senden. Hier hast du viele Möglichkeiten, Videos, Texte und Musik hinzuzufügen, um deine Zuschauer zu unterhalten, während du dich wieder verbindest.

4.1.a - **[OBS Studio](https://obsproject.com/download) herunterladen**
4.1.b - **OBS Studio installieren und starten**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - Im Auto-Wizard:
- Optimieren für Streaming
- **Auflösung:** 1920x1080
- **FPS:** 30
- **Service:** Twitch
- Konto verbinden
- Im Popup-Fenster anmelden
- **Schätz-Bitrate deaktivieren** und manuell **5900** eingeben *(7900, wenn du Twitch-Partner bist)*
- Den Wizard abschließen

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">

4.1.d - **In OBS** unten links die folgenden **Szenen hinzufügen**
- Start
- Live
- Low
- Brb
- End

---
## 4.2 NOALBS

> [!NOTE]  
> Dies ist das Programm, das OBS über Chat-Befehle steuert und automatisch Szenen umschaltet, wenn der Stream vom Telefon erkannt oder verloren wird.

4.2.a - **[NOALBS herunterladen](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)**, entpacke es an einen beliebigen Ort *(empfohlen: einen „Stream“-Ordner mit einem Unterordner für NOALBS erstellen).*  

4.2.b - In diesem Ordner sollten jetzt die folgenden Dateien sein:
- `.env`
- `config.json`
- `noalbs`

4.2.c - NOALBS benötigt Zugriff auf ein Twitch-Konto, um auf Chat-Befehle zu reagieren.  
Melde dich mit deinem bevorzugten Twitch-Konto an und öffne diesen **[Link](https://b3ck.com/twitch/oauth)**.  
- Klicke auf **Mit Twitch autorisieren** und kopiere den gesamten Code von der Website.  

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - Öffne die `.env` Datei mit einem Texteditor.  
- Ersetze den gesamten Inhalt mit dem kopierten Code.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

- Speichern und schließen.  

4.2.e - Lade die [config.json](../config.json) Datei herunter und ersetze deine lokale Datei damit.  
- Öffne `config.json` mit einem Texteditor.  
- Ersetze alle Vorkommen von *REPLACE_STREAMER_NAME* mit deinem Twitch-Benutzernamen.  

4.2.f - Öffne die **[Belabox Cloud](https://cloud.belabox.net/#relays)** Seite und navigiere zu **SRT(LA) relays**.  
- Scrolle nach unten zu **NOALBSv2 Konfiguration**.  
- Ersetze *REPLACE_BELLABOX_URL* mit der URL von der Belabox-Seite.  
- Ersetze *REPLACE_BELLABOX_INGEST_KEY* mit dem letzten Teil der URL.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.g - Gehe zurück zu OBS, öffne die WebSocket-Einstellungen und klicke auf **Verbindungsinfo anzeigen**.  
- Kopiere das **Server-Passwort**.  
- Ersetze *REPLACE_OBS_WEBSOCKET_PASSWORD* mit den kopierten Daten.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">

4.2.h - Speichern und schließen der `config.json` Datei.  
*Detaillierte Informationen auf der [NOALBS GitHub-Seite](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching).*  

4.2.i - **Starte das `noalbs` Programm**.  
- Falls Fehler auftreten, werden sie hier angezeigt.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">  

4.2.j - **Erstelle eine Verknüpfung**, um das Programm einfacher zu starten.  
- Rechtsklicke auf die `noalbs` Datei, wähle **Verknüpfung erstellen** und ziehe die Verknüpfung auf den Desktop.  

---
# 5 - OBS verschönern

Die Grundeinrichtung ist abgeschlossen, aber die Szenen sind noch ziemlich leer. 
Nachfolgend findest du eine Erklärung, welche Szene wofür verwendet wird und was typischerweise hinzugefügt wird.

> [!NOTE]  
> Die folgenden Vorschläge sind nur Empfehlungen. Du kannst dein Design frei gestalten.

Start
- Wird zu Beginn jedes Streams angezeigt, bis das Telefon live ist.
- Oft wird ein Video mit Musik als Hintergrund verwendet.
- Einfacher Text: "Starting Soon ..." ("Gleich geht's los ...")

Live
- Sobald eine Verbindung vom Telefon zu OBS besteht, wird diese Szene angezeigt.
- Zusätzliche Inhalte sind nicht nötig, da Overlays direkt auf dem Telefon laufen sollten.

Low
- Wird angezeigt, wenn die Verbindung zum Telefon schlechte Qualität hat.
- Einfacher Text: "Low Bitrate".

Brb
- Wird aktiviert, wenn die Verbindung zum Telefon komplett verloren geht oder du den Stream absichtlich beendest *(z. B. aus Datenschutzgründen)*.
- Oft werden alte VODs oder Clips verwendet. *(Für Clips empfiehlt sich ein "Clips"-Ordner und das Hinzufügen einer VLC-Medienquelle – benötigt den [VLC Media Player](https://www.videolan.org/vlc/)).*
- Einfacher Text: "Be right back" ("Bin gleich zurück")
- Diese Szene kann auch genutzt werden, wenn du eine Toilettenpause machst oder kurz privat sprechen musst.

Ende
- Kann durch Eingabe von `!end` im Twitch-Chat aktiviert werden.
- Ähnlich wie die Startszene: Video mit Musik.
- Einfacher Text: "Ending Stream" ("Stream beendet").

---
# 6 - Normaler Betrieb

> [!NOTE]  
> Vor **jedem** IRL-Stream müssen die folgenden Schritte durchgeführt werden:

6.a - **Starte deinen PC zu Hause** und stelle sicher, dass er mit dem Internet verbunden ist und nicht automatisch herunterfährt.  
6.b - **Starte OBS & NOALBS** auf deinem PC.  
6.c - **Gehe nach draußen** an den Ort, an dem du streamen möchtest.  
6.d - Gib `!start` im **Twitch-Chat** ein, um den Stream auf Twitch zu starten.  
6.e - **Gehe in IRL Pro live** → Nach wenigen Sekunden wechselt OBS zur **Live-Szene**.  
6.f - Falls du die Verbindung auf dem Telefon verlierst oder beendest → Nach wenigen Sekunden wird auf die **Brb-Szene** umgeschaltet.  
6.g - Sobald die Verbindung vom Telefon wiederhergestellt ist → Nach wenigen Sekunden wird zurück zur **Live-Szene** gewechselt.  
6.h - **Beende oder starte den Stream manuell in IRL Pro**, um zwischen `!brb` und `!live` zu wechseln.  
6.i - **Beende den Stream** automatisch, wenn du jemanden raidest oder per Chat-Befehl `!stop`.  

> [!IMPORTANT]  
> Bei jedem Szenenwechsel in OBS erscheint eine Textnachricht im Chat.  

---
# 7 - Zweite Internetverbindung

> [!NOTE]  
> Dies ist optional, kann aber in vielen Fällen die Stabilität des Streams erheblich verbessern. Es verhindert jedoch keine Ausfälle in Bereichen ohne Netzabdeckung, wie z. B. tief in den Bergen oder Tunneln.

Wie in der [Übersicht](#overview) dargestellt, kann eine zweite Internetverbindung für dein Telefon eingerichtet werden, um die Wahrscheinlichkeit von Ausfällen während des Streams zu reduzieren. Dies kann entweder durch einen **mobilen WLAN-Router** oder ein **zweites Telefon mit aktiviertem mobilen Hotspot** erfolgen.

> [!IMPORTANT]  
> Es wird dringend empfohlen, für die zweite SIM-Karte einen anderen Anbieter zu verwenden.  
> Die zweite SIM-Karte verbraucht etwa **50 % des gesamten Datenvolumens**.  

---
# 8 - Direkt zu Twitch streamen

Falls der Relay-Server oder dein Heim-PC aus irgendeinem Grund nicht funktioniert, kannst du in der IRL Pro App ganz einfach zum direkten Streaming auf Twitch wechseln.

8.a - Gehe zu **Einstellungen** > **Verbindungen** und schalte **Belabox aus** und **Twitch ein**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600">  
</details>

8.b - Gehe zurück zu **Einstellungen** > **Video**. Scrolle nach unten und aktiviere **Bitrate an Auflösung anpassen** wieder und stelle das **Format** auf Auto.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Zusätzliche Hilfe

### IRL App
Hier ist deren [Discord](https://discord.gg/irlpro).

### OBS
Du kannst deren [Forum](https://obsproject.com/forum/) besuchen oder eine der zahlreichen YouTube-Anleitungen anschauen.

### NOALBS
Hier ist die Anleitung auf [GitHub](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) sowie deren [Discord](https://discord.gg/efWu5HWM2u).

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Möchtest du mich unterstützen?](https://ko-fi.com/naginreed)
