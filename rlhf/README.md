# RLHF — Reinforcement Learning from Human Feedback

## 1. Objetivo

Esta seção apresenta exercícios relacionados a **RLHF (Reinforcement Learning from Human Feedback)**, com foco na utilização de preferências humanas para orientar a avaliação e o desenvolvimento de sistemas de IA.

No contexto deste projeto, o foco prático é a comparação de respostas, identificação de diferenças de qualidade, escolha de preferência e justificativa baseada em evidências. O exercício não pretende reproduzir uma infraestrutura completa de treinamento de modelos em produção; pretende demonstrar a competência avaliativa que participa de processos orientados por feedback humano.

## 2. Relação entre preferência humana e treinamento

Em processos de RLHF, avaliações humanas podem fornecer sinais sobre quais comportamentos ou respostas são preferíveis. Em uma prática de avaliação, o papel da pessoa avaliadora é produzir julgamentos consistentes segundo critérios definidos.

A preferência deve refletir a qualidade da resposta para a tarefa, e não simplesmente gosto pessoal.

## 3. Comparação A/B

A comparação A/B apresenta duas respostas para a mesma solicitação. O avaliador analisa as duas separadamente e depois determina a preferência.

```text
Mesma instrução
      ↓
Resposta A      Resposta B
      ↓              ↓
Análise individual
      ↓              ↓
Comparação de evidências
          ↓
   Preferência final
```

## 4. Critérios

Dependendo do exercício, podem ser considerados:

- factualidade;
- relevância;
- clareza;
- completude;
- segurança;
- aderência às instruções;
- qualidade geral;
- preferência comparativa.

Os critérios devem ser definidos antes da decisão para reduzir avaliações inconsistentes.

## 5. Processo de decisão

1. Ler a solicitação.
2. Identificar requisitos explícitos e implícitos relevantes.
3. Ler as respostas integralmente.
4. Registrar evidências.
5. Avaliar cada resposta de forma independente.
6. Comparar pontos fortes e limitações.
7. Selecionar a preferência.
8. Justificar a decisão.
9. Registrar limitações ou empate quando aplicável.

## 6. O que torna uma preferência defensável

Uma preferência é defensável quando outra pessoa consegue entender quais características da resposta determinaram a decisão. Frases como "A resposta B parece melhor" são insuficientes sem explicar o motivo.

Uma justificativa adequada relaciona **critério + evidência + impacto na tarefa**.

## 7. Empates

Duas respostas podem receber pontuações equivalentes e ainda apresentar diferenças qualitativas. Se a rubrica resultar em empate, a preferência pode ser registrada separadamente, desde que sua natureza seja explicitada.

Isso evita alterar artificialmente uma pontuação apenas para produzir um vencedor.

## 8. Relação com AI Response Evaluator

A comparação de preferência desenvolve habilidades de análise crítica, julgamento consistente, identificação de diferenças sutis e documentação de decisões. Essas capacidades são diretamente relacionadas à avaliação humana de outputs de IA.

## 9. Relação com QA e Auditoria

O processo se aproxima de QA e Auditoria pela existência de critérios, evidências, decisões rastreáveis e necessidade de consistência. A preferência não deve ser arbitrária: deve ser justificável a partir das características observáveis das respostas.

## 10. Limitações

Preferências humanas podem variar entre avaliadores. Por isso, projetos reais podem utilizar guidelines, treinamento, calibração, revisão e métricas de concordância. Neste portfólio, o objetivo é demonstrar o processo de decisão e a qualidade da justificativa, não apresentar uma medição estatística de concordância entre avaliadores.

## 11. Estrutura

```text
rlhf/
├── README.md
├── exemplo-001.md
├── exemplo-002.md
├── exemplo-003.md
└── exemplo-004.md
```

## 12. Fontes de estudo

- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Fine-tuning de modelos de linguagem](https://huggingface.co/learn/llm-course/chapter11/1)
- [Microsoft Learn — Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
