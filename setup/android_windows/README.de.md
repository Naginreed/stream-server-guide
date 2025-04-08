# Anleitung für <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> Diese Übersetzungen wurden mit KI generiert und können Fehler enthalten.  
> Korrekturen können gerne per Pull-Request eingereicht werden.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> Falls du das falsche Betriebssystem gewählt hast, nutze die obigen Buttons.

> [!IMPORTANT]  
> <details>
> <summary>Du kannst die 3 Linien oben rechts nutzen, um zu jedem Abschnitt der Anleitung zu springen</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# Allgemeine Informationen
Diese Anleitung beschreibt eine **günstige und einfache** Lösung für
- besseres **IRL**-Streaming
- **Android** als Streaming-Handy
- **Windows** als Heim-PC

---
## Übersicht <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> Auf den ersten Blick sieht das ziemlich kompliziert aus, aber wir gehen Schritt-für-Schritt mit Bildern *(wenn verfügbar)* durch den gesamten Einrichtungsprozess.

**Vorteile**  

- 👍 Kann mit einer einzigen Internetverbindung vom Handy genutzt werden
- 👍 Falls die Verbindung vom Handy abbricht, sehen die Zuschauer weiterhin Videos/Clips (1x Stream-Start und 1x VOD)
- 👍 Eine zweite Internetverbindung kann hinzugefügt werden, um die Handyverbindung zuverlässiger zu machen
- 👍 Beim Wechsel zwischen WiFi und Mobilfunk bleibt der Stream online

**Nachteile**  

- 👎 Zusätzliche monatliche Kosten für den Relay-Server ($10 USD)
- 👎 Zusätzliche monatliche Kosten für eine zweite Internetverbindung (Optional)
- 👎 Erster Setup-Aufwand benötigt Zeit
---
# 1 - Streaming-Handy  

> [!NOTE]   
> Falls du mehrere Handys hast, nutze das stärkste/neueste als Streaming-Handy

1.a - Installiere **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** aus dem Google Play Store

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - SRT/SRTLA-Relay

> [!NOTE]   
> Dieser Server nimmt die beiden SRTLA-Streams und kombiniert sie zu einem SRT-Stream, wie in der [Übersicht](#overview) zu sehen.

> [!IMPORTANT]   
> Dieser Service kostet $10 USD.

2.a - Erstelle ein Konto bei [Github](https://github.com/signup) *(falls du bereits eines hast, gehe direkt zum Login)*
 - Danach musst du deine E-Mail-Adresse bestätigen und dich [einloggen](https://github.com/login)

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - Nach dem Login öffne die [Belabox Sponsorship](https://github.com/sponsors/rationalsa) Seite  
 - Scrolle nach unten und wähle den **$10 pro Monat**-Tarif, der 1x SRT/SRTLA-Relay-Server beinhaltet
 - Fülle deine Rechnungsdaten aus und richte deine Zahlungsmethode ein *(nur Kreditkarte oder Paypal unterstützt)*
 - Alternativ können deine Zuschauer auch [Gutscheine](https://shop.belabox.net/product/belabox-cloud-voucher) für mehrere Monate kaufen.

2.c - Sobald du gesponsert hast oder einen Gutschein hast, öffne die [Belabox Cloud](https://cloud.belabox.net) Seite und
 - Logge dich mit deinem Github-Konto ein/autorisieren  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - Oben auf der Seite drücke auf die **3 Linien** und dann auf **SRT(LA) relays**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - Klicke auf **Add** und ändere den Namen. Wähle den **Server** in deiner **nächstgelegenen Region** aus.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - Scrolle nach unten bis zu **Moblin Settings** und klicke auf den **Add automatically to Moblin**-Button, um die richtigen Informationen automatisch in Moblin einzutragen.  

---
# 3 - Streaming-Handy
3.a - Öffne die **IRL Pro App** und gehe zum **Zahnrad-Symbol** *(Einstellungen)* oben links  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - Gehe zu **Connections**, wo du die **Belabox Cloud** sehen solltest. Tippe auf **New connection**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - Tippe oben auf **TWITCH.TV** und trage deinen Benutzernamen und deinen [Streamkey](https://dashboard.twitch.tv/settings/stream) ein, dann speichere  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - Gehe zurück ins Menü und tippe auf **Streamer**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - Tippe auf **Twitch Username** und füge deinen Benutzernamen hinzu, dann bestätige. Scrolle nach unten und trage deinen [Streamlabs API Key](https://streamlabs.com/dashboard#/settings/api-settings) ein. *(Falls du jemals Chat-Einstellungen ändern musst, gehe hierher zurück)*

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - Gehe zurück ins Menü und tippe auf **Video**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - Gehe zu **Video** und stelle folgende Einstellungen ein  
 - **Auflösung:** 1920x1080p  
 - **FPS:** 30 feste Rate  
 - **Bitrate passt zur Auflösung:** Aus  
 - **Bitrate:** 4500 kbps  
 - **Format:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - Gehe zurück ins Menü und tippe auf **Overlays**, dann auf **Web Overlays**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - Wir möchten Alerts zu IRL Pro hinzufügen. Dazu gehen wir in unser Alerts-Dashboard im Browser  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) und kopieren die Widget-URL

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - Gehe zurück zu IRL Pro und füge ein **New web overlay** hinzu  
 - **Name:** Alerts  
 - **URL:** Füge die von Streamlabs Alertbox kopierte URL ein  
 - **Breite:** 600  
 - **Höhe:** 400  
*(hier kannst du später die Größe oder Position der Alerts anpassen)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - Nach dem Speichern stelle sicher, dass Alerts aktiviert ist.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - Gehe zurück zur **Hauptansicht** und **prüfe**, ob der **Chat** lädt und teste, ob die **Alerts** **funktionieren**  
 - Streamlabs *(Test-Alerts sind im [Alertbox](https://streamlabs.com/dashboard#/alertbox)-Dashboard verfügbar)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - Windows-PC
Jeder normale PC oder Laptop kann genutzt werden, am besten direkt mit dem Heimrouter verkabelt.
 Falls du einen neuen nur für diese Aufgabe kaufen möchtest, schau dir vielleicht Mini-PCs an.
> [!WARNING]  
> Dieser PC benötigt während des gesamten Streams eine **STABILE** Internetverbindung mit mindestens 6Mbit Upload *[Speedtest](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> Dies ist das Programm, das den Stream vom Relay-Server empfängt und zurück in alte RTMP/h.264-Standards konvertiert und direkt an Twitch sendet. Hier hast du viele Optionen, um Videos, Text und Musik einzustellen, um deine Zuschauer zu unterhalten, während du die Verbindung wiederherstellst.*

4.1.a - **Lade [OBS Studio](https://obsproject.com/download)** für dein System herunter.  
4.1.b - **Installiere OBS Studio** und **starte** es.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - Im Auto-Assistenten:
- Optimieren für Streaming
- **Auflösung:** 1920x1080
- **FPS:** 30
- **Dienst:** Twitch
- Konto verbinden
- Melde dich im neu geöffneten Fenster an.
- Deaktiviere **Bitrate schätzen** und gib manuell **5900** ein *(7900, wenn du Twitch-Partner bist)*
- **Beende** den Assistenten.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **Füge in OBS** unten links nun folgende **Szenen** hinzu:
- Start
- Live
- Low
- Brb
- End

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Klicke auf die Live-Szene und füge eine **Medienquelle** mit dem Namen **Belabox Cloud** hinzu.
- Ein neues Fenster mit Einstellungen öffnet sich.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - Öffne die **[Belabox Cloud](https://cloud.belabox.net/#relays)**-Seite.
- Gehe zu **SRT(LA) relays** und
- scrolle nach unten, bis du **OBS Media Source Settings** siehst.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **Gehe zurück zu OBS** und **setze dieselben Einstellungen**:
- Deaktiviere "Local File"
- Setze "Network Buffering" auf 1 MB
- Kopiere die Eingabe von der Belabox Cloud-Seite
- Setze "Reconnect Delay" auf 2S
- Aktiviere "Close file when inactive"

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - Klicke mit der rechten Maustaste auf die **Belabox Cloud**-Quelle, dann auf **Transformieren** und **An Bildschirm anpassen** *(oder wähle sie aus und drücke STRG+F)*.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - Kopiere *(STRG+C)* die **Belabox Cloud**-Quelle in die **Low**-Szene.  
4.1.j - Gehe zu **Einstellungen** unten rechts. Wähle im neuen Fenster **Audio** und **Deaktiviere alle globalen Audiogeräte**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - Klicke in der oberen Menüleiste auf **Tools** und dann auf **Websocket Server Settings**. Aktiviere **Enable WebSocket Server** und klicke auf **OK**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> Dies ist das Programm, das OBS über Chat-Befehle steuert und automatisch Szenen wechselt, wenn der Stream vom Telefon erkannt oder verloren geht.

4.2.a - **Lade [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** für dein System herunter und entpacke es an einen Ort deiner Wahl *(ich empfehle, einen Stream-Ordner und darin einen NOALBS-Unterordner zu erstellen)*.  
4.2.b - In diesem Ordner sollten nun folgende 3 Dateien vorhanden sein:
- .env
- config.json
- noalbs

4.2.c - Damit NOALBS auf unsere Chat-Befehle reagiert, müssen wir den Zugriff auf ein Twitch-Konto gewähren. Sobald du dich mit deinem bevorzugten Konto bei Twitch angemeldet hast, klicke auf diesen **[Link](https://b3ck.com/twitch/oauth)**, dann auf **Authorize with Twitch** und kopiere den gesamten Code von der Website.

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **Öffne** die **.env**-Datei mit einem Texteditor.
- Ersetze alles mit deinen kopierten Daten.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

- Speichere und schließe die Datei.

4.2.f - Lade die [config.json](../config.json) von hier herunter und ersetze sie mit deiner lokalen Datei.
- **Öffne** die **config.json**-Datei mit einem Texteditor.  
- Ersetze alle 3x *REPLACE_STREAMER_NAME* mit deinem Twitch-Kontonamen.

4.2.g - Öffne die **[Belabox Cloud](https://cloud.belabox.net/#relays)**-Seite und gehe zu **SRT(LA) relays**.  
- Scrolle nach unten zu **NOALBSv2 configuration**.  
- Ersetze *REPLACE_BELLABOX_URL* mit der URL von der Belabox-Seite.
- Ersetze *REPLACE_BELLABOX_INGEST_KEY* mit dem letzten Teil der URL.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - Gehe zurück zu OBS in die Websocket-Einstellungen und klicke auf **Show Connect Info**.  
- Kopiere das **Server-Passwort**.
- Ersetze *REPLACE_OBS_WEBSOCKET_PASSWORD* mit den kopierten Daten.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - Speichere und schließe die config.json-Datei. *Detaillierte Infos auf [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*.  
4.2.j - Starte das **noalbs**-Programm. Es sollte wie im Bild unten aussehen. Fehler werden hier ebenfalls angezeigt.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - Du kannst eine Verknüpfung erstellen, indem du mit der rechten Maustaste auf die noalbs-Datei klickst und **Verknüpfung erstellen** auswählst. Ziehe die Verknüpfung beispielsweise auf den Desktop für einfacheren Zugriff.

---
# 5 - OBS verschönern
Wir sind mit dem grundlegenden Setup fertig, aber die Szenen sind noch ziemlich leer.
Im Folgenden wird erklärt, wofür welche Szene verwendet wird und was normalerweise eingefügt wird.
> [!NOTE]  
> Dies sind nur Empfehlungen. Du kannst sie nach Belieben gestalten.

**Start**
- Diese Szene wird jedes Mal angezeigt, wenn der Stream beginnt, bis das Telefon live geht.
- Oft werden Video+Musik als Hintergrund verwendet.
- Einfacher Text "Starting Soon ..."

**Live**
- Sobald eine Verbindung vom Telefon zu OBS besteht, wird diese Szene angezeigt.
- Keine zusätzlichen Elemente erforderlich, da Overlays auf dem Telefon laufen sollten.

**Low**
- Wird angezeigt, wenn die Verbindung zum Telefon schlecht ist.
- Einfacher Text "low bitrate"

**Brb**
- Wird angezeigt, wenn die Verbindung zum Telefon vollständig verloren geht oder du den Livestream in IRLPro absichtlich beendest *(z.B. aus Datenschutzgründen)*.
- Oft werden alte VODs oder Clips verwendet *(für Clips empfehle ich einen Ordner namens "Clips" und das Hinzufügen einer VLC-Medienquelle *erfordert [VLC Media Player](https://www.videolan.org/vlc/)*)*.
- Einfacher Text "Be right back"
- Kann aktiviert werden, wenn du kurz auf die Toilette gehst oder ein privates Gespräch führst.

**End**
- Kann durch Eingabe von `!end` im Twitch-Chat aktiviert werden.
- Ähnlich wie das Start-Video mit Musik.
- Einfacher Text "Ending Stream"

---
# 6 - Normaler Betrieb
> [!NOTE]  
> Vor **jedem** IRL-Stream musst du Folgendes tun:

6.a - **Starte** deinen **PC** zu Hause und stelle sicher, dass er eine Internetverbindung hat und sich nicht automatisch ausschaltet.  
6.b - **Starte OBS & NOALBS** auf deinem PC.  
6.c - **Gehe nach draußen**, um deinen IRL-Stream zu starten.  
6.d - Gib `!start` im **Twitch-Chat** ein, um den Stream auf Twitch zu starten.  
6.e - **Gehe in IRL Pro live** -> nach ein paar Sekunden wechselst du zur **Live-Szene**.  
6.f - Wenn du den Stream stoppst oder die Verbindung verlierst -> nach ein paar Sekunden wechselst du zur **Brb-Szene**.  
6.g - Sobald die Verbindung vom Telefon zum Internet wiederhergestellt ist -> nach ein paar Sekunden wechselst du zurück zur **Live-Szene**.  
6.h - Beende/Starte den Livestream manuell in IRLPro, um zwischen `!brb` und `!live` zu wechseln.  
6.i - **Stoppe den Stream** automatisch, wenn du jemanden raidet, oder mit dem Chat-Befehl `!stop`.  

> [!IMPORTANT]  
> Bei jedem Szenenwechsel in OBS erscheint eine Textnachricht im Chat.
---
# 7 - Zweite Internetverbindung
> [!NOTE]  
> Dies ist optional, verbessert aber in vielen Fällen die Stream-Stabilität erheblich. Es verhindert jedoch keine Ausfälle in Gebieten ohne Empfang, wie tief in den Bergen oder Tunneln.

Wie in der [Übersicht](#overview) zu sehen ist, kann eine zweite Internetverbindung für dein Telefon die Wahrscheinlichkeit von Ausfällen beim Livestream verringern.  
Entweder ein mobiler WLAN-Router oder ein zweites Telefon mit aktivem Mobile Hotspot.  

> [!IMPORTANT]  
> Für diese zweite SIM-Karte wird ein anderer Anbieter dringend empfohlen.
> Die zweite SIM verbraucht ebenfalls etwa ~50% der gesamten Daten.
---
# 8 - Direkt zu Twitch streamen

Falls der Relay-Server oder der Heim-PC aus irgendeinem Grund nicht funktioniert, kannst du in der IRL Pro App leicht auf direktes Streaming umschalten.  

8.a - Gehe zu **Einstellungen** > **Verbindungen** und schalte **Belabox aus** und **Twitch ein**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - Gehe zurück zu **Einstellungen** und dann zu **Video**. Scrolle nach unten und aktiviere **Bitrate passt zur Auflösung** und setze **Format** auf Auto.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Zusätzliche Hilfe
### IRL App
Hier ist ihr [Discord](https://discord.gg/irlpro).
### OBS
Du kannst ihr [Forum](https://obsproject.com/forum/) besuchen oder eines der hunderten YouTube-Tutorials ansehen.
### NOALBS
Hier ist die Anleitung auf [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) und ihr [Discord](https://discord.gg/efWu5HWM2u).

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Möchtest du mich unterstützen?](https://ko-fi.com/naginreed)