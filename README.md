# 🎻 Dedo de Violinista

**Dedo de Violinista** é um visualizador interativo de partituras MusicXML projetado especificamente para auxiliar estudantes e professores de violino. Ele combina a renderização precisa de partituras com um guia visual de dedilhado em tempo real e um sistema de metrônomo profissional.

<img width="1469" height="764" alt="image" src="https://github.com/user-attachments/assets/1c41dab8-51a0-4507-a197-6cd0430bdf4a" />


## ✨ Principais Funcionalidades

- **Visualização Interativa**: Renderização de alta qualidade usando [OpenSheetMusicDisplay](https://github.com/opensheetmusicdisplay/opensheetmusicdisplay).
- **Guia de Dedilhado**: Um braço de violino virtual que mostra as posições dos dedos (1ª posição) em tempo real conforme a música toca.
- **Metrônomo Profissional**:
  - Som de alta fidelidade (*Side Stick/Rimshot*) via WebAudioFont.
  - **Contagem Configurável**: Escolha entre 1, 2 ou 4 compassos de preparação.
  - **Detecção de Anacruza**: Ajusta automaticamente a contagem para entradas em tempos incompletos.
  - **Pausa de Preparação**: 1 segundo de silêncio antes do início da contagem.
- **Trechos e Loops**:
  - Seleção de intervalo de compassos para estudo focado.
  - Modo **Loop** automático para repetição contínua de trechos.
- **Suporte Multi-Instrumento**: Escolha qual "voz" da partitura deve guiar o dedilhado no braço do violino.
- **Mapeamento Customizado**: Ajustes finos de digitação (ex: uso do dedo 4 para intervalos de tritura em todas as cordas).
- **Temas**: Suporte a temas claro (Bege Clássico) e escuro.

## 🚀 Como Usar

1. **Carregar Partitura**: Utilize o botão "Carregar partitura" para importar arquivos `.xml`, `.musicxml` ou `.mxl`.
2. **Configurar**: Ajuste o BPM (andamento), a reverberação e o nível de zoom.
3. **Selecionar Trecho**: Define os compassos inicial e final se desejar estudar apenas uma parte.
4. **Guia de Dedilhado**: Se houver mais de um instrumento na partitura, use o seletor "Guia" para escolher qual voz será exibida no braço do violino.
5. **Praticar**: Ative o Metrônomo e o Loop conforme necessário e clique em **Play**.

## 🛠️ Tecnologias Utilizadas

- **HTML5 / CSS3** (Vanilla para máxima performance)
- **JavaScript** (ES6+)
- **OpenSheetMusicDisplay (OSMD)**: Renderização de MusicXML.
- **WebAudioFont**: Motor de áudio baseado em samples para o metrônomo.
- **Soundfont-player**: Reprodução do som de violino para as notas da partitura.
- **JSZip**: Para suporte a arquivos MusicXML compactados (.mxl).

## 📄 Licença

Desenvolvido pelo professor **Glauber Santiago** — DAC/UFSCar.
Este projeto está disponível para fins educacionais.

---
[servidores.ufscar.br/glauber/](https://servidores.ufscar.br/glauber/) | [sites.google.com/view/glauberia](https://sites.google.com/view/glauberia)
