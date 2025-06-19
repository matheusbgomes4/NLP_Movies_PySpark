# 🎬 Análise de Sentimentos com PySpark e NLP

Este projeto utiliza **técnicas de Processamento de Linguagem Natural (NLP)** com **PySpark** para classificar sentimentos (positivos ou negativos) de resenhas de filmes. O projeto foi desenvolvido com base prática, simulando um cenário real de análise de dados textuais em larga escala.

---

## 📌 Objetivo

Classificar automaticamente resenhas de filmes como **positivas ou negativas**, a partir do texto, utilizando algoritmos de NLP combinados com **Árvore de Decisão** no PySpark.

---

## 🛠️ Tecnologias Utilizadas

- Python
- PySpark
- NLP (Processamento de Linguagem Natural)
- TF-IDF
- Bag of Words
- DecisionTreeClassifier

---

## 📁 Estrutura do Notebook

### 🧼 1. Limpeza e Processamento
- Remoção de caracteres especiais com expressões regulares
- Tokenização das palavras
- Remoção de StopWords

### 🧠 2. Vetorização
- Construção do modelo Bag of Words
- Aplicação de TF-IDF para calcular a relevância das palavras

### 🌲 3. Modelagem
- Ajuste de uma Árvore de Decisão com os dados vetorizados
- Divisão entre treino e teste
- Avaliação com métricas de acurácia

### 📊 4. Interpretação dos Resultados
- Análise do desempenho do modelo
- Observações sobre overfitting, relevância das palavras e interpretação dos vetores

---

## 🔍 Exemplo de Dados

| Resenha                                   | Sentimento |
|------------------------------------------|------------|
| "Gostei muito do filme, ótimo roteiro!"  | Positivo   |
| "Filme fraco, final decepcionante."      | Negativo   |

---
