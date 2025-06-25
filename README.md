# Detección de Neumonía en Rayos X con Deep Learning

Este proyecto utiliza modelos de transferencia de aprendizaje (ResNet50 y EfficientNetB0) para clasificar imágenes de rayos X de tórax como NORMALES o con NEUMONÍA.

## Estructura del proyecto
- `detector_neumonia_xray.ipynb`: Notebook principal con el flujo de trabajo completo.
- `chest_xray/`: Carpeta con las imágenes organizadas en `train/`, `val/` y `test/`.
- `requirements.txt`: Librerías necesarias para ejecutar el proyecto.

## Uso
1. Clona el repositorio y navega a la carpeta del proyecto.
2. Crea y activa un entorno virtual.
3. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```
4. Ejecuta el notebook `detector_neumonia_xray.ipynb`.

## Dataset
El dataset utilizado es [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Notas
- Las carpetas de imágenes no se suben al repositorio por su tamaño. Descárgalas desde Kaggle y colócalas en la estructura indicada.
- El archivo `.gitignore` está configurado para evitar subir datos y archivos temporales.
