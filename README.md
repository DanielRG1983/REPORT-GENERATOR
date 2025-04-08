# 🛡️ **DRG_REPORT_GENERATOR_V7** – Gerador Avançado de Relatórios de Chat

---

## 🙋 Sobre o Desenvolvedor

- **Daniel Rodrigues Guimarães**
- Agente de Polícia Civil do Estado do Piauí
- Bacharel em Ciência da Computação
- Pós-graduado em Perícia Cibernética
- Pós-graduado em Engenharia de Software

📧 **Contato/PIX**: danielrg.apc@gmail.com

---

## 📝 **Descrição da Aplicação**

Ferramenta desenvolvida especialmente para **análise técnica e investigação policial**, permitindo a **geração automática de relatórios** profissionais com base em **exportações do Cellebrite** e outros formatos de chat (TXT), com suporte completo a **anexos multimídia**.

---

## ✅ **Principais Funcionalidades**

- 📂 Leitura de arquivos `.txt` de conversas extraídos do Cellebrite
  - Suporte tanto a marcações em **português** quanto em **inglês**
- 🧍 Identificação e exibição dos **participantes da conversa**
- 🕓 Inclusão de **timestamp** de cada mensagem
- 📎 Inserção de **anexos multimídia**, incluindo:
  - Imagens (.jpg, .jpeg, .png, .webp)
  - Vídeos (.mp4, .avi, .mov) com geração de miniatura
  - PDFs (inserção da 1ª página como imagem)
  - Áudios (.opus), com leitura automática das **transcrições** `.txt`
- 🧠 Detecção automática de transcrições e associação correta aos anexos
- 🧾 Três **formatos de relatório** disponíveis:
  - **Com tabela:** organização formal e estruturada
  - **Sem tabela:** estilo de redação mais livre e fluido
  - **Estilo WhatsApp:** (caso implementado) com diferenciação visual entre participantes
- 💼 Saída nos formatos:
  - `.docx` (compatível com Microsoft Word)
  - `.wps` (compatível com WPS Office – gerado a partir do `.docx`)
- 🖥️ Interface gráfica com **Tkinter**:
  - Simples, funcional e intuitiva
  - Seleção de formato e modelo de relatório
  - Barra de progresso com porcentagem

---

## ⚙️ **Requisitos Técnicos**

- **Sistema Operacional:** Windows
- **ffmpeg.exe** na mesma pasta da aplicação (usado para extrair thumbnails de vídeos)
- **WPS Office** instalado, caso deseje gerar `.wps`

---
IMPORTANTE:

## Desative o antivírus ou crie uma exceção para a aplicação;

## Execute o aplicativo como administrador.

## 🚀 **Como Usar**

1. Inicie o programa executável
2. Selecione o arquivo `.txt` exportado do Cellebrite
3. Selecione a pasta contendo os anexos
4. Escolha o **tipo de relatório** (com ou sem tabela)
5. Escolha o **formato do arquivo final** (`.docx` ou `.wps`)
6. Clique em **Executar**
7. Escolha o local para salvar o arquivo
8. Aguarde a mensagem de confirmação

---

## 🔒 **Considerações Finais**

- O programa não depende do **Microsoft Office** instalado
- A conversão para `.wps` é feita via **CLI do WPS Office**
- Pode ser empacotado via **PyInstaller** para distribuição como `.exe`
- Funcionalidade robusta para uso forense e documental, com foco na **fidelidade das mensagens e anexos**

---


