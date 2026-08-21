# Estudos Conceituais

## 1. Objetivo

Esta seção reúne conteúdos do ecossistema Microsoft relacionados a **linguagem natural, sistemas conversacionais, agentes e perguntas e respostas** que foram estudados conceitualmente durante o projeto.

O README principal estabelece uma distinção importante: **Question Answering, Conversational Language Understanding (CLU), Microsoft Copilot Studio e Azure AI Bot Service não são apresentados como implementações práticas realizadas neste repositório**.

## 2. Question Answering

O **Custom Question Answering (CQA)** é uma capacidade de NLP voltada à criação de aplicações conversacionais sobre dados de conhecimento. Um projeto pode utilizar FAQs, manuais, documentos e outras fontes para construir uma base de conhecimento capaz de retornar respostas às perguntas dos usuários.

### Conceito

```text
Pergunta do usuário
        │
        ▼
Base de conhecimento
        │
        ▼
Recuperação da resposta
        │
        ▼
Resposta ao usuário
```

### Possíveis aplicações

- FAQ automatizado;
- suporte ao cliente;
- bases de conhecimento;
- assistentes virtuais;
- recuperação de informações em documentos.

A documentação atual da Microsoft informa que o **Custom Question Answering será descontinuado no Azure Language em 31 de março de 2029** e orienta novos projetos a utilizar as capacidades do Microsoft Foundry. Portanto, esse conteúdo é registrado aqui como conhecimento conceitual e histórico da tecnologia estudada.

## 3. Conversational Language Understanding — CLU

A **Conversational Language Understanding (CLU)** é uma capacidade de compreensão de linguagem natural voltada à criação de modelos personalizados capazes de identificar **intenções** e extrair **entidades** de enunciados.

### Exemplo conceitual

**Entrada:** `Quero consultar o status do meu pedido.`

**Intenção:** `consultar_pedido`

**Entidade:** `pedido`

O CLU não executa a ação solicitada. Ele fornece a interpretação do texto para que a aplicação cliente possa decidir o que fazer.

### Ciclo conceitual

```text
Exemplos rotulados
       │
       ▼
Treinamento do modelo
       │
       ▼
Avaliação
       │
       ▼
Melhoria
       │
       ▼
Implantação
       │
       ▼
Predição de intenção + entidades
```

A qualidade dos dados rotulados é fundamental para o desempenho do modelo. A documentação atual da Microsoft informa que o CLU será descontinuado no Azure Language em **31 de março de 2029**, recomendando novos projetos no Microsoft Foundry.

## 4. Microsoft Copilot Studio

O **Microsoft Copilot Studio** foi estudado conceitualmente como uma plataforma para criação e personalização de experiências conversacionais e agentes.

No contexto deste projeto, o interesse está em compreender como tecnologias de linguagem podem ser utilizadas para estruturar interações entre usuários e sistemas.

### Conceitos relacionados

- agentes;
- tópicos;
- intenções;
- entidades;
- instruções em linguagem natural;
- integração com dados e serviços;
- automação de processos.

O Copilot Studio pode ser relacionado ao fluxo mais amplo de uma solução conversacional: compreender a entrada do usuário, determinar o contexto, consultar informações ou ferramentas e produzir uma resposta ou ação.

## 5. Azure AI Bot Service

O **Azure AI Bot Service** foi estudado conceitualmente como tecnologia do ecossistema Microsoft para construção de experiências de bots e aplicações conversacionais.

### Possíveis cenários

- atendimento ao cliente;
- suporte técnico;
- FAQ;
- agentes virtuais;
- aplicações web;
- experiências multicanal.

O conceito central é separar a **compreensão da linguagem** da **lógica da aplicação**. O modelo ou serviço interpreta a mensagem, enquanto a aplicação determina como responder, consultar sistemas ou executar ações.

## 6. Relação entre as tecnologias

```text
                    Usuário
                       │
                       ▼
               Linguagem natural
                       │
          ┌────────────┴────────────┐
          ▼                         ▼
       CLU / NLU            Question Answering
          │                         │
          └────────────┬────────────┘
                       ▼
              Aplicação conversacional
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
       Copilot Studio      Bot / agente
             │                   │
             └─────────┬─────────┘
                       ▼
                  Resposta / ação
```

O diagrama é conceitual e serve para relacionar os conceitos estudados. Não representa uma solução implementada neste repositório.

## 7. Diferença entre intenção e entidade

Um ponto importante no estudo de sistemas conversacionais é distinguir **o que o usuário quer fazer** de **qual informação está presente na mensagem**.

- **Intenção:** representa o objetivo geral do usuário.
- **Entidade:** representa uma informação relevante extraída do enunciado.

Exemplo:

`Quero cancelar o pedido 12345.`

- Intenção: `cancelar_pedido`
- Entidade: `12345` como identificador do pedido.

Essa separação ajuda aplicações conversacionais a transformar linguagem natural em informações estruturadas que podem ser utilizadas pela lógica do sistema.

## 8. Relação com o Azure Language e Azure Speech

Os estudos conceituais complementam os recursos práticos de texto e fala documentados nas outras seções do projeto.

Um fluxo possível seria:

```text
Voz
 │
 ▼
Azure Speech — Speech to Text
 │
 ▼
Texto
 │
 ▼
Compreensão de linguagem
 │
 ├── intenção
 ├── entidades
 └── pergunta / contexto
 │
 ▼
Aplicação conversacional
 │
 ▼
Resposta
```

Esse fluxo representa uma arquitetura possível. Não deve ser interpretado como uma implementação realizada neste laboratório.

## 9. Escopo e precisão documental

Para preservar a fidelidade do portfólio, esta seção utiliza verbos como **estudar, compreender, explorar conceitualmente e analisar**. Ela não apresenta exemplos teóricos como evidências de execução.

Essa distinção é importante em documentação técnica porque permite separar:

1. **prática realizada** — recursos efetivamente explorados no laboratório;
2. **estudo conceitual** — tecnologias compreendidas por meio da documentação e materiais do desafio;
3. **possibilidades de aplicação** — cenários que poderiam ser implementados futuramente.

## 10. Referências oficiais Microsoft

- [Custom Question Answering — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview)
- [Conversational Language Understanding — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)
- [Azure Language — visão geral](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Copilot Studio — documentação](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
