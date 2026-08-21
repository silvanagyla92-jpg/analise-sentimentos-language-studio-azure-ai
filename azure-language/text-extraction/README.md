# Text Extraction

## Escopo

Esta seção reúne os recursos de extração de informação textual estudados no contexto do Azure Language. O objetivo é transformar texto não estruturado em elementos que possam ser analisados posteriormente.

## Principais capacidades

### Named Entity Recognition (NER)

A extração de entidades identifica categorias relevantes em um texto, como pessoas, organizações, locais, datas e outros tipos suportados pelo serviço. O resultado ajuda a estruturar informação que originalmente estava apenas em linguagem natural.

### Key Phrase Extraction

A extração de frases-chave identifica termos ou expressões que representam os principais conceitos de um documento. É útil para síntese inicial, indexação e exploração de conteúdo.

## Fluxo

```text
Texto não estruturado
        ↓
Processamento de linguagem
        ↓
Entidades / frases-chave
        ↓
Informação estruturada
        ↓
Análise ou aplicação
```

## Aplicações

- organização automática de documentos;
- classificação e indexação;
- identificação de pessoas, locais e organizações;
- descoberta de temas principais;
- preparação de dados para análises posteriores.

## Limitações

A extração depende do contexto, idioma e características do texto. Um resultado identificado pelo modelo deve ser validado antes de ser utilizado em processos críticos.

## Relação com o projeto

O estudo demonstra que NLP não se limita à classificação de sentimentos: também pode converter texto livre em elementos estruturados que facilitam a análise e a tomada de decisão.

## Fontes oficiais

[Microsoft Learn — Named Entity Recognition](https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/overview)  
[Microsoft Learn — Key Phrase Extraction](https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*