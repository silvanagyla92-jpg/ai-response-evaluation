# Hugging Face

## 1. Objetivo

Esta pasta registra estudos e práticas relacionados ao ecossistema **Hugging Face**, incluindo modelos, datasets, tokenizadores, bibliotecas e materiais educacionais.

O ecossistema é especialmente relevante para este projeto porque conecta conceitos de LLMs e processamento de linguagem natural a artefatos concretos de modelos, dados e ferramentas de avaliação.

## 2. Principais componentes

### Modelos

O Hub disponibiliza modelos que podem ser pesquisados, avaliados e utilizados em diferentes tarefas. A escolha de um modelo deve considerar tarefa, dados, limitações, licença e desempenho observado.

### Datasets

Datasets são conjuntos estruturados de dados utilizados em treinamento, validação, teste ou avaliação. A documentação oficial da biblioteca Datasets aborda carregamento, processamento e compartilhamento de conjuntos de dados.

### Tokenizers

Tokenizadores convertem texto em unidades que podem ser processadas por modelos de linguagem. O modo como o texto é tokenizado influencia representação, comprimento de entrada e uso do contexto.

### Transformers

A biblioteca Transformers fornece ferramentas para trabalhar com modelos de Transformer e diferentes tarefas de linguagem e outras modalidades. O curso oficial apresenta arquiteturas, inferência, fine-tuning e avaliação. citeturn0search3

## 3. Relação com avaliação de respostas

A Hugging Face também é útil para compreender a cadeia:

```text
Dados
  ↓
Preparação / tokenização
  ↓
Modelo
  ↓
Inferência ou treinamento
  ↓
Avaliação
  ↓
Análise dos resultados
```

Avaliar um sistema exige considerar a tarefa e o conjunto de dados. Uma métrica isolada não substitui uma análise contextual da qualidade.

## 4. Curadoria e qualidade de dados

A qualidade de um dataset é parte importante de qualquer processo de desenvolvimento de IA. Questões de duplicação, inconsistência, representatividade, ruído e adequação à tarefa podem afetar treinamento e avaliação.

Para este projeto, o estudo de datasets é diretamente relacionado à competência de **Data Annotator**, pois ajuda a compreender como dados rotulados e estruturados podem ser usados em processos de IA.

## 5. LLMs e aprendizado

O curso oficial da Hugging Face aborda LLMs, Transformers, datasets, tokenizadores, fine-tuning e curadoria de datasets. Ele também recomenda conhecimento prévio de Python e fundamentos de aprendizado profundo para melhor aproveitamento. citeturn0search3turn0search2

## 6. Competências relacionadas

- LLMs;
- NLP;
- Transformers;
- datasets;
- tokenização;
- inferência;
- fine-tuning;
- avaliação de modelos;
- curadoria de dados;
- análise crítica de outputs.

## 7. Fontes confiáveis

- [Hugging Face — Learn](https://huggingface.co/learn)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Datasets Documentation](https://huggingface.co/docs/datasets/index)
- [Hugging Face — Transformers Documentation](https://huggingface.co/docs/transformers/index)
- [Hugging Face — Tokenizers Documentation](https://huggingface.co/docs/tokenizers/index)

As ferramentas e versões evoluem. Para atividades técnicas, a documentação oficial correspondente à versão utilizada deve ser considerada a referência principal.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
