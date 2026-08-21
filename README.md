# Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI

## 1. Sobre o projeto

Repositório desenvolvido como entregável do desafio de projeto do **Bootcamp Suzano — Python Developer**, da [DIO](https://www.dio.me/), com foco na exploração de **Inteligência Artificial, Processamento de Linguagem Natural (NLP) e tecnologias de fala do ecossistema Microsoft Azure**.

O projeto reúne estudos, experimentações, conceitos técnicos e aprendizados relacionados ao **Azure Language / Language Studio** e ao **Azure Speech / Speech Studio**, além da exploração conceitual de tecnologias relacionadas à linguagem conversacional, sistemas de perguntas e respostas e agentes de IA.

> **TL;DR:** Projeto de aprendizagem em Azure AI com foco em **NLP, análise de sentimentos, mineração de opinião, extração de informações, detecção de idioma, sumarização e processamento de fala**. Também foram estudados conceitualmente **Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service**.

### Escopo

Os recursos de Azure Language e Azure Speech foram explorados no contexto do laboratório. Question Answering, CLU, Microsoft Copilot Studio e Azure AI Bot Service são tratados como **estudos conceituais**, e não como implementações práticas realizadas neste repositório.

---

## 2. Navegação do projeto

A documentação está organizada por domínio e finalidade. As áreas práticas são separadas dos estudos conceituais e das áreas de evidências, resultados e fontes.

| Área | Conteúdo |
|---|---|
| [**Azure Language**](./azure-language/) | Sentiment Analysis, Opinion Mining, Key Phrase Extraction, NER, Language Detection e Summarization. |
| [**Azure Speech**](./azure-speech/) | Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment. |
| [**Estudos conceituais**](./estudos-conceituais/) | Question Answering, CLU, Copilot Studio e Bot Service. |
| [**Evidências**](./evidencias/) | Critérios e organização dos registros das atividades práticas. |
| [**Resultados**](./resultados/) | Learnings, Conclusions, competências e limitações. |
| [**Fontes**](./fontes/) | Referências oficiais Microsoft e materiais complementares. |

### Estrutura atual do repositório

```text
analise-sentimentos-language-studio-azure-ai/
│
├── README.md
│
├── azure-language/
│   ├── README.md
│   ├── sentiment-analysis/
│   │   └── README.md
│   ├── opinion-mining/
│   │   └── README.md
│   ├── key-phrase-extraction/
│   │   └── README.md
│   ├── named-entity-recognition/
│   │   └── README.md
│   ├── language-detection/
│   │   └── README.md
│   └── summarization/
│       └── README.md
│
├── azure-speech/
│   ├── README.md
│   ├── speech-to-text/
│   │   └── README.md
│   ├── text-to-speech/
│   │   └── README.md
│   ├── speech-translation/
│   │   └── README.md
│   └── pronunciation-assessment/
│       └── README.md
│
├── estudos-conceituais/
│   ├── README.md
│   ├── question-answering/
│   │   └── README.md
│   ├── conversational-language-understanding/
│   │   └── README.md
│   ├── copilot-studio/
│   │   └── README.md
│   └── bot-service/
│       └── README.md
│
├── evidencias/
│   ├── README.md
│   ├── azure-language/
│   │   └── README.md
│   └── azure-speech/
│       └── README.md
│
├── resultados/
│   ├── README.md
│   ├── learnings/
│   │   └── README.md
│   └── conclusions/
│       └── README.md
│
└── fontes/
    ├── README.md
    ├── microsoft-azure/
    │   └── README.md
    └── dio/
        └── README.md
```

### Fluxo de navegação e conhecimento

```text
                         README.md
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
 Azure Language       Azure Speech       Estudos conceituais
        │                   │                   │
        │                   │                   │
        └──────────────┬────┴───────────────────┘
                       │
                       ▼
             Relação entre fala e NLP
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
     Evidências     Resultados     Fontes
```

O diagrama representa **navegação e relação conceitual**, não uma implementação integrada obrigatória.

---

## 3. O que foi praticado

### 3.1 Azure Language e Language Studio

O Azure Language reúne capacidades de NLP para analisar, classificar e extrair informações de texto. No laboratório foram explorados recursos relacionados a sentimento, opinião, frases-chave, entidades, idioma e sumarização.

### 3.2 Análise de sentimentos e mineração de opinião

A análise de sentimentos classifica polaridade e fornece pontuações de confiança. A mineração de opinião acrescenta granularidade ao relacionar sentimentos a aspectos do texto.

Aplicações: avaliações, feedbacks, pesquisas de satisfação, comentários e triagem de grandes volumes de texto.

### 3.3 Extração de informações

Key Phrase Extraction identifica conceitos relevantes. NER identifica entidades como pessoas, organizações e locais. Esses recursos podem transformar texto não estruturado em informações mais estruturadas.

### 3.4 Detecção de idioma

A detecção de idioma identifica o idioma predominante de um texto e pode apoiar fluxos multilíngues.

### 3.5 Sumarização

A sumarização produz versões condensadas de documentos ou conversas, devendo ser usada com validação humana quando detalhes omitidos puderem afetar decisões.

### 3.6 Azure Speech e Speech Studio

Foram estudados Speech to Text, Text to Speech, Speech Translation, Pronunciation Assessment e outros recursos relacionados ao ecossistema Speech.

---

## 4. Aprendizados e competências

O projeto consolidou conhecimentos de NLP, análise automatizada de texto, processamento de fala, leitura de documentação técnica, serviços cloud e organização de documentação no GitHub.

As competências apresentam relação com **AI Training, AI Response Evaluation, Data Annotation, QA e documentação técnica**.

---

## 5. Exploração conceitual

### 5.1 Question Answering

Question Answering foi estudado como tecnologia para construir respostas sobre bases de conhecimento. A documentação atual informa mudanças de ciclo de vida para Custom Question Answering e orienta novos projetos a considerar as alternativas atuais do Microsoft Foundry.

### 5.2 Conversational Language Understanding (CLU)

CLU permite criar modelos personalizados para interpretar intenções e extrair entidades. A documentação atual da Microsoft informa que o recurso será descontinuado no Azure Language em **31 de março de 2029** e recomenda considerar Microsoft Foundry para novos projetos.

### 5.3 Microsoft Copilot Studio

Foi estudado conceitualmente como plataforma para criação e personalização de agentes e experiências conversacionais.

### 5.4 Azure AI Bot Service

Foi estudado conceitualmente para compreender arquiteturas de bots, integração com canais e experiências conversacionais.

> **Importante:** esses quatro temas são apresentados como estudos conceituais, não como soluções implementadas neste projeto.

---

## 6. Relação entre fala e linguagem

Um fluxo conceitual estudado é:

**Voz → Speech to Text → Texto → Azure Language → Resultado**

Em atendimento ao cliente, por exemplo, uma gravação pode ser transcrita e posteriormente analisada para sentimento, entidades, frases-chave ou idioma. Esse fluxo representa uma possibilidade arquitetural e não uma implementação integrada realizada neste repositório.

---

## 7. Aplicações relacionadas

Os conhecimentos podem ser relacionados a análise de satisfação, feedbacks, classificação de opiniões, processamento documental, atendimento automatizado, análise de chamadas, transcrição, sistemas de perguntas e respostas, extração de informações e aplicações multilíngues.

Esses são **cenários possíveis**, não soluções implementadas neste repositório.

---

## 8. Conteúdo explorado

### 8.1 Documentação oficial Microsoft

- [Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/)
- [Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)
- [Question Answering](https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview)
- [Conversational Language Understanding](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)

### 8.2 Conteúdo complementar

Os estudos foram relacionados aos materiais do **Bootcamp Suzano — Python Developer**, da DIO, e complementados pela documentação oficial da Microsoft.

---

## 9. Documentação e evidências

- [**Evidências**](./evidencias/) — organização dos registros da prática;
- [**Resultados**](./resultados/) — aprendizados, competências e conclusões;
- [**Fontes**](./fontes/) — documentação oficial e materiais complementares.

---

## 10. Resultado do projeto

O resultado principal é uma documentação técnica estruturada que diferencia recursos explorados no laboratório de conteúdos estudados conceitualmente.

Para detalhes, consulte [**Resultados**](./resultados/).

---

## 11. Contato

**Autor:** Nágyla Silva  
**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**GitHub:** [silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

**LinkedIn:** [Nágyla Silva](https://www.linkedin.com/in/n%C3%A1gyla-silva-215aba35/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*