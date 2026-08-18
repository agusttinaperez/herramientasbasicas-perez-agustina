# Herramientas Básicas para el Análisis de Datos — Trabajo Final Integrador

**Autora:** Agustina Pérez
**Curso:** Herramientas básicas para el Análisis de Datos — Centro de e-Learning UTN.BA
**Cohorte:** UTN.BA 2026

## Objetivo

Analizar el rendimiento de campañas de marketing digital en 6 plataformas
(Meta, TikTok, Google Search, Google Display, Snapchat y LinkedIn) para
responder: **¿qué plataforma genera mejor retorno de inversión (ROAS), y cómo
varía este resultado según el tipo de campaña (objetivo)?**

Este análisis busca simular una decisión real de negocio: en qué plataforma
conviene invertir el presupuesto publicitario según el objetivo de la campaña
(ventas, leads, tráfico, etc.).

## Dataset

- **Nombre:** Digital Marketing Performance Dataset (Synthetic, Benchmark-Based)
- **Fuente:** Kaggle — [enlace](https://www.kaggle.com/datasets/alinaboulsi/digital-marketing-performance-dataset)
- **Tamaño:** 30.000 filas × 35 columnas
- **Período:** 01/01/2023 al 31/12/2025
- **Naturaleza:** dataset sintético (generado artificialmente con fines
  educativos), pensado para practicar dashboards de marketing y análisis de KPIs.

## Pasos realizados

1. **Definición de la pregunta y selección del dataset.**
2. **Limpieza y preparación de datos (Python/pandas):** conversión de fechas,
   eliminación de columnas redundantes, cálculo de KPIs y análisis de outliers.
3. **Exploración y visualización (EDA con matplotlib/seaborn):** 4 gráficos
   analizando ROAS por plataforma, por objetivo de campaña, evolución temporal
   del gasto y relación gasto-eficiencia.
4. **Cálculo de KPIs:** ROAS (Return on Ad Spend) y CTR (Click-Through Rate),
   calculados a partir de `spend`, `revenue`, `clicks` e `impressions`.
5. **Dashboard interactivo en Power BI:** en desarrollo.
6. **Publicación en GitHub.**

## Estructura del repositorio

- **data/raw/** → dataset original (CSV) y su diccionario de datos
- **notebooks/** → notebook de limpieza y EDA en Python (.ipynb)
- **dashboard/** → archivo .pbix y/o capturas del dashboard
- **README.md** → este archivo

## Enlaces

- Notebook: [ver en GitHub](https://github.com/agusttinaperez/herramientasbasicas-perez-agustina/blob/main/notebooks/Trabajo_Final_Integrador_Agustina_P%C3%A9rez.ipynb)
- Dashboard (.pbix o capturas): pendiente de publicación
- Dataset fuente: https://www.kaggle.com/datasets/alinaboulsi/digital-marketing-performance-dataset

## Fuentes

- Dataset: alinaboulsi, "Digital Marketing Performance Dataset", Kaggle, 2026. Disponible en: https://www.kaggle.com/datasets/alinaboulsi/digital-marketing-performance-dataset
