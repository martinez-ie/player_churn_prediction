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
* `avg_session_time`: tempo médio por sessão
* `days_since_last_login`: dias desde o último login
* `level`: nível atual do jogador
* `in_game_purchases`: número de compras in-game
* `total_matches`: número de partidas jogadas
* `wins`: número de vitórias
* `win_rate`: taxa de vitórias (wins / total\_matches)
* `churned`: 1 se o jogador abandonou, 0 se está ativo

## 🛠️ Tecnologias e Ferramentas

* Python (Pandas, NumPy)
* Visualização: Matplotlib, Seaborn
* Machine Learning: Scikit-learn, XGBoost
* Jupyter Notebook

## 📐 Etapas do Projeto e Código

As etapas completas com códigos estão disponíveis no Jupyter Notebook:
🔗 [Notebook no GitHub](https://github.com/martinez-ie/player_churn_prediction/blob/main/churn_games_completo.ipynb)

## 📊 Resultados

* A **Regressão Logística** teve bom desempenho geral, mas com menor recall na classe de churn (0.55).
* O modelo **Random Forest** alcançou 99% de acurácia e 91% de recall para churn.
* O **XGBoost** teve desempenho excelente, com 99% de acurácia e também 91% de recall — o mesmo da Random Forest, mas com mais robustez e estabilidade.

### Métricas de Destaque para XGBoost:

* **Acurácia:** 99%
* **Precision:** 100%
* **Recall (churn):** 91%
* **F1-score (churn):** 0.95

## 🎯 Conclusão

O projeto demonstra como dados comportamentais simulados podem ser usados para prever abandono em jogos. A introdução de variáveis como `avg_session_time` e `win_rate` aumentou o poder preditivo dos modelos.
Modelos como **Random Forest** e **XGBoost** foram altamente eficazes, com destaque para o XGBoost por sua performance equilibrada.
Essa abordagem pode ser usada por empresas do setor de games para criar estratégias de retenção baseadas em dados.

---

> Projeto desenvolvido por Ingrid Martinez | [LinkedIn](https://www.linkedin.com/in/ingridmartinezm/) | [GitHub](https://github.com/martinez-ie)
