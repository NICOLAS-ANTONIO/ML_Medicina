# Análisis Predictivo de Factores de Riesgo para Hospitalización Post-Biopsia Prostática

Este proyecto se enmarca en el contexto de la realización del bootcamp de Henry para Data Science. La base de datos la entrega el equipo de Henry.

## Descripción
El presente trabajo consta de tres etapas:

### Exploración y Limpieza de Datos:
- Se identifican y tratan problemas de calidad de los datos.
- Realización de un análisis exploratorio para entender la distribución de las variables.
- Manejo de valores nulos y duplicados.
- Eliminación de variables redundantes o con alta correlación.

### Preparación de Datos:
- Transformación de variables categóricas y numéricas según fuera necesario.
- Manejo de desequilibrios en la variable objetivo.
- Dividir los datos en conjuntos de entrenamiento y prueba.

### Modelamiento:
- Se utiliza un modelo de Árbol de Decisión y un modelo de k-vecinos como ejemplos.
- Se ajustan hiperparámetros para optimizar el rendimiento del modelo.
- Se evalúa el rendimiento del modelo utilizando métricas como precisión, recall y exactitud.
- Exploración de la importancia de las variables en el modelo.

## Conclusión:
A modo de conclusión podemos revisar las métricas del modelo:

Exactitud (Accuracy): 97.37%
La exactitud indica la proporción general de predicciones correctas. Un 97.37% sugiere un alto nivel de precisión global del modelo en prever la hospitalización.

Precisión (Precision): 80%
La precisión del 80% destaca que el 80% de las predicciones positivas del modelo fueron casos reales de hospitalización. Este resultado indica una capacidad sólida para evitar falsas alarmas.

Recuperación (Recall): 66.67%
Una tasa de recuperación del 66.67% significa que el modelo pudo identificar correctamente el 66.67% de todos los casos reales de hospitalización. Aunque no es la más alta, sigue siendo un nivel considerable de sensibilidad para detectar casos positivos.

Estas métricas en conjunto sugieren que el modelo k-vecinos optimizado tiene un rendimiento sólido, especialmente en términos de precisión, manteniendo un equilibrio entre prever correctamente los casos de hospitalización y minimizar las falsas alarmas.
