# Language Detection — Azure Language

## Visão geral

**Language Detection** identifica o idioma predominante de um texto. O recurso é útil em aplicações multilíngues porque permite determinar qual processamento linguístico deve ser aplicado antes de outras etapas.

Por exemplo, um sistema que recebe comentários de usuários em português, inglês e espanhol pode detectar o idioma e encaminhar cada conteúdo para uma análise compatível.

## Fluxo de uma aplicação multilíngue

```text
Entrada do usuário
       ↓
Detecção de idioma
       ↓
Roteamento por idioma
       ↓
Análise de texto
       ↓
Resultado estruturado
```

## Exemplo

```text
"O atendimento foi excelente."
        ↓
Português
        ↓
Sentiment Analysis / NER / outras análises
```

A detecção pode ser usada como etapa de roteamento, mas a aplicação deve considerar que alguns textos são curtos demais ou possuem mistura de idiomas para que uma identificação seja inequívoca.

## Aplicações

- atendimento multilíngue;
- classificação automática de documentos;
- roteamento de pipelines NLP;
- triagem de comentários;
- sistemas de busca e organização de conteúdo;
- preparação de dados para tradução ou análise.

## Relação com outros recursos

A detecção de idioma pode anteceder recursos como análise de sentimentos, NER e extração de frases-chave. Isso permite criar pipelines em que o resultado de uma etapa influencia a configuração das seguintes.

## Pontos de atenção

- textos muito curtos podem ser ambíguos;
- conteúdo com vários idiomas pode exigir tratamento específico;
- variantes linguísticas e dialetos podem ter suporte diferente;
- o idioma detectado não informa, por si só, intenção, sentimento ou identidade do autor.

## Integração

A Microsoft disponibiliza APIs de runtime e bibliotecas cliente para recursos do Azure Language. Para cenários de grande volume, determinados recursos também suportam processamento assíncrono.

## Escopo do projeto

O estudo deste recurso contribui para compreender como sistemas de NLP podem operar sobre dados multilíngues e como a escolha correta do idioma influencia as etapas posteriores de processamento.

## Fontes oficiais

- [Microsoft Learn — Azure Language overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Asynchronous Language features](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/use-asynchronously)
- [Microsoft Learn — Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
