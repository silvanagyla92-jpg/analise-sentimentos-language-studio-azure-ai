# Análise de Sentimentos

## Objetivo

A análise de sentimentos identifica a polaridade de um texto e fornece resultados em nível de sentença e documento. No Azure Language, os rótulos principais são **positive**, **neutral** e **negative**, acompanhados de pontuações de confiança.

## Como interpretar

O serviço não deve ser tratado como uma verdade absoluta sobre o estado emocional de uma pessoa. O resultado é uma previsão estatística baseada no texto fornecido. Contexto, ironia, ambiguidades, linguagem informal e domínio podem afetar o resultado.

## Fluxo conceitual

```text
Texto → Azure Language → Sentimento → Confiança → Interpretação
```

## Aplicações

- feedback de clientes;
- avaliações de produtos e serviços;
- pesquisas de satisfação;
- classificação de comentários;
- triagem de grandes volumes de texto.

A Microsoft documenta que o resultado pode ser obtido em nível de sentença e documento, com pontuações de confiança, e orienta considerar idioma, limites e características do texto ao processar os dados.

## Relação com o projeto

Este recurso foi explorado no laboratório e constitui um dos principais focos do projeto. A documentação aqui registra o conceito e sua aplicação, sem transformar a previsão do modelo em conclusão humana definitiva.

## Fonte oficial

[Microsoft Learn — Sentiment analysis and opinion mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
