# Key Phrase Extraction — Azure Language

## Visão geral

**Key Phrase Extraction** identifica os principais conceitos e termos relevantes presentes em texto não estruturado. O objetivo é reduzir grandes volumes de conteúdo a um conjunto de expressões que represente seus temas centrais.

É importante diferenciar esse recurso de um resumo. A extração de frases-chave seleciona conceitos relevantes; ela não necessariamente produz um novo texto coerente e completo.

## Exemplo conceitual

Entrada:

> "A equipe de suporte resolveu rapidamente o problema de conexão e explicou como configurar o aplicativo."

As frases-chave poderiam destacar conceitos relacionados a **suporte**, **problema de conexão**, **configuração do aplicativo** e outros termos relevantes retornados pelo modelo.

## Fluxo

```text
Texto não estruturado
        ↓
Processamento linguístico
        ↓
Identificação de conceitos relevantes
        ↓
Lista de frases-chave
        ↓
Agrupamento / indexação / análise
```

## Aplicações

- indexação de documentos;
- organização de grandes coleções textuais;
- criação de metadados;
- descoberta de temas;
- preparação de dados para busca;
- análise de feedback;
- apoio à classificação e exploração de documentos.

## Diferença para outros recursos

| Recurso | Objetivo |
|---|---|
| Key Phrase Extraction | Encontrar conceitos importantes |
| Summarization | Produzir uma versão resumida do conteúdo |
| NER | Identificar entidades como pessoas, locais e organizações |
| Sentiment Analysis | Estimar polaridade |

## Boas práticas

O contexto disponível influencia o resultado. Para análises mais úteis, é importante fornecer texto suficientemente representativo e interpretar as frases-chave junto com a fonte original. Uma lista de termos isolados não substitui a leitura do documento quando decisões dependem de contexto.

A Microsoft também disponibiliza processamento por APIs e bibliotecas cliente e possui modalidades assíncronas para determinados cenários de processamento em lote.

## IA responsável

Frases-chave podem refletir padrões estatísticos do texto e não necessariamente representam todos os assuntos relevantes. Em conteúdos sensíveis ou de alto impacto, os resultados devem ser validados antes de serem usados para decisões automatizadas.

## Atualização de ciclo de vida

A documentação atual da Microsoft informa mudanças no ciclo de vida de recursos do Azure Language. Para novos projetos, é importante verificar a orientação vigente no Microsoft Foundry antes de construir dependências de longo prazo.

## Fontes oficiais

- [Microsoft Learn — Key Phrase Extraction](https://learn.microsoft.com/en-us/azure/ai-services/language-service/key-phrase-extraction/overview)
- [Microsoft Learn — Azure Language overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
