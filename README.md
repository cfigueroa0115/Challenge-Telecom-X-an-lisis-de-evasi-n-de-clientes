#  Customer Churn Analysis – Telecom X

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)  
![Pandas](https://img.shields.io/badge/Pandas-1.5+-brightgreen.svg)  
![License](https://img.shields.io/badge/License-Educational-yellow.svg)

---

##  Resumen del Reto

Fuiste contratado como asistente de análisis de datos en **Telecom X** para participar en el proyecto **"Churn de Clientes"**. La empresa enfrenta una tasa elevada de cancelaciones y busca entender qué factores están impulsando la pérdida de clientes.

Tu tarea principal consiste en **recopilar, procesar y analizar los datos de clientes** utilizando Python. A partir de tu análisis, el equipo de Data Science podrá desarrollar **modelos predictivos y estrategias de retención** más eficaces.

---

##  Descripción del Proyecto

Este repositorio presenta un análisis exploratorio sobre la evasión de clientes (churn) en **Telecom X**, utilizando un conjunto de datos con información detallada sobre clientes, servicios contratados, facturación y tipo de contrato.

Se abordan distintas etapas del análisis de datos: desde la limpieza y transformación, hasta la exploración visual y la identificación de patrones relevantes para comprender mejor los factores de cancelación.

---

##  Dataset

- **Formato:** JSON  
- **Fuente:** [TelecomX_Data.json](https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json)  
- **Total de registros:** 7,267 clientes

### Principales variables:

- **Demográficas:** `Gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- **Servicios:** `PhoneService`, `InternetService`, `StreamingTV`, etc.  
- **Facturación:** `MonthlyCharges`, `TotalCharges`, `DailyCharges`  
- **Variable objetivo:** `Churn` (Sí/No)

---

##  Requisitos

- Python 3.8+  
- Librerías necesarias:

```bash
pip install pandas numpy matplotlib seaborn requests

## Principales hallazgos

Los clientes con contratos mensuales presentan mayor tasa de cancelación.
Menor tiempo de permanencia (tenure) y menor número de servicios contratados están fuertemente asociados al churn.
Algunos métodos de pago y un alto consumo diario se relacionan con mayor probabilidad de cancelación.

