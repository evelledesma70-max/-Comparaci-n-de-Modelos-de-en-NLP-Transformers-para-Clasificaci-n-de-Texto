# -Comparaci-n-de-Modelos-de-en-NLP-Transformers-para-Clasificaci-n-de-Texto
Proyecto académico que compara distintos **modelos Transformer** aplicados a **clasificación de sentimientos** con el dataset **IMDB**, evaluando precisión y rendimiento computacional.  ---

# Comparación de Modelos Transformer para Clasificación de Sentimientos

Este proyecto presenta una **evaluación comparativa de modelos de lenguaje basados en Transformers**
aplicados a la **clasificación de sentimientos** utilizando el **dataset IMDB**.

El estudio analiza tanto el rendimiento predictivo como la eficiencia computacional de diferentes
arquitecturas modernas de NLP.

---

## 🎯 Objetivo del Proyecto

Comparar modelos Transformer en tareas de clasificación de texto, evaluando su **precisión** y su
**comportamiento computacional**, con el fin de identificar el mejor equilibrio entre desempeño y costo.

---

## 🧠 Modelos Evaluados

- ALBERT-base  
- ALBERT-large  
- ModernBERT-base  
- ModernBERT-large  

---

## 📊 Dataset Utilizado

**IMDB Movie Reviews Dataset**
- Reseñas de películas
- Clasificación binaria:
  - `positive`
  - `negative`

---

## 📈 Métricas de Evaluación

- Accuracy
- Tiempo de inferencia
- Tiempo de carga del modelo
- Tamaño del modelo
- Velocidad de procesamiento (samples/segundo)

---

## ⚙️ Metodología

1. Carga y preparación del dataset
2. Inferencia mediante `pipeline` de Hugging Face
3. Normalización de etiquetas
4. Evaluación de métricas de clasificación
5. Benchmark computacional
6. Visualización comparativa de resultados

---

## ▶️ Ejecución del Proyecto

```bash
pip install -r requirements.txt
python src/main.py

