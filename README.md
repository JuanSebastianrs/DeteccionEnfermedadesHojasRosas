# Rose Leaf Disease Classification

**Classical computer vision and machine learning for rose-leaf images.**

Academic project by **Juan Sebastián Rodríguez Salazar and Johan Santiago Caro Valencia**. The implementation combines image preprocessing, visual-feature extraction and classification experiments.

[Main notebook](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/src/notebook.ipynb) · [Saved models](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/src/Models/) · [Project video](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/Video.mp4)

## Project focus

The project explores a classical vision pipeline for leaf-image analysis, including:

- Image transformations and data augmentation.
- Filtering, edge detection and contrast adjustment.
- Local feature extraction and Bag of Visual Words.
- Supervised classification and model comparison.
- Color- and texture-based exploratory segmentation.

The notebook is the reference for the implemented experiments and their evaluation.

## Start here

1. Open the [main notebook](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/src/notebook.ipynb).
2. Review its preprocessing, feature-extraction and model-evaluation sections.
3. Inspect the [image folders](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/Imagenes/) and [saved-model directory](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/src/Models/).
4. Watch the [project video](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/Video.mp4) for the walkthrough.

## Local exploration

```bash
git clone https://github.com/JuanSebastianrs/DeteccionEnfermedadesHojasRosas.git
cd DeteccionEnfermedadesHojasRosas
jupyter lab
```

Use a Python environment compatible with the notebook imports and review its local data paths before executing cells.

## Layout

```text
DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/
  Imagenes/        # Image assets
  src/
    notebook.ipynb # Experiments
    Models/        # Saved models
  Video.mp4        # Walkthrough
  README.md        # Original course brief
  LICENSE
```

## Evaluation

Read results together with the preprocessing and split definitions in the notebook. A score from this academic dataset does not establish generalization to unseen farms, lighting conditions or plant varieties.

## Credits and license

Developed by Juan Sebastián Rodríguez Salazar and Johan Santiago Caro Valencia. The original [course brief](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/README.md) is preserved. See the existing [license](DeteccionEnfermedadesHojasRosas_JohanCaro_SebastianRodriguez/LICENSE).

## Resumen en español

Clasificación de imágenes de hojas de rosas mediante visión por computador clásica y aprendizaje automático. Este README permite encontrar directamente el código, las imágenes, los modelos y el video del proyecto.
