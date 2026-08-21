# Sentiment Analysis — Azure Language

## Visão geral

**Sentiment Analysis** é um recurso de NLP do Azure Language que estima a polaridade expressa em textos. A classificação principal utiliza as categorias **positive**, **negative** e **neutral**, acompanhadas de pontuações de confiança. O serviço pode produzir resultados no nível do documento e das sentenças.

O objetivo não é "ler emoções" de forma humana, mas transformar padrões linguísticos em uma previsão estruturada. Por isso, o resultado deve ser interpretado como uma saída probabilística do modelo e não como uma verdade sobre a intenção ou o estado emocional do autor.

## Fluxo de processamento

```text
Texto
  ↓
Idioma / localidade
  ↓
Pré-processamento e análise NLP
  ↓
Sentimento por sentença
  ↓
Sentimento agregado do documento
  ↓
Pontuações de confiança
  ↓
Interpretação e decisão
```

Em aplicações reais, a qualidade da entrada é importante. Textos muito curtos, sarcasmo, ironia, gírias, negação e referências dependentes de contexto podem dificultar a classificação.

## Exemplo conceitual

> "O atendimento foi rápido, mas o aplicativo apresentou vários erros."

O texto possui sinais positivos e negativos. A análise por sentença ajuda a localizar essas diferenças e o resultado agregado representa a combinação identificada pelo modelo.

## Sentiment Analysis x Opinion Mining

Os recursos são relacionados, mas não equivalentes:

| Recurso | Pergunta principal |
|---|---|
| Sentiment Analysis | Qual é a polaridade do texto? |
| Opinion Mining | Qual aspecto foi avaliado e qual opinião está associada a ele? |

Exemplo: "A câmera é excelente, mas a bateria é ruim." A análise de sentimento identifica polaridades; a mineração de opinião acrescenta a relação entre **câmera → positivo** e **bateria → negativo**.

## Aplicações

- análise de avaliações de produtos;
- classificação de feedback de clientes;
- pesquisas de satisfação;
- monitoramento de comentários;
- priorização de grandes volumes de texto;
- indicadores de experiência do cliente;
- apoio a dashboards e processos de QA.

## Integração técnica

A Microsoft disponibiliza REST APIs e bibliotecas cliente para trabalhar com Azure Language. Uma integração normalmente envolve um recurso do serviço, endpoint e autenticação. A análise pode ser usada de forma síncrona e existem também mecanismos assíncronos para cargas maiores.

## Qualidade e IA responsável

Um modelo pode apresentar vieses ou desempenho desigual entre domínios, idiomas e estilos de escrita. Antes de automatizar decisões, é recomendável testar exemplos representativos, avaliar falsos positivos e falsos negativos e manter revisão humana em decisões de maior impacto.

## Escopo deste projeto

Neste portfólio, o recurso é documentado como parte do estudo de **processamento de linguagem natural, avaliação crítica de respostas de IA e compreensão de serviços Azure**. A documentação não deve ser interpretada como prova de implantação produtiva.

## Fontes oficiais

- [Microsoft Learn — Sentiment Analysis e Opinion Mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)
- [Microsoft Learn — Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
