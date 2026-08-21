# Extração de Informações de Texto

Esta área reúne dois recursos importantes do Azure Language: **Key Phrase Extraction** e **Named Entity Recognition (NER)**.

## Frases-chave

A extração de frases-chave identifica termos e expressões que representam assuntos relevantes do texto. Pode apoiar indexação, organização documental, descoberta de tópicos e análise de feedback.

## NER — Named Entity Recognition

O NER identifica e classifica entidades presentes no texto, como pessoas, organizações, locais e outras categorias suportadas. Isso ajuda a transformar conteúdo não estruturado em informação mais estruturada.

## Comparação

```text
Texto
 ├── Frases-chave → assuntos e conceitos relevantes
 └── NER          → entidades e categorias
```

## Exemplo conceitual

Em “A Microsoft lançou um produto em São Paulo”, um sistema de NER pode identificar **Microsoft** como organização e **São Paulo** como local, enquanto a extração de frases-chave procura os termos mais representativos do conjunto textual.

## Fontes oficiais

[Azure Language — visão geral](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)  
[Key Phrase Extraction](https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/overview)  
[Named Entity Recognition](https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*