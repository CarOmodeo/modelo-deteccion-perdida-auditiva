# 🎧 Modelo de Machine Learning para la Detección Temprana de Pérdida Auditiva

Este proyecto fue desarrollado como tesis final para la Especialización en Inteligencia Artificial en la UBA. Tiene como objetivo anticipar indicios de pérdida auditiva en trabajadores expuestos a ruidos, permitiendo así prevenir daños irreversibles y mejorar la calidad de vida.

> 🏥 Proyecto realizado en colaboración con **Doktuz+**.  
> 📅 Fecha: Marzo - Junio 2025  
> 👩‍💻 Autora: Esp. Ing. Carolina Pérez Omodeo

---

## 🎯 Objetivo

Diseñar un modelo de clasificación con machine learning que identifique trabajadores en riesgo de desarrollar pérdida auditiva, basándose en datos clínicos y ocupacionales.

---

## 🧪 Tecnologías utilizadas

- **Python** (pandas, scikit-learn, matplotlib, seaborn)
- **Modelos**: Logistic Regression, Decision Tree, Random Forest
- **Preprocesamiento**: imputación (KNN), normalización, balanceo de clases (SMOTE, undersampling)
- **Evaluación**: F1-score, recall, ROC AUC

---

## 📈 Metodología

1. **Recolección y limpieza de datos**
   - Dataset proporcionado por Doktuz+ (estudios audiométricos reales)
   - Eliminación de columnas irrelevantes o con muchos valores nulos
   - Procesamiento de variables numéricas y categóricas

2. **Definición de la variable target**
   - Criterios clínicos validados por médicos especialistas
   - Clasificación binaria (riesgo / no riesgo)

3. **Balanceo de clases**
   - SMOTE (oversampling)
   - Undersampling para comparación de estrategias

4. **Entrenamiento de modelos**
   - Selección de algoritmos y optimización con Optuna
   - Métricas priorizadas: **Recall** y **F1-score** por sensibilidad médica

5. **Selección final y análisis**
   - Reentrenamiento del mejor modelo
   - Interpretación de variables más relevantes para la predicción

---

## 📊 Resultados

- El mejor modelo alcanzó una **AUC = 84%**.
- Se validó la importancia clínica de variables como:
  - Edad
  - Horas de exposición
  - Años de trabajo
  - Índice BIAP (pérdida auditiva por oído)

---

## 🔒 Confidencialidad

Por tratarse de un proyecto interno de la empresa **Doktuz+**, **el código fuente no es público**.  
Sin embargo, este repositorio ofrece una descripción del proceso de desarrollo, enfoques aplicados y resultados obtenidos.

---

## 🎥 Demo / Presentación

Podés ver una explicación breve del proyecto en el siguiente video:

📽️ [Ver video demo](media/demo-video.mp4)

---

## 📬 Contacto

🌐 [LinkedIn](https://www.linkedin.com/in/carolina-omodeo)

---

> Gracias por tu interés en este proyecto.
