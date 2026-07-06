# 🏆 Brasileirão Série A | Machine Learning & Analytics

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-Acadêmico-lightgrey)

</p>

---

# ⚽ Quando o apito inicial é dado, os dados entram em campo.

Imagine um estádio lotado.

A torcida canta.

O juiz apita.

A bola rola.

Durante noventa minutos acontecem milhares de eventos: passes, finalizações, cartões, gols, vitórias e derrotas.

Para um torcedor, tudo isso representa emoção.

Para um cientista de dados, representa informação.

Este projeto transforma temporadas inteiras do Campeonato Brasileiro Série A em conhecimento, utilizando Estatística, Análise Exploratória de Dados e Machine Learning para compreender quais fatores influenciam o resultado das partidas.

---

# 🎯 Objetivo

Desenvolver um MVP aplicando todas as etapas fundamentais de um projeto de Ciência de Dados:

* entendimento do problema;
* análise exploratória;
* estatística descritiva;
* pré-processamento;
* engenharia de atributos;
* treinamento de modelos;
* otimização;
* avaliação dos resultados.

---

# 🏟 Dataset

Base histórica do Campeonato Brasileiro Série A.

**Fonte**

https://raw.githubusercontent.com/Renata-Correa/Sprint_Machine_Learning_e_Analytics/refs/heads/main/campeonato-brasileiro-full.csv

---

# ❓ Pergunta do Projeto

> **É possível identificar padrões históricos capazes de explicar e prever o resultado de uma partida do Campeonato Brasileiro?**

---

# 🧠 Hipóteses

✔ O fator casa influencia os resultados.

✔ Times mais ofensivos vencem mais partidas.

✔ Defesas consistentes apresentam melhor desempenho.

✔ Modelos de Machine Learning conseguem aprender esses padrões.

---

# 📚 Estrutura do Projeto

```text
📂 Brasileirao-ML

│
├── notebooks/
│   ├── Parte_1_EDA.ipynb
│   ├── Parte_2_Preprocessamento.ipynb
│   ├── Parte_3_Modelagem.ipynb
│   ├── Parte_4_Otimizacao.ipynb
│   └── Parte_5_Resultados.ipynb
│
├── outputs/
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# ⚙ Tecnologias

* Python

* Pandas

* NumPy

* Matplotlib

* Seaborn

* Scikit-Learn

* Google Colab

---

# 📊 Etapas do Projeto

## ⚽ Primeiro Tempo - Conhecendo o Campeonato

Nesta etapa foi realizado o entendimento dos dados.

Foram analisados:

* estrutura do dataset;
* atributos;
* estatísticas descritivas;
* qualidade dos dados;
* valores ausentes;
* primeiras visualizações.

---

## 🧹 Intervalo - Preparando o Time

Antes da modelagem foi necessário preparar os dados.

Foram realizadas:

* limpeza;
* criação de novas variáveis;
* codificação;
* seleção de atributos;
* preparação para Machine Learning.

---

## 🤖 Segundo Tempo - Machine Learning

Quatro modelos foram treinados:

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting

Todos foram comparados utilizando métricas de classificação.

---

## 🏆 Prorrogação - Otimização

O melhor modelo foi refinado utilizando:

* GridSearchCV
* Cross Validation

Buscando a melhor combinação de hiperparâmetros.

---

## 🥇 Apito Final - Avaliação

Os modelos foram avaliados utilizando:

* Accuracy
* Precision
* Recall
* F1-score
* Matriz de Confusão

---

# 📈 Principais Insights

📍 O fator casa apresentou influência significativa.

📍 Times ofensivos tendem a vencer mais, porém o ataque isoladamente não explica o resultado.

📍 Defesas sólidas apresentaram comportamento mais consistente.

📍 O Machine Learning conseguiu aprender padrões relevantes presentes nos dados históricos.

---

# 📊 Fluxo do Projeto

```text
Problema
      │
      ▼
Carga dos Dados
      │
      ▼
Análise Exploratória
      │
      ▼
Pré-processamento
      │
      ▼
Feature Engineering
      │
      ▼
Machine Learning
      │
      ▼
GridSearchCV
      │
      ▼
Avaliação
      │
      ▼
Conclusões
```

---

# 🚀 Próximos Passos

O projeto pode evoluir incorporando:

* desempenho dos últimos cinco jogos;
* ranking dos clubes;
* saldo de gols acumulado;
* posição na tabela;
* estatísticas como mandante e visitante;
* XGBoost;
* LightGBM;
* Dashboard em Streamlit.

---

# 🎓 Objetivo Acadêmico

Projeto desenvolvido como requisito da disciplina de **Machine Learning & Analytics** da Pós-Graduação em Ciência de Dados.

---

# 👩‍💻 Autora

**Renata Corrêa**

*"No futebol, uma temporada termina quando o juiz apita.*

*Na Ciência de Dados, cada resultado encontrado marca apenas o início da próxima descoberta."*
