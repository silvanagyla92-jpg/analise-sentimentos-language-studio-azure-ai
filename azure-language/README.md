# Azure Language — Processamento de Linguagem Natural

## 1. Objetivo

Esta seção documenta os recursos de **Processamento de Linguagem Natural (NLP)** explorados no projeto com o **Azure Language / Language Studio**. O foco é compreender como serviços de IA transformam texto não estruturado em informações úteis para análise, classificação e apoio à tomada de decisão.

O Azure Language reúne recursos pré-configurados e recursos personalizados para processamento de texto. Neste projeto, o conteúdo do README principal é aprofundado em seis capacidades: **análise de sentimentos, mineração de opinião, extração de frases-chave, reconhecimento de entidades nomeadas (NER), detecção de idioma e sumarização**.

> **Escopo:** esta documentação amplia os conceitos do laboratório. Ela não transforma os recursos estudados conceitualmente em implementações práticas que não foram realizadas.

## 2. Análise de sentimentos

A análise de sentimentos identifica a polaridade de um texto. O serviço pode retornar **positive, negative e neutral** no nível de sentença e de documento. Quando um documento contém sentenças positivas e negativas, a classificação do documento pode ser **mixed**.

O resultado também apresenta pontuações de confiança. Valores mais próximos de 1 indicam maior confiança do modelo na classificação. Essas pontuações são saídas do modelo e não representam uma garantia de correção.

### Aplicações

- avaliações de clientes;
- pesquisas de satisfação;
- comentários sobre produtos e serviços;
- triagem de feedback;
- análise de interações de atendimento;
- acompanhamento de percepção sobre temas ou marcas.

### Exemplo conceitual

**Entrada:** `O atendimento foi rápido e excelente.`

**Interpretação:** sentimento predominantemente positivo, acompanhado de uma pontuação de confiança.

Textos ambíguos, ironia, linguagem informal, contexto insuficiente e características específicas do domínio podem influenciar a classificação.

## 3. Mineração de opinião

A **Opinion Mining**, também chamada de análise de sentimento baseada em aspectos, aprofunda a análise de sentimentos. Em vez de considerar somente a polaridade geral, ela relaciona uma opinião a um **alvo/aspecto** específico do texto.

Exemplo: `O quarto estava ótimo, mas a equipe foi pouco atenciosa.`

Uma análise granular pode relacionar `quarto` a uma avaliação positiva e `equipe` a uma avaliação negativa. Isso permite descobrir **o que** foi avaliado e não apenas se o comentário inteiro foi positivo ou negativo.

A mineração de opinião é documentada pela Microsoft como uma extensão da análise de sentimentos e seus resultados são retornados junto à análise de sentimento quando essa capacidade é solicitada.

## 4. Extração de frases-chave

A **Key Phrase Extraction** identifica conceitos e expressões relevantes presentes em um texto. Diferentemente da sumarização, seu objetivo principal é retornar termos representativos dos assuntos centrais.

### Aplicações

- indexação de documentos;
- descoberta de tópicos;
- organização de conteúdo;
- análise de feedback;
- classificação e triagem;
- preparação de dados para etapas posteriores de análise.

## 5. Reconhecimento de Entidades Nomeadas — NER

O **Named Entity Recognition (NER)** identifica e categoriza entidades presentes em texto não estruturado. Entre as categorias reconhecidas estão pessoas, organizações, locais e quantidades, além de outras classes suportadas pelo serviço.

O NER pré-configurado trabalha com categorias já definidas. Para necessidades específicas de um domínio, a Microsoft também disponibiliza **Custom NER**, que permite construir modelos voltados para entidades especializadas.

### Exemplo conceitual

`A Microsoft possui escritórios em São Paulo.`

O processamento pode identificar `Microsoft` como organização e `São Paulo` como localização.

## 6. Detecção de idioma

A detecção de idioma identifica o idioma predominante de um conteúdo textual. Essa capacidade é importante em aplicações que recebem dados multilíngues e precisam selecionar o processamento adequado.

### Cenários de uso

- atendimento multilíngue;
- roteamento de documentos;
- classificação por idioma;
- preparação de pipelines de NLP;
- aplicações internacionais.

## 7. Sumarização

A sumarização reduz conteúdos extensos para facilitar a identificação das informações principais. A documentação atual do Azure Language contempla soluções para **texto, conversas e documentos nativos**.

A abordagem **extrativa** seleciona informações relevantes do conteúdo original. A abordagem **abstrativa** pode produzir uma formulação nova e condensada das ideias principais.

### Aplicações

- síntese de documentos;
- resumo de conversas;
- apoio à análise de reuniões;
- triagem de grandes volumes de texto;
- preparação de informação para análise humana.

## 8. Relação entre os recursos

```text
                 TEXTO NÃO ESTRUTURADO
                          │
                          ▼
                 ┌─────────────────┐
                 │  Azure Language │
                 └────────┬────────┘
                          │
       ┌──────────┬───────┼───────┬──────────┐
       ▼          ▼       ▼       ▼          ▼
  Sentimento   Opinião   NER   Idioma   Frases-chave
       │          │       │       │          │
       └──────────┴───────┴───────┴──────────┘
                          │
                          ▼
                  INFORMAÇÃO ANALISÁVEL
                          │
                          ▼
                    Sumarização* 

* A sumarização é outra capacidade do ecossistema e pode ser aplicada
  conforme o tipo de conteúdo e o fluxo da solução.
```

O diagrama é conceitual e não representa uma aplicação integrada implementada neste repositório.

## 9. Integração técnica

Os recursos do Azure Language podem ser utilizados por **REST APIs e bibliotecas cliente/SDK**, além das interfaces de exploração disponibilizadas pela Microsoft. A documentação de desenvolvimento apresenta APIs específicas para diferentes recursos de análise de texto.

A Microsoft também documenta operações assíncronas para determinados recursos. Em cenários compatíveis, é possível processar múltiplas capacidades sobre os dados, incluindo sentimento, NER, detecção de idioma, frases-chave e sumarização.

## 10. IA responsável e limitações

Os resultados de NLP devem ser tratados como **inferências produzidas por modelos de IA**, não como verdades absolutas. Qualidade do texto, contexto, idioma, ironia, ambiguidades e características específicas do domínio podem afetar o resultado.

Em aplicações reais, é importante considerar:

- validação dos resultados;
- proteção de dados sensíveis;
- privacidade e segurança;
- monitoramento de qualidade;
- avaliação específica para o domínio;
- revisão humana em decisões de maior impacto.

## 11. Escopo deste projeto

O README principal informa que os recursos de Azure Language / Language Studio foram explorados no contexto do laboratório. Esta página organiza e aprofunda esses conhecimentos para facilitar a consulta e a rastreabilidade da aprendizagem.

## 12. Referências oficiais Microsoft

- [Azure Language — visão geral](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Sentiment analysis and Opinion Mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)
- [Key phrase extraction](https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/overview)
- [Named Entity Recognition](https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/overview)
- [Summarization](https://learn.microsoft.com/en-us/azure/ai-services/language-service/summarization/overview)
- [Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)
- [Uso assíncrono de recursos do Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/use-asynchronously)
