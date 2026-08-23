# Evaluations

## 1. Objetivo

A pasta **evaluations** reúne os casos práticos individuais de avaliação de respostas de Inteligência Artificial. Cada arquivo representa uma avaliação documentada, permitindo acompanhar a tarefa, as respostas analisadas, os critérios utilizados, as evidências, a pontuação e a decisão final.

## 2. Finalidade

O conjunto de avaliações funciona como evidência prática das competências desenvolvidas no projeto. Os casos podem envolver diferentes modelos, plataformas, tipos de instrução, critérios de qualidade e cenários de comparação.

A proposta é manter cada avaliação suficientemente detalhada para que uma terceira pessoa consiga compreender o que foi solicitado, o que foi respondido e por que determinada decisão foi registrada.

## 3. Estrutura de uma avaliação

Quando aplicável, cada avaliação pode conter:

1. Introdução e objetivo.
2. Contexto.
3. Pergunta ou instrução original.
4. Respostas avaliadas.
5. Requisitos explícitos.
6. Rubrica e critérios.
7. Verificação de cumprimento das instruções.
8. Análise por critério.
9. Pontuação.
10. Comparação e preferência, quando aplicável.
11. Parecer.
12. Conclusão.
13. Competências demonstradas.
14. Fontes, quando utilizadas.

## 4. Rubrica-base

A rubrica utilizada no projeto pode trabalhar com seis dimensões principais:

| Critério | Pergunta central |
|---|---|
| Factualidade | O conteúdo está correto? |
| Relevância | A resposta permanece no escopo? |
| Clareza | A comunicação é compreensível e adequada? |
| Completude | Os requisitos necessários foram contemplados? |
| Segurança | Existe conteúdo que introduza risco relevante? |
| Alucinação | Há conteúdo fabricado ou não sustentado? |

Cada avaliação pode adaptar a aplicação dos critérios ao objetivo específico, sem alterar arbitrariamente a definição da rubrica dentro do mesmo caso.

## 5. Evidência

A evidência deve ser retirada da própria resposta sempre que possível. O trecho selecionado deve preservar contexto suficiente para sustentar a decisão.

Quando uma fonte externa for necessária para verificar uma afirmação, ela deve ser identificada de forma rastreável.

## 6. Cumprimento de instruções

O cumprimento de instruções pode ser registrado separadamente da pontuação oficial quando a tarefa tiver requisitos específicos, como número exato de frases, formato, idioma, público-alvo ou posição obrigatória de determinada informação.

Isso permite verificar conformidade sem transformar automaticamente cada requisito em um novo critério de pontuação.

## 7. Comparação de modelos

Quando duas respostas forem geradas para a mesma solicitação, cada uma deve ser analisada individualmente antes da comparação. A preferência qualitativa deve ser fundamentada e não precisa alterar a pontuação oficial quando a rubrica resultar em empate.

## 8. Verificação e atualização

Como conteúdos de Inteligência Artificial evoluem rapidamente, informações que dependem de versões de plataformas, APIs ou documentação atual devem ser verificadas na fonte oficial correspondente no momento da avaliação.

## 9. Organização

```text
evaluations/
├── README.md
├── avaliacao-001.md
├── avaliacao-002.md
├── ...
└── avaliacao-015.md
```

Novas avaliações podem ser adicionadas mantendo a numeração e a estrutura documental do projeto.

## 10. Competências demonstradas

- AI Response Evaluation;
- AI Trainer;
- Data Annotation;
- Prompt Evaluation;
- Instruction Following;
- Comparative Evaluation;
- Evidence-Based Decision Making;
- QA e Auditoria aplicada a outputs de IA.

## 11. Fontes de estudo

- [IBM — Machine Learning](https://www.ibm.com/br-pt/think/topics/machine-learning)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Microsoft Learn — Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)
- [Microsoft Learn — RAG e IA generativa](https://learn.microsoft.com/pt-br/azure/search/retrieval-augmented-generation-overview)
- [Microsoft Learn — Microsoft Foundry Agent Service](https://learn.microsoft.com/pt-br/azure/ai-foundry/agents/overview)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
