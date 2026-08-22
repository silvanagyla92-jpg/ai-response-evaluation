# Conceitos Explicados

## 1. Objetivo

A pasta **CONCEITOS-EXPLICADOS** reúne conteúdos didáticos sobre fundamentos de Inteligência Artificial que servem como base conceitual para as avaliações deste projeto. O foco é transformar conceitos técnicos em explicações claras, verificáveis e adequadas a diferentes níveis de conhecimento, mantendo atenção à precisão terminológica e às limitações dos modelos de IA.

Os conteúdos desta área apoiam principalmente as atividades de **AI Response Evaluator**, **AI Trainer** e **Data Annotator**, porque uma avaliação consistente depende da compreensão do conceito que está sendo explicado, comparado ou avaliado.

## 2. Escopo dos conceitos

Os quatro módulos iniciais foram organizados para formar uma sequência progressiva:

1. **Inteligência Artificial e Aprendizado de Máquina** — fundamentos, relação entre IA, aprendizado de máquina e aprendizado profundo, dados, treinamento, inferência e padrões.
2. **Grandes Modelos de Linguagem (LLMs)** — funcionamento conceitual, treinamento, tokens, contexto, geração de texto, limitações e avaliação.
3. **Embeddings e RAG** — representação vetorial, busca semântica, recuperação de informação e geração aumentada por recuperação.
4. **Agentes de IA** — modelos com ferramentas, memória, planejamento, tomada de decisão e execução de fluxos de trabalho.

Essa divisão permite estudar desde os fundamentos até arquiteturas mais compostas utilizadas em aplicações modernas de IA generativa.

## 3. Como os conteúdos são utilizados nas avaliações

Os conceitos não são tratados apenas como material teórico. Eles servem como referência para:

- verificar a **factualidade** de respostas;
- identificar simplificações aceitáveis e erros conceituais;
- avaliar se uma explicação é adequada ao público solicitado;
- verificar a **completude** de uma resposta;
- distinguir informação factual de metáfora, hipótese ou opinião;
- reconhecer possíveis **alucinações**;
- comparar respostas de diferentes modelos;
- apoiar a criação e a aplicação de critérios de avaliação reproduzíveis.

## 4. Princípios de elaboração

### Precisão

As explicações devem representar o conceito de maneira tecnicamente defensável, evitando afirmações absolutas quando o tema depender de contexto.

### Clareza

A linguagem deve ser adaptada ao público-alvo. Um conceito pode ser tecnicamente correto e ainda assim ser inadequado se for explicado com complexidade desnecessária.

### Rastreabilidade

Quando informações externas forem utilizadas, as fontes devem ser identificadas para permitir conferência posterior.

### Separação entre fato e simplificação

Metáforas e analogias podem facilitar a compreensão, mas devem ser reconhecidas como recursos didáticos e não como definições literais do funcionamento de um sistema.

### Atualização

IA generativa, LLMs, RAG e agentes são áreas em rápida evolução. Por isso, os conteúdos devem ser revisados quando houver mudanças relevantes em conceitos, arquiteturas, práticas ou documentação.

## 5. Fontes de referência

A curadoria inicial utiliza materiais educacionais e técnicos de organizações reconhecidas, incluindo IBM, Microsoft, Google Cloud e Hugging Face. As fontes são utilizadas para fundamentação conceitual, não como substitutas da análise crítica realizada nas avaliações.

- [IBM Think — Inteligência Artificial e Aprendizado de Máquina](https://www.ibm.com/think/topics)
- [IBM Think — LLMs](https://www.ibm.com/br-pt/think/topics/large-language-models)
- [IBM Think — RAG agêntica](https://www.ibm.com/br-pt/think/topics/agentic-rag)
- [IBM Think — Agentes de IA](https://www.ibm.com/br-pt/think/topics/ai-agents)
- [Microsoft Learn — Azure AI](https://learn.microsoft.com/azure/ai-services/)
- [Google Cloud — Inteligência Artificial](https://cloud.google.com/ai)
- [Hugging Face Learn](https://huggingface.co/learn)

## 6. Relação com o portfólio

Esta seção funciona como uma base conceitual para as demais áreas do repositório. O objetivo não é apenas demonstrar conhecimento de termos de IA, mas evidenciar a capacidade de interpretar conceitos, verificar respostas e registrar decisões de avaliação com critérios claros.

## 7. Estrutura

```text
CONCEITOS-EXPLICADOS/
├── README.md
├── 001-fundamentos-ia-machine-learning/
│   └── README.md
├── 002-grandes-modelos-de-linguagem/
│   └── README.md
├── 003-embeddings-e-rag/
│   └── README.md
└── 004-agentes-de-ia/
    └── README.md
```

**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
