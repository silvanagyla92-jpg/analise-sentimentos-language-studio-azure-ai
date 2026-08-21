# Análise de Sentimentos

## Objetivo

A análise de sentimentos do Azure Language classifica a polaridade expressa em texto e retorna rótulos como **positive, neutral e negative**, acompanhados de pontuações de confiança em níveis de sentença e documento. A mineração de opinião pode complementar esse resultado relacionando sentimentos a aspectos específicos.

## Fluxo

```text
Texto → Azure Language → Polaridade → Confiança → Interpretação humana
```

## Como interpretar

O resultado é uma previsão do modelo, não uma medição direta do estado emocional de uma pessoa. Ironia, contexto, ambiguidade, linguagem informal e características do domínio podem afetar a interpretação. Pontuação de confiança não significa certeza absoluta.

## Aplicações

- avaliações de clientes;
- pesquisas de satisfação;
- feedbacks;
- classificação de comentários;
- triagem de grandes volumes de texto.

## Relação com o projeto

Este foi um dos principais recursos explorados no laboratório. O estudo enfatiza interpretação crítica e validação humana, especialmente quando o resultado pode apoiar decisões.

## Fonte oficial

[Microsoft Learn — Sentiment analysis and opinion mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*