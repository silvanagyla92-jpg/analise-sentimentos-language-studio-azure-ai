# Custom Question Answering — Estudo conceitual

## O que é

**Custom Question Answering (CQA)** é um recurso de NLP orientado à construção de experiências conversacionais baseadas em conhecimento fornecido pela organização, como FAQs, manuais e documentos.

A ideia central é transformar uma coleção de conhecimento em uma base que possa responder perguntas de usuários sem exigir que cada resposta seja programada manualmente.

## Arquitetura conceitual

```text
Documentos / FAQ
       ↓
Base de conhecimento
       ↓
Pergunta do usuário
       ↓
Recuperação da informação relevante
       ↓
Resposta
       ↓
Interface conversacional
```

## Exemplo

Uma empresa possui um manual de atendimento. Um usuário pergunta:

> "Qual é o prazo para troca?"

O sistema procura informação relevante na base de conhecimento e apresenta uma resposta baseada no conteúdo configurado.

## Diferença para um chatbot completo

Question Answering é uma capacidade de conhecimento/perguntas e respostas. Um chatbot completo envolve também interface, gerenciamento de diálogo, autenticação, integrações, regras de negócio e, eventualmente, outros modelos de IA.

## Aplicações

- FAQs corporativas;
- suporte interno;
- manuais de produtos;
- bases de conhecimento;
- assistentes de atendimento;
- portais de autoatendimento.

## Qualidade da base

A qualidade das respostas depende da qualidade, atualidade e cobertura do conhecimento fornecido. Documentos contraditórios, desatualizados ou incompletos podem produzir respostas inadequadas.

## Status atual

A documentação atual da Microsoft informa que **Custom Question Answering será descontinuado no Azure Language em 31 de março de 2029**. Para novos projetos, a Microsoft orienta direcionar as soluções para **Microsoft Foundry** e planejar a migração de cargas existentes.

## Por que estudar

Mesmo com a mudança de plataforma, o conceito é importante para compreender **recuperação de conhecimento, sistemas conversacionais e avaliação de respostas**. Esse conhecimento também ajuda a entender arquiteturas modernas baseadas em grounding e RAG.

## Escopo deste repositório

Este conteúdo é **estudo conceitual**. Ele não deve ser interpretado como uma implementação produtiva de CQA.

## Fontes oficiais

- [Microsoft Learn — Custom Question Answering](https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview)
- [Microsoft Learn — Model lifecycle](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/model-lifecycle)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
