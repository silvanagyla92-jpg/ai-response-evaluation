# Avaliação 012 — Aderência à Instrução

## 1. Introdução

Esta avaliação apresenta um exercício prático de análise da capacidade de um modelo de Inteligência Artificial de **seguir instruções específicas de conteúdo e formato**.

O exercício utiliza uma solicitação com múltiplas restrições simultâneas, incluindo quantidade exata de frases, ausência de listas e tópicos, ausência de exemplos e uma exigência específica para o conteúdo da última frase.

O objetivo é verificar não apenas se a resposta apresenta informações corretas, mas também se ela **cumpre integralmente as instruções fornecidas pelo usuário**.

Essa competência é relevante em processos de avaliação de respostas de IA porque uma resposta pode ser clara e relevante, mas ainda assim ser considerada inadequada caso não siga as restrições estabelecidas na solicitação.

---

## 2. Plataforma utilizada

**Plataforma:** Claude

**Finalidade:** Geração da resposta utilizada como objeto de avaliação durante este exercício prático.

**Fonte da resposta:** Resposta gerada pelo Claude para a pergunta proposta na Avaliação 012.

**Observação:** A resposta foi utilizada exclusivamente como objeto de análise neste projeto demonstrativo. A avaliação foi realizada pela autora utilizando a rubrica definida no projeto.

As avaliações apresentadas neste portfólio possuem finalidade educacional e demonstrativa. Elas não representam avaliações oficiais realizadas pela Anthropic, OpenAI ou por qualquer outra empresa.

---

## 3. Pergunta

> Explique o que é RAG (Retrieval-Augmented Generation) em exatamente 3 frases. Não utilize listas, tópicos ou exemplos. Na última frase, mencione uma vantagem do RAG em relação ao uso isolado de um LLM.

---

## 4. Resposta avaliada

> RAG (Retrieval-Augmented Generation) é uma técnica que combina um modelo de linguagem com um sistema de busca em uma base de dados externa, recuperando informações relevantes antes de gerar uma resposta.
>
> Esse processo ocorre em três etapas: o sistema busca trechos relevantes em documentos externos, insere esses trechos como contexto junto à pergunta original e então o modelo gera a resposta com base nesse contexto ampliado.
>
> Em relação ao uso isolado de um LLM, essa abordagem reduz significativamente o risco de alucinações, já que a resposta é ancorada em fontes reais e verificáveis, em vez de depender apenas do conhecimento estático adquirido durante o treinamento.

---

## 5. Critérios

Cada avaliação individual utiliza seis critérios. Cada critério recebe uma pontuação de **0 a 2 pontos**, totalizando no máximo **12 pontos**.

### 5.1. Factualidade — 0 a 2

Avalia se as informações apresentadas estão corretas, precisas e livres de afirmações incorretas, excessivamente abrangentes ou potencialmente enganosas.

### 5.2. Relevância — 0 a 2

Avalia se a resposta permanece diretamente relacionada à pergunta e evita informações desnecessárias ou fora do contexto.

### 5.3. Clareza — 0 a 2

Avalia se a resposta é compreensível, organizada e adequada ao contexto apresentado.

### 5.4. Completude — 0 a 2

Avalia se a resposta apresenta as informações necessárias para atender ao que foi solicitado, sem omissões relevantes.

### 5.5. Segurança — 0 a 2

Avalia se a resposta evita conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.

### 5.6. Alucinação — 0 a 2

Avalia se a resposta apresenta informações inventadas, não sustentadas ou apresentadas como fatos sem evidência suficiente.

**Pontuação máxima: 12 pontos.**

---

## 6. Escala de pontuação

Cada critério recebe uma pontuação conforme o nível de atendimento observado na resposta.

| Pontuação | Classificação |
| ---------: | ------------- |
| **0** | **Inadequado** |
| **1** | **Parcialmente adequado** |
| **2** | **Adequado** |

A pontuação é atribuída individualmente para cada critério, considerando o conteúdo efetivamente apresentado pela resposta.

**Pontuação máxima: 12 pontos.**

---

## 7. Escala de classificação

Após a análise individual dos seis critérios, as pontuações são somadas para determinar a classificação geral da resposta.

| Pontuação total | Classificação |
| ---------------: | ------------- |
| **0–3 pontos** | **Inadequada** |
| **4–6 pontos** | **Parcialmente adequada** |
| **7–9 pontos** | **Adequada** |
| **10–12 pontos** | **Excelente** |

**Fonte:** Metodologia própria desenvolvida para este portfólio.

A classificação quantitativa deve ser interpretada em conjunto com a análise qualitativa e os pontos de atenção identificados durante a avaliação.

---

## 8. Resultado

| Critério | Pontuação |
| --- | ---: |
| **Factualidade** | **1/2** |
| **Relevância** | **2/2** |
| **Clareza** | **2/2** |
| **Completude** | **2/2** |
| **Segurança** | **2/2** |
| **Alucinação** | **2/2** |
| **Pontuação total** | **11/12** |

**Classificação: Excelente**

**Aderência à instrução:** Totalmente adequada

**Tipo de problema identificado:** Generalização factual / excesso de certeza

**Gravidade:** Baixa

A resposta cumpriu integralmente as restrições estruturais apresentadas na solicitação, mas apresentou uma formulação excessivamente categórica ao relacionar o uso de RAG à redução significativa do risco de alucinações e à utilização de fontes reais e verificáveis.

---

## 9. Justificativa

A resposta apresentou excelente desempenho quanto à aderência às instruções fornecidas pelo usuário.

A solicitação estabelecia múltiplas restrições simultâneas, e a resposta conseguiu cumprir integralmente essas condições.

A resposta:

1. apresenta uma definição de RAG;
2. utiliza exatamente três frases;
3. não utiliza listas;
4. não utiliza tópicos;
5. não apresenta exemplos;
6. apresenta uma vantagem do RAG em relação ao uso isolado de um LLM na última frase.

Entretanto, a avaliação factual identificou uma limitação relevante na formulação da terceira frase.

A afirmação de que o RAG **“reduz significativamente o risco de alucinações”** apresenta uma generalização que deveria ser qualificada. O RAG pode contribuir para reduzir determinados tipos de respostas incorretas ao fornecer contexto recuperado ao modelo, mas esse mecanismo não garante a correção das informações recuperadas nem elimina a possibilidade de geração de respostas incorretas.

A expressão **“fontes reais e verificáveis”** também é excessivamente abrangente, pois a recuperação de uma fonte não garante, por si só, que ela seja correta, confiável, atual ou suficiente para fundamentar a resposta.

Por esse motivo, a **Factualidade recebeu 1/2**.

A limitação, entretanto, não caracteriza alucinação. Não foram identificadas evidências suficientes de que o modelo tenha inventado informações. O problema está na **generalização e no excesso de certeza da formulação**, e não na fabricação de fatos.

Com base na rubrica utilizada, a resposta recebeu **11/12 pontos** e foi classificada como **Excelente**.

---

## 10. Pontos fortes

* Cumpre exatamente a quantidade de frases solicitada.
* Não utiliza listas.
* Não utiliza tópicos.
* Não apresenta exemplos.
* Define RAG de maneira objetiva.
* Explica de forma resumida o funcionamento geral do processo.
* Apresenta uma vantagem do RAG na última frase.
* Mantém relação direta com a pergunta.
* Utiliza linguagem clara e relativamente acessível.
* Demonstra elevada aderência às restrições explícitas do usuário.
* Mantém a resposta dentro do formato solicitado.

---

## 11. Limitações

A principal limitação identificada está relacionada à **precisão factual da formulação utilizada na terceira frase**.

A resposta afirma:

> “essa abordagem reduz significativamente o risco de alucinações”

Essa afirmação pode ser considerada excessivamente abrangente porque o RAG pode reduzir determinados tipos de respostas incorretas, mas não garante que a resposta gerada seja correta nem elimina o risco de alucinação.

A resposta também afirma:

> “a resposta é ancorada em fontes reais e verificáveis”

Essa formulação apresenta outro nível de generalização, pois a simples recuperação de documentos ou fontes não garante automaticamente que essas informações sejam confiáveis, atuais, corretas ou verificáveis.

Uma formulação tecnicamente mais precisa poderia utilizar qualificadores como **“pode reduzir”**, **“pode ajudar a reduzir”** ou **“quando as fontes recuperadas são confiáveis e relevantes”**.

Essas limitações justificam a redução da pontuação de **Factualidade para 1/2**, mas não justificam redução nos demais critérios.

---

## 12. Análise detalhada

### 12.1. Factualidade — 1/2

A definição geral de RAG e a descrição simplificada de seu funcionamento são adequadas.

Entretanto, a terceira frase apresenta uma afirmação excessivamente categórica sobre a relação entre RAG e alucinações.

O RAG pode fornecer contexto externo ao modelo e contribuir para respostas mais fundamentadas, mas não garante que as informações recuperadas estejam corretas ou que o modelo produzirá uma resposta factual.

A expressão **“reduz significativamente”** deveria ser qualificada, pois o efeito depende da implementação, da qualidade das fontes recuperadas, da estratégia de recuperação e da forma como o modelo utiliza o contexto.

A expressão **“fontes reais e verificáveis”** também é ampla demais para ser apresentada sem qualificadores.

Portanto, existe uma limitação factual relevante, mas não uma falsidade completa.

**Pontuação: 1/2 — Parcialmente adequado.**

### 12.2. Relevância — 2/2

A resposta permanece diretamente relacionada à solicitação.

Ela explica o conceito de RAG, descreve seu funcionamento e apresenta uma vantagem em relação ao uso isolado de um LLM.

Não foram identificadas informações significativamente desviantes ou desnecessárias.

**Pontuação: 2/2 — Adequado.**

### 12.3. Clareza — 2/2

A resposta apresenta linguagem objetiva e estrutura lógica.

A primeira frase apresenta a definição, a segunda explica o funcionamento e a terceira apresenta uma vantagem.

Apesar da possibilidade de maior precisão técnica na terceira frase, a informação permanece compreensível para o leitor.

**Pontuação: 2/2 — Adequado.**

### 12.4. Completude — 2/2

A solicitação estabelecia requisitos específicos de conteúdo e formato.

A resposta:

* explica o que é RAG;
* utiliza exatamente três frases;
* não utiliza listas;
* não utiliza tópicos;
* não apresenta exemplos;
* apresenta uma vantagem do RAG na última frase.

Não foram identificadas omissões relevantes em relação ao que foi solicitado.

A existência de uma limitação factual na formulação de uma das informações não caracteriza falta de conteúdo.

**Pontuação: 2/2 — Adequado.**

### 12.5. Segurança — 2/2

Não foram identificados conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.

O conteúdo é educacional e descreve um conceito relacionado a sistemas de Inteligência Artificial.

**Pontuação: 2/2 — Adequado.**

### 12.6. Alucinação — 2/2

Não foram identificadas evidências suficientes de informações inventadas ou fabricadas.

As afirmações apresentadas estão relacionadas a conceitos reais de RAG e de redução de determinados tipos de respostas incorretas por meio de recuperação de contexto.

O problema identificado está relacionado à **generalização factual e ao excesso de certeza**, e não à invenção de informações.

Essa distinção é importante para evitar classificar automaticamente uma afirmação imprecisa ou excessivamente abrangente como alucinação.

**Pontuação: 2/2 — Adequado.**

---

## 13. Observação da avaliadora

A principal característica positiva observada nesta avaliação foi a capacidade do modelo de cumprir simultaneamente múltiplas restrições explícitas de conteúdo e formato.

A resposta apresentou exatamente três frases, não utilizou listas, não apresentou tópicos, não utilizou exemplos e reservou a última frase para apresentar uma vantagem do RAG em relação ao uso isolado de um LLM.

Entretanto, a análise também demonstrou que **aderência à instrução não equivale automaticamente a precisão factual**.

A resposta pode seguir perfeitamente as instruções de formato e ainda apresentar uma formulação que necessita de maior qualificação técnica.

Neste caso, o principal ponto de atenção foi a afirmação de que o RAG **“reduz significativamente o risco de alucinações”** e que a resposta estaria **“ancorada em fontes reais e verificáveis”**.

Essas expressões deveriam ser qualificadas para evitar transmitir uma garantia que o mecanismo de RAG, por si só, não fornece.

A avaliação, portanto, diferencia:

**Aderência à instrução:** totalmente adequada.

**Factualidade:** parcialmente adequada devido à generalização factual.

**Alucinação:** não identificada.

**Gravidade:** baixa.

---

## 14. Processo

A avaliação foi realizada individualmente para cada um dos seis critérios definidos na metodologia.

O processo seguiu as seguintes etapas:

1. Identificação da pergunta e das instruções explícitas.
2. Separação das restrições de conteúdo e formato.
3. Verificação da quantidade exata de frases.
4. Verificação da presença de listas.
5. Verificação da presença de tópicos.
6. Verificação da presença de exemplos.
7. Verificação do conteúdo exigido na última frase.
8. Análise da factualidade das afirmações apresentadas.
9. Identificação de possíveis generalizações ou afirmações excessivamente categóricas.
10. Verificação de possíveis sinais de alucinação.
11. Avaliação da relevância, clareza e completude.
12. Avaliação de segurança.
13. Classificação da gravidade do problema identificado.
14. Atribuição da pontuação individual para cada critério.
15. Soma das pontuações e classificação final.

A pontuação final foi obtida pela soma:

**1 + 2 + 2 + 2 + 2 + 2 = 11/12 pontos.**

A pontuação corresponde à classificação **10–12 pontos — Excelente**.

---

## 15. Competências praticadas

Esta avaliação permitiu praticar as seguintes competências:

* Avaliação de *Instruction Following*;
* Interpretação de instruções explícitas;
* Decomposição de uma solicitação em requisitos verificáveis;
* Verificação de restrições de formato;
* Contagem e análise estrutural de frases;
* Identificação de listas e tópicos;
* Verificação de conteúdo obrigatório;
* Avaliação de factualidade;
* Avaliação de relevância;
* Avaliação de clareza;
* Avaliação de completude;
* Identificação de generalizações factuais;
* Identificação de excesso de certeza;
* Diferenciação entre generalização e alucinação;
* Análise crítica de respostas de LLM;
* Aplicação consistente de uma rubrica;
* Documentação estruturada de resultados.

---

## 16. Competências demonstradas

A atividade demonstra competências relevantes para funções de **AI Response Evaluator**, **AI Trainer** e **Data Annotator**, especialmente em tarefas relacionadas à avaliação da qualidade e conformidade de outputs de modelos de IA.

### AI Response Evaluator

* Verificação sistemática de aderência a instruções;
* Identificação de restrições explícitas;
* Avaliação de factualidade;
* Identificação de generalizações excessivas;
* Diferenciação entre erro factual e alucinação;
* Avaliação de relevância, clareza e completude;
* Aplicação de critérios padronizados;
* Classificação da gravidade de problemas;
* Justificativa objetiva de pontuações.

### AI Trainer

* Análise crítica do comportamento de um modelo diante de instruções específicas;
* Identificação de oportunidades de melhoria em respostas de LLM;
* Avaliação da precisão das formulações;
* Identificação de situações em que qualificadores são necessários;
* Análise de como uma resposta pode ser tecnicamente aprimorada sem perder aderência à instrução.

### Data Annotator

* Aplicação consistente de categorias;
* Classificação estruturada de características de respostas;
* Identificação de atributos específicos;
* Aplicação de critérios previamente definidos;
* Registro padronizado de decisões.

---

## 17. Relação com QA e Auditoria

A atividade apresenta relação direta com práticas de **Quality Assurance (QA)** e **Auditoria**, especialmente na verificação de conformidade com requisitos previamente definidos.

A avaliação demonstra competências transferíveis, como:

* aplicação de critérios previamente estabelecidos;
* verificação de conformidade;
* identificação de desvios;
* classificação de não conformidades;
* diferenciação entre tipos de problemas;
* classificação de gravidade;
* análise baseada em evidências;
* documentação das decisões;
* rastreabilidade dos resultados;
* padronização do processo avaliativo;
* controle de qualidade.

Nesse contexto, as instruções fornecidas pelo usuário podem ser tratadas como requisitos de avaliação, enquanto a resposta gerada pelo modelo representa o **output a ser validado**.

A atividade também demonstra uma prática importante de QA: distinguir entre **não conformidade**, **erro factual**, **generalização**, **oportunidade de melhoria** e **ausência de problema**.

Essa abordagem é transferível para processos de avaliação e controle de qualidade de respostas geradas por sistemas de Inteligência Artificial.

---

## 18. Conclusão

A resposta avaliada apresentou **aderência integral às instruções fornecidas pelo usuário**.

Ela explicou o conceito de RAG, utilizou exatamente três frases, não utilizou listas ou tópicos, não apresentou exemplos e incluiu na última frase uma vantagem em relação ao uso isolado de um LLM.

Entretanto, a avaliação identificou uma **generalização factual de baixa gravidade** na afirmação de que o RAG reduz significativamente o risco de alucinações e de que a resposta estaria ancorada em fontes reais e verificáveis.

O RAG pode contribuir para respostas mais fundamentadas ao fornecer contexto recuperado, mas não garante a correção das fontes nem elimina a possibilidade de respostas incorretas.

A limitação foi classificada como problema de **Factualidade**, e não como alucinação, pois não foram identificadas evidências suficientes de informações inventadas.

Com base na rubrica utilizada, a resposta recebeu:

**11/12 — Excelente**

**Aderência à instrução: Totalmente adequada.**

**Classificação de erro: Generalização factual / excesso de certeza — baixa gravidade.**

---

## 19. Natureza do projeto

Este projeto possui caráter **educacional e demonstrativo**.

As avaliações são realizadas como exercícios práticos para desenvolver competências relacionadas à avaliação, análise crítica, aderência a instruções e controle de qualidade de respostas de Inteligência Artificial.

Os resultados não representam avaliações oficiais, certificações ou testes realizados para empresas ou plataformas de Inteligência Artificial.

---

## 20. Contato

**Nágyla Silva**

* **LinkedIn:** [www.linkedin.com/in/nágyla-silva-215aba35a](https://www.linkedin.com/in/nágyla-silva-215aba35a)
* **GitHub:** [github.com/silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

---

*Portfólio desenvolvido para demonstrar aprendizado prático e competências relacionadas à avaliação e qualidade de respostas de Inteligência Artificial.*
