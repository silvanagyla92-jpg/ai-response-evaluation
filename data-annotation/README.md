# Data Annotation

## 1. Objetivo

Esta seção apresenta a **anotação de dados** como atividade de preparação, organização e classificação de informações para uso em sistemas de Inteligência Artificial. O foco está na aplicação consistente de categorias, rótulos, guidelines e critérios definidos previamente.

A anotação é especialmente relevante em tarefas de treinamento e avaliação porque modelos dependem de dados e referências de qualidade para desenvolver ou medir desempenho. O curso da Hugging Face inclui conteúdos sobre conjuntos de dados, tokenização, curadoria de dados de alta qualidade e ajuste fino de modelos. [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

## 2. O que é anotação de dados

Anotar dados significa associar informações a rótulos ou atributos que representam alguma propriedade relevante para a tarefa. Dependendo do projeto, a anotação pode envolver classificação de texto, identificação de entidades, avaliação de qualidade, categorização de imagens ou comparação de respostas.

O rótulo não deve ser escolhido apenas por impressão pessoal. Ele deve seguir uma guideline que explique as categorias, exceções, prioridades e critérios de decisão.

## 3. Processo de anotação

```text
Receber guideline
      ↓
Compreender categorias
      ↓
Analisar o dado
      ↓
Identificar evidência
      ↓
Aplicar rótulo
      ↓
Revisar consistência
      ↓
Registrar decisão
```

## 4. Guidelines

Uma guideline bem construída deve reduzir ambiguidades. Deve explicar o significado de cada rótulo, apresentar limites entre categorias e indicar como lidar com casos difíceis.

Quando duas categorias parecem possíveis, o anotador deve procurar a regra de desempate prevista na guideline em vez de criar uma regra pessoal.

## 5. Consistência

A qualidade da anotação depende não apenas de acertar casos individuais, mas de manter decisões coerentes ao longo do conjunto. Consistência significa aplicar o mesmo princípio a casos equivalentes, salvo quando a guideline determinar tratamento diferente.

Em avaliações profissionais, também pode haver revisão por outra pessoa e mecanismos de controle de qualidade para identificar divergências.

## 6. Evidência

Toda decisão relevante deve ser sustentada pelo próprio dado. Em uma resposta de IA, por exemplo, o anotador pode destacar uma afirmação factual, uma instrução seguida ou uma falha observável.

A evidência deve ser suficiente para permitir auditoria posterior sem depender de interpretação que não esteja registrada.

## 7. Anotação de respostas de IA

No contexto deste projeto, a anotação pode representar características como:

- factualidade;
- relevância;
- clareza;
- completude;
- segurança;
- presença de conteúdo fabricado;
- aderência às instruções;
- preferência entre respostas;
- presença de viés ou tratamento desigual.

A escolha das categorias depende da tarefa e da guideline utilizada.

## 8. Erros comuns

### Ambiguidade de rótulo
Quando categorias possuem definições sobrepostas, decisões diferentes podem surgir para o mesmo dado.

### Excesso de interpretação
O anotador acrescenta informação que não está presente no material analisado.

### Inconsistência
Casos equivalentes recebem rótulos diferentes sem justificativa.

### Falta de evidência
A decisão é registrada sem indicar o trecho que a sustenta.

### Confusão entre fato e opinião
Uma preferência pessoal é registrada como se fosse um critério objetivo.

## 9. Relação com QA e Auditoria

A anotação estruturada compartilha princípios com QA e Auditoria: critérios definidos, evidências, rastreabilidade, controle de inconsistências e revisão. A principal diferença é que o objetivo da anotação é transformar dados não estruturados em informação categorizada de acordo com uma finalidade específica.

## 10. Competências praticadas

- Data annotation;
- classificação e categorização;
- aplicação de guidelines;
- controle de consistência;
- análise de evidências;
- revisão de qualidade;
- documentação de decisões;
- identificação de ambiguidades.

## 11. Fontes de estudo

- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Datasets](https://huggingface.co/docs/datasets/index)
- [Microsoft Learn — Azure AI](https://learn.microsoft.com/azure/ai-services/)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
