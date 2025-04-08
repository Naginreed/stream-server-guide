# Руководство для <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> Эти переводы были созданы с использованием ИИ и могут содержать ошибки.  
> Вы можете предложить исправления через pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> Если вы выбрали не ту ОС, используйте кнопки выше.

> [!IMPORTANT]  
> <details>
> <summary>Вы можете использовать 3 линии в верхнем правом углу, чтобы перейти к любому разделу руководства</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# Общая информация
Это руководство описывает **дешевое и простое** решение для:
- улучшения **IRL**-стриминга
- использования **Android** в качестве стримингового телефона
- использования **Windows** в качестве домашнего ПК

---
## Обзор <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> Сначала это может показаться сложным, но мы пройдем весь процесс настройки шаг за шагом с изображениями *(если они доступны)*.

**Плюсы**  

- 👍 можно использовать с одним интернет-подключением от телефона
- 👍 если подключение телефона прервется, зрители все равно увидят видео/клипы (1x начало стрима и 1x VOD)
- 👍 можно добавить второй интернет для повышения надежности подключения телефона
- 👍 при переключении между Wi-Fi и мобильным интернетом стрим не прерывается

**Минусы**  

- 👎 Дополнительные ежемесячные затраты на релейный сервер ($10 USD)
- 👎 Дополнительные ежемесячные затраты на второй интернет (опционально)
- 👎 Первоначальная настройка занимает некоторое время

---
# 1 - Стриминговый телефон  

> [!NOTE]   
> Если у вас несколько телефонов, используйте самый мощный/новый в качестве стримингового.

1.a - Установите **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** из Google Play Store

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - SRT/SRTLA релейный сервер

> [!NOTE]   
> Этот сервер объединяет два SRTLA-потока в один SRT-поток, как показано в [Обзоре](#overview).

> [!IMPORTANT]   
> Эта услуга стоит $10 USD.

2.a - Создайте аккаунт на [Github](https://github.com/signup) *(если у вас уже есть аккаунт, перейдите к входу)*
 - Затем вам нужно подтвердить адрес электронной почты и [войти](https://github.com/login).

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - После входа откройте страницу [Belabox Sponsorship](https://github.com/sponsors/rationalsa)  
 - Прокрутите вниз и выберите тариф **$10 в месяц**, который включает 1x SRT/SRTLA релейный сервер.
 - Заполните информацию о платеже и настройте способ оплаты *(поддерживаются только кредитные карты или Paypal)*.
 - Альтернативно, ваши зрители могут купить [ваучеры](https://shop.belabox.net/product/belabox-cloud-voucher) на несколько месяцев.

2.c - После спонсирования или получения ваучера откройте страницу [Belabox Cloud](https://cloud.belabox.net) и:
 - Войдите/авторизуйтесь с помощью аккаунта Github.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - В верхней части страницы нажмите **3 линии**, затем **SRT(LA) relays**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - Нажмите **Add** и измените имя. Измените **Server** на ближайший к вам **локацию**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - Прокрутите вниз до раздела **Moblin Settings** и нажмите кнопку **Add automatically to Moblin**, чтобы автоматически добавить правильную информацию в Moblin.  

---
# 3 - Стриминговый телефон
3.a - Откройте приложение **IRL Pro** и перейдите к значку **шестеренки** *(Настройки)* в верхнем левом углу.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - Перейдите в раздел **Connections**, где вы должны увидеть **Belabox Cloud**. Нажмите **New connection**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - Нажмите на **TWITCH.TV** вверху и введите имя пользователя и ваш [Streamkey](https://dashboard.twitch.tv/settings/stream), затем нажмите сохранить.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - Вернитесь в меню и нажмите **Streamer**.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - Нажмите **Twitch Username** и добавьте имя пользователя, затем OK. Прокрутите вниз и введите ваш [Streamlabs API Key](https://streamlabs.com/dashboard#/settings/api-settings). *(Если вам нужно изменить настройки чата, вернитесь сюда.)*

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - Вернитесь в меню и нажмите **Video**.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - Перейдите в раздел **Video** и установите следующие настройки:  
 - **Разрешение:** 1920x1080p  
 - **Частота кадров:** 30 фиксированная  
 - **Битрейт соответствует разрешению:** Выкл.  
 - **Битрейт:** 4500 kbps  
 - **Формат:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - Вернитесь в меню и нажмите **Overlays**, затем **Web Overlays**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - Мы хотим добавить алерты в IRL Pro. Для этого перейдите в панель управления алертами через браузер:  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) и скопируйте URL виджета.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - Вернитесь в IRL Pro и добавьте **New web overlay**:  
 - **Имя:** Alerts  
 - **URL:** Вставьте скопированный URL из Streamlabs Alertbox  
 - **Ширина:** 600  
 - **Высота:** 400  
*(здесь можно позже изменить размер или положение алертов)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - После сохранения убедитесь, что Alerts включены.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - Вернитесь в **Главное меню** и **проверьте**, что **Чат** загружается, и протестируйте, что **Алерты** **работают**.  
 - Streamlabs *(тестовые алерты доступны в [Alertbox](https://streamlabs.com/dashboard#/alertbox))*.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - Windows-ПК
Любой обычный ПК или ноутбук можно использовать, лучше подключить его напрямую к домашнему интернет-роутеру.
 Если вы хотите купить новый ПК только для этой задачи, возможно, стоит рассмотреть мини-ПК.
> [!WARNING]  
> Этот ПК должен иметь **СТАБИЛЬНОЕ** интернет-подключение во время всего стрима с минимум 6 Мбит/с загрузки *[Speedtest](https://www.nperf.com)*.

## 4.1 OBS
> [!NOTE]  
> Это программа, которая получает поток с релейного сервера, преобразует его обратно в старые стандарты RTMP/h.264 и напрямую транслирует на Twitch. Здесь у вас есть множество опций для добавления видео, текста, музыки, чтобы развлекать зрителей, пока вы переподключаетесь*.

4.1.a - **Скачайте [OBS Studio](https://obsproject.com/download)** для вашей системы.  
4.1.b - **Установите OBS Studio** и **запустите** его.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - В автоматическом мастере настройки:  
 - Оптимизировать для стриминга.  
 - **Разрешение:** 1920x1080.  
 - **FPS:** 30.  
 - **Сервис:** Twitch.  
 - Подключить аккаунт.  
 - Войдите в появившемся окне.  
 - Снимите галочку **Оценить битрейт** и вручную введите **5900** *(7900, если вы партнер Twitch)*.  
 - **Завершите** мастер.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **В OBS** внизу слева **добавьте** следующие **сцены**:  
 - Start (Старт).  
 - Live (Эфир).  
 - Low (Низкое качество).  
 - Brb (Скоро вернусь).  
 - End (Завершение).  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Нажмите на сцену **Live**, добавьте **Источник медиа** с названием **Belabox Cloud**.  
 - Откроется новое окно с настройками.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - Откройте страницу **[Belabox Cloud](https://cloud.belabox.net/#relays)**.  
 - Перейдите в раздел **SRT(LA) relays**.  
 - Прокрутите вниз до раздела **OBS Media Source Settings**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **Вернитесь в OBS** и **установите** **те же настройки**:  
 - Снимите галочку **Local File**.  
 - Установите **Network Buffering** на 1 MB.  
 - Скопируйте **Input** со страницы Belabox Cloud.  
 - Установите **Reconnect Delay** на 2S.  
 - Поставьте галочку **Close file when inactive**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - Кликните правой кнопкой на источник **Belabox Cloud**, затем **Transform** и **Fit to Screen** *(или выделите его и нажмите CTRL+F)*.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - Затем скопируйте *(CTRL+C)* источник **Belabox Cloud** в сцену **Low**.  
4.1.j - Перейдите в **Настройки** внизу справа. В новом окне выберите **Audio** и **Отключите все глобальные аудиоустройства**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - В верхнем меню нажмите **Tools**, затем **Websocket Server Settings**. Поставьте галочку **Enable WebSocket Server** и нажмите **OK**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> Это программа, которая управляет OBS через команды чата и автоматически переключает сцены, если поток с телефона обнаружен или потерян.

4.2.a - **Скачайте [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** для вашей системы и распакуйте в удобное место *(рекомендую создать папку Stream, а в ней подпапку NOALBS)*.  
4.2.b - В этой папке должны быть следующие 3 файла:  
 - .env  
 - config.json  
 - noalbs  

4.2.c - Чтобы NOALBS реагировал на команды чата, нужно предоставить доступ к аккаунту Twitch. Войдите в предпочитаемый аккаунт Twitch, перейдите по **[ссылке](https://b3ck.com/twitch/oauth)**, нажмите **Authorize with Twitch** и скопируйте весь код с сайта.  

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **Откройте** файл **.env** в текстовом редакторе.  
 - Замените всё скопированными данными.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - Сохраните и закройте файл.  

4.2.f - Скачайте [config.json](../config.json) отсюда и замените им локальный файл.  
 - **Откройте** файл **config.json** в текстовом редакторе.  
 - Замените все 3 вхождения *REPLACE_STREAMER_NAME* на имя вашего аккаунта Twitch.  

4.2.g - Откройте страницу **[Belabox Cloud](https://cloud.belabox.net/#relays)** и перейдите в **SRT(LA) relays**.  
 - Прокрутите вниз до **NOALBSv2 configuration**.  
 - Замените *REPLACE_BELLABOX_URL* на URL со страницы Belabox.  
 - Замените *REPLACE_BELLABOX_INGEST_KEY* на последнюю часть URL.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - Вернитесь в OBS, в настройки WebSocket, нажмите **Show Connect Info**.  
 - Скопируйте **Server Password**.  
 - Замените *REPLACE_OBS_WEBSOCKET_PASSWORD* на скопированные данные.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - Сохраните и закройте файл config.json. *Подробная информация на [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*.  
4.2.j - Запустите программу **noalbs**. Она должна выглядеть, как на изображении ниже. Ошибки также отображаются здесь.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - Вы можете создать ярлык, кликнув правой кнопкой на файл noalbs и выбрав **Create Shortcut**, затем перетащите ярлык, например, на рабочий стол для удобного доступа.  

---
# 5 - Оформление OBS
Мы завершили базовую настройку, но сцены пока пустые.  
Ниже объясняется, для чего используется каждая сцена и что обычно на них добавляют.  
> [!NOTE]  
> Это всего лишь рекомендации. Вы можете оформить сцены по своему вкусу.  

**Start (Старт)**  
- Эта сцена отображается при запуске стрима, пока телефон не выйдет в эфир.  
- Часто используют видео + музыка на фоне.  
- Простой текст "Starting Soon ..." ("Скоро начнём...").  

**Live (Эфир)**  
- Как только телефон подключается к OBS, отображается эта сцена.  
- Дополнительные элементы не нужны, так как оверлеи должны работать на телефоне.  

**Low (Низкое качество)**  
- Используется при плохом соединении с телефоном.  
- Простой текст "low bitrate" ("низкий битрейт").  

**Brb (Скоро вернусь)**  
- Активируется при полной потере соединения с телефоном или при ручном завершении стрима в IRLPro *(например, для конфиденциальности)*.  
- Часто используют старые записи или клипы *(для клипов рекомендуется создать папку Clips и добавить источник VLC Media Source, требуется [VLC Media Player](https://www.videolan.org/vlc/))*.  
- Простой текст "Be right back" ("Скоро вернусь").  
- Можно переключаться на эту сцену, если вы отошли в туалет или ведёте личный разговор.  

**End (Завершение)**  
- Активируется командой `!end` в чате Twitch.  
- Аналогично стартовой сцене: видео + музыка.  
- Простой текст "Ending Stream" ("Завершение трансляции").  

---
# 6 - Стандартная работа  
> [!NOTE]  
> Перед **каждым** IRL-стримом необходимо выполнить следующие действия:  

6.a - **Включите ПК** дома, убедитесь, что он подключён к интернету и не выключится автоматически.  
6.b - **Запустите OBS и NOALBS** на ПК.  
6.c - **Выйдите на улицу**, где планируете начать IRL-стрим.  
6.d - Введите `!start` в **чате Twitch**, чтобы начать трансляцию.  
6.e - **Запустите эфир в IRL Pro** → через несколько секунд переключитесь на сцену **Live**.  
6.f - Если вы остановили трансляцию или потеряли соединение с телефоном → через несколько секунд переключитесь на сцену **Brb**.  
6.g - Как только соединение с телефоном восстановится → через несколько секунд вернётесь на сцену **Live**.  
6.h - Вручную завершайте/запускайте трансляцию в IRLPro для переключения между `!brb` и `!live`.  
6.i - **Остановите трансляцию** автоматически при рейде или командой `!stop` в чате.  

> [!IMPORTANT]  
> При каждом изменении сцены в OBS в чате будет появляться текстовое сообщение.  

---
# 7 - Второе интернет-подключение  
> [!NOTE]  
> Это опционально, но значительно улучшает стабильность стрима. Однако это не предотвращает отключения в зонах без покрытия (например, в горах или туннелях).  

Как показано в [обзоре](#overview), можно использовать второе интернет-подключение для телефона, чтобы снизить вероятность прерывания трансляции.  
Это может быть мобильный Wi-Fi роутер или второй телефон с раздачей интернета.  

> [!IMPORTANT]  
> Для второй SIM-карты настоятельно рекомендуется использовать другого провайдера.  
> Вторая SIM-карта также будет потреблять около ~50% общего трафика.  

---
# 8 - Прямая трансляция на Twitch  

Если по какой-то причине релейный сервер или домашний ПК не работают, вы можете легко переключиться на прямую трансляцию в приложении IRL Pro.  

8.a - Перейдите в **Настройки** > **Connections**, отключите **Belabox** и включите **Twitch**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - Вернитесь в **Настройки**, затем **Video**. Прокрутите вниз и включите **Bitrate matches resolution**, а **Format** установите на Auto.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Дополнительная помощь  
### Приложение IRL  
Их [Discord](https://discord.gg/irlpro).  
### OBS  
Можно проверить их [форум](https://obsproject.com/forum/) или посмотреть один из сотен туториалов на YouTube.  
### NOALBS  
Гайд на [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) и их [Discord](https://discord.gg/efWu5HWM2u).  

---
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Хотите помочь мне?](https://ko-fi.com/naginreed)