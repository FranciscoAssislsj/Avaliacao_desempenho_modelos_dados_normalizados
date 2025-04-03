# Avaliação de Modelos de Regressão com Normalização
## Objetivo:
Analisar como a normalização influencia no desempenho dos modelos RandomForestRegressor, AdaBoostRegressor e GradientBoostingRegressor utilizando métricas de avaliação.

## Tecnologias Utilizadas:
Python,Pandas,NumPy,Scikit-learn

## Dados:
O dataset utilizado contém informações sobre imóveis, incluindo:
Variáveis categóricas e numéricas que influenciam no preço.
SalePrice: O preço final do imóvel (variável alvo).

## Normalização e Tratamento de Dados:
Preenchimento de valores nulos com a média da coluna.
Normalização dos dados numéricos antes do treinamento dos modelos.

## Métricas:
R² Score (Coeficiente de Determinação), MAE (Erro Absoluto Médio), MSE (Erro Quadrático Médio), RMSE (Raiz do Erro Quadrático Médio)
