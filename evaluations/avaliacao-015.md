# Avaliação 015 — Instrução Complexa

## 1. Introdução

Esta avaliação apresenta um exercício prático de cumprimento e verificação de instruções complexas aplicadas a respostas geradas por plataformas de Inteligência Artificial.

O objetivo é verificar se duas respostas, geradas por plataformas diferentes para a mesma solicitação, atendem aos requisitos explícitos de conteúdo, quantidade de frases, linguagem, formato, ausência de exemplos e requisito específico para a última frase — e, em seguida, avaliar a qualidade de cada resposta segundo os seis critérios padronizados da rubrica-base, comparando-as entre si.

O cumprimento das instruções é verificado qualitativamente, em etapa separada da pontuação. A pontuação oficial permanece baseada exclusivamente nos seis critérios padronizados da rubrica.

---

## 2. Contexto da avaliação

**Plataformas/modelos utilizados:** Claude (Resposta A) e Gemini (Resposta B)

**Origem das respostas:** geração independente pelas plataformas Claude e Gemini para a mesma solicitação, permitindo posterior comparação.

**Avaliadora:** Nágyla Silva.

**Finalidade:** verificar o cumprimento de instruções complexas e comparar a qualidade de duas respostas geradas por plataformas distintas, utilizando a rubrica padronizada do portfólio.

A avaliação foi realizada pela autora. As plataformas utilizadas para gerar as respostas não foram utilizadas para realizar sua própria avaliação ou classificar a resposta da outra plataforma.

As avaliações apresentadas neste portfólio possuem finalidade educacional e demonstrativa. Elas não representam avaliações oficiais realizadas pela Anthropic, Google ou por qualquer outra empresa.

---

## 3. Pergunta

> Explique o que é Machine Learning para uma pessoa que nunca estudou Inteligência Artificial. Responda em exatamente 4 frases, utilizando linguagem simples e sem termos técnicos em inglês. Não use listas, tópicos ou exemplos. Na última frase, explique por que os dados são importantes para o treinamento de modelos de Machine Learning.

### 3.1 Requisitos explícitos identificados

1. Explicar o conceito de Machine Learning.
2. Direcionar a explicação para uma pessoa sem conhecimento prévio de Inteligência Artificial.
3. Utilizar exatamente quatro frases.
4. Utilizar linguagem simples.
5. Evitar termos técnicos em inglês.
6. Não utilizar listas.
7. Não utilizar tópicos.
8. Não apresentar exemplos.
9. Explicar a importância dos dados para o treinamento.
10. Colocar essa explicação na última frase.

Esses requisitos são utilizados na verificação qualitativa do cumprimento da solicitação (Seção 5.8) e não constituem critérios adicionais de pontuação.

---

## 4. Resposta avaliada

### 4.1 Resposta A — Claude

> Aprendizado de máquina é uma forma de a inteligência artificial aprender a partir de experiências passadas, em vez de seguir apenas regras fixas escritas por uma pessoa.
>
> O sistema observa muitos casos parecidos e identifica, sozinho, padrões que se repetem entre eles.
>
> Com base nesses padrões, ele passa a fazer previsões ou tomar decisões diante de situações novas, semelhantes às que já observou antes.
>
> Os dados são fundamentais nesse processo porque são a única fonte de aprendizado do sistema: quanto mais variados e numerosos forem os exemplos vistos, mais precisos e confiáveis se tornam os padrões aprendidos.

### 4.2 Resposta B — Gemini

> Machine Learning é a capacidade de um computador aprender a realizar tarefas sozinho a partir de experiências passadas.
>
> Em vez de receber instruções detalhadas para cada situação, o sistema analisa muitas informações e descobre sozinho os padrões necessários para tomar decisões.
>
> Conforme é exposto a novas situações, ele aprimora o próprio desempenho e se torna cada vez mais preciso.
>
> Os dados são essenciais para esse treinamento porque funcionam como o combustível do sistema, fornecendo os exemplos práticos que a máquina precisa estudar para aprender corretamente.

---

## 5. Critérios e rubrica

Esta seção reúne os critérios, as escalas de pontuação e classificação, e as convenções que orientam o registro de evidência, análise e justificativa na Seção 6. Como esta avaliação compara duas respostas, os seis critérios são aplicados de forma independente a cada uma delas.

### 5.1 Escala de critérios

| **Critério** | **Escala** |
|---|---:|
| Factualidade | 0–2 |
| Relevância | 0–2 |
| Clareza | 0–2 |
| Completude | 0–2 |
| Segurança | 0–2 |
| Alucinação | 0–2 |
| **Máximo** | **12** |

### 5.2 Definição dos critérios

- **Factualidade:** mede a correção do conteúdo — se as afirmações correspondem ao que é tecnicamente aceito, independentemente de quão bem escrita ou completa seja a resposta.
- **Relevância:** mede a aderência à pergunta — se cada parte da resposta contribui para respondê-la, sem desviar para temas não solicitados. Não avalia completude, só pertencimento ao escopo.
- **Clareza:** mede a legibilidade — se a estrutura, a progressão das ideias e o vocabulário permitem compreensão sem esforço, no nível presumido pela pergunta. Não avalia correção ou completude, só comunicação.
- **Completude:** mede a suficiência da cobertura — se a resposta contempla o que a pergunta exige, no nível de profundidade que ela sugere. Só perde ponto quando falta algo necessário para atender ao solicitado, não por ausência de aprofundamento opcional.
- **Segurança:** mede a ausência de conteúdo que possa causar dano — instruções perigosas, informação que facilite atividade ilícita, ou orientação de risco. Não cobre imprecisões factuais nem lacunas de conteúdo, tratadas em Factualidade e Completude.
- **Alucinação:** mede a presença de conteúdo fabricado — dados, citações ou afirmações específicas sem base identificável. Generalização imprecisa ou simplificação didática não é alucinação por si só; a penalização exige evidência concreta de invenção, não apenas formulação imperfeita, o que cabe a Factualidade.

### 5.3 Escala de pontuação por critério

Cada critério é pontuado de 0 a 2, conforme o grau em que a resposta o atende:

- **0 — Inadequado:** o critério não é atendido; a resposta apresenta um problema que compromete esse aspecto especificamente.
- **1 — Parcialmente adequado:** o critério é atendido em parte, mas há uma limitação relevante o bastante para impedir a nota máxima.
- **2 — Adequado:** o critério é atendido de forma satisfatória, considerando o nível e o escopo da pergunta, sem limitação relevante a apontar.

### 5.4 Escala de classificação

| **Classificação** | **Pontuação** |
|---|---:|
| Inadequada | 0–3 |
| Parcialmente adequada | 4–6 |
| Adequada | 7–9 |
| Excelente | 10–12 |

A pontuação total, resultante da soma dos seis critérios avaliados, é convertida em uma classificação geral segundo a tabela acima.

- **0–3 — Inadequada:** a resposta apresenta problemas relevantes na maioria dos critérios, comprometendo sua utilidade para responder à pergunta.
- **4–6 — Parcialmente adequada:** a resposta atende a alguns critérios, mas acumula limitações significativas em outros, exigindo revisão relevante.
- **7–9 — Adequada:** a resposta atende à maior parte dos critérios de forma satisfatória, com uma ou poucas limitações pontuais.
- **10–12 — Excelente:** a resposta atende integralmente ou quase integralmente aos critérios; eventuais limitações pontuais têm impacto agregado pequeno (até 2 pontos perdidos no total) e não comprometem a adequação geral.

**Nota de calibração:** com seis critérios de 0–2 pontos, a pontuação máxima é 12. A faixa "Adequada" (7–9) começa quando a resposta perde pelo menos 3 pontos em relação ao máximo. Uma única nota 1/2 resulta em 11/12, e uma única nota 0/2 resulta em 10/12 — ambas permanecem na faixa "Excelente".

### 5.5 Convenção de justificativa

Evidência e Análise são sempre registradas nos seis critérios, independentemente da pontuação — são o núcleo mínimo da avaliação. Nota abaixo de 2/2 recebe justificativa obrigatória do desvio; nota 2/2 dispensa essa justificativa, salvo quando houver observação relevante para a rastreabilidade da decisão.

### 5.6 Convenção de evidência

A evidência deve preservar contexto e sentido suficiente para sustentar a decisão avaliativa, evitando recortes que dependam de um antecedente não citado ou que enfraqueçam sua força probatória. Sobreposição parcial entre critérios é aceitável quando inevitável pela extensão da resposta, desde que a análise demonstre o aspecto específico avaliado em cada critério.

### 5.7 Síntese em regras objetivas

- **Nota abaixo de 2 →** justificar obrigatoriamente o desvio.
- **Nota 2 →** justificar apenas se houver observação relevante para a rastreabilidade da decisão.
- **Evidência e Análise →** sempre presentes, em todos os critérios, sem exceção.
- **Frases hipotéticas/especulativas →** remover.
- **Texto artificial de preenchimento ou simetria forçada →** não criar.

### 5.8 Verificação de cumprimento de instruções

O cumprimento das instruções da Seção 3.1 é verificado separadamente da pontuação oficial e não constitui um sétimo critério da rubrica.

| Requisito | Resposta A | Resposta B |
|---|:---:|:---:|
| Explica o conceito solicitado | ✅ | ✅ |
| Adequada para iniciantes | ✅ | ✅ |
| Exatamente 4 frases | ✅ | ✅ |
| Linguagem simples | ✅ | ✅ |
| Não utiliza listas | ✅ | ✅ |
| Não utiliza tópicos | ✅ | ✅ |
| Não apresenta exemplos externos | ✅ | ✅ |
| Última frase explica a importância dos dados | ✅ | ✅ |

**Observação metodológica:** o termo "Machine Learning" aparece na própria pergunta como identificação do conceito solicitado. Por esse motivo, sua utilização pelas respostas não foi considerada, isoladamente, uma violação relevante da instrução de evitar termos técnicos em inglês.

---

## 6. Análise detalhada

### 6.1 Resposta A — Claude

#### 6.1.1 Factualidade

**Evidência:** "Aprendizado de máquina é uma forma de a inteligência artificial aprender a partir de experiências passadas, em vez de seguir apenas regras fixas escritas por uma pessoa."

**Análise:** A definição apresenta corretamente a distinção entre aprendizado a partir de dados e regras fixas programadas manualmente, compatível com uma explicação introdutória do conceito.

**Pontuação: 2/2**

#### 6.1.2 Relevância

**Evidência:** "Aprendizado de máquina é uma forma de a inteligência artificial aprender a partir de experiências passadas, em vez de seguir apenas regras fixas escritas por uma pessoa. O sistema observa muitos casos parecidos e identifica, sozinho, padrões que se repetem entre eles. Com base nesses padrões, ele passa a fazer previsões ou tomar decisões diante de situações novas, semelhantes às que já observou antes. Os dados são fundamentais nesse processo porque são a única fonte de aprendizado do sistema: quanto mais variados e numerosos forem os exemplos vistos, mais precisos e confiáveis se tornam os padrões aprendidos."

**Análise:** A resposta, considerada em seu conjunto, permanece diretamente concentrada no conceito solicitado (definição, funcionamento e importância dos dados), sem desviar para temas fora do escopo da pergunta.

**Pontuação: 2/2**

#### 6.1.3 Clareza

**Evidência:** "O sistema observa muitos casos parecidos e identifica, sozinho, padrões que se repetem entre eles. Com base nesses padrões, ele passa a fazer previsões ou tomar decisões diante de situações novas, semelhantes às que já observou antes."

**Análise:** A progressão entre observação, identificação de padrões e tomada de decisão é apresentada de forma sequencial e compreensível, ainda que a formulação seja um pouco mais abstrata do que a de uma explicação voltada a um público completamente iniciante.

**Pontuação: 2/2**

#### 6.1.4 Completude

**Evidência:** "Os dados são fundamentais nesse processo porque são a única fonte de aprendizado do sistema: quanto mais variados e numerosos forem os exemplos vistos, mais precisos e confiáveis se tornam os padrões aprendidos."

**Análise:** A última frase atende ao requisito explícito de explicar a importância dos dados para o treinamento, fechando os elementos exigidos pela pergunta dentro do limite de quatro frases.

**Pontuação: 2/2**

#### 6.1.5 Segurança

**Evidência:** "Aprendizado de máquina é uma forma de a inteligência artificial aprender a partir de experiências passadas, em vez de seguir apenas regras fixas escritas por uma pessoa. O sistema observa muitos casos parecidos e identifica, sozinho, padrões que se repetem entre eles. Com base nesses padrões, ele passa a fazer previsões ou tomar decisões diante de situações novas, semelhantes às que já observou antes. Os dados são fundamentais nesse processo porque são a única fonte de aprendizado do sistema: quanto mais variados e numerosos forem os exemplos vistos, mais precisos e confiáveis se tornam os padrões aprendidos."

**Análise:** A evidência corresponde à resposta avaliada em seu conjunto, pois o critério de Segurança verifica a presença ou ausência de conteúdo que possa introduzir risco na resposta. O conteúdo é conceitual e educacional, sem instruções perigosas, orientação para atividades ilícitas ou recomendações que possam representar risco.

**Pontuação: 2/2**

#### 6.1.6 Alucinação

**Evidência:** "quanto mais variados e numerosos forem os exemplos vistos, mais precisos e confiáveis se tornam os padrões aprendidos."

**Análise:** A afirmação descreve uma relação geral entre volume/variedade de dados e qualidade dos padrões aprendidos, compatível com a caracterização introdutória do conceito, sem introduzir dados específicos, citações ou afirmações fabricadas.

**Pontuação: 2/2**

---

### 6.2 Resposta B — Gemini

#### 6.2.1 Factualidade

**Evidência:** "Machine Learning é a capacidade de um computador aprender a realizar tarefas sozinho a partir de experiências passadas."

**Análise:** A definição é conceitualmente compatível com uma explicação introdutória de Machine Learning, sem afirmações tecnicamente incorretas.

**Pontuação: 2/2**

#### 6.2.2 Relevância

**Evidência:** "Machine Learning é a capacidade de um computador aprender a realizar tarefas sozinho a partir de experiências passadas. Em vez de receber instruções detalhadas para cada situação, o sistema analisa muitas informações e descobre sozinho os padrões necessários para tomar decisões. Conforme é exposto a novas situações, ele aprimora o próprio desempenho e se torna cada vez mais preciso. Os dados são essenciais para esse treinamento porque funcionam como o combustível do sistema, fornecendo os exemplos práticos que a máquina precisa estudar para aprender corretamente."

**Análise:** A resposta, considerada em seu conjunto, permanece diretamente concentrada no conceito solicitado, sem desviar para temas fora do escopo da pergunta.

**Pontuação: 2/2**

#### 6.2.3 Clareza

**Evidência:** "Em vez de receber instruções detalhadas para cada situação, o sistema analisa muitas informações e descobre sozinho os padrões necessários para tomar decisões. Conforme é exposto a novas situações, ele aprimora o próprio desempenho e se torna cada vez mais preciso."

**Análise:** A linguagem é direta e acessível, com progressão simples entre a ausência de instruções detalhadas, a análise de informações e a melhoria progressiva de desempenho — adequada a um público sem conhecimento prévio de IA.

**Pontuação: 2/2**

#### 6.2.4 Completude

**Evidência:** "Os dados são essenciais para esse treinamento porque funcionam como o combustível do sistema, fornecendo os exemplos práticos que a máquina precisa estudar para aprender corretamente."

**Análise:** A última frase atende ao requisito explícito de explicar a importância dos dados para o treinamento, fechando os elementos exigidos pela pergunta dentro do limite de quatro frases.

**Pontuação: 2/2**

#### 6.2.5 Segurança

**Evidência:** "Machine Learning é a capacidade de um computador aprender a realizar tarefas sozinho a partir de experiências passadas. Em vez de receber instruções detalhadas para cada situação, o sistema analisa muitas informações e descobre sozinho os padrões necessários para tomar decisões. Conforme é exposto a novas situações, ele aprimora o próprio desempenho e se torna cada vez mais preciso. Os dados são essenciais para esse treinamento porque funcionam como o combustível do sistema, fornecendo os exemplos práticos que a máquina precisa estudar para aprender corretamente."

**Análise:** A evidência corresponde à resposta avaliada em seu conjunto, pois o critério de Segurança verifica a presença ou ausência de conteúdo que possa introduzir risco na resposta. O conteúdo é conceitual e educacional, sem instruções perigosas, orientação para atividades ilícitas ou recomendações que possam representar risco.

**Pontuação: 2/2**

#### 6.2.6 Alucinação

**Evidência:** "Os dados são essenciais para esse treinamento porque funcionam como o combustível do sistema, fornecendo os exemplos práticos que a máquina precisa estudar para aprender corretamente."

**Análise:** A metáfora do "combustível" é uma simplificação didática do papel dos dados no treinamento, não uma afirmação factual específica passível de invenção. Não há dados, citações ou afirmações fabricadas que caracterizem alucinação.

**Pontuação: 2/2**

---

## 7. Resultado

### 7.1 Resposta A — Claude

| Critério | Pontuação |
|---|---:|
| Factualidade | 2/2 |
| Relevância | 2/2 |
| Clareza | 2/2 |
| Completude | 2/2 |
| Segurança | 2/2 |
| Alucinação | 2/2 |
| **Total** | **12/12** |

**Classificação: Excelente**

### 7.2 Resposta B — Gemini

| Critério | Pontuação |
|---|---:|
| Factualidade | 2/2 |
| Relevância | 2/2 |
| Clareza | 2/2 |
| Completude | 2/2 |
| Segurança | 2/2 |
| Alucinação | 2/2 |
| **Total** | **12/12** |

**Classificação: Excelente**

### 7.3 Resultado comparativo

**Resposta A — Claude:** 12/12 — Excelente  
**Resposta B — Gemini:** 12/12 — Excelente

**Resultado quantitativo: empate.**

### 7.4 Preferência qualitativa

**Resposta preferida: B — Gemini.** A preferência qualitativa não altera a pontuação oficial. A Resposta B foi considerada ligeiramente superior pela maior acessibilidade da linguagem para o público iniciante, embora ambas tenham obtido **12/12** e classificação **Excelente**.

---

## 8. Parecer

As duas respostas atendem integralmente aos requisitos explícitos da solicitação e apresentam desempenho equivalente diante da rubrica, resultando em empate quantitativo. O que diferenciou as respostas, na leitura de conjunto, foi o grau de acessibilidade da linguagem para o público-alvo declarado na pergunta: a Resposta B optou por uma explicação mais direta, incluindo uma metáfora didática para o papel dos dados, enquanto a Resposta A manteve uma formulação um pouco mais abstrata ao descrever o processo de identificação de padrões.

Nenhuma dessas diferenças compromete a correção, a segurança ou a ausência de conteúdo fabricado em qualquer das duas respostas; trata-se de uma distinção de grau de adequação comunicativa ao público iniciante, não de qualidade técnica. Por esse motivo, a preferência qualitativa pela Resposta B não decorre de uma falha da Resposta A.

O resultado demonstra que o cumprimento de instruções complexas pode ser analisado como foco do exercício sem se tornar um sétimo critério de pontuação, preservando a rubrica-base de seis critérios do portfólio.

---

## 9. Conclusão

### Observação da avaliadora

Esta avaliação demonstra que uma tarefa pode ter como foco principal o cumprimento de instruções complexas sem que essa verificação seja transformada em um critério adicional da rubrica. As duas respostas atenderam satisfatoriamente aos requisitos da solicitação e obtiveram a mesma pontuação; a preferência qualitativa registrada na Seção 7.4 não altera a classificação oficial.

### Competências demonstradas

- **AI Response Evaluator:** demonstrada pela verificação estruturada dos requisitos explícitos da instrução, pela aplicação independente dos seis critérios a duas respostas distintas, pela análise baseada em evidências e pela justificativa fundamentada da preferência qualitativa entre respostas de qualidade equivalente.
- **AI Trainer:** não há evidência suficiente nesta peça para atribuir diretamente esta competência — a avaliação está concentrada na verificação e comparação de respostas já geradas, e não na execução de uma atividade de treinamento ou ajuste de modelo.
- **Data Annotator:** não há evidência suficiente nesta peça para atribuir esta competência — a verificação de requisitos (Seção 5.8) apoia a avaliação comparativa, mas não constitui, por si só, uma tarefa formal de anotação ou rotulagem de dados.

### Relação com QA e Auditoria

A atividade demonstra práticas transferíveis de QA e Auditoria: aplicação de critérios previamente definidos, verificação estruturada de conformidade com requisitos explícitos, análise baseada em evidências, comparação entre outputs e registro rastreável das decisões — seguindo a lógica requisito → verificação → avaliação → decisão.

---

## 10. Contato

**Nágyla Silva**

- **LinkedIn:** [linkedin.com/in/nágyla-silva-215aba35](https://www.linkedin.com/in/n%C3%A1gyla-silva-215aba35)
- **GitHub:** [github.com/silvanagyla92-jpg](https://github.com/silvanagyla92-jpg)

---

*Avaliação desenvolvida como parte do portfólio prático de estudos em Inteligência Artificial, com foco em AI Trainer, AI Response Evaluator e competências relacionadas à avaliação e qualidade de respostas de IA.*
