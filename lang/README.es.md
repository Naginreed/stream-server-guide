# Servidor de Transmisión
[![English](https://img.shields.io/badge/English-English-orange.svg)](README.md)
[![Spanish](https://img.shields.io/badge/Spanish-Español-orange.svg)](lang/README.es.md)
[![Chinese](https://img.shields.io/badge/Chinese-中文-orange.svg)](lang/README.zh-CN.md)
[![French](https://img.shields.io/badge/French-Français-orange.svg)](lang/README.fr.md)
[![German](https://img.shields.io/badge/German-Deutsch-orange.svg)](lang/README.de.md)
[![Portuguese](https://img.shields.io/badge/Portuguese-Português-orange.svg)](lang/README.pt-BR.md)
[![Japanese](https://img.shields.io/badge/Japanese-日本語-orange.svg)](lang/README.ja.md)
[![Russian](https://img.shields.io/badge/Russian-Русский-orange.svg)](lang/README.ru.md)
[![Korean](https://img.shields.io/badge/Korean-한국어-orange.svg)](lang/README.ko.md)
[![Arabic](https://img.shields.io/badge/Arabic-العربية-orange.svg)](lang/README.ar.md)

> [!WARNING]
> Estas traducciones fueron generadas utilizando IA y pueden contener errores.  
> Siéntete libre de enviar correcciones mediante un pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)

> [!TIP]
> Salta a mi configuración fácil y económica seleccionando el sistema operativo arriba.

---
## ¿Qué es un Servidor de Transmisión?

En la transmisión IRL, a menudo te encuentras en situaciones en las que deseas tomar un breve descanso, por ejemplo, para ir al baño o para ocultar información sensible.  
Puedes *finalizar la transmisión en vivo*, pero esto hará que pierdas espectadores y creará un nuevo VOD cada vez que lo hagas.  
Lo mismo sucede cada vez que pierdes toda la señal de tu teléfono o te quedas sin batería.

> [!NOTE]  
> **Todo lo que sucede en el teléfono afecta directamente tu transmisión**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

Para evitar esto, muchos streamers utilizan un llamado Servidor de Transmisión.

Estos actúan como un intermediario entre tu teléfono y el servicio de transmisión *(por ejemplo, Twitch, Kick, YouTube)*, y pueden detectar cualquier interrupción en la transmisión del teléfono y, en su lugar, mostrar clips divertidos para mantener informados y entretenidos a los espectadores.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3 Versiones
La versión que elijas depende típicamente de:

**💵 Cuánto dinero quieres gastar**  
**VS**  
**🛠️⏳ Cuánto trabajo y tiempo quieres invertir**

---
## Variante A - Configuración Hospedada
La versión más sencilla es alquilar un Servidor de Transmisión que combina todos los [Componentes](#components) y a menudo ofrece diferentes niveles de soporte.

- **Proveedores Conocidos**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Variante B - Configuración Mixta
Si tienes un buen PC e internet estable en casa, puedes mover algunos [Componentes](#components) a tu PC personal para "ahorrar" costos mensuales.

> [!WARNING]
> Esto requiere conocimientos técnicos y llevará varias horas de configuración. Parte del soporte lo harás tú mismo.

- **Proveedores Conocidos**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Variante C - Configuración Completa en Casa
Puedes mover todos los [Componentes](#components) a tu PC personal sin costos adicionales.

> [!CAUTION]
> Esto requiere **conocimientos técnicos avanzados** y todo el soporte/mantenimiento lo harás tú mismo.  
> Podría haber riesgos de seguridad si la configuración no es correcta.

- **Red:**  
IP pública, dynDNS, reenvío de puertos o configuración de firewall.
- **Servidor:**  
Instalación y mantenimiento de contenedores Docker, incluidos ajustes locales.
- **Contenedores Docker:**  
[All-in-One Container by Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) o [bbox-receiver by Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Componentes Técnicos

- **SRTLA Receiver/Endpoints:** Recibe múltiples conexiones SRTLA y las combina en una transmisión SRT.
- **SLS:** Ofrece la transmisión SRT bajo petición con un ID de transmisión y muestra una página de estado con información de conexión (por ejemplo, bitrate).
- **NOALBS:** Cambia escenas en OBS según la página de estado de SLS o comandos de chat y publica información en el chat.
- **OBS:** Software de transmisión en un PC o servidor que permite la conversión entre SRT y RTMP, agregando muchas opciones de personalización.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [¿Quieres ayudarme?](https://ko-fi.com/naginreed)

