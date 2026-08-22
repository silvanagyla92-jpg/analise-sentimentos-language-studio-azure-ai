# Evidências Documentais — Azure Speech

## 1. Objetivo

Esta pasta documenta como poderiam ser organizadas evidências relacionadas ao **Azure Speech**. Como o projeto foi desenvolvido sem uma assinatura Azure disponível para execução dos serviços, **não são apresentadas capturas de tela, transcrições reais ou resultados experimentais produzidos diretamente pelo Speech Studio**.

O conteúdo desta seção complementa o estudo teórico de `azure-speech/` e define critérios para uma eventual documentação prática futura.

## 2. Recursos estudados

O projeto aborda conceitualmente:

- Speech to Text;
- Text to Speech;
- Speech Translation;
- Pronunciation Assessment.

## 3. O que seria uma evidência prática

Com acesso futuro a um ambiente compatível, poderiam ser registrados:

- ferramenta e recurso utilizado;
- idioma e localidade;
- áudio ou texto de entrada;
- configurações relevantes;
- transcrição ou saída gerada;
- resultado de tradução;
- resultado de síntese de voz;
- avaliação de pronúncia;
- interpretação e limitações observadas.

Somente resultados realmente produzidos durante uma execução devem ser apresentados como evidência.

## 4. Exemplo conceitual de registro

**Recurso:** Speech to Text  
**Objetivo:** observar a conversão de fala em texto  
**Entrada:** áudio de teste autorizado  
**Resultado esperado segundo a documentação:** transcrição correspondente ao áudio  
**Interpretação:** avaliação da qualidade da transcrição considerando idioma, pronúncia, ruído e contexto  
**Observação:** esse registro é apenas um modelo documental e **não representa uma execução realizada neste projeto**.

## 5. Relação com NLP

Um fluxo possível em uma solução real seria:

Áudio
→ Speech to Text
→ Texto
→ Azure Language
→ análise de linguagem

Esse fluxo é apresentado neste projeto como arquitetura conceitual. Ele não comprova que uma integração ponta a ponta tenha sido executada.

## 6. Qualidade e interpretação

Uma futura evidência de Speech deve considerar fatores como:

- qualidade do áudio;
- ruído ambiente;
- microfone;
- idioma;
- localidade;
- duração do áudio;
- pronúncia;
- vocabulário e contexto.

Esses fatores podem influenciar a saída do serviço.

## 7. Privacidade e segurança

Áudios podem conter informações pessoais e características identificáveis da voz. Não devem ser publicados registros de terceiros sem autorização.

Também não devem ser publicados:

- chaves de API;
- tokens;
- senhas;
- credenciais;
- endpoints privados;
- informações confidenciais.

## 8. Evidência x documentação

Uma explicação sobre Speech to Text é documentação técnica. Um áudio criado apenas para ilustrar o conceito é exemplo didático. Uma transcrição realmente produzida por uma execução documentada é evidência prática.

O repositório mantém essas categorias separadas para não atribuir ao projeto resultados que não foram observados diretamente.

## 9. Fontes oficiais

- [Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Microsoft Learn — Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)
- [Microsoft Learn — Pronunciation Assessment](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/how-to-pronunciation-assessment)
- [Microsoft Learn — Speech Studio](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
