<!--
    title: Voice-Pro: Ferramenta definitiva de conversão de voz AI e tradução multilíngue
    description: Poderoso aplicativo da web com tecnologia AI para processamento de vídeo do YouTube, reconhecimento de fala, tradução e texto para fala com suporte multilíngue
    keywords: Conversão de voz AI, tradução do YouTube, geração de legendas, fala para texto, texto para fala, clonagem de voz, tradução multilíngue, Alternativa ElevenLabs
    author: ABUS
    version: 2.0.0
    last-updated: 2025-02-23
    product-type: Software de processamento multimídia AI
    platforms: Windows
    technology-stack: Whisper, Edge-TTS, Gradio, CUDA, Faster-Whisper, Whisper-Timestamped, E2-TTS, F5-TTS, YouTube Downloader, Demucs, MDX-Net, RVC, CosyVoice, kokoro
    license: LGPL
-->

<h1 align="center">
Voice-Pro
</h1>

<p align="center">
  <i align="center">A melhor solução de reconhecimento de voz, tradução e dublagem multilíngue com IA 🚀</i>
</p>

<h4 align="center">
  <a href="https://www.youtube.com/channel/UCbCBWXuVbk-OBp9T4H5JjAA">
    <img src="https://img.shields.io/badge/youtube-d95652.svg?style=flat-square&logo=youtube" alt="youtube" style="height: 20px;">
  </a>
  <a href="https://www.amazon.com/dp/B0F1LQZ42T">
    <img src="https://img.shields.io/badge/Amazon-f90.svg?style=flat-square&logo=amazon&logoColor=white" alt="Amazon" style="height: 20px;">
  </a>
  <a href="https://r17wvy-t2.myshopify.com">
    <img src="https://img.shields.io/badge/Shopify-7ab55c.svg?style=flat-square&logo=shopify&logoColor=white" alt="Shopify" style="height: 20px;">
  </a>
    <a href="https://www.buymeacoffee.com/abus">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" style="height: 20px;">
  </a>
  <a href="https://github.com/abus-aikorea/voice-pro/releases">
    <img src="https://img.shields.io/github/v/release/abus-aikorea/voice-pro" alt="release" style="height: 20px;">
  </a>
</h4>

<p align="center">
    <img src="images/main_page_crop.por.jpg?raw=true" alt="Dubbing Studio"/>
</p>
<br />


## 🎙️ Um aplicativo web baseado em IA para reconhecimento de voz, tradução e dublagem


<p>  
  <a href="README.kor.md">
    <img src="https://flagcdn.com/16x12/kr.png" alt="South Korea Flag" style="vertical-align: middle;"> 한국어
  </a> ∙ 
  <a href="README.eng.md">
    <img src="https://flagcdn.com/16x12/us.png" alt="United Kingdom Flag" style="vertical-align: middle;"> English
  </a> ∙ 
  <a href="README.zh.md">
    <img src="https://flagcdn.com/16x12/cn.png" alt="China Flag" style="vertical-align: middle;"> 中文简体
  </a> ∙ 
  <a href="README.tw.md">
    <img src="https://flagcdn.com/16x12/tw.png" alt="Taiwan Flag" style="vertical-align: middle;"> 中文繁體
  </a> ∙ 
  <a href="README.jpn.md">
    <img src="https://flagcdn.com/16x12/jp.png" alt="Japan Flag" style="vertical-align: middle;"> 日本語
  </a> ∙ 
  <a href="README.deu.md">
    <img src="https://flagcdn.com/16x12/de.png" alt="Germany Flag" style="vertical-align: middle;"> Deutsch
  </a> ∙ 
  <a href="README.spa.md">
    <img src="https://flagcdn.com/16x12/es.png" alt="Spain Flag" style="vertical-align: middle;"> Español
  </a> ∙ 
  <a href="README.por.md">
    <img src="https://flagcdn.com/16x12/pt.png" alt="Portugal Flag" style="vertical-align: middle;"> Português
  </a>
</p>

Voice-Pro é um aplicativo web de ponta que transforma a criação de conteúdo multimídia. Ele integra download de vídeos do YouTube, separação de voz, reconhecimento de fala, tradução e conversão de texto em fala (TTS) em uma única ferramenta poderosa, oferecendo uma solução ideal para criadores, pesquisadores e profissionais multilíngues.

- 🔊 Reconhecimento de fala de alto nível: **Whisper**, **Faster-Whisper**, **Whisper-Timestamped**, **WhisperX**
- 🎤 Clonagem de voz Zero-Shot: **F5-TTS**, **E2-TTS**, **CosyVoice**
- 📢 Conversão de texto em fala multilíngue: **Edge-TTS**, **kokoro**
- 🎥 Processamento de vídeos do YouTube e extração de áudio: **yt-dlp**
- 🌍 Tradução instantânea para mais de 100 idiomas: **Deep-Translator**


Como uma alternativa robusta ao **ElevenLabs**, o Voice-Pro capacita podcasters, desenvolvedores e criadores com soluções de voz avançadas.

## ⚠️ Por favor, note
- **Atualização de v2.x para v3.x**: Não é possível. Recomendamos excluir a pasta `installer_files` e executar a versão mais recente do `start.bat`.
- **Atualização de v3.x para v3.x**: Possível. Após baixar o código mais recente, execute `update.bat`.
- **Usuários iniciantes**: Consulte as instruções de instalação abaixo.
- **Resolução de problemas**: Na maioria dos casos, os problemas podem ser resolvidos excluindo a pasta `installer_files` e, em seguida, executando `configure.bat` seguido por `start.bat`.

## 📰 Notícias e Histórico

<details open>
<summary>Versão 3.0</summary>

- 🔥 A função **AI Cover** foi removida.  
- 🚀 Suporte para **m-bain/whisperX** foi adicionado.  

</details>

<details>
<summary>Versão 2.0</summary>

- 🐍 Construído com Python 3.10.15, Torch 2.5.1+cu124 e Gradio 5.14.0.  
- 🆓 A versão de teste gratuita suporta mídias de até **60 segundos** de duração.  
- 🔥 A função **AI Cover** foi adicionada.  
- 🎤 Suporte para **CosyVoice** e **kokoro** foi introduzido.  
- ⏳ A primeira execução baixa **CozyVoice2-0.5B (9GB)**, o que pode levar mais de uma hora dependendo da velocidade da rede.  
- 🎧 Amostras de voz para clonagem serão atualizadas continuamente.  
- 📝 **spaCy** foi adicionado para tradução e TTS naturais por sentença.  
- ☁️ A versão por assinatura inclui o tradutor e TTS do **Microsoft Azure**.  
- 🏪 A versão por assinatura oferece **uso ilimitado** (sem limite de 60 segundos) durante o período de assinatura e pode ser adquirida no [**Shopify**](https://r17wvy-t2.myshopify.com).  

</details>

## ▶️ Demonstrações

### Aba `Estúdio de Dublagem`: Transcrição, Tradução e TTS
<div aria-labelledby="studio-demo-description">
  <video src="https://github.com/user-attachments/assets/1cf084a4-3286-4055-86d2-238ed179560e"
   width="100%" 
   style="max-width: 720px;" 
   controls="controls" 
   muted="muted"
   aria-describedby="studio-demo-description2">
   </video>

  <p id="studio-demo-description">Demonstração do fluxo de trabalho completo de processamento de mídia na aba Estúdio: Mostra um processo contínuo de transformação de mídia, desde o download de vídeos do YouTube até a separação de vozes por IA, legendas automáticas com Whisper, tradução multilíngue e dublagem profissional usando F5-TTS.</p>
</div>

### Aba `F5-TTS-Multi`: Criação de Podcasts
<div aria-labelledby="tts-demo-description">
  <video src="https://github.com/user-attachments/assets/2d4b7d84-ca19-4efd-a847-a66fa0db616e" width="100%" style="max-width: 720px;" controls muted aria-describedby="tts-demo-description"></video>
  <p id="tts-demo-description">Demonstração da tecnologia inovadora de clonagem de voz por IA do F5-TTS: Apresenta uma tecnologia avançada de conversão de voz que imita precisamente as vozes reais de Mark Zuckerberg e Elon Musk para criar conteúdos totalmente novos.</p>
</div>

### Aba `Tradução ao Vivo`: Reconhecimento e Tradução em Tempo Real
<div aria-labelledby="translate-demo-description">
  <video src="https://github.com/user-attachments/assets/eb53dd3a-df0a-4f7f-819c-cf92d477e2d1" width="100%" style="max-width: 720px;" controls muted aria-describedby="translate-demo-description"></video>
  <p id="translate-demo-description">Demonstração da função de tradução multilíngue em tempo real: Apresenta um processo inovador de processamento de mídia multilíngue que captura instantaneamente conteúdos de notícias da BBC, gera legendas em tempo real e as traduz imediatamente para outros idiomas.</p>
</div>

## ⭐ Recursos principais

### 1. Estúdio de dublagem
- Downloads de vídeos do YouTube e extração de áudio
- Separação de vozes com **Demucs**
- Suporta mais de 100 idiomas para reconhecimento e tradução de fala

### 2. Tecnologias de fala
- **Fala para texto:** **Whisper**, **Faster-Whisper**, **Whisper-Timestamped**, **WhisperX**
- **Texto para fala:** 
  - **Edge-TTS**: Mais de 100 idiomas, 400+ vozes
  - **E2-TTS**, **F5-TTS**, **CosyVoice**: Clonagem sem treinamento prévio
  - **kokoro**: Classificado como #2 na Arena TTS do HuggingFace

### 3. Tradução em tempo real
- Reconhecimento instantâneo de fala
- Tradução multilíngue em tempo real
- Entradas de áudio personalizáveis


## 🤖 Interface Web

### Aba `Estúdio de Dublagem`
- Centro integrado: Downloads do YouTube, remoção de ruído, legendas, tradução e TTS
- Suporta todos os formatos compatíveis com ffmpeg
- Opções de saída: WAV, FLAC, MP3
- Legendas e reconhecimento para mais de 100 idiomas
- TTS com ajustes de velocidade, volume e tom
<p align="center"><img style="width: 90%; height: 90%" src="images/main_page.por.jpg?raw=true" alt="Interface Web de Conversão de Voz Multilíngue e Geração de Legendas"/></p>

### Aba `Legendas Whisper`
- Foco em legendas: Mais de 90 idiomas
- Exibição de legendas integrada ao vídeo
- Destaque por palavra e opções de remoção de ruído

### Aba `Tradução`
- Tradução para mais de 100 idiomas
- Suporte a arquivos de legendas (ASS, SSA, SRT, etc.)
- Reconhecimento e tradução de voz em tempo real
<p align="center"><img style="width: 90%; height: 90%" src="images/live_translation_bbc.jpg?raw=true" alt="Interface Web para Reconhecimento de Fala e Tradução em Tempo Real"/></p>

### Aba `Geração de Voz`
- Opções: **Edge-TTS**, **F5-TTS**, **CosyVoice**, **kokoro**
- Podcasts com vozes de celebridades e suporte multilíngue
<p align="center"><img style="width: 90%; height: 90%" src="images/tts_f5_multi.jpg?raw=true" alt="Interface Web para Produção de Podcasts usando Tecnologia de Clonagem de Voz"/></p>


## 🎤✨ Voz de referência

- Por favor, solicite a voz que você deseja adicionar na página de Issues. [Issues](https://github.com/abus-aikorea/voice-pro/issues/50)

<details>
<summary>
English
</summary> <br />

<table>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Andrew Bustamante.jpg" width="150"><br>Andrew Bustamante</td>
    <td align="center"><img src="celebrities30sREADME/English/Andrew Huberman.jpg" width="150"><br>Andrew Huberman</td>
    <td align="center"><img src="celebrities30sREADME/English/Avi Loeb.jpg" width="150"><br>Avi Loeb</td>
    <td align="center"><img src="celebrities30sREADME/English/Ben Shapiro.jpg" width="150"><br>Ben Shapiro</td>
    <td align="center"><img src="celebrities30sREADME/English/Brett Johnson.jpg" width="150"><br>Brett Johnson</td>
    <td align="center"><img src="celebrities30sREADME/English/Brian Keating.jpg" width="150"><br>Brian Keating</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Coffeezilla.jpg" width="150"><br>Coffeezilla</td>
    <td align="center"><img src="celebrities30sREADME/English/Dan Carlin.jpg" width="150"><br>Dan Carlin</td>
    <td align="center"><img src="celebrities30sREADME/English/David Buss.jpg" width="150"><br>David Buss</td>
    <td align="center"><img src="celebrities30sREADME/English/David Fravor.jpg" width="150"><br>David Fravor</td>
    <td align="center"><img src="celebrities30sREADME/English/David Kipping.jpg" width="150"><br>David Kipping</td>
    <td align="center"><img src="celebrities30sREADME/English/Dennis Whyte.jpg" width="150"><br>Dennis Whyte</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Donald Hoffman.jpg" width="150"><br>Donald Hoffman</td>
    <td align="center"><img src="celebrities30sREADME/English/Donald Trump.jpg" width="150"><br>Donald Trump</td>
    <td align="center"><img src="celebrities30sREADME/English/Douglas Murray.jpg" width="150"><br>Douglas Murray</td>
    <td align="center"><img src="celebrities30sREADME/English/Duncan Trussell.jpg" width="150"><br>Duncan Trussell</td>
    <td align="center"><img src="celebrities30sREADME/English/Elon Musk.jpg" width="150"><br>Elon Musk</td>
    <td align="center"><img src="celebrities30sREADME/English/Garry Nolan.jpg" width="150"><br>Garry Nolan</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Jack Barsky.jpg" width="150"><br>Jack Barsky</td>
    <td align="center"><img src="celebrities30sREADME/English/James Sexton.jpg" width="150"><br>James Sexton</td>
    <td align="center"><img src="celebrities30sREADME/English/Jeff Bezos.jpg" width="150"><br>Jeff Bezos</td>
    <td align="center"><img src="celebrities30sREADME/English/Joe Rogan.jpg" width="150"><br>Joe Rogan</td>
    <td align="center"><img src="celebrities30sREADME/English/John Mearsheimer.jpg" width="150"><br>John Mearsheimer</td>
    <td align="center"><img src="celebrities30sREADME/English/Jordan Peterson.jpg" width="150"><br>Jordan Peterson</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Kanye 'Ye' West.jpg" width="150"><br>Kanye 'Ye' West</td>
    <td align="center"><img src="celebrities30sREADME/English/Mark Zuckerberg.jpg" width="150"><br>Mark Zuckerberg</td>
    <td align="center"><img src="celebrities30sREADME/English/Michael Levin.jpg" width="150"><br>Michael Levin</td>
    <td align="center"><img src="celebrities30sREADME/English/Michael Saylor.jpg" width="150"><br>Michael Saylor</td>
    <td align="center"><img src="celebrities30sREADME/English/Michio Kaku.jpg" width="150"><br>Michio Kaku</td>
    <td align="center"><img src="celebrities30sREADME/English/MrBeast.jpg" width="150"><br>MrBeast</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Nick Lane.jpg" width="150"><br>Nick Lane</td>
    <td align="center"><img src="celebrities30sREADME/English/Paul Rosolie.jpg" width="150"><br>Paul Rosolie</td>
    <td align="center"><img src="celebrities30sREADME/English/Ryan Graves.jpg" width="150"><br>Ryan Graves</td>
    <td align="center"><img src="celebrities30sREADME/English/Sam Altman.jpg" width="150"><br>Sam Altman</td>
    <td align="center"><img src="celebrities30sREADME/English/Sam Harris.jpg" width="150"><br>Sam Harris</td>
    <td align="center"><img src="celebrities30sREADME/English/Stephen Wolfram.jpg" width="150"><br>Stephen Wolfram</td>
  </tr>
  <tr>
    <td align="center"><img src="celebrities30sREADME/English/Tucker Carlson.jpg" width="150"><br>Tucker Carlson</td>
    <td align="center"><img src="celebrities30sREADME/English/Vitalik Buterin.jpg" width="150"><br>Vitalik Buterin</td>
    <td align="center"><img src="celebrities30sREADME/English/Yuval Harari.jpg" width="150"><br>Yuval Harari</td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>
</details>


<details>
<summary>
Chinese
</summary> <br />

<table>
  <tr>
    <td align="center"><img src="celebrities30sREADME/Chinese/Dilraba Dilmurat.jpg" width="150"><br>迪丽热巴 (Dílì Rèbā)</td>
    <td align="center"><img src="celebrities30sREADME/Chinese/Jolin Tsai.jpg" width="150"><br>蔡依林 (Cài Yīlín)</td>
    <td align="center"><img src="celebrities30sREADME/Chinese/Kris Wu.jpg" width="150"><br>吴亦凡 (Wú Yìfán)</td>
    <td align="center"><img src="celebrities30sREADME/Chinese/Li Yifeng.jpg" width="150"><br>李易峰 (Lǐ Yìfēng)</td>
    <td align="center"><img src="celebrities30sREADME/Chinese/Yang Mi.jpg" width="150"><br>杨幂 (Yáng Mì)</td>
    <td align="center"><img src="celebrities30sREADME/Chinese/Zhao Liying.jpg" width="150"><br>赵丽颖 (Zhào Lìyǐng)</td>
  </tr>
</table>
</details>


<details>
<summary>
Korean
</summary> <br />

<table>
  <tr>
    <td align="center"><img src="celebrities30sREADME/Korean/BTS Jin.jpg" width="150"><br>BTS 진 (Jin)</td>
    <td align="center"><img src="celebrities30sREADME/Korean/BTS RM.jpg" width="150"><br>BTS RM</td>
    <td align="center"><img src="celebrities30sREADME/Korean/IU.jpg" width="150"><br>IU (아이유)</td>
    <td align="center"><img src="celebrities30sREADME/Korean/LeeByungHun.jpg" width="150"><br>이병헌</td>
    <td align="center"><img src="celebrities30sREADME/Korean/LeeJungJae.jpg" width="150"><br>이정재</td>
    <td align="center"><img src="celebrities30sREADME/Korean/YouJaeSuk.jpg" width="150"><br>유재석</td>
  </tr>
</table>
</details>


<details>
<summary>
Japanese
</summary> <br />

<table>
  <tr>
    <td align="center"><img src="celebrities30sREADME/Japanese/Ayase Haruka.jpg" width="150"><br>綾瀬はるか (Ayase Haruka)</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>
</details>
<br />


## 💻 Requisitos do Sistema
- **SO:** Windows 10/11 (64 bits) ※ Linux/Mac não suportados
- **GPU:** NVIDIA com suporte a CUDA 12.4 (recomendado)
- **VRAM:** 4 GB ou mais (8 GB+ preferível)
- **RAM:** 4 GB ou mais
- **Armazenamento:** Pelo menos 20 GB de espaço livre
- **Internet:** Obrigatória

## 📀 Instalação

Instale o Voice-Pro facilmente com **configure.bat** e **start.bat**.

### 1. Preparação do Pacote
- Baixe a versão mais recente em [![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/voice-pro)](https://github.com/abus-aikorea/voice-pro/) (**Source code (zip)**)
```bash
git clone https://github.com/abus-aikorea/voice-pro.git
```

### 2. Instalação e Execução
1. 🚀 **configure.bat**
   - Instala git, ffmpeg e CUDA (se usar GPU NVIDIA)
   - Execute apenas uma vez; requer internet, pode levar mais de 1 hora
   - Não feche a janela de comando
2. 🚀 **start.bat**
   - Inicia a interface web do Voice-Pro
   - Na primeira execução, instala dependências (pode levar mais de 1 hora)
   - Em caso de problemas, delete **installer_files** e execute novamente

### 3. Atualização
- 🚀 **update.bat**: Atualiza o ambiente Python (mais rápido que reinstalar)

### 4. Desinstalação
- Execute **uninstall.bat** ou delete a pasta (instalação portátil)

## ❓ Dicas de Uso

#### Se o navegador não abrir automaticamente
- Feche a janela de comando do Windows e execute **start.bat** novamente
- Abra o navegador manualmente e insira o endereço exibido na janela de comando (ex.: **http://127.0.0.1:7870**)

#### Se ocorrer um erro CUDA Out-of-Memory
- Verifique o status da memória da GPU no Gerenciador de Tarefas do Windows - guia "Desempenho"
- Defina o nível de remoção de ruído para 0 ou 1 (o nível 2 requer pelo menos 8 GB de memória GPU)
- Configure o tipo de cálculo como "int" (o tipo "float" tem melhor qualidade, mas exige mais memória GPU)

#### Como melhorar a qualidade das legendas?
- Modelos Whisper maiores tendem a melhorar a qualidade das legendas (large > medium > small > base > tiny), mas isso não é garantido
- Entre os tipos de cálculo, "float" oferece bom desempenho; "int" reduz o uso da GPU e aumenta a velocidade por meio de quantização do modelo, mas com perda de desempenho
- Aumentar o nível de remoção de ruído elimina mais sons de fundo e usa apenas a voz restante para reconhecimento, mas não garante sempre bons resultados



## 🚨 Aviso
- Este repositório oferece uma **versão de teste gratuita** do Voice-Pro.
- A versão de teste gratuita do Voice-Pro permite processar até **60 segundos** de mídia.
- A versão de assinatura suporta Microsoft Azure TTS e Translator. Compre-o na [Shopify](https://r17wvy-t2.myshopify.com/pt).

<table>
  <tr>
    <th></th>
    <th>Trial Version</th>
    <th>☕Contributor Version</th>
    <th>Subscription Version</th>
  </tr>
  <tr>
    <th>Media Length Limit</th>
    <td>60 seconds</td>
    <td>Unlimited</td>
    <td>Unlimited</td>
  </tr>
  <tr>
    <th>Translation Service</th>
    <td>Google Translate (Open Source)</td>
    <td>Google Translate (Open Source)</td>
    <td>Azure Translate (Microsoft)</td>
  </tr>
  <tr>
    <th>Text-to-Speech Service</th>
    <td>Edge TTS (Open Source)</td>
    <td>Edge TTS (Open Source)</td>
    <td>Azure TTS (Microsoft)</td>
  </tr>
</table>

## ☕ Contribuições

Olá, sou David da equipe Voice-Pro.
Nossa equipe descobre as melhores tecnologias de IA do setor e as fornece para que qualquer pessoa possa usá-las de forma fácil e conveniente.
Somos uma pequena startup na Coreia que existe há apenas um ano. Estamos trabalhando arduamente para ajudar você e outros criadores a produzir conteúdo excelente.

Sua avaliação de ⭐⭐⭐⭐⭐ seria muito apreciada, pois ajuda nossa empresa a crescer com você. Por favor, ajude a apoiar nossa pequena equipe.

Obrigado,
Serviço de Atendimento ao Cliente ABUS


- Se você deseja participar e nos ajudar com este projeto, sinta-se à vontade para criar um [Issues](https://github.com/abus-aikorea/voice-pro/issues).
- Se algo der errado, envie um [Pull requests](https://github.com/abus-aikorea/voice-pro/pulls) para melhorar este projeto.
- Qualquer tipo de contribuição é bem-vindo.
- Para dúvidas relacionadas a compras, parcerias comerciais, ajustes técnicos, investimentos e outros assuntos, entre em contato conosco por e-mail (<abus.aikorea@gmail.com>).
- Se você gosta deste projeto, por favor, dê uma estrela a este repositório. Nós agradeceríamos muito. ⭐⭐⭐
- Você pode apoiar o Voice-Pro com uma doação aqui:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/abus)



## 📬 Contato
- Email: <abus.aikorea@gmail.com>
- Homepage (Korean): <https://abuskorea.imweb.me>
- Naver (Korean): [30-day subscription](https://smartstore.naver.com/abus/products/11308510267)
- Shopify (Global): [30-day subscription](https://r17wvy-t2.myshopify.com/pt)

## 👍 YouTube
- [PlayList](https://www.youtube.com/watch?v=Tu2okoHY174&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)
- [Karaokê: Pop](https://www.youtube.com/watch?v=MqQP3ewvJUk&list=PLwx5dnMDVC9bVxfGo58U-R-w3fUHqwiD6) | [K-Pop](https://www.youtube.com/watch?v=v6qjf_ELsLA&list=PLwx5dnMDVC9Z8kB01tQKfzTysaCCxC3C8) | [J-Pop](https://www.youtube.com/watch?v=KKLzoWHFAxw&list=PLwx5dnMDVC9bd6y3wXs-bOas2cXIi-GAq)

## 🙏 Créditos
* Demucs: <https://github.com/facebookresearch/demucs>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>
* edge-TTS: <https://github.com/rany2/edge-tts>
* F5-TTS: <https://github.com/SWivid/F5-TTS.git>
* openai-whisper: <https://github.com/openai/whisper>
* faster-whisper: <https://github.com/SYSTRAN/faster-whisper>
* whisper-timestamped: <https://github.com/linto-ai/whisper-timestamped>
* whisperX: <https://github.com/m-bain/whisperX>
* CosyVoice: <https://github.com/FunAudioLLM/CosyVoice>
* kokoro: <https://github.com/hexgrad/kokoro>
* Deep-Translator: <https://github.com/nidhaloff/deep-translator>
* spaCy: <https://github.com/explosion/spaCy>

## ©️ Direitos Autorais
<img src="images/ABUS-logo.jpg" width="100" height="100"> por [ABUS](https://abuskorea.imweb.me)