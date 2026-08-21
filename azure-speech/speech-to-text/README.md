# Speech to Text

## Objetivo

Speech to Text converte áudio em texto por meio de reconhecimento automático de fala. O recurso permite transformar uma entrada de voz em texto que pode ser armazenado, pesquisado ou encaminhado para outras etapas de processamento.

## Fluxo

```text
Áudio
  ↓
Speech to Text
  ↓
Transcrição
  ↓
Azure Language / NLP
  ↓
Análise
```

## Aplicações

- transcrição de reuniões e entrevistas;
- acessibilidade;
- atendimento e suporte;
- geração de legendas;
- preparação de áudio para análise de linguagem.

## Relação com o projeto

O Speech to Text é a ponte conceitual entre voz e NLP. Uma transcrição pode ser encaminhada para análise de sentimentos, entidades, frases-chave ou sumarização, formando um fluxo voz → texto → análise.

## Cuidados

Ruído, sotaques, sobreposição de vozes, qualidade do áudio e vocabulário específico podem afetar a transcrição. Quando a precisão for relevante, o texto transcrito deve ser revisado.

## Fonte oficial

[Microsoft Learn — Speech to text overview](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-to-text)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*