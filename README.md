# Retencion-de-clientes
Retencion de clientes MODEL FITNES
# 📊Análisis de Retención de Clientes en Model Fitness


## 📌Descripción del Proyecto
Este proyecto se centra en el análisis de la pérdida de clientes (churn) en la cadena de gimnasios Model Fitness. El objetivo es identificar patrones de comportamiento que permitan predecir qué clientes tienen mayor probabilidad de cancelar sus membresías y desarrollar estrategias para retenerlos. Para ello, se utilizaron técnicas de análisis exploratorio de datos (EDA), modelos de clasificación binaria (regresión logística y bosque aleatorio) y clustering para segmentar a los clientes en grupos con características similares.

## 🛠Tecnologías Utilizadas
Lenguajes de programación: Python

Librerías principales: Pandas, Matplotlib, Seaborn, Scikit-learn, SciPy

Herramientas: Jupyter Notebook

Métricas clave: Exactitud, Precisión, Recall, Dendrograma, K-Means

## 📊Estructura del Proyecto
### 1. Análisis Exploratorio de Datos (EDA)
Carga de datos: Se cargó el conjunto de datos gym_churn_us.csv.

Limpieza y transformación: Se verificaron valores nulos y se analizaron las características de los clientes.

Visualización: Se crearon histogramas y una matriz de correlación para identificar patrones.

### 2. Modelos de Clasificación
Regresión Logística: Exactitud: 91.63%, Precisión: 87.29%, Recall: 78.22%.

Bosque Aleatorio: Exactitud: 91.00%, Precisión: 84.95%, Recall: 78.22%.

### 3. Clustering de Clientes
Estandarización de datos: Se escalaron las características para el clustering.

Dendrograma: Se identificaron 5 clústeres.

K-Means: Se agruparon los clientes en 5 clústeres con diferentes tasas de cancelación.

### 4. Conclusiones y Recomendaciones
Grupos objetivo: Clientes con alta probabilidad de cancelación (Clúster 3) y clientes leales (Clúster 1 y 2).

Medidas para reducir la rotación: Promociones, mejora de la experiencia del cliente y comunicación proactiva.

## 📈Resultados Clave
#### Análisis Exploratorio de Datos (EDA)
Clientes que no cancelan: Viven cerca del gimnasio, tienen contratos largos y alta frecuencia de visitas.

Clientes que cancelan: Viven más lejos, tienen contratos cortos y baja frecuencia de visitas.

#### Modelos de Clasificación
Regresión Logística: Ligera ventaja en precisión (87.29%).

#### Bosque Aleatorio: Rendimiento similar, pero menor precisión (84.95%).

## Clustering de Clientes
### Clúster 3: Tasa de cancelación del 57.29%. Clientes con contratos cortos y baja frecuencia de visitas.

### Clúster 2: Tasa de cancelación del 2.20%. Clientes con contratos largos y alta frecuencia de visitas.

## 📈Conclusiones y Recomendaciones
### 1. Grupos Objetivo
Clientes con alta probabilidad de cancelación: Ofrecer promociones y mejorar la experiencia.

Clientes leales: Implementar un sistema de recompensas por lealtad.

### 2. Medidas para Reducir la Rotación
Promociones y Descuentos: Incentivar la renovación de contratos.

Mejora de la Experiencia del Cliente: Optimizar la plataforma digital y ofrecer asesorías personalizadas.

Comunicación Proactiva: Enviar recordatorios y ofertas personalizadas.
