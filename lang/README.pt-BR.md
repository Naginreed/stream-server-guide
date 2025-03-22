# Servidor de Streaming
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
> Essas traduções foram geradas por IA e podem conter erros.
> Sinta-se à vontade para enviar correções por meio de um pull request.

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)

> [!TIP]
> Pule para minha configuração fácil e econômica selecionando o sistema operacional acima.

---
## O que é um Servidor de Streaming?

No streaming IRL, muitas vezes você se encontra em situações onde deseja fazer uma pausa curta, por exemplo, para ir ao banheiro ou esconder informações sensíveis.
Você pode *encerrar a transmissão ao vivo*, mas isso fará com que você perca espectadores e criará um novo VOD toda vez que fizer isso.
O mesmo acontece sempre que você perde completamente o sinal do telefone ou fica sem bateria.

> [!NOTE]
> **Tudo o que acontece no telefone afeta diretamente sua transmissão.**

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">

Para evitar isso, muitos streamers utilizam um Servidor de Streaming.

Ele age como um intermediário entre o seu telefone e o serviço de streaming *(por exemplo, Twitch, Kick, YouTube)* e pode detectar qualquer interrupção na transmissão do telefone e, em vez disso, exibir clipes engraçados para manter os espectadores informados e entretidos.

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">

---

## 3 Versões
A escolha da versão geralmente depende de:

**💵 Quanto dinheiro você quer gastar**  
**VS**  
**🛠️⏳ Quanto tempo e esforço você quer investir**

---
## Variante A - Configuração Hospedada
A versão mais simples é alugar um Servidor de Streaming que combine todos os [Componentes](#components) e frequentemente ofereça diferentes níveis de suporte.

- **Provedores Conhecidos**  
https://comparison.dallnett.com/

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">

---
## Variante B - Configuração Híbrida
Se você tem um bom PC e uma conexão de internet estável em casa, pode mover alguns [Componentes](#components) para o seu PC pessoal para "economizar" custos mensais.

> [!WARNING]
> Isso requer conhecimento técnico e levará várias horas para configurar. Parte do suporte deverá ser feita por você mesmo.

- **Provedores Conhecidos**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">

---
## Variante C - Configuração Completa em Casa
Você pode mover todos os [Componentes](#components) para o seu PC pessoal sem custos adicionais.

> [!CAUTION]
> Isso requer **conhecimento técnico avançado** e toda a manutenção e suporte serão de sua responsabilidade.  
> Podem existir riscos de segurança se a configuração for feita incorretamente.

- **Rede:**  
IP público, DNS dinâmico, encaminhamento de portas ou configurações de firewall.
- **Servidor:**  
Instalação e manutenção de contêineres Docker, incluindo ajustes locais.
- **Contêineres Docker:**  
[Contêiner All-in-One de Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) ou [bbox-receiver de Datagutt](https://github.com/datagutt/bbox-receiver)

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">

---
## Componentes Técnicos

- **Receptor/Endpoints SRTLA:** Recebe várias conexões SRTLA e as combina em um fluxo SRT.
- **SLS:** Oferece o fluxo SRT sob demanda com um ID de stream e exibe uma página de status com informações da conexão (ex.: taxa de bits).
- **NOALBS:** Alterna cenas no OBS com base na página de status do SLS ou em comandos de chat e publica informações no chat conectado.
- **OBS:** Software de streaming em um PC ou servidor que permite a conversão entre SRT e RTMP, adicionando uma ampla gama de opções de personalização.

---
## Ko-Fi
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Quer me apoiar?](https://ko-fi.com/naginreed)

