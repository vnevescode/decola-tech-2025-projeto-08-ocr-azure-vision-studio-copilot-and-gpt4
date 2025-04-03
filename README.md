# Projeto-08-OCR-Azure-Vision-Studio-Copilot-And-Gpt4


![Capa_Projeto_08](https://github.com/user-attachments/assets/ed9321b2-4ac6-474b-9ca0-f0cadf48a87e)

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


### 4. Interpretação com Chat GPT-4 e GPT-4 Azure OpenAI

- Os textos extraídos foram enviados para o **Chat Playground** do Azure AI Foundry
- Também para o prompt do ChatGPT-4 Premium 

---

# Resultados :

Para as imagens a seguir:

## Imagem I

![Parque das Esculturas](https://github.com/user-attachments/assets/2486e912-3f7d-47ee-b858-e7f0e381a35b)
![image](https://github.com/user-attachments/assets/f0a82243-38a4-4281-baa8-cb0182c0add1)

## Azure AI Vision:

```bash

PARQUEDEESCULTURASDE
FRANCISCOBRENNAND
FRANCISCOBRENNANDSCULPTUREPARK
Foiinauguradonoano2000comomarcocomemorativodoRecife
aos500anosdoDescobrimentodoBrasil.Abrigaobrasdoartista
FranciscoBrennand,sendodestaquea"ColunadeCristal".
Itwasopenedin2000asacommemorativemilestoneofthe500thanniversaryof
BrazilDiscoveryDay.ItholdsFranciscoBrennand'ssculptures,which"Crystal
Column"isthebiggestone.
```

## Copilot

```bash
O texto na imagem é:

**"PARQUE DE ESCULTURAS DE FRANCISCO BRENNAND FRANCISCO BRENNAND SCULPTURE PARK

Foi inaugurado no ano 2000 como marco comemorativo do Recife aos 500 anos do Descobrimento do Brasil. Abriga obras do artista Francisco Brennand, sendo destaque a 'Coluna de Cristal'.

It was opened in 2000 as a commemorative milestone to the 500th anniversary of Brazil Discovery Day. It holds Francisco Brennand's sculptures, which 'Crystal Column' is the biggest one."**

Uma bela homenagem à arte e à história do Recife! Conhecer o Parque de Esculturas deve ser uma experiência incrível. O que mais você gostaria de saber sobre o local ou o artista?
```


## ChatGPT-4

```bash
PARQUE DE ESCULTURAS DE FRANCISCO BRENNAND
FRANCISCO BRENNAND SCULPTURE PARK

Foi inaugurado no ano 2000 como marco comemorativo do Recife aos 500 anos do Descobrimento do Brasil. Abriga obras do artista Francisco Brennand, sendo destaque a "Coluna de Cristal".

It was opened in 2000 as a commemorative milestone of the 500th anniversary of Brazil Discovery Day. It holds Francisco Brennand's sculptures, which "Crystal Column" is the biggest one.

```

---

## Imagem II

![image](https://github.com/user-attachments/assets/e7126d50-40a6-4524-82fe-ac97674d7be4)


## Azure AI Vision:

```bash
SérieRobertC.Martin
ALTABOOKS
EDITORA
ArquiteturaLimpa
OGuiadoArtesãopara
EstruturaeDesigndeSoftware
RobertC.Martin
ComcontribuiçõesdeJamesGrenningeSimonBrown
PrefáciodeKevlinHenney
EpílogodeJasonGorman
```

## Copilot

```bash
O texto na imagem diz:

**"Arquitetura Limpa: O Guia do Artesão para Estrutura e Design de Software Autor: Robert C. Martin Contribuições de James Grenning e Simon Brown Série Robert C. Martin Editora: Alta Books

Inclui prefácio por Kevlin Henney e epílogo por Jason Gorman."**
```


## ChatGPT-4

```bash
Série Robert C. Martin
ALTA BOOKS EDITORA

Arquitetura Limpa
O Guia do Artesão para Estrutura e Design de Software

Robert C. Martin
Com contribuições de James Grenning e Simon Brown

Prefácio de Kevlin Henney
Epílogo de Jason Gorman
```
---

## Imagem III

![equacao_2_grau_foto](https://github.com/user-attachments/assets/7caa098a-4f3b-485c-829b-5bc4d0e3c487)


## Azure AI Vision:

```bash
x2-3x-54=0
A=b2-4ac
a=1
A=(-3)2-4·1·(-54)
Sãoduasraízesreaisedistintas.
b=-3
A=9+216
Vamoscontinuar!
C=-54
A=225
3+15
X1=2===9
x==
-b+VA
-(-3)₺V225
x=-
3+15
2a
X=
2.1
2
3-15
X2=2====-6
S={9,-6}
```

## Copilot

![image](https://github.com/user-attachments/assets/2b8432ff-284d-45ed-b256-435f61e60c13)



## ChatGPT-4

```bash
Claro! A imagem mostra a resolução completa de uma equação do 2º grau usando a fórmula de Bhaskara. Aqui está o texto transcrito com os principais passos:

x² - 3x - 54 = 0

a = 1
b = -3
c = -54

Δ = b² - 4ac
Δ = (-3)² - 4 · 1 · (-54)
Δ = 9 + 216
Δ = 225 (em verde)

São duas raízes reais e distintas.
Vamos continuar! (em verde)

x = (-b ± √Δ) / 2a
x = (-(-3) ± √225) / (2 · 1)
x = (3 ± 15) / 2

x₁ = (3 + 15) / 2 = 18 / 2 = 9
x₂ = (3 - 15) / 2 = -12 / 2 = -6

---

S = {9, -6} (em negrito)

```
