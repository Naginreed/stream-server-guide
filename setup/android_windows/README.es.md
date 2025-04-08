# Guía para <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> Estas traducciones fueron generadas con IA y pueden contener errores.  
> Siéntete libre de enviar correcciones mediante un pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> Si seleccionaste el sistema operativo incorrecto, usa los botones de arriba.

> [!IMPORTANT]  
> <details>
> <summary>Puedes usar las 3 líneas en la esquina superior derecha para saltar a cualquier sección de la guía</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# Información General
Esta guía describe una solución **económica y sencilla** para:
- Mejorar la transmisión **en vivo (IRL)**.
- Usar **Android** como teléfono de transmisión.
- Usar **Windows** como PC de casa.

---
## Resumen <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> A primera vista, esto parece complicado, pero iremos paso a paso con imágenes *(cuando estén disponibles)* durante todo el proceso de configuración.

**Ventajas**  

- 👍 Puede usarse con una sola conexión a Internet desde el teléfono.
- 👍 Si la conexión del teléfono falla, los espectadores seguirán viendo videos/clips (1 inicio de transmisión y 1 VOD).
- 👍 Se puede agregar una segunda conexión a Internet para hacer la conexión del teléfono más confiable.
- 👍 Al cambiar de WiFi a móvil y viceversa, la transmisión no se interrumpe.

**Desventajas**  

- 👎 Costo mensual adicional por el servidor de retransmisión ($10 USD).
- 👎 Costo mensual adicional por una segunda conexión a Internet (opcional).
- 👎 Requiere tiempo para la configuración inicial.

---
# 1 - Teléfono de Transmisión  

> [!NOTE]   
> Si tienes varios teléfonos, usa el más potente/nuevo como teléfono de transmisión.

1.a - Instala **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** desde Google Play Store.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - Retransmisión SRT/SRTLA

> [!NOTE]   
> Este servidor toma los dos flujos SRTLA y los combina en un solo flujo SRT, como se muestra en el [Resumen](#overview).

> [!IMPORTANT]   
> Este servicio cuesta $10 USD.

2.a - Crea una cuenta en [Github](https://github.com/signup) *(si ya tienes una, inicia sesión)*.
 - Luego, verifica tu dirección de correo electrónico y [inicia sesión](https://github.com/login).

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - Una vez iniciada sesión, abre la página de [Patrocinio de Belabox](https://github.com/sponsors/rationalsa).  
 - Desplázate hacia abajo y selecciona el nivel de **$10 al mes**, que incluye 1 servidor de retransmisión SRT/SRTLA.
 - Completa tu información de facturación y configura tu método de pago *(solo se aceptan tarjetas de crédito o PayPal)*.
 - Alternativamente, también puedes pedir a tus espectadores que compren [vouchers](https://shop.belabox.net/product/belabox-cloud-voucher) para varios meses.

2.c - Una vez que hayas patrocinado o tengas un voucher, abre la página de [Belabox Cloud](https://cloud.belabox.net) y:
 - Inicia sesión/autoriza con tu cuenta de Github.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - En la parte superior de la página, presiona las **3 líneas** y luego **SRT(LA) relays**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - Haz clic en **Add** y cambia el nombre. Cambia el **Server** a tu **ubicación más cercana**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - Desplázate hacia abajo hasta ver **Moblin Settings** y toca el botón **Add automatically to Moblin** para agregar automáticamente la información correcta en Moblin.  

---
# 3 - Teléfono de Transmisión
3.a - Abre la **aplicación IRL Pro** y ve al símbolo de **Engranaje** *(Configuración)* en la esquina superior izquierda.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - Ve a **Connections**, donde deberías ver **Belabox Cloud**. Toca en **New connection**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - Toca en **TWITCH.TV** en la parte superior y completa tu nombre de usuario y tu [Streamkey](https://dashboard.twitch.tv/settings/stream), luego guarda.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - Regresa al menú y toca **Streamer**.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - Toca **Twitch Username** y agrega tu nombre de usuario y acepta. Desplázate hacia abajo e ingresa tu [Clave API de Streamlabs](https://streamlabs.com/dashboard#/settings/api-settings). *(Si necesitas cambiar configuraciones del chat, vuelve aquí)*.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - Regresa al menú y toca **Video**.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - Ve a **Video** y configura lo siguiente:  
 - **Resolución:** 1920x1080p  
 - **FPS:** 30 fps fijos  
 - **Bitrate matches resolution:** Desactivado  
 - **Bitrate:** 4500 kbps  
 - **Formato:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - Regresa al menú y toca **Overlays**, luego **Web Overlays**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - Queremos agregar alertas a IRL Pro. Para esto, vamos al panel de alertas en el navegador:  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) y copia la URL del widget.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - Regresa a IRL Pro y agrega un **New web overlay**:  
 - **Nombre:** Alertas  
 - **URL:** Pega la que copiaste de Streamlabs Alertbox  
 - **Ancho:** 600  
 - **Alto:** 400  
*(puedes ajustar esto más tarde si las alertas tienen un tamaño o posición incorrectos)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - Una vez guardado, verifica que las alertas estén activadas.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - Regresa a la **vista principal** y **verifica** que el **chat** se cargue y prueba que las **alertas** **funcionen**.  
 - Streamlabs *(las alertas de prueba están disponibles en [Alertbox](https://streamlabs.com/dashboard#/alertbox))*.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - PC con Windows
Cualquier PC o portátil normal puede usarse, preferiblemente conectado directamente al router de tu casa.  
Si quieres comprar uno nuevo solo para esta tarea, considera mini-PCs.  
> [!WARNING]  
> Esta PC necesita una conexión a Internet **ESTABLE** durante toda la transmisión con al menos 6Mbit de subida *[Speedtest](https://www.nperf.com)*.  

## 4.1 OBS
> [!NOTE]  
> Este es el programa que recibe el stream del servidor de retransmisión y lo convierte de vuelta a los estándares antiguos RTMP/h.264, transmitiéndolo directamente a Twitch. Aquí tienes muchas opciones para configurar videos, texto, música y entretener a tus espectadores mientras te reconectas*.

4.1.a - **Descarga [OBS Studio](https://obsproject.com/download)** para tu sistema.  
4.1.b - **Instala OBS Studio** y **inícialo**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - En el asistente automático:
 - Optimizar para streaming.
 - **Resolución:** 1920x1080.
 - **FPS:** 30.
 - **Servicio:** Twitch.
 - Conectar cuenta.
 - Inicia sesión en la ventana emergente.
 - Desmarca **Estimar bitrate** e ingresa manualmente **5900** *(7900 si eres Partner de Twitch)*.
 - **Finaliza** el asistente.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **En OBS**, en la parte inferior izquierda, **añade** las siguientes **escenas**:
 - Inicio.
 - En vivo.
 - Baja calidad.
 - Brb (Volveré pronto).
 - Fin.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Haz clic en la escena "En vivo" y añade una **Fuente de medios** con el nombre **Belabox Cloud**.  
 - Se abrirá una nueva ventana con configuraciones.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - Abre la página **[Belabox Cloud](https://cloud.belabox.net/#relays)**.  
 - Ve a **Relays SRT(LA)**.
 - Desplázate hacia abajo hasta ver **Configuración de fuente de medios para OBS**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **Regresa a OBS** y **configura los mismos parámetros**:
 - Desmarca "Archivo local".
 - Establece el búfer de red en 1 MB.
 - Copia la entrada de la página de Belabox Cloud.
 - Establece el retraso de reconexión en 2 segundos.
 - Marca "Cerrar archivo cuando esté inactivo".

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - Haz clic derecho en la fuente **Belabox Cloud**, luego **Transformar** y **Ajustar a pantalla** *(o selecciónala y presiona CTRL+F)*.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - Luego copia *(CTRL+C)* la fuente **Belabox Cloud** y pégala en la escena **Baja calidad**.  
4.1.j - Ve a **Configuración** en la esquina inferior derecha. En el nuevo video, selecciona **Audio** y **Desactiva todos los dispositivos de audio globales**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - En la barra de menú superior, haz clic en **Herramientas** y luego en **Configuración del servidor WebSocket**. Marca **Habilitar servidor WebSocket** y haz clic en **Aceptar**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> Este es el programa que controla OBS mediante comandos de chat y cambia automáticamente las escenas si se detecta o pierde la transmisión desde el teléfono.

4.2.a - **Descarga [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** para tu sistema y descomprímelo en una ubicación de tu preferencia *(recomiendo crear una carpeta "Stream" y dentro una subcarpeta "NOALBS")*.  
4.2.b - Dentro de esta carpeta deberías tener ahora los siguientes 3 archivos:
 - .env
 - config.json
 - noalbs

4.2.c - Para que NOALBS responda a nuestros comandos de chat, necesitamos dar acceso a una cuenta de Twitch. Una vez que inicies sesión con tu cuenta preferida en Twitch, haz clic en este **[enlace](https://b3ck.com/twitch/oauth)**, luego en **Autorizar con Twitch** y copia todo el código del sitio web.

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **Abre** el archivo **.env** con un editor de texto.
 - Reemplaza todo con los datos copiados.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - Guarda y cierra el archivo.

4.2.f - Descarga el [config.json](../config.json) desde aquí y reemplázalo con tu archivo local.  
 - **Abre** el archivo **config.json** con un editor de texto.  
 - Reemplaza las 3 veces donde dice *REPLACE_STREAMER_NAME* con tu nombre de cuenta de Twitch.

4.2.g - Abre la página **[Belabox Cloud](https://cloud.belabox.net/#relays)** y ve a **Relays SRT(LA)**.  
 - Desplázate hacia abajo hasta **Configuración de NOALBSv2**.  
 - Reemplaza *REPLACE_BELLABOX_URL* con la URL de la página de Belabox.  
 - Reemplaza *REPLACE_BELLABOX_INGEST_KEY* con la última parte de la URL.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - Regresa a OBS, ve a la configuración de WebSocket y haz clic en **Mostrar información de conexión**.  
 - Copia la **Contraseña del servidor**.  
 - Reemplaza *REPLACE_OBS_WEBSOCKET_PASSWORD* con los datos copiados.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - Guarda y cierra el archivo config.json. *Más detalles en [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*.  
4.2.j - Inicia el programa **noalbs**. Debería verse como en la imagen de abajo. Los errores también se mostrarán aquí.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - Puedes crear un acceso directo haciendo clic derecho en el archivo noalbs y seleccionando **Crear acceso directo**, luego arrástralo, por ejemplo, al escritorio para un acceso más fácil.  

---
# 5 - Haz que OBS se vea bien
Hemos terminado con la configuración básica, pero las escenas están bastante vacías.  
A continuación, una explicación de para qué se usa cada escena y lo que la gente suele incluir.  
> [!NOTE]  
> Lo siguiente son solo recomendaciones. Siéntete libre de diseñar como prefieras.

**Inicio**  
- Cada vez que el stream comienza, se usa esta escena hasta que el teléfono esté en vivo.  
- A menudo se usa un video + música de fondo.  
- Texto simple: "Comenzando pronto...".  

**En vivo**  
- Tan pronto como haya conexión desde el teléfono a OBS, se mostrará esta escena.  
- No se necesitan elementos adicionales, ya que las superposiciones deben ejecutarse en el teléfono.  

**Baja calidad**  
- Cuando la conexión con el teléfono es de mala calidad.  
- Texto simple: "Bajo bitrate".  

**Brb (Volveré pronto)**  
- Cuando la conexión con el teléfono se pierde por completo o detienes la transmisión en IRLPro a propósito *(por privacidad)*.  
- A menudo se usan VODs antiguos o clips *(para clips, recomiendo una carpeta llamada "Clips" y añadir una fuente de medios VLC *requiere [VLC Media Player](https://www.videolan.org/vlc/)*)*.  
- Texto simple: "Volveré pronto".  
- Puede activarse cuando vas al baño o tienes una conversación privada por unos minutos.  

**Fin**  
- Se puede activar escribiendo `!end` en el chat de Twitch.  
- Similar al video + música de inicio.  
- Texto simple: "Terminando la transmisión".  

---
# 6 - Operación normal  
> [!NOTE]  
> Antes de **cada** transmisión IRL, debes hacer lo siguiente:  

6.a - **Enciende tu PC** en casa y asegúrate de que tenga conexión a Internet y que no se apague automáticamente.  
6.b - **Inicia OBS y NOALBS** en tu PC.  
6.c - **Sal** al lugar donde quieras comenzar tu transmisión IRL.  
6.d - Escribe `!start` en el **chat de Twitch** para comenzar la transmisión en Twitch.  
6.e - **Transmite en vivo en IRL Pro** -> después de unos segundos, cambiarás a la escena **En vivo**.  
6.f - Si detienes o pierdes la conexión desde el teléfono -> después de unos segundos, cambiarás a la escena **Brb**.  
6.g - Tan pronto como se restablezca la conexión del teléfono a Internet -> después de unos segundos, volverás a la escena **En vivo**.  
6.h - Detén/inicia la transmisión manualmente en IRLPro para cambiar entre `!brb` y `!live`.  
6.i - **Detén la transmisión** automáticamente si haces un raid o con el comando de chat `!stop`.  

> [!IMPORTANT]  
> Con cada cambio de escena en OBS, verás un mensaje de texto en el chat.  

---
# 7 - Segunda conexión a Internet  
> [!NOTE]  
> Esto es opcional y mejora mucho la estabilidad de la transmisión en muchos casos. Pero no evita cortes en zonas sin servicio, como montañas profundas o túneles.  

Como se ve en el [Resumen](#overview), puede haber una segunda conexión a Internet para tu teléfono para reducir la posibilidad de cortes en la transmisión en vivo.  
Puede ser un router WiFi móvil o un segundo teléfono con hotspot activo.  

> [!IMPORTANT]  
> Para esta segunda SIM, se recomienda encarecidamente un proveedor diferente.  
> La segunda SIM también consumirá aproximadamente ~50% del total de datos.  

---
# 8 - Transmitir directamente a Twitch  

Si por alguna razón el servidor de retransmisión o el PC en casa no funcionan, puedes volver fácilmente a la transmisión directa en la aplicación IRL Pro.  

8.a - Ve a **Configuración** > **Conexiones** y desactiva **Belabox** y activa **Twitch**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - Regresa a **Configuración**, luego a **Video**. Desplázate hacia abajo y activa **El bitrate coincide con la resolución** y establece **Formato** en Automático.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Ayuda adicional  
### Aplicación IRL  
Aquí está su [Discord](https://discord.gg/irlpro).  
### OBS  
Puedes consultar su [Foro](https://obsproject.com/forum/) o buscar uno de los cientos de tutoriales en YouTube.  
### NOALBS  
Aquí está la guía en [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) y su [Discord](https://discord.gg/efWu5HWM2u).  

---
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [¿Quieres ayudarme?](https://ko-fi.com/naginreed)