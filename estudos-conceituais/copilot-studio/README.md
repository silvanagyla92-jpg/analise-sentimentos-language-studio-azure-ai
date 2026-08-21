# Microsoft Copilot Studio — Estudo conceitual

## O que é

**Microsoft Copilot Studio** é uma plataforma para criação e personalização de agentes e experiências conversacionais. O conceito combina configuração de tópicos, fontes de conhecimento, ações e integrações para criar experiências capazes de responder e executar tarefas.

## Componentes conceituais

Uma solução pode envolver:

- instruções e comportamento do agente;
- tópicos e fluxos conversacionais;
- fontes de conhecimento;
- conectores e ações;
- autenticação e permissões;
- canais de publicação;
- monitoramento e avaliação.

## Fluxo simplificado

```text
Usuário
   ↓
Agente
   ↓
Interpretação da solicitação
   ↓
Conhecimento / ação / integração
   ↓
Resposta ou execução
   ↓
Feedback e avaliação
```

## Exemplo conceitual

Um agente interno poderia responder perguntas sobre políticas da empresa e, quando necessário, acionar uma automação para consultar um sistema autorizado.

A diferença importante é que **responder** e **executar uma ação** são capacidades distintas. Uma solução bem projetada precisa controlar quais ações podem ser executadas e com quais permissões.

## Relação com Azure Language

Recursos de NLP podem ser usados como componentes de soluções conversacionais. O conhecimento estudado em sentimentos, entidades, intenções e question answering ajuda a compreender como agentes interpretam entradas e acessam informações.

## Governança e segurança

Agentes corporativos precisam de controle sobre dados, conectores, identidades e permissões. Informações sensíveis não devem ser expostas apenas porque um agente consegue acessá-las. Também é importante registrar comportamentos relevantes e estabelecer limites para ações automatizadas.

## Avaliação

A qualidade de um agente deve ser avaliada por critérios como:

- correção das respostas;
- aderência às fontes;
- capacidade de recusar solicitações inadequadas;
- comportamento em perguntas ambíguas;
- segurança das ações;
- consistência entre diferentes entradas.

## Por que estudar

O Copilot Studio aproxima conceitos de NLP de aplicações reais de agentes. Para um perfil voltado a **AI Trainer e AI Response Evaluator**, ele é relevante porque evidencia a necessidade de testar comportamento, contexto, segurança e qualidade de respostas.

## Escopo

Este documento representa **estudo conceitual** dentro deste projeto. Não afirma a construção de um agente produtivo neste repositório.

## Fontes oficiais

- [Microsoft Learn — Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)
- [Microsoft Learn — Copilot Studio documentation](https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
