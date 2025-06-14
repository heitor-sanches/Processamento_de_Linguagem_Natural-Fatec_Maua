# Processamento de Linguagem-Natural - Fatec Mauá

## Aula 02 - Python e Bibliotecas de PLN
Descrição: Introdução ao Python aplicado ao PLN.

Objetivo: Demonstrar conceitos fundamentais da linguagem Python para aplicações básicas do PLN.

Técnicas: Sintaxe e estrutura, variáveis, operadores, manipulação de strings, laços de repetição e outros.

Observações: Demonstra o setup do ambiente e primeiros contatos com dados textuais.

## Aula 03 - Processamento de Texto
Descrição: Processamento e pré-processamento de dados textuais.

Objetivo: Ensinar como limpar, normalizar e preparar textos para análises futuras.

Técnicas: Remoção de pontuação, lematização, remoção de stopwords, tokenização e stemming.

Observações: Mostrar a importância do pré-processamento para o desempenho de modelos.

## Aula 04 - Extração de Características em Texto
Descrição: Transformação de texto em representações numéricas.

Objetivo: Aplicar técnicas de vetorização para análise automática.

Técnicas: BOW, TF-IDF, WordEmbedding.

Observações: Explica como transformar dados textuais em dados estruturados para Machine Learning.

## Aula 05 - Análise Sintática
Descrição: Estudo das relações gramaticais entre palavras.

Objetivo: Analisar a estrutura interna das sentenças.

Técnicas: Part-of-Speech Tagging (POS), parsing de dependências.

Observações: Utilização do SpaCy para análise sintática profunda.

## Aula 06 - Análise Semântica
Descrição: Análise do significado dos textos.

Objetivo: Explorar o sentido e as relações semânticas entre palavras.

Técnicas: WordNet, Similaridade Semântica.

Observações: Demonstra como medir similaridade entre palavras e conceitos.

## Aula 07 - Descoberta de Conhecimento
Descrição: Extração de informações e padrões ocultos.

Objetivo: Identificar tópicos ou informações relevantes em grandes volumes de texto.

Técnicas: WordCloud, análise de frequência, mineração de texto.

Observações: Apresenta visualizações para melhor interpretação dos dados.

## Aula 10 - Análise de Sentimentos e Classificação de Textos
Descrição: Aplicações e técnicas de análise de sentimentos em textos curtos.

Objetivo: Demonstrar como classificar sentimentos utilizando algoritmos de aprendizado de máquina.

Técnicas: Utilização da biblioteca NLTK com VADER, classificação com Naive Bayes e Árvores de Decisão, análise de polaridade e pontuação composta.

Observações: Apresenta exemplos práticos com textos fictícios e avaliações de filmes, destacando o uso de modelos supervisionados e léxicos para identificação de sentimentos.

## Aula 11 - Pipeline de Classificação de Texto
Descrição: Construção de um pipeline completo para classificação de textos com técnicas de PLN.

Objetivo: Aplicar os conceitos de Processamento de Linguagem Natural (PLN) para construir um pipeline completo de classificação de texto.

Técnicas: Limpeza, tokenização, remoção de stopwords, stemming/lemmatização, vetorização com Bag of Words, TF-IDF e Word Embeddings; classificação com modelos supervisionados e avaliação com métricas como precisão e F1-score.

Observações: O notebook enfatiza a comparação entre diferentes técnicas de representação textual e modelos, promovendo a análise crítica sobre desempenho e aplicação prática.

## Aula 12 - Teste do Modelo com Novas Frases
Descrição: Avaliação do desempenho do modelo de classificação de sentimentos usando frases inéditas.

Objetivo: Implementar uma Rede Neural Recorrente (RNN) simples em Python para prever a próxima palavra em uma sequência de texto, utilizando a biblioteca TensorFlow/Keras e implementar uma Rede Long Short-Term Memory (LSTM) em Python para classificar o sentimento de frases como "positivo" ou "negativo", utilizando a biblioteca TensorFlow/Keras.

Técnicas: Tokenização de entrada, padding de sequência, inferência com modelo LSTM, interpretação de probabilidades, mapeamento de classes.

Observações: Ressaltar que erros de previsão podem indicar limitações no vocabulário, dados de treino insuficientes ou desequilíbrio nas classes. Mostrar como diagnósticos (como inspeção de probabilidades e vocabulário) ajudam a melhorar a performance.

## Projeto 01 - Análise Quantitativa de Corpus
Descrição: Análise exploratória de corpus textual.

Objetivo: Levantar estatísticas básicas como contagem de palavras e tokens únicos.

Técnicas: mineração de dados, extração da informação, cálculos de relevância de palavras.

Observações: Gerar elementos para discutir criticamente os resultados obtidos.

## Projeto 02 - Análise de Estatística Descritiva
Descrição: Análise estatística aplicada a textos.

Objetivo: Aplicar conceitos de estatística em características de textos (média de palavras, dispersão etc.).

Técnicas: Mineração de Texto e calculos estatísticos.

Observações: Complementa a análise quantitativa do Projeto 01 com visão estatística.

## Projeto 03 - Análise de Relevância de Termos
Descrição: Identificação dos termos mais importantes em textos.

Objetivo: Avaliar relevância de palavras para análise e classificação.

Técnicas: TF-IDF, análise de frequências.

Observações: Mostra como ranquear palavras por importância relativa dentro de um corpus.
