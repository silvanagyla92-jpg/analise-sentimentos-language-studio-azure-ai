# Resultados

## 1. Objetivo

Esta seção consolida os **aprendizados, resultados documentais e conclusões** obtidos durante a exploração de recursos de Azure AI relacionados a processamento de linguagem natural e fala.

O resultado principal deste projeto não é apresentado como uma aplicação de produção. Trata-se de uma **experiência de aprendizagem documentada**, com distinção entre prática realizada, estudo conceitual e possibilidades de aplicação.

## 2. Principais conhecimentos consolidados

### Processamento de linguagem natural

Foi consolidada a compreensão de como serviços de NLP podem analisar texto não estruturado para identificar padrões e informações relevantes.

### Análise de sentimentos

Foi estudado o uso de classificações de sentimento e pontuações de confiança para interpretar opiniões presentes em textos.

### Mineração de opinião

Foi compreendida a diferença entre uma classificação geral de sentimento e uma análise mais granular, relacionada a aspectos específicos de produtos ou serviços.

### Extração de informação

O estudo de frases-chave e entidades demonstrou como texto livre pode ser transformado em informações mais estruturadas.

### Processamento multilíngue

A detecção de idioma mostrou a importância de identificar o idioma do conteúdo antes ou durante a construção de pipelines de processamento.

### Sumarização

Foi consolidado o conceito de reduzir conteúdos extensos para facilitar a leitura e a análise, distinguindo abordagens extrativas e abstrativas.

### Processamento de fala

O estudo do Azure Speech permitiu compreender o ciclo entre áudio e linguagem, incluindo Speech to Text, Text to Speech, tradução e avaliação de pronúncia.

## 3. Relação entre as capacidades

```text
              DADOS NÃO ESTRUTURADOS
                       │
          ┌────────────┴────────────┐
          │                         │
        Áudio                      Texto
          │                         │
          ▼                         ▼
   Azure Speech              Azure Language
          │                         │
   Speech to Text          ┌────────┼─────────┐
          │                ▼        ▼         ▼
          └────────────► Sentimento NER  Frases-chave
                           │
                           ▼
                       Análise
                           │
                           ▼
                     Informação útil
```

Esse modelo representa uma relação conceitual entre os serviços estudados e não uma solução integrada implementada.

## 4. Competências desenvolvidas

O projeto contribuiu para desenvolver ou consolidar conhecimentos relacionados a:

- fundamentos de NLP;
- análise automatizada de texto;
- avaliação de resultados de modelos de IA;
- processamento de fala;
- interpretação de documentação técnica;
- uso de serviços de IA em nuvem;
- organização de conhecimento técnico;
- documentação em Markdown;
- estruturação de projetos no GitHub;
- diferenciação entre prática, conceito e hipótese de aplicação.

## 5. Relação com competências profissionais

Os conhecimentos podem ser relacionados a atividades de:

- **AI Training**;
- **AI Response Evaluation**;
- **Data Annotation**;
- **Quality Assurance (QA)**;
- análise e classificação de dados textuais;
- documentação técnica;
- avaliação de resultados de sistemas de IA;
- Processamento de Linguagem Natural.

Essa relação representa uma conexão entre os conhecimentos adquiridos e possíveis competências profissionais; não significa que o projeto, isoladamente, comprove experiência profissional em cada uma dessas funções.

## 6. O que foi praticado x o que foi estudado

| Categoria | Conteúdo |
|---|---|
| Exploração prática | Azure Language / Language Studio e recursos de NLP apresentados no laboratório |
| Exploração prática | Azure Speech / Speech Studio e recursos de fala apresentados no laboratório |
| Estudo conceitual | Question Answering |
| Estudo conceitual | Conversational Language Understanding (CLU) |
| Estudo conceitual | Microsoft Copilot Studio |
| Estudo conceitual | Azure AI Bot Service |
| Aplicação possível | Integração entre fala, transcrição e análise de linguagem |

Essa separação preserva a fidelidade do README principal.

## 7. Principais conclusões

### 7.1 IA transforma dados não estruturados

Texto e áudio podem ser processados para produzir informações estruturadas e úteis para aplicações.

### 7.2 Uma única classificação nem sempre é suficiente

A análise de sentimentos fornece uma visão geral, enquanto a mineração de opinião permite analisar aspectos específicos de uma experiência.

### 7.3 Contexto e qualidade dos dados importam

Resultados de modelos dependem da qualidade e das características dos dados. Por isso, resultados automatizados precisam ser avaliados dentro do contexto de uso.

### 7.4 Serviços podem ser combinados

Azure Speech e Azure Language podem formar etapas diferentes de um pipeline: primeiro transformar fala em texto e depois analisar o texto.

### 7.5 Documentação faz parte do resultado técnico

Registrar o que foi feito, o que foi estudado e quais limitações existem é parte importante de um projeto de aprendizagem e facilita sua avaliação e reprodução.

## 8. Limitações do resultado

Este projeto não deve ser interpretado como uma avaliação de desempenho de modelos em um conjunto de dados controlado nem como uma aplicação de produção.

Também não são apresentados números de precisão, recall, F1-score ou benchmarks porque esses dados não foram produzidos no laboratório documentado.

Da mesma forma, exemplos conceituais não devem ser confundidos com resultados experimentais.

## 9. Próximos passos possíveis

Como evolução do projeto, poderiam ser adicionados:

1. evidências visuais das práticas realizadas;
2. exemplos reais de entradas e saídas, sem dados sensíveis;
3. comparação de resultados em diferentes textos;
4. integração programática por SDK ou REST API;
5. pipeline conceitual ou implementado de Speech to Text + Azure Language;
6. avaliação estruturada de respostas e classificações;
7. análise das limitações dos modelos em diferentes contextos.

Esses itens são **possibilidades futuras**, não resultados já realizados.

## 10. Referências oficiais

- [Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview)
- [Sentiment analysis and Opinion Mining](https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api)
- [Speech Translation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-translation)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
