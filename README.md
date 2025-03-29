# Previsão de Preços de Casas em Boston
Este repositório contém um projeto de Machine Learning aplicado ao clássico conjunto de dados do Boston Housing. O objetivo é demonstrar como aplicar um modelo de regressão para prever o valor médio das casas em diferentes regiões de Boston, utilizando técnicas modernas de modelagem e avaliação de desempenho.

## Descrição do Projeto
O conjunto de dados do Boston Housing é amplamente utilizado em projetos de regressão e aprendizado de máquina, sendo ideal para a aplicação de conceitos como pré-processamento, engenharia de atributos, tuning de hiperparâmetros e avaliação de modelos. Neste projeto, utilizamos o algoritmo XGBoost como modelo preditivo principal, realizando a otimização dos hiperparâmetros por meio do RandomizedSearchCV e validação cruzada com K-Fold (5 folds), garantindo maior robustez ao modelo. A avaliação de desempenho foi feita com base em métricas como RMSE (Root Mean Squared Error), MAE (Mean Absolute Error) e R² (coeficiente de determinação), além da análise gráfica dos resíduos para verificar a qualidade dos ajustes. Por fim, o modelo treinado foi aplicado aos dados de teste e os resultados foram exportados em formato CSV.

Referências: [Desafio Boston Housing no Kaggle](https://www.kaggle.com/c/boston-housing)
