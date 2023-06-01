# Modelado y predicción clásico de series temporales aplicado a epidemiología en infecciones 

Forecasting de series temporales usando ARIMA y realizando una comparativa con modelos más simples como Holt-Winters aplicado a incidencia de las bacterias MARSA y Staphylococcus Aureus, en conjunto con la aplicación mensual de antibiótico Levofloxacino.

![image](https://github.com/pacotoh/arima-marsa/assets/13855039/9e437651-c737-4379-8317-6d9e38be61f2)

## Aplicación de modelo ARIMA por fuerza bruta y filtrado de modelos por los criterios:
- RMSE
- Estacionariedad e invertibilidad
- Principio de parsimonia
- Valores AIC y BIC

## Elección de mejores modelos para predicciones de 3, 6 y 13 meses

## Herramientas utilizadas
- Jupyter notebook con Anaconda
- Librería SARIMAX de statmodels para generar modelos ARIMA
- paquetes adfuller para realización de test de Dickey-Fuller y seasonal_decompose
- plotly para representación de gráficas
- pickle para almacenamiento de los modelos obtenidos por fuerza bruta
- dataframes para organizar los datos en forma de tabla

## Estudio de ACF y PACF

![image](https://github.com/pacotoh/arima-marsa/assets/13855039/20e1e42a-73d1-4873-b82a-6bdfd839e38f)

Estudio pormenorizado de gráficas ACF y PACF de aquellos modelos con mejores características predictivas, así como mejores valores estadísticos.

## Estudio de valores residuales de los modelos ARIMA

![image](https://github.com/pacotoh/arima-marsa/assets/13855039/c7e55808-9214-4f40-88a9-d50373560c9b)
