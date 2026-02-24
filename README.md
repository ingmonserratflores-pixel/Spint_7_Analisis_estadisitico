# Spint_7_Analisis_estadisitico
Objetivo: analizar comportamiento de clientes de una empresa de telecom del 2020-2024,Validar:  planes actuales, información de clientes y uso de los servicios. Crear perfil estadístico de los clientes, detectar comportamientos atípicos y segmentar. Identificar patrones de consumo, estrategias de retención y mejorar planes ofrecidos por la empresa.
Proyecto de Análisis de Datos — Telecom Usage
🎯 Objetivo del Proyecto

El objetivo de este proyecto es realizar un análisis exploratorio de datos (EDA) sobre registros de uso de telecomunicaciones, con el fin de:

Evaluar la calidad de los datos.
Identificar valores nulos estructurales y reales.
Detectar inconsistencias lógicas.
Analizar distribuciones demográficas (edad).
Identificar posibles outliers mediante métodos estadísticos (IQR y Z-score).
Extraer conclusiones relevantes para la toma de decisiones basada en datos.

📁 Datasets Utilizados. El proyecto utiliza los siguientes datasets:

a. usage.csv  Contiene registros de actividad de usuarios: user_id, type (call o text), duration, length, order_value, otras variables relacionadas al consumo

b. users.csv   Contiene información demográfica: user_id, age, otras variables descriptivas

c. Planes.csv    Contiene información de los 2 tipos de planes que maneja: basico y premium

🔎 Etapas del Análisis Realizadas

1 Exploración inicial: Revisión de dimensiones del dataset, Inspección de tipos de datos, Identificación de valores nulos

2 Análisis de valores faltantes: Clasificación de nulos estructurales vs nulos problemáticos, Evaluación porcentual de impacto

3️ Consistencia lógica: Validación de reglas de negocio: text no debería tener duration, call no debería tener length, Se detectaron inconsistencias mínimas (<0.1% del dataset).

4 Análisis demográfico: Clasificación por grupos de edad: Jóvenes, Adultos y Adultos mayores

5 Detección de Outliers:  Aplicación de: Método IQR Z-score (|z| > 3) y Evaluación del impacto estadístico de valores extremos.

6 Interpretación Estadística: Diferencia entre media y mediana, Aplicación conceptual de la Ley de los Grandes Números y Teorema del Límite Central


Subir el archivo .ipynb

Subir los archivos CSV al entorno
