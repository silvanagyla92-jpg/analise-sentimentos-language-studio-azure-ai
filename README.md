# Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI

## 1. Sobre o projeto

Repositório desenvolvido como entregável do desafio de projeto do **Bootcamp Suzano — Python Developer**, da DIO, com foco na exploração de **Inteligência Artificial, Processamento de Linguagem Natural (NLP) e tecnologias de fala do ecossistema Microsoft Azure**.

O projeto reúne estudos, conceitos técnicos e aprendizados relacionados ao **Azure Language / Language Studio** e ao **Azure Speech / Speech Studio**, além da exploração conceitual de tecnologias relacionadas à linguagem conversacional, sistemas de perguntas e respostas e agentes de IA.

> **TL;DR:** Projeto de aprendizagem em Azure AI com foco em **NLP, análise de sentimentos, mineração de opinião, extração de informações, detecção de idioma, sumarização e processamento de fala**. Também foram estudados conceitualmente **Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service**.

### Escopo

Os recursos de Azure Language e Azure Speech são documentados com base no estudo da documentação oficial e nos conteúdos de formação da Microsoft concluídos pela autora. Question Answering, CLU, Microsoft Copilot Studio e Azure AI Bot Service são tratados como **estudos conceituais**, e não como implementações práticas realizadas neste repositório.

A ausência de uma assinatura/ambiente Azure disponível para este projeto impediu a execução dos serviços diretamente na plataforma. Por isso, **não são apresentados neste repositório resultados experimentais, métricas, capturas de tela ou integrações que não tenham sido efetivamente realizadas**.

---

## 2. Navegação do projeto

A documentação está organizada por domínio e finalidade. As áreas técnicas são separadas dos estudos conceituais e das áreas de evidências, resultados e fontes.

| Área | Conteúdo |
|---|---|
| [**Azure Language**](./azure-language/) | NLP aplicado a texto: Sentiment Analysis, Opinion Mining, Key Phrase Extraction, Named Entity Recognition (NER), Language Detection e Summarization. |
| [**Azure Speech**](./azure-speech/) | Tecnologias de fala: Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment. |
| [**Estudos conceituais**](./estudos-conceituais/) | Question Answering, Conversational Language Understanding (CLU), Copilot Studio e Bot Service. |
| [**Evidências**](./evidencias/) | Evidências documentais, critérios de registro e distinção entre estudo teórico e execução prática. |
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

## 3. Formação e certificações relacionadas

A fundamentação deste projeto também está relacionada a **cursos e módulos oficiais da Microsoft Learn concluídos pela autora, com certificados correspondentes**.

### Formação Microsoft Learn relacionada ao projeto

| Formação | Plataforma | Status | Relação com o projeto |
|---|---|---|---|
| **Introdução à análise de texto no Azure** | Microsoft Learn | **Concluído / certificado** | Fundamenta os conceitos de análise de texto e NLP utilizados na área Azure Language. |
| **Analisar texto com a Linguagem do Azure no Foundry Tools** | Microsoft Learn | **Concluído / certificado** | Relaciona-se a detecção de idioma, entidades e análise de texto. |
| **Desenvolver soluções de linguagem natural no Azure** | Microsoft Learn | **Concluído / certificado** | Consolida a construção conceitual de soluções de linguagem natural. |
| **Introdução à fala no Azure** | Microsoft Learn | **Concluído / certificado** | Fundamenta Speech to Text, Text to Speech e conceitos de voz. |
| **Introdução aos conceitos de fala de IA** | Microsoft Learn | **Concluído / certificado** | Apoia a compreensão dos fundamentos de IA aplicada à fala. |
| **Criar aplicativos com reconhecimento de fala usando o Azure Speech nas ferramentas do Microsoft Foundry** | Microsoft Learn | **Concluído / certificado** | Relaciona-se à utilização conceitual de reconhecimento e síntese de fala. |
| **Introdução aos conceitos de processamento de linguagem natural** | Microsoft Learn | **Concluído / certificado** | Fundamenta tokenização, modelos de linguagem, análise estatística e semântica. |

> **Comprovação:** os certificados são de posse da autora. Os links oficiais dos cursos e módulos estão organizados em [**Fontes → Microsoft Azure**](./fontes/microsoft-azure/). Os dados de certificado que não foram transcritos neste README não são inferidos nem inventados.

### Como a formação se conecta ao portfólio

A formação Microsoft Learn representa **conhecimento formal concluído e certificado**. A documentação deste repositório transforma parte desse conhecimento em material estruturado de estudo, análise e referência.

Isso deve ser diferenciado de experiência profissional: possuir certificação demonstra conclusão da formação, enquanto a execução prática de um serviço específico exige ambiente, recursos e evidências correspondentes.

---

## 4. O que foi estudado

### 4.1 Azure Language e Language Studio

O Azure Language reúne capacidades de NLP para analisar, classificar e extrair informações de texto. No projeto são estudados recursos relacionados a sentimento, opinião, frases-chave, entidades, idioma e sumarização.

A documentação específica de cada recurso foi organizada na pasta [**Azure Language**](./azure-language/), permitindo aprofundar cada capacidade sem sobrecarregar este README principal.

### 4.2 Análise de sentimentos e mineração de opinião

A **Sentiment Analysis** procura identificar a orientação geral de um texto e fornece pontuações de confiança associadas às previsões. Dependendo do recurso e da operação utilizada, a análise pode considerar documentos e sentenças.

A **Opinion Mining** acrescenta uma camada de granularidade ao relacionar opiniões e sentimentos a aspectos ou alvos mencionados no texto. Essa diferença é importante: um comentário pode ser globalmente positivo e, ao mesmo tempo, apresentar avaliações negativas sobre um aspecto específico.

Aplicações possíveis incluem avaliações de produtos, feedbacks, pesquisas de satisfação, comentários, atendimento ao cliente e triagem de grandes volumes de texto. Os resultados automatizados devem ser interpretados considerando contexto, ironia, ambiguidade, domínio e qualidade dos dados.

### 4.3 Extração de informações

**Key Phrase Extraction** procura identificar conceitos ou expressões relevantes de um texto, podendo apoiar indexação, organização temática e síntese de grandes volumes documentais.

**Named Entity Recognition (NER)** identifica entidades nomeadas e suas categorias, como pessoas, organizações e locais, ajudando a transformar texto não estruturado em informações mais estruturadas.

Esses recursos não substituem uma modelagem de dados completa: a utilidade do resultado depende do idioma, contexto, domínio e qualidade do texto de entrada.

### 4.4 Detecção de idioma

A **Language Detection** identifica o idioma predominante de um texto e pode apoiar fluxos multilíngues. Em uma arquitetura maior, a identificação do idioma pode ser utilizada para selecionar posteriormente um modelo, uma voz, uma estratégia de tradução ou um processo de NLP compatível.

### 4.5 Sumarização

A **Summarization** busca produzir uma representação condensada de documentos ou conversas, reduzindo o volume de informação necessário para uma primeira leitura.

A sumarização deve ser avaliada quanto à fidelidade ao conteúdo original. Quando informações omitidas puderem afetar decisões, a revisão humana continua sendo importante.

### 4.6 Azure Speech e Speech Studio

São estudados **Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment**, além de conceitos relacionados ao ecossistema Speech.

Esses recursos mostram a relação entre áudio, voz, texto e linguagem: uma aplicação pode transformar fala em texto, processar o texto com recursos de NLP e, em determinados cenários, produzir novamente uma saída de voz.

A documentação específica está organizada em [**Azure Speech**](./azure-speech/).

---

## 5. Prática, estudo e limites do projeto

Para manter a documentação tecnicamente fiel, este projeto diferencia três níveis de conhecimento:

### 5.1 Conhecimento formal concluído

Corresponde aos **cursos e módulos Microsoft Learn concluídos e certificados pela autora**. Esses conteúdos constituem a base de formação utilizada para compreender os serviços e conceitos apresentados no repositório.

### 5.2 Conhecimento técnico documentado

Corresponde ao conteúdo produzido nas pastas `azure-language/`, `azure-speech/`, `estudos-conceituais/`, `resultados/` e `fontes/`. Nessa camada são explicados conceitos, funcionalidades, fluxos, aplicações possíveis, limitações e relações entre tecnologias.

### 5.3 Execução prática

A execução direta dos serviços Azure exige um ambiente compatível e recursos disponíveis na plataforma. Como não há uma assinatura Azure disponível para este projeto, **não são reivindicados testes práticos, métricas, capturas de tela, chamadas de API ou integrações que não tenham sido efetivamente realizados**.

Consequentemente, exemplos de entradas e saídas apresentados na documentação devem ser entendidos como **exemplos didáticos ou descrições do comportamento documentado**, e não como resultados produzidos pela autora no ambiente Azure.

Essa distinção evita confundir **certificação**, **conhecimento técnico** e **experiência prática comprovada**.

---

## 6. Aprendizados e competências

O projeto consolidou conhecimentos de **NLP, análise automatizada de texto, processamento de fala, serviços cloud, leitura de documentação técnica, avaliação crítica de resultados e organização de documentação no GitHub**.

Entre os conhecimentos técnicos desenvolvidos estão:

- compreensão do ciclo texto → processamento → resultado;
- diferenciação entre análise de sentimento e mineração de opinião;
- identificação de usos de extração de frases-chave e entidades;
- compreensão de fluxos multilíngues e de fala;
- leitura e interpretação de documentação de serviços cloud;
- atenção a limitações, confiança, contexto e qualidade dos dados;
- organização de conhecimento técnico em uma estrutura versionada.

Essas competências apresentam relação com **AI Training, AI Response Evaluation, Data Annotation, QA e documentação técnica**. A relação deve ser entendida como **competência desenvolvida por meio de estudo e documentação**, e não como comprovação de experiência profissional formal nessas funções.

---

## 7. Exploração conceitual

### 7.1 Question Answering

Question Answering foi estudado como abordagem para construir experiências capazes de responder perguntas a partir de uma base de conhecimento. O conceito é diferente de uma simples busca por palavras-chave: o objetivo é interpretar a pergunta e recuperar ou produzir uma resposta apoiada pelo conhecimento disponível.

No contexto deste projeto, o recurso foi estudado para compreender arquiteturas de perguntas e respostas, preparação de conhecimento e relação com aplicações conversacionais.

### 7.2 Conversational Language Understanding (CLU)

**CLU** permite criar modelos personalizados para interpretar intenções e extrair entidades de enunciados. Conceitualmente, isso ajuda uma aplicação conversacional a responder à pergunta: **“o que o usuário pretende fazer e quais informações importantes ele forneceu?”**

No projeto, o tema foi estudado para compreender a diferença entre intenção, entidade, treinamento, avaliação e integração em uma aplicação conversacional.

A documentação atual da Microsoft deve ser consultada para informações de ciclo de vida e alternativas recomendadas antes de novos projetos.

### 7.3 Microsoft Copilot Studio

Foi estudado conceitualmente como plataforma para criação e personalização de agentes e experiências conversacionais. O estudo permite compreender temas como agentes, tópicos, instruções, fontes de conhecimento, integração e governança.

### 7.4 Azure AI Bot Service

Foi estudado conceitualmente para compreender arquiteturas de bots, integração com canais e experiências conversacionais. O foco foi entender o papel de componentes de conversação e integração, e não apresentar um bot funcional como entrega deste repositório.

> **Importante:** esses quatro temas são apresentados como **estudos conceituais**, não como soluções implementadas neste projeto.

---

## 8. Relação entre fala e linguagem

Um fluxo conceitual estudado é:

**Voz → Speech to Text → Texto → Azure Language → Resultado**

Por exemplo, em um cenário de atendimento ao cliente, uma gravação poderia ser transcrita e posteriormente analisada para sentimento, entidades, frases-chave ou idioma. Dependendo da necessidade, outros componentes poderiam traduzir ou sintetizar uma resposta.

Esse fluxo ajuda a compreender como diferentes serviços podem compor uma arquitetura de IA multimodal. Entretanto, ele representa **uma possibilidade arquitetural e não uma implementação integrada realizada neste repositório**.

---

## 9. Aplicações relacionadas

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

Esses são **cenários possíveis**, não soluções implementadas neste repositório.

---

## 10. Fontes e documentação

### 10.1 Documentação oficial Microsoft

As fontes oficiais devem ser consideradas a referência técnica prioritária para conceitos, recursos disponíveis, limitações e mudanças de ciclo de vida.

- [Azure Language — Microsoft Learn](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/)
- [Azure Speech — Microsoft Learn](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/)
- [Speech Studio — Microsoft Learn](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-studio-overview)
- [Microsoft Learn — Introdução à análise de texto no Azure](https://learn.microsoft.com/pt-br/training/modules/get-started-text-analysis-azure/)
- [Microsoft Learn — Analisar texto com a Linguagem do Azure no Foundry Tools](https://learn.microsoft.com/pt-br/training/modules/analyze-text-ai-language/)
- [Microsoft Learn — Desenvolver soluções de linguagem natural no Azure](https://learn.microsoft.com/pt-br/training/paths/develop-language-solutions-azure-ai/)
- [Microsoft Learn — Introdução à fala no Azure](https://learn.microsoft.com/pt-br/training/modules/get-started-speech-azure/)
- [Microsoft Learn — Introdução aos conceitos de fala de IA](https://learn.microsoft.com/pt-br/training/modules/introduction-ai-speech/)
- [Microsoft Learn — Criar aplicativos com reconhecimento de fala usando o Azure Speech](https://learn.microsoft.com/pt-br/training/modules/create-speech-enabled-apps/)
- [Microsoft Learn — Introdução aos conceitos de processamento de linguagem natural](https://learn.microsoft.com/pt-br/training/paths/ai-concepts/)

Para o detalhamento por recurso e outras referências, consulte [**Fontes → Microsoft Azure**](./fontes/microsoft-azure/).

### 10.2 Conteúdo complementar

Os estudos também foram relacionados aos materiais do **Bootcamp Suzano — Python Developer**, da DIO. Consulte [**Fontes → DIO**](./fontes/dio/).

---

## 11. Evidências e resultados

A documentação foi organizada para separar **conhecimento, evidência e interpretação**:

- [**Evidências**](./evidencias/) — critérios para registros e documentação das atividades;
- [**Resultados**](./resultados/) — aprendizados, competências, limitações e conclusões;
- [**Fontes**](./fontes/) — documentação oficial e materiais complementares.

Como não houve acesso a uma assinatura Azure para execução dos serviços, as áreas de evidências não apresentam resultados experimentais fictícios. Quando uma atividade prática vier a ser realizada, o registro deverá permitir compreender o recurso utilizado, o contexto, a entrada, a saída observada e a interpretação do resultado.

---

## 12. Resultado do projeto

O resultado principal é uma **documentação técnica estruturada de aprendizagem em Azure AI**, apoiada por formação oficial Microsoft Learn e organizada para demonstrar a capacidade de diferenciar:

- formação certificada × experiência prática;
- conhecimento técnico × evidência de execução;
- estudo conceitual × implementação efetiva;
- possibilidade arquitetural × solução realmente construída;
- resultado automatizado × interpretação humana;
- documentação oficial × material complementar.

O projeto também consolida uma base de conhecimento que pode ser utilizada como referência para estudos posteriores em NLP, avaliação de sistemas de IA, QA, anotação de dados e treinamento de modelos.

Para detalhes, consulte [**Resultados**](./resultados/).

---

## 13. Contato

**Autor:** Nágyla Silva  
**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**GitHub:** [silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

**LinkedIn:** [Nágyla Silva](https://www.linkedin.com/in/n%C3%A1gyla-silva-215aba35/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*