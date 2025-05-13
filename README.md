# Clasificación de Células Sanguíneas

## 🎯 Objetivo
Clasificar imágenes de células sanguíneas en diferentes tipos utilizando una red neuronal convolucional (CNN).

## 🧬 Dataset
- **Imágenes**: Fotografías microscópicas de células sanguíneas.
- **Etiquetas**: Archivo `labels.csv` que contiene los nombres de archivo y sus respectivas clases.

## 🧠 Arquitectura del Modelo
 es un modelo de Transformer

## 🧪 Métricas de Evaluación
- Accuracy
- F1-Score
- Precision
- Recall

## 📈 Resultados
- Accuracy en conjunto de validación: 27%
- F1-Score promedio: 0.33

## 📂 Estructura del Proyecto
- `notebooks/`: Contiene los notebooks para preprocesamiento, entrenamiento y evaluación.
- `data/`: Contiene las imágenes y el archivo de etiquetas.
- `artifacts/`: Almacena el modelo entrenado.
- `mlruns/`: Directorio generado por MLflow para el seguimiento de experimentos.

## 🛠️ Requisitos
Ver `requirements.txt` para las dependencias necesarias.
