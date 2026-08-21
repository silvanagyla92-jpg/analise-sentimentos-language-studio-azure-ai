# Summarization — Azure Language

## Visão geral

**Summarization** utiliza modelos de NLP para produzir uma representação mais curta de textos extensos. No Azure Language, há recursos de sumarização voltados a diferentes tipos de conteúdo, incluindo documentos e conversas, conforme as capacidades e versões atualmente suportadas.

A finalidade é reduzir o esforço necessário para compreender grandes volumes de informação, preservando os pontos considerados mais relevantes pelo modelo.

## Sumarização extrativa e abstrativa

É importante distinguir duas ideias:

- **Extrativa:** seleciona ou reorganiza trechos relevantes do texto original.
- **Abstrativa:** produz uma formulação nova que representa o conteúdo.

A técnica disponível depende do recurso, modelo e cenário. A documentação oficial deve ser consultada para verificar o comportamento vigente.

## Fluxo

```text
Documento / conversa
        ↓
Segmentação e processamento
        ↓
Identificação de informações relevantes
        ↓
Geração da representação resumida
        ↓
Revisão e utilização
```

## Aplicações

- resumos de documentos;
- síntese de relatórios;
- apoio à leitura de grandes volumes de texto;
- resumo de conversas e atendimentos;
- preparação de informação para análise humana;
- redução de tempo de triagem.

## Exemplo conceitual

Um relatório de 20 páginas pode conter histórico, contexto, resultados e recomendações. Uma sumarização bem configurada pode produzir uma visão compacta desses elementos, permitindo que o usuário decida quais partes merecem leitura detalhada.

## Limitações

Um resumo é uma transformação do conteúdo, não uma cópia integral. Informações importantes podem ser omitidas, simplificadas ou apresentadas sem a nuance original. Em conteúdo jurídico, médico, financeiro ou operacional crítico, o resumo não deve substituir a fonte primária.

Também é importante avaliar possíveis erros de interpretação, especialmente quando o texto possui negações, relações causais, números, exceções ou referências espalhadas por diferentes partes do documento.

## Processamento assíncrono

A Microsoft documenta suporte a processamento assíncrono para sumarização e outros recursos de Language. Esse modelo é útil para trabalhos em lote, nos quais a aplicação envia dados, acompanha o processamento e recupera os resultados posteriormente.

## Relação com este projeto

A sumarização demonstra como NLP pode transformar grandes quantidades de texto em informação mais acessível. No contexto do portfólio, também reforça a importância de **avaliar criticamente a saída de modelos de IA**, verificando fidelidade e preservação do significado.

## Fontes oficiais

- [Microsoft Learn — Azure Language overview](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview)
- [Microsoft Learn — Asynchronous Language features](https://learn.microsoft.com/en-us/azure/ai-services/language-service/concepts/use-asynchronously)
- [Microsoft Learn — Azure Language REST API](https://learn.microsoft.com/en-us/rest/api/language/)

---

**Projeto:** Análise de Sentimentos e Processamento de Linguagem Natural com Azure AI  
**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
