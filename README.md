# Práctica 0 - Entropía de Imágenes (Visión por Computador)

Este proyecto procesa un dataset de imágenes (`images_pr0.zip`), calcula entropía a color y en escala de grises, genera gráficas, aplica modificaciones en al menos 10 imágenes y crea un **informe automático en HTML** (y PDF opcional).

## Uso

```bash
pip install -r requirements.txt
jupyter lab Practica0.ipynb
```

El notebook espera `images_pr0.zip` (el dataset que entregó el docente: `training_set/` con
una subcarpeta por categoría) en esta misma carpeta. Extrae hasta 20 imágenes por clase en
`data/images_extracted/` y deja las tablas, las gráficas y el informe en `output/`. Ni el zip ni
las salidas se versionan.

## Qué incluye el informe

- Imagen + ruta + histogramas (gris y color) de muestra por categoría.
- Entropía en gris y color para todas las imágenes.
- Diagramas de cajas y bigotes por categoría (gris y color).
- Explicación de entropía (general, gris y color).
- Análisis de categorías con mayor entropía.
- Modificaciones en 10 imágenes (pequeña, mediana, grande) y comparación en gráfico de barras.

## Licencia

MIT. Ver [LICENSE](LICENSE).
