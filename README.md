# Modelos Predictivos para la Mejora de la Eficiencia en Instalaciones de Energías Renovables

Este repositorio forma parte del Trabajo Fin de Grado de José Manuel Muelas de la Linde, centrado en el uso de modelos de Machine Learning y Deep Learning para la predicción de la generación energética en parques eólicos y solares.

---

## Objetivo del Proyecto

Desarrollar e implementar modelos predictivos que permitan anticipar la producción de energía en instalaciones renovables, con el fin de mejorar la planificación, el mantenimiento y la eficiencia operativa.

El estudio se centra en:

- Parques solares: Predicción de potencia generada en base a variables meteorológicas y de sensores.
- Parques eólicos: Estimación de generación en función de velocidad del viento, dirección, humedad y otros factores.

---

## Metodología

1. **Preprocesamiento de datos**
   - Limpieza, manejo de nulos, creación de nuevas variables (feature engineering).
   - Normalización de variables meteorológicas.

2. **Modelos de Machine Learning**
   - Regressión Lineal
   - Random Forest
   - XGBoost
   - Métricas evaluadas: MAE, RMSE, R²

3. **Modelos de Deep Learning**
   - Redes neuronales densas (MLP)
   - Redes recurrentes (LSTM)
   - Entrenamiento con Keras + TensorFlow

4. **Evaluación cruzada**
   - Validación en diferentes instalaciones (por ejemplo, entrenar en Plant_1 y probar en Plant_2)

5. **Comparación de resultados y análisis de errores**

---

## Tecnologías utilizadas

- Python 3.10
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn, XGBoost
- TensorFlow, Keras
- Jupyter Notebook
- VS Code

---

## Resultados esperados

- Predicciones precisas de generación energética a corto plazo.
- Análisis comparativo entre modelos clásicos y redes neuronales.
- Posibilidad de aplicar los modelos en escenarios reales de planificación energética.

---

## Estado del proyecto

- [x] Importación y preprocesamiento de datos
- [x] Entrenamiento de modelos clásicos
- [x] Implementación de modelos de deep learning
- [x] Optimización y ajuste de hiperparámetros
- [ ] Documentación y presentación final

---

## Autor

José Manuel Muelas de la Linde  
Grado en Ingeniería en Tecnologías Industriales  
Trabajo Fin de Grado – Universidad de Málaga (UMA)  
Tutor: Lola Burgueño

---

## Licencia

Este proyecto se encuentra bajo la licencia Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International. Consulta el archivo `LICENSE` para más detalles.
