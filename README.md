# 💻 Dashboard Análisis de Mercado — Laptops | Power BI

Análisis exploratorio del mercado de laptops con foco en pricing, marcas, configuraciones de hardware y distribución de almacenamiento. Desarrollado en Power BI sobre dataset de Kaggle.

## 📊 Vista previa

![Dashboard Laptops](screenshot/dashboard_laptops.png)

## 🎯 Preguntas de negocio respondidas

- ¿Qué marcas tienen el precio promedio más alto?
- ¿Qué tipo de almacenamiento domina el mercado?
- ¿Cómo se relaciona la RAM con el precio final?
- ¿Qué marcas usan más procesadores AMD vs Intel?

## 🔍 Hallazgos principales

- **Razer** lidera en precio promedio (~$3,500) duplicando a la segunda marca (Millenium)
- **95.5% del mercado usa SSD** — HDD y eMMC son marginales
- La RAM de **32GB** concentra el mayor volumen de unidades en el segmento premium
- **MSI y Asus** tienen los stacks de RAM más grandes del mercado, con fuerte predominancia Intel
- El rango de precios va de $201 a $7,150 — mercado altamente segmentado

## 🛠️ Stack

| Herramienta | Uso |
|-------------|-----|
| Power BI Desktop | Modelado, DAX, visualizaciones |
| DAX | Precio promedio por marca, recuentos segmentados, waterfall chart |
| Dataset | [Laptop Price Dataset — Kaggle](https://www.kaggle.com/datasets/juanmerinobermejo/laptops-price-dataset) |


## 📌 Características del dashboard

- **KPIs:** total de unidades, precio promedio, mínimo y máximo
- **Precio por marca:** bar chart ordenado descendente con scroll
- **Storage type:** pie chart con distribución SSD/eMMC/HDD
- **RAM vs Precio:** waterfall chart — aumento/disminución por segmento de RAM
- **CPU por marca:** stacked bar AMD/Intel/Otra
- **Filtros interactivos:** Brand, GPU, RAM

---

**Gerónimo Pautazzo** · [LinkedIn](https://www.linkedin.com/in/geronimo-pautazzo-88900325a/) · [Portfolio completo](https://github.com/geronimo290)
