# 004 — Agentes de IA

## Objetivo

Apresentar o conceito de agentes de Inteligência Artificial e explicar como modelos de linguagem podem ser integrados a memória, ferramentas, planejamento e mecanismos de execução para realizar tarefas com diferentes níveis de autonomia.

## O que é um agente de IA

Um agente de IA é um sistema projetado para executar tarefas ou atingir objetivos utilizando informações disponíveis, processos de decisão e, em muitos casos, ferramentas externas. Em aplicações modernas, grandes modelos de linguagem podem atuar como componente central de agentes que interpretam instruções e coordenam ações.

Um agente não deve ser confundido simplesmente com um chatbot. Um chatbot pode apenas produzir respostas textuais, enquanto um sistema agêntico pode ser projetado para planejar etapas, consultar fontes, chamar ferramentas e executar ações dentro das permissões definidas.

## Componentes conceituais

### Modelo

O modelo de linguagem pode interpretar instruções, analisar informações e produzir decisões ou planos intermediários.

### Memória

Sistemas agênticos podem utilizar memória de curto ou longo prazo para manter informações relevantes entre etapas ou interações. A implementação e o significado de "memória" variam conforme a arquitetura.

### Ferramentas

Ferramentas permitem que o agente interaja com sistemas externos, como APIs, bases de dados, mecanismos de busca ou funções de software. A chamada de ferramentas amplia as capacidades do sistema além da geração de texto.

### Planejamento

Em tarefas complexas, o sistema pode decompor um objetivo em etapas, selecionar ações e utilizar resultados intermediários para decidir o próximo passo.

### Execução e observação

Depois de realizar uma ação, o agente pode receber um resultado e utilizá-lo para ajustar o fluxo de trabalho. Esse ciclo pode continuar até que a tarefa seja concluída, interrompida ou encaminhada para intervenção humana.

## Fluxo simplificado

```text
Objetivo / instrução
        ↓
Interpretação e planejamento
        ↓
Escolha de ferramenta ou ação
        ↓
Execução
        ↓
Observação do resultado
        ↓
Novo planejamento ou conclusão
```

## Autonomia não significa ausência de controle

A autonomia de um agente depende das permissões, ferramentas, políticas e limites definidos para o sistema. Um agente que pode consultar uma base de dados não necessariamente possui permissão para alterá-la; um agente que pode executar uma função não necessariamente deve executá-la sem confirmação.

Por isso, segurança, controle de acesso, monitoramento e possibilidade de intervenção humana são aspectos importantes no desenvolvimento e na avaliação de agentes.

## Agentes e RAG

Agentes podem utilizar RAG como uma das ferramentas de recuperação de informação. Em uma arquitetura agêntica, o sistema pode decidir quais fontes consultar, dividir uma tarefa em etapas e combinar informações recuperadas antes de produzir uma resposta ou executar uma ação.

Isso não significa que todo sistema RAG seja um agente ou que todo agente utilize RAG. São conceitos relacionados, mas distintos.

## Relação com avaliação

Avaliar agentes exige considerar não apenas a resposta final, mas também o comportamento do fluxo de trabalho. Dependendo da tarefa, podem ser avaliados seleção de ferramentas, uso das informações recuperadas, cumprimento de restrições, segurança das ações e qualidade do resultado final.

## Pontos para verificação em avaliações

- A resposta diferencia agente de simples geração de texto?
- O papel das ferramentas foi explicado corretamente?
- A autonomia é apresentada como dependente de permissões e arquitetura?
- A relação entre agentes e RAG é descrita sem confundir os conceitos?
- São considerados segurança, controle e possibilidade de intervenção?

## Fontes

- [IBM Think — O que são agentes de IA?](https://www.ibm.com/br-pt/think/topics/ai-agents)
- [IBM Think — RAG agêntica](https://www.ibm.com/br-pt/think/topics/agentic-rag)
- [IBM Think — AI Agent Use Cases](https://www.ibm.com/think/topics/ai-agent-use-cases)
- [Microsoft Learn — Azure AI](https://learn.microsoft.com/azure/ai-services/)

**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
