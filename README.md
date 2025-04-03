# Projeto-08-OCR-Azure-Vision-Studio-Copilot-And-Gpt4

Esse projeto faz análises de imagens com conteúdo e retorna as informações contidas. Para testes utilizo o Microsoft azure vision, o Microsoft Copilot e o ChatGpt-4


# 🤖 OCR com Azure AI Vision + Copilot + GPT-4

Este projeto demonstra o uso de **OCR com Azure AI Vision**, complementado com a inteligência do **Microsoft Copilot** e **GPT-4 via Azure OpenAI**, para extrair, interpretar e expandir o conteúdo de imagens com texto.

---

## 📂 Estrutura do repositório

- `inputs/` → Imagens utilizadas para extração de texto (OCR)
- `output/` → Resultados do reconhecimento de texto (em `.json` ou `.txt`)
- `readme.md` → Instruções, prints, aprendizados e insights do projeto

---

## 🚀 Tecnologias Utilizadas

| Tecnologia             | Descrição                                                                 |
|------------------------|---------------------------------------------------------------------------|
| Azure AI Vision        | Reconhecimento de texto (OCR) em imagens via Vision Studio               |
| Microsoft Copilot      | Organização e análise dos textos extraídos com auxílio em tempo real      |
| Azure OpenAI + GPT-4   | Interpretação avançada dos conteúdos OCR, geração de insights e contexto  |

---

## ✅ Passo a passo do projeto (sem código)

### 1. Criação do ambiente Azure

- Recurso criado: **Azure AI Vision**
- Região: East US
- Plano: F0 ou S1
- Acesso via: [Vision Studio](https://azure.com/visionstudio)

### 2. Upload e OCR

- Certifique-se que está logado com a conta Azure e marque a caixa "I acknowledge that this demo will incur usage to resource  in my Azure account."
- Acesse a aba **Extract text from images** no Vision Studio
- Faça upload das imagens
- Visualize e baixe o texto reconhecido em JSON ou copie manualmente

### 3. Processamento com Copilot

- Acesse "https://copilot.microsoft.com/"
- Coloque a imagem desejada e espere o processamento
- Visualize e baixe o texto reconhecido em JSON ou copie manualmente


### 4. Interpretação com Chat GPT-4 (Azure OpenAI)

- Os textos extraídos foram enviados para o **Chat Playground** do Azure AI Foundry
- Prompts utilizados:
  ```text
  Abaixo está um texto extraído de imagem com OCR. Faça um resumo e identifique possíveis ações ou insights empresariais.
  [cole o conteúdo extraído aqui]
