# 🎻 Dedo de Violinista

Visualizador interativo de partituras com guia de dedilhado para violino. Funciona 100% no navegador — sem instalação necessária.

🔗 **Acesse agora:** [glauberlasantiago.github.io/dedo-de-violinista](https://glauberlasantiago.github.io/dedo-de-violinista/)

<img width="913" height="836" alt="image" src="https://github.com/user-attachments/assets/30785877-b68a-4c11-bfbd-615342e18108" />


## Funcionalidades

- 📄 **Carregamento de partituras** — suporta arquivos `.xml`, `.musicxml` e `.mxl`
- 📖 **Hinário Novo Cântico (HNC)** — navegue e carregue hinos diretamente pelo seletor
- 🎵 **Reprodução de áudio** — toca a partitura com som de violino ou piano, usando WebAudio
- 🎹 **Braço do violino virtual** — exibe em tempo real o dedilhado nas cordas (Mi, Lá, Ré, Sol)
- ⏱ **Controle de BPM** — ajuste a velocidade e opção de redução automática (-30 BPM)
- 🔁 **Loop e trecho** — defina compasso inicial/final e repita quantas vezes quiser
- 🎤 **Metrônomo e contagem** — 1, 2 ou 4 compassos de introdução antes da execução
- 🔊 **Reverb** — controle de reverberação para o som
- 🎯 **Modo Foco** — esconde tudo e exibe apenas a partitura em tela cheia
- 🔍 **Zoom** — ajuste de 40% a 300%
- 🌙 **Tema claro/escuro** — alternância com um clique
- 🎛 **Solo e Guia de instrumento** — para partituras com múltiplas partes
- 💾 **Exportar** — salva o app com a partitura embutida em um único HTML
- 📱 **Responsivo** — funciona em celular e desktop
- 📲 **PWA** — instale como app no celular ou desktop para uso offline

## Como usar

1. Acesse o site pelo link acima
2. Clique em 📂 para carregar uma partitura `.xml`/`.mxl` **ou** selecione um hino pelo seletor **📖 HNC**
3. Ajuste BPM, trecho, metrônomo e pressione **▶ Tocar**
4. Acompanhe o dedilhado no braço do violino virtual

## Instalar como app (PWA)

No navegador (Chrome, Edge, Safari):
1. Acesse o site
2. Clique no ícone de **instalar** (⊕) na barra de endereço
3. O app funciona offline após a primeira visita

## Tecnologias

- [OpenSheetMusicDisplay](https://opensheetmusicdisplay.github.io/) — renderização de partituras MusicXML
- [soundfont-player](https://github.com/danigb/soundfont-player) — reprodução de áudio via SoundFont
- [WebAudioFont](https://surikov.github.io/webaudiofont/) — fontes de áudio para WebAudio
- [JSZip](https://stuk.github.io/jszip/) — descompactação de arquivos `.mxl`
- HTML, CSS e JavaScript puro — sem frameworks

## Estrutura

```
index.html       → Aplicação completa (single-file)
manifest.json    → Manifesto PWA
sw.js            → Service Worker para cache offline
icons/
  icon-192.png   → Ícone 192x192
  icon-512.png   → Ícone 512x512
```

## Licença

Este projeto é de uso livre para fins educacionais e pessoais.
