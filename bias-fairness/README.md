# Bias & Fairness

## 1. Objetivo

Esta seção aborda **viés, fairness, equidade e riscos associados a sistemas de Inteligência Artificial**. O objetivo é desenvolver capacidade para identificar padrões de tratamento desigual, estereótipos, generalizações indevidas e diferenças de desempenho entre grupos ou contextos.

A existência de um modelo estatístico não elimina automaticamente vieses. Dados históricos podem refletir desigualdades, erros de coleta, critérios de seleção e decisões humanas anteriores. A IBM destaca que conjuntos de dados de validação e treinamento podem incorporar vieses e erros humanos e que o contexto de implantação também pode produzir consequências não intencionais. [IBM — Tipos de aprendizado de máquina](https://www.ibm.com/br-pt/think/topics/machine-learning-types)

## 2. Conceitos fundamentais

### Viés

Viés é uma tendência sistemática que pode produzir resultados inadequados ou injustos. Na avaliação de IA, é necessário identificar de onde o viés pode surgir: dados, definição da tarefa, rótulos, métricas, modelo, interface ou contexto de uso.

### Fairness

Fairness pode ser entendida como o tratamento justo de pessoas ou grupos segundo critérios adequados ao contexto. Não existe uma única métrica universal de fairness que resolva todos os cenários.

### Equidade

Equidade considera diferenças relevantes entre pessoas ou grupos para evitar que uma aplicação aparentemente uniforme produza consequências desiguais.

## 3. Fontes de viés

```text
Dados históricos
      ↓
Coleta e seleção
      ↓
Rotulagem
      ↓
Treinamento
      ↓
Modelo
      ↓
Implantação
      ↓
Impacto observado
```

Um problema pode aparecer em qualquer etapa. Por isso, corrigir apenas o modelo pode não resolver a causa original.

## 4. Como avaliar uma resposta

Ao analisar uma resposta de IA, o avaliador deve perguntar:

1. Há generalização sobre um grupo?
2. A afirmação apresenta evidência suficiente?
3. Pessoas diferentes são tratadas de forma desigual sem justificativa?
4. Existe estereótipo ou associação indevida?
5. O contexto foi considerado?
6. A resposta poderia produzir dano ou discriminação se aplicada literalmente?

## 5. Fato, viés e alucinação

Esses conceitos não são equivalentes. Uma afirmação pode ser factual, mas enviesada na seleção do contexto. Pode também ser falsa sem apresentar viés de grupo. E uma resposta pode conter uma alucinação sem envolver fairness.

A avaliação deve identificar qual problema está efetivamente presente, evitando atribuir rótulos apenas porque uma resposta parece inadequada.

## 6. Mitigação

Estratégias podem incluir melhoria da qualidade e diversidade dos dados, revisão das guidelines de anotação, testes por grupos relevantes, avaliação humana, monitoramento pós-implantação e mecanismos de governança.

Nenhuma técnica isolada garante ausência de viés. A mitigação deve ser adequada ao risco e ao contexto.

## 7. Relação com QA e Auditoria

A análise de fairness exige critérios definidos, amostras representativas, evidências e documentação. Essas características se aproximam de processos de QA e Auditoria porque permitem identificar desvios, registrar não conformidades e acompanhar ações corretivas.

## 8. Competências demonstradas

- identificação de vieses;
- análise crítica de respostas;
- avaliação de fairness;
- análise de riscos;
- verificação baseada em evidências;
- documentação de não conformidades;
- pensamento crítico sobre dados e modelos.

## 9. Fontes de estudo

- [IBM — Tipos de aprendizado de máquina](https://www.ibm.com/br-pt/think/topics/machine-learning-types)
- [IBM — Guia de Inteligência Artificial](https://www.ibm.com/think/topics/ai-guide)
- [Microsoft Responsible AI](https://www.microsoft.com/ai/responsible-ai)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
