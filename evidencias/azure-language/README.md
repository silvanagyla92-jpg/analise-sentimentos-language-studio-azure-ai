# Evidências Documentais — Azure Language

## 1. Objetivo

Esta pasta documenta como poderiam ser organizadas evidências relacionadas aos recursos do **Azure Language**. Neste projeto, porém, não houve uma assinatura Azure disponível para executar os serviços; portanto, **não há capturas de tela nem resultados experimentais reais publicados aqui**.

O conteúdo deve ser entendido como orientação documental para futuras evidências e como complemento aos estudos teóricos da pasta `azure-language/`.

## 2. Escopo atual

Os recursos estudados no projeto são:

- Sentiment Analysis;
- Opinion Mining;
- Key Phrase Extraction;
- Named Entity Recognition (NER);
- Language Detection;
- Summarization.

Os exemplos e explicações desses recursos são conceituais e fundamentados principalmente na documentação oficial da Microsoft.

## 3. O que seria uma evidência prática

Com acesso futuro a um ambiente compatível, poderiam ser registrados:

- tela da ferramenta utilizada;
- recurso selecionado;
- texto de entrada;
- idioma configurado;
- resultado apresentado;
- pontuações ou categorias retornadas;
- interpretação do resultado;
- limitações observadas.

Somente materiais realmente produzidos durante uma execução devem ser classificados como evidência prática.

## 4. Exemplo conceitual de registro

**Recurso:** Sentiment Analysis  
**Objetivo:** observar a classificação de uma avaliação  
**Entrada:** texto de teste não sensível  
**Resultado esperado segundo a documentação:** classificação de sentimento e respectivas pontuações de confiança  
**Interpretação:** análise do resultado em relação ao texto fornecido  
**Observação:** a saída de um modelo não representa garantia de correção.

Esse exemplo **não representa um teste executado neste repositório**.

## 5. Evidência x explicação

Uma página da Microsoft explicando Sentiment Analysis é uma **fonte documental**. Um exemplo textual criado para explicar o funcionamento é um **exemplo didático**. Uma captura ou resultado produzido durante uma execução real é uma **evidência prática**.

Manter essas categorias separadas é essencial para preservar a precisão do portfólio.

## 6. Privacidade e segurança

Não devem ser publicados:

- tokens;
- chaves de API;
- credenciais;
- endpoints privados;
- dados pessoais desnecessários;
- documentos confidenciais.

Caso sejam utilizadas evidências futuramente, os dados devem ser anonimizados sempre que necessário.

## 7. Critérios para futuras evidências

Uma evidência adequada deve ser:

- autêntica;
- verificável;
- legível;
- contextualizada;
- relacionada ao recurso documentado;
- acompanhada de uma interpretação;
- livre de informações sensíveis.

## 8. Fontes oficiais

- [Microsoft Learn — Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Developer guide](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide)
- [Sentiment Analysis e Opinion Mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
