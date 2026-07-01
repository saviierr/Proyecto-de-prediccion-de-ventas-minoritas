# Predicción de Ventas Minoristas con Big Data

## Información del proyecto

**Asignatura:** Prácticas y Herramientas de Big Data  
**Tema:** Predicción de Ventas Minoristas  
**Universidad:** Universidad Internacional del Ecuador (UIDE)  
**Docente:** Ing. Diego Fernando Pinto Orellana  

**Integrantes:**
- Marlon Savier Torres Soto
- Anderson Michael Calva Vivanco

---

## Descripción

Este repositorio contiene el desarrollo del proyecto integrador de Big Data, enfocado en la predicción de ventas minoristas utilizando el dataset oficial de la competencia **Store Sales - Time Series Forecasting** de Kaggle.

El proyecto busca analizar grandes volúmenes de datos históricos para identificar patrones de comportamiento en las ventas y desarrollar un modelo predictivo que apoye la planificación del inventario, el reabastecimiento de productos y la toma de decisiones en la Corporación Favorita.

---

## Dataset utilizado

**Nombre:** Store Sales - Time Series Forecasting  
**Fuente:** Kaggle (Competencia oficial de Corporación Favorita)  
**URL:** https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

**Formato original:** CSV  
**Registros:** 3.000.888 (tabla `train.csv`)  
**Columnas principales:** 6  
**Variable objetivo:** `sales`

> **Nota:** El dataset no se incluye en este repositorio debido a su tamaño y a las políticas de distribución de Kaggle. Para ejecutar los notebooks, es necesario descargar los archivos desde la página oficial de la competencia.

---

## Tecnologías utilizadas

- Python
- Apache Spark
- PySpark
- Spark SQL
- Jupyter Notebook
- Git y GitHub

---

## Estructura del repositorio

```text
.
├── README.md
├── .gitignore
├── notebooks/
│   ├── TA2.1_Fase1.ipynb
│   ├── TA2.2_Parquet.ipynb
│   └── TA3.2_SparkSQL.ipynb
└── docs/
    ├── TA2.1-Fase1-Proyecto_SavierSoto-AndersonCalva.pdf
    └── GA1-5_ProyectoFase1_PrediccionVentasMinoristas.pdf
```

---

## Objetivo

Diseñar una solución basada en Big Data para analizar datos históricos de ventas y construir un modelo predictivo que permita anticipar la demanda diaria de productos en las diferentes sucursales de la Corporación Favorita.