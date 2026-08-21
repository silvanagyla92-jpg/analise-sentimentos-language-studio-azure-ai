# Fontes

## 1. Objetivo

Esta seção reúne as referências utilizadas para fundamentar a documentação técnica e os estudos do projeto.

A prioridade é dada à **documentação oficial da Microsoft**, especialmente ao Microsoft Learn, porque os serviços Azure Language e Azure Speech evoluem continuamente. Materiais do **Bootcamp Suzano — Python Developer, da DIO**, são utilizados como contexto do desafio quando efetivamente relacionados ao projeto.

## 2. Fonte principal — Microsoft Learn

O Microsoft Learn é a principal referência técnica deste projeto para compreender conceitos, funcionalidades, limitações, formas de integração e atualizações dos serviços.

### Azure Language

A documentação do Azure Language apresenta recursos para análise de texto, incluindo sentimento, mineração de opinião, frases-chave, entidades, detecção de idioma e sumarização.

**Referência:**

https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview

### Sentiment Analysis e Opinion Mining

Documentação utilizada para compreender rótulos de sentimento, pontuações de confiança, análise por sentença/documento e mineração de opinião baseada em aspectos.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/sentiment-opinion-mining/how-to/call-api

### Key Phrase Extraction

Referência para compreender a identificação dos principais conceitos presentes em textos não estruturados.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/overview

### Named Entity Recognition

Referência para compreender a identificação e categorização de entidades em textos e a diferença entre NER pré-configurado e Custom NER.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/named-entity-recognition/overview

### Summarization

Referência para compreender sumarização de texto, conversas e documentos e as diferenças entre abordagens extrativas e abstrativas.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/summarization/overview

## 3. Azure Speech

### Visão geral

A documentação do Azure Speech foi utilizada para compreender Speech to Text, Text to Speech, tradução de fala e outras capacidades de processamento de áudio.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview

### Speech Studio

Referência para compreender a interface de exploração e testes dos recursos de fala.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview

### Speech Translation

Referência para compreender tradução de fala em tempo real, tradução fala-para-texto e fala-para-fala.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-translation

### Text to Speech

Referência para compreender síntese de voz e vozes neurais.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/text-to-speech

### Custom Speech

Referência para compreender personalização do reconhecimento de fala para vocabulário e domínios específicos.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/custom-speech-overview

### Pronunciation Assessment

Referência para compreender avaliação automatizada de pronúncia, precisão e fluência.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-pronunciation-assessment

### Idiomas e vozes suportados

Referência indispensável para verificar disponibilidade de idiomas e localidades por funcionalidade.

https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support

## 4. Estudos conceituais

### Custom Question Answering

Utilizado para compreender sistemas conversacionais baseados em bases de conhecimento. A documentação atual também registra a transição dessa tecnologia para soluções no Microsoft Foundry.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/question-answering/overview

### Conversational Language Understanding — CLU

Utilizado para compreender intenção, entidades, treinamento, avaliação e implantação de modelos personalizados de compreensão de linguagem.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/conversational-language-understanding/overview

### Microsoft Copilot Studio

Utilizado como referência conceitual para agentes e experiências conversacionais.

https://learn.microsoft.com/en-us/microsoft-copilot-studio/

## 5. APIs e integração

A documentação de desenvolvimento do Azure Language foi utilizada para compreender as possibilidades de integração por REST API e SDKs.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/developer-guide

Também foi consultada a documentação sobre processamento assíncrono de recursos do Language.

https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/use-asynchronously

## 6. DIO — contexto do desafio

O projeto foi desenvolvido como entregável do **Bootcamp Suzano — Python Developer**, da DIO. O material do desafio constitui a referência de contexto educacional, enquanto a documentação técnica dos serviços Azure é fundamentada prioritariamente nas fontes oficiais da Microsoft.

**DIO:**

https://www.dio.me/

## 7. Critério de seleção das fontes

As fontes devem ser classificadas segundo sua função:

| Tipo | Uso |
|---|---|
| Documentação oficial Microsoft | Fundamentação técnica dos serviços Azure |
| Material da DIO | Contexto educacional e desafio do projeto |
| Evidência própria | Comprovação das práticas realizadas |
| Material complementar | Apenas quando efetivamente utilizado e identificável |

## 8. Atualização das referências

Serviços de IA em nuvem são atualizados continuamente. Algumas funcionalidades podem mudar de nome, disponibilidade, API, ciclo de vida ou plataforma. Por isso, as referências devem ser revistas antes de utilizar este projeto como guia de implementação em produção.

Um exemplo importante é a documentação atual do Microsoft Learn que informa a aposentadoria de **Custom Question Answering e CLU no Azure Language em 31 de março de 2029**, orientando novos projetos para Microsoft Foundry.

## 9. Boas práticas de documentação

Ao adicionar uma nova fonte:

1. verificar se ela foi realmente utilizada;
2. preferir a documentação oficial do fornecedor;
3. registrar o título e a finalidade da fonte;
4. evitar links sem contexto;
5. não apresentar material conceitual como evidência prática;
6. verificar se a documentação continua atualizada.
