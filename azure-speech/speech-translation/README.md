# Speech Translation — Azure Speech

## Visão geral

**Speech Translation** combina reconhecimento de fala e tradução para transformar uma fala em um idioma em texto traduzido para outro idioma. É um recurso útil para experiências multilíngues e cenários de comunicação entre pessoas que usam idiomas diferentes.

## Fluxo

```text
Fala no idioma A
       ↓
Reconhecimento da fala
       ↓
Texto / representação linguística
       ↓
Tradução
       ↓
Texto no idioma B
       ↓
Opcional: Text to Speech
```

Quando combinado com TTS, o fluxo pode produzir uma experiência de tradução de voz quase ponta a ponta.

## Exemplo conceitual

```text
Português
"Onde fica a estação?"
        ↓
Speech Translation
        ↓
Inglês
"Where is the station?"
```

O exemplo é ilustrativo. A qualidade real depende de áudio, idioma, contexto e suporte da funcionalidade.

## Aplicações

- reuniões multilíngues;
- atendimento a clientes internacionais;
- viagens e orientação;
- educação;
- comunicação entre equipes;
- acessibilidade e experiências multilíngues.

## Idiomas e localidades

Nem todos os recursos possuem o mesmo conjunto de idiomas. A Microsoft publica tabelas de suporte específicas para Speech Translation, Speech to Text, Text to Speech e Pronunciation Assessment. Essa verificação deve fazer parte do planejamento técnico.

## Desafios

Tradução automática pode perder nuances culturais, expressões idiomáticas, humor ou contexto. Em conversas técnicas ou de alto impacto, a revisão humana pode ser necessária.

## Integração com Azure Language

Depois que a fala é transformada em texto, o conteúdo pode alimentar outros recursos de NLP. Por exemplo:

```text
Fala
 ↓
Speech Translation
 ↓
Texto traduzido
 ↓
Sentiment Analysis
 ↓
Indicador de polaridade
```

Esse tipo de pipeline mostra como serviços especializados podem ser combinados em uma arquitetura de IA.

## Relação com o projeto

O estudo deste recurso amplia a compreensão de aplicações multimodais e mostra como **voz, tradução e NLP** podem trabalhar em conjunto.

## Fontes oficiais

- [Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Microsoft Learn — Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
