# Prompt Engineering

## 1. Objetivo

Esta seção reúne práticas de **engenharia de prompts** aplicadas ao desenvolvimento e à avaliação de instruções para sistemas de Inteligência Artificial. O objetivo é demonstrar como uma solicitação pode ser estruturada para reduzir ambiguidades, definir contexto, estabelecer restrições e orientar o formato da saída.

A engenharia de prompts não deve ser tratada como uma fórmula universal. O comportamento varia conforme o modelo, a tarefa, o contexto e a configuração utilizada. A documentação atual da Microsoft destaca que prompts claros, contexto adequado, divisão de tarefas e especificação de saída podem ajudar, mas exigem testes e iteração. [Microsoft Learn — Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)

## 2. Estrutura de um bom prompt

Um prompt pode combinar diferentes elementos:

- **Objetivo:** o que deve ser realizado.
- **Contexto:** informações necessárias para interpretar a tarefa.
- **Papel ou perspectiva:** quando realmente contribuir para a tarefa.
- **Restrições:** limites de conteúdo, extensão, idioma ou formato.
- **Critérios de qualidade:** condições que a resposta precisa satisfazer.
- **Formato de saída:** estrutura esperada para facilitar leitura ou processamento.

Quanto mais importante for uma restrição, mais explicitamente ela deve ser formulada.

## 3. Clareza e especificidade

Instruções vagas aumentam a margem de interpretação. Uma formulação mais específica pode indicar público-alvo, objetivo, quantidade de itens, tom, idioma e formato.

Entretanto, especificidade excessiva também pode gerar conflito entre regras. O prompt deve ser suficientemente detalhado para orientar o modelo, mas organizado de forma que as instruções não se contradigam.

## 4. Decomposição de tarefas

Problemas complexos podem ser divididos em etapas menores. A decomposição facilita a verificação porque cada parte pode receber requisitos próprios.

Exemplo de estrutura conceitual:

```text
Tarefa complexa
    ↓
Identificar requisitos
    ↓
Produzir conteúdo
    ↓
Verificar restrições
    ↓
Formatar saída
    ↓
Revisar resultado
```

## 5. Saída estruturada

Quando a resposta será avaliada ou utilizada por outro sistema, definir a estrutura esperada pode aumentar a consistência. Formatos como tabelas, campos fixos ou estruturas de dados podem facilitar validação posterior.

A Microsoft recomenda contratos de saída pequenos e estáveis quando uma aplicação necessita de estrutura previsível. [Microsoft Learn — Design de mensagens do sistema](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/advanced-prompt-engineering)

## 6. Contexto e grounding

Fornecer contexto relevante ajuda o modelo a trabalhar com informações específicas da tarefa. Em aplicações baseadas em documentos, esse contexto pode ser obtido por mecanismos de recuperação, como RAG.

É importante não confundir um prompt com uma fonte de verdade. Uma instrução pode orientar o comportamento, mas não garante que todas as afirmações produzidas estarão corretas.

## 7. Teste e refinamento

O processo recomendado é iterativo:

1. Definir o objetivo.
2. Criar uma primeira versão.
3. Executar o prompt.
4. Avaliar a resposta.
5. Identificar falhas.
6. Alterar uma variável por vez quando possível.
7. Reexecutar.
8. Registrar o resultado.

Esse processo transforma engenharia de prompts em uma prática verificável, e não apenas em tentativa e erro informal.

## 8. Avaliação de prompts

Os prompts deste projeto podem ser avaliados por critérios como:

| Aspecto | Pergunta de verificação |
|---|---|
| Clareza | O modelo consegue identificar a tarefa sem interpretação excessiva? |
| Completude | Todos os requisitos necessários foram informados? |
| Consistência | Existem instruções conflitantes? |
| Controle de saída | O formato solicitado é suficientemente explícito? |
| Relevância | O contexto fornecido ajuda realmente na tarefa? |
| Robustez | Pequenas mudanças na entrada provocam falhas inesperadas? |
| Segurança | O prompt estabelece limites adequados para o cenário? |

## 9. Relação com AI Response Evaluator

Uma pessoa que avalia respostas precisa compreender como a instrução condiciona a saída. Uma resposta aparentemente incompleta pode, por exemplo, estar correta quando a solicitação limitava a extensão. Por isso, o avaliador deve sempre comparar a resposta com o prompt original.

A documentação do projeto registra essa relação entre **instrução → resposta → evidência → avaliação**.

## 10. Competências demonstradas

- Prompt design;
- Prompt refinement;
- Instruction following;
- Avaliação de aderência;
- Análise de qualidade de saída;
- Identificação de ambiguidades;
- Estruturação de requisitos;
- Teste comparativo;
- Documentação de resultados.

## 11. Fontes de estudo

- [Microsoft Learn — Técnicas de engenharia de prompt](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/prompt-engineering)
- [Microsoft Learn — Design de mensagens do sistema](https://learn.microsoft.com/pt-br/azure/foundry/openai/concepts/advanced-prompt-engineering)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
