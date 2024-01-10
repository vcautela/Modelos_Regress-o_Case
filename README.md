# Modelos_Regressao_Case
Exercício feito com dataset de empresa de seguros, para comparação de diferentes modelos de regressão

dataset possui as seguintes colunas: ['idade', 'sexo', 'imc', 'quantidade_filhos', 'fumante', 'regiao', 'custos_seguro']

Foi testado os seguintes modelos de regressão: Statsmodel.smf.ols, sklearn.model.LinearRegression, sklearn.ensemble.RandomForestRegressor, sklearn.ensemble.AdaBoostRegressor, sklearn.ensemble.GradientBoostingRegressor

Para desempenho dos modelos, foi usado as seguintes métrica: R² (coeficiente de determinação) e MAE (Mean Absolute Error), sendo que foi medido o Erro Absoluto Médio (MAE) para a base de treino e para a base de teste

Foi utilizado GridSearchCV para melhorar o desempenho de um dos modelos a partir de escolha de hiperparametros 
