# Text to Speech — Azure Speech

## Visão geral

**Text to Speech (TTS)** converte texto em fala sintetizada. Ele permite que uma aplicação transforme respostas textuais em áudio, criando interfaces mais acessíveis e experiências conversacionais.

## Fluxo

```text
Texto gerado
    ↓
Seleção de idioma / voz
    ↓
Síntese de fala
    ↓
Áudio
    ↓
Reprodução ou armazenamento
```

O resultado depende da voz, idioma, localidade e configuração utilizada. O suporte de vozes e localidades deve ser verificado na documentação oficial.

## Aplicações

- leitores de texto;
- acessibilidade;
- assistentes virtuais;
- sistemas de atendimento;
- conteúdos educacionais;
- navegação e orientação por voz;
- respostas faladas em aplicações multimodais.

## Relação com Speech to Text

Os dois recursos podem formar um ciclo conversacional:

```text
Pessoa fala
   ↓
Speech to Text
   ↓
Texto
   ↓
Processamento / IA
   ↓
Texto de resposta
   ↓
Text to Speech
   ↓
Pessoa ouve
```

Esse padrão é uma base para muitos sistemas de interação por voz.

## Voz neural e naturalidade

A síntese moderna procura produzir fala com características naturais de pronúncia e prosódia. Mesmo assim, naturalidade percebida pode variar conforme idioma, voz, conteúdo e contexto. A seleção de uma voz apropriada faz parte do design da experiência.

## Responsabilidade e transparência

Quando uma voz sintetizada representa um assistente, personagem ou serviço, é importante não induzir o usuário a acreditar que está interagindo com uma pessoa real quando isso não é verdade. Também devem ser considerados direitos de uso, privacidade e proteção de dados.

## Qualidade

Nomes próprios, siglas, números, abreviações e termos técnicos podem exigir atenção especial. Testes com frases reais do domínio ajudam a verificar pronúncia e inteligibilidade antes da adoção em produção.

## Relação com o projeto

O TTS representa a etapa inversa do STT: **texto → voz**. No contexto deste portfólio, ele complementa o estudo de aplicações que combinam voz, processamento de linguagem natural e IA.

## Fontes oficiais

- [Microsoft Learn — Azure Speech](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Microsoft Learn — Language and voice support](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/language-support)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
