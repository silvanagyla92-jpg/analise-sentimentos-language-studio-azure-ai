# Conversational Language Understanding (CLU)

## Conceito

CLU é uma capacidade de compreensão de linguagem natural que permite criar modelos personalizados para prever **intenções** e extrair **entidades** de enunciados.

### Exemplo

```text
Entrada: “Quero consultar o status do meu pedido.”

Intenção: consultar pedido
Entidade: pedido
```

## Ciclo de desenvolvimento

A documentação da Microsoft descreve um fluxo que envolve rotular dados, treinar o modelo, avaliar desempenho, melhorar o conjunto de dados/modelo, publicar e então usar o modelo para prever intenções e entidades.

A qualidade e representatividade dos dados rotulados influenciam diretamente o desempenho.

## Multilíngue

A documentação atual permite cenários multilíngues, mas o desempenho deve ser avaliado por idioma e conjunto de dados. É importante verificar suporte e disponibilidade antes de uso em produção.

## Ciclo de vida

A Microsoft informa que CLU será descontinuada no Azure Language em **31 de março de 2029** e recomenda Microsoft Foundry para novos projetos.

## Escopo

CLU foi estudada conceitualmente neste projeto e não é apresentada como implementação prática.

## Fonte oficial

[Microsoft Learn — Conversational Language Understanding](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*