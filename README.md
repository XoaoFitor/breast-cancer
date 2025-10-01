# Breast Cancer — Gradient Boosting (Classificação) + Diabetes (Regressão)

### Este projeto explora Gradient Boosting em dois cenários:

Classificação no dataset Breast Cancer Wisconsin (Diagnostic) (via sklearn.datasets.load_breast_cancer) para prever se o tumor é maligno ou benigno.

Regressão no dataset Diabetes (via sklearn.datasets.load_diabetes) para prever um desfecho contínuo de saúde.

O notebook principal é breast-cancer.ipynb e contém tanto a parte teórica (perguntas e respostas sobre AdaBoost vs GBM, hiperparâmetros e “stochastic gradient boosting”) quanto a execução prática dos modelos.

#### Aviso: este projeto é educacional. Não deve ser usado para suporte diagnóstico ou decisão clínica.

## Objetivos

Demonstrar um pipeline compacto de modelagem com GradientBoostingClassifier e GradientBoostingRegressor.

Avaliar desempenho com métricas apropriadas (classificação e regressão).

Visualizar matriz de confusão, curva ROC e importância de features (para a parte de classificação).
