# Análisis exploratorio y preparación de datos - Seguro de vida

Este repositorio contiene un notebook de Google Colab que realiza un análisis exploratorio y procesamiento de datos sobre un conjunto de pólizas de seguro, con el objetivo de preparar la información para futuros modelos de machine learning orientados a la predicción de renovación.

---

## 👤 Autor

Andres Evans – [@aevans32](https://github.com/aevans32)

---

## 🧪 Dataset

El archivo de datos utilizado se llama **`InsuranceCompany.csv`** y contiene información sobre clientes, primas, edad, ingresos, historial de pagos y si renovaron su póliza (`renewal`).

📥 **Este archivo está disponible exclusivamente para los alumnos de la Universidad del Pacífico** a través de los espacios virtuales de **Blackboard**, en el curso:

> **Machine Learning para la Toma de Decisiones**

Para ejecutar el notebook correctamente, los estudiantes deben descargar el archivo desde Blackboard y colocarlo en el mismo directorio que el notebook.

---

## 📘 Contenido del notebook

El notebook incluye:

- Carga y validación del dataset
- Análisis exploratorio de variables numéricas y categóricas
- Codificación de variables categóricas mediante One Hot Encoding
- Escalado de variables numéricas con `StandardScaler`
- Visualización de correlación con mapas de calor (`sns.heatmap`)
- Preparación final de datos para modelado

---

## 📎 Tecnologías utilizadas

- Python (Google Colab)
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🧑‍🏫 Propósito

Este notebook fue escrito específicamente para apoyar el aprendizaje de los **alumnos del curso de Machine Learning para la Toma de Decisiones** de la **Universidad del Pacífico**.  
Sirve como una guía práctica para aplicar conceptos fundamentales de preparación de datos, codificación, normalización y visualización antes de entrenar un modelo de clasificación.

---

## 📝 Instrucciones

1. Descargar el archivo `InsuranceCompany.csv` desde Blackboard.
2. Abrir el notebook en Google Colab.
3. Subir el archivo CSV al entorno de Colab.
4. Ejecutar todas las celdas desde el menú `Entorno de ejecución > Ejecutar todo`.

---
