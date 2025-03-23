# Serveur de Streaming
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
> Ces traductions ont été générées par une IA et peuvent contenir des erreurs.
> N'hésitez pas à soumettre des corrections via une pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows.README.fr.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac.README.fr.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows.README.fr.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac.README.fr.md)

> [!TIP]
> Passez à ma configuration simple et économique en sélectionnant votre système d'exploitation ci-dessus.

---
## Qu'est-ce qu'un Serveur de Streaming ?

Dans le streaming IRL, vous vous retrouvez souvent dans des situations où vous souhaitez faire une courte pause, par exemple, pour aller aux toilettes ou masquer des informations sensibles.
Vous pouvez *arrêter le livestream*, mais cela vous fera perdre des spectateurs et créera une nouvelle VOD à chaque fois.
La même chose se produit si vous perdez totalement votre signal mobile ou si votre batterie est épuisée.

> [!NOTE]
> **Tout ce qui se passe sur le téléphone affecte directement votre stream**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

Pour éviter cela, de nombreux streamers utilisent un serveur de streaming.

Il agit comme un intermédiaire entre votre téléphone et le service de streaming *(par exemple, Twitch, Kick, YouTube)* et peut détecter toute interruption du flux mobile et afficher à la place des clips amusants pour divertir et informer les spectateurs.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3 Versions
Le choix de la version dépend généralement de :

**💵 Combien d'argent souhaitez-vous dépenser**  
**VS**  
**🛠️⏳ Combien de temps et d'efforts souhaitez-vous investir**

---
## Variante A - Configuration hébergée
La version la plus simple consiste à louer un serveur de streaming qui regroupe tous les [Composants](#composants) et propose souvent différents niveaux d'assistance.

- **Fournisseurs connus**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Variante B - Configuration mixte
Si vous avez un bon PC et une bonne connexion Internet à domicile, vous pouvez déplacer certains [Composants](#composants) sur votre PC personnel pour "économiser" des coûts mensuels.
> [!WARNING]
> Cela nécessite certaines connaissances techniques et prendra plusieurs heures à configurer. Une partie du support est à votre charge.

- **Fournisseurs connus**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), et [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)  
- **Guides**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows.README.fr.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac.README.fr.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows.README.fr.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac.README.fr.md)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Variante C - Configuration complètement locale
Vous pouvez déplacer tous les [Composants](#composants) sur votre PC personnel, ce qui ne vous coûtera plus d'argent supplémentaire.
> [!CAUTION]
> Cela nécessite **des connaissances techniques avancées**, et tout le support/maintenance est à votre charge.  
> Il peut y avoir des risques de sécurité en cas de mauvaise configuration.
- **Réseau** :  
Adresse IP publique, dynDNS, redirection de port ou configuration du pare-feu.
- **Serveur** :  
Installation et maintenance des conteneurs Docker, y compris la modification des paramètres locaux.
- **Conteneurs Docker** :  
[All-in-One Container par Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) ou [bbox-receiver par Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Composants
- **SRTLA Receiver/Endpoints** : Reçoit plusieurs connexions SRTLA et les combine en un flux SRT.
- **SLS** : Fournit le flux SRT sur demande avec un ID de flux et inclut une page d'état avec des informations de connexion (ex. : débit binaire).
- **NOALBS** : Change les scènes OBS en fonction de la page d'état SLS ou des commandes de chat et affiche des informations dans le chat connecté.
- **OBS** : Logiciel de streaming sur PC ou serveur permettant la conversion entre SRT et RTMP et offrant de nombreuses options de personnalisation.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Vous voulez me soutenir ?](https://ko-fi.com/naginreed)


