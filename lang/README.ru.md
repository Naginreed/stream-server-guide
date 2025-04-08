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
> Эти переводы были сгенерированы ИИ и могут содержать ошибки.  
> Вы можете отправить исправления через pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ru.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ru.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ru.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ru.md)

> [!TIP]
> Перейдите сразу к моему простому и доступному руководству по настройке, выбрав операционную систему выше.

---
## Что такое Stream-Server
В IRL-стриминге часто возникают ситуации, когда вам нужно сделать короткий перерыв, например, чтобы сходить в туалет или скрыть конфиденциальную информацию.
Вы можете *завершить трансляцию*, но это приведет к потере зрителей и созданию нового видео каждый раз, когда вы это делаете.
То же самое происходит, если вы теряете сигнал сотовой сети или у вас разряжается батарея.

> [!NOTE]  
> **Все, что происходит на телефоне, напрямую влияет на ваш поток.**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

Чтобы избежать этого, многие стримеры используют так называемый Stream-Server.

Он действует как посредник между вашим телефоном и стриминговым сервисом *(например, Twitch, Kick, YouTube)*, позволяя обнаруживать сбои в передаче потока и вместо этого показывать забавные клипы, чтобы удержать зрителей в курсе и развлечь их.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

# 3 Варианта
Выбор версии обычно зависит от следующего:

**💵 Сколько денег вы готовы потратить**  
**VS**  
**🛠️⌛ Сколько работы и времени вы готовы вложить**

---
## Вариант A - Хостинг
Самый простой вариант — арендовать Stream-Server, который объединяет все [Компоненты](#компоненты) и часто предлагает различные уровни поддержки.

- **Известные провайдеры**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Вариант B - Комбинированная настройка
Если у вас есть хороший ПК и стабильное интернет-соединение дома, вы можете перенести некоторые [Компоненты](#компоненты) на домашний ПК, чтобы "сэкономить" на ежемесячных расходах.
> [!WARNING]
> Это требует некоторых технических знаний и займет несколько часов настройки. Часть поддержки выполняется вами.

- **Известные провайдеры**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)  
- **Руководства**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.ru.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.ru.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.ru.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.ru.md)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Вариант C - Полная домашняя настройка
Вы можете перенести все [Компоненты](#компоненты) на домашний ПК, что избавит вас от дополнительных расходов.
> [!CAUTION]
> Это требует **глубоких технических знаний**, и весь процесс поддержки и обслуживания ложится на вас.  
> Возможны риски безопасности при неправильной конфигурации.
- **Сеть**:  
Публичный IP, dynDNS, проброс портов или настройки фаервола.
- **Сервер**:  
Установка и обслуживание контейнеров Docker, включая изменение локальных настроек.
- **Контейнеры Docker**:  
[All-in-One Container от Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) или [bbox-receiver от Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Компоненты
- **SRTLA Receiver/Endpoints**: Принимает несколько соединений SRTLA и объединяет их в один поток SRT.
- **SLS**: Предоставляет поток SRT по запросу с идентификатором потока и включает страницу статуса с информацией о подключении (например, битрейт).
- **NOALBS**: Меняет сцены OBS на основе страницы статуса SLS или команд чата и публикует информацию в подключенном чате.
- **OBS**: Программное обеспечение для стриминга на ПК или сервере, позволяющее конвертировать SRT в RTMP и добавлять множество параметров настройки.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Хотите поддержать меня?](https://ko-fi.com/naginreed)

