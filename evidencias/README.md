# Evidências

## 1. Objetivo

Esta pasta reúne as evidências visuais e documentais que comprovam as práticas realizadas durante o laboratório de **Azure AI, Azure Language / Language Studio e Azure Speech / Speech Studio**.

A função desta seção é separar claramente **o que foi efetivamente praticado** do conteúdo que foi apenas estudado conceitualmente.

## 2. Tipos de evidência

Podem ser organizados aqui:

- capturas de tela do Language Studio;
- capturas de tela do Speech Studio;
- resultados de análises de sentimentos;
- resultados de mineração de opinião;
- exemplos de entidades identificadas;
- resultados de extração de frases-chave;
- testes de detecção de idioma;
- resultados de sumarização;
- testes de Speech to Text;
- testes de Text to Speech;
- testes de Speech Translation;
- registros de Pronunciation Assessment;
- outros registros diretamente relacionados às práticas realizadas.

## 3. Organização recomendada

Quando as evidências forem adicionadas, recomenda-se utilizar nomes descritivos e ordenados, por exemplo:

```text
evidencias/
│
├── README.md
├── 01-language-studio-sentimentos.png
├── 02-language-studio-opiniao.png
├── 03-language-studio-entidades.png
├── 04-language-studio-frases-chave.png
├── 05-language-studio-idioma.png
├── 06-language-studio-sumarizacao.png
├── 07-speech-studio-speech-to-text.png
├── 08-speech-studio-text-to-speech.png
├── 09-speech-studio-translation.png
└── 10-speech-studio-pronunciation.png
```

A nomenclatura é uma sugestão de organização. Os nomes finais devem corresponder aos arquivos realmente existentes no repositório.

## 4. Como documentar uma evidência

Cada evidência deve, sempre que possível, estar associada a quatro informações:

| Informação | O que registrar |
|---|---|
| Recurso | Qual serviço ou funcionalidade foi testado |
| Ação | O que foi realizado |
| Entrada | Qual texto, áudio ou dado foi utilizado |
| Resultado | O que o serviço retornou ou apresentou |

### Exemplo

**Recurso:** análise de sentimentos  
**Ação:** envio de um comentário para análise  
**Entrada:** texto de avaliação  
**Resultado:** classificação de sentimento e pontuações de confiança

## 5. Evidência x documentação conceitual

Uma captura de tela de uma documentação da Microsoft **não deve ser apresentada como evidência de execução do laboratório**. Da mesma forma, um exemplo criado apenas para explicar um conceito não comprova que a funcionalidade foi utilizada na prática.

Por isso, esta pasta deve priorizar registros produzidos durante as atividades efetivamente realizadas.

## 6. Situação atual

O README principal informa que, neste momento, o projeto possui a documentação técnica consolidada, mas **não possui capturas de tela ou outras evidências visuais organizadas nesta seção**.

Assim, esta pasta está preparada para receber as evidências conforme forem organizadas, sem inventar ou atribuir ao laboratório resultados que não estejam documentados.

## 7. Critérios de qualidade

Antes de adicionar uma evidência, verificar:

- a imagem está legível;
- o recurso utilizado pode ser identificado;
- o contexto da ação está claro;
- não existem chaves, tokens ou informações pessoais expostas;
- o arquivo possui nome descritivo;
- a evidência corresponde realmente ao projeto.

## 8. Privacidade e segurança

Nunca publicar nesta pasta **chaves de API, tokens, senhas, endpoints privados, dados pessoais desnecessários ou informações confidenciais**.

Caso uma captura de tela contenha uma informação sensível, ela deve ser removida ou ocultada antes da publicação.

## 9. Referências oficiais

- [Azure Language — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Azure Speech — Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/)
- [Speech Studio overview](https://learn.microsoft.com/en-us/azure/ai-services/speech-service/speech-studio-overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
