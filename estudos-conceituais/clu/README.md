# Conversational Language Understanding (CLU)

## Conceito

Conversational Language Understanding (CLU) permite criar modelos personalizados para interpretar enunciados e identificar **intenções** e **entidades**.

## Exemplo

```text
Entrada: "Quero saber onde está meu pedido."

Intenção: consultar_pedido
Entidade: pedido
```

## Ciclo de desenvolvimento

```text
Dados de exemplo
      ↓
Rotulagem
      ↓
Treinamento
      ↓
Avaliação
      ↓
Ajustes
      ↓
Publicação
      ↓
Predição de intenção e entidades
```

A representatividade e a qualidade dos dados de treinamento são fundamentais para o desempenho do modelo. Casos reais, variações linguísticas e exemplos ambíguos devem fazer parte da avaliação.

## Aplicações

- classificação de intenções;
- identificação de entidades em comandos;
- interfaces conversacionais;
- automação de atendimento;
- roteamento de solicitações.

## Escopo

CLU foi estudada conceitualmente neste projeto e não é apresentada como implementação prática.

## Ciclo de vida

A Microsoft informa que CLU será descontinuada no Azure Language em **31 de março de 2029** e recomenda considerar Microsoft Foundry para novos projetos.

## Fonte oficial

[Microsoft Learn — Conversational Language Understanding](https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*