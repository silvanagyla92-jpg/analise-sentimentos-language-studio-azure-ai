# Evidências — Azure Language

## Objetivo

Esta pasta deve concentrar as evidências relacionadas às atividades e experimentações com recursos do **Azure Language**. A função da evidência é demonstrar o que foi efetivamente realizado, observado ou testado, sem misturar resultados comprovados com explicações conceituais.

## O que pode ser considerado evidência

- capturas de tela do Language Studio / Microsoft Foundry;
- exemplos de entradas e respectivas saídas;
- registros de configuração utilizados no estudo;
- resultados de chamadas de API, quando apropriado e sem dados sensíveis;
- tabelas comparativas de respostas;
- observações sobre comportamento do serviço;
- arquivos de apoio produzidos durante a prática.

## Estrutura recomendada

```text
evidencias/azure-language/
├── README.md
├── imagens/
├── exemplos/
└── resultados/
```

As subpastas acima podem ser criadas somente quando houver arquivos reais para armazenar. O repositório não deve criar evidências fictícias apenas para preencher a estrutura.

## Como documentar uma evidência

Cada evidência deve informar, quando possível:

1. recurso utilizado;
2. objetivo do teste;
3. entrada fornecida;
4. configuração relevante;
5. saída observada;
6. interpretação;
7. limitações ou inconsistências encontradas;
8. data ou contexto da execução.

## Exemplo de registro

```text
Recurso: Sentiment Analysis
Objetivo: observar classificação de uma avaliação
Entrada: texto de teste não sensível
Saída: polaridade + confiança
Interpretação: resultado compatível / resultado inesperado
Observação: avaliar contexto e possíveis ambiguidades
```

## Evidência x explicação

Uma página que explica como Sentiment Analysis funciona é **documentação**, não evidência de execução. Uma captura de tela de uma análise realmente realizada é evidência. Essa distinção aumenta a credibilidade do portfólio.

## Privacidade

Não devem ser publicados tokens, chaves de API, endpoints privados, dados pessoais, documentos confidenciais ou informações de clientes. Dados reais devem ser anonimizados ou substituídos por exemplos seguros.

## Critérios de qualidade

Uma boa evidência deve ser:

- verificável;
- contextualizada;
- legível;
- relevante para o tópico;
- livre de segredos e dados desnecessários;
- coerente com o que o README afirma ter sido praticado.

## Relação com o projeto

Esta pasta é responsável por separar **o que foi demonstrado na prática** do conteúdo conceitual mantido em `azure-language/`.

## Fontes

- [Microsoft Learn — Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
