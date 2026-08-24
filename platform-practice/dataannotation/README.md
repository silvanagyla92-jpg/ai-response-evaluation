# DataAnnotation

## 1. Objetivo

Esta pasta documenta estudos e práticas relacionados à **DataAnnotation**, com foco em anotação, classificação, avaliação de respostas e aplicação consistente de critérios.

O registro deve diferenciar claramente **informação pública sobre a plataforma**, **estudo independente**, **prática realizada** e **experiência profissional**. Uma descrição pública da plataforma não deve ser apresentada como comprovação de atividade profissional.

## 2. O que é anotação de dados

Anotação de dados consiste em associar rótulos, categorias, atributos ou julgamentos estruturados a dados segundo regras definidas. Dependendo da tarefa, os dados anotados podem apoiar treinamento, avaliação ou análise de sistemas de IA.

A qualidade da anotação depende de critérios claros, consistência entre avaliadores, tratamento adequado de casos ambíguos e revisão das decisões.

## 3. Tipos de atividades relacionadas

Dependendo do projeto e do guideline, tarefas de anotação e avaliação podem envolver:

- classificação de textos;
- categorização de conteúdo;
- comparação de respostas;
- avaliação de factualidade;
- verificação de aderência a instruções;
- identificação de características específicas;
- atribuição de notas ou rótulos;
- registro de justificativas;
- revisão de anotações.

A lista representa tipos de atividade comuns no domínio, e não uma afirmação de que todas foram executadas pela autora.

## 4. Fluxo de trabalho recomendado

```text
Guideline / instrução
        ↓
Leitura do item
        ↓
Identificação dos critérios
        ↓
Análise da evidência
        ↓
Aplicação do rótulo / julgamento
        ↓
Revisão da decisão
        ↓
Registro
```

O avaliador deve consultar primeiro a regra da tarefa e só depois decidir. Quando o guideline não for suficiente, a incerteza deve ser registrada em vez de ser substituída por uma regra inventada.

## 5. Evidência e rastreabilidade

Uma anotação de qualidade deve permitir reconstruir a lógica da decisão. Para exercícios públicos, uma estrutura útil é:

| Campo | Descrição |
|---|---|
| Item | Conteúdo analisado |
| Critério | Regra aplicada |
| Evidência | Elemento observável que sustenta a decisão |
| Decisão | Rótulo, nota ou preferência |
| Justificativa | Explicação objetiva |
| Incerteza | Ambiguidade ou limitação |
| Revisão | Resultado da conferência |

A evidência deve ser suficiente para sustentar a decisão, sem extrapolar o que o item realmente demonstra.

## 6. Consistência entre avaliações

Consistência significa aplicar o mesmo critério a situações equivalentes, salvo quando o próprio guideline estabelecer uma diferença.

Para manter consistência:

1. interpretar a instrução antes da classificação;
2. definir o critério aplicável;
3. procurar evidências no item;
4. evitar critérios subjetivos não previstos;
5. revisar casos limítrofes;
6. comparar decisões semelhantes quando isso fizer parte do processo de qualidade.

## 7. Relação com AI Response Evaluation

A anotação é complementar à avaliação de respostas. Em uma avaliação estruturada, o resultado pode ser representado como:

```text
Resposta observada
       ↓
Critério
       ↓
Evidência
       ↓
Análise
       ↓
Rótulo / pontuação
       ↓
Justificativa
```

Essa estrutura é especialmente útil para o portfólio porque demonstra não apenas o resultado, mas o raciocínio avaliativo documentado.

## 8. Relação com QA e Auditoria

A metodologia apresenta práticas transferíveis de QA e Auditoria: aplicação de requisitos, identificação de desvios, evidência rastreável, revisão e registro de decisões.

Entretanto, anotação de dados e auditoria não são atividades idênticas. A primeira normalmente produz rótulos ou julgamentos estruturados; a segunda pode examinar processos, controles e conformidade em escopo mais amplo.

## 9. Privacidade e propriedade do conteúdo

Não devem ser publicados neste diretório:

- dados pessoais de terceiros;
- credenciais ou informações de acesso;
- tarefas privadas;
- informações de clientes;
- guidelines internos não públicos;
- conteúdo protegido sem autorização de redistribuição;
- screenshots contendo informações sensíveis.

Materiais utilizados para demonstrar competências devem ser públicos, autorizados ou criados especificamente para o portfólio.

## 10. Fontes confiáveis

- [DataAnnotation — site oficial](https://www.dataannotation.tech/)
- [Hugging Face — Datasets](https://huggingface.co/docs/datasets/index)
- [Hugging Face — Evaluate](https://huggingface.co/docs/evaluate/index)
- [NIST — AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)
- [NIST — AI RMF Playbook](https://airc.nist.gov/airmf-resources/playbook/)

As fontes oficiais devem ser consultadas novamente quando uma informação depender de regras ou características operacionais atuais da plataforma.

## 11. Competências relacionadas

- Data Annotation;
- AI Response Evaluation;
- aplicação de guidelines;
- classificação e categorização;
- análise crítica;
- registro de evidências;
- consistência de decisões;
- controle de qualidade;
- QA e Auditoria.

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
