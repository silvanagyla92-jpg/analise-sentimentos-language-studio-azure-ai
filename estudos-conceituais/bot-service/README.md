# Azure AI Bot Service — Estudo conceitual

## O que é

**Azure AI Bot Service** é um serviço associado à construção e integração de experiências de bots. Um bot pode receber mensagens de diferentes canais e encaminhá-las para uma lógica conversacional ou para componentes de IA.

## Arquitetura conceitual

```text
Usuário / canal
      ↓
Bot / camada de comunicação
      ↓
Lógica conversacional
      ↓
Serviço de IA / conhecimento / API
      ↓
Resposta
      ↓
Canal do usuário
```

A arquitetura real depende dos serviços utilizados. Um bot pode ser apenas uma interface para regras de negócio ou integrar modelos de linguagem, bases de conhecimento e automações.

## Relação com outros conceitos

- **Question Answering:** pode fornecer conhecimento para perguntas.
- **CLU:** pode contribuir para interpretação de intenção e entidades em arquiteturas compatíveis.
- **Copilot Studio:** fornece uma experiência de criação e gestão de agentes, com capacidades próprias de integração e publicação.
- **Azure Speech:** pode ser utilizado em cenários em que voz participa da experiência.

## Aplicações

- atendimento ao cliente;
- suporte interno;
- FAQ;
- orientação de usuários;
- automação de tarefas conversacionais;
- integração com sistemas corporativos.

## Segurança

Um bot pode atuar como uma porta de entrada para sistemas internos. Portanto, autenticação, autorização, validação de entrada e controle das ações são fundamentais. O fato de um usuário conseguir perguntar algo não significa que ele deva ter acesso aos dados ou operações relacionados.

## Avaliação de qualidade

Um bot deve ser testado com perguntas normais, ambiguidades, erros de digitação, solicitações fora do escopo e tentativas de obter informações não autorizadas. Também é importante avaliar se respostas são corretas, úteis, seguras e coerentes.

## Relação com o projeto

O estudo conceitual de Bot Service ajuda a conectar NLP e IA a uma **interface de aplicação**. Para profissionais de avaliação de IA, esse contexto é importante porque a qualidade de um modelo precisa ser observada dentro do sistema que o utiliza.

## Escopo

Este documento registra um **estudo conceitual**. Não constitui evidência de implantação de um bot produtivo neste repositório.

## Fontes oficiais

- [Microsoft Learn — Azure AI Bot Service](https://learn.microsoft.com/en-us/azure/bot-service/)
- [Microsoft Learn — Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
