# Proyecto-Redes-Neuronales

Este proyecto implementa y compara diferentes arquitecturas de redes neuronales convolucionales (CNN) para la clasificación de dígitos del 0 al 9 utilizando un dataset propio generado por estudiantes del curso.
Además, se desarrolla un módulo de predicción en vivo con cámara web (OCR simple) que permite identificar dígitos escritos en tiempo real.

📁CNNproyecto/
Numbers/
Dataset propio con las carpetas Train/ y Test/, cada una con subcarpetas 0 a 9.
Proyecto_P3.ipynb
Notebook principal donde se desarrolla todo el entrenamiento, comparación de modelos y análisis.
final_cnn_model.h5
Modelo final entrenado elegido como el mejor.
live_digit_recognition.py
Script para la predicción en vivo utilizando la cámara web (OCR de dígitos escritos a mano).

Objetivos Principales
Preprocesar un dataset real de imágenes de dígitos escritos a mano.
Entrenar varias arquitecturas CNN y comparar su desempeño.
Generar análisis de precisión, pérdida y métricas por clase.
Construir un sistema OCR que detecte dígitos en tiempo real.
Seleccionar el modelo con mejor desempeño y aplicarlo al sistema final.

OCR en Tiempo Real

El archivo live_digit_recognition.py implementa un sistema OCR basado en:
Captura de cámara web
Preprocesamiento de imagen (blur, umbralización, dilatación)
Detección de contornos
Redimensionamiento e inversión del dígito
Predicción usando el modelo CNN
Visualización con bounding boxes y probabilidades
Ejemplo ejecutando el script:
python live_digit_recognition.py


[Base de datos](https://drive.google.com/drive/folders/1KxNRcFgh5lMXE9hJ132RSyBkdpXQp50J?usp=sharing)

[Reporte Modelos en .ipynb](https://github.com/NelsonAbad/Proyecto-Redes-Neuronales/blob/ab61abdddc01b29103dfb95ed9fcb7830b8c1389/Proyecto_P3.ipynb)

[Reporte CV en .ipynb](https://github.com/NelsonAbad/Proyecto-Redes-Neuronales/blob/ab61abdddc01b29103dfb95ed9fcb7830b8c1389/live_digit_recognition.ipynb)

[Reporte Modelos en HTML](Proyecto_P3.html)

[Reporte CV en HTML](live_digit_recognition.html)

[Modelo preguardado](https://github.com/NelsonAbad/Proyecto-Redes-Neuronales/blob/ab61abdddc01b29103dfb95ed9fcb7830b8c1389/final_cnn_model.h5)

[Power Point](https://docs.google.com/presentation/d/1cWwi7JbOopC0Y_MVrtdIHg6UGdkrtRl42wg_hz0lWWo/edit?usp=sharing)

[Video](https://drive.google.com/file/d/1Q1pOzHjrkdp4KXi3RKYDPOZmgRyE6kot/view?usp=sharing)
