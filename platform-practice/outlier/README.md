# Outlier

## 1. Objetivo

Esta pasta organiza estudos e práticas relacionadas à plataforma **Outlier**, com foco em atividades públicas e competências ligadas à avaliação, treinamento e melhoria de sistemas de Inteligência Artificial.

A documentação deve distinguir informações públicas da plataforma de atividades efetivamente executadas. A existência de uma descrição de tarefa não comprova, por si só, experiência profissional da autora.

## 2. Contexto da plataforma

A Outlier apresenta publicamente atividades em que especialistas podem contribuir para o desenvolvimento de IA por meio de tarefas como criação de prompts, elaboração de critérios de avaliação e classificação ou ranqueamento de respostas. citeturn0search2turn0search0

A plataforma também descreve tarefas de avaliação de factualidade e relevância em determinados domínios. citeturn0search6turn0search10

Essas informações são utilizadas aqui como **referência de domínio e estudo**. Projetos e tarefas podem variar de acordo com área, localização, perfil e período.

## 3. Tipos de competência relacionados

### Avaliação de respostas

Verificar se uma resposta atende à solicitação, apresenta informações corretas, permanece relevante e respeita critérios definidos.

### Criação de prompts

Elaborar instruções que permitam testar capacidades ou limitações de um modelo. O prompt deve ter objetivo claro e permitir avaliação do resultado.

### Construção de rubricas

Transformar requisitos de qualidade em critérios observáveis. Uma rubrica útil deve reduzir ambiguidades e permitir decisões consistentes.

### Ranking

Comparar respostas produzidas para uma tarefa equivalente e estabelecer uma preferência fundamentada nos critérios da atividade.

## 4. Processo de avaliação

```text
Solicitação
     ↓
Critérios / rubrica
     ↓
Resposta do modelo
     ↓
Verificação
     ↓
Evidências
     ↓
Pontuação / ranking
     ↓
Justificativa
     ↓
Revisão
```

A decisão deve ser sustentada por características observáveis do output. Preferências pessoais de estilo não devem substituir critérios objetivos quando estes estiverem definidos.

## 5. Modelo de registro para o portfólio

| Campo | Pergunta orientadora |
|---|---|
| Contexto | O que estava sendo avaliado? |
| Solicitação | Qual era a instrução? |
| Critérios | Quais requisitos determinavam qualidade? |
| Evidência | O que foi observado na resposta? |
| Decisão | Qual nota, rótulo ou ranking foi atribuído? |
| Justificativa | Por que essa decisão foi tomada? |
| Incerteza | O que não pôde ser confirmado? |
| Revisão | A decisão foi conferida? |
| Competência | Qual habilidade foi demonstrada? |

## 6. Relação com AI Response Evaluation

As práticas descritas nesta pasta complementam as avaliações individuais em `evaluations/`. O princípio central é transformar uma resposta de IA em um objeto avaliável por meio de requisitos, critérios, evidências e decisões documentadas.

Uma boa avaliação deve evitar confundir:

- erro factual com estilo;
- ausência de informação com informação falsa;
- descumprimento de instrução com preferência pessoal;
- simplificação didática com alucinação sem evidência.

## 7. Relação com QA e Auditoria

O fluxo apresenta forte relação metodológica com QA:

**requisito → teste/verificação → evidência → identificação do desvio → decisão → registro**

Em auditoria, a mesma lógica ajuda a preservar rastreabilidade e fundamentação, embora uma atividade de avaliação de resposta não seja equivalente a uma auditoria formal.

## 8. Limitações e cautelas

A plataforma e seus projetos podem mudar. Por isso, informações sobre oportunidades, requisitos, disponibilidade, remuneração ou processos seletivos devem ser consultadas diretamente nas fontes oficiais no momento da utilização.

Este repositório não deve publicar tarefas privadas, dados de clientes, credenciais, informações pessoais ou materiais internos não autorizados.

## 9. Fontes confiáveis

- [Outlier — site oficial](https://outlier.ai/)
- [Outlier — Meet the Experts](https://outlier.ai/meet-our-experts)
- [Outlier — What Experts Do](https://outlier.ai/blog/so-what-do-outlier-experts-actually-do)
- [Outlier — AI / Machine Learning Experts](https://outlier.ai/experts/ml)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Evaluate](https://huggingface.co/docs/evaluate/index)

## 10. Competências relacionadas ao portfólio

- AI Trainer;
- AI Response Evaluator;
- Prompt Engineering;
- construção e aplicação de rubricas;
- ranking de respostas;
- análise crítica;
- Data Annotation;
- QA e Auditoria;
- documentação baseada em evidências.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
