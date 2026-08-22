# Evidências Documentais

## 1. Objetivo

Esta pasta reúne a **documentação das evidências e dos critérios de evidência** relacionados aos estudos de Azure AI, Azure Language e Azure Speech. Como o projeto foi desenvolvido sem uma assinatura Azure disponível para execução dos serviços, **não são apresentadas capturas de tela, resultados experimentais ou testes realizados diretamente nas plataformas**.

O objetivo desta seção é separar claramente:

- conteúdo teórico baseado em documentação oficial;
- exemplos conceituais utilizados para aprendizagem;
- evidências de execução, quando existirem em um contexto futuro;
- limitações do ambiente utilizado neste projeto.

## 2. Situação atual das evidências

Neste momento, o repositório deve ser interpretado como um **projeto teórico e documental**. Os exemplos apresentados nas demais pastas servem para explicar como os recursos funcionam e como poderiam ser utilizados, mas não comprovam execução direta no Azure Language Studio, Microsoft Foundry ou Speech Studio.

Não foram criadas evidências fictícias para preencher a estrutura do GitHub.

## 3. O que seria uma evidência prática

Caso exista acesso futuro a um ambiente Azure, poderiam ser documentados:

- capturas de tela do Language Studio ou Microsoft Foundry;
- capturas de tela do Speech Studio;
- entradas e saídas de análises de sentimentos;
- resultados de mineração de opinião;
- exemplos de entidades identificadas;
- resultados de extração de frases-chave;
- testes de detecção de idioma;
- resultados de sumarização;
- transcrições de Speech to Text;
- resultados de Text to Speech;
- resultados de Speech Translation;
- registros de Pronunciation Assessment.

Esses materiais somente devem ser adicionados se forem realmente produzidos durante uma execução.

## 4. Evidência x documentação conceitual

Uma página que explica o funcionamento de um serviço é **documentação técnica**. Um exemplo criado para explicar um conceito é **exemplo didático**. Uma captura de tela de uma execução real, acompanhada do contexto, entrada e resultado observado, é **evidência prática**.

Essas categorias não devem ser misturadas. Essa separação preserva a transparência e a credibilidade do portfólio.

## 5. Modelo para futuras evidências

Quando houver uma execução real, cada registro poderá conter:

| Informação | O que registrar |
|---|---|
| Recurso | Serviço ou funcionalidade utilizada |
| Objetivo | O que se pretendia observar |
| Entrada | Texto, áudio ou dado utilizado |
| Configuração | Idioma, modelo ou parâmetros relevantes |
| Resultado | Saída efetivamente apresentada |
| Interpretação | Análise do resultado |
| Limitações | Problemas, ambiguidades ou fatores que afetaram a saída |
| Contexto | Data e condições da execução |

## 6. Organização futura

Se forem obtidas evidências reais posteriormente, elas poderão ser organizadas em:

- `evidencias/azure-language/` — evidências de recursos de linguagem;
- `evidencias/azure-speech/` — evidências de recursos de fala.

Os nomes dos arquivos deverão corresponder às evidências realmente existentes, evitando estruturas vazias ou arquivos fictícios.

## 7. Privacidade e segurança

Nunca publicar:

- chaves de API;
- tokens;
- senhas;
- endpoints privados;
- dados pessoais desnecessários;
- documentos confidenciais;
- gravações de terceiros sem autorização.

Qualquer evidência futura deve ser revisada antes da publicação.

## 8. Critérios de qualidade

Uma evidência prática adequada deve ser:

- autêntica;
- verificável;
- contextualizada;
- legível;
- relacionada ao projeto;
- livre de credenciais e dados sensíveis.

## 9. Referências oficiais

- [Azure Language — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Azure Speech — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Speech Studio overview](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
