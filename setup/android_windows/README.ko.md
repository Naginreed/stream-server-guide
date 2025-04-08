# <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a> 가이드

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
> 이 번역은 AI로 생성되었으며 오류가 포함될 수 있습니다.  
> 수정 사항은 풀 리퀘스트로 제출해 주세요.  

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.ko.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.ko.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.ko.md)

> [!TIP]  
> 잘못된 OS를 선택한 경우 위 버튼을 사용하세요.  

> [!IMPORTANT]  
> <details>  
> <summary>오른쪽 상단의 3줄 메뉴를 사용하여 가이드의 특정 섹션으로 이동할 수 있습니다</summary>  
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">  
> </details>  

---  
# 일반 정보  
이 가이드는 **저렴하고 쉬운** 솔루션을 설명합니다:  
- 더 나은 **IRL** 스트리밍  
- **Android**를 스트리밍 폰으로 사용  
- **Windows**를 홈 PC로 사용  

---  
## 개요 <a id="overview" />  

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">  

> [!NOTE]  
> 처음 보면 복잡해 보이지만, 전체 설정 과정을 단계별로 그림과 함께 설명합니다.  

**장점**  

- 👍 폰의 단일 인터넷 연결로 사용 가능  
- 👍 폰 연결이 실패해도 시청자는 비디오/클립을 볼 수 있음 (1회 스트림 시작 및 1회 VOD)  
- 👍 더 안정적인 폰 연결을 위해 두 번째 인터넷 추가 가능  
- 👍 WiFi와 모바일 데이터 간 전환 시 스트림이 중단되지 않음  

**단점**  

- 👎 릴레이 서버 추가 월 비용 ($10 USD)  
- 👎 두 번째 인터넷 추가 월 비용 (선택 사항)  
- 👎 초기 설정에 시간이 소요됨  

---  
# 1 - 스트리밍 폰  

> [!NOTE]  
> 여러 대의 폰이 있다면 가장 강력한/최신 폰을 스트리밍 폰으로 사용하세요.  

1.a - Google Play 스토어에서 **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** 설치  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">  

---  
# 2 - SRT/SRTLA 릴레이  

> [!NOTE]  
> 이 서버는 두 개의 SRTLA 스트림을 받아 하나의 SRT 스트림으로 결합합니다 ([개요](#overview) 참조).  

> [!IMPORTANT]  
> 이 서비스는 월 $10 USD가 듭니다.  

2.a - [Github](https://github.com/signup) 계정 생성 *(이미 계정이 있다면 로그인으로 건너뛰세요)*  
 - 이메일 주소를 확인하고 [로그인](https://github.com/login)하세요.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">  

2.b - 로그인 후 [Belabox Sponsorship](https://github.com/sponsors/rationalsa) 페이지 열기  
 - 아래로 스크롤하여 **월 $10** 티어 선택 (1x SRT/SRTLA 릴레이 서버 포함)  
 - 청구 정보 입력 및 결제 정보 설정 *(신용 카드 또는 페이팔만 지원)*  
 - 또는 시청자에게 여러 달 사용 가능한 [바우처](https://shop.belabox.net/product/belabox-cloud-voucher)를 구매하도록 할 수 있습니다.  

2.c - 스폰서십을 등록하거나 바우처가 있다면 [Belabox Cloud](https://cloud.belabox.net) 페이지 열기  
 - Github 계정으로 로그인/인증  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">  

2.d - 페이지 상단의 **3줄 메뉴**를 누르고 **SRT(LA) relays** 선택  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">  

2.e - **Add** 클릭 후 이름 변경. **Server**를 **가장 가까운 위치**로 변경  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">  

2.f - 아래로 스크롤하여 **Moblin Settings**를 찾고 **Add automatically to Moblin** 버튼을 눌러 Moblin에 자동으로 정보 추가  

---  
# 3 - 스트리밍 폰  
3.a - **IRL Pro 앱** 열고 왼쪽 상단의 **기어 아이콘** *(설정)* 선택  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">  

3.b - **Connections**로 이동하여 **Belabox Cloud** 확인. **New connection** 탭.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">  

3.c - 상단의 **TWITCH.TV** 탭하고 사용자 이름과 [스트림 키](https://dashboard.twitch.tv/settings/stream) 입력 후 저장  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">  

3.d - 메뉴로 돌아가 **Streamer** 탭  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">  

3.e - **Twitch Username** 탭하고 사용자 이름 입력 후 확인. 아래로 스크롤하여 [Streamlabs API 키](https://streamlabs.com/dashboard#/settings/api-settings) 입력. *(채팅 설정 변경이 필요할 때 여기로 다시 오세요)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">  

3.f - 메뉴로 돌아가 **Video** 탭  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">  

3.g - **Video**에서 다음 설정 적용  
 - **해상도:** 1920x1080p  
 - **FPS:** 30 고정  
 - **해상도에 맞는 비트레이트:** 끄기  
 - **비트레이트:** 4500 kbps  
 - **형식:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">  

3.h - 메뉴로 돌아가 **Overlays** 탭 후 **Web Overlays**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">  

3.i - IRL Pro에 알림을 추가하려면 브라우저로 알림 대시보드 이동  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox)에서 위젯 URL 복사  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">  

3.j - IRL Pro로 돌아가 **New web overlay** 추가  
 - **이름:** Alerts  
 - **URL:** Streamlabs Alertbox에서 복사한 URL 붙여넣기  
 - **너비:** 600  
 - **높이:** 400  
*(알림 크기나 위치가 잘못된 경우 나중에 여기서 변경 가능)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">  

3.k - 저장 후 Alerts가 켜져 있는지 확인  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">  

3.l - **메인 화면**으로 돌아가 **채팅**이 로드되는지 확인하고 **알림**이 **작동**하는지 테스트  
 - Streamlabs *(테스트 알림은 [Alertbox](https://streamlabs.com/dashboard#/alertbox)에서 사용 가능)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">  

---  
# 4 - Windows-PC  
일반 PC나 노트북을 사용할 수 있으며, 홈 인터넷 라우터에 직접 연결하는 것이 가장 좋습니다.  
이 작업만을 위해 새로 구매하려면 미니 PC를 고려해 보세요.  

> [!WARNING]  
> 이 PC는 전체 스트리밍 동안 **안정적인** 인터넷 연결이 필요하며 최소 6Mbit 업로드 속도가 필요합니다 *[Speedtest](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> 이 프로그램은 릴레이 서버에서 스트림을 받아서 오래된 RTMP/h.264 표준으로 변환하고 Twitch로 직접 스트리밍합니다. 여기서는 시청자들이 재연결하는 동안 즐길 수 있도록 비디오, 텍스트, 음악 등 다양한 옵션을 설정할 수 있습니다.*

4.1.a - 시스템에 맞는 **[OBS Studio](https://obsproject.com/download)** 다운로드  
4.1.b - **OBS Studio 설치** 후 **실행**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - 자동 설정 마법사에서  
 - 스트리밍 최적화 선택  
 - **해상도:** 1920x1080  
 - **FPS:** 30  
 - **서비스:** Twitch  
 - 계정 연결  
 - 새로 뜬 창에 로그인  
 - **비트레이트 자동 추정** 해제 후 수동으로 **5900** 입력 *(Twitch 파트너인 경우 7900)*  
 - 마법사 **완료**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **OBS** 왼쪽 하단에서 다음 **장면 추가**  
 - 시작  
 - 라이브  
 - 저화질  
 - 잠시 자리 비움  
 - 종료  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - 라이브 장면 클릭 후 **미디어 소스** 추가, 이름은 **Belabox Cloud**  
 - 설정 창이 열립니다  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - **[Belabox Cloud](https://cloud.belabox.net/#relays)** 페이지 열기  
 - **SRT(LA) 릴레이**로 이동  
 - **OBS 미디어 소스 설정**이 보일 때까지 스크롤  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **OBS**로 돌아가서 **동일한 설정 적용**  
 - 로컬 파일 체크 해제  
 - 네트워크 버퍼링을 1MB로 설정  
 - Belabox Cloud 페이지에서 입력 복사  
 - 재연결 지연을 2초로 설정  
 - 비활성 시 파일 닫기 체크  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - **Belabox Cloud** 소스 우클릭 후 **변환** > **화면에 맞추기** *(또는 선택 후 CTRL+F)*  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - **Belabox Cloud** 소스를 **저화질** 장면으로 복사 *(CTRL+C)*  
4.1.j - 오른쪽 하단 **설정** > **오디오**에서 **모든 글로벌 오디오 장치 비활성화**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - 상단 메뉴 바에서 **도구** > **웹소켓 서버 설정** 클릭  
 - **웹소켓 서버 활성화** 체크 후 **확인**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> 이 프로그램은 채팅 명령으로 OBS를 제어하고, 폰 스트림이 감지되거나 끊길 때 자동으로 장면을 전환합니다.

4.2.a - 시스템에 맞는 **[NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** 다운로드 후 원하는 위치에 압축 해제 *(스트림 폴더 내 NOALBS 하위 폴더 권장)*  
4.2.b - 이 폴더 내에 다음 3개 파일이 있어야 함  
 - .env  
 - config.json  
 - noalbs  

4.2.c - NOALBS가 채팅 명령에 응답하려면 Twitch 계정 접근 권한이 필요합니다. 원하는 계정으로 Twitch에 로그인한 후 **[이 링크](https://b3ck.com/twitch/oauth)**를 클릭하고 **Authorize with Twitch**를 누른 후 웹사이트에서 전체 코드 복사  

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **.env** 파일을 텍스트 편집기로 열기  
 - 모든 내용을 복사한 데이터로 교체  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - 파일 저장 후 닫기  

4.2.f - [config.json](../config.json) 다운로드 후 로컬 파일 교체  
 - **config.json** 파일을 텍스트 편집기로 열기  
 - *REPLACE_STREAMER_NAME*을 Twitch 계정 이름으로 3번 교체  

4.2.g - **[Belabox Cloud](https://cloud.belabox.net/#relays)** 페이지 열고 **SRT(LA) 릴레이**로 이동  
 - **NOALBSv2 구성**까지 스크롤  
 - *REPLACE_BELLABOX_URL*을 Belabox 페이지의 URL로 교체  
 - *REPLACE_BELLABOX_INGEST_KEY*를 URL의 마지막 부분으로 교체  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - OBS로 돌아가서 웹소켓 설정에서 **연결 정보 표시** 클릭  
 - **서버 비밀번호** 복사  
 - *REPLACE_OBS_WEBSOCKET_PASSWORD*를 복사한 데이터로 교체  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - config.json 파일 저장 후 닫기. *자세한 정보는 [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - **noalbs** 프로그램 실행. 아래 그림과 같이 표시됩니다. 오류도 여기에 표시됨  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - noalbs 파일 우클릭 후 **바로 가기 만들기**를 눌러 바탕 화면 등에 드래그하여 쉽게 접근 가능  

---
# 5 - OBS 예쁘게 꾸미기
기본 설정은 완료되었지만, 장면이 비어 있습니다.  
다음은 각 장면의 용도와 일반적으로 추가하는 내용에 대한 설명입니다.  
> [!NOTE]  
> 다음은 권장 사항일 뿐입니다. 원하는 대로 디자인하세요.

**시작**  
- 스트림 시작 시 폰이 라이브될 때까지 이 장면이 표시됩니다.  
- 비디오+음악을 배경으로 자주 사용합니다.  
- "곧 시작합니다..." 같은 간단한 텍스트  

**라이브**  
- 폰에서 OBS로 연결이 되면 이 장면이 표시됩니다.  
- 폰에서 오버레이가 실행되므로 추가 요소가 필요 없습니다.  

**저화질**  
- 폰 연결 품질이 나쁠 때 표시됩니다.  
- "저화질" 같은 간단한 텍스트  

**잠시 자리 비움**  
- 폰 연결이 완전히 끊기거나 IRLPro에서 수동으로 라이브스트림을 종료할 때 *(개인 정보 보호를 위해)*  
- 이전 VOD나 클립을 자주 사용합니다 *(클립은 [VLC 미디어 플레이어](https://www.videolan.org/vlc/)가 필요함)*  
- "곧 돌아오겠습니다" 같은 텍스트  
- 화장실 가거나 잠시 대화할 때 전환 가능  

**종료**  
- Twitch 채팅에 `!end` 입력으로 활성화됩니다.  
- 시작 비디오+음악과 유사합니다.  
- "스트림 종료 중" 같은 텍스트  

---
# 6 - 일반적인 운영  
> [!NOTE]  
> **매번** IRL 스트림 전에 다음을 수행해야 합니다.  

6.a - 집에 있는 **PC를 시작**하고 인터넷 연결이 되어 있는지, 자동 종료되지 않는지 확인  
6.b - PC에서 **OBS & NOALBS 실행**  
6.c - IRL 스트림을 시작할 장소로 **외출**  
6.d - Twitch 채팅에 `!start` 입력하여 Twitch로 스트림 시작  
6.e - **IRL Pro에서 라이브 시작** → 몇 초 후 **라이브 장면**으로 전환  
6.f - 폰에서 연결이 끊기거나 중지되면 → 몇 초 후 **잠시 자리 비움 장면**으로 전환  
6.g - 폰에서 인터넷 연결이 복구되면 → 몇 초 후 **라이브 장면**으로 다시 전환  
6.h - IRLPro에서 수동으로 라이브스트림 시작/종료하여 `!brb`와 `!live` 전환  
6.i - 누군가를 레이드하거나 채팅 명령 `!stop`으로 **스트림 자동 종료**  

> [!IMPORTANT]  
> OBS에서 장면이 전환될 때마다 채팅에 메시지가 표시됩니다.  

---
# 7 - 2차 인터넷 연결  
> [!NOTE]  
> 이는 선택 사항이지만 많은 경우 스트림 안정성을 크게 향상시킵니다. 하지만 산속이나 터널 같은 무신호 지역에서는 중단을 방지하지 못합니다.  

[개요](#overview)에서 본 것처럼 라이브 스트림 중단 가능성을 줄이기 위해 폰에 2차 인터넷 연결을 사용할 수 있습니다.  
모바일 WiFi 라우터 또는 핫스팟이 활성화된 두 번째 폰을 사용합니다.  

> [!IMPORTANT]  
> 두 번째 SIM에는 다른 통신사 사용을 강력히 권장합니다.  
> 두 번째 SIM도 전체 데이터의 약 ~50%를 소비합니다.  

---
# 8 - Twitch로 직접 스트리밍  

어떤 이유로든 릴레이 또는 홈 PC가 작동하지 않을 경우 IRL Pro 앱에서 쉽게 직접 스트리밍으로 전환할 수 있습니다.  

8.a - **설정** > **연결**로 이동하여 **Belabox 끄기** 및 **Twitch 켜기**  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - **설정** > **비디오**로 돌아가서 **비트레이트 해상도 일치** 다시 켜기 및 **형식**을 자동으로 설정  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - 추가 도움  
### IRL 앱  
[디스코드](https://discord.gg/irlpro) 참조  
### OBS  
[포럼](https://obsproject.com/forum/) 확인 또는 수백 개의 YouTube 튜토리얼 참조  
### NOALBS  
[Github 가이드](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) 및 [디스코드](https://discord.gg/efWu5HWM2u) 참조  

---
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [도움을 주시겠습니까?](https://ko-fi.com/naginreed)
