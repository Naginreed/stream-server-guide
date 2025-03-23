# 스트림 서버 (Stream-Server)
[![English](https://img.shields.io/badge/English-English-orange.svg)](../README.md)
[![Spanish](https://img.shields.io/badge/Spanish-Español-orange.svg)](README.es.md)
[![Chinese](https://img.shields.io/badge/Chinese-中文-orange.svg)](README.zh-CN.md)
[![French](https://img.shields.io/badge/French-Français-orange.svg)](README.fr.md)
[![German](https://img.shields.io/badge/German-Deutsch-orange.svg)](README.de.md)
[![Portuguese](https://img.shields.io/badge/Portuguese-Português-orange.svg)](README.pt-BR.md)
[![Japanese](https://img.shields.io/badge/Japanese-日本語-orange.svg)](README.ja.md)
[![Russian](https://img.shields.io/badge/Russian-Русский-orange.svg)](README.ru.md)
[![Korean](https://img.shields.io/badge/Korean-한국어-orange.svg)](README.ko.md)
[![Arabic](https://img.shields.io/badge/Arabic-العربية-orange.svg)](README.ar.md)

> [!WARNING]
> 이 번역은 인공지능(AI)에 의해 생성되었으며 오류가 포함될 수 있습니다.  
> 수정 사항이 있으면 풀 리퀘스트(Pull Request)를 통해 제출해 주세요.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ko.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ko.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ko.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ko.md)

> [!TIP]
> 위에서 운영 체제를 선택하여 간편하고 저렴한 설정 방법을 확인하세요.

---
## 스트림 서버(Stream-Server)란 무엇인가?
IRL 스트리밍을 하다 보면 화장실을 가거나 민감한 정보를 가려야 하는 등 잠깐의 휴식이 필요한 상황이 종종 발생합니다.  
라이브 스트림을 *종료*할 수도 있지만, 이렇게 하면 시청자를 잃게 되고, 매번 새로운 VOD가 생성됩니다.  
마찬가지로 휴대폰 신호가 완전히 끊기거나 배터리가 방전될 때도 같은 문제가 발생합니다.

> [!NOTE]  
> **Everything that happens on the phone affects directly your stream**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

이를 방지하기 위해 많은 스트리머들이 스트림 서버(Stream-Server)라는 것을 사용합니다.

스트림 서버는 휴대폰과 스트리밍 서비스 *(예: Twitch, Kick, YouTube)* 사이에서 중간 역할을 하며,
휴대폰 스트림이 끊기는 경우 이를 감지하여 시청자들에게 재미있는 클립을 보여주어
그들이 상황을 이해하고 계속 즐길 수 있도록 도와줍니다.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

# 3가지 버전
어떤 버전을 선택할지는 다음 요소에 따라 결정됩니다:

**💵 얼마나 많은 돈을 투자할 의향이 있는가**  
**VS**  
**🛠️⌛ 얼마나 많은 시간과 노력을 투자할 의향이 있는가**

---
## 버전 A - 호스팅 설정
가장 간단한 방법은 모든 [구성 요소](#구성-요소)를 포함하는 스트림 서버를 임대하는 것입니다. 이 서버는 다양한 수준의 지원을 제공할 수도 있습니다.

- **알려진 제공업체**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## 버전 B - 혼합 설정
좋은 성능의 PC와 안정적인 인터넷이 있다면 일부 [구성 요소](#구성-요소)를 집에서 실행하여 월별 비용을 절약할 수 있습니다.
> [!WARNING]
> 여기에는 약간의 기술 지식이 필요하며 설정하는 데 몇 시간이 걸립니다. 일부 지원은 직접 수행합니다.

- **알려진 제공업체**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/) 및 [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)  
- **설정 가이드**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ko.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ko.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ko.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ko.md)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## 버전 C - 전체 홈 설정
모든 [구성 요소](#구성-요소)를 집에서 직접 실행할 수 있으며, 추가 비용이 들지 않습니다.
> [!CAUTION]
> **고급 기술 지식**이 필요하며, 모든 유지보수 및 지원은 직접 해야 합니다.  
> 잘못된 설정 시 보안 위험이 발생할 수 있습니다.
- **네트워크**:  
공인 IP, dynDNS, 포트 포워딩 또는 방화벽 설정.
- **서버**:  
Docker 컨테이너 설치 및 유지보수, 로컬 설정 변경 포함.
- **Docker 컨테이너**:  
[Glowf1sh의 올인원 컨테이너](https://hub.docker.com/r/glowf1sh/srtla-receiver) 또는 [Datagutt의 bbox-receiver](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## 구성 요소
- **SRTLA 수신기/엔드포인트**: 여러 SRTLA 연결을 수신하여 하나의 SRT 스트림으로 결합합니다.
- **SLS**: 요청 시 스트림 ID와 함께 SRT 스트림을 제공하며, 연결 정보(예: 비트레이트)가 포함된 상태 페이지를 포함합니다.
- **NOALBS**: SLS 상태 페이지 또는 채팅 명령어를 기반으로 OBS 장면을 변경하고, 연결된 채팅에 정보를 게시합니다.
- **OBS**: SRT와 RTMP 간 변환을 가능하게 하며 다양한 커스터마이징 옵션을 제공하는 PC 또는 서버용 스트리밍 소프트웨어입니다.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [후원하고 싶으신가요?](https://ko-fi.com/naginreed)

