## Detector de Objetos con YOLOv8 + Sistema de Recomendaciones

Este proyecto implementa un sistema de detección de objetos usando YOLOv8 en Google Colab.
Cuando el modelo detecta una de las siguientes clases:
- laptop
- mouse
- keyboard
- cell phone

El sistema muestra automáticamente 4 imágenes de recomendaciones provenientes de Google Drive.

## Tecnologías utilizadas

- Python 3
- YOLOv8 (Ultralytics)
- OpenCV
- Matplotlib
- Pillow (PIL)
- Google Colab
- Google Drive



## Funcionamiento del Proyecto

Se monta Google Drive en Google Colab.<br/>
Se carga una imagen para analizar. <br/>
YOLOv8 detecta objetos y toma el objeto más relevante entre las 4 clases. <br/>
Si detecta una categoría válida, se buscan en Drive 4 imágenes aleatorias de esa clase. <br/>
Las imágenes se muestran en una cuadrícula 2x2.
