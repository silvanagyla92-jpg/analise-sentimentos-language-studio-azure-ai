# Opinion Mining

## Objetivo

Opinion Mining complementa a análise de sentimentos ao relacionar a polaridade de uma opinião a **aspectos ou características específicas** mencionadas no texto.

## Exemplo

```text
"A bateria é excelente, mas a tela é ruim."

Bateria → positivo
Tela    → negativo
```

## Diferença para análise de sentimentos

A análise de sentimentos responde principalmente **qual é a polaridade do texto ou da sentença**. Opinion Mining acrescenta granularidade ao identificar aspectos e associar a eles avaliações positivas ou negativas.

## Fluxo conceitual

```text
Texto
 ↓
Sentenças
 ↓
Aspectos / opiniões
 ↓
Polaridade associada
 ↓
Interpretação por aspecto
```

## Aplicações

- avaliação detalhada de produtos;
- identificação de pontos fortes e problemas em serviços;
- análise de satisfação;
- priorização de melhorias;
- exploração de grandes volumes de avaliações.

## Cuidados

Negação, ironia, linguagem coloquial, contexto insuficiente e textos muito curtos podem reduzir a qualidade da interpretação. A saída do modelo deve ser analisada considerando o domínio e o contexto original.

## Relação com o projeto

O tópico amplia o estudo de análise de sentimentos e demonstra como NLP pode transformar comentários livres em informações estruturadas para apoiar análise humana.

## Fonte oficial

[Microsoft Learn — Sentiment analysis and opinion mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*