# Data Science Aplicada a Receitas

Este projeto demonstra a aplicação prática de técnicas de ciência de dados em um conjunto de dados de receitas culinárias. Ele foi desenvolvido com foco em 4 pilares principais:

- **Análise Exploratória de Dados (EDA)**
- **Sistema de Recomendação baseado em Tags**
- **Modelos de Regressão (Previsão de target contínuo)**
- **Modelos de Classificação (Classificação binária)**

---

##  1. Análise Exploratória (EDA)

Notebook: `01_eda_receitas.ipynb`

- Avaliação estatística das variáveis numéricas
- Remoção de outliers para melhor visualização
- Análise de correlação e distribuição
- Insights visuais para guiar a modelagem

---

##  2. Sistema de Recomendação

Notebook: `02_sistema_recomendacao.ipynb`

- Algoritmo de recomendação baseado em similaridade de tags e score ponderado
- Recomendações personalizadas por perfil de cliente
- Facilidade de adaptação a novos dados

---

##  3. Modelagem de Regressão

Notebook: `regressor_target.ipynb`

- Comparação entre Regressão Linear, Random Forest e Gradient Boosting
- Otimização de hiperparâmetros com GridSearchCV
- Validação cruzada e análise de desempenho (RMSE, R², Correlação)
- Gráfico Observado vs Predito
- Interpretação das variáveis mais relevantes

---

##  4. Modelagem de Classificação

Notebook: `classificacao_receitas.ipynb`

- Avaliação de modelos: Logistic Regression, Random Forest, SVC, Gradient Boosting
- Otimização de SVC e GB via GridSearchCV
- Métricas analisadas: Accuracy, Precision, Recall, F1-Score, ROC AUC
- Análise de importância das variáveis

---

##  Estrutura do Projeto

```
classification_data/
regression_data/
data/processed/
notebooks/
```

---

##  Requisitos

Instale as dependências com:

```bash
pip install -r requirements.txt
```

---

## Observações

- Todos os notebooks foram mantidos organizados para fácil entendimento e reprodução.
- As bases de treino e teste já estão separadas para regressão e classificação.

---

## Resultado Final

Este projeto demonstra a capacidade de aplicar técnicas de machine learning, validação e explicabilidade. Ideal para contextos de recomendação de conteúdo, previsão de notas ou classificação de receitas conforme perfil do usuário.

---

## Autor

Projeto desenvolvido por Thaina Cordeiro