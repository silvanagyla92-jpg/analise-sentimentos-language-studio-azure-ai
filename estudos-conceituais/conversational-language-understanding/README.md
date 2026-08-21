# Conversational Language Understanding (CLU) — Estudo conceitual

## O que é

**Conversational Language Understanding (CLU)** é uma capacidade de compreensão de linguagem natural voltada a identificar o que um usuário pretende fazer e quais informações relevantes aparecem em sua mensagem.

Dois conceitos centrais são:

- **Intent (intenção):** ação ou objetivo que o usuário deseja realizar.
- **Entity (entidade):** informação específica presente no enunciado.

## Exemplo

Usuário:

> "Quero reservar uma passagem para São Paulo amanhã."

Interpretação conceitual:

```text
Intenção: reservar_passagem
Entidades:
  destino = São Paulo
  data = amanhã
```

Essa estrutura permite que uma aplicação encaminhe a solicitação para uma lógica de negócio adequada.

## Ciclo de desenvolvimento

Um projeto de compreensão conversacional normalmente envolve:

1. definir intenções e entidades;
2. coletar exemplos representativos;
3. rotular os dados;
4. treinar ou ajustar o modelo;
5. avaliar desempenho;
6. publicar/deployar uma versão;
7. monitorar e atualizar conforme novos padrões aparecem.

A avaliação deve considerar não apenas acurácia média, mas também erros por intenção, confusões entre classes e cobertura dos exemplos reais.

## CLU x Sentiment Analysis

São problemas diferentes:

- Sentiment Analysis estima polaridade.
- CLU busca entender intenção e entidades de um enunciado.

Uma aplicação pode usar os dois em conjunto. Um cliente poderia dizer que deseja cancelar um serviço e, ao mesmo tempo, demonstrar sentimento negativo.

## Aplicações

- assistentes conversacionais;
- roteamento de solicitações;
- automação de atendimento;
- classificação de comandos;
- extração de parâmetros para sistemas de negócio.

## Status atual

A Microsoft informa que **CLU será descontinuado no Azure Language em 31 de março de 2029**. Para evitar interrupções, a orientação atual é migrar cargas existentes e direcionar novos projetos para **Microsoft Foundry**.

## Por que estudar CLU

O conceito continua relevante porque intenção, entidade, classificação e avaliação de modelos são fundamentos de sistemas conversacionais. Também ajuda a compreender arquiteturas modernas de agentes e aplicações de IA.

## IA responsável

Dados de treinamento devem representar a variedade de linguagem esperada. Classes mal definidas, exemplos insuficientes e dados enviesados podem gerar erros sistemáticos. Em atendimento ou decisões relevantes, é importante manter mecanismos de correção e supervisão humana.

## Escopo

Este documento registra **estudo conceitual**, não uma declaração de implementação produtiva.

## Fontes oficiais

- [Microsoft Learn — Conversational Language Understanding](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)
- [Microsoft Learn — Model lifecycle](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/model-lifecycle)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
