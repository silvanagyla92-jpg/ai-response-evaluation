# Avaliação 007 — RAG (Retrieval-Augmented Generation)

## 1. Pergunta do usuário

> O que é RAG (Retrieval-Augmented Generation)? Explique de forma simples como funciona, qual problema ele procura resolver e cite pelo menos dois benefícios e dois exemplos de aplicação prática.

---

## 2. Resposta avaliada

> **RAG** é uma técnica que combina um LLM com busca em uma base de dados externa, funcionando em três etapas: **recuperação** (o sistema busca trechos relevantes em documentos externos com base na pergunta), **aumento** (esses trechos são inseridos junto com a pergunta, formando um contexto ampliado) e **geração** (o LLM produz a resposta com base nesse contexto, em vez de depender só do que aprendeu no treinamento).
>
> **Problema que resolve:** conhecimento congelado dos LLMs, que causa respostas desatualizadas e alucinações.
>
> **Benefícios:** reduz alucinações e permite respostas atualizadas/específicas sem precisar retreinar o modelo.
>
> **Aplicações:** chatbots de suporte que usam manuais da empresa e assistentes internos que buscam em documentos corporativos.

---

## 2.1. Plataforma utilizada

**Plataforma:** Claude

**Finalidade:** Geração da resposta utilizada como objeto de avaliação durante este exercício prático.

**Fonte da resposta:** Resposta gerada pelo Claude para a pergunta proposta na Avaliação 007.

**Observação:** A resposta foi utilizada exclusivamente como objeto de análise neste projeto demonstrativo. A avaliação foi realizada pela autora utilizando a rubrica definida no projeto.

---

## 3. Critérios de avaliação

| Critério     | Pontuação | Avaliação                                                                                                                                           |
| ------------ | --------: | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| Factualidade |       2/2 | A resposta apresenta uma explicação adequada sobre RAG e descreve corretamente, em nível introdutório, as etapas de recuperação, aumento e geração. |
| Relevância   |       2/2 | A resposta atende diretamente aos elementos solicitados na pergunta.                                                                                |
| Clareza      |       2/2 | A explicação é organizada e apresenta o funcionamento do RAG de maneira compreensível.                                                              |
| Completude   |       2/2 | A resposta apresenta definição, funcionamento, problema, benefícios e aplicações práticas, atendendo aos requisitos da pergunta.                    |
| Segurança    |       2/2 | Não foram identificados conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.                                    |
| Alucinação   |       2/2 | Não foram identificadas informações claramente inventadas ou sem fundamento aparente no conteúdo avaliado.                                          |

---

## 4. Resultado

**Pontuação total: 12/12**

**Classificação: Excelente**

---

## 5. Justificativa

A resposta foi considerada excelente porque atende aos principais elementos solicitados na pergunta.

Ela apresenta uma definição de RAG, explica seu funcionamento por meio das três etapas — **recuperação, aumento e geração** —, identifica o problema que a técnica procura resolver, apresenta benefícios e fornece dois exemplos de aplicações práticas.

A estrutura utilizada também facilita a compreensão do conceito, tornando a resposta adequada para uma explicação introdutória sobre RAG.

Embora exista uma simplificação na afirmação de que o conhecimento congelado dos LLMs "causa" respostas desatualizadas e alucinações, essa formulação não foi considerada suficiente para reduzir a pontuação, considerando o contexto introdutório da pergunta.

Da mesma forma, a afirmação de que o RAG "reduz alucinações" é apresentada como um benefício geral da técnica, não como uma garantia de eliminação completa das alucinações.

Com base na rubrica utilizada, a resposta recebeu **12/12 pontos** e foi classificada como **Excelente**.

---

## 6. Observação da avaliadora

Durante a avaliação, foi considerado o conteúdo efetivamente apresentado pela resposta e sua capacidade de atender aos requisitos presentes na pergunta.

Não foram adicionadas informações externas para complementar ou corrigir a resposta durante a atribuição das notas.

A análise foi realizada separadamente para cada critério, permitindo diferenciar aspectos como factualidade, relevância, clareza, completude, segurança e possíveis alucinações.

Esse procedimento busca manter a avaliação baseada em evidências e critérios objetivos.

---

## 7. Processo de avaliação

A avaliação foi realizada individualmente para cada critério, utilizando uma escala de 0 a 2 pontos.

A análise considerou o conteúdo apresentado na resposta e sua aderência à solicitação original.

### Escala utilizada

* **0 — Inadequado:** apresenta problema significativo no critério avaliado.
* **1 — Parcialmente adequado:** apresenta características positivas, mas possui limitações.
* **2 — Adequado:** atende satisfatoriamente ao critério avaliado.

---

## 8. Resultado por critério

### Factualidade — 2/2

A resposta apresenta uma explicação adequada sobre RAG e descreve seu funcionamento geral por meio das etapas de recuperação, aumento e geração.

A explicação de que informações externas são recuperadas e utilizadas como contexto para a geração da resposta é adequada para o nível introdutório proposto.

Não foram identificados erros factuais relevantes que justificassem a redução da pontuação.

### Relevância — 2/2

A resposta atende diretamente aos elementos solicitados na pergunta.

Ela apresenta:

* definição de RAG;
* funcionamento;
* problema que procura resolver;
* benefícios;
* aplicações práticas.

O conteúdo permanece focado no tema e não apresenta informações significativamente desviantes.

### Clareza — 2/2

A resposta utiliza uma estrutura organizada e apresenta o funcionamento do RAG em três etapas:

1. **Recuperação**
2. **Aumento**
3. **Geração**

Essa organização facilita a compreensão do processo e torna a explicação adequada para uma introdução ao conceito.

### Completude — 2/2

A resposta atende aos requisitos apresentados na pergunta.

Ela explica o que é RAG, descreve seu funcionamento, apresenta o problema que procura resolver, cita benefícios e fornece exemplos de aplicações práticas.

Também apresenta dois exemplos concretos de aplicação:

* chatbots de suporte que utilizam manuais da empresa;
* assistentes internos que consultam documentos corporativos.

Dessa forma, não foram identificadas lacunas relevantes em relação ao que foi solicitado.

### Segurança — 2/2

Não foram identificados conteúdos perigosos, inadequados ou orientações que possam representar risco ao usuário.

A resposta apresenta informações técnicas e educacionais sobre uma técnica de Inteligência Artificial.

### Alucinação — 2/2

Não foram identificadas informações claramente inventadas ou afirmações sem fundamento aparente dentro do conteúdo avaliado.

A resposta apresenta conceitos relacionados ao funcionamento geral do RAG e não introduz fatos específicos que indiquem uma possível fabricação de informações.

A expressão de que o RAG "reduz alucinações" foi considerada uma descrição geral de um benefício da técnica, e não uma afirmação de que o RAG elimina completamente esse tipo de problema.

---

## 9. Conclusão

A resposta analisada apresentou desempenho satisfatório em todos os critérios avaliados.

Ela explicou o conceito de RAG, descreveu seu funcionamento em três etapas, apresentou o problema que procura resolver, indicou benefícios e forneceu exemplos de aplicações práticas.

Apesar de utilizar algumas simplificações próprias de uma explicação introdutória, não foram identificados problemas relevantes que justificassem a redução da pontuação.

Com base na rubrica utilizada, a resposta recebeu **12/12 pontos** e foi classificada como **Excelente**.

---

## 10. Competências praticadas

Esta avaliação permitiu praticar as seguintes competências:

* Avaliação estruturada de respostas de IA;
* Análise crítica de conteúdo;
* Avaliação de factualidade;
* Avaliação de relevância;
* Avaliação de clareza;
* Avaliação de completude;
* Identificação de possíveis limitações de respostas geradas por IA;
* Análise de segurança;
* Identificação de possíveis alucinações;
* Aplicação consistente de uma rubrica;
* Justificativa baseada em evidências;
* Documentação estruturada de resultados.

---

## 11. Natureza do projeto

Este projeto possui caráter **educacional e demonstrativo**.

As avaliações são realizadas como exercícios práticos para desenvolver competências relacionadas à avaliação e melhoria de respostas de Inteligência Artificial.

Os resultados não representam avaliações oficiais, certificações ou testes realizados para empresas ou plataformas de Inteligência Artificial.

---

## 12. Contato

**Nágyla Silva**

* **LinkedIn:** [www.linkedin.com/in/nágyla-silva-215aba35a](https://www.linkedin.com/in/nágyla-silva-215aba35a)
* **GitHub:** [github.com/silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

---

*Portfólio desenvolvido para demonstrar aprendizado prático e competências relacionadas à avaliação e qualidade de respostas de Inteligência Artificial.*
