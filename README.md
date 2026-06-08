# Segmentación Automática de Nódulos Pulmonares (BME513)

**Autores:** Maximiliano Morales  
**Institución:** Universidad de Valparaíso 

## Descripción del Proyecto
Este repositorio contiene el código fuente y el informe técnico para la segmentación semántica de nódulos pulmonares en tomografías computarizadas (CT). El sistema utiliza una red neuronal convolucional (arquitectura U-Net) implementada en PyTorch para procesar matrices 2D y detectar la región de interés con alta precisión espacial, mitigando el desbalance de clases biológico mediante la función de pérdida Dice Loss.

## Requisitos de Software
El proyecto está diseñado para ejecutarse en **Google Colab** utilizando aceleración por GPU. Las dependencias principales incluyen:
* Python 3.10+
* PyTorch
* NumPy
* Matplotlib

## Instrucciones de Ejecución
1. Clonar este repositorio en su entorno local o directamente en Google Colab.
2. Abrir el cuaderno principal ubicado en `notebooks/Entrenamiento_UNet.ipynb`.
3. Ejecutar las celdas de configuración iniciales, las cuales se encargarán de descargar e instalar dinámicamente el conjunto de datos (*Medical Segmentation Decathlon*) en la carpeta `data/` del entorno virtual.
4. (Opcional) Para la inferencia sin entrenamiento, descargar los pesos preentrenados del modelo desde [Insertar Enlace a Google Drive futuro] y colocarlos en la carpeta `models/`.

## Informe Final
El código fuente en LaTeX y el PDF final de la investigación se encuentran en el directorio `report/`.
