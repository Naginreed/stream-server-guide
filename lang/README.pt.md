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
> Estas traduções foram geradas por IA e podem conter erros.  
> Sinta-se à vontade para enviar correções via pull request.  

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_windows/README.pt.md)
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../setup/ios_mac/README.pt.md)
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_windows/README.pt.md)
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../setup/android_mac/README.pt.md)

> [!TIP]  
> Pule para minha Configuração Barata e Fácil selecionando o SO acima.  

---  
## O que é um Stream-Server  
Em transmissões IRL, você frequentemente se depara com situações em que deseja fazer uma pausa rápida, por exemplo, para ir ao banheiro ou ocultar informações sensíveis.  
Você pode *Encerrar a Transmissão*, mas isso fará você perder espectadores e criará um novo VOD cada vez que fizer isso.  
O mesmo acontece toda vez que você perde o sinal do celular ou fica sem bateria.  

> [!NOTE]  
> **Tudo o que acontece no celular afeta diretamente sua transmissão**  

<img src="https://github.com/user-attachments/assets/13ce58f3-6930-4711-bfaf-4e7716c1d48d" width="600">  

Para evitar isso, muitos streamers usam um chamado Stream-Server.  

Eles atuam como intermediários entre seu celular e o serviço de streaming *(ex.: Twitch, Kick, YouTube)* e, portanto, podem detectar qualquer interrupção na transmissão do celular e, em vez disso, exibir alguns clipes engraçados para manter os espectadores informados e entretidos.  

<img src="https://github.com/user-attachments/assets/71fb1bfa-afe5-49f4-bc21-3f7ed7e5bc39" width="600">  

---  

# 3 Versões  
Qual versão você escolhe geralmente depende de:  

**💵 Quanto dinheiro você quer gastar**  
**VS**  
**🛠️⌛ Quanto trabalho e tempo você quer investir**  

---  
## Variante A - Configuração Hospedada  
A versão mais simples é alugar um Stream-Server que combina todos os [Componentes](#components) e frequentemente oferece diferentes níveis de suporte.  

- **Provedores Conhecidos**  
https://comparison.dallnett.com/  

<img src="https://github.com/user-attachments/assets/a586203b-726f-4dd2-a874-3f5c8e96ee16" width="600">  

---  
## Variante B - Configuração Mista  
Se você tem um PC decente e boa internet em casa, pode mover alguns [Componentes](#components) para seu PC doméstico para "economizar" custos mensais.  
> [!WARNING]  
> Isso requer algum conhecimento técnico e levará várias horas de configuração. Parte do suporte é feito por você mesmo.  

- **Provedores Conhecidos**  
[Belabox Cloud](https://cloud.belabox.net/), [IRLHosting](https://irlhosting.com/whmcs/aff.php?aff=35), [IRLServer](https://irlserver.com/), e [AntiSCUFF](https://antiscuff.com/cloud-obs-packages/)  
- **Guias**  
[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_windows)  
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](setup/ios_mac)  
[![Badge-android-win](https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_windows)  
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](setup/android_mac)  

<img src="https://github.com/user-attachments/assets/55bb4690-ce13-4f1f-b418-7426f6ddf54f" width="600">  

---  
## Variante C - Configuração Totalmente Doméstica  
Você pode mover todos os [Componentes](#components) para seu PC doméstico, o que agora custará dinheiro extra.  
> [!CAUTION]  
> Isso requer **conhecimento técnico avançado** e todo o Suporte/Manutenção é feito por você mesmo.  
> Pode haver Riscos de Segurança, se configurado incorretamente.  
- **Rede**:  
IP público, dynDNS, encaminhamento de portas ou configurações de firewall.  
- **Servidor**:  
Instalação e manutenção de contêineres Docker, incluindo alterações de configurações locais.  
- **Contêineres Docker**:  
[Contêiner All-in-One por Glowf1sh](https://hub.docker.com/r/glowf1sh/srtla-receiver) ou [bbox-receiver por Datagutt](https://github.com/datagutt/bbox-receiver)  

<img src="https://github.com/user-attachments/assets/de57944b-9fed-411d-a9c5-40b2bed001e3" width="600">  

---  
## Componentes  
- **Receptor/Endpoints SRTLA**: Recebe múltiplas conexões SRTLA e as combina em um fluxo SRT.  
- **SLS**: Oferece o fluxo SRT por solicitação com um ID de transmissão e inclui uma página de status com informações de conexão (ex.: taxa de bits).  
- **NOALBS**: Alterna cenas no OBS com base na página de status do SLS ou comandos do chat e posta informações no chat conectado.  
- **OBS**: Software de transmissão em um PC ou servidor que permite conversão entre SRT e RTMP e adiciona uma grande quantidade de opções de personalização.  

---  
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Quer me ajudar?](https://ko-fi.com/naginreed)