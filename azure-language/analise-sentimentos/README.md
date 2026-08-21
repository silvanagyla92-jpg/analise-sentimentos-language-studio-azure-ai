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

A Microsoft recomenda considerar limites de dados, idioma e contexto ao interpretar os resultados. Para chamadas síncronas, o resultado é retornado imediatamente e os dados não são armazenados na conta pelo serviço nesse fluxo. citehttps://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call

## Relação com o projeto

Este recurso foi explorado no laboratório e constitui um dos principais focos do projeto. A documentação aqui registra o conceito e sua aplicação, sem transformar a previsão do modelo em conclusão humana definitiva.

## Fonte oficial

[Microsoft Learn — Sentiment analysis and opinion mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call)
