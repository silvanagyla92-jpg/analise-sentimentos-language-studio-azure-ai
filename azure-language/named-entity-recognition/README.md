# Named Entity Recognition (NER)

## Objetivo

Named Entity Recognition identifica e categoriza entidades mencionadas em texto não estruturado, como pessoas, organizações e locais, conforme as categorias suportadas pelo serviço.

## Fluxo

```text
Texto → NER → Entidades + categorias → Informação estruturada
```

## Exemplo conceitual

```text
"A Microsoft possui escritórios em São Paulo."

Microsoft  → Organização
São Paulo  → Localização
```

## Aplicações

- organização de documentos;
- extração de informação;
- indexação;
- enriquecimento de dados;
- análise de conteúdo;
- preparação para outras etapas de NLP.

## NER pré-configurado e personalizado

O NER pré-configurado utiliza categorias fornecidas pelo serviço. Para necessidades específicas de um domínio, a Microsoft também oferece recursos de Custom NER, nos quais modelos podem ser construídos com dados próprios.

## Cuidados

Entidades dependem do contexto. Nomes ambíguos, abreviações, erros de escrita e vocabulário especializado podem afetar a identificação. Resultados importantes devem ser validados.

## Fonte oficial

[Microsoft Learn — Named Entity Recognition](https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*