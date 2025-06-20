# Clasificacion-de-fracturas-en-extremidades-superiores-con-aprendizaje-profundo
## Descripción
Este proyecto implementa un sistema de clasificación automática de fracturas óseas en radiografías de extremidades superiores utilizando técnicas de aprendizaje profundo. El objetivo es contribuir a la asistencia en el diagnóstico médico mediante modelos de redes neuronales convolucionales (CNN).

El trabajo se centra en la clasificación de radiografías provenientes del conjunto de datos MURA (Musculoskeletal Radiographs), específicamente de las siguientes regiones anatómicas: codo, dedo, antebrazo, mano, húmero, hombro y muñeca.

## Modelos utilizados
- EfficientNet-B4
- ResNet50
- ConvextNeXt-Largue

## Tecnologías
- Python
- PyTorch
- Albumentations
- Scikit-learn
- Matplotlib / Seaborn

## Cómo ejecutar
1. Clonar el repositorio.
2. Descargar el dataset siguiendo las instrucciones en `/data/README.md`.
3. Ejecutar los scripts de preprocesamiento.
4. Entrenar los modelos con los scripts de `/src/`.

## Contribución
Este proyecto fue desarrollado como parte de un trabajo académico y actualmente no se encuentra abierto a contribuciones externas. Para dudas o sugerencias, contactar al autor/a.

## Licencia
Este repositorio tiene fines educativos y de investigación. Los derechos del conjunto de datos pertenecen a **Stanford ML Group (MURA dataset)**.
