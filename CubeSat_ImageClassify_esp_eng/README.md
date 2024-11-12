# CubeSat_ImageClassify

## Description / Descripción

Welcome to the CubeSat Image Classify Hackathon project! This project includes the following Notebooks:

- *Notebook 1*: Introduction to the problem and an overview of the hackathon 
- *Notebook 2*: Reading and analyzing the astronomical data
- *Notebook 3*: Classification using a machine learning model
- *Notebook 4*: Classification using a deep learning model




¡Bienvenido al proyecto CubeSat Image Classify Hackathon! Este proyecto incluye los siguientes Notebooks:

- Notebook 1*: Introducción al problema y visión general del hackathon 
- Notebook 2*: Lectura y análisis de los datos astronómicos
- Notebook 3*: Clasificación utilizando un modelo de aprendizaje automático
- Notebook 4*: Clasificación utilizando un modelo de aprendizaje profundo



## Data / Datos

The data used in this hackathon can be found at [link: coming soon]. It contains approximately 16,000 images, each with a size of 3x512x512. The images are classified into the following categories:

0. Blurry
1. Corrupt
2. Missing_Data
3. Noisy
4. Priority

Los datos utilizados en este hackathon pueden consultarse en [enlace: próximamente]. Contiene aproximadamente 16.000 imágenes, cada una con un tamaño de 3x512x512. Las imágenes se clasifican en las siguientes categorías

0. Borrosa
1. Corrupta
2. Datos_faltantes
3. Ruidoso
4. Prioridad


## Hackathon Task / Tarea del Hackathon

Develop a machine learning model that accurately classifies data captured by CubeSats. The goal is to prioritize which images are most valuable for transmission back to Earth, given the limited onboard resources and slow data downlink speeds. Your task is to create a lightweight model that improves the efficiency and/or classification accuracy of the existing solution in this [paper](https://arxiv.org/pdf/2408.14865).

Desarrollar un modelo de aprendizaje automático que clasifique con precisión los datos captados por los CubeSats. El objetivo es priorizar qué imágenes son más valiosas para su transmisión a la Tierra, dados los limitados recursos a bordo y la lentitud de las velocidades de bajada de datos. Su tarea consiste en crear un modelo ligero que mejore la eficiencia y/o la precisión de clasificación de la solución existente en este [trabajo de investigación](https://arxiv.org/pdf/2408.14865).

## Prerequisites / Requisitos previos

All the necessary libraries and dependencies to run the notebooks are listed in the [requirements.txt](https://github.com/Hack4Dev/CubeSat_ImageClassify/blob/main/requirements.txt) file.

Todas las bibliotecas de programación y dependencias necesarias para ejecutar los cuadernos se enumeran en el archivo [requirements.txt](https://github.com/Hack4Dev/CubeSat_ImageClassify/blob/main/requirements.txt).

### Installation / Instalación


#### On Your Local Machine / En su computadora local

To install a single package, use the following command:

Para instalar un solo paquete, utilice el siguiente comando:

```bash
pip install --user <package>
```

To install all required packages, run:

Para instalar todos los paquetes necesarios, ejecute

```bash
pip install -r requirements.txt
```

On the Ilifu Cloud Computing System:

Sobre el sistema de computación en nube Ilifu:


If you are participating through our cloud computing system [ilifu](https://www.ilifu.ac.za/), you can install Python libraries locally using the following command:

Si participa a través de nuestro sistema de computación en nube [ilifu](https://www.ilifu.ac.za/), puede instalar las bibliotecas de Python localmente utilizando el siguiente comando:


```bash
/shared/venv/bin/python -m pip install --user <package>
```

### Would you like to clone this repository? Feel free! /  ¿Le gustaría clonar este repositorio? ¡No dude en hacerlo!

```bash
git clone https://github.com/Hack4Dev/CubeSat_ImageClassify.git
```

Then make sure you have the right Python libraries for the notebooks. 

A continuación, asegúrese de que dispone de las bibliotecas Python adecuadas para los cuadernos. 

### New to Github? / ¿Eres nuevo en Github?


The easiest way to get all of the lecture and tutorial material is to clone this repository. To do this you need git installed on your laptop. If you're working on Linux you can install git using apt-get (you might need to use sudo):

La forma más fácil de obtener todo el material de las clases y tutoriales es clonar este repositorio. Para ello necesitas tener instalado git en tu portátil. Si estás trabajando en Linux puedes instalar git usando apt-get (puede que necesites usar sudo):


```
apt install git
```

You can then clone the repository by typing:

A continuación, puede clonar el repositorio escribiendo:

```
git clone https://github.com/Hack4Dev/CubeSat_ImageClassify.git
```

To update your clone if changes are made, use:

Para actualizar su clon si se realizan cambios, utilice:

```
cd CubeSat_ImageClassify/
git pull
```

### Original research work: / Trabajo de investigación original:

Chatar, Keenan AA, et al. "Data downlink prioritization using image classification on-board a 6U CubeSat." Sensors, Systems, and Next-Generation Satellites XXVII. Vol. 12729. SPIE, 2023. [link:](https://arxiv.org/pdf/2408.1486).


### Data used (coming soon)

