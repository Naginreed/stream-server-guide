# Guia para <a href=""><img src="https://img.shields.io/badge/Windows-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green" height="30"></a>

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
> Estas traduções foram geradas por IA e podem conter erros.  
> Sinta-se à vontade para enviar correções via pull request.  

[![Badge-ios-win](https://img.shields.io/badge/Windows-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_windows/README.ptx.md)  
[![Badge-ios-mac](https://img.shields.io/badge/Mac-grey?logo=iOS&logoSize=auto&labelColor=blue)](../ios_mac/README.pt.md)  
[![Badge-android-mac](https://img.shields.io/badge/Mac-grey?logo=android&logoColor=white&logoSize=auto&label=Android&labelColor=green)](../android_mac/README.pt.md)  

> [!TIP]  
> Se escolheu o sistema operacional errado, use os botões acima.  

> [!IMPORTANT]  
> <details>  
> <summary>Você pode usar as 3 linhas no canto superior direito para ir para qualquer seção do guia</summary>  
> <img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/ddcfa25e-e806-48a7-9882-60fdc8794947">  
> </details>  

---  
# Informações Gerais  
Este guia descreve uma solução **Barata e Fácil** para:  
- Melhor transmissão **IRL**  
- **Android** como celular de transmissão  
- **Windows** como PC doméstico  

---  
## Visão Geral <a id="overview" />  

<img src="https://github.com/user-attachments/assets/acb012f3-b7ce-4e62-ae6b-86057db87be9" width="600">  

> [!NOTE]  
> À primeira vista, isso parece complicado, mas vamos percorrer todo o processo de configuração passo a passo com imagens *(quando disponíveis)*.  

**Pontos Positivos**  

- 👍 Pode ser usado com uma única conexão de internet do celular  
- 👍 Se a conexão do celular falhar, os espectadores ainda verão vídeos/clipes (1x início da transmissão e 1x VOD)  
- 👍 Uma segunda internet pode ser adicionada para tornar a conexão do celular mais confiável  
- 👍 Ao alternar entre WiFi e dados móveis, a transmissão não cai  

**Pontos Negativos**  

- 👎 Custo mensal adicional para o servidor de retransmissão ($10 USD)  
- 👎 Custo mensal adicional para a 2ª internet (Opcional)  
- 👎 Leva algum tempo para a configuração inicial  

---  
# 1 - Celular de Transmissão  

> [!NOTE]  
> Se tiver vários celulares, use o mais potente/novo como celular de transmissão  

1.a - Instale o **[IRL Pro](https://play.google.com/store/apps/details?id=app.irlpro.android)** na Google Play Store  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/a762e027-b75a-4d72-9667-12f7b032b98c" height="400">  

---  
# 2 - Retransmissão SRT/SRTLA  

> [!NOTE]  
> Este servidor recebe os dois fluxos SRTLA e os combina em um único fluxo SRT, como visto na [Visão Geral](#overview)  

> [!IMPORTANT]  
> Este serviço custa $10 USD.  

2.a - Crie uma conta no [Github](https://github.com/signup) *(se já tiver uma, pule para o Login)*  
 - Você precisará verificar seu e-mail e [fazer login](https://github.com/login)  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafd6a15-7ec2-4f3e-8a1f-7737e41d9a8f" height="600">  

2.b - Após o login, abra a página de [Patrocínio Belabox](https://github.com/sponsors/rationalsa)  
 - Role para baixo e selecione o plano de **$10 por mês**, que inclui 1 servidor de retransmissão SRT/SRTLA  
 - Preencha suas informações de cobrança e configure o pagamento *(apenas cartão de crédito ou Paypal)*  
 - Alternativamente, seus espectadores podem comprar [Vouchers](https://shop.belabox.net/product/belabox-cloud-voucher) para vários meses.  

2.c - Após patrocinar ou ter um voucher, abra a página [Belabox Cloud](https://cloud.belabox.net) e:  
 - Faça login/autorize com sua conta do Github  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/5385a7b6-e1c4-42ac-a5a1-729cf53dc732" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f8b19ac5-7862-4097-8701-78001048d003" height="600">  

2.d - No topo da página, pressione as **3 linhas** e depois **SRT(LA) relays**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4c33128e-253c-493e-8d40-2c19e67a2389" height="600">  

2.e - Clique em **Adicionar** e altere o nome. Mude o **Servidor** para o **local mais próximo**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/8425c1a1-add3-40d1-8082-b03312429539" height="600">  

2.f - Role para baixo até ver **Configurações Moblin** e toque no botão **Adicionar automaticamente ao Moblin** para inserir as informações corretas no Moblin.  

---  
# 3 - Celular de Transmissão  
3.a - Abra o **aplicativo IRL Pro** e vá para o símbolo de **Engrenagem** *(Configurações)* no canto superior esquerdo  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/626275d4-07ad-4d98-bc62-d89d06ec9624" width="600">  

3.b - Vá para **Conexões**, onde você deve ver o **Belabox Cloud**. Toque em **Nova conexão**.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7d4997bb-1b4d-412e-89b2-d06f12ec8516" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/d5471b2e-eb11-4020-a84c-9a6fcdd3c3dc" height="600">  

3.c - Toque em **TWITCH.TV** no topo e preencha seu nome de usuário e sua [chave de transmissão](https://dashboard.twitch.tv/settings/stream), depois salve  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/be697be2-845b-4fa9-b936-79a472b474bf" height="600">  

3.d - Volte ao menu e toque em **Streamer**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/7563e4e2-010c-4dc5-8b4e-3b8ec58db229" height="600">  

3.e - Toque em **Nome de usuário Twitch** e adicione seu nome de usuário e OK. Role para baixo e insira sua [Chave API do Streamlabs](https://streamlabs.com/dashboard#/settings/api-settings). *(Se precisar alterar configurações de chat, volte aqui)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/4883fb7a-0038-4426-b2de-c9c245f83e16" height="600">  

3.f - Volte ao menu e toque em **Vídeo**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/06bd7f40-ca4d-487c-b084-8e1a190e2bde" height="600">  

3.g - Vá para **Vídeo** e defina as seguintes configurações:  
 - **Resolução:** 1920x1080p  
 - **FPS:** 30 taxa fixa  
 - **Taxa de bits corresponde à resolução:** Desligado  
 - **Taxa de bits:** 4500 kbps  
 - **Formato:** HEVC  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/e6166d54-aa8a-4301-8afb-3a4684428f9f" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/eece480d-b620-42a5-825e-28f1b5d7b701" height="600">  

3.h - Volte ao menu e toque em **Sobreposições**, depois em **Sobreposições Web**  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/1a04874c-6158-4af1-acbb-1825b638acd4" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/8bab03e7-7b0d-4ad8-a96a-3e4ec995a504" height="600">  

3.i - Queremos adicionar alertas ao IRL Pro. Para isso, acesse o painel de alertas no navegador:  
 - [Streamlabs](https://streamlabs.com/dashboard#/alertbox) e copie o URL do Widget  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/255e3ef7-cbd5-4cfa-84a8-17d68c78ccb6" height="600">  
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/82365cc6-ade2-458f-b583-ccad4b0b62f1" height="600">  

3.j - Volte ao IRL Pro e adicione uma **Nova sobreposição web**:  
 - **Nome:** Alertas  
 - **URL:** Cole o URL copiado do Streamlabs Alertbox  
 - **Largura:** 600  
 - **Altura:** 400  
*(você pode ajustar depois se os alertas estiverem no tamanho ou posição errados)*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/c793f03a-6526-4cf1-8ca6-b10b15570d00" height="600">  
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/436e5036-a8f9-44e2-9fb6-c7e5af1d3e06" height="600">  

3.k - Após salvar, verifique se os Alertas estão ativados.  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/6bde279b-c60f-4e59-a8a6-90edfbf6685d" height="600">  

3.l - Volte para a **Tela Principal** e **verifique** se o **Chat** está carregando e teste se os **Alertas** estão **funcionando**  
 - Streamlabs *(Testes de alertas estão disponíveis no [Alertbox](https://streamlabs.com/dashboard#/alertbox))*  

<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/80417b7c-d629-44ac-b3ad-013e5eaf0842" width="600">  

---  
# 4 - PC Windows  
Qualquer PC ou notebook normal pode ser usado, de preferência conectado diretamente ao roteador de internet doméstico.  
Se quiser comprar um novo apenas para essa tarefa, considere Mini-PCs.  

> [!WARNING]  
> Este PC precisa ter uma conexão de internet **ESTÁVEL** durante toda a transmissão, com pelo menos 6Mbit de upload *[Teste de Velocidade](https://www.nperf.com)*

## 4.1 OBS
> [!NOTE]  
> Este é o programa que recebe o stream do servidor de retransmissão e o converte de volta para os padrões antigos RTMP/h.264, transmitindo-o diretamente para a Twitch. Aqui você tem várias opções para configurar vídeos, textos, músicas e entreter seus espectadores enquanto se reconecta.*

4.1.a - **Baixe o [OBS Studio](https://obsproject.com/download)** para o seu sistema  
4.1.b - **Instale o OBS Studio** e **inicie-o**.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/3555ea78-d6bd-440b-9bdc-15a91799f1a2" width="400">

4.1.c - No assistente automático:
 - Otimize para transmissão
 - **Resolução:** 1920x1080
 - **FPS:** 30
 - **Serviço:** Twitch
 - Conecte sua conta
 - Faça login na janela que aparecer.
 - Desmarque **Estimar bitrate** e insira manualmente **5900** *(7900 se você for parceiro da Twitch)*
 - **Finalize** o assistente

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/a6164a26-5ba9-4219-9c22-c2eb6abfa0e1" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/bafb9a3c-1d6e-4909-9c78-d0381c521b30" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/4bf17fc2-00ad-40b0-b262-0334f62d978a" height="400">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c7e714a3-fd5a-4783-aaff-9c82ea227f59" height="400">

4.1.d - **No OBS**, no canto inferior esquerdo, **adicione** as seguintes **cenas**:
 - Início
 - Ao Vivo
 - Baixa Qualidade
 - Brb (Volto já)
 - Fim

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/344aaedc-92df-41c1-9e65-1dd6223deb0d" width="600">

4.1.e - Clique na cena "Ao Vivo" e adicione uma **Fonte de Mídia** com o nome **Belabox Cloud**.  
 - Uma nova janela de configurações será aberta.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/dedc65b3-03c6-4ad0-a2f6-ef907ff541cc" width="600">

4.1.f - Abra a página **[Belabox Cloud](https://cloud.belabox.net/#relays)**  
 - Vá para **SRT(LA) relays** e
 - Role para baixo até ver **Configurações de Fonte de Mídia do OBS**

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/d6669e01-035c-4879-aa2e-df7ebe333b9a" width="600">

4.1.g - **Volte ao OBS** e **defina as mesmas configurações**:
 - Desmarque "Arquivo Local"
 - Defina "Buffer de Rede" para 1 MB
 - Copie a entrada da página Belabox Cloud
 - Defina "Atraso de Reconexão" para 2S
 - Marque "Fechar arquivo quando inativo"

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fb5d68c6-b45b-4b40-8f70-ad1aaf224e78" width="600">

4.1.h - Clique com o botão direito na fonte **Belabox Cloud**, depois em **Transformar** e **Ajustar à Tela** *(ou selecione e pressione CTRL+F)*  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/c993bb43-a3ea-4bc5-a75a-c46858d2305e" width="600">

4.1.i - Copie *(CTRL+C)* a fonte **Belabox Cloud** para a cena **Baixa Qualidade**  
4.1.j - Vá para **Configurações** no canto inferior direito. Na nova janela, selecione **Áudio** e **Desative todos os Dispositivos de Áudio Globais**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/20b58802-fc64-491d-9d74-3bd0aef2d93d" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/87a30f26-a525-47c2-9427-b0a1ffbe7067" width="500">

4.1.k - Na barra de menu superior, clique em **Ferramentas** e depois em **Configurações do Servidor WebSocket**. Marque **Habilitar Servidor WebSocket** e clique em **OK**  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/cec9078c-a2e2-45dc-9bec-24041f19a98f" width="500">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/918e7d93-3191-4080-b5e3-3d1c8c4b9d85" width="500">

---
## 4.2 NOALBS
> [!NOTE]  
> Este é o programa que controla o OBS por meio de comandos no chat e alterna automaticamente as cenas se o stream do telefone for detectado ou perdido.

4.2.a - **Baixe o [NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching/releases)** para o seu sistema e extraia para uma pasta de sua preferência *(recomendo criar uma pasta "Stream" e depois uma subpasta "NOALBS")*  
4.2.b - Dentro desta pasta, você deve ter os seguintes 3 arquivos:
 - .env
 - config.json
 - noalbs

4.2.c - Para o NOALBS responder aos nossos comandos no chat, precisamos conceder acesso a uma conta da Twitch. Após fazer login com sua conta preferencial na Twitch, clique neste **[Link](https://b3ck.com/twitch/oauth)**, depois em **Autorizar com Twitch** e copie todo o código do site.

<img src="https://github.com/user-attachments/assets/d668b651-5f7e-45b3-9e1a-e26eb5174b19" height="200">
<img src="https://github.com/user-attachments/assets/44ca3f4b-4ea8-47a8-868e-180fc5c62ba7" height="180">

4.2.d - **Abra** o arquivo **.env** com um editor de texto:
 - Substitua todo o conteúdo com os dados copiados.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/33dabd80-1a70-4ac1-8451-b942200767b0" height="40">

 - Salve e feche o arquivo.

4.2.f - Baixe o [config.json](../config.json) daqui e substitua o arquivo local.  
 - **Abra** o arquivo **config.json** com um editor de texto  
 - Substitua todas as 3 ocorrências de *REPLACE_STREAMER_NAME* com o nome da sua conta da Twitch.

4.2.g - Abra a página **[Belabox Cloud](https://cloud.belabox.net/#relays)** e vá para **SRT(LA) relays**  
 - Role para baixo até **Configuração NOALBSv2**  
 - Substitua *REPLACE_BELLABOX_URL* pela URL da página Belabox  
 - Substitua *REPLACE_BELLABOX_INGEST_KEY* pela última parte da URL.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/fe194e73-c223-4327-9680-af1b570869b1" height="350">

4.2.h - Volte ao OBS, nas configurações do WebSocket, e clique em **Mostrar Informações de Conexão**.  
 - Copie a **Senha do Servidor**  
 - Substitua *REPLACE_OBS_WEBSOCKET_PASSWORD* com os dados copiados.

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/ab6652a4-7ff0-41f6-8746-1290e2d243ba" height="200">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/7f04f75c-0611-43d6-8831-5fc8487981db" height="300">
<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/f16885ce-8c51-4bb4-92fa-b0e7311f3b41" height="100">

4.2.i - Salve e feche o arquivo config.json. *Informações detalhadas no [Github do NOALBS](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching)*  
4.2.j - Inicie o programa **noalbs**. Ele deve parecer com a imagem abaixo. Erros também são exibidos aqui.  

<img src="https://github.com/Naginreed/irl-cae-setup/assets/71943093/0329e383-07f3-40e8-8f80-de3d0fa3391d" height="270">

4.2.k - Você pode criar um atalho clicando com o botão direito no arquivo noalbs e selecionando **Criar Atalho**, arrastando-o, por exemplo, para a área de trabalho para acesso mais fácil.  

---
# 5 - Deixe o OBS bonito
Terminamos a configuração básica, mas as cenas estão bem vazias.  
A seguir está uma explicação sobre para que cada cena é usada e o que as pessoas normalmente adicionam.  
> [!NOTE]  
> A seguir estão apenas recomendações. Sinta-se à vontade para personalizar como quiser.

**Início**  
- Sempre que o stream começa, esta cena é exibida até o telefone ficar ao vivo.  
- Vídeo + Música são frequentemente usados como plano de fundo.  
- Texto simples "Iniciando em breve...".  

**Ao Vivo**  
- Assim que houver conexão do telefone com o OBS, esta cena será exibida.  
- Nada adicional é necessário, pois os overlays devem ser executados no telefone.  

**Baixa Qualidade**  
- Quando a conexão com o telefone está ruim.  
- Texto simples "bitrate baixo".  

**Brb (Volto já)**  
- Quando a conexão com o telefone é perdida completamente ou você encerra o stream no IRLPro intencionalmente *(por privacidade)*.  
- VODs antigos ou clipes são frequentemente usados *(para clipes, recomendo uma pasta chamada "Clipes" e adicionar uma Fonte de Mídia VLC *requer [VLC Media Player](https://www.videolan.org/vlc/)*)*.  
- Texto simples "Volto já".  
- Pode ser ativada quando você vai ao banheiro ou tem uma conversa privada por alguns minutos.  

**Fim**  
- Pode ser ativada digitando `!end` no chat da Twitch.  
- Semelhante ao vídeo/música de início.  
- Texto simples "Encerrando o stream".  

---
# 6 - Operação Normal  
> [!NOTE]  
> Antes de **cada** transmissão IRL, você precisa fazer o seguinte:  

6.a - **Ligue** seu **PC** em casa e certifique-se de que ele tenha conexão com a internet e não desligue automaticamente.  
6.b - **Inicie o OBS e o NOALBS** no seu PC.  
6.c - **Saia** para onde deseja iniciar sua transmissão IRL.  
6.d - Digite `!start` no **chat da Twitch** para iniciar o stream na Twitch.  
6.e - **Vá ao vivo no IRL Pro** -> após alguns segundos, você será alternado para a cena **Ao Vivo**.  
6.f - Se você parar ou perder a conexão no telefone -> após alguns segundos, será alternado para a cena **Brb**.  
6.g - Assim que a conexão do telefone com a internet for restaurada -> após alguns segundos, você voltará para a cena **Ao Vivo**.  
6.h - Encerre/inicie o stream manualmente no IRLPro para alternar entre `!brb` e `!live`.  
6.i - **Pare o stream** automaticamente se fizer um raid em alguém ou com o comando `!stop` no chat.  

> [!IMPORTANT]  
> Com cada mudança de cena no OBS, você verá uma mensagem de texto no chat.  

---
# 7 - 2ª Conexão de Internet  
> [!NOTE]  
> Isso é opcional e melhora muito a estabilidade do stream em muitos casos. Mas não evita quedas em áreas sem serviço, como montanhas ou túneis.  

Como visto no [Visão Geral](#overview), pode haver uma 2ª conexão de internet para o seu telefone, reduzindo a chance de quedas na transmissão ao vivo.  
Pode ser um roteador Wi-Fi móvel ou um segundo telefone com hotspot ativo.  

> [!IMPORTANT]  
> Para este segundo chip, é altamente recomendado um provedor diferente.  
> O segundo chip também consumirá cerca de ~50% do total de dados.  

---
# 8 - Transmitir diretamente para a Twitch  

Se, por algum motivo, o servidor de retransmissão ou o PC em casa não estiver funcionando, você pode facilmente voltar a transmitir diretamente no aplicativo IRL Pro.  

8.a - Vá para **Configurações** > **Conexões** e desative **Belabox** e ative **Twitch**.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/452ea3a0-76e7-4cf1-8f16-4e9f531f2923" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/45b2d58a-e62e-426f-bc2c-e0af3e1d582b" height="600"> 
</details>

8.b - Volte para **Configurações** e depois **Vídeo**. Role para baixo e ative **Bitrate corresponde à resolução** e defina **Formato** para Automático.  
<details>
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/011c5d28-461d-4c5a-a0ff-9f09bcf24de6" height="600">
<img src="https://github.com/Naginreed/irl-cae_Android-Win/assets/71943093/f2bbe20d-c1d8-408f-90c0-7e54a56b2936" height="600">
</details>

---
# 9 - Ajuda Adicional  
### Aplicativo IRL  
Aqui está o [Discord](https://discord.gg/irlpro) deles.  
### OBS  
Você pode verificar o [Fórum](https://obsproject.com/forum/) ou procurar um dos muitos tutoriais no YouTube.  
### NOALBS  
Aqui está o guia no [Github](https://github.com/NOALBS/nginx-obs-automatic-low-bitrate-switching) e o [Discord](https://discord.gg/efWu5HWM2u) deles.  

---
## Ko-Fi  
<a href="https://ko-fi.com/naginreed"><img src="https://github.com/Naginreed/irl-cae-setup-ioS/assets/71943093/29446800-fcff-4170-9ee0-7fec375ddfd8" alt="Naginreed Ko-Fi" height="60"></a><br> [Quer me ajudar?](https://ko-fi.com/naginreed)
