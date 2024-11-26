# Casino EDA and Predictive Modeling
### 📄 Descripción
Este proyecto combina un Análisis Exploratorio de Datos (EDA) y un pipeline de Machine Learning para analizar y predecir comportamientos en un conjunto de datos de transacciones de un casino en línea. Abarca desde la limpieza y visualización de datos hasta la creación de modelos de predicción para entender la actividad de los usuarios.
### 🚀 Características del Proyecto
#### Análisis Exploratorio de Datos (EDA):

Limpieza de datos y preprocesamiento para análisis precisos.
Análisis temporal y categórico de las transacciones.
Visualización de patrones clave como la distribución de transacciones, los usuarios más frecuentes y los mayores gastadores.
#### Pipeline de Machine Learning:

Creación de características temporales basadas en datos de transacciones históricas.
Entrenamiento y evaluación de un modelo de clasificación con XGBoost para predecir la actividad futura de los usuarios.
Divisiones balanceadas en conjuntos de entrenamiento y prueba.
#### Exportación de Datos:

Generación de archivos CSV para análisis posteriores en herramientas como Power BI.

### 📊 Conjunto de Datos
Fuente: https://data.mendeley.com/datasets/9j5gcygnwg/1
Descripción: Contiene información sobre transacciones, identificadores de usuarios, montos y tipos de transacción.
Filtrado Temporal: Se incluyen transacciones realizadas hasta el 29 de febrero de 2020.
### 🛠️ Herramientas Utilizadas
#### Librerías de Python:
##### Gestión y análisis de datos:

pandas
numpy
##### Visualización de datos:

matplotlib
seaborn
plotly
##### Machine Learning:

scikit-learn
xgboost
##### Otras:

datetime


### 🔍 Análisis Exploratorio
#### 1. Limpieza y Transformación
Conversión de columnas temporales (ReqTimeUTC).
Renombramiento y mapeo de tipos de transacción.
Filtrado por rango de fechas válido.
#### 2. Visualización de Patrones
Histograma acumulativo para comparar tipos de transacciones.
Barras para analizar los usuarios más frecuentes y los mayores gastadores.
Heatmap para identificar patrones horarios y semanales.
#### 3. Generación de Métricas
Datos diarios y mensuales por cliente.
Duración de actividad de los usuarios en el casino.

### 🧠 Pipeline de Machine Learning
#### 1. Preparación de Datos
Generación de características basadas en la actividad de 14 días.
Codificación de respuesta como cliente activo/inactivo.
#### 2. Entrenamiento y Evaluación
Modelo: XGBoost.
Métricas de rendimiento: Precisión y matriz de confusión.

### 📂 Archivos Generados
top_20_active_users.csv: Usuarios más frecuentes.
top_20_high_spenders.csv: Usuarios con mayor gasto.
hour_day_grouped.csv: Resumen por hora y día.
daily_customer_data.csv: Actividad diaria de clientes.
customer_lifetime.csv: Inicio y final de actividad de usuarios.
customer_transitions.csv: Transiciones entre meses.
monthly_metrics.csv: Métricas de clientes por mes.

### 🔧 Instrucciones para Ejecutar
#### Requisitos Previos:

#### Instalar dependencias:

pip install pandas numpy matplotlib seaborn xgboost scikit-learn
Asegurarse de tener el archivo Online_casino_DIB.csv en el directorio de trabajo.

#### Ejecutar el Notebook:

Abrir y ejecutar casino_EDA_analysis.ipynb.
Continuar con classification_pipeline.ipynb para el modelo de Machine Learning.
#### Exportar Resultados:

Archivos CSV generados estarán listos para análisis adicionales en Power BI u otras herramientas.

### 📌 Próximos Pasos
#### Expandir el modelo con más características derivadas.
#### Experimentar con otros algoritmos de clasificación.
#### Implementar un pipeline de análisis automatizado para datos futuros.

### Desarrollado como un ejercicio de análisis y modelado predictivo.



# -Casino-EDA-and-Predictive-Modeling
