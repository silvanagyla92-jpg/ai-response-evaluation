# Avaliação 012 — Aderência à Instrução

## 1. Introdução

Esta avaliação foi desenvolvida para analisar a capacidade de um modelo de Inteligência Artificial de **seguir instruções específicas de conteúdo e formato**.

O exercício utiliza uma solicitação com múltiplas restrições simultâneas, incluindo quantidade exata de frases, ausência de listas e tópicos, ausência de exemplos e uma exigência específica para o conteúdo da última frase.

O objetivo é verificar não apenas se a resposta apresenta informações corretas, mas também se ela **cumpre integralmente as instruções fornecidas pelo usuário**.

Essa competência é relevante em processos de avaliação de respostas de IA porque uma resposta pode ser factual e clara, mas ainda assim ser considerada inadequada caso não siga as restrições estabelecidas na solicitação.

---

## 2. Plataforma utilizada

**Plataforma:** Claude

**Finalidade:** Geração da resposta utilizada como objeto de avaliação durante este exercício prático.

**Fonte da resposta:** Resposta gerada pelo Claude para a pergunta proposta na Avaliação 012.

**Observação:** A resposta foi utilizada exclusivamente como objeto de análise neste projeto demonstrativo. A avaliação foi realizada pela autora utilizando a rubrica definida no projeto.

---

## 3. Pergunta do usuário

> Explique o que é RAG (Retrieval-Augmented Generation) em exatamente 3 frases. Não utilize listas, tópicos ou exemplos. Na última frase, mencione uma vantagem do RAG em relação ao uso isolado de um LLM.

---

## 4. Resposta avaliada

> RAG (Retrieval-Augmented Generation) é uma técnica que combina um modelo de linguagem com um sistema de busca em uma base de dados externa, recuperando informações relevantes antes de gerar uma resposta.
>
> Esse processo ocorre em três etapas: o sistema busca trechos relevantes em documentos externos, insere esses trechos como contexto junto à pergunta original e então o modelo gera a resposta com base nesse contexto ampliado.
>
> Em relação ao uso isolado de um LLM, essa abordagem reduz significativamente o risco de alucinações, já que a resposta é ancorada em fontes reais e verificáveis, em vez de depender apenas do conhecimento estático adquirido durante o treinamento.

---

## 5. Critérios de avaliação

| Critério         | Pontuação | Avaliação                                                                                                                                                                                                            |
| ---------------- | --------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Factualidade** |   **2/2** | A resposta apresenta uma explicação adequada sobre RAG e seu funcionamento geral. A afirmação sobre redução do risco de alucinações é plausível, embora possa ser qualificada para evitar interpretação de garantia. |
| **Relevância**   |   **2/2** | A resposta permanece diretamente relacionada à solicitação e aborda os elementos exigidos.                                                                                                                           |
| **Clareza**      |   **2/2** | A resposta utiliza linguagem objetiva e apresenta o conceito de maneira compreensível.                                                                                                                               |
| **Completude**   |   **2/2** | A resposta atende aos requisitos de conteúdo e formato estabelecidos na pergunta.                                                                                                                                    |
| **Segurança**    |   **2/2** | Não foram identificados conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.                                                                                                     |
| **Alucinação**   |   **2/2** | Não foram identificadas informações claramente inventadas ou afirmações sem fundamento aparente dentro do conteúdo avaliado.                                                                                         |

---

## 6. Escala de pontuação

A avaliação utiliza uma escala de **0 a 2 pontos por critério**.

* **0 — Inadequado:** apresenta problema significativo no critério avaliado.
* **1 — Parcialmente adequado:** apresenta características positivas, mas possui limitações relevantes.
* **2 — Adequado:** atende satisfatoriamente ao critério avaliado.

A pontuação máxima possível nesta avaliação é de **12 pontos**.

---

## 7. Escala de classificação

A classificação geral utilizada no projeto é:

* **0 a 4 pontos — Inadequada**
* **5 a 8 pontos — Parcialmente adequada**
* **9 a 10 pontos — Adequada**
* **11 a 12 pontos — Excelente**

A classificação considera a pontuação total obtida nos seis critérios avaliados.

---

## 8. Resultado

**Pontuação total: 12/12**

**Classificação: Excelente**

**Aderência à instrução: Totalmente adequada**

A resposta cumpriu as principais restrições apresentadas na solicitação, incluindo a quantidade exata de frases, a ausência de listas, a ausência de tópicos, a ausência de exemplos e a apresentação de uma vantagem na última frase.

---

## 9. Justificativa

A resposta apresentou excelente desempenho na avaliação de aderência à instrução.

A solicitação estabelecia várias restrições simultâneas, e a resposta conseguiu atendê-las sem introduzir elementos que contrariassem diretamente o formato solicitado.

A resposta:

* apresenta uma definição de RAG;
* utiliza exatamente três frases;
* não utiliza listas;
* não utiliza tópicos;
* não apresenta exemplos;
* apresenta uma vantagem do RAG em relação ao uso isolado de um LLM na última frase.

A estrutura demonstra capacidade de seguir instruções específicas mesmo quando existem múltiplas restrições de formato.

A única observação técnica está relacionada à formulação de que o RAG **“reduz significativamente o risco de alucinações”** e de que a resposta estaria “ancorada em fontes reais e verificáveis”. Essa formulação poderia ser mais cuidadosamente qualificada, pois o uso de recuperação de informações não garante, por si só, que as informações recuperadas sejam corretas nem elimina a possibilidade de uma resposta incorreta.

Essa observação, entretanto, não compromete a aderência estrutural à instrução nem foi considerada suficiente para reduzir a pontuação geral.

---

## 10. Pontos fortes

### 10.1. Cumprimento da quantidade de frases

A resposta apresenta exatamente **três frases**, conforme solicitado.

Cada frase possui uma função clara:

1. definição de RAG;
2. explicação simplificada do funcionamento;
3. apresentação de uma vantagem em relação ao uso isolado de um LLM.

### 10.2. Cumprimento das restrições de formato

A resposta não utiliza:

* listas;
* marcadores;
* tópicos;
* exemplos.

Isso demonstra boa aderência às restrições explícitas da solicitação.

### 10.3. Atendimento da instrução sobre a última frase

A terceira frase apresenta explicitamente uma comparação entre RAG e o uso isolado de um LLM.

Dessa forma, a exigência relacionada ao conteúdo da última frase foi atendida.

### 10.4. Organização da informação

Mesmo com a limitação de exatamente três frases, a resposta distribui adequadamente as informações entre definição, funcionamento e vantagem.

---

## 11. Limitações

Embora a resposta tenha atendido integralmente às instruções estruturais, existe uma pequena oportunidade de melhoria relacionada à **precisão da formulação técnica**.

A afirmação:

> “essa abordagem reduz significativamente o risco de alucinações”

pode ser interpretada como uma afirmação ampla.

O RAG pode ajudar a reduzir determinados tipos de respostas incorretas ao fornecer contexto externo ao modelo, mas não elimina o risco de alucinação e não garante que a informação recuperada ou a resposta gerada esteja correta.

Da mesma forma, a expressão:

> “a resposta é ancorada em fontes reais e verificáveis”

pode ser considerada uma simplificação, pois a existência de uma fonte recuperada não significa automaticamente que ela seja correta, atual ou suficientemente verificável.

Esses pontos representam **oportunidades de melhoria na precisão técnica**, e não falhas relevantes de aderência à instrução.

---

## 12. Análise detalhada

### 12.1. A resposta explicou o que é RAG?

**Resultado: Atendido.**

A primeira frase define RAG como uma técnica que combina um modelo de linguagem com um sistema de busca em uma base de dados externa.

A definição é adequada para uma explicação introdutória.

### 12.2. A resposta utilizou exatamente três frases?

**Resultado: Atendido.**

A resposta apresenta exatamente três frases.

A exigência quantitativa foi cumprida.

### 12.3. A resposta utilizou listas?

**Resultado: Atendido.**

Não foram utilizadas listas estruturadas.

A segunda frase menciona três etapas do processo, mas apresenta essas informações de forma contínua dentro de uma única frase.

Portanto, a menção às três etapas não caracteriza uma lista.

### 12.4. A resposta utilizou tópicos?

**Resultado: Atendido.**

A resposta não apresenta títulos, marcadores ou tópicos internos.

O conteúdo foi apresentado em formato textual contínuo.

### 12.5. A resposta apresentou exemplos?

**Resultado: Atendido.**

A resposta não apresenta exemplos de aplicações ou situações específicas de utilização do RAG.

Essa restrição foi respeitada.

### 12.6. A última frase apresentou uma vantagem do RAG?

**Resultado: Atendido.**

A terceira frase estabelece explicitamente uma comparação com o uso isolado de um LLM e apresenta como vantagem a redução do risco de determinadas alucinações.

Portanto, o requisito específico para a última frase foi atendido.

### 12.7. Houve violação relevante da instrução?

**Resultado: Não identificada.**

Não foram identificadas violações relevantes das restrições estabelecidas na pergunta.

A resposta demonstrou aderência tanto ao conteúdo solicitado quanto ao formato exigido.

### 12.8. Existe alguma oportunidade de melhoria?

**Resultado: Sim, de baixa gravidade.**

A principal oportunidade de melhoria está na qualificação da afirmação relacionada à redução de alucinações.

Essa questão está relacionada à **precisão técnica**, e não ao cumprimento das instruções de formato.

---

## 13. Observação da avaliadora

Durante a avaliação, foi considerado o conteúdo efetivamente apresentado na resposta e sua aderência às instruções explícitas da pergunta.

A análise foi realizada individualmente para cada requisito, verificando quantidade de frases, presença de listas ou tópicos, existência de exemplos e atendimento da exigência relacionada à última frase.

Também foi considerada a diferença entre **cumprimento de instrução** e **qualidade técnica da formulação**.

A resposta pode cumprir integralmente uma instrução e ainda apresentar pequenas oportunidades de melhoria em sua precisão ou qualificação de determinadas afirmações.

Neste caso, a resposta foi considerada integralmente aderente às instruções, com uma pequena observação técnica sobre a forma como o benefício do RAG em relação às alucinações foi apresentado.

---

## 14. Processo de avaliação

O processo foi realizado em etapas:

1. Identificação das instruções explícitas presentes na pergunta;
2. Separação das restrições de conteúdo e de formato;
3. Verificação da quantidade de frases;
4. Verificação da presença ou ausência de listas;
5. Verificação da presença ou ausência de tópicos;
6. Verificação da presença ou ausência de exemplos;
7. Verificação do conteúdo exigido na última frase;
8. Avaliação dos critérios gerais de qualidade;
9. Identificação de possíveis limitações técnicas;
10. Classificação final da resposta.

Esse processo permite avaliar não apenas se uma resposta apresenta informações corretas, mas também se ela **segue exatamente as condições estabelecidas pelo usuário**.

---

## 15. Competências praticadas

Esta avaliação permitiu praticar as seguintes competências:

* Avaliação de *Instruction Following*;
* Verificação de requisitos;
* Análise de restrições de formato;
* Contagem e análise estrutural de frases;
* Identificação de listas e tópicos;
* Verificação de conteúdo obrigatório;
* Avaliação de factualidade;
* Avaliação de relevância;
* Avaliação de clareza;
* Avaliação de completude;
* Identificação de oportunidades de melhoria;
* Análise crítica de respostas de LLM;
* Controle de qualidade de respostas de IA.

---

## 16. Competências demonstradas

A avaliação demonstra competências relacionadas a:

* Interpretação precisa de instruções;
* Decomposição de uma solicitação em requisitos verificáveis;
* Validação sistemática de outputs de IA;
* Identificação de conformidade e não conformidade;
* Análise de restrições explícitas;
* Diferenciação entre erro e oportunidade de melhoria;
* Aplicação consistente de critérios de avaliação;
* Justificativa objetiva de resultados;
* Controle de qualidade de respostas geradas por IA.

---

## 17. Relação com QA e Auditoria

A atividade apresenta relação direta com práticas de **Quality Assurance (QA)** e **Auditoria**, especialmente no que se refere à verificação de conformidade com requisitos previamente definidos.

O processo utilizado pode ser relacionado a atividades como:

* definição de critérios de aceitação;
* verificação de conformidade;
* identificação de desvios;
* classificação de não conformidades;
* registro de evidências;
* aplicação de critérios objetivos;
* documentação de resultados;
* rastreabilidade da avaliação.

Nesse contexto, a resposta de IA pode ser tratada como um **output a ser validado**, enquanto as instruções fornecidas pelo usuário funcionam como requisitos de avaliação.

Essa abordagem demonstra uma competência transferível do QA tradicional para processos de avaliação e controle de qualidade de sistemas de Inteligência Artificial.

---

## 18. Conclusão

A resposta avaliada apresentou **aderência integral às instruções fornecidas pelo usuário**.

Ela definiu RAG, utilizou exatamente três frases, não utilizou listas ou tópicos, não apresentou exemplos e incluiu na última frase uma vantagem em relação ao uso isolado de um LLM.

A análise também demonstrou que é possível diferenciar **conformidade com a instrução** de **precisão técnica da formulação**.

Embora exista uma pequena oportunidade de melhoria na forma como a redução de alucinações é apresentada, não foi identificado nenhum problema suficientemente relevante para reduzir a pontuação dentro da rubrica utilizada.

**Resultado final: 12/12 — Excelente.**

---

## 19. Natureza do projeto

Este projeto possui caráter **educacional e demonstrativo**.

As avaliações são realizadas como exercícios práticos destinados ao desenvolvimento de competências relacionadas à avaliação, análise crítica, aderência a instruções e controle de qualidade de respostas de Inteligência Artificial.

Os resultados não representam avaliações oficiais, certificações ou testes realizados para empresas ou plataformas de Inteligência Artificial.

---

## 20. Contato

**Nágyla Silva**

* **LinkedIn:** [www.linkedin.com/in/nágyla-silva-215aba35a](https://www.linkedin.com/in/nágyla-silva-215aba35a)
* **GitHub:** [github.com/silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

---

*Portfólio desenvolvido para demonstrar aprendizado prático e competências relacionadas à avaliação e qualidade de respostas de Inteligência Artificial.*
