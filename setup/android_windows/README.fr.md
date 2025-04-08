# Guide pour <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> Ces traductions ont été générées par une IA et peuvent contenir des erreurs.  
> N'hésitez pas à soumettre des corrections via une pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.x.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.x.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.x.md)

> [!TIP]
> Si vous avez choisi le mauvais OS, utilisez les boutons ci-dessus.

> [!IMPORTANT]  
> <details>
> <summary>Vous pouvez utiliser les 3 lignes en haut à droite pour accéder à n'importe quelle section du guide</summary>
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">
> </details>

---
# Informations générales
Ce guide décrit une solution **économique et simple** pour :
- un meilleur streaming **IRL**
- utiliser un **Android** comme téléphone de streaming
- utiliser un **Windows** comme PC domestique

---
## Aperçu <a id="overview" />

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">

> [!NOTE]  
> À première vue, cela semble compliqué, mais nous allons passer étape par étape avec des images *(quand disponibles)* tout au long du processus de configuration.

**Points positifs**  

- 👍 Peut être utilisé avec une seule connexion Internet depuis le téléphone
- 👍 Si la connexion du téléphone échoue, les spectateurs verront toujours des vidéos/clips (1x démarrage du stream et 1x VOD)
- 👍 Une deuxième connexion Internet peut être ajoutée pour rendre la connexion du téléphone plus fiable
- 👍 Lors du passage du WiFi au mobile et vice versa, le stream ne se coupe pas

**Points négatifs**  

- 👎 Coût mensuel supplémentaire pour le serveur relais (10 $ USD)
- 👎 Coût mensuel supplémentaire pour une 2ème connexion Internet (optionnel)
- 👎 Prend du temps pour la première configuration

---
# 1 - Téléphone de streaming  

> [!NOTE]   
> Si vous avez plusieurs téléphones, utilisez le plus puissant/récent comme téléphone de streaming

1.a - Installez **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** depuis le Google Play Store

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">

---
# 2 - Relais SRT/SRTLA

> [!NOTE]   
> Ce serveur prend les deux flux SRTLA et les combine en un seul flux SRT comme vu dans l'[Aperçu](#overview)

> [!IMPORTANT]   
> Ce service coûte 10 $ USD.

2.a - Créez un compte sur [Github](https://github.com/signup) *(si vous en avez déjà un, passez à la connexion)*
 - Vous devrez ensuite vérifier votre adresse e-mail et vous [connecter](https://github.com/login)

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">

2.b - Une fois connecté, ouvrez la page [Belabox Sponsorship](https://github.com/sponsors/rationalsa)  
 - Descendez et sélectionnez le niveau **10 $ par mois** qui inclut 1 serveur relais SRT/SRTLA
 - Remplissez vos informations de facturation et configurez votre moyen de paiement *(seulement carte de crédit ou Paypal supportés)*
 - Alternativement, vous pouvez aussi laisser vos spectateurs acheter des [bons](https://shop.belabox.net/product/belabox-cloud-voucher) pour plusieurs mois.

2.c - Une fois que vous avez sponsorisé ou obtenu un bon, ouvrez la page [Belabox Cloud](https://cloud.belabox.net) et
 - Connectez-vous/autorisez avec votre compte Github  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">

2.d - En haut de la page, appuyez sur les **3 lignes** puis **SRT(LA) relays**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">

2.e - Cliquez sur **Ajouter** et changez le nom. Changez le **Serveur** pour votre **localisation la plus proche**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">

2.f - Descendez jusqu'à voir **Paramètres Moblin** et appuyez sur le bouton **Ajouter automatiquement à Moblin** pour ajouter automatiquement les bonnes informations dans Moblin.  

---
# 3 - Téléphone de streaming
3.a - Ouvrez l'**application IRL Pro** et allez à l'icône **Engrenage** *(Paramètres)* en haut à gauche  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">

3.b - Allez dans **Connexions** où vous devriez voir **Belabox Cloud**. Appuyez sur **Nouvelle connexion**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">

3.c - Appuyez sur **TWITCH.TV** en haut et remplissez votre nom d'utilisateur et votre [clé de stream](https://dashboard.twitch.tv/settings/stream), puis sauvegardez  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">

3.d - Retournez au menu et appuyez sur **Streamer**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">

3.e - Appuyez sur **Nom d'utilisateur Twitch** et ajoutez votre nom d'utilisateur, puis OK. Descendez et entrez votre [clé API Streamlabs](https://streamlabs.com/dashboard#/settings/api-settings). *(Si vous devez changer des paramètres de chat, revenez ici)*

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">

3.f - Retournez au menu et appuyez sur **Vidéo**

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">

3.g - Allez dans **Vidéo** et configurez les paramètres suivants  
 - **Résolution:** 1920x1080p  
 - **FPS:** 30 taux fixe  
 - **Bitrate correspond à la résolution:** Désactivé  
 - **Bitrate:** 4500 kbps  
 - **Format:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">

3.h - Retournez au menu et appuyez sur **Superpositions**, puis sur **Superpositions Web**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">

3.i - Nous voulons ajouter des alertes à IRL Pro. Pour cela, nous allons dans notre tableau de bord des alertes via un navigateur  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) et copiez l'URL du widget

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">

3.j - Retournez dans IRL Pro et ajoutez une **Nouvelle superposition web**  
 - **Nom:** Alertes  
 - **URL:** Collez celle que vous avez copiée depuis Streamlabs Alertbox  
 - **Largeur:** 600  
 - **Hauteur:** 400  
*(vous pourrez ajuster plus tard si les alertes sont mal dimensionnées ou mal positionnées)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">

3.k - Une fois sauvegardé, vérifiez que les Alertes sont activées.

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">

3.l - Retournez à la **Vue principale** et **vérifiez** que le **Chat** se charge et testez que les **Alertes** **fonctionnent**  
 - Streamlabs *(Les tests d'alertes sont disponibles dans l'[Alertbox](https://streamlabs.com/dashboard#/alertbox))*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">

---
# 4 - PC Windows
N'importe quel PC ou ordinateur portable peut être utilisé, de préférence câblé directement à votre routeur Internet domestique.
 Si vous souhaitez en acheter un nouveau juste pour cette tâche, envisagez peut-être les mini-PC.
> [!WARNING]  
> Ce PC doit avoir une connexion Internet **STABLE** pendant tout le stream avec au moins 6 Mbit en upload *[Test de vitesse](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> C'est le programme qui récupère le flux du serveur relais et le reconvertit aux anciens standards RTMP/h.264 pour le diffuser directement sur Twitch. Vous avez ici de nombreuses options pour ajouter des vidéos, du texte, de la musique afin de divertir vos spectateurs pendant que vous vous reconnectez*.

4.1.a - **Téléchargez [OBS Studio](https://obsproject.com/download)** pour votre système.  
4.1.b - **Installez OBS Studio** et **lancez-le**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - Dans l'assistant automatique :
- Optimiser pour le streaming
- **Résolution :** 1920x1080
- **FPS :** 30
- **Service :** Twitch
- Connecter le compte
- Connectez-vous dans la nouvelle fenêtre qui s'ouvre.
- Décochez **Estimer le débit binaire** et entrez manuellement **5900** *(7900 si vous êtes partenaire Twitch)*
- **Terminez** l'assistant.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **Dans OBS**, en bas à gauche, **ajoutez** maintenant les **scènes** suivantes :
- Démarrage
- En direct
- Faible débit
- Brb
- Fin

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Cliquez sur la scène **En direct**, puis ajoutez une **Source média** nommée **Belabox Cloud**.
- Une nouvelle fenêtre de paramètres s'ouvrira.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - Ouvrez la page **[Belabox Cloud](https://cloud.belabox.net/#relays)**.
- Allez dans **Relais SRT(LA)**
- Faites défiler jusqu'à voir **Paramètres de source média OBS**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **Retournez dans OBS** et **configurez les mêmes paramètres** :
- Décochez **Fichier local**
- Réglez la mise en mémoire tampon réseau à 1 Mo
- Copiez l'entrée depuis la page Belabox Cloud
- Définissez le délai de reconnexion à 2S
- Cochez **Fermer le fichier lorsqu'il est inactif**.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - Faites un clic droit sur la source **Belabox Cloud**, puis **Transformation** et **Adapter à l'écran** *(ou sélectionnez-la et appuyez sur CTRL+F)*.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - Copiez *(CTRL+C)* la source **Belabox Cloud** vers la scène **Faible débit**.  
4.1.j - Allez dans **Paramètres** en bas à droite. Dans la nouvelle vidéo, sélectionnez **Audio** et **Désactivez tous les périphériques audio globaux**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - Dans la barre de menu en haut, cliquez sur **Outils**, puis sur **Paramètres du serveur WebSocket**. Cochez **Activer le serveur WebSocket** et cliquez sur **OK**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> C'est le programme qui contrôle OBS via des commandes de chat et change automatiquement les scènes si le flux du téléphone est détecté ou perdu.

4.2.a - **Téléchargez [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** pour votre système et décompressez-le à l'emplacement de votre choix *(je recommande de créer un dossier Stream puis un sous-dossier NOALBS)*.  
4.2.b - Dans ce dossier, vous devriez maintenant avoir les 3 fichiers suivants :
- .env
- config.json
- noalbs

4.2.c - Pour que NOALBS réponde à nos commandes de chat, nous devons donner accès à un compte Twitch. Une fois connecté avec votre compte préféré sur Twitch, cliquez sur ce **[lien](https://b3ck.com/twitch/oauth)**, puis sur **Autoriser avec Twitch** et copiez tout le code du site web.

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **Ouvrez** le fichier **.env** avec un éditeur de texte.
- Remplacez tout par vos données copiées.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

- Enregistrez et fermez le fichier.

4.2.f - Téléchargez le [config.json](../config.json) d'ici et remplacez-le avec votre fichier local.
- **Ouvrez** le fichier **config.json** avec un éditeur de texte.
- Remplacez les 3 occurrences de *REPLACE_STREAMER_NAME* par votre nom de compte Twitch.

4.2.g - Ouvrez la page **[Belabox Cloud](https://cloud.belabox.net/#relays)** et allez dans **Relais SRT(LA)**.
- Faites défiler jusqu'à **Configuration NOALBSv2**.
- Remplacez *REPLACE_BELLABOX_URL* par l'URL de la page Belabox.
- Remplacez *REPLACE_BELLABOX_INGEST_KEY* par la dernière partie de l'URL.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - Retournez dans OBS, dans les paramètres WebSocket, et cliquez sur **Afficher les infos de connexion**.
- Copiez le **Mot de passe du serveur**.
- Remplacez *REPLACE_OBS_WEBSOCKET_PASSWORD* par les données copiées.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - Enregistrez et fermez le fichier config.json. *Informations détaillées sur [NOALBS Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*.  
4.2.j - Lancez le programme **noalbs**. Il devrait ressembler à l'image ci-dessous. Les erreurs y sont également affichées.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - Vous pouvez créer un raccourci en faisant un clic droit sur le fichier noalbs et en cliquant sur **Créer un raccourci**, puis en glissant le raccourci sur le bureau par exemple pour un accès plus facile.  

---
# 5 - Rendre OBS joli
Nous avons terminé la configuration de base, mais les scènes sont assez vides.
Voici une explication sur l'utilisation de chaque scène et ce que les gens y mettent généralement.
> [!NOTE]  
> Ce qui suit n'est qu'une recommandation. N'hésitez pas à personnaliser comme vous le souhaitez.

**Démarrage**
- Cette scène est utilisée à chaque début de stream jusqu'à ce que le téléphone soit en direct.
- Une vidéo + musique est souvent utilisée en arrière-plan.
- Un simple texte "Démarrage bientôt...".

**En direct**
- Dès qu'une connexion du téléphone à OBS est établie, cette scène est affichée.
- Aucun élément supplémentaire n'est nécessaire, car les overlays doivent fonctionner sur le téléphone.

**Faible débit**
- Lorsque la connexion avec le téléphone est de mauvaise qualité.
- Un simple texte "Faible débit".

**Brb**
- Lorsque la connexion avec le téléphone est complètement perdue ou que vous arrêtez manuellement le stream dans IRLPro *(pour des raisons de confidentialité)*.
- D'anciens VOD ou clips sont souvent utilisés *(pour les clips, je recommande un dossier nommé Clips et d'ajouter une source média VLC *nécessite [VLC Media Player](https://www.videolan.org/vlc/)*)*.
- Un simple texte "De retour bientôt".
- Peut être activée lorsque vous allez aux toilettes ou avez une conversation privée pendant quelques minutes.

**Fin**
- Peut être activée en tapant `!end` dans le chat Twitch.
- Similaire à la vidéo de démarrage + musique.
- Un simple texte "Fin du stream".

---
# 6 - Fonctionnement normal
> [!NOTE]  
> Avant **chaque** stream IRL, vous devez effectuer les étapes suivantes.

6.a - **Allumez** votre **PC** à la maison et assurez-vous qu'il a une connexion Internet et qu'il ne s'éteint pas automatiquement.  
6.b - **Lancez OBS & NOALBS** sur votre PC.  
6.c - **Sortez** à l'endroit où vous souhaitez commencer votre stream IRL.  
6.d - Tapez `!start` dans le **chat Twitch** pour démarrer le stream sur Twitch.  
6.e - **Passez en direct dans IRL Pro** -> après quelques secondes, vous basculez vers la scène **En direct**.  
6.f - Si vous arrêtez ou perdez la connexion sur le téléphone -> après quelques secondes, vous basculez vers la scène **Brb**.  
6.g - Dès que la connexion du téléphone à Internet est rétablie -> après quelques secondes, vous revenez à la scène **En direct**.  
6.h - Arrêtez/démarrez le stream manuellement dans IRLPro pour basculer entre `!brb` et `!live`.  
6.i - **Arrêtez le stream** automatiquement si vous raidissez quelqu'un ou avec la commande chat `!stop`.  

> [!IMPORTANT]  
> À chaque changement de scène dans OBS, vous verrez un message dans le chat.
---
# 7 - 2ème connexion Internet
> [!NOTE]  
> Ceci est facultatif mais améliore grandement la stabilité du stream dans de nombreux cas. Cela ne prévient cependant pas les coupures dans les zones sans service comme les montagnes ou les tunnels.

Comme indiqué dans l'[aperçu](#overview), une 2ème connexion Internet peut être utilisée pour votre téléphone afin de réduire les risques de coupures pendant le stream en direct.  
Soit un routeur WiFi mobile, soit un deuxième téléphone avec hotspot mobile activé.  

> [!IMPORTANT]  
> Il est fortement recommandé d'utiliser un autre opérateur pour cette deuxième SIM.
> La 2ème SIM consommera également environ ~50 % des données globales.
---
# 8 - Streamer directement sur Twitch
Si pour une raison quelconque le relais ou le PC à domicile ne fonctionne pas, vous pouvez facilement revenir au streaming direct dans l'application IRL Pro.  

8.a - Allez dans **Paramètres** > **Connexions** et désactivez **Belabox** et activez **Twitch**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - Retournez dans **Paramètres**, puis **Vidéo**. Faites défiler et réactivez **Le débit binaire correspond à la résolution** et réglez le **Format** sur Auto.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Aide supplémentaire
### Application IRL
Voici leur [Discord](https://discord.gg/irlpro).
### OBS
Vous pouvez consulter leur [forum](https://obsproject.com/forum/) ou regarder l'un des centaines de tutoriels YouTube.
### NOALBS
Voici le guide sur [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) et leur [Discord](https://discord.gg/efWu5HWM2u).

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Vous voulez m'aider ?](https://ko-fi.com/naginreed)