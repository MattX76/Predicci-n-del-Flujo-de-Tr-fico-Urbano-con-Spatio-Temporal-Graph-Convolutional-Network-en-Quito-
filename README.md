# Predicción del Flujo de Tráfico Urbano con ST-GCN en Quito
Este repositorio contiene el proyecto PIS 23-05 de la EPN, que implementa un modelo ST-GCN para predecir el flujo de tráfico en Quito. Incluye el código Python para la arquitectura del modelo, preprocesamiento de datos de tráfico, y visualización de resultados. Es ideal para proyectos de Smart Cities y Deep Learning.

# Predicción del Flujo de Tráfico Urbano con ST-GCN en Quito

## 📍 Proyecto PIS 23-05 - Escuela Politécnica Nacional

Este proyecto, desarrollado como parte del **Proyecto de Integración de Saberes (PIS 23-05)** de la Escuela Politécnica Nacional (EPN), se enfoca en la predicción del flujo vehicular en la ciudad de Quito. Utiliza un modelo de red neuronal de grafos espacio-temporales (ST-GCN) para capturar la compleja dinámica del tráfico, considerando tanto la evolución temporal como la conectividad espacial de la red vial.

El objetivo principal es proveer una solución avanzada y precisa para la gestión inteligente del tráfico, demostrando la aplicación de técnicas de **Deep Learning** a problemas de series de tiempo georreferenciadas.

***

### 🚀 Características Principales

* **Modelo ST-GCN**: Una arquitectura de vanguardia para la predicción de series de tiempo multivariadas y espaciales.
* **Análisis de Datos**: Scripts para el preprocesamiento, normalización y estructuración de datos de tráfico.
* **Visualización de Resultados**: Herramientas para generar gráficos que comparan los valores de tráfico reales y predichos.
* **Métricas de Desempeño**: Cálculo de métricas clave como MAE, RMSE y MAPE para una evaluación exhaustiva del modelo.
* **Base de Datos**: Inclusión de la base de datos de tráfico y la estructura de la red vial para replicabilidad.

***

### 📂 Estructura del Repositorio


├── data/                    # Contiene la base de datos y archivos de datos preprocesados
├── notebook/                # Notebooks de Jupyter con el desarrollo y análisis del proyecto
├── src/                     # Código fuente de las clases y funciones del modelo
│   ├── model.py             # Definición de la arquitectura ST-GCN
│   ├── data_loader.py       # Clases para cargar y procesar los datos
│   └── utils.py             # Funciones de utilidad (métricas, visualización, etc.)
└── README.md                # Archivo principal de descripción del proyecto


***

### 🛠️ Requisitos

Para ejecutar este proyecto, necesitas las siguientes librerías de Python. Puedes instalarlas usando `pip`:

```bash
pip install torch numpy pandas matplotlib scikit-learn
📋 Uso
Clona el repositorio:

Bash

git clone [[https://github.com/tu-usuario/nombre-del-repositorio.git]
Prepara los datos:
Asegúrate de que tus datos de tráfico y la matriz de adyacencia de la red vial estén ubicados en la carpeta data/.

Ejecuta el Notebook:
Abre y ejecuta el notebook principal en la carpeta notebook/ para entrenar el modelo, evaluarlo y visualizar los resultados.

