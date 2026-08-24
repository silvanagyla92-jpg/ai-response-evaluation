# Platform Practice

## 1. Objetivo

A pasta **platform-practice** reúne registros de estudo, exploração e prática em ambientes relacionados à avaliação de respostas, treinamento de sistemas de IA, anotação de dados e comparação de modelos.

O objetivo é transformar o uso de plataformas em **evidência documentada de aprendizagem**, sem confundir estudo independente com experiência profissional. Cada atividade deve registrar apenas aquilo que foi efetivamente realizado e que pode ser sustentado por evidências.

## 2. Por que praticar em diferentes plataformas

Ambientes distintos podem apresentar tarefas, interfaces, guidelines e formas de avaliação diferentes. Compará-los ajuda a desenvolver competências transferíveis, como:

- seguir instruções e critérios;
- identificar erros factuais e inconsistências;
- comparar respostas de modelos;
- classificar e rotular dados;
- justificar decisões com evidências;
- revisar o próprio trabalho;
- reconhecer limitações de uma avaliação;
- manter consistência entre itens semelhantes.

A prática deve ser entendida como complemento às avaliações estruturadas existentes em `evaluations/` e aos fundamentos documentados em `conceitos-explicados/`.

## 3. Plataformas registradas

### DataAnnotation

Ambiente associado a tarefas de anotação, avaliação e treinamento de dados para sistemas de IA. Neste projeto, o foco documental deve permanecer em competências observáveis, como classificação, aplicação de critérios e avaliação de respostas.

### Outlier

Plataforma voltada a projetos relacionados ao desenvolvimento e treinamento de sistemas de IA. Os registros deste repositório devem distinguir claramente informações públicas sobre a plataforma de qualquer atividade efetivamente realizada pela autora.

### Hugging Face

Ecossistema que disponibiliza modelos, datasets, bibliotecas e materiais educacionais. O curso oficial aborda Transformers, LLMs, Datasets, Tokenizers, fine-tuning, avaliação e curadoria de dados. citeturn0search3turn0search2

### LMSYS Chatbot Arena

Ambiente de comparação de modelos de linguagem por meio de batalhas lado a lado e avaliações humanas. O projeto FastChat, mantido pela LMSYS, documenta a infraestrutura e os recursos de avaliação associados ao Arena. citeturn0search1turn0search4

## 4. Processo recomendado de documentação

```text
Objetivo da atividade
        ↓
Instrução / guideline
        ↓
Análise do item
        ↓
Aplicação dos critérios
        ↓
Decisão ou anotação
        ↓
Revisão
        ↓
Evidência e justificativa
        ↓
Registro final
```

Sempre que possível, um registro deve informar: plataforma, objetivo, tipo de tarefa, instruções relevantes, critérios utilizados, decisão, evidência, dificuldades, limitações e aprendizado obtido.

## 5. Relação com avaliação de respostas

A prática em plataformas complementa a metodologia do projeto. Uma avaliação de qualidade deve separar a **instrução recebida**, a **resposta observada**, os **critérios aplicados** e a **decisão final**.

Em comparações A/B, a preferência deve ser fundamentada na qualidade relativa das respostas e não simplesmente em tamanho, estilo ou preferência pessoal. Materiais da LMSYS mostram explicitamente abordagens de avaliação pareada e preocupação com critérios de qualidade e imparcialidade. citeturn0search6turn0search0

## 6. Relação com QA e Auditoria

O fluxo praticado é compatível com princípios transferíveis de QA e auditoria:

**requisito → verificação → evidência → identificação de desvio → decisão → registro**

Isso favorece consistência, rastreabilidade e revisão posterior das decisões.

## 7. Confidencialidade e publicação

Não devem ser publicados dados pessoais, credenciais, tarefas privadas, informações de clientes, materiais internos ou conteúdo protegido que não possa ser redistribuído. Screenshots devem ser revisados antes da publicação e, quando necessário, anonimizados.

## 8. Fontes confiáveis

- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Hugging Face — Datasets](https://huggingface.co/docs/datasets/index)
- [Hugging Face — Transformers](https://huggingface.co/docs/transformers/index)
- [LMSYS FastChat](https://github.com/lm-sys/FastChat)
- [LMSYS Chatbot Arena / documentação](https://github.com/lm-sys/FastChat/blob/main/docs/arena.md)
- [DataAnnotation](https://www.dataannotation.tech/)
- [Outlier](https://outlier.ai/)

As características e políticas das plataformas podem mudar. Informações operacionais devem ser conferidas diretamente nas páginas oficiais no momento da atividade.

## 9. Estrutura

```text
platform-practice/
├── README.md
├── dataannotation/
│   └── README.md
├── outlier/
│   └── README.md
├── hugging-face/
│   └── README.md
└── lmsys-chatbot-arena/
    └── README.md
```

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
