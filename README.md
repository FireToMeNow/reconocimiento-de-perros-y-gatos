# Perros y gatos (TensorFlow.js)

Clasificador de imágenes perro/gato en el navegador usando la cámara web.

- `index.html`: clasificación en vivo con la cámara (requiere HTTPS, p. ej. GitHub Pages).
- `prueba.html`: prueba del modelo con fotos de ejemplo (sin cámara).
- `model.json` + `group1-shard*.bin`: modelo CNN (100x100, escala de grises) entrenado con el dataset `cats_vs_dogs`.
- `Clasificador_de_perros_y_gatos.ipynb`: notebook de entrenamiento (Colab). Descarga el dataset `cats_vs_dogs` de TensorFlow Datasets, entrena los modelos y exporta el modelo a TensorFlow.js.
- `requirements.txt`: versiones de las librerías para ejecutar el notebook en local.
