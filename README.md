---

# Desafío Telecom X — Análisis ETL y EDA

## Descripción del proyecto

Este proyecto presenta un análisis exploratorio de datos (EDA) sobre clientes de **Telecom X**, utilizando un proceso estructurado de **Extracción, Transformación y Carga (ETL)** a partir de un dataset en formato JSON.
El objetivo principal es **identificar patrones de comportamiento y factores asociados a la pérdida de clientes (churn)**, generando insights accionables para la toma de decisiones de negocio.

---

## Objetivo

Analizar los datos de clientes de Telecom X para:

* Comprender los principales factores que influyen en el churn.
* Identificar segmentos de alto riesgo.
* Proponer recomendaciones estratégicas orientadas a la retención de clientes.

---

## Alcance del análisis

El proyecto cubre las siguientes etapas:

1. Extracción de datos desde una fuente JSON alojada en GitHub.
2. Validación y respaldo de datos crudos.
3. Limpieza y normalización del dataset.
4. Transformación y creación de variables derivadas.
5. Análisis Exploratorio de Datos (EDA).
6. Generación de insights y recomendaciones de negocio.

> Este análisis es **descriptivo y exploratorio**; no se desarrollan modelos predictivos en esta fase.

---

## Herramientas y tecnologías

* **Lenguaje:** Python 3
* **Entorno:** Jupyter Notebook / Google Colab
* **Librerías principales:**

  * pandas
  * numpy
  * requests
  * matplotlib
  * seaborn

---

##  Estructura del proyecto

```
telecomx-challenge/
├── README.md
├── requirements.txt
├── data_raw/
│   └── TelecomX_Data_raw.json
├── data_processed/
│   └── telecomx_clean.parquet
├── notebooks/
│   └── 01_telecomx_etl_eda.ipynb
└── outputs/
    ├── figures/
    └── tables/
```

---

##  Ejecución del proyecto

1. Clonar o descargar el repositorio.
2. Abrir el notebook `JATG_telecomx_etl_eda.ipynb`.
3. Ejecutar las celdas en orden, desde la extracción de datos hasta las conclusiones.
4. Verificar que el notebook se ejecute sin errores de principio a fin.

---

## Principales hallazgos (resumen)

* El churn es significativamente mayor en clientes con baja antigüedad.
* Los contratos mensuales presentan mayor riesgo de abandono.
* Cargos mensuales elevados están asociados a mayor churn.
* Un mayor número de servicios activos reduce la probabilidad de abandono.
* El método de pago y el tipo de servicio influyen en la retención.

---

## Recomendaciones clave

* Reforzar el onboarding durante el primer año.
* Incentivar la migración a contratos de mayor duración.
* Optimizar la propuesta de valor para clientes de alto cargo.
* Implementar estrategias de cross-selling para aumentar la permanencia.

---

## Limitaciones

* El análisis no considera información temporal detallada.
* No se evalúan causas externas al dataset (competencia, mercado, promociones).
* Los resultados no implican causalidad, solo asociaciones.

---

## Siguientes pasos

* Desarrollo de un modelo predictivo de churn.
* Integración de métricas de experiencia del cliente.
* Evaluación del impacto financiero de las estrategias de retención.

---

## Autor

**Jesus Armando Tapia Gallegos**
Proyecto desarrollado como parte del **Desafío Telecom X**.

---
