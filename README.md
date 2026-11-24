# El Detective de Señales

Proyecto de clasificación de señales digitales mediante una red neuronal convolucional (CNN 1D).

## Fase 1: Generación y preparación de datos
Se generan 4000 señales ASK, FSK, PSK y 16-QAM, se agrega ruido gaussiano (AWGN) y se divide el conjunto en 80 % de entrenamiento y 20 % de prueba.

## Fase 2: Diseño y entrenamiento
Se preparan los datos, se construye una CNN 1D con cuatro clases de salida, se entrena durante 10 épocas y se evalúa con los datos de prueba.

## Cómo ejecutar
Abre `Detective_de_Senales.ipynb` en Google Colab y ejecuta todas las celdas en orden. Para una instalación local, instala las dependencias con `pip install -r requirements.txt` y abre el cuaderno en Jupyter.

## Archivos generados al ejecutar
- `Dataset_Detective_de_Senales.npz`: conjunto de datos.
- `Modelo_Detective_de_Senales.keras`: modelo entrenado.

Los resultados pueden variar debido a la generación aleatoria de señales y al entrenamiento.
