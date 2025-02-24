![TripleTen Logo](/Images/TripleTenLogo.jpeg)

[English](#time-series-analysis-predicting-taxi-demand) | [Português](#análise-de-séries-temporais-previsão-de-demanda-de-táxi) | [Español](#análisis-de-series-temporales-predicción-de-demanda-de-taxi)
---

# Time Series Analysis: Predicting Taxi Demand

## Overview
This project, developed for the TripleTen Data Science course, focuses on predicting hourly taxi demand at airports. The goal was to build a model with RMSE of less than 48 to help optimize driver allocation during peak hours.

## Project Tasks
- Load and resample time series data to hourly intervals
- Conduct time series analysis to identify patterns
- Create temporal features while preventing data leakage
- Train multiple models with different approaches
- Evaluate models on test data
- Compare model performance

## Technical Stack
- **Python Libraries**:
  - pandas & numpy: Data manipulation
  - scikit-learn: Machine Learning implementation
  - matplotlib: Data visualization
  - Random Forest & Linear Regression: Prediction models

## Machine Learning Implementation
1. **Data Preparation**:
   - Resampling to hourly intervals
   - Feature engineering with lags and rolling means
   - Train-test split (90-10) maintaining temporal order

2. **Linear Regression Model**
   - Simple baseline model
   - RMSE Train: 25.82
   - RMSE Test: 48.41

3. **Random Forest (depth=8)**
   - Medium complexity model
   - RMSE Train: 17.97
   - RMSE Test: 48.34

4. **Random Forest (depth=12)**
   - Best performing model
   - RMSE Train: 12.00
   - RMSE Test: 47.42

## Data Science Skills Demonstrated
1. **Time Series Analysis**
   - Temporal feature engineering
   - Pattern identification
   - Data leakage prevention
   - Trend and seasonality analysis

2. **Machine Learning**
   - Model development and evaluation
   - Feature importance analysis
   - Performance metrics analysis
   - Model comparison

3. **Data Analysis**
   - Exploratory Data Analysis
   - Feature engineering
   - Performance visualization
   - Results interpretation

4. **Software Engineering**
   - Code optimization
   - Data preprocessing
   - Error handling
   - Documentation

## Results and Conclusions
- Best model: Random Forest (depth=12) with RMSE: 47.42
- Successfully achieved target RMSE < 48
- Identified key temporal patterns in taxi demand
- Most important feature: 24-hour lag (44.3% importance)

[Access the project here](Time_Series.ipynb)

---

# Análise de Séries Temporais: Previsão de Demanda de Táxi

## Visão Geral
Este projeto, desenvolvido para o curso de Ciência de Dados da TripleTen, tem como foco a previsão da demanda horária de táxis em aeroportos. O objetivo foi construir um modelo com REQM inferior a 48 para ajudar a otimizar a alocação de motoristas durante os horários de pico.

## Tarefas do Projeto
- Carregar e reamostrar os dados da série temporal para intervalos de uma hora
- Conduzir uma análise de série temporal para identificar padrões
- Criar atributos temporais evitando vazamento de dados
- Treinar múltiplos modelos com diferentes abordagens
- Avaliar os modelos nos dados de teste
- Comparar o desempenho dos modelos

## Stack Tecnológico
- **Bibliotecas Python**:
  - pandas & numpy: Manipulação de dados
  - scikit-learn: Implementação de Machine Learning
  - matplotlib: Visualização de dados
  - Random Forest & Regressão Linear: Modelos preditivos

## Implementação de Machine Learning
1. **Preparação dos Dados**:
   - Reamostragem para intervalos de uma hora
   - Engenharia de atributos com defasagens e médias móveis
   - Divisão treino-teste (90-10) mantendo a ordem temporal

2. **Modelo de Regressão Linear**
   - Modelo de linha de base simples
   - REQM Treino: 25.82
   - REQM Teste: 48.41

3. **Random Forest (profundidade=8)**
   - Modelo de complexidade média
   - REQM Treino: 17.97
   - REQM Teste: 48.34

4. **Random Forest (profundidade=12)**
   - Melhor modelo
   - REQM Treino: 12.00
   - REQM Teste: 47.42

## Habilidades em Ciência de Dados Demonstradas
1. **Análise de Séries Temporais**
   - Engenharia de atributos temporais
   - Identificação de padrões
   - Prevenção de vazamento de dados
   - Análise de tendências e sazonalidade

2. **Machine Learning**
   - Desenvolvimento e avaliação de modelos
   - Análise de importância de atributos
   - Avaliação de métricas de desempenho
   - Comparação de modelos

3. **Análise de Dados**
   - Análise Exploratória de Dados
   - Engenharia de atributos
   - Visualização de desempenho
   - Interpretação de resultados

4. **Engenharia de Software**
   - Otimização de código
   - Preparação de dados
   - Tratamento de erros
   - Documentação

## Resultados e Conclusões
- Melhor modelo: Random Forest (profundidade=12) com REQM: 47.42
- Meta alcançada: REQM < 48
- Identificação de padrões temporais chave na demanda de táxi
- Atributo mais importante: defasagem de 24 horas (44,3% de importância)

[Acesse o projeto aqui](Series_Temporais.ipynb)


---


# Análisis de Series Temporales: Predicción de Demanda de Taxi

## Descripción General
Este proyecto, desarrollado para el curso de Ciencia de Datos de TripleTen, se centra en la predicción de la demanda horaria de taxis en aeropuertos. El objetivo fue construir un modelo con RMSE inferior a 48 para ayudar a optimizar la asignación de conductores durante las horas pico.

## Tareas del Proyecto
- Cargar y remuestrear los datos de la serie temporal a intervalos de una hora
- Realizar análisis de series temporales para identificar patrones
- Crear atributos temporales evitando fugas de datos
- Entrenar múltiples modelos con diferentes enfoques
- Evaluar los modelos en los datos de prueba
- Comparar el rendimiento de los modelos

## Stack Tecnológico
- **Bibliotecas de Python**:
  - pandas & numpy: Manipulación de datos
  - scikit-learn: Implementación de Machine Learning
  - matplotlib: Visualización de datos
  - Random Forest & Regresión Lineal: Modelos predictivos

## Implementación de Machine Learning
1. **Preparación de Datos**:
   - Remuestreo a intervalos de una hora
   - Ingeniería de atributos con rezagos y medias móviles
   - División entrenamiento-prueba (90-10) manteniendo el orden temporal

2. **Modelo de Regresión Lineal**
   - Modelo base simple
   - RMSE Entrenamiento: 25.82
   - RMSE Prueba: 48.41

3. **Random Forest (profundidad=8)**
   - Modelo de complejidad media
   - RMSE Entrenamiento: 17.97
   - RMSE Prueba: 48.34

4. **Random Forest (profundidad=12)**
   - Mejor modelo
   - RMSE Entrenamiento: 12.00
   - RMSE Prueba: 47.42

## Habilidades en Ciencia de Datos Demostradas
1. **Análisis de Series Temporales**
   - Ingeniería de atributos temporales
   - Identificación de patrones
   - Prevención de fugas de datos
   - Análisis de tendencias y estacionalidad

2. **Machine Learning**
   - Desarrollo y evaluación de modelos
   - Análisis de importancia de atributos
   - Evaluación de métricas de rendimiento
   - Comparación de modelos

3. **Análisis de Datos**
   - Análisis Exploratorio de Datos
   - Ingeniería de atributos
   - Visualización del rendimiento
   - Interpretación de resultados

4. **Ingeniería de Software**
   - Optimización de código
   - Preprocesamiento de datos
   - Manejo de errores
   - Documentación

## Resultados y Conclusiones
- Mejor modelo: Random Forest (profundidad=12) con RMSE: 47.42
- Meta alcanzada: RMSE < 48
- Identificación de patrones temporales clave en la demanda de taxis
- Atributo más importante: rezago de 24 horas (44.3% de importancia)

[Accede al proyecto aquí](Series_Temporales.ipynb)
