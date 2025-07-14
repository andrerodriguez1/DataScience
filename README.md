# 📊 Curso de Data Science - Ingenias+
Este repositorio contiene las pre-entregas correspondientes al curso de **Data Science** dictado por **Ingenias+**

**Grupo 15**  
- Andrea Rodriguez  
- Belen Massuco

## Dataset utilizado

- **Fuente:** [Estimaciones Agrícolas - Ministerio de Agricultura](https://datos.magyp.gob.ar/dataset/estimaciones-agricolas)  
- **Período:** 1969/1970 a 2022/2023  
- **Variables principales:**  
  - `provincia_nombre`  
  - `departamento_nombre`  
  - `cultivo`  
  - `ciclo`  
  - `sup_sembrada`  
  - `sup_cosechada`  
  - `produccion`  
  - `rendimiento`

## Estructura del repositorio

├── PRE_ENTREGA2.ipynb #  
   - Tema y dataset seleccionado en dupla.
   - Descripción del objetivo del trabajo.
   - Exploración y transformación de datos con Pandas.
   - Visualización inicial de datos.

├── PRE_ENTREGA_3.ipynb # 
  - Trabaja modelos supervisados sobre todo el dataset.
  - Incluye OneHotEncoding para cultivo y región.
  - Usa Regresión Lineal y Random Forest.
  - Ajusta hiperparámetros.
  - Evalúa importancia de variables.
  - Hace modelos específicos para maíz, soja y trigo.Modelado supervisado: regresión lineal y Random Forest

├── FINAL_ENTREGA_4.ipynb # Clustering con K-Means y DBSCAN
   - Desarrollo de un modelo de aprendizaje no supervisado (clustering).
   - Análisis exploratorio.
   - Aplicación de algoritmo.
   - Justificación de decisiones tomadas.

## Metodología

1. **Limpieza y preprocesamiento:** corrección de valores, creación de nuevas variables, codificación de variables categóricas (*OneHotEncoding*).  
2. **Análisis exploratorio (EDA):** estadística descriptiva, visualizaciones, correlaciones.  
3. **Modelado supervisado:** entrenamiento de **Regresión Lineal** y **Random Forest**, evaluación de métricas y ajuste de hiperparámetros.  
4. **Modelado no supervisado:** aplicación de **K-Means** y **DBSCAN** para segmentar provincias/departamentos según características de producción.  
5. **Análisis de resultados:** interpretación de clusters y comparación entre algoritmos.

## Herramientas utilizadas

- **Python 3.x**
- **Google Colab**
---

