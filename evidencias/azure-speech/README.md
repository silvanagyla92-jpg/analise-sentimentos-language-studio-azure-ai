# Evidências — Azure Speech

## Objetivo

Esta pasta organiza evidências relacionadas aos estudos e experimentações com **Azure Speech**. O objetivo é registrar de forma auditável aquilo que foi realmente observado em recursos como Speech to Text, Text to Speech, Speech Translation e Pronunciation Assessment.

## Tipos de evidência

Podem ser utilizados:

- capturas de tela do ambiente de estudo;
- exemplos de áudio autorizados;
- transcrições produzidas durante testes;
- resultados de tradução;
- exemplos de síntese de voz;
- resultados de avaliação de pronúncia;
- tabelas de comparação;
- registros técnicos sem credenciais.

## Modelo de registro

```text
Recurso:
Objetivo:
Entrada:
Configuração:
Resultado observado:
Interpretação:
Limitações:
```

## Exemplo de fluxo de evidência

```text
Áudio de teste
    ↓
Speech to Text
    ↓
Transcrição observada
    ↓
Azure Language
    ↓
Análise complementar
```

Quando a prática envolver tradução ou síntese, o fluxo deve identificar claramente o recurso utilizado e separar entrada, processamento e saída.

## Qualidade do áudio

Evidências de Speech devem registrar, quando relevante, fatores como ruído, qualidade do microfone, duração, idioma e localidade. Esses elementos ajudam a interpretar por que uma transcrição ou avaliação pode ter determinado resultado.

## Privacidade

Áudio pode conter voz identificável e informações pessoais. Não publique gravações de terceiros sem autorização. Nunca inclua chaves, tokens ou credenciais nos arquivos, capturas de tela ou exemplos.

## Evidência x documentação

Uma explicação sobre Speech to Text pertence à documentação técnica. Uma captura de uma transcrição efetivamente realizada é evidência. O portfólio deve manter essas duas funções separadas.

## Critérios de qualidade

As evidências devem ser:

- relevantes;
- legíveis;
- contextualizadas;
- reproduzíveis quando possível;
- protegidas contra exposição de dados sensíveis.

## Relação com o projeto

Esta área sustenta a parte prática do estudo de voz e ajuda a demonstrar como recursos de Speech podem ser integrados a pipelines de NLP.

## Fontes oficiais

- [Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Microsoft Learn — Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)
- [Microsoft Learn — Pronunciation Assessment](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-pronunciation-assessment)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
