# Projeto_Integrador

Projeto final do curso de data science.

MVP para predição da qualidade do ar na cidade de São Paulo.

A qualidade do ar é um elemento vital. Especialmente para pessoas que possuem problemas de saúde, informações preditivas acerca desse aspecto podem fornecer um método de prevenção contra complicações respiratórias.

Criar um modelo preditivo da presença de MP 2.5 no ar da região para as próximas 12 horas, gerando um índice de qualidade do ar que varia de 0-10.

Métrica utilizada: Root Mean Squared Error

MP 2.5: variável target que determina a qualidade do ar.
DDV: direção do vento
DVG: direção global do vento
VV: velocidade do vento, analisado para potencial dispersão do MP 2.5.
TEMP: temperatura
UR: umidade relativa do ar
-------------------------

The final project of the data science course. MVP for predicting air quality in the city of São Paulo.
Air quality is a vital element, especially for people who have health problems, predictive information about this aspect can provide a method of preventing respiratory complications.
Using machine learning techniques, the group created a predictive model of the presence of PM 2.5 in the air for the next 12 hours, generating an air quality index ranging from 0-10 that can be used for the use of preventive actions in people with breathing problems.

Metric used: RMSE (Root Mean Squared Error) is a frequently used measure of the differences between the values ​​(sample or population values) predicted by a model or estimator and the observed values. The RMSE serves to aggregate the magnitudes of errors in the forecasts for several moments in a single measure of predictive power. In general, a lower RMSE is better than a higher RMSE.

Data used:
MP 2.5: target variable that determines air quality.
DDV: wind direction
DVG: global wind direction
VV: wind speed, analyzed for potential dispersion of PM 2.5.
TEMP: temperature
RH: relative humidity

7 models were tested to select the one with the least error:
Ridge (8.05%), SVM (8.30%), Decision Tree (5.33%) , KNN (3.19%), Random Forest (4.98%), Light GBm (2.42%),  XGBoost (2.18%)
