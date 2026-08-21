# Opinion Mining — Azure Language

## Visão geral

**Opinion Mining**, associado à análise de sentimentos, acrescenta granularidade à interpretação de opiniões. Em vez de considerar apenas a polaridade geral de um comentário, o recurso procura relacionar uma opinião a um **aspecto ou atributo** mencionado no texto.

Isso é especialmente útil em avaliações de produtos e serviços, nas quais uma mesma mensagem pode conter elogios e críticas diferentes.

## Exemplo

> "A tela é excelente, mas a bateria dura pouco."

Uma leitura estruturada pode representar:

```text
Tela      → positivo
Bateria   → negativo
```

Esse nível de detalhe permite descobrir **o que** o usuário aprovou ou rejeitou, e não apenas se o comentário foi globalmente positivo ou negativo.

## Relação com Sentiment Analysis

| Sentiment Analysis | Opinion Mining |
|---|---|
| Identifica polaridade | Relaciona polaridade a aspectos |
| Visão mais geral | Visão mais granular |
| Útil para classificação | Útil para diagnóstico de atributos |

Os dois recursos podem ser usados conjuntamente.

## Fluxo conceitual

```text
Comentário
   ↓
Identificação das sentenças
   ↓
Identificação de aspectos/opiniões
   ↓
Determinação da polaridade
   ↓
Pontuações e relações
   ↓
Análise por atributo
```

## Aplicações

- avaliações de restaurantes;
- reviews de produtos;
- pesquisas de satisfação;
- análise de atendimento;
- monitoramento de características de serviços;
- identificação de problemas recorrentes;
- comparação de atributos entre produtos.

## Exemplo de uso analítico

Imagine 10 mil avaliações de um aplicativo. Uma classificação somente positiva/negativa pode indicar satisfação geral. A mineração de opinião permite separar temas como **interface, desempenho, preço, suporte e estabilidade** e observar quais aspectos concentram avaliações negativas.

Isso transforma texto não estruturado em informação que pode ser agrupada, contabilizada e visualizada em dashboards.

## Limitações

A interpretação depende do contexto linguístico. Ironia, ambiguidades, frases incompletas, referências implícitas e linguagem específica de um domínio podem reduzir a qualidade. Também é importante evitar inferências sobre pessoas que não estejam sustentadas pelo texto.

## Integração técnica

A Microsoft disponibiliza APIs e SDKs para enviar documentos ao Azure Language e processar os resultados. O fluxo de uma aplicação normalmente envolve coleta, preparação do texto, chamada do serviço, armazenamento estruturado da resposta e interpretação posterior.

## Relação com o projeto

Este tópico amplia o estudo de análise de sentimentos e ajuda a compreender como **avaliação de texto** pode ser transformada em sinais mais úteis para análise de qualidade, experiência do cliente e processos de avaliação.

## Fontes oficiais

- [Microsoft Learn — Sentiment Analysis e Opinion Mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)
- [Microsoft Learn — Azure Language overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
