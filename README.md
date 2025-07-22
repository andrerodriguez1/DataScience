# 📊 Curso de Data Science - Ingenias+
Este repositorio contiene las pre-entregas correspondientes al curso de **Data Science** dictado por **Ingenias+**

## Cosechando Datos: Estimaciones agrícolas en Argentina

🌾 **Introducción al Proyecto**

Este proyecto tiene como objetivo realizar un análisis exploratorio y desarrollar modelos predictivos y de segmentación sobre la producción agrícola en Argentina. Para ello, se utilizó un dataset de estadísticas agrícolas históricas provenientes del portal oficial del Ministerio de Agricultura de la Nación.

El dataset incluye información desde el ciclo agrícola 1969/1970 hasta 2022/2023, con registros organizados por provincia y departamento, lo que permite un análisis geográfico y temporal.

🎯 **Objetivo general**

Analizar la evolución de la producción agrícola en distintas regiones del país a lo largo del tiempo, identificando tendencias, patrones regionales y factores asociados a la variabilidad de los rendimientos y la superficie cultivada.

Objetivos específicos

 - Análisis histórico: Evaluar la evolución de la superficie sembrada y cosechada, la producción y el rendimiento por cultivo y región.
 - Modelado predictivo (aprendizaje supervisado): Estimar la producción futura en función de variables como superficie sembrada, año y región.
 - Segmentación (aprendizaje no supervisado): Identificar grupos de departamentos o regiones con comportamientos productivos similares.

👥 **Integrantes: Equipo 15**

Andrea Rodriguez

Belen Massuco

📊 **Descripción de los datasets**

Fuente: Portal de datos abiertos del Ministerio de Agricultura, Ganadería y Pesca de la Nación Argentina.

Enlace: https://catalogo.datos.gba.gob.ar/dataset/estimaciones-agro/archivo/d3e23031-164a-43e0-b104-01ced63e4abd

Cobertura temporal: 1969/1970 – 2022/2023

Cobertura geográfica: Provincias y departamentos de todo el país.

Variables principales:

 - provincia_nombre: Nombre de la provincia
 - departamento_nombre: Nombre del departamento
 - cultivo: Nombre del cultivo (ej. Soja, Maíz, Trigo)
 - ciclo: Año de campaña (ej. 2004/2005)
 - sup_sembrada: Superficie sembrada (hectáreas)
 - sup_cosechada: Superficie cosechada (hectáreas)
 - produccion: Producción (toneladas)
 - rendimiento: Rendimiento (kg/ha)

🗂️ **Estructura del Repositorio**

El repositorio está organizado en carpetas, cada una correspondiente a una etapa del proyecto:

📁 **Pre-Entrega 1**

Contiene las notebooks individuales 5 y 7, realizadas por cada integrante como entregas previas al trabajo grupal.

📁 **Pre-Entrega 2**

Se incluye el proceso de limpieza de los datos y el análisis exploratorio, además de la visualización de la información por regiones, cultivos y años.

📁 **Pre-Entrega 3**

En esta carpeta se incluyen los modelos de regresión con algoritmos supervisados como Random Forest Regressor, con validación cruzada y métricas de evaluación haciendo hincapié en los tres cultivos con mayor producción del país: Trigo, Soja y Maíz.

📁 **Pre-Entrega 4**

En esta entrega se aplicaron modelos de aprendizaje no supervisado: KMeans y DBSCAN con el objetivo de segmentar la producción según el comportamiento agrícola. Se incluye el uso de PCA para reducción de dimensionalidad junto a la visualización de los modelos para su interpretación y obtención de conclusiones.

Presentación: Resumen del trabajo realizado, hallazgos y visualizaciones clave.

README.md: Este archivo contiene la documentación general del proyecto.

🧪 **Metodología**

*Limpieza y evaluación de los datos*: Se identificaron y trataron valores nulos y datos faltantes, y se ajustaron los tipos de datos en variables clave que originalmente estaban almacenadas como texto. Además, se generaron nuevas variables derivadas y se reorganizó la información provincial agrupada por región, con el fin de facilitar un análisis más estructurado y comparativo.

*Análisis exploratorio*: Se investigaron las tendencias de los cultivos a lo largo del tiempo, desagregadas por región y ciclo agrícola. Además, se realizó un análisis descriptivo de las variables cuantitativas. La generación de visualizaciones facilitó la interpretación de los patrones presentes en los datos y el comportamiento general del conjunto.

*Modelado predictivo* (aprendizaje supervisado): Con el objetivo de estimar la producción futura, se desarrollaron y evaluaron distintos modelos de aprendizaje supervisado.

Se implementaron modelos como Random Forest Regressor y Regresión lineal.

Se aplicó validación cruzada y ajuste de hiperparámetros (GridSearchCV) para optimizar el rendimiento y evaluar el overfitting.

Las métricas utilizadas para la evaluación de los modelos fueron: RMSE, MAE y R².

*Aprendizaje no supervisado*: Para complementar el enfoque supervisado y descubrir patrones ocultos en los datos, se aplicaron técnicas de clustering y reducción de dimensionalidad.

Se utilizaron algoritmos como K-means y DBSCAN para segmentar los datos según comportamientos similares de producción.

Se aplicó PCA (Análisis de Componentes Principales) para visualizar las componentes que más aportaron a la varianza.

Se analizaron los clusters identificados.

Gracias a este enfoque metodológico completo, fue posible abordar el problema desde diferentes perspectivas, combinando el análisis descriptivo de los datos, la predicción mediante modelos supervisados y la exploración de patrones ocultos a través de técnicas de segmentación.

🛠️ **Herramientas utilizadas**

Lenguaje: Python 3.10

Análisis y visualización: pandas, numpy, matplotlib, seaborn

Modelado predictivo: sklearn (train_test_split, RandomForestRegressor, Regresión Lineal), GridSearchCV

Modelo No Supervisado: scikit-learn (KMeans, DBSCAN, PCA)

Entorno: Google Colab, GitHub


