# Avaliação 007 — RAG (Retrieval-Augmented Generation)

## 1. Introdução

Esta avaliação apresenta um exercício prático de análise de uma resposta gerada por Inteligência Artificial. O objetivo é verificar a qualidade da resposta a partir de critérios previamente definidos, considerando aspectos como factualidade, relevância, clareza, completude, segurança e possíveis evidências de alucinação.

A atividade demonstra a aplicação de uma metodologia estruturada de avaliação de respostas de IA, com registro das decisões, evidências observadas e justificativas utilizadas para chegar ao resultado final.

Neste exercício, o foco está na avaliação de uma explicação introdutória sobre **RAG (Retrieval-Augmented Generation)**, considerando seu funcionamento, o problema que procura ajudar a resolver, seus benefícios e suas aplicações práticas.

---

## 2. Plataforma utilizada

**Plataforma:** Claude

**Finalidade:** Utilização da plataforma para geração da resposta utilizada como objeto de avaliação durante este exercício prático.

**Fonte da resposta:** Resposta gerada pelo Claude para a pergunta proposta na Avaliação 007.

**Observação:** A resposta foi utilizada exclusivamente como objeto de análise neste projeto demonstrativo. A avaliação foi realizada pela autora utilizando a rubrica definida no projeto.

As avaliações apresentadas neste portfólio possuem finalidade educacional e demonstrativa. Elas não representam avaliações oficiais realizadas pela Anthropic, OpenAI ou por qualquer outra empresa.

---

## 3. Pergunta

> O que é RAG (Retrieval-Augmented Generation)? Explique de forma simples como funciona, qual problema ele procura resolver e cite pelo menos dois benefícios e dois exemplos de aplicação prática.

---

## 4. Resposta avaliada

> **RAG** é uma técnica que combina um LLM com busca em uma base de dados externa, funcionando em três etapas: **recuperação** (o sistema busca trechos relevantes em documentos externos com base na pergunta), **aumento** (esses trechos são inseridos junto com a pergunta, formando um contexto ampliado) e **geração** (o LLM produz a resposta com base nesse contexto, em vez de depender só do que aprendeu no treinamento).
>
> **Problema que resolve:** conhecimento congelado dos LLMs, que causa respostas desatualizadas e alucinações.
>
> **Benefícios:** reduz alucinações e permite respostas atualizadas/específicas sem precisar retreinar o modelo.
>
> **Aplicações:** chatbots de suporte que usam manuais da empresa e assistentes internos que buscam em documentos corporativos.

---

## 5. Critérios

Cada avaliação individual utiliza seis critérios. Cada critério recebe uma pontuação de **0 a 2 pontos**, totalizando no máximo **12 pontos**.

### 5.1. Factualidade — 0 a 2

Avalia se as informações apresentadas estão corretas, precisas e livres de afirmações incorretas ou excessivamente generalizadas.

### 5.2. Relevância — 0 a 2

Avalia se a resposta permanece relacionada à pergunta e evita informações desnecessárias ou fora do contexto.

### 5.3. Clareza — 0 a 2

Avalia se a resposta é compreensível, organizada e adequada ao contexto apresentado.

### 5.4. Completude — 0 a 2

Avalia se a resposta apresenta as informações necessárias para atender ao que foi solicitado, sem omissões relevantes.

### 5.5. Segurança — 0 a 2

Avalia se a resposta evita conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.

### 5.6. Alucinação — 0 a 2

Avalia se a resposta apresenta informações inventadas, fabricadas ou apresentadas como fatos sem fundamento suficiente.

**Pontuação máxima: 12 pontos.**

---

## 6. Escala de pontuação

Cada um dos seis critérios recebe uma pontuação conforme o nível de atendimento observado na resposta.

* **0 — Inadequado:** apresenta problema significativo no critério avaliado.
* **1 — Parcialmente adequado:** atende parcialmente ao critério, mas apresenta limitações relevantes.
* **2 — Adequado:** atende satisfatoriamente ao critério avaliado.

A pontuação máxima possível é de **12 pontos**.

---

## 7. Escala de classificação

Após a análise individual dos seis critérios, as pontuações são somadas para determinar a classificação geral da resposta.

| **Pontuação total** | **Classificação** |
| ------------------: | ----------------- |
| **0–3 pontos** | **Inadequada** |
| **4–6 pontos** | **Parcialmente adequada** |
| **7–9 pontos** | **Adequada** |
| **10–12 pontos** | **Excelente** |

**Fonte:** Metodologia própria desenvolvida para este portfólio.

A classificação considera exclusivamente a pontuação total obtida nos seis critérios avaliados.

---

## 8. Resultado

| **Critério** | **Pontuação** |
| --- | ---: |
| Factualidade | **1/2** |
| Relevância | **2/2** |
| Clareza | **2/2** |
| Completude | **2/2** |
| Segurança | **2/2** |
| Alucinação | **2/2** |
| **Pontuação total** | **11/12** |

**Classificação: Excelente**

> **Observação:** A resposta recebeu **11/12 pontos** e foi classificada como **Excelente** de acordo com a escala quantitativa definitiva do projeto. Entretanto, a análise qualitativa identificou limitações de precisão técnica em algumas afirmações, especialmente nas expressões “conhecimento congelado”, “causa respostas desatualizadas e alucinações” e “reduz alucinações”. Essas limitações foram concentradas no critério de **Factualidade**, sem caracterizar a resposta como uma alucinação.

---

## 9. Justificativa

A resposta atende aos principais elementos solicitados na pergunta.

Ela apresenta uma definição de RAG e explica seu funcionamento por meio das etapas de **recuperação, aumento e geração**. Também identifica um problema que a técnica procura ajudar a tratar, apresenta benefícios e fornece dois exemplos concretos de aplicações práticas.

A estrutura da resposta facilita a compreensão do conceito e permanece adequada ao nível introdutório solicitado pelo usuário.

Entretanto, foram identificadas algumas formulações que reduzem a precisão técnica da resposta.

A primeira está na afirmação:

> “conhecimento congelado dos LLMs, que causa respostas desatualizadas e alucinações.”

A expressão **“conhecimento congelado”** constitui uma simplificação válida para explicar que o conhecimento incorporado durante o treinamento não é automaticamente atualizado com novos acontecimentos. Entretanto, a afirmação de que esse fator **“causa”** respostas desatualizadas e alucinações estabelece uma relação causal excessivamente ampla.

A falta de atualização pode contribuir para respostas desatualizadas, mas as alucinações podem ocorrer por diferentes fatores e não são necessariamente causadas pela ausência de atualização do conhecimento.

A segunda questão está na afirmação:

> “reduz alucinações”.

Essa formulação também é excessivamente abrangente quando apresentada sem qualificação. O RAG **pode contribuir para reduzir determinados tipos de respostas incorretas ou alucinações** quando documentos relevantes e confiáveis são corretamente recuperados e utilizados como contexto. Entretanto, isso não constitui uma garantia de redução de alucinações em todas as situações.

Também é necessário observar que o RAG não substitui o conhecimento adquirido pelo modelo durante o treinamento. O conteúdo recuperado funciona como **contexto adicional** utilizado para orientar a geração da resposta.

Essas limitações reduzem a precisão factual da resposta, mas não comprometem significativamente sua adequação geral como explicação introdutória.

Com base na rubrica utilizada, a resposta recebeu **11/12 pontos** e foi classificada como **Excelente**.

---

## 10. Pontos fortes

* Define RAG de forma objetiva.
* Explica o conceito por meio das etapas de recuperação, aumento e geração.
* Relaciona RAG ao uso de informações externas.
* Identifica a necessidade de complementar o conhecimento do modelo com informações externas.
* Apresenta benefícios relacionados ao uso de contexto externo.
* Fornece dois exemplos concretos de aplicações práticas.
* Utiliza linguagem clara e acessível.
* Responde diretamente aos elementos solicitados pelo usuário.
* Diferencia as etapas de recuperação, aumento e geração.
* Mantém foco no tema solicitado.
* Não apresenta nomes, acontecimentos ou dados específicos evidentemente inventados.
* Permite identificar claramente os pontos que necessitam de maior precisão técnica.

---

## 11. Limitações

A principal limitação da resposta está relacionada à **precisão de algumas afirmações sobre o funcionamento e os benefícios do RAG**.

A expressão:

> “conhecimento congelado dos LLMs”

é uma simplificação utilizada para descrever o fato de que o conhecimento incorporado durante o treinamento não é automaticamente atualizado com novas informações.

Entretanto, a continuação:

> “que causa respostas desatualizadas e alucinações”

estabelece uma relação causal excessivamente ampla.

A ausência de atualização pode contribuir para respostas desatualizadas, mas não constitui uma explicação suficiente para todas as ocorrências de alucinação.

Também é necessário qualificar a afirmação:

> “reduz alucinações”.

O RAG pode contribuir para reduzir determinados tipos de erros ao fornecer informações externas relevantes e potencialmente mais atualizadas, mas sua eficácia depende de fatores como qualidade das fontes, qualidade da recuperação, relevância dos documentos recuperados e utilização adequada do contexto pelo modelo.

Portanto, a formulação não deve ser interpretada como uma garantia de redução ou eliminação de alucinações.

Outra simplificação está na descrição do processo como se o LLM respondesse “em vez de depender só do que aprendeu no treinamento”.

Na prática, o modelo continua utilizando as capacidades adquiridas durante o treinamento, enquanto as informações recuperadas funcionam como **contexto adicional** para orientar a geração.

Essas limitações justificam a redução da pontuação de **Factualidade para 1/2**, mas não comprometem os demais critérios.

---

## 12. Análise detalhada

### Factualidade — 1/2

A resposta apresenta uma explicação geral adequada sobre RAG e descreve seu funcionamento por meio das etapas de recuperação, aumento e geração.

A explicação de que informações externas podem ser recuperadas e utilizadas como contexto para orientar a geração da resposta é adequada para o nível introdutório proposto.

A resposta também identifica corretamente um dos problemas que o RAG procura ajudar a tratar: a necessidade de complementar o conhecimento do modelo com informações externas que podem ser mais específicas ou atualizadas.

Entretanto, existem formulações que reduzem a precisão da explicação.

A expressão **“conhecimento congelado”** é uma simplificação aceitável, mas a afirmação de que esse conhecimento **“causa” respostas desatualizadas e alucinações** estabelece uma relação causal excessivamente ampla.

A ausência de atualização pode contribuir para respostas desatualizadas, mas não explica sozinha a ocorrência de alucinações.

Além disso, a afirmação de que o RAG **“reduz alucinações”** é apresentada sem qualificação. O RAG pode ajudar a reduzir determinados erros quando informações relevantes e confiáveis são recuperadas e utilizadas adequadamente, mas não garante a eliminação ou redução de alucinações em todas as situações.

Também é importante esclarecer que o RAG não substitui o conhecimento adquirido pelo modelo durante o treinamento. Os documentos recuperados funcionam como contexto adicional para orientar a geração.

Dessa forma, a resposta é majoritariamente adequada, mas apresenta generalizações técnicas que necessitam de qualificação.

**Pontuação: 1/2.**

### Relevância — 2/2

A resposta atende diretamente aos elementos solicitados na pergunta.

Ela apresenta:

* definição de RAG;
* funcionamento;
* problema que procura ajudar a resolver;
* benefícios;
* aplicações práticas.

O conteúdo permanece focado no tema e não apresenta informações significativamente desviantes.

**Pontuação: 2/2.**

### Clareza — 2/2

A resposta utiliza uma estrutura organizada e apresenta o funcionamento do RAG em três etapas:

1. **Recuperação**
2. **Aumento**
3. **Geração**

Essa organização facilita a compreensão do processo e torna a explicação adequada para uma introdução ao conceito.

A separação entre problema, benefícios e aplicações também contribui para a clareza da resposta.

As limitações identificadas estão principalmente relacionadas à precisão de algumas afirmações, e não à forma de apresentação.

**Pontuação: 2/2.**

### Completude — 2/2

A resposta atende aos requisitos apresentados na pergunta.

Ela explica o que é RAG, descreve seu funcionamento, apresenta o problema que procura ajudar a resolver, cita benefícios e fornece exemplos de aplicações práticas.

Também apresenta dois exemplos concretos de aplicação:

* chatbots de suporte que utilizam manuais da empresa;
* assistentes internos que consultam documentos corporativos.

Dessa forma, não foram identificadas lacunas relevantes em relação ao que foi explicitamente solicitado pelo usuário.

As limitações de precisão técnica não representam ausência de conteúdo e, portanto, não justificam redução neste critério.

**Pontuação: 2/2.**

### Segurança — 2/2

Não foram identificados conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.

A resposta apresenta informações técnicas e educacionais sobre uma técnica de Inteligência Artificial.

**Pontuação: 2/2.**

### Alucinação — 2/2

Não foram identificadas informações claramente inventadas ou afirmações sem fundamento aparente dentro do conteúdo avaliado.

A resposta apresenta conceitos relacionados ao funcionamento geral do RAG e não introduz pessoas, acontecimentos, fontes ou dados específicos evidentemente fabricados.

As simplificações identificadas sobre a relação entre conhecimento desatualizado, alucinações e benefícios do RAG foram tratadas como questões de **precisão conceitual e generalização**, e não como evidência de informação inventada.

A afirmação de que o RAG “reduz alucinações” também não foi classificada como alucinação. O problema está na amplitude da formulação e na ausência de qualificação, não na invenção de um fato específico.

Por esse motivo, o critério permanece em **2/2**.

**Pontuação: 2/2.**

---

## 13. Observação da avaliadora

Durante a avaliação, foi considerado exclusivamente o conteúdo efetivamente apresentado pela resposta e sua capacidade de atender aos requisitos presentes na pergunta original.

Não foram adicionadas informações externas para completar ou corrigir a resposta durante a atribuição das notas.

A análise buscou diferenciar:

* **erro factual**;
* **generalização excessiva**;
* **simplificação conceitual**;
* **informação inventada**;
* **omissão de informação**;
* **limitação de precisão técnica**.

A expressão **“conhecimento congelado”** foi considerada uma simplificação aceitável para uma explicação introdutória, mas sua utilização acompanhada da afirmação de que esse conhecimento “causa” alucinações foi considerada excessivamente abrangente.

A afirmação de que o RAG **“reduz alucinações”** também foi considerada uma generalização que necessita de qualificação. Uma formulação metodologicamente mais precisa seria indicar que o RAG **pode contribuir para reduzir determinados tipos de erros ou alucinações**, dependendo da qualidade da recuperação e das informações utilizadas como contexto.

Essas questões foram concentradas no critério de **Factualidade**, evitando penalização duplicada nos critérios de **Completude** ou **Alucinação**.

O critério de **Alucinação** foi mantido em **2/2** porque não foram identificadas evidências de que a resposta tenha inventado pessoas, acontecimentos, fontes, dados ou fatos específicos.

Esse procedimento mantém a distinção entre uma **afirmação excessivamente generalizada** e uma **informação inventada**, evitando que esses fenômenos sejam tratados como equivalentes.

---

## 14. Processo

A resposta foi analisada individualmente em cada um dos seis critérios definidos na metodologia do projeto.

Para cada critério, foi atribuída uma pontuação de **0 a 2 pontos**, considerando exclusivamente as características observadas no conteúdo avaliado e sua aderência à solicitação original.

A pontuação final foi obtida pela soma dos resultados individuais:

**1 + 2 + 2 + 2 + 2 + 2 = 11/12 pontos.**

A classificação final foi determinada pela **Escala de Classificação da Rubrica de Avaliação**, correspondendo à faixa de:

**10–12 pontos — Excelente.**

O processo também considerou a diferença entre:

* erro factual;
* simplificação conceitual;
* informação inventada;
* omissão de informação;
* afirmação excessivamente generalizada;
* limitação técnica;
* informação relevante apresentada corretamente.

A análise buscou evitar que uma única falha fosse automaticamente reproduzida nos demais critérios.

Nesse sentido, uma limitação de factualidade não foi automaticamente considerada uma falha de completude, clareza ou alucinação.

Essa separação contribui para maior consistência, rastreabilidade e independência entre os critérios.

---

## 15. Competências praticadas

Esta avaliação permitiu praticar as seguintes competências:

* Avaliação estruturada de respostas de IA;
* Análise crítica de conteúdo;
* Avaliação de factualidade;
* Avaliação de relevância;
* Avaliação de clareza;
* Avaliação de completude;
* Identificação de simplificações conceituais;
* Identificação de generalizações excessivas;
* Diferenciação entre simplificação e erro factual;
* Diferenciação entre generalização e alucinação;
* Análise da qualidade de explicações técnicas;
* Análise de segurança;
* Identificação de possíveis alucinações;
* Aplicação consistente de uma rubrica;
* Justificativa baseada em evidências;
* Documentação estruturada de resultados;
* Quality Assessment.

---

## 16. Competências demonstradas

A atividade demonstra competências relacionadas às funções de **AI Response Evaluator** e **AI Trainer**, além de competências transferíveis do contexto de **QA e Auditoria**.

### AI Response Evaluator

* Aplicação de critérios objetivos para avaliação de respostas de IA;
* Análise individual de diferentes dimensões de qualidade;
* Avaliação da factualidade de uma explicação técnica sobre RAG;
* Identificação de generalizações excessivas;
* Diferenciação entre erro factual, generalização e simplificação didática;
* Identificação de possíveis evidências de alucinação;
* Avaliação da aderência da resposta aos requisitos da pergunta;
* Classificação estruturada da qualidade da resposta;
* Justificativa das pontuações com base no conteúdo avaliado;
* Aplicação consistente de uma rubrica previamente definida.

### AI Trainer

* Análise crítica da qualidade de respostas geradas por IA;
* Avaliação da adequação da resposta ao nível solicitado pelo usuário;
* Identificação de formulações que poderiam ser tecnicamente aprimoradas;
* Avaliação da capacidade da resposta de explicar conceitos de IA de forma acessível;
* Identificação de oportunidades para melhorar precisão e contextualização em respostas técnicas;
* Identificação de afirmações que necessitam de maior qualificação para evitar generalizações excessivas.

### Data Annotator

Esta avaliação demonstra competências relacionadas à análise e classificação estruturada de conteúdo.

Entretanto, não demonstra diretamente uma tarefa de anotação ou rotulagem de dados, pois o exercício está concentrado na avaliação da qualidade de uma resposta gerada por IA.

---

## 17. Relação com QA e Auditoria

A atividade apresenta relação com práticas de **Quality Assurance (QA)** e auditoria por utilizar critérios previamente definidos, análise baseada em evidências, identificação de possíveis problemas e documentação estruturada dos resultados.

A avaliação demonstra competências transferíveis para processos de controle de qualidade, especialmente:

* Aplicação consistente de critérios previamente definidos;
* Análise baseada em evidências;
* Avaliação individual de diferentes dimensões de qualidade;
* Identificação e documentação de limitações;
* Diferenciação entre tipos de problemas;
* Registro estruturado das decisões;
* Rastreabilidade das justificativas;
* Padronização do processo de avaliação;
* Consistência na aplicação de critérios de qualidade;
* Evitação de penalização duplicada pelo mesmo problema.

A atividade também demonstra uma prática importante de QA: **não tratar todos os problemas como equivalentes**.

Uma simplificação conceitual, uma omissão, uma informação inventada e uma afirmação excessivamente generalizada podem possuir impactos diferentes e devem ser avaliadas de acordo com critérios previamente definidos.

Nesse sentido, a atividade demonstra uma abordagem baseada em **critérios, evidências, classificação, justificativa e rastreabilidade**, competências transferíveis para processos de QA e auditoria.

---

## 18. Conclusão

A resposta analisada apresentou desempenho adequado na maioria dos critérios avaliados.

Ela explicou o conceito de RAG, descreveu seu funcionamento por meio das etapas de recuperação, aumento e geração, apresentou um problema que a técnica procura ajudar a tratar, indicou benefícios e forneceu exemplos de aplicações práticas.

Foram identificadas limitações de precisão, principalmente na relação estabelecida entre conhecimento desatualizado e alucinações e na afirmação de que o RAG **“reduz alucinações”** sem apresentar as condições e limitações dessa afirmação.

A expressão **“conhecimento congelado”** também representa uma simplificação que deve ser utilizada com cautela, especialmente quando associada a uma relação causal direta com alucinações.

Essas limitações foram consideradas no critério de **Factualidade**, que recebeu **1/2**.

Não foram identificados problemas relevantes de relevância, clareza, completude ou segurança.

Também não foram identificadas evidências de informações claramente inventadas. Por esse motivo, o critério de **Alucinação** permaneceu em **2/2**.

Com base na rubrica utilizada, a resposta recebeu:

**11/12 pontos — Excelente.**

A classificação quantitativa não elimina as limitações qualitativas identificadas. O resultado demonstra que uma resposta pode permanecer dentro da faixa superior da rubrica e, ainda assim, apresentar aspectos específicos que necessitam de aprimoramento técnico.

A avaliação demonstra competências relacionadas às funções de **AI Response Evaluator** e **AI Trainer**, além de competências transferíveis de **QA e Auditoria**, especialmente na aplicação de critérios, análise baseada em evidências, identificação de limitações, diferenciação entre tipos de problemas e documentação estruturada das decisões.

---

## 19. Natureza do projeto

Este projeto possui caráter **educacional e demonstrativo**.

As avaliações são realizadas como exercícios práticos para desenvolver competências relacionadas à avaliação, análise crítica, qualidade e melhoria de respostas de Inteligência Artificial.

Os resultados não representam avaliações oficiais, certificações ou testes realizados para a Anthropic, OpenAI ou qualquer outra empresa.

A metodologia de avaliação, os critérios, as escalas e as classificações utilizadas neste portfólio foram desenvolvidos para fins de demonstração prática das competências da autora.

---

## 20. Contato

**Nágyla Silva**

* **LinkedIn:** [www.linkedin.com/in/nágyla-silva-215aba35a](https://www.linkedin.com/in/nágyla-silva-215aba35a)
* **GitHub:** [github.com/silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

---

*Avaliação desenvolvida como parte do portfólio prático de estudos em Inteligência Artificial, com foco em AI Trainer, AI Response Evaluator, Data Annotation e competências relacionadas à avaliação e qualidade de respostas de IA.*
