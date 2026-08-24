# LMSYS Chatbot Arena

## 1. Objetivo

Esta pasta documenta estudos e práticas relacionados ao **LMSYS Chatbot Arena**, ambiente de comparação de modelos de linguagem por meio de avaliações humanas.

A prática é relevante para o projeto porque a comparação lado a lado permite exercitar **preferência humana, avaliação comparativa, análise de instruções e justificativa baseada em evidências**.

## 2. Como funciona a comparação

A lógica básica de uma avaliação pareada pode ser representada assim:

```text
Mesma solicitação
       ↓
Resposta A  ↔  Resposta B
       ↓           ↓
Avaliação individual
       ↓           ↓
Comparação dos critérios
       ↓
Preferência / empate
       ↓
Justificativa baseada em evidências
```

A documentação do FastChat descreve o Chatbot Arena como uma plataforma de benchmark com batalhas anônimas e randomizadas entre modelos. citeturn0search1turn0search7

## 3. Critérios que podem ser analisados

Dependendo da tarefa, a avaliação pode considerar:

- aderência à instrução;
- factualidade;
- relevância;
- clareza;
- completude;
- segurança;
- qualidade geral;
- profundidade adequada ao pedido;
- presença de erros ou informações não sustentadas.

O critério deve ser definido antes da decisão sempre que a atividade possuir uma rubrica específica.

## 4. Imparcialidade na comparação

Uma avaliação comparativa deve evitar vieses relacionados ao nome do modelo, ordem de apresentação, comprimento da resposta ou preferência estilística. Os materiais de avaliação do FastChat incluem instruções explícitas para comparação pareada, imparcialidade e prevenção de posição ou comprimento como fatores indevidos. citeturn0search6

Quando duas respostas forem próximas, a justificativa deve apontar a diferença concreta que sustenta a preferência. Se não houver diferença relevante, o empate pode ser a decisão mais adequada.

## 5. Relação com RLHF e preferência humana

Avaliações humanas de preferência podem produzir sinais úteis para desenvolvimento e alinhamento de modelos. Entretanto, uma comparação A/B realizada neste portfólio **não representa, isoladamente, um pipeline completo de RLHF**.

O repositório FastChat também disponibiliza dados de julgamentos humanos e ferramentas para estudar concordância entre avaliadores. citeturn0search0turn0search8

## 6. Boas práticas para os exercícios

1. Ler a instrução antes de observar as respostas.
2. Avaliar cada resposta individualmente.
3. Verificar os requisitos explícitos.
4. Separar qualidade técnica de preferência pessoal.
5. Não premiar automaticamente respostas mais longas.
6. Procurar erros factuais ou violações de segurança.
7. Registrar evidências suficientes para sustentar a decisão.
8. Explicar por que uma resposta é superior ou por que existe empate.

## 7. Relação com AI Response Evaluator

A atividade desenvolve competências diretamente relacionadas à avaliação de respostas: interpretação de critérios, comparação sistemática, identificação de diferenças relevantes, tomada de decisão e documentação de justificativas.

## 8. Fontes confiáveis

- [LMSYS / FastChat — repositório oficial](https://github.com/lm-sys/FastChat)
- [FastChat — documentação do Chatbot Arena](https://github.com/lm-sys/FastChat/blob/main/docs/arena.md)
- [FastChat — LLM Judge](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

As características da plataforma e seus números de participação podem mudar. Informações quantitativas devem ser verificadas na fonte oficial e na versão atual da documentação.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
