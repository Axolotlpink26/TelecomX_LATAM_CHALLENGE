# TelecomX_LATAM_CHALLENGE
Análisis de evasión de clientes (Churn) para la empresa Telecom X. Proyecto de limpieza, exploración de datos y extracción de insights estratégicos de negocio utilizando Python.
# 📉 Análisis de Evasión de Clientes (Churn) - Telecom X

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-150458.svg)
![Data Science](https://img.shields.io/badge/Data_Science-Business_Intelligence-success.svg)

## 📌 Descripción del Proyecto
Este proyecto forma parte de un desafío práctico enfocado en la **Ciencia de Datos para Negocios**. El objetivo principal es analizar la base de datos de la empresa de telecomunicaciones "Telecom X", la cual enfrenta una alta tasa de cancelación de servicios (Churn) por parte de sus clientes. 

A través de un proceso completo de extracción, limpieza, transformación y Análisis Exploratorio de Datos (EDA), este repositorio documenta la búsqueda de los factores clave que impulsan la fuga de clientes. El resultado final proporciona *insights* y recomendaciones estratégicas que permiten a la empresa tomar decisiones informadas y sentar las bases para futuros modelos predictivos.

## ⚙️ Tecnologías y Dependencias
El proyecto fue desarrollado utilizando **Python** y se ejecuta sobre un entorno de Jupyter Notebook (Google Colab). Las principales bibliotecas utilizadas son:

* `pandas`: Manipulación y limpieza de datos estructurados.
* `numpy`: Operaciones numéricas y manejo de matrices.
* `requests` y `json`: Consumo y extracción de datos desde una API REST.
* `seaborn` / `matplotlib` / `plotly`: *(Agrega estas si utilizaste gráficos)* Creación de visualizaciones para el análisis exploratorio.

## 📂 Estructura del Proyecto
* `TelecomX_LATAM.ipynb`: Notebook principal que contiene todo el código fuente. Incluye la extracción de la API, el tratamiento de datos nulos, la ingeniería de características (creación de la variable `cuentas_diarias`) y el análisis exploratorio.
* `telecom_churn_data_processed.csv`: Dataset final limpio, estandarizado y traducido al español, listo para ser utilizado en algoritmos de Machine Learning o herramientas de BI.
* `README.md`: Documentación del proyecto.

## 🚀 Instalación y Ejecución
Para visualizar o interactuar con el código, tienes dos opciones principales:

### Opción 1: Google Colab (Recomendada)
1. Descarga el archivo `TelecomX_LATAM.ipynb` o abre directamente el repositorio desde Google Colab.
2. No necesitas instalar dependencias locales. Solo asegúrate de ejecutar las celdas en orden. El notebook se encarga de extraer la base de datos original vía API de forma automática.

### Opción 2: Entorno Local
1. Clona este repositorio:
   ```bash
   git clone [https://github.com/Axolotlpink26/TelecomX_LATAM_CHALLENGE](https://github.com/Axolotlpink26/TelecomX_LATAM_CHALLENGE)
