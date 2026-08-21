# Azure Speech — processamento de fala

## 1. Objetivo

Esta seção documenta os recursos de **fala e áudio** estudados no projeto por meio do **Azure Speech / Speech Studio**. O foco é compreender como sistemas de IA podem reconhecer fala, sintetizar voz, traduzir áudio e avaliar aspectos da pronúncia.

O Azure Speech disponibiliza capacidades como **Speech to Text, Text to Speech, Speech Translation, Pronunciation Assessment e Custom Speech**, além de outras funcionalidades. O Speech Studio oferece uma interface para explorar e testar vários desses recursos sem exigir implementação completa em código.

## 2. Speech to Text

**Speech to Text** converte áudio falado em texto. A documentação atual do Azure Speech contempla diferentes cenários, incluindo **transcrição em tempo real, transcrição rápida e transcrição em lote**.

### Fluxo conceitual

```text
Áudio / voz humana
       │
       ▼
 Azure Speech
       │
       ▼
Reconhecimento de fala
       │
       ▼
 Texto transcrito
```

### Aplicações

- legendagem;
- ditado;
- transcrição de reuniões;
- análise de chamadas;
- acessibilidade;
- transformação de áudio em dados textuais para posterior NLP.

O texto produzido pode alimentar recursos do Azure Language, criando o fluxo conceitual **fala → transcrição → análise de linguagem**.

## 3. Batch Speech to Text

A transcrição em lote é adequada para arquivos de áudio que serão processados de forma assíncrona, especialmente quando há grandes volumes ou gravações previamente armazenadas.

Esse modelo de processamento é diferente de uma interação em tempo real: o arquivo é enviado para processamento e o resultado fica disponível posteriormente.

## 4. Text to Speech

**Text to Speech (TTS)** converte texto em fala sintetizada. O Azure Speech utiliza vozes neurais para produzir áudio com características mais naturais de articulação, entonação e prosódia.

A Microsoft disponibiliza vozes padrão em muitos idiomas e localidades e também oferece opções de voz personalizada sujeitas às regras de acesso e uso responsável.

### Aplicações

- assistentes virtuais;
- leitura automática de conteúdo;
- acessibilidade;
- sistemas educacionais;
- respostas de agentes;
- geração de áudio a partir de textos.

O Speech Studio também oferece ferramentas de criação de conteúdo de áudio sem código para determinados cenários.

## 5. Speech Translation

O **Speech Translation** permite traduzir fala em tempo real. A entrada é um fluxo de áudio em um idioma de origem e o serviço pode produzir texto traduzido, áudio traduzido ou ambos, dependendo da configuração.

### Fluxo conceitual

```text
Fala no idioma A
       │
       ▼
Speech Translation
       │
       ├──► Texto no idioma B
       │
       └──► Voz sintetizada no idioma B
```

A Microsoft documenta recursos de tradução de fala para texto, fala para fala, múltiplos idiomas e cenários de interpretação ao vivo.

### Aplicações

- comunicação multilíngue;
- reuniões internacionais;
- atendimento ao cliente;
- viagens;
- acessibilidade linguística;
- experiências conversacionais multilíngues.

## 6. Pronunciation Assessment

O **Pronunciation Assessment** avalia a fala de uma pessoa e fornece feedback relacionado à precisão e à fluência da pronúncia. A documentação da Microsoft descreve métricas e recursos destinados especialmente a cenários de aprendizagem de idiomas.

Dependendo da configuração e do idioma, a avaliação pode considerar aspectos como precisão, fluência, prosódia e outros elementos do desempenho oral.

### Aplicações

- aprendizagem de idiomas;
- treinamento de pronúncia;
- plataformas educacionais;
- exercícios de fala;
- avaliação automatizada de desempenho oral.

O Speech Studio disponibiliza um ambiente de teste dessa capacidade sem necessidade de desenvolver imediatamente uma aplicação completa.

## 7. Custom Speech

O **Custom Speech** permite adaptar o reconhecimento de fala para cenários em que o modelo base apresenta dificuldades, por exemplo, devido a vocabulário específico, terminologia técnica, sotaques ou características particulares do domínio.

A Microsoft documenta o uso de dados de treinamento e teste, incluindo áudio com transcrições humanas e dados textuais, conforme o idioma e o tipo de personalização disponível.

### Quando faz sentido personalizar

- vocabulário técnico;
- nomes próprios pouco comuns;
- terminologia empresarial;
- setores com linguagem especializada;
- ambientes acústicos ou padrões de fala específicos.

Modelos personalizados exigem dados adequados e avaliação cuidadosa. A qualidade dos dados de treinamento influencia diretamente a qualidade do resultado.

## 8. Integração com Azure Language

Um dos principais conceitos relacionados ao projeto é a integração entre processamento de fala e processamento de linguagem.

```text
Voz
 │
 ▼
Speech to Text
 │
 ▼
Transcrição
 │
 ▼
Azure Language
 │
 ├── Sentimento
 ├── Opinião
 ├── Entidades
 ├── Frases-chave
 └── Outros recursos de NLP
```

Esse fluxo demonstra como um dado originalmente não estruturado em áudio pode ser transformado em texto e posteriormente analisado por recursos de NLP.

> **Importante:** esse fluxo é uma possibilidade arquitetural estudada no projeto. Não deve ser interpretado como uma aplicação integrada implementada neste repositório.

## 9. Idiomas e localidades

O suporte de idiomas varia conforme o recurso. Speech to Text, Text to Speech, Pronunciation Assessment e Speech Translation não necessariamente possuem exatamente as mesmas localidades e capacidades.

Por isso, em uma implementação real, deve-se verificar a tabela oficial de idiomas e localidades antes de escolher o recurso, o modelo e a configuração regional.

## 10. Formas de integração

O Azure Speech pode ser integrado por meio do **Speech SDK**, APIs REST e ferramentas de linha de comando. A Microsoft disponibiliza exemplos para linguagens como Python, C#, Java, JavaScript, C++ e outras.

O Speech Studio é particularmente útil para exploração inicial, prototipação e testes rápidos antes da integração em uma aplicação.

## 11. IA responsável e limitações

Reconhecimento e síntese de fala podem envolver dados pessoais e características biométricas ou contextuais. Em aplicações reais, devem ser considerados consentimento, privacidade, segurança, retenção de dados, qualidade do áudio e possíveis erros de reconhecimento.

Também é necessário considerar que sotaques, ruído, sobreposição de vozes, vocabulário especializado e qualidade do microfone podem afetar a transcrição.

## 12. Escopo deste projeto

Os recursos de Azure Speech / Speech Studio foram apresentados no README principal como parte do laboratório e dos estudos realizados. Esta página consolida os conceitos técnicos para documentação do aprendizado.

## 13. Referências oficiais Microsoft

- [Azure Speech — visão geral](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/overview)
- [Azure Speech — documentação](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Speech Studio overview](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)
- [Speech Translation](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-translation)
- [Text to Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/text-to-speech)
- [Custom Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/custom-speech-overview)
- [Pronunciation Assessment](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-pronunciation-assessment)
- [Idiomas e vozes suportados](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)
