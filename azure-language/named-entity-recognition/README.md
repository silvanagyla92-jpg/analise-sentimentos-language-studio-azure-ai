# Named Entity Recognition (NER) — Azure Language

## Visão geral

**Named Entity Recognition (NER)** identifica e classifica entidades mencionadas em textos. Em vez de tratar todo o documento como uma sequência de palavras sem estrutura, o modelo procura reconhecer categorias semânticas relevantes, como pessoas, organizações, locais, datas e outros tipos suportados pelo serviço.

## Exemplo conceitual

Entrada:

> "A Microsoft anunciou uma nova iniciativa em São Paulo em agosto de 2026."

Uma saída conceitual pode identificar elementos como:

```text
Microsoft      → organização
São Paulo      → localização
agosto de 2026 → expressão temporal
```

As categorias e entidades efetivamente retornadas dependem do modelo, idioma e versão do serviço.

## Fluxo

```text
Documento
   ↓
Análise linguística
   ↓
Detecção de entidades
   ↓
Classificação por categoria
   ↓
Offsets / informações da ocorrência
   ↓
Uso estruturado na aplicação
```

## NER x Key Phrase Extraction

- **NER** procura entidades que se encaixam em categorias semânticas.
- **Key Phrase Extraction** procura conceitos ou expressões importantes, sem exigir que sejam entidades nomeadas.

Uma empresa pode ser uma entidade nomeada; "experiência do cliente" pode ser uma frase-chave.

## Aplicações

- extração de informações de documentos;
- organização de bases textuais;
- enriquecimento de metadados;
- identificação de pessoas e organizações em conteúdo permitido;
- preparação de dados para busca e análise;
- apoio a pipelines de NLP.

## Privacidade e segurança

A identificação de entidades não significa que seja seguro expor ou armazenar os dados encontrados. Textos podem conter informações pessoais, financeiras ou confidenciais. O projeto deve aplicar minimização de dados, controle de acesso e políticas de retenção adequadas.

## Custom NER

O Azure Language também possui recursos de **custom named entity recognition**, destinados a cenários em que categorias específicas do domínio precisam ser reconhecidas. Essa abordagem exige dados de treinamento e avaliação mais cuidadosos.

## Limitações

Entidades podem ser ambíguas. O mesmo termo pode representar categorias diferentes dependendo do contexto. Erros de ortografia, abreviações, linguagem informal e domínios muito específicos também podem influenciar a qualidade.

## Fontes oficiais

- [Microsoft Learn — Azure Language overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)
- [Azure AI Language REST API](https://learn.microsoft.com/en-us/rest/api/language/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
