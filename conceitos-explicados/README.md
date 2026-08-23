# Conceitos Explicados

## 1. Objetivo

A pasta **conceitos-explicados** reúne a base conceitual que sustenta as avaliações deste projeto. O objetivo é apresentar, de forma organizada e verificável, fundamentos de Inteligência Artificial, Aprendizado de Máquina, Grandes Modelos de Linguagem, embeddings, RAG e agentes de IA.

Os conteúdos funcionam como referência para as avaliações práticas porque uma análise de resposta exige conhecimento suficiente para diferenciar uma definição correta de uma simplificação excessiva, um erro factual, uma alucinação ou uma afirmação antropomórfica sem fundamento.

## 2. Fundamentos de Inteligência Artificial e Aprendizado de Máquina

### Inteligência Artificial

Inteligência Artificial é um campo amplo da computação dedicado ao desenvolvimento de sistemas capazes de executar tarefas associadas a capacidades como percepção, aprendizagem, resolução de problemas, tomada de decisão e geração de conteúdo. IA não corresponde a uma única técnica ou arquitetura.

### Aprendizado de Máquina

Aprendizado de Máquina é um subconjunto da IA no qual algoritmos aprendem padrões a partir de dados e utilizam esses padrões para realizar inferências ou previsões sobre novos dados. A IBM descreve ML como uma área concentrada em aprender padrões dos dados de treinamento e realizar inferências sobre novos dados. [IBM — O que é aprendizado de máquina](https://www.ibm.com/br-pt/think/topics/machine-learning)

### Tipos de aprendizado

Entre as categorias amplamente utilizadas estão aprendizado supervisionado, não supervisionado, semissupervisionado, auto-supervisionado e por reforço. A escolha depende do problema, dos dados e do objetivo. [IBM — Tipos de aprendizado de máquina](https://www.ibm.com/br-pt/think/topics/machine-learning-types)

### Aprendizado profundo

Aprendizado Profundo é uma abordagem baseada em redes neurais com múltiplas camadas. É utilizado em tarefas envolvendo padrões complexos, incluindo linguagem, imagens e áudio.

### Treinamento e inferência

Durante o treinamento, parâmetros do modelo são ajustados de acordo com os dados e o objetivo definido. Na inferência, o modelo recebe novos dados e produz uma saída utilizando os padrões incorporados em seus parâmetros.

É importante não concluir que maior quantidade de dados garante automaticamente maior qualidade. Qualidade, diversidade, representatividade, preparação dos dados, arquitetura, objetivo e avaliação também importam.

## 3. Grandes Modelos de Linguagem — LLMs

### Conceito

Um Grande Modelo de Linguagem, ou LLM, é um modelo de aprendizado profundo treinado em grandes quantidades de dados para processar e gerar linguagem natural. A Hugging Face apresenta LLMs no contexto de NLP e descreve o ecossistema de Transformers, Datasets e Tokenizers utilizado para trabalhar com esses modelos. [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

### Tokens e contexto

Antes de processar uma entrada textual, o conteúdo é dividido em unidades chamadas tokens. O modelo opera dentro de uma janela de contexto que limita a quantidade de informação considerada em uma interação.

A presença de uma informação na janela de contexto não significa que ela será necessariamente considerada correta ou igualmente relevante.

### Geração

Durante a inferência, o modelo recebe uma entrada e gera uma sequência de saída considerando o contexto e as configurações utilizadas. A saída não deve ser tratada automaticamente como consulta a uma base de fatos perfeita.

### Limitações

LLMs podem produzir respostas linguisticamente convincentes e incorretas. Também podem reproduzir vieses presentes nos dados e apresentar desempenho diferente conforme a tarefa, idioma, contexto e configuração.

## 4. Embeddings e RAG

### Embeddings

Embeddings são representações numéricas de conteúdos como palavras, trechos, documentos ou consultas. O conteúdo é transformado em vetores que podem ser comparados matematicamente para identificar relações de similaridade.

Essas representações são úteis em mecanismos de busca semântica, recomendação, classificação e recuperação de informação. Um embedding não é uma representação perfeita de todo o significado de um texto; ele captura relações úteis de acordo com o modelo e a tarefa.

### RAG

RAG, sigla de *Retrieval-Augmented Generation*, combina recuperação de informações com geração de texto. Uma arquitetura típica prepara uma consulta, recupera conteúdos relevantes e fornece os trechos encontrados ao modelo generativo como contexto.

A documentação da Microsoft destaca que RAG pode fundamentar respostas em conteúdo próprio, mas também apresenta desafios relacionados a compreensão de consultas, acesso a múltiplas fontes, limites de tokens, latência, relevância, governança e segurança. [Microsoft Learn — RAG e IA generativa](https://learn.microsoft.com/pt-br/azure/search/retrieval-augmented-generation-overview)

### Fluxo conceitual

```text
Consulta do usuário
        ↓
Preparação da consulta
        ↓
Recuperação de conteúdo
        ↓
Contexto relevante
        ↓
Modelo de linguagem
        ↓
Resposta
```

### Recuperação e geração

A qualidade do RAG depende tanto da recuperação quanto da geração. Documentos inadequados, fragmentação ruim ou recuperação pouco relevante podem prejudicar o resultado. Mesmo com bons trechos recuperados, o modelo pode interpretar ou sintetizar o contexto incorretamente.

Por isso, avaliações de RAG devem distinguir **qualidade da recuperação**, **qualidade do contexto** e **qualidade da resposta gerada**.

## 5. Agentes de Inteligência Artificial

### Conceito

Um agente de IA é um sistema projetado para executar tarefas ou atingir objetivos utilizando um modelo, instruções, informações e ferramentas. A documentação do Microsoft Foundry descreve agentes como aplicações capazes de raciocinar sobre solicitações, chamar ferramentas, acessar dados externos e tomar decisões em várias etapas. [Microsoft Learn — Microsoft Foundry Agent Service](https://learn.microsoft.com/pt-br/azure/ai-foundry/agents/overview)

### Componentes

**Modelo:** fornece capacidades de linguagem e raciocínio.

**Instruções:** definem objetivos, limites e comportamento esperado.

**Ferramentas:** permitem acesso a dados ou ações, como pesquisa, arquivos, APIs ou funções.

**Memória:** pode preservar informações relevantes conforme a arquitetura.

**Planejamento:** permite decompor tarefas e decidir ações intermediárias quando necessário.

### Fluxo simplificado

```text
Objetivo / instrução
        ↓
Interpretação e planejamento
        ↓
Escolha de ferramenta
        ↓
Execução
        ↓
Observação do resultado
        ↓
Novo passo ou conclusão
```

### Agente não é sinônimo de chatbot

Um chatbot pode limitar-se à geração de texto. Um agente pode utilizar ferramentas, acessar fontes externas e executar ações em múltiplas etapas. A diferença deve ser analisada pela arquitetura e pelas capacidades efetivamente disponíveis, não apenas pelo nome da aplicação.

### Autonomia e controle

Autonomia não significa ausência de controle. Permissões, ferramentas, políticas, autenticação, monitoramento, limites de ação e intervenção humana são componentes relevantes de sistemas agênticos.

## 6. Relação entre os conceitos

```text
Inteligência Artificial
        ↓
Aprendizado de Máquina
        ↓
Aprendizado Profundo
        ↓
Grandes Modelos de Linguagem
        ↓
Embeddings / Recuperação / RAG
        ↓
Agentes de IA
```

Essa sequência é didática e não representa uma hierarquia obrigatória de implementação. Um LLM é uma aplicação de aprendizado profundo; embeddings podem apoiar recuperação; RAG pode fornecer contexto a um modelo; e agentes podem combinar modelos, ferramentas, memória e recuperação.

## 7. Aplicação na avaliação de respostas

A base conceitual será utilizada para verificar:

- correção de definições;
- distinção entre fato e simplificação;
- adequação da linguagem;
- completude;
- afirmações absolutas;
- antropomorfização indevida;
- diferenças entre treinamento e inferência;
- papel e qualidade dos dados;
- alucinações;
- recuperação e geração em RAG;
- diferença entre chatbot e agente;
- segurança e controle de agentes.

Uma resposta tecnicamente sofisticada não deve receber nota alta automaticamente. A avaliação precisa considerar o que foi solicitado e o público definido pela tarefa.

## 8. Fontes e atualização

A base deste README é complementada por documentação técnica e educacional de fontes reconhecidas:

- [IBM — Guia de Inteligência Artificial](https://www.ibm.com/think/topics/ai-guide)
- [IBM — Aprendizado de Máquina](https://www.ibm.com/br-pt/think/topics/machine-learning)
- [IBM — Tipos de aprendizado de máquina](https://www.ibm.com/br-pt/think/topics/machine-learning-types)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Microsoft Learn — Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)
- [Microsoft Learn — RAG e IA generativa](https://learn.microsoft.com/pt-br/azure/search/retrieval-augmented-generation-overview)
- [Microsoft Learn — Microsoft Foundry Agent Service](https://learn.microsoft.com/pt-br/azure/ai-foundry/agents/overview)

Como tecnologias e plataformas de IA evoluem rapidamente, informações dependentes de versão devem ser verificadas na documentação oficial correspondente no momento da avaliação.

## 9. Estrutura para as avaliações

As quatro subpastas oficiais ficam reservadas para os conteúdos práticos correspondentes aos temas conceituais:

```text
conceitos-explicados/
├── README.md
├── 001-fundamentos-ia-machine-learning/
├── 002-grandes-modelos-de-linguagem/
├── 003-embeddings-e-rag/
└── 004-agentes-de-ia/
```

As avaliações futuras serão colocadas nas pastas temáticas correspondentes, mantendo o README desta pasta como referência consolidada.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
