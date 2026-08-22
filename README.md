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
| [**Azure Language**](./azure-language/) | NLP aplicado a texto: Sentiment Analysis, Opinion Mining, Key Phrase Extraction, Named Entity Recognition (NER), Language Detection e Summarization. |
| [**Azure Speech**](./azure-speech/) | Tecnologias de fala: Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment. |
| [**Estudos conceituais**](./estudos-conceituais/) | Question Answering, Conversational Language Understanding (CLU), Copilot Studio e Bot Service. |
| [**Evidências**](./evidencias/) | Organização e critérios para registros das atividades práticas. |
| [**Resultados**](./resultados/) | Aprendizados, competências, limitações e conclusões. |
| [**Fontes**](./fontes/) | Documentação oficial da Microsoft e materiais complementares. |

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

### Navegação por domínio

```text
                         README.md
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
      Azure Language   Azure Speech   Estudos conceituais
             │              │              │
      ┌──────┼──────┐   ┌───┼────┐    ┌────┼─────┐
      ▼      ▼      ▼   ▼   ▼    ▼    ▼    ▼     ▼
  Sentiment Opinion  NER  STT TTS  Translation Q&A  CLU  Copilot/Bot
  + demais NLP       │
             └───────┼───────────────┐
                     ▼               ▼
                Evidências       Resultados
                     │               │
                     └───────┬───────┘
                             ▼
                           Fontes
```

O diagrama representa **a organização e a navegação do conhecimento no repositório**. O fluxo entre Azure Speech e Azure Language apresentado nas seções seguintes é uma possibilidade arquitetural; ele **não significa que uma integração ponta a ponta tenha sido implementada neste repositório**.

### Acesso rápido às subáreas

- [Sentiment Analysis](./azure-language/sentiment-analysis/)
- [Opinion Mining](./azure-language/opinion-mining/)
- [Key Phrase Extraction](./azure-language/key-phrase-extraction/)
- [Named Entity Recognition](./azure-language/named-entity-recognition/)
- [Language Detection](./azure-language/language-detection/)
- [Summarization](./azure-language/summarization/)
- [Speech to Text](./azure-speech/speech-to-text/)
- [Text to Speech](./azure-speech/text-to-speech/)
- [Speech Translation](./azure-speech/speech-translation/)
- [Pronunciation Assessment](./azure-speech/pronunciation-assessment/)
- [Question Answering](./estudos-conceituais/question-answering/)
- [Conversational Language Understanding](./estudos-conceituais/conversational-language-understanding/)
- [Microsoft Copilot Studio](./estudos-conceituais/copilot-studio/)
- [Azure AI Bot Service](./estudos-conceituais/bot-service/)

---

## 3. O que foi praticado

### 3.1 Azure Language e Language Studio

O Azure Language reúne capacidades de NLP para analisar, classificar e extrair informações de texto. No laboratório foram explorados recursos relacionados a sentimento, opinião, frases-chave, entidades, idioma e sumarização.

A documentação específica de cada recurso foi organizada na pasta [**Azure Language**](./azure-language/), permitindo aprofundar cada capacidade sem sobrecarregar este README principal.

### 3.2 Análise de sentimentos e mineração de opinião

A **Sentiment Analysis** procura identificar a orientação geral de um texto e fornece pontuações de confiança associadas às previsões. Dependendo do recurso e da operação utilizada, a análise pode considerar documentos e sentenças.

A **Opinion Mining** acrescenta uma camada de granularidade ao relacionar opiniões e sentimentos a aspectos ou alvos mencionados no texto. Essa diferença é importante: um comentário pode ser globalmente positivo e, ao mesmo tempo, apresentar avaliações negativas sobre um aspecto específico.

Aplicações possíveis incluem avaliações de produtos, feedbacks, pesquisas de satisfação, comentários, atendimento ao cliente e triagem de grandes volumes de texto. Os resultados automatizados devem ser interpretados considerando contexto, ironia, ambiguidade, domínio e qualidade dos dados.

### 3.3 Extração de informações

**Key Phrase Extraction** procura identificar conceitos ou expressões relevantes de um texto, podendo apoiar indexação, organização temática e síntese de grandes volumes documentais.

**Named Entity Recognition (NER)** identifica entidades nomeadas e suas categorias, como pessoas, organizações e locais, ajudando a transformar texto não estruturado em informações mais estruturadas.

Esses recursos não substituem uma modelagem de dados completa: a utilidade do resultado depende do idioma, contexto, domínio e qualidade do texto de entrada.

### 3.4 Detecção de idioma

A **Language Detection** identifica o idioma predominante de um texto e pode apoiar fluxos multilíngues. Em uma arquitetura maior, a identificação do idioma pode ser utilizada para selecionar posteriormente um modelo, uma voz, uma estratégia de tradução ou um processo de NLP compatível.

### 3.5 Sumarização

A **Summarization** busca produzir uma representação condensada de documentos ou conversas, reduzindo o volume de informação necessário para uma primeira leitura.

A sumarização deve ser avaliada quanto à fidelidade ao conteúdo original. Quando informações omitidas puderem afetar decisões, a revisão humana continua sendo importante.

### 3.6 Azure Speech e Speech Studio

Foram estudados **Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment**, além de conceitos relacionados ao ecossistema Speech.

Esses recursos mostram a relação entre áudio, voz, texto e linguagem: uma aplicação pode transformar fala em texto, processar o texto com recursos de NLP e, em determinados cenários, produzir novamente uma saída de voz.

A documentação específica está organizada em [**Azure Speech**](./azure-speech/).

---

## 4. Aprendizados e competências

O projeto consolidou conhecimentos de **NLP, análise automatizada de texto, processamento de fala, serviços cloud, leitura de documentação técnica, avaliação crítica de resultados e organização de documentação no GitHub**.

Entre os conhecimentos técnicos desenvolvidos estão:

- compreensão do ciclo texto → processamento → resultado;
- diferenciação entre análise de sentimento e mineração de opinião;
- identificação de usos de extração de frases-chave e entidades;
- compreensão de fluxos multilíngues e de fala;
- leitura e interpretação de documentação de serviços cloud;
- atenção a limitações, confiança, contexto e qualidade dos dados;
- organização de conhecimento técnico em uma estrutura versionada.

Essas competências apresentam relação com **AI Training, AI Response Evaluation, Data Annotation, QA e documentação técnica**. A relação deve ser entendida como **competência desenvolvida por meio de estudo, prática e documentação do projeto**, e não como comprovação de experiência profissional formal nessas funções.

---

## 5. Exploração conceitual

### 5.1 Question Answering

Question Answering foi estudado como abordagem para construir experiências capazes de responder perguntas a partir de uma base de conhecimento. O conceito é diferente de uma simples busca por palavras-chave: o objetivo é interpretar a pergunta e recuperar ou produzir uma resposta apoiada pelo conhecimento disponível.

No contexto deste projeto, o recurso foi estudado para compreender arquiteturas de perguntas e respostas, preparação de conhecimento e relação com aplicações conversacionais.

A documentação atual da Microsoft informa mudanças de ciclo de vida para **Custom Question Answering** e orienta novos projetos a considerar as alternativas atuais do Microsoft Foundry.

### 5.2 Conversational Language Understanding (CLU)

**CLU** permite criar modelos personalizados para interpretar intenções e extrair entidades de enunciados. Conceitualmente, isso ajuda uma aplicação conversacional a responder à pergunta: **“o que o usuário pretende fazer e quais informações importantes ele forneceu?”**

No projeto, o tema foi estudado para compreender a diferença entre intenção, entidade, treinamento, avaliação e integração em uma aplicação conversacional.

A documentação atual da Microsoft informa que o recurso será descontinuado no Azure Language em **31 de março de 2029** e recomenda considerar Microsoft Foundry para novos projetos.

### 5.3 Microsoft Copilot Studio

Foi estudado conceitualmente como plataforma para criação e personalização de agentes e experiências conversacionais. O estudo permite compreender temas como agentes, tópicos, instruções, fontes de conhecimento, integração e governança.

### 5.4 Azure AI Bot Service

Foi estudado conceitualmente para compreender arquiteturas de bots, integração com canais e experiências conversacionais. O foco foi entender o papel de componentes de conversação e integração, e não apresentar um bot funcional como entrega deste repositório.

> **Importante:** esses quatro temas são apresentados como **estudos conceituais**, não como soluções implementadas neste projeto.

---

## 6. Relação entre fala e linguagem

Um fluxo conceitual estudado é:

**Voz → Speech to Text → Texto → Azure Language → Resultado**

Por exemplo, em um cenário de atendimento ao cliente, uma gravação poderia ser transcrita e posteriormente analisada para sentimento, entidades, frases-chave ou idioma. Dependendo da necessidade, outros componentes poderiam traduzir ou sintetizar uma resposta.

Esse fluxo ajuda a compreender como diferentes serviços podem compor uma arquitetura de IA multimodal. Entretanto, ele representa **uma possibilidade arquitetural e não uma implementação integrada realizada neste repositório**.

---

## 7. Aplicações relacionadas

Os conhecimentos estudados podem ser relacionados a:

- análise de satisfação e feedback;
- classificação e interpretação de opiniões;
- processamento documental;
- extração de informações de textos;
- análise de chamadas e transcrições;
- atendimento automatizado;
- aplicações multilíngues;
- sistemas de perguntas e respostas;
- agentes e experiências conversacionais;
- avaliação de qualidade de pronúncia e fala.

Esses são **cenários possíveis**, não soluções implementadas neste repositório. A finalidade desta seção é mostrar como os conhecimentos estudados podem ser transferidos para problemas reais sem confundir possibilidade de aplicação com evidência de implementação.

---

## 8. Conteúdo explorado

### 8.1 Documentação oficial Microsoft

As fontes oficiais devem ser consideradas a referência técnica prioritária para conceitos, APIs, recursos disponíveis, limitações e mudanças de ciclo de vida.

- [Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/)
- [Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)
- [Question Answering](https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview)
- [Conversational Language Understanding](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)

Para o detalhamento por recurso, consulte [**Fontes → Microsoft Azure**](./fontes/microsoft-azure/).

### 8.2 Conteúdo complementar

Os estudos foram relacionados aos materiais do **Bootcamp Suzano — Python Developer**, da DIO, e complementados pela documentação oficial da Microsoft.

O material complementar é utilizado como contexto educacional. Para informações técnicas que possam mudar ao longo do tempo, a documentação oficial da Microsoft é priorizada.

Consulte [**Fontes → DIO**](./fontes/dio/).

---

## 9. Documentação e evidências

A documentação foi organizada para separar **conhecimento, evidência e interpretação**:

- [**Evidências**](./evidencias/) — organização dos registros das atividades práticas;
- [**Resultados**](./resultados/) — aprendizados, competências, limitações e conclusões;
- [**Fontes**](./fontes/) — documentação oficial e materiais complementares.

Quando uma atividade prática for documentada com evidência, o registro deve permitir compreender, sempre que possível, **o recurso utilizado, o contexto da atividade, a entrada, a saída observada e a interpretação do resultado**.

Não devem ser apresentados como evidência resultados, capturas de tela, métricas ou implementações que não tenham sido realmente realizados ou registrados.

---

## 10. Resultado do projeto

O resultado principal é uma **documentação técnica estruturada de aprendizagem em Azure AI**, organizada para demonstrar não apenas o que cada tecnologia faz, mas também a capacidade de diferenciar:

- prática realizada × estudo conceitual;
- possibilidade arquitetural × implementação efetiva;
- resultado automatizado × interpretação humana;
- documentação oficial × material complementar;
- conhecimento técnico × evidência de experiência.

O projeto também consolida uma base de conhecimento que pode ser utilizada como referência para estudos posteriores em NLP, avaliação de sistemas de IA, QA, anotação de dados e treinamento de modelos.

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