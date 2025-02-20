![TripleTen Logo](/Images/TripleTenLogo.jpeg)

[English](#machine-learning-for-texts-sentiment-analysis-of-movie-reviews) | [Português](#aprendizado-de-máquina-para-textos-análise-de-sentimento-de-resenhas-de-filmes) | [Español](#aprendizaje-automático-para-textos-análisis-de-sentimiento-de-reseñas-de-películas)
---

# Machine Learning for Texts: Sentiment Analysis of Movie Reviews

## Overview
This project, developed for the TripleTen Data Science course, focuses on automatically classifying movie reviews as positive or negative. The goal was to build a model with an F1-score of at least 0.85 for sentiment analysis.

## Project Tasks
- Load and preprocess IMDB movie review data
- Conduct EDA to understand class distribution
- Preprocess text data for modeling
- Train multiple models using different approaches
- Test models on provided test data
- Validate models with new reviews
- Analyze and compare model results

## Technical Stack
- **Python Libraries**:
  - pandas & numpy: Data manipulation
  - NLTK & spaCy: Natural Language Processing
  - scikit-learn: Machine Learning implementation
  - LightGBM: Gradient Boosting
  - BERT: Transformers for NLP
  - matplotlib & seaborn: Data visualization

## Machine Learning Implementation
1. **Baseline Model (DummyClassifier)**
   - Three strategies tested: most_frequent, stratified, uniform
   - Established baseline F1-score of 0.50

2. **NLTK + TF-IDF Model**
   - Text preprocessing with NLTK
   - TF-IDF vectorization
   - Logistic Regression classifier
   - Achieved F1-score of 0.85

3. **spaCy + TF-IDF Model**
   - Advanced linguistic processing with spaCy
   - TF-IDF vectorization
   - Logistic Regression classifier
   - Achieved F1-score of 0.86

4. **LGBMClassifier Model**
   - spaCy preprocessing
   - TF-IDF features
   - Gradient boosting implementation
   - Achieved F1-score of 0.82

## Data Science Skills Demonstrated
1. **Natural Language Processing**
   - Text preprocessing and normalization
   - Feature extraction with TF-IDF
   - Advanced linguistic analysis
   - Sentiment analysis

2. **Machine Learning**
   - Model development and evaluation
   - Hyperparameter optimization
   - Performance metrics analysis
   - Cross-validation techniques

3. **Data Analysis**
   - Exploratory Data Analysis
   - Feature engineering
   - Performance visualization
   - Results interpretation

4. **Software Engineering**
   - Pipeline development
   - Code optimization
   - Error handling
   - Documentation

## Results and Conclusions
- Best performing model: spaCy + TF-IDF (F1-score: 0.86)
- Linear models outperformed more complex approaches
- Successful achievement of target F1-score ≥ 0.85
- Demonstrated model robustness on new reviews

1. Click <a href="https://1drv.ms/f/s!AsjCMhySSWhFg5RuJIev0HIha_JXZQ?e=5lLjo5" target="_blank" rel="noopener noreferrer">here</a> to open the OneDrive link.
2. Navigate to the `Sprint_14` directory and download the `datasets` folder.
3. Move the downloaded `datasets` folder into the `Sprint_14` directory where you cloned this project.
4. Open the `.ipynb` file of your preferred language and run the project.
5. If executing locally, ensure all required libraries are installed on your machine.

[Access the project here](Machine-Learning-for-Texts.ipynb)

---

# Aprendizado de Máquina para Textos: Análise de Sentimento de Resenhas de Filmes

## Visão Geral
Projeto desenvolvido para o curso de Ciência de Dados da TripleTen, focado na classificação automática de resenhas de filmes como positivas ou negativas. O objetivo era construir um modelo com F1-score de pelo menos 0.85 para análise de sentimentos.

## Objetivos do Projeto
- Filtrar e categorizar automaticamente resenhas de filmes
- Treinar um modelo para detectar resenhas negativas
- Alcançar F1-score mínimo de 0.85
- Validar o modelo com novas resenhas
- Implementar diferentes abordagens de NLP

## Stack Técnico
- **Bibliotecas Python**:
 - pandas & numpy: Manipulação de dados
 - NLTK & spaCy: Processamento de Linguagem Natural
 - scikit-learn: Implementação de Machine Learning
 - LightGBM: Gradient Boosting
 - BERT: Transformers para NLP
 - matplotlib & seaborn: Visualização de dados

## Implementação de Machine Learning
1. **Modelo Base (DummyClassifier)**
  - Três estratégias testadas: most_frequent, stratified, uniform
  - Estabeleceu F1-score base de 0.50

2. **Modelo NLTK + TF-IDF**
  - Pré-processamento de texto com NLTK
  - Vetorização TF-IDF
  - Classificador de Regressão Logística
  - F1-score alcançado: 0.85

3. **Modelo spaCy + TF-IDF**
  - Processamento linguístico avançado com spaCy
  - Vetorização TF-IDF
  - Classificador de Regressão Logística
  - F1-score alcançado: 0.86

4. **Modelo LGBMClassifier**
  - Pré-processamento com spaCy
  - Features TF-IDF
  - Implementação de gradient boosting
  - F1-score alcançado: 0.82

## Habilidades Demonstradas
1. **Processamento de Linguagem Natural**
  - Pré-processamento e normalização de texto
  - Extração de features com TF-IDF
  - Análise linguística avançada
  - Análise de sentimentos

2. **Machine Learning**
  - Desenvolvimento e avaliação de modelos
  - Otimização de hiperparâmetros
  - Análise de métricas de performance
  - Técnicas de validação cruzada

3. **Análise de Dados**
  - Análise Exploratória de Dados
  - Engenharia de features
  - Visualização de performance
  - Interpretação de resultados

4. **Engenharia de Software**
  - Desenvolvimento de pipeline
  - Otimização de código
  - Tratamento de erros
  - Documentação

## Resultados e Conclusões
- Melhor modelo: spaCy + TF-IDF (F1-score: 0.86)
- Modelos lineares superaram abordagens mais complexas
- Alcance bem-sucedido do F1-score alvo ≥ 0.85
- Demonstração de robustez em novas resenhas

### **Instruções para Acesso ao Dataset**
Para conseguir executar esse projeto é necessário que você tenha acesso aos dados utilizados. Entretanto, devido ao tamanho dos arquivos, não foi possível subir para o GitHub. Para acessá-los, siga estas etapas:

1. Clique <a href="https://1drv.ms/f/s!AsjCMhySSWhFg5RuJIev0HIha_JXZQ?e=5lLjo5" target="_blank" rel="noopener noreferrer">aqui</a> para acessar o link do OneDrive.
2. Entre no diretório `Sprint_14` e baixe o diretório `datasets`.
3. Vá até o diretório onde você clonou este projeto e cole a pasta `datasets` dentro do diretório `Sprint_14`.
4. Abra o arquivo `.ipynb` do idioma de sua escolha e execute normalmente o projeto.
5. Se estiver executando localmente, garanta que todas as bibliotecas necessárias estão instaladas em sua máquina.

[Acesse o projeto por aqui.](Aprendizado-Automatico-Para-Textos.ipynb)
---

# Aprendizaje Automático para Textos: Análisis de Sentimiento de Reseñas de Películas

## Descripción General
Proyecto desarrollado para el curso de Ciencia de Datos de TripleTen, enfocado en la clasificación automática de reseñas de películas como positivas o negativas. El objetivo era construir un modelo con F1-score de al menos 0.85 para análisis de sentimientos.

## Objetivos del Proyecto
- Filtrar y categorizar automáticamente reseñas de películas
- Entrenar un modelo para detectar reseñas negativas
- Alcanzar F1-score mínimo de 0.85
- Validar el modelo con nuevas reseñas
- Implementar diferentes enfoques de NLP

## Stack Tecnológico
- **Bibliotecas Python**:
 - pandas & numpy: Manipulación de datos
 - NLTK & spaCy: Procesamiento de Lenguaje Natural
 - scikit-learn: Implementación de Machine Learning
 - LightGBM: Gradient Boosting
 - BERT: Transformers para NLP
 - matplotlib & seaborn: Visualización de datos

## Implementación de Machine Learning
1. **Modelo Base (DummyClassifier)**
  - Tres estrategias probadas: most_frequent, stratified, uniform
  - Estableció F1-score base de 0.50

2. **Modelo NLTK + TF-IDF**
  - Preprocesamiento de texto con NLTK
  - Vectorización TF-IDF
  - Clasificador de Regresión Logística
  - F1-score alcanzado: 0.85

3. **Modelo spaCy + TF-IDF**
  - Procesamiento lingüístico avanzado con spaCy
  - Vectorización TF-IDF
  - Clasificador de Regresión Logística
  - F1-score alcanzado: 0.86

4. **Modelo LGBMClassifier**
  - Preprocesamiento con spaCy
  - Features TF-IDF
  - Implementación de gradient boosting
  - F1-score alcanzado: 0.82

## Habilidades Demostradas
1. **Procesamiento de Lenguaje Natural**
  - Preprocesamiento y normalización de texto
  - Extracción de features con TF-IDF
  - Análisis lingüístico avanzado
  - Análisis de sentimientos

2. **Machine Learning**
  - Desarrollo y evaluación de modelos
  - Optimización de hiperparámetros
  - Análisis de métricas de rendimiento
  - Técnicas de validación cruzada

3. **Análisis de Datos**
  - Análisis Exploratorio de Datos
  - Ingeniería de features
  - Visualización de rendimiento
  - Interpretación de resultados

4. **Ingeniería de Software**
  - Desarrollo de pipeline
  - Optimización de código
  - Manejo de errores
  - Documentación

## Resultados y Conclusiones
- Mejor modelo: spaCy + TF-IDF (F1-score: 0.86)
- Modelos lineales superaron enfoques más complejos
- Logro exitoso del F1-score objetivo ≥ 0.85
- Demostración de robustez en nuevas reseñas

### **Instrucciones para Acceder al Dataset**
Para ejecutar este proyecto, debe tener acceso a los datos utilizados. Sin embargo, debido al tamaño de los archivos, no se pudieron cargar en GitHub. Para acceder a ellos, siga estos pasos:

1. Haga clic <a href="https://1drv.ms/f/s!AsjCMhySSWhFg5RuJIev0HIha_JXZQ?e=5lLjo5" target="_blank" rel="noopener noreferrer">aquí</a> para acceder al enlace de OneDrive.  
2. Ingrese al directorio `Sprint_14` y descargue el directorio `datasets`.  
3. Vaya al directorio donde clonó este proyecto y pegue la carpeta `datasets` dentro del directorio `Sprint_14`.  
4. Abra el archivo `.ipynb` en el idioma de su elección y ejecute el proyecto normalmente.  
5. Si está ejecutando localmente, asegúrese de que todas las bibliotecas necesarias estén instaladas en su máquina.

[Acceda al proyecto aquí](Machine-Learning-for-Texts.ipynb)