# 002 — Grandes Modelos de Linguagem (LLMs)

## Objetivo

Explicar, em nível conceitual, o que são Grandes Modelos de Linguagem (LLMs), como são treinados e utilizados e quais limitações precisam ser consideradas na avaliação de suas respostas.

## O que é um LLM

Um Grande Modelo de Linguagem é um modelo de aprendizado profundo treinado em grandes quantidades de dados para processar e gerar linguagem natural. Modelos desse tipo aprendem padrões estatísticos e relações presentes nos dados de treinamento e utilizam esses padrões para produzir saídas a partir de uma entrada.

A expressão "modelo de linguagem" não significa que o sistema possui compreensão humana. Uma explicação de qualidade deve evitar antropomorfizar o modelo e deve diferenciar geração estatística de conceitos humanos como consciência, intenção ou experiência subjetiva.

## Tokens e contexto

Antes de processar uma entrada textual, o conteúdo é dividido em unidades chamadas tokens. O modelo processa essas unidades dentro de uma janela de contexto, que limita a quantidade de informação considerada em uma determinada interação.

O tamanho da janela de contexto é importante porque determina quanto conteúdo pode estar disponível para o modelo durante uma geração. Isso não significa, porém, que todo conteúdo dentro da janela receberá a mesma relevância.

## Treinamento

Durante o treinamento, o modelo ajusta seus parâmetros para reduzir erros de previsão em relação ao objetivo definido. Em modelos de linguagem, uma tarefa central é prever tokens em sequências de texto. O treinamento envolve grandes conjuntos de dados e procedimentos de otimização computacionalmente intensivos.

## Inferência e geração

Na inferência, o modelo recebe uma entrada e gera uma saída token por token, considerando o contexto disponível e as configurações utilizadas. O resultado não deve ser interpretado automaticamente como uma consulta a uma base de fatos perfeita.

## Limitações relevantes

LLMs podem produzir respostas plausíveis, mas incorretas. Esse fenômeno é frequentemente chamado de alucinação. Também podem reproduzir vieses presentes nos dados ou apresentar desempenho desigual entre tarefas e contextos.

Por isso, a avaliação de uma resposta deve considerar factualidade, relevância, clareza, completude, segurança e sinais de conteúdo fabricado, além de verificar se a resposta cumpriu as instruções recebidas.

## Relação com avaliação de respostas

Um avaliador precisa separar três perguntas diferentes: a resposta está correta? A resposta atende ao que foi solicitado? A resposta apresenta riscos ou conteúdo inventado? Essa separação evita que uma resposta bem escrita receba uma nota alta apenas por parecer convincente.

## Pontos para verificação em avaliações

- A explicação define LLM sem antropomorfização indevida?
- O papel dos dados de treinamento foi descrito corretamente?
- A resposta diferencia treinamento de inferência?
- A resposta evita afirmar que o modelo possui conhecimento perfeito?
- Limitações como alucinação e viés são tratadas de forma conceitualmente adequada?

## Fontes

- [IBM Think — O que é LLM?](https://www.ibm.com/br-pt/think/topics/large-language-models)
- [Hugging Face Learn](https://huggingface.co/learn)
- [Google Cloud — AI](https://cloud.google.com/ai)

**Autor:** Nágyla Silva

*Projeto integrado do portfólio prático de estudos em Inteligência Artificial, com foco em engenharia de prompts, avaliação crítica de respostas de IA e desenvolvimento de competências para AI Trainer, AI Response Evaluator e Data Annotator.*
