# LMSYS Chatbot Arena

## 1. Objetivo

Esta pasta documenta estudos e práticas relacionados ao **LMSYS Chatbot Arena**, ambiente de comparação de modelos de linguagem por meio de avaliações humanas.

A prática é relevante para este projeto porque a comparação A/B exige que a pessoa avaliadora observe duas respostas para uma tarefa equivalente, identifique diferenças e registre uma preferência fundamentada.

## 2. Comparação de respostas

O processo pode ser representado como:

```text
Mesma solicitação
      ↓
Resposta A   ↔   Resposta B
      ↓              ↓
Qualidade individual
      ↓              ↓
Comparação
      ↓
Preferência fundamentada
```

A preferência deve considerar critérios relevantes para a tarefa, e não apenas estilo pessoal.

## 3. Aspectos avaliáveis

- factualidade;
- relevância;
- clareza;
- completude;
- segurança;
- aderência à instrução;
- qualidade geral.

Quando dois outputs forem muito próximos, a justificativa deve apontar a diferença efetivamente observada.

## 4. Relação com RLHF

A avaliação humana de preferência pode fornecer sinais úteis em processos de desenvolvimento e alinhamento de modelos. Neste projeto, a prática é tratada como exercício de avaliação comparativa e não como reprodução de todo o pipeline de treinamento de um modelo.

## 5. Boas práticas

- Ler a instrução antes das respostas.
- Avaliar cada resposta individualmente.
- Evitar preferência baseada apenas em comprimento.
- Identificar erros factuais.
- Verificar cumprimento de restrições.
- Registrar evidências.
- Justificar a escolha final.

## 6. Fontes

- [LMSYS Chatbot Arena](https://chat.lmsys.org/)
- [LMSYS Org no GitHub](https://github.com/lm-sys)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
