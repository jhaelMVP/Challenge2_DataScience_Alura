# Challenge2_DataScience_Alura
challenge del grupo de data science en alura latam
🚀 Challenge Telecom X: Análisis de Churn de Clientes

Estado del Proyecto: Finalizado ✅

Este proyecto tiene como objetivo analizar la evasión de clientes (churn) en una empresa de telecomunicaciones, identificando los principales factores que influyen en la pérdida de usuarios. A través de Python y técnicas de Análisis Exploratorio de Datos (EDA), se concluyó que la estabilidad contractual y los costos mensuales son los principales detonantes del abandono del servicio.

🧰 Herramientas y Tecnologías

Lenguaje: Python

Librerías: Pandas, Seaborn, Matplotlib, Requests

Entorno: Google Colab

Formatos de datos: CSV, JSON

Fuente de datos: API REST

📂 Estructura del Proyecto
├── data/        # Archivos de datos (CSV, JSON)
├── notebooks/   # Notebooks de análisis (Google Colab)
├── reports/     # Gráficos e informes finales
└── README.md    # Documentación del proyecto

📁 Origen de los Datos

Los datos fueron obtenidos desde la API de Telecom X, disponible en el repositorio de desafíos de Alura LATAM.
La ingesta se realizó mediante la librería requests y la estructuración con pandas.

📊 Variables Analizadas
Información del Cliente

Género

Adulto mayor

Pareja y dependientes

Servicios Contratados

Tipo de Internet (DSL / Fibra Óptica)

Seguridad en línea

Soporte técnico

Variable Objetivo

Churn: Indica si el cliente abandonó el servicio (Yes / No)

🔍 Metodología de Análisis
1. Limpieza y Preparación de Datos

Tratamiento de valores nulos: Eliminación de registros con TotalCharges inválidos.

Corrección de tipos de datos: Conversión de texto a valores numéricos.

Integridad del dataset: Eliminación de duplicados y estandarización de categorías.

2. Ingeniería de Características

Cuentas_Diarias: Cálculo del costo diario aproximado (MonthlyCharges / 30).

Renombramiento: Traducción de columnas al español.

Binarización: Conversión de la variable Churn a formato numérico (0 / 1).

📈 Resultados y Hallazgos
📌 Resumen Estadístico

Cargo mensual promedio: $64.76

Antigüedad mediana: 29 meses

Tasa de evasión: 26.5%

🔎 Insights Clave

Tipo de contrato: Los contratos Mes a Mes presentan la mayor tasa de churn.

Servicios: Existe una correlación positiva entre la Fibra Óptica y la evasión.

Precio: Los clientes que abandonan tienen mayores cargos mensuales.

🏁 Recomendaciones

Estrategias de fidelización: Incentivar contratos anuales o de mayor duración.

Mejora del onboarding: Refuerzo del acompañamiento durante los primeros 6 meses.

Optimización del producto: Evaluar costos y estabilidad del servicio de Fibra Óptica.

📌 Este análisis proporciona una base sólida para la toma de decisiones estratégicas orientadas a reducir la evasión de clientes y mejorar la retención.
