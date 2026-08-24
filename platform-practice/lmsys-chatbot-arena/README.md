# LMSYS Chatbot Arena

## 1. Objetivo

Esta pasta documenta estudos e práticas relacionados ao **LMSYS Chatbot Arena**, com foco em comparação de modelos de linguagem, avaliação humana, preferência pareada e análise crítica de respostas.

O ambiente é especialmente relevante para o projeto porque uma avaliação lado a lado exige que o avaliador compare respostas produzidas para uma tarefa equivalente e justifique a decisão com base em características observáveis.

## 2. O que é o Chatbot Arena

O projeto FastChat, mantido pela organização LMSYS, documenta o Chatbot Arena como um ambiente de benchmark em que modelos são comparados por meio de batalhas anônimas e randomizadas. citeturn0search1turn0search7

Para este portfólio, o principal aprendizado não é reproduzir toda a infraestrutura da Arena, mas compreender a lógica de **avaliação comparativa por preferência humana**.

## 3. Estrutura de uma comparação A/B

```text
Mesma solicitação
       ↓
Resposta A       Resposta B
       ↓              ↓
Avaliação individual
       ↓              ↓
Aplicação dos critérios
       ↓              ↓
Comparação das evidências
       ↓
Preferência / empate
       ↓
Justificativa
```

O avaliador deve analisar as respostas individualmente antes de decidir qual é superior. Isso reduz o risco de escolher uma resposta apenas por impressão inicial.

## 4. Critérios de avaliação

Dependendo da tarefa, podem ser analisados:

- aderência à instrução;
- factualidade;
- relevância;
- clareza;
- completude;
- segurança;
- qualidade geral;
- consistência;
- ausência de informações fabricadas.

Os critérios precisam ser definidos pelo contexto da avaliação. Uma característica considerada importante em uma tarefa pode ser irrelevante em outra.

## 5. Imparcialidade

Uma comparação confiável deve reduzir fatores que não representam qualidade real. Entre eles estão a ordem das respostas, o comprimento, o estilo pessoal do avaliador e o conhecimento prévio sobre o modelo.

A documentação do FastChat inclui materiais específicos para avaliação pareada e discussão de fatores que podem afetar julgamentos. citeturn0search6

Uma boa justificativa deve responder: **qual diferença observável entre A e B sustenta a preferência?**

Se as duas respostas forem equivalentes diante dos critérios, o empate é uma decisão válida.

## 6. Preferência humana e RLHF

Preferências humanas podem fornecer sinais utilizados em processos de treinamento e alinhamento de modelos. O repositório FastChat também disponibiliza ferramentas e dados relacionados a julgamentos de modelos. citeturn0search0turn0search8

Entretanto, uma avaliação A/B feita neste projeto **não deve ser descrita como RLHF completo**. Ela representa uma prática de avaliação comparativa e preferência humana que pode ajudar a compreender uma etapa desse ecossistema.

## 7. LLM-as-a-Judge e avaliação humana

A comparação humana pode ser complementada por métodos automáticos ou por modelos avaliadores. Esses métodos precisam ser interpretados com cautela, pois um avaliador automático também pode apresentar vieses ou falhas.

Neste portfólio, quando a avaliação é realizada pela autora, a decisão deve ser identificada explicitamente como **avaliação humana**.

## 8. Modelo de registro

| Campo | Descrição |
|---|---|
| Solicitação | Tarefa apresentada aos modelos |
| Resposta A | Output analisado |
| Resposta B | Output analisado |
| Critérios | Dimensões utilizadas |
| Evidência A | Ponto relevante da resposta A |
| Evidência B | Ponto relevante da resposta B |
| Preferência | A, B ou empate |
| Justificativa | Razão baseada nos critérios |
| Limitações | Incertezas ou fatores não confirmados |

## 9. Relação com AI Response Evaluation

A metodologia do Chatbot Arena complementa as avaliações individuais do diretório `evaluations/`.

Enquanto uma avaliação individual pergunta **“a resposta atende aos critérios?”**, uma comparação A/B acrescenta a pergunta **“qual das duas respostas atende melhor aos critérios?”**.

Essa distinção é importante para não transformar preferência relativa em afirmação absoluta de qualidade.

## 10. Relação com QA e Auditoria

A comparação A/B possui uma lógica compatível com QA:

**requisito → inspeção → evidência → comparação → decisão → registro**

Em auditoria, a documentação da evidência também é importante para permitir revisão posterior. Entretanto, avaliação de respostas e auditoria formal permanecem atividades distintas.

## 11. Fontes confiáveis

- [LMSYS / FastChat — repositório oficial](https://github.com/lm-sys/FastChat)
- [FastChat — Chatbot Arena](https://github.com/lm-sys/FastChat/blob/main/docs/arena.md)
- [FastChat — LLM Judge](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge)
- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

Informações sobre ranking, número de modelos, participação ou funcionamento operacional podem mudar. Para dados atuais, deve-se consultar a documentação oficial vigente.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
