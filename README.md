# 🎮 Previsão de Churn em Jogos Online com Machine Learning

## 🔖 Visão Geral

Este projeto tem como objetivo identificar jogadores com alto risco de abandono (churn) em um jogo online, utilizando técnicas de análise de dados e machine learning.

## 📊 Objetivo do Projeto

Antecipar quais jogadores estão propensos a abandonar o jogo com base em seu comportamento dentro da plataforma, permitindo a empresas do setor de games desenvolverem estratégias de retenção personalizadas.

## 💡 Pergunta de Negócio

> “Com base no comportamento do jogador, é possível prever se ele está prestes a abandonar o jogo?”

## 📂 Fonte dos Dados

Os dados foram simulados com `NumPy` e `Pandas` para representar cenários realistas de comportamento de jogadores. A base inclui:

* `user_id`
* `play_time`: tempo total de jogo (horas)
* `sessions`: número de sessões jogadas
* `days_since_last_login`: dias desde o último login
* `level`: nível atual do jogador
* `in_game_purchases`: número de compras in-game
* `churned`: 1 se o jogador abandonou, 0 se está ativo

## 🛠️ Tecnologias e Ferramentas

* Python (Pandas, NumPy)
* Visualização: Matplotlib, Seaborn
* Machine Learning: Scikit-learn
* Jupyter Notebook

## 📐 Etapas do Projeto

1. **Definição do Problema**
2. **Simulação de Base de Dados Realista**
3. **Análise Exploratória de Dados (EDA)**
4. **Preparação dos Dados**
5. **Modelagem com ML (Logistic Regression e Random Forest)**
6. **Avaliação de Desempenho**
7. **Visualização e Interpretação dos Resultados**

## 📊 Resultados

* **Modelo Random Forest** alcançou acurácia de 100% na base simulada, com excelente capacidade de identificar jogadores churnados.
* **Regressão Logística** apresentou desempenho razoável, mas com dificuldades em identificar casos de churn corretamente.

## 📅 Possíveis Expansões

* Aplicar SMOTE para balancear classes
* Testar modelos como XGBoost
* Adicionar novas variáveis: tempo médio por sessão, histórico de vitórias/derrotas
* Criar dashboard interativo com Power BI

## 🎯 Conclusão

O projeto demonstra como dados comportamentais podem ser usados para prever abandono em jogos. É uma prova de conceito valiosa para empresas do setor aplicarem modelos preditivos em suas estratégias de retenção.

---

> Projeto desenvolvido por Ingrid Martinez | [LinkedIn](https://www.linkedin.com/in/ingridmartinezm/) | [GitHub](https://github.com/martinez-ie)
