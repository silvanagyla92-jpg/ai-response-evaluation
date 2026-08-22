# 003 — Embeddings e RAG

## Objetivo

Explicar como textos podem ser representados matematicamente para permitir comparação semântica e como a geração aumentada por recuperação (RAG) utiliza recuperação de informações externas para fornecer contexto a modelos generativos.

## O que são embeddings

Embeddings são representações numéricas de conteúdos, como palavras, trechos de texto, documentos ou consultas. O conteúdo é transformado em vetores que podem ser comparados matematicamente para identificar relações de similaridade.

Em aplicações de busca semântica, a representação vetorial permite procurar conteúdos relacionados ao significado de uma consulta, mesmo quando as palavras utilizadas na consulta não são exatamente iguais às palavras presentes no documento.

É importante não afirmar que embeddings representam "o significado completo" de um texto de forma perfeita. Eles são representações aprendidas que capturam determinadas relações úteis para uma tarefa e dependem do modelo utilizado.

## O que é RAG

RAG, sigla de Retrieval-Augmented Generation, é uma abordagem que combina recuperação de informações com geração de texto. Em uma arquitetura típica, uma consulta é transformada em uma representação adequada para busca, documentos relevantes são recuperados e o conteúdo recuperado é fornecido ao modelo generativo como contexto.

A principal vantagem é permitir que o sistema utilize informações externas à memória paramétrica do modelo. Isso pode melhorar respostas sobre conteúdos específicos ou que mudam com o tempo, desde que a fonte utilizada seja adequada e a recuperação funcione corretamente.

## Fluxo conceitual

```text
Consulta do usuário
       ↓
Representação / consulta para busca
       ↓
Recuperação de documentos relevantes
       ↓
Contexto recuperado
       ↓
Modelo de linguagem
       ↓
Resposta fundamentada no contexto disponível
```

## Componentes importantes

### Documentos e preparação

Os documentos precisam ser organizados e, frequentemente, divididos em partes menores. O particionamento deve preservar contexto suficiente para que os trechos recuperados sejam úteis.

### Embedding

Um modelo de embeddings transforma documentos e consultas em vetores que podem ser comparados por medidas de similaridade.

### Índice ou banco vetorial

Os vetores podem ser armazenados em estruturas de busca apropriadas para localizar conteúdos semanticamente relacionados.

### Recuperação

A consulta é usada para localizar os trechos mais relevantes. Estratégias híbridas podem combinar correspondência lexical e busca vetorial.

### Geração

Os trechos recuperados são inseridos no contexto fornecido ao modelo generativo, que produz a resposta com base nessa informação e na instrução recebida.

## Limitações do RAG

RAG não garante automaticamente respostas corretas. Se os documentos forem inadequados, estiverem desatualizados ou se a recuperação trouxer trechos irrelevantes, a resposta final também poderá ser inadequada. Além disso, o modelo generativo pode interpretar incorretamente o contexto recuperado.

## Relação com avaliação

Em uma avaliação de respostas de RAG, é importante separar a qualidade da recuperação da qualidade da geração. Uma resposta pode ser linguisticamente clara, mas estar fundamentada em contexto irrelevante; também pode receber bons documentos e ainda produzir uma síntese incorreta.

## Pontos para verificação em avaliações

- O conceito de embedding foi explicado como representação vetorial?
- A resposta diferencia busca semântica de simples correspondência de palavras?
- O papel da recuperação no RAG foi identificado?
- A resposta evita afirmar que RAG elimina completamente alucinações?
- A fonte recuperada é tratada como parte importante da qualidade da resposta?

## Fontes

- [IBM Think — RAG agêntica](https://www.ibm.com/br-pt/think/topics/agentic-rag)
- [IBM Think — Agentic Chunking](https://www.ibm.com/think/topics/agentic-chunking)
- [Microsoft Learn — Azure AI Search](https://learn.microsoft.com/azure/search/)
- [Hugging Face Learn](https://huggingface.co/learn)

**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
