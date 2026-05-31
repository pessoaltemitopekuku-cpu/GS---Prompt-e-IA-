# ⛏️ DRG AI – Sistema de Suporte Tático para Missões Espaciais

<p align="center">
  <img src="https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/DRG_Logo.webp" alt="DRG AI Logo" width="400" style="max-width: 100%;">
</p>

---

## 🌌 Visão Geral

Este projeto foi desenvolvido com base no universo de **Deep Rock Galactic (DRG)**, utilizando elementos e a identidade visual do jogo para criar uma experiência imersiva de monitoramento de telemetria e suporte tático a missões de mineração em **Hoxxes IV**.

O núcleo do ecossistema é a **DRG AI**: uma inteligência artificial corporativa, ranzinza e especializada no contexto do jogo, integrada com um sistema de **RAG (Retrieval-Augmented Generation)**. O seu principal objetivo é analisar dados de sensores (temperatura, energia, escudos), emitir relatórios operacionais críticos e auxiliar os mineradores respondendo a dúvidas sobre mecânicas, missões, biomas, criaturas, classes e recursos da corporação.

---

## 📊 Dashboard de Monitorização & Interface

O sistema conta com um terminal tático simulado e um dashboard visual para que a Gerência e os mineradores consigam interpretar os riscos da operação em tempo real.

### 📸 Demonstração do Painel Operacional

---

## 🤖 Capacidades da DRG AI

Inspirada nos computadores de bordo de ficção científica e nos sistemas de monitoramento de colónias espaciais, a DRG AI possui as seguintes diretrizes:

* **Análise de RAG em Tempo Real:** Consulta manuais técnicos e diretrizes de missão armazenados no GitHub para responder com 0% de alucinação.
* **Suporte de Campo:** Explica mecânicas de jogo, fraquezas de criaturas nativas e composições de biomas hostis.
* **Personalidade Corporativa:** Respostas curtas, frias, diretas e focadas na eficiência do trabalho e na sobrevivência da equipa.

---

## 🔊 Sistema de Áudio (Text-to-Speech)

O projeto possui suporte nativo para geração automática de voz a partir das respostas produzidas pela inteligência artificial utilizando a biblioteca **Edge TTS (Text-to-Speech)**. 

Os textos gerados pelo modelo Llama 3.2 são processados, limpos de caracteres de formatação (Markdown/Asteriscos) e convertidos em transmissões de rádio realistas. Isto emula o canal de comunicação áudio original utilizado pelo *Mission Control* durante as partidas de Deep Rock Galactic.

---

## 🛠️ Como Utilizar o Projeto

Para garantir o funcionamento correto do ecossistema e evitar erros de conexão local, siga esta ordem estrita de execução no Google Colab:

1. **Instalação de Dependências:** Execute a primeira célula para instalar pacotes vitais (`pypdf`, `edge-tts`, `ollama` e a dependência de descompactação do sistema `zstd`).
2. **Inicialização do Servidor:** Execute a célula de ativação do Ollama. O script irá encerrar portas travadas e subir o servidor em background via Python `subprocess`.
3. **Carga do Modelo:** Aguarde o download de 100% do modelo local `llama3.2:1b`.
4. **Extração do RAG:** Execute a célula do conversor de PDF. Os ficheiros serão baixados diretamente do repositório Git e limpos via Regex.
5. **Painel de Interação:** Utilize a célula `"Pergunte ao DRG AI"` para realizar perguntas dinâmicas baseadas nos documentos fornecidos.

---

## 📦 Dependências Técnicas

O projeto foi desenhado para rodar inteiramente na nuvem através do Google Colab (CPU), eliminando a necessidade de downloads manuais de ficheiros ou configurações complexas de hardware local.

* **Linguagem:** Python 3.12+
* **LLM Local:** Ollama (Modelo Llama 3.2 1B)
* **Extração de Documentos:** PyPDF (PdfReader)
* **Voz Artificial:** Edge-TTS (`pt-BR-AntonioNeural`)
* **Processamento de Contexto:** Expressões Regulares (`re`)

---

## 🔗 Relação de Links do Projeto

Utilize os links oficiais listados abaixo para aceder à infraestrutura de código, assistir à demonstração e ler os manuais utilizados pela inteligência artificial:

* **Notebook do Projeto (Google Colab):** [Insere o Link do teu Notebook aqui]
* **Vídeo de Demonstração (YouTube):** [Insere o Link do teu Vídeo de 3 minutos aqui]
* **Base de Dados RAG - Manual do Jogo (PDF):** [https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Deep%20Rock%20Galactic.pdf](https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Deep%20Rock%20Galactic.pdf)
* **Base de Dados RAG - Diretrizes da Missão (PDF):** [https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Miss%C3%A3o.pdf](https://github.com/pessoaltemitopekuku-cpu/GS---Prompt-e-IA-/blob/main/Miss%C3%A3o.pdf)

---

## 👥 Desenvolvedores / Integrantes

* **Nome do Aluno 1** - RMXXXXX - Turma XX
* **Nome do Aluno 2** - RMXXXXX - Turma XX
