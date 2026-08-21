# Speech to Text — Azure Speech

## Visão geral

**Speech to Text (STT)** converte fala em texto utilizando modelos de reconhecimento automático de fala. A tecnologia permite que aplicações processem áudio como dados textuais e, a partir daí, executem outras tarefas de NLP.

O recurso é especialmente importante em fluxos multimodais nos quais a entrada original é voz, mas a análise posterior acontece sobre texto.

## Fluxo

```text
Áudio / voz
    ↓
Captura e transmissão
    ↓
Modelo de reconhecimento de fala
    ↓
Transcrição
    ↓
Texto estruturado
    ↓
Azure Language / aplicação
```

## Modos de uso

Dependendo do cenário, o Azure Speech oferece reconhecimento de áudio curto, reconhecimento contínuo e recursos para processamento em lote. A escolha depende da duração do áudio, latência desejada e arquitetura da aplicação.

## Exemplo de integração com NLP

```text
Usuário fala
    ↓
Speech to Text
    ↓
"O atendimento demorou muito"
    ↓
Sentiment Analysis
    ↓
Sentimento negativo
```

Esse fluxo demonstra a integração conceitual entre **Azure Speech** e **Azure Language**.

## Aplicações

- transcrição de reuniões;
- acessibilidade;
- atendimento ao cliente;
- assistentes de voz;
- análise de chamadas;
- legendagem;
- entrada de voz em aplicações.

## Qualidade da transcrição

Ruído, microfone, distância do locutor, sobreposição de falas, sotaque, velocidade da fala e vocabulário específico podem afetar o reconhecimento. A transcrição deve ser validada quando for usada em processos críticos.

## Idiomas e localidades

O suporte varia por recurso e localidade. A Microsoft mantém uma tabela específica para verificar quais idiomas e localidades estão disponíveis para Speech to Text, Text to Speech, tradução e outros recursos.

## IA responsável

Uma transcrição pode conter informações pessoais e confidenciais. Aplicações devem controlar acesso aos áudios e textos derivados, definir políticas de retenção e informar os usuários quando apropriado sobre o processamento de voz.

## Relação com o projeto

O STT é uma etapa importante do fluxo estudado no projeto porque permite transformar **voz em texto analisável**. Depois da transcrição, recursos de NLP podem identificar sentimento, entidades, frases-chave ou outros sinais linguísticos.

## Fontes oficiais

- [Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Microsoft Learn — Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)
- [Microsoft Learn — Azure Language](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
