# Speech to Text

## Objetivo

O Azure Speech permite reconhecer fala e produzir uma transcrição textual. O recurso pode ser usado em aplicações interativas e em cenários de transcrição em lote.

## Fluxo

```text
Áudio → Speech to Text → Transcrição → Processamento posterior
```

A transcrição pode alimentar outras etapas de NLP, como análise de sentimentos, entidades ou frases-chave.

## Cenários

- legendagem e acessibilidade;
- transcrição de reuniões;
- atendimento e call centers;
- comandos por voz;
- análise posterior de conversas.

## Batch Speech to Text

A transcrição em lote é adequada quando o processamento não precisa ocorrer como uma interação síncrona imediata e grandes conjuntos de áudio precisam ser processados.

## Cuidados

Qualidade do áudio, ruído, sotaque, idioma, terminologia específica e condições de gravação podem influenciar a transcrição. A documentação de idiomas e localidades deve ser consultada antes da implementação.

## Fonte oficial

[Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)  
[Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*