# Sentiment Analysis

## Objetivo

O Azure Language oferece análise de sentimentos para identificar a polaridade expressa em textos. O resultado pode indicar sentimentos **positive**, **neutral** ou **negative**, com pontuações de confiança para apoiar a interpretação do resultado.

## Funcionamento

```text
Texto de entrada
      ↓
Azure Language
      ↓
Análise de sentimentos
      ↓
Polaridade + confiança
      ↓
Interpretação e validação humana
```

A análise pode ser realizada em nível de documento e de sentença. Em textos com várias frases, a análise por sentença permite observar mudanças de polaridade dentro do mesmo documento.

## Exemplo conceitual

```text
Entrada: "O atendimento foi excelente, mas o tempo de espera foi ruim."

Atendimento → positivo
Tempo de espera → negativo
```

## Aplicações

- análise de avaliações de clientes;
- pesquisas de satisfação;
- classificação de comentários;
- monitoramento de feedback;
- triagem de grandes volumes de texto.

## Interpretação crítica

A pontuação de confiança representa a confiança do modelo na previsão; não significa certeza absoluta nem mede diretamente o estado emocional de uma pessoa. Ironia, contexto, negação, linguagem informal e vocabulário específico de domínio podem afetar o resultado.

## Relação com o projeto

Este é um dos principais recursos do projeto e está diretamente relacionado ao estudo de NLP e à avaliação crítica de resultados produzidos por IA.

## Fonte oficial

[Microsoft Learn — Sentiment analysis and opinion mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*