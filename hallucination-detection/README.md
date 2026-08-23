# Hallucination Detection

## 1. Objetivo

Esta seção apresenta uma metodologia para identificar **informações incorretas, inventadas, não sustentadas ou apresentadas com confiança indevida** por sistemas de Inteligência Artificial.

O foco não é penalizar toda imprecisão como alucinação. A análise deve distinguir erro factual, omissão, simplificação didática, interpretação inadequada e fabricação de conteúdo.

## 2. O que é uma alucinação

No contexto de IA generativa, o termo alucinação é usado para descrever uma saída que contém informação que não corresponde adequadamente aos fatos ou às evidências disponíveis. Um modelo pode produzir uma resposta linguisticamente convincente sem possuir uma base factual suficiente para aquela afirmação.

Por isso, fluência não deve ser utilizada como prova de verdade.

## 3. Categorias de problemas

| Categoria | Característica |
|---|---|
| Erro factual | A afirmação contradiz informação verificável. |
| Informação não sustentada | A resposta apresenta um detalhe sem evidência suficiente. |
| Fonte fabricada | Citação, estudo ou link não identificável é apresentado como real. |
| Precisão falsa | Número, data ou nome específico é inventado ou incorreto. |
| Simplificação | A explicação reduz complexidade sem necessariamente fabricar informação. |
| Omissão | Algo necessário para a tarefa não foi informado. |

## 4. Processo de verificação

```text
Afirmação da resposta
        ↓
Identificar o que precisa ser verificado
        ↓
Localizar fonte confiável
        ↓
Comparar afirmação e evidência
        ↓
Classificar o resultado
        ↓
Registrar evidência e decisão
```

Quando a afirmação depender de informação atual, a fonte deve ser recente e adequada ao tema. Para conceitos técnicos, documentação oficial, artigos acadêmicos e materiais institucionais são preferíveis a fontes sem autoria identificável.

## 5. Evidência

Uma avaliação robusta deve registrar a afirmação relevante e a evidência que permite classificá-la. Não basta afirmar que algo "parece falso".

Quando não for possível confirmar uma informação, o avaliador deve registrar a limitação em vez de transformar incerteza em certeza.

## 6. Fontes e citações

A existência de uma citação não garante sua validade. Deve-se verificar se a fonte existe, se realmente sustenta a afirmação e se foi representada corretamente.

Da mesma forma, uma resposta sem citação não é automaticamente uma alucinação. Muitas afirmações gerais podem ser avaliadas pelo conhecimento consolidado, enquanto afirmações específicas exigem verificação mais cuidadosa.

## 7. Relação com LLMs

Grandes modelos de linguagem aprendem padrões a partir de grandes conjuntos de dados e geram saídas a partir do contexto disponível. A documentação da Hugging Face apresenta LLMs e transformadores como sistemas capazes de executar diversas tarefas de linguagem, mas também destaca a necessidade de compreender limitações e avaliação. [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

## 8. Alucinação em RAG

RAG pode fornecer contexto externo ao modelo, mas não transforma automaticamente a geração em resposta correta. A documentação da Microsoft ressalta que a qualidade do RAG depende da preparação do conteúdo, recuperação relevante, limites de contexto, segurança e governança. [Microsoft Learn — RAG e IA generativa](https://learn.microsoft.com/pt-br/azure/search/retrieval-augmented-generation-overview)

Portanto, uma avaliação de RAG deve separar **qualidade da recuperação** e **qualidade da geração**.

## 9. Checklist do avaliador

- A afirmação é verificável?
- Existe fonte confiável?
- A fonte realmente sustenta a afirmação?
- O modelo apresentou detalhe específico sem base?
- Há número, data, nome ou citação suspeita?
- A resposta transforma incerteza em certeza?
- O problema é alucinação ou apenas incompletude?
- A informação está atualizada para a data da avaliação?

## 10. Relação com QA e Auditoria

A detecção de alucinações exige rastreabilidade, comparação com critérios e documentação de evidências. O processo se aproxima de auditoria porque a conclusão deve poder ser revisada por outra pessoa.

## 11. Fontes de estudo

- [Hugging Face — LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)
- [Microsoft Learn — RAG e IA generativa](https://learn.microsoft.com/pt-br/azure/search/retrieval-augmented-generation-overview)
- [IBM — Guia de Inteligência Artificial](https://www.ibm.com/think/topics/ai-guide)

---

**Projeto:** Avaliação de Resposta de IA

**Autora:** Nágyla Silva

Projeto integrante do portfólio prático em Inteligência Artificial, desenvolvido para demonstrar competências em treinamento e avaliação de sistemas de IA, análise crítica de respostas e anotação de dados, aplicadas às funções de AI Trainer, AI Response Evaluator e Data Annotator, com base em experiência em QA e Auditoria.
