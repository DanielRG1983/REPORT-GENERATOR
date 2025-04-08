# REPORT-GENERATOR

## 🙋 Sobre o Desenvolvedor:

DANIEL RODRIGUES GUIMARÃES
Agente de Polícia Civil do Estado do Piauí
Bacharel em Ciência da Computação
Pós Graduado em Perícia Cibernética
Pós Graduado em Engenharia de Software
Para apoiar este projeto, considere fazer uma doação através da chave pix do desenvolvedor:
danielrg.apc@gmail.com

# 📝 DRG_REPORT_GENERATOR_V7 – Gerador Avançado de Relatórios de Chat


Aplicação desenvolvida por **DanielRG – PCPI** para **geração automática de relatórios profissionais** com base em arquivos de chat (formato `.txt`) e anexos (imagens, vídeos, áudios, PDFs e transcrições).  
Ideal para uso investigativo, técnico ou documental.

---

## ✅ Funcionalidades:

- 📂 Leitura automatizada de arquivos `.txt` exportados de conversas (com suporte a **WhatsApp** em português e inglês)
- 📎 Reconhecimento e inserção de **anexos** (fotos, vídeos, áudios, PDFs, imagens `.webp`)
- 🧠 Detecção e inserção de **transcrições automáticas** associadas aos anexos `.opus`, `.mp4`, `.avi`, etc.
- 📊 **Três formatos de relatório** disponíveis:
  - **Com tabela:** estrutura organizada e formal
  - **Sem tabela:** texto corrido e limpo
  - **Estilo WhatsApp:** mensagens destacadas com cores diferentes para o **(Proprietário)** e os demais participantes
- 📝 Suporte aos formatos de saída:
  - **DOCX (Microsoft Word)**
  - **WPS (WPS Office)** *(inclui conversão automática a partir do DOCX)*
- 📅 Inclusão de metadados da conversa: hora de início, última atividade, e lista de participantes
- 💡 Interface gráfica amigável desenvolvida com `Tkinter`
- 🔄 Indicação visual de progresso via mensagem piscante durante a geração
- 💙 Tela de manual integrada com instruções completas
- 📧 Email clicável com cópia automática para clipboard
- 💰 QR Code para **doações via PIX** ao desenvolvedor

---

## 🔧 Requisitos:

- **Sistema Operacional:** Windows
- **ffmpeg.exe** na mesma pasta da aplicação (necessário para gerar thumbnails de vídeos)
- Para gerar `.wps`: necessário ter **WPS Office** instalado no sistema

---

## 🚀 Como usar:

1. **Abra o programa executável**
2. Selecione o arquivo `.txt` exportado do chat
3. Selecione a **pasta de anexos** correspondente (imagens, vídeos, transcrições .txt)
4. Escolha o **modelo de relatório** desejado (tabela, texto ou WhatsApp)
5. Escolha o **formato final** (DOCX ou WPS)
6. Clique em **Executar**
7. Defina o nome do arquivo e local de salvamento
8. Aguarde a mensagem "Processo concluído com sucesso!"

---

## 📦 Observações:

- O código está pronto para ser empacotado com PyInstaller.
- O antivírus pode bloquear o `.exe`; recomendo adicionar exceção ou executar como administrador.
- O programa suporta textos com marcações em **português ou inglês**, e identifica automaticamente o idioma base.

---

