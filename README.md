# ⛏️ DRG AI – Sistema de Suporte Tático para Missões Espaciais

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/DRG_Logo.webp" alt="DRG AI Logo" width="1000" style="max-width: 100%;">
</p>

---

## 🌌 Visão Geral

Este projeto foi desenvolvido com base no universo de **Deep Rock Galactic (DRG)**, utilizando elementos e a identidade visual do jogo para criar uma experiência imersiva de monitoramento de telemetria e suporte tático a missões de mineração em **Hoxxes IV**.

O núcleo do ecossistema é a **DRG AI**: uma inteligência artificial corporativa, ranzinza e especializada no contexto do jogo. O seu principal objetivo é analisar dados de sensores (temperatura, energia, escudos), emitir relatórios operacionais críticos e auxiliar os mineradores respondendo a dúvidas sobre mecânicas, missões, biomas, criaturas, classes e recursos da corporação.

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Funcoes.png" alt="Código IA" width="1000" style="max-width: 100%;">
</p>

---

## 🤖 Capacidades da DRG AI

Inspirada nos computadores de bordo de ficção científica e nos sistemas de monitoramento de colónias espaciais, a DRG AI possui as seguintes diretrizes:

* **Suporte de Campo:** Explica mecânicas de jogo, fraquezas de criaturas nativas e composições de biomas hostis.
* **Transcricação de voz:** Equipada com transcrição de voz a IA gera campos de áudio para facilitar a comunicação.

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/DRG_AI.png" alt="Código IA" width="1000" style="max-width: 100%;">
</p>

---

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Perguntas_DRG_AI.png" alt="Código IA" width="1000" style="max-width: 100%;">
</p>

---

## 🔊 Sistema de Áudio (Text-to-Speech)

O projeto possui suporte nativo para geração automática de voz a partir das respostas produzidas pela inteligência artificial utilizando a biblioteca **Edge TTS (Text-to-Speech)**. 

Os textos gerados pelo modelo Llama 3.2 são processados, limpos de caracteres de formatação (Markdown/Asteriscos) e convertidos em transmissões de rádio realistas. Isto emula o canal de comunicação áudio original utilizado pelo *Mission Control* durante as partidas de Deep Rock Galactic.

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Play_Audio.png" alt="Código IA" width="1000" style="max-width: 100%;">
</p>

---

## 🛠️ Como Utilizar o Projeto

Para garantir o funcionamento correto do ecossistema e evitar erros de conexão local, siga esta ordem estrita de execução no Google Colab:

1. **Instalação de Dependências:** Execute a primeira célula para instalar pacotes vitais (`pypdf`, `edge-tts`, `ollama` e a dependência de descompactação do sistema `zstd`).
2. **Inicialização do Servidor:** Execute a célula de ativação do Ollama. O script irá encerrar portas travadas e subir o servidor em background via Python `subprocess`.
3. **Carga do Modelo:** Aguarde o download de 100% do modelo local `llama3.2:1b`.
4. **Painel de Interação:** Utilize a célula `"Pergunte ao DRG AI"` para realizar perguntas dinâmicas baseadas nos textos fornecidos.

---

## 📦 Dependências Técnicas

O projeto foi desenhado para rodar inteiramente na nuvem através do Google Colab (CPU), eliminando a necessidade de downloads manuais de ficheiros ou configurações complexas de hardware local.

* **Linguagem:** Python 3.12+
* **LLM Local:** Ollama (Modelo Llama 3.2 1B)
* **Voz Artificial:** Edge-TTS (`pt-BR-AntonioNeural`)
* **Processamento de Contexto:** Expressões Regulares (`re`)

---

## 🔗 Relação de Links do Projeto

Utilize os links oficiais listados abaixo para aceder à infraestrutura de código, assistir à demonstração e ler os manuais utilizados pela inteligência artificial:

* **Notebook do Projeto (Google Colab):** https://colab.research.google.com/drive/1WutWC0zhlUYVbvDxdAuUmyq_wrWuhHz1?usp=sharing
* **Vídeo de Demonstração (YouTube):** https://youtu.be/uG2rUrzPEkU

---

## 👥 Desenvolvedores / Integrantes

* **Temitope Kuku da Silva Ogunbanjo** - RM 573772 - Turma 1CCPO
* **Gabrieli de Lima Pettena de Oliveira** - RM569799 - Tura 1CPPO
