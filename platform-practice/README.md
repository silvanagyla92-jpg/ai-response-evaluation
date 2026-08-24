# Platform Practice

## 1. Objetivo

A pasta **platform-practice** reúne estudos, exploração documentada e práticas relacionadas a ambientes usados no ecossistema de treinamento, avaliação e desenvolvimento de sistemas de Inteligência Artificial.

O objetivo não é apenas registrar nomes de plataformas, mas explicar **quais competências podem ser desenvolvidas em cada ambiente, quais tipos de tarefas são relevantes para AI Response Evaluation e como transformar uma atividade em evidência verificável**.

Os registros deste diretório devem distinguir claramente três situações:

- **estudo:** leitura de documentação, cursos e materiais públicos;
- **prática:** exercício realizado pela autora e documentado no projeto;
- **experiência profissional:** atividade efetivamente realizada em contexto profissional, que somente deve ser declarada quando houver evidência correspondente.

Essa distinção aumenta a precisão do portfólio e evita atribuir experiência profissional com base apenas no conhecimento de uma plataforma.

## 2. Competências desenvolvidas

A prática estruturada em diferentes ambientes pode desenvolver competências transferíveis para funções de **AI Trainer, AI Response Evaluator e Data Annotator**, entre elas:

- interpretação de instruções e guidelines;
- classificação e anotação de dados;
- avaliação de factualidade e relevância;
- comparação de respostas;
- identificação de inconsistências e erros;
- criação e aplicação de critérios de qualidade;
- elaboração de justificativas baseadas em evidências;
- revisão e controle de qualidade;
- consistência entre avaliações semelhantes;
- identificação de limitações e incertezas;
- documentação rastreável das decisões.

## 3. Relação com o projeto AI Response Evaluation

As plataformas funcionam como ambientes complementares à metodologia documentada em `evaluations/`, `response-evaluation/`, `conceitos-explicados/` e `rlhf/`.

A lógica central é:

```text
Instrução / guideline
        ↓
Compreensão da tarefa
        ↓
Análise do output
        ↓
Aplicação dos critérios
        ↓
Registro de evidências
        ↓
Decisão / anotação
        ↓
Revisão de qualidade
        ↓
Documentação final
```

Uma avaliação confiável deve separar o que foi **observado** do que foi **inferido**. Quando uma conclusão não puder ser confirmada, ela deve ser registrada como limitação ou hipótese, e não como fato.

## 4. Ambientes documentados

### 4.1 DataAnnotation

A DataAnnotation é um ambiente voltado a trabalhos relacionados à melhoria de sistemas de IA. Para este projeto, a relevância está principalmente nas competências de avaliação, classificação, revisão e aplicação consistente de critérios.

A documentação da pasta deve concentrar-se em habilidades observáveis e em materiais públicos, sem publicar tarefas privadas, instruções internas ou dados confidenciais.

### 4.2 Outlier

A Outlier apresenta atividades relacionadas ao treinamento e à melhoria de modelos de IA, incluindo tarefas como criação de prompts, elaboração de critérios de avaliação e classificação de respostas, conforme informações públicas da própria plataforma. citeturn0search2turn0search0

Para o portfólio, essas informações servem como referência sobre tipos de tarefas existentes. Elas não devem ser apresentadas automaticamente como experiência profissional da autora.

### 4.3 Hugging Face

A Hugging Face oferece um ecossistema amplo de modelos, datasets, bibliotecas e recursos educacionais. A documentação oficial de Transformers apresenta recursos para treinamento e avaliação, enquanto a biblioteca Evaluate fornece ferramentas para avaliar modelos, datasets e métricas de diferentes tarefas. citeturn0search1turn0search3turn0search8

Isso torna a plataforma particularmente relevante para compreender a relação entre **dados → processamento → modelo → inferência → avaliação**.

### 4.4 LMSYS Chatbot Arena

O LMSYS Chatbot Arena é relevante para o estudo de comparação de modelos por preferência humana. No contexto deste projeto, a prática A/B ajuda a desenvolver a capacidade de comparar respostas produzidas para uma mesma solicitação e justificar a preferência com base em critérios explícitos.

A comparação deve evitar decisões puramente subjetivas: o avaliador precisa identificar a diferença observável que sustenta a escolha.

## 5. Como documentar uma prática

Cada registro de atividade deve procurar responder:

1. Qual era o objetivo?
2. Qual instrução ou guideline foi utilizada?
3. Qual era a tarefa?
4. Quais critérios foram aplicados?
5. Qual resposta, dado ou item foi analisado?
6. Qual decisão foi tomada?
7. Qual evidência sustenta a decisão?
8. Houve ambiguidade ou limitação?
9. O item foi revisado?
10. Qual competência foi desenvolvida?

Um registro consistente permite que outra pessoa compreenda **como a decisão foi produzida**, e não apenas qual foi o resultado.

## 6. QA e Auditoria aplicados à prática

A metodologia possui relação direta com princípios de QA e auditoria:

**requisito → verificação → evidência → desvio → decisão → registro → revisão**

O objetivo é reduzir decisões arbitrárias e aumentar a rastreabilidade. Em avaliações repetitivas, também é importante verificar se o mesmo critério está sendo aplicado de forma consistente em itens equivalentes.

## 7. Avaliação A/B e preferência humana

Em uma comparação A/B, duas respostas são analisadas para uma mesma solicitação. O avaliador deve primeiro verificar cada resposta individualmente e depois comparar os resultados.

```text
Mesma instrução
      ↓
Resposta A      Resposta B
      ↓              ↓
Avaliação individual
      ↓              ↓
Comparação dos pontos relevantes
              ↓
     Preferência fundamentada
```

A preferência deve ser explicável. Uma resposta não deve ser escolhida apenas porque é mais longa, mais formal ou utiliza palavras mais sofisticadas.

## 8. Qualidade e confiabilidade dos dados

A qualidade da avaliação depende também da qualidade dos dados e das instruções utilizadas. Ambiguidade de guideline, critérios contraditórios, exemplos insuficientes ou decisões inconsistentes podem comprometer a utilidade dos registros.

Por isso, quando houver dúvida, o registro deve documentar a incerteza e indicar qual informação adicional seria necessária para uma decisão mais segura.

## 9. Confidencialidade e publicação

Não devem ser publicados:

- credenciais ou informações de acesso;
- dados pessoais de terceiros;
- informações de clientes;
- tarefas privadas;
- guidelines internos não públicos;
- conteúdo protegido que não possa ser redistribuído;
- capturas de tela com informações sensíveis.

Screenshots devem ser revisados e, quando necessário, anonimizados antes de serem adicionados ao repositório.

## 10. Fontes confiáveis

- [DataAnnotation — site oficial](https://www.dataannotation.tech/)
- [Outlier — site oficial](https://outlier.ai/)
- [Outlier — atividades de AI Training](https://outlier.ai/meet-our-experts)
- [Hugging Face — Learn](https://huggingface.co/learn)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Transformers](https://huggingface.co/docs/transformers/index)
- [Hugging Face — Training / Fine-tuning](https://huggingface.co/docs/transformers/main/training)
- [Hugging Face — Evaluate](https://huggingface.co/docs/evaluate/index)
- [LMSYS / FastChat — GitHub](https://github.com/lm-sys/FastChat)

As plataformas e suas políticas podem mudar. Informações sobre disponibilidade, requisitos, remuneração ou processos de seleção devem ser verificadas diretamente nas fontes oficiais no momento da consulta.

## 11. Estrutura

```text
platform-practice/
├── README.md
├── dataannotation/
│   └── README.md
├── outlier/
│   └── README.md
├── hugging-face/
│   └── README.md
└── lmsys-chatbot-arena/
    └── README.md
```

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
