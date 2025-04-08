# دليل <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> هذه الترجمات تم إنشاؤها باستخدام الذكاء الاصطناعي وقد تحتوي على أخطاء.  
> يمكنك تقديم تصحيحات عبر طلب سحب (pull request).

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> إذا اخترت نظام التشغيل الخطأ، استخدم الأزرار أعلاه.

> [!IMPORTANT]  
> <details>
> <summary>يمكنك استخدام الخطوط الثلاثة في أعلى اليمين للانتقال إلى أي قسم في الدليل</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# معلومات عامة
يصف هذا الدليل حلاً **رخيصًا وسهلاً** لـ:
- تحسين بث **IRL** (في الحياة الواقعية)
- استخدام **Android** كهاتف بث
- استخدام **Windows** كحاسوب منزلي

---
## نظرة عامة <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> قد يبدو هذا معقدًا في البداية، لكننا سنشرحه خطوة بخطوة مع الصور *(عند توفرها)* خلال عملية الإعداد بأكملها.

**الإيجابيات**  

- 👍 يمكن استخدامه باتصال إنترنت واحد من الهاتف
- 👍 في حالة فشل اتصال الهاتف، سيظل المشاهدون يشاهدون مقاطع الفيديو/المقاطع (بداية بث واحدة وVOD واحد)
- 👍 يمكن إضافة اتصال إنترنت ثانٍ لتحسين موثوقية اتصال الهاتف
- 👍 عند التبديل بين الواي فاي والبيانات الخلوية، لا ينقطع البث

**السلبيات**  

- 👎 تكلفة شهرية إضافية لخادم الترحيل (10 دولار أمريكي)
- 👎 تكلفة شهرية إضافية لاتصال إنترنت ثانٍ (اختياري)
- 👎 يستغرق بعض الوقت للإعداد الأولي

---
# 1 - هاتف البث  

> [!NOTE]   
> إذا كان لديك عدة هواتف، استخدم الأقوى/الأحدث كهاتف بث

1.أ - قم بتثبيت تطبيق **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** من متجر Google Play

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - خادم SRT/SRTLA الترحيل

> [!NOTE]   
> يأخذ هذا الخادم تدفقين SRTLA ويجمعهما في تدفق SRT واحد كما هو موضح في [النظرة العامة](#overview)

> [!IMPORTANT]   
> تكلفة هذه الخدمة 10 دولار أمريكي شهريًا.

2.أ - أنشئ حسابًا على [Github](https://github.com/signup) *(إذا كان لديك حساب بالفعل، انتقل إلى تسجيل الدخول)*
 - تحتاج بعد ذلك إلى التحقق من عنوان بريدك الإلكتروني وتسجيل [الدخول](https://github.com/login)

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.ب - بعد تسجيل الدخول، افتح صفحة [رعاية Belabox](https://github.com/sponsors/rationalsa)  
 - انتقل لأسفل واختر المستوى **10 دولار شهريًا** الذي يتضمن خادم ترحيل SRT/SRTLA واحدًا
 - املأ معلومات الفواتير وحدد طريقة الدفع *(يتم دعم بطاقات الائتمان وPayPal فقط)*
 - بدلاً من ذلك، يمكنك أيضًا أن تطلب من المشاهدين شراء [قسائم](https://shop.belabox.net/product/belabox-cloud-voucher) لعدة أشهر.

2.ج - بعد أن تصبح راعيًا أو تحصل على قسيمة، افتح صفحة [Belabox Cloud](https://cloud.belabox.net) وقم بـ:
 - تسجيل الدخول/التفويض باستخدام حساب Github  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.د - في أعلى الصفحة، اضغط على **الخطوط الثلاثة** ثم **SRT(LA) relays**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.هـ - انقر على **إضافة** وغير الاسم. غيّر **الخادم** إلى **أقرب موقع لك**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.و - انتقل لأسفل حتى ترى **إعدادات Moblin** واضغط على زر **Add automatically to Moblin** لإضافة المعلومات الصحيحة تلقائيًا إلى Moblin.  

---
# 3 - هاتف البث
3.أ - افتح تطبيق **IRL Pro** وانتقل إلى رمز **الترس** *(الإعدادات)* في أعلى اليسار  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.ب - انتقل إلى **الاتصالات** حيث يجب أن ترى **Belabox Cloud**. اضغط على **اتصال جديد**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.ج - اضغط على **TWITCH.TV** في الأعلى واملأ اسم المستخدم ومفتاح البث [Streamkey](https://dashboard.twitch.tv/settings/stream) ثم اضغط على حفظ  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.د - عد إلى القائمة واضغط على **Streamer**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.هـ - اضغط على **Twitch Username** وأضف اسم المستخدم ثم موافق. انتقل لأسفل وأدخل مفتاح [Streamlabs API](https://streamlabs.com/dashboard#/settings/api-settings). *(إذا احتجت لتغيير أي إعدادات للدردشة، عد إلى هنا لاحقًا)*

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.و - عد إلى القائمة واضغط على **Video**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.ز - انتقل إلى **Video** وحدد الإعدادات التالية  
 - **الدقة:** 1920x1080p  
 - **معدل الإطارات:** 30 ثابت  
 - **معدل البت يتطابق مع الدقة:** إيقاف  
 - **معدل البت:** 4500 كيلوبت/ثانية  
 - **التنسيق:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.ح - عد إلى القائمة واضغط على **Overlays** ثم **Web Overlays**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.ط - نريد إضافة التنبيهات إلى IRL Pro. للقيام بذلك، ننتقل إلى لوحة التنبيهات عبر المتصفح  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) ونسخ رابط الـ Widget

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.ي - عد إلى IRL Pro وأضف **New web overlay**  
 - **الاسم:** التنبيهات  
 - **الرابط:** الصق الرابط الذي نسخته من Streamlabs Alertbox  
 - **العرض:** 600  
 - **الارتفاع:** 400  
*(يمكنك تعديل الحجم أو الموضع لاحقًا إذا كانت التنبيهات غير مناسبة)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.ك - بعد الحفظ، تأكد من تشغيل التنبيهات.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.ل - عد إلى **العرض الرئيسي** وتأكد من تحميل **الدردشة** وجرب أن **التنبيهات** تعمل  
 - Streamlabs *(تتوفر تنبيهات اختبار في [Alertbox](https://streamlabs.com/dashboard#/alertbox))*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - حاسوب Windows
يمكن استخدام أي حاسوب أو لابتوب عادي، ويفضل أن يكون متصلاً مباشرة بموجه الإنترنت المنزلي.
 إذا كنت ترغب في شراء جهاز جديد لهذه المهمة، قد ترغب في النظر إلى أجهزة الكمبيوتر الصغيرة.
> [!WARNING]  
> يحتاج هذا الحاسوب إلى اتصال إنترنت **مستقر** طوال مدة البث بسرعة تحميل لا تقل عن 6 ميجابت/ثانية *[اختبار السرعة](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> هذا هو البرنامج الذي يحصل على البث من خادم الترحيل ويعيد تحويله إلى معايير RTMP/h.264 القديمة ويبثه مباشرة إلى Twitch. هنا لديك الكثير من الخيارات لتعيين مقاطع الفيديو والنصوص والموسيقى لتسلية مشاهديك أثناء إعادة الاتصال*

4.1.a - **قم بتنزيل [OBS Studio](https://obsproject.com/download)** لنظامك  
4.1.b - **قم بتثبيت OBS Studio** و**تشغيله**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - في معالج التكوين التلقائي:
- تحسين للبث
- **الدقة:** 1920x1080
- **معدل الإطارات:** 30
- **الخدمة:** Twitch
- توصيل الحساب
- تسجيل الدخول في النافذة المنبثقة الجديدة.
- قم بإلغاء تحديد **تقدير معدل البت** وأدخل يدويًا **5900** *(7900 إذا كنت شريكًا في Twitch)*
- **إنهاء** المعالج

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **في OBS** في الجزء السفلي الأيسر، **أضف** الآن المشاهد التالية:
- بداية
- بث مباشر
- جودة منخفضة
- أعود قريبًا
- نهاية

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - انقر على مشهد البث المباشر، وأضف **مصدر وسائط** باسم **Belabox Cloud**.
- ستفتح نافذة جديدة بالإعدادات

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - افتح صفحة **[Belabox Cloud](https://cloud.belabox.net/#relays)**
- انتقل إلى **SRT(LA) relays**
- مرر لأسفل حتى ترى **إعدادات مصدر الوسائط لـ OBS**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **عد إلى OBS** و**اضبط** نفس الإعدادات
- ألغِ تحديد الملف المحلي
- اضبط تخزين الشبكة المؤقت على 1 ميجابايت
- انسخ الإدخال من صفحة Belabox Cloud
- اضبط تأخير إعادة الاتصال على 2 ثانية
- حدد إغلاق الملف عند عدم النشاط

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - انقر بزر الماوس الأيمن على مصدر **Belabox Cloud**، ثم **تحويل** و**ملاءمة للشاشة** *(أو حدده واضغط CTRL+F)*  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - ثم انسخ *(CTRL+C)* مصدر **Belabox Cloud** إلى مشهد **الجودة المنخفضة**  
4.1.j - انتقل إلى **الإعدادات** في الجزء السفلي الأيمن. في الفيديو الجديد، حدد **الصوت** و**تعطيل جميع أجهزة الصوت العامة**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - في شريط القائمة العلوي، انقر على **أدوات** ثم على **إعدادات خادم WebSocket**. حدد **تمكين خادم WebSocket** واضغط **موافق**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> هذا هو البرنامج الذي يتحكم في OBS عبر أوامر الدردشة ويقوم تلقائيًا بتبديل المشاهد إذا تم اكتشاف بث من الهاتف أو فقده

4.2.a - **قم بتنزيل [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** لنظامك وقم بفك ضغطه في موقع تفضله *(أوصي بإنشاء مجلد Stream ثم مجلد فرعي لـ NOALBS)*  
4.2.b - داخل هذا المجلد، يجب أن يكون لديك الآن الملفات الثلاثة التالية:
- .env
- config.json
- noalbs

4.2.c - لكي يستجيب NOALBS لأوامر الدردشة الخاصة بنا، نحتاج إلى منحه حق الوصول إلى حساب Twitch. بمجرد تسجيل الدخول باستخدام حسابك المفضل في Twitch، انقر على هذا **[الرابط](https://b3ck.com/twitch/oauth)**، ثم اضغط على **التفويض باستخدام Twitch** وانسخ الكود بالكامل من الموقع

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **افتح** ملف **.env** باستخدام محرر نصوص
- استبدل كل شيء بالبيانات التي نسختها

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

- احفظ الملف وأغلقه

4.2.f - قم بتنزيل ملف [config.json](../config.json) من هنا واستبدله بملفك المحلي.
- **افتح** ملف **config.json** باستخدام محرر نصوص  
- استبدل جميع حالات *REPLACE_STREAMER_NAME* باسم حساب Twitch الخاص بك

4.2.g - افتح صفحة **[Belabox Cloud](https://cloud.belabox.net/#relays)** وانتقل إلى **SRT(LA) relays**  
- مرر لأسفل إلى **تكوين NOALBSv2**  
- استبدل *REPLACE_BELLABOX_URL* بالرابط من صفحة Belabox  
- استبدل *REPLACE_BELLABOX_INGEST_KEY* بالجزء الأخير من الرابط  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - عد إلى OBS في إعدادات WebSocket وانقر على **عرض معلومات الاتصال**.
- انسخ **كلمة مرور الخادم**  
- استبدل *REPLACE_OBS_WEBSOCKET_PASSWORD* بالبيانات المنسوخة  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - احفظ ملف config.json وأغلقه. *معلومات مفصلة [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - ابدأ برنامج **noalbs**. يجب أن يبدو كما في الصورة أدناه. الأخطاء تظهر هنا أيضًا  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - يمكنك إنشاء اختصار بالنقر بزر الماوس الأيمن على ملف noalbs والضغط على **إنشاء اختصار** وسحب الاختصار إلى سطح المكتب على سبيل المثال لسهولة الوصول  

---
# 5 - اجعل OBS جميلًا
لقد انتهينا من الإعداد الأساسي، لكن المشاهد فارغة جدًا.
فيما يلي شرح لما يستخدم كل مشهد وما يضعه الأشخاص عادةً.
> [!NOTE]  
> التالي مجرد توصيات. يمكنك التصميم كما تريد.

**بداية**
- كل مرة يبدأ فيها البث بهذا المشهد حتى يصبح الهاتف متصلاً
- غالبًا ما يستخدم الفيديو والموسيقى كخلفية
- نص بسيط "قريبًا نبدأ ..."

**بث مباشر**
- بمجرد وجود اتصال من الهاتف إلى OBS، سيظهر هذا
- لا حاجة لأشياء إضافية، لأن التراكبات يجب أن تعمل على الهاتف

**جودة منخفضة**
- عندما يكون اتصال الهاتف بجودة سيئة
- نص بسيط "معدل بت منخفض"

**أعود قريبًا**
- عندما يفقد الاتصال بالهاتف تمامًا أو تقوم بإنهاء البث المباشر في IRLPro عن قصد *(للخصوصية)*
- غالبًا ما تستخدم مقاطع VOD القديمة أو المقاطع *(للمقاطع، أوصي بمجلد باسم Clips وإضافة مصدر وسائط VLC *يتطلب [VLC Media Player](https://www.videolan.org/vlc/)*)*
- نص بسيط "أعود قريبًا"
- يمكن التبديل إليه عندما تذهب إلى المرحاض أو لديك محادثة خاصة لبضع دقائق

**نهاية**
- يمكن تفعيله بكتابة !end في دردشة Twitch
- مشابه لفيديو البداية والموسيقى
- نص بسيط "إنهاء البث"

---
# 6 - التشغيل العادي
> [!NOTE]  
> قبل **كل** بث IRL، تحتاج إلى القيام بما يلي

6.a - **قم بتشغيل جهاز الكمبيوتر** في المنزل وتأكد من وجود اتصال بالإنترنت وأن الكمبيوتر لا يتم إيقاف تشغيله تلقائيًا  
6.b - **ابدأ OBS & NOALBS** على جهاز الكمبيوتر الخاص بك  
6.c - **اخرج** إلى المكان الذي تريد بدء بث IRL منه  
6.d - أدخل `!start` في **دردشة Twitch** لبدء البث إلى Twitch  
6.e - **ابدأ البث في IRL Pro** -> بعد بضع ثوانٍ، سيتم التبديل إلى **مشهد البث المباشر**  
6.f - إذا توقفت أو فقدت الاتصال بالهاتف -> بعد بضع ثوانٍ، سيتم التبديل إلى **مشهد أعود قريبًا**  
6.g - بمجرد استعادة الاتصال من الهاتف إلى الإنترنت -> بعد بضع ثوانٍ، سيتم العودة إلى **مشهد البث المباشر**  
6.h - قم بإنهاء/بدء البث المباشر يدويًا في IRLPro للتبديل بين `!brb` و `!live`  
6.i - **أوقف البث** تلقائيًا إذا قمت بغارة على شخص ما أو باستخدام أمر الدردشة `!stop`  

> [!IMPORTANT]  
> مع كل تغيير مشهد في OBS، سترى رسالة نصية في الدردشة
---
# 7 - اتصال إنترنت ثانٍ  
> [!NOTE]  
> هذا اختياري ويحسن استقرار البث كثيرًا في العديد من الحالات. لكنه لا يمنع الانقطاعات في المناطق التي لا توجد بها خدمة مثل الجبال العميقة أو الأنفاق.

كما هو موضح في [الملخص](#overview)، يمكن أن يكون هناك اتصال إنترنت ثانٍ لهاتفك لتقليل فرص انقطاع البث المباشر.  
إما جهاز توجيه WiFi محمول أو هاتف ثانٍ مع نقطة اتصال نشطة.  

> [!IMPORTANT]  
> يوصى بشدة بمزود خدمة مختلف لبطاقة SIM الثانية.
> ستستهلك بطاقة SIM الثانية أيضًا حوالي ~50% من إجمالي البيانات
---
# 8 - البث مباشرة إلى Twitch  

إذا كان خادم الترحيل أو الكمبيوتر المنزلي لا يعمل لأي سبب، يمكنك بسهولة العودة إلى البث المباشر في تطبيق IRL Pro.  

8.a - انتقل إلى **الإعدادات** > **الاتصالات** وقم بإيقاف **Belabox** وتشغيل **Twitch**  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - عد إلى **الإعدادات** ثم **الفيديو**. مرر لأسفل وقم بتشغيل **معدل البت يتطابق مع الدقة** مرة أخرى و**التنسيق** إلى تلقائي.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - مساعدة إضافية  
### تطبيق IRL 
هنا [Discord](https://discord.gg/irlpro) الخاص بهم
### OBS 
يمكنك التحقق من [المنتدى](https://obsproject.com/forum/) الخاص بهم أو مجرد البحث عن أحد مئات دروس اليوتيوب
### NOALBS
هنا الدليل على [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) و [Discord](https://discord.gg/efWu5HWM2u) الخاص بهم

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [هل تريد مساعدتي؟](https://ko-fi.com/naginreed)