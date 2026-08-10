# Análise de Sentimentos com Language Studio no Azure AI

Repositório criado como entregável do desafio de projeto do **Bootcamp Suzano - Python Developer**, da [DIO](https://www.dio.me). O objetivo foi praticar e aprofundar o uso das ferramentas **Azure Speech Studio** e **Language Studio**, com foco em análise de fala e linguagem natural.

## 📋 Sobre o desafio

Laboratório prático com o objetivo de desenvolver habilidades na criação de soluções de IA voltadas para voz e linguagem, utilizando o ecossistema Azure AI. Este repositório reúne as anotações, capturas de tela e insights adquiridos durante a prática, servindo como material de apoio para estudos futuros.

## 🎯 Objetivos de aprendizagem

- Aplicar os conceitos aprendidos em um ambiente prático
- Documentar processos técnicos de forma clara e estruturada
- Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica
- Explorar o Azure Speech Studio e a análise linguística proporcionada pelo Language Studio

## 🛠️ Ferramentas utilizadas

- **Azure Speech Studio** — reconhecimento e síntese de fala
- **Azure Language Studio** — análise de texto e compreensão de linguagem natural
- **Azure AI Services** — plataforma de serviços cognitivos da Microsoft

## 🔍 Entendendo as ferramentas

### Azure Speech Studio

É a interface do Azure AI Services voltada para tudo relacionado a voz. Principais capacidades:

* **Speech to Text (reconhecimento de fala)** — converte áudio em texto, com suporte a transcrição em tempo real ou de arquivos gravados. Permite treinar modelos customizados para vocabulário específico (nomes técnicos, jargões, sotaques).
* **Text to Speech (síntese de voz)** — converte texto em áudio com vozes neurais bem naturais; dá pra escolher entre vozes prontas ou criar uma voz customizada.
* **Speech Translation** — tradução de fala em tempo real entre idiomas.
* **Speaker Recognition** — identifica ou verifica quem está falando (útil em cenários de biometria de voz).
* **Pronunciation Assessment** — avalia a pronúncia do usuário, comum em apps de ensino de idiomas.

No laboratório da DIO, o foco costuma ser explorar o Speech to Text — gravar ou usar um áudio de exemplo, rodar o reconhecimento e observar a precisão da transcrição, testando diferentes idiomas/sotaques.

### Azure Language Studio

É a interface para tudo relacionado a texto e linguagem natural (NLP). Principais capacidades:

* **Análise de sentimento e mineração de opinião** — classifica um texto como positivo, negativo, neutro ou misto, e ainda aponta frases específicas que geraram cada sentimento.
* **Extração de frases-chave** — identifica os termos mais relevantes de um texto.
* **Reconhecimento de entidades nomeadas (NER)** — identifica pessoas, lugares, organizações, datas etc. dentro do texto.
* **Detecção de idioma** — identifica automaticamente em que idioma o texto foi escrito.
* **Sumarização de texto** — gera resumos automáticos de documentos ou conversas.
* **Question Answering** — cria uma base de perguntas e respostas a partir de documentos (o "Análise de texto e resposta a perguntas" que aparece no print da DIO).
* **Conversational Language Understanding (CLU)** — treina modelos para entender intenção em linguagem coloquial, usado para construir bots (ligado ao "Serviço de bot do Azure" que também aparece no conteúdo do desafio).

### Como eles se conectam no desafio

A lógica comum de um pipeline de IA de voz e linguagem é:

1. Speech Studio transcreve o áudio (voz → texto)
2. Language Studio analisa esse texto (sentimento, entidades, intenção, etc.)

Ou seja, um usuário fala algo, o Speech Studio transcreve, e o Language Studio interpreta o que foi dito — por exemplo, detectando se o cliente está insatisfeito em uma ligação de call center, ou entendendo a intenção por trás de um comando de voz para um bot.

## 📚 Conteúdo explorado

- [Análise de texto e resposta a perguntas](docs/language-studio.md)
- [Serviço de bot do Azure](docs/language-studio.md)
- [Compreensão da linguagem coloquial](docs/language-studio.md)
- [Estúdio de fala (Speech Studio)](docs/speech-studio.md)
- [Language Studio](docs/language-studio.md)

## 📝 Anotações e insights

As anotações detalhadas de cada etapa da prática estão organizadas na pasta [`docs/`](docs/):

- **[speech-studio.md](docs/speech-studio.md)** — anotações sobre reconhecimento de fala, transcrição e síntese de voz no Azure Speech Studio
- **[language-studio.md](docs/language-studio.md)** — anotações sobre análise de texto, extração de informações e compreensão de linguagem coloquial no Language Studio
- **[insights.md](docs/insights.md)** — principais aprendizados, desafios encontrados e reflexões sobre aplicações práticas

## 🖼️ Capturas de tela

As evidências visuais da prática estão disponíveis em [`assets/screenshots/`](assets/screenshots/).

## ✅ Resultado

Repositório documentado com o passo a passo da prática realizada, servindo como referência pessoal e material de estudo para futuras implementações envolvendo IA de voz e linguagem no Azure.

---

**Autor:** Nágyla Aparecida Silva
**Bootcamp:** Suzano - Python Developer — DIO

