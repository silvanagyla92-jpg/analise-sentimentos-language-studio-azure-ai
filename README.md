# Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI

## 1. Sobre o projeto

Repositório desenvolvido como entregável do desafio de projeto do **Bootcamp Suzano — Python Developer**, da [DIO](https://www.dio.me/), com foco na exploração de recursos de **Inteligência Artificial, Processamento de Linguagem Natural (NLP) e tecnologias de fala do ecossistema Microsoft Azure**.

O projeto reúne estudos, experimentações, conceitos técnicos e aprendizados relacionados ao **Azure Language / Language Studio** e ao **Azure Speech / Speech Studio**, além da exploração conceitual de tecnologias relacionadas à linguagem conversacional, sistemas de perguntas e respostas e agentes de IA.

> **TL;DR:** Projeto de aprendizagem em Azure AI com foco em **NLP, análise de sentimentos, mineração de opinião, reconhecimento de entidades, processamento de texto e fala**. Também foram estudados conceitualmente **Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service**. O repositório foi estruturado como documentação técnica no GitHub.

Este laboratório teve como objetivo explorar recursos de Inteligência Artificial voltados para **linguagem natural e fala**, utilizando interfaces e serviços do ecossistema Azure AI.

No contexto do desafio, foram abordados conceitos e funcionalidades relacionados a:

- Processamento de Linguagem Natural (NLP);
- análise de sentimentos;
- mineração de opinião;
- extração de frases-chave;
- reconhecimento de entidades nomeadas (NER);
- detecção de idioma;
- sumarização;
- processamento de fala;
- conversão de fala em texto;
- compreensão de linguagem conversacional;
- sistemas de perguntas e respostas;
- integração conceitual entre serviços de fala e linguagem.

O **Azure Language** disponibiliza recursos para processamento de linguagem natural, incluindo análise de sentimentos, mineração de opinião, reconhecimento de entidades, extração de frases-chave, detecção de idioma, sumarização e outros cenários de processamento de texto.

O **Speech Studio** oferece uma interface para explorar recursos do Azure Speech, incluindo conversão de fala em texto, tradução de fala, avaliação de pronúncia, síntese de voz e outros recursos relacionados ao processamento de fala.

> **Nota sobre o escopo:** os recursos relacionados ao Azure Language / Language Studio e Azure Speech / Speech Studio foram explorados no contexto do laboratório. **Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service foram estudados conceitualmente por meio da documentação oficial da Microsoft e dos materiais do desafio.** Esses recursos não são apresentados como implementações práticas realizadas neste projeto.

---

## 2. Navegação do projeto

A documentação foi organizada em áreas temáticas para facilitar a consulta e separar os conteúdos práticos, conceituais, evidências, resultados e fontes.

| Área | Conteúdo |
|---|---|
| [**Azure Language**](./azure-language/) | Recursos de NLP explorados no Azure Language / Language Studio, incluindo análise de sentimentos, mineração de opinião, frases-chave, entidades, detecção de idioma e sumarização. |
| [**Azure Speech**](./azure-speech/) | Recursos de fala estudados no Azure Speech / Speech Studio, incluindo Speech to Text, Batch Speech to Text, Text to Speech, Speech Translation, Pronunciation Assessment e Custom Speech. |
| [**Estudos conceituais**](./estudos-conceituais/) | Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service, tratados como estudos conceituais. |
| [**Evidências**](./evidencias/) | Organização das evidências da prática, critérios de documentação e registro das atividades realizadas. |
| [**Resultados**](./resultados/) | Aprendizados, competências desenvolvidas, limitações, conclusões e possíveis próximos passos. |
| [**Fontes**](./fontes/) | Documentação oficial da Microsoft, materiais da DIO e critérios utilizados para seleção das referências. |

### Estrutura do repositório

```text
analise-sentimentos-language-studio-azure-ai/
│
├── README.md
│
├── azure-language/
│   └── README.md
│
├── azure-speech/
│   └── README.md
│
├── estudos-conceituais/
│   └── README.md
│
├── evidencias/
│   └── README.md
│
├── resultados/
│   └── README.md
│
└── fontes/
    └── README.md
```

---

## 3. O que foi praticado

### 3.1 Azure Language e Language Studio

O **Azure Language** fornece recursos de processamento de linguagem natural que podem ser utilizados para analisar, classificar, extrair informações e compreender conteúdo textual.

Os recursos a seguir foram explorados diretamente na interface do **Language Studio**, no contexto do laboratório.

### 3.2 Análise de sentimentos e mineração de opinião

Permite analisar textos para identificar a polaridade de sentimentos e opiniões expressas no conteúdo.

Possíveis aplicações incluem:

- avaliações de clientes;
- comentários;
- pesquisas de satisfação;
- feedbacks;
- interações de atendimento;
- análise de opiniões.

### 3.3 Extração de frases-chave

Permite identificar termos e expressões relevantes presentes em um texto, auxiliando na identificação dos principais assuntos abordados.

Pode ser utilizada em cenários como:

- classificação de conteúdo;
- organização de documentos;
- análise de feedback;
- indexação;
- descoberta de tópicos.

### 3.4 Reconhecimento de Entidades Nomeadas (NER)

Permite identificar e classificar elementos presentes em um texto, como:

- pessoas;
- organizações;
- locais;
- datas;
- outras categorias de entidades.

Esse processamento pode contribuir para transformar informações textuais em dados estruturados.

### 3.5 Detecção de idioma

Permite identificar automaticamente o idioma de um conteúdo textual, sendo útil em aplicações que precisam processar informações provenientes de diferentes idiomas.

### 3.6 Sumarização

Permite produzir versões resumidas de documentos, conversas e outros conteúdos extensos, facilitando a identificação das principais informações.

### 3.7 Azure Speech e Speech Studio

O **Speech Studio** é uma interface baseada em navegador para explorar recursos do Azure Speech.

Entre os recursos estudados estão:

- **Speech to Text** — conversão de fala em texto;
- **Batch Speech to Text** — transcrição em lote;
- **Text to Speech** — síntese de voz;
- **Speech Translation** — tradução de fala;
- **Pronunciation Assessment** — avaliação de pronúncia;
- **Custom Speech** — recursos de personalização para reconhecimento de fala.

Esses recursos demonstram como tecnologias de IA podem ser aplicadas ao processamento de voz, áudio e linguagem natural.

---

## 4. Aprendizados e competências

A realização do projeto permitiu consolidar conhecimentos sobre **Processamento de Linguagem Natural, análise automatizada de texto, processamento de fala e utilização de serviços de IA em ambiente cloud**.

Entre os principais conhecimentos desenvolvidos estão:

- fundamentos de NLP;
- análise de sentimentos e mineração de opinião;
- extração de informações a partir de texto;
- reconhecimento de entidades;
- processamento multilíngue;
- sumarização;
- processamento e transcrição de fala;
- leitura e interpretação de documentação técnica;
- exploração de serviços de IA da Microsoft;
- documentação de estudos e experimentos;
- organização de projetos técnicos no GitHub.

Esses conhecimentos apresentam relação com competências utilizadas em áreas como:

- Inteligência Artificial;
- AI Training;
- AI Response Evaluation;
- Data Annotation;
- Quality Assurance (QA);
- Processamento de Linguagem Natural;
- análise e classificação de dados textuais;
- documentação técnica.

---

## 5. Exploração conceitual

Além dos recursos explorados no contexto do laboratório, foram estudados conceitualmente outros componentes do ecossistema Microsoft relacionados à linguagem natural e aplicações conversacionais.

### 5.1 Question Answering

O **Question Answering** foi estudado como recurso para criação de sistemas capazes de responder perguntas com base em informações previamente estruturadas e fontes de conhecimento específicas.

Possíveis aplicações incluem:

- atendimento ao cliente;
- bases de conhecimento;
- suporte;
- FAQ automatizado;
- sistemas de recuperação de informações.

A documentação atual do Azure Language apresenta o **Custom Question Answering (CQA)** como a evolução do antigo QnA Maker para novos desenvolvimentos.

> **Escopo:** este recurso foi explorado conceitualmente e não é apresentado como uma implementação prática realizada neste projeto.

### 5.2 Conversational Language Understanding (CLU)

A **Conversational Language Understanding (CLU)** foi estudada conceitualmente como tecnologia utilizada para identificar **intenções e entidades** em linguagem natural.

Exemplo conceitual:

**Entrada:**

> "Quero consultar o status do meu pedido."

**Intenção:**

> Consultar pedido

**Entidade:**

> Pedido

Esse tipo de processamento pode ser utilizado em agentes e aplicações conversacionais.

> **Escopo:** CLU foi estudada conceitualmente e não é apresentada como implementação prática neste repositório.

### 5.3 Microsoft Copilot Studio

O **Microsoft Copilot Studio** foi explorado conceitualmente como plataforma para criação e personalização de agentes e experiências conversacionais.

O estudo permitiu compreender sua relação com conceitos de:

- agentes;
- intenções;
- entidades;
- tópicos;
- experiências conversacionais;
- automação baseada em linguagem natural.

### 5.4 Azure AI Bot Service

O **Azure AI Bot Service** também foi estudado conceitualmente no contexto das tecnologias utilizadas para criação de bots e experiências conversacionais.

Entre os possíveis cenários de aplicação estão:

- atendimento ao cliente;
- suporte;
- FAQ automatizado;
- agentes virtuais;
- aplicações web;
- experiências multicanal.

> **Importante:** Question Answering, CLU, Microsoft Copilot Studio e Azure AI Bot Service são apresentados nesta seção como **conhecimentos explorados conceitualmente**, não como soluções implementadas neste projeto.

---

## 6. Relação entre fala e linguagem

Um dos conceitos importantes estudados é a possibilidade de combinar diferentes capacidades de IA em um mesmo fluxo.

### 6.1 Fluxo conceitual

Um exemplo conceitual é:

**Voz → Transcrição → Análise de linguagem → Resultado**

Um possível fluxo seria:

1. O usuário fornece uma gravação de áudio.
2. Um serviço de Speech realiza a conversão de fala em texto.
3. O texto resultante pode ser processado por recursos do Azure Language.
4. O conteúdo pode ser analisado para identificar sentimento, entidades, frases-chave ou idioma.
5. Os resultados podem ser utilizados por uma aplicação para gerar informações ou apoiar análises.

Esse fluxo representa uma possibilidade de integração entre diferentes capacidades de IA para transformar dados não estruturados, como voz e texto, em informações úteis.

### 6.2 Exemplo de aplicação

Em um cenário de atendimento ao cliente:

**Cliente fala → Speech to Text → Transcrição → Análise de sentimento → Identificação de informações → Análise**

O exemplo demonstra conceitualmente como recursos de processamento de fala e linguagem podem ser combinados em um fluxo de análise.

> **Observação:** o fluxo apresentado representa uma possibilidade de aplicação dos serviços estudados e **não corresponde a uma implementação integrada realizada neste repositório**.

---

## 7. Aplicações relacionadas

Os conhecimentos estudados neste projeto podem ser relacionados a diferentes cenários de aplicação de IA, incluindo:

- análise de satisfação de clientes;
- análise de feedbacks;
- classificação de opiniões;
- processamento automatizado de documentos;
- atendimento automatizado;
- chatbots e agentes conversacionais;
- análise de chamadas de atendimento;
- transcrição de áudio;
- sistemas de perguntas e respostas;
- extração automatizada de informações;
- aplicações multilíngues;
- automação de processos baseados em linguagem natural.

Esses cenários representam **possibilidades de aplicação dos conhecimentos estudados** e não devem ser interpretados como soluções implementadas neste repositório.

---

## 8. Conteúdo explorado

### 8.1 Documentação oficial Microsoft

- [Azure Language — documentação oficial](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/)
- [Azure AI Bot Service — página oficial](https://azure.microsoft.com/en-us/products/ai-services/ai-bot-service/)
- [Compreensão de linguagem coloquial no Microsoft Copilot Studio](https://learn.microsoft.com/pt-br/microsoft-copilot-studio/advanced-clu-get-started)
- [Speech Studio — documentação oficial](https://learn.microsoft.com/pt-br/azure/ai-services/speech-service/speech-studio-overview)

### 8.2 Conteúdo complementar

Os conceitos estudados durante o desafio foram consolidados neste README utilizando como referência a documentação oficial da Microsoft e os materiais disponibilizados durante o **Bootcamp Suzano — Python Developer**, da DIO.

A documentação foi utilizada para ampliar a compreensão sobre:

- processamento de linguagem natural;
- análise de sentimentos;
- processamento de fala;
- linguagem conversacional;
- sistemas de perguntas e respostas;
- agentes e chatbots;
- aplicações de IA baseadas em linguagem natural.

---

## 9. Documentação e evidências

Como o repositório atualmente possui documentação distribuída em áreas específicas, cada seção pode ser consultada diretamente:

- [**Evidências da prática**](./evidencias/) — registros e critérios para documentar as atividades realizadas;
- [**Resultados e aprendizados**](./resultados/) — consolidação dos conhecimentos, competências, limitações e conclusões;
- [**Fontes e referências**](./fontes/) — documentação oficial da Microsoft e demais materiais utilizados.

As informações apresentadas neste repositório foram consolidadas a partir da prática realizada durante o desafio e dos estudos complementares relacionados às tecnologias exploradas.

---

## 10. Resultado do projeto

O projeto consolida uma experiência de aprendizagem relacionada a **Inteligência Artificial, Processamento de Linguagem Natural, análise de sentimentos, processamento de fala e serviços de IA em nuvem**.

O resultado principal é a organização dos conhecimentos estudados em uma documentação técnica estruturada, diferenciando claramente os recursos explorados no laboratório daqueles estudados apenas conceitualmente.

Para consultar os resultados detalhados, acesse [**Resultados**](./resultados/).

---

## 11. Conhecimentos e tecnologias

**Inteligência Artificial | NLP | Azure AI | Azure Language | Language Studio | Azure Speech | Speech Studio | Análise de Sentimentos | Mineração de Opinião | NER | Processamento de Texto | Processamento de Fala | Documentação Técnica | GitHub**

---

## 12. Contexto do projeto

**Bootcamp:** Suzano — Python Developer  
**Plataforma:** DIO

**Área de interesse:** Inteligência Artificial, AI Response Evaluation, AI Training, Data Annotation, QA e tecnologias relacionadas à IA.

---

## 13. Autora

**Nágyla Silva**

---

## 14. Repositório

**GitHub:**  
[Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI](https://github.com/silvanagyla92-jpg/analise-sentimentos-language-studio-azure-ai)
