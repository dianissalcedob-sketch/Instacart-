# 🛒 Instacart - Análisis de hábitos de compra

## 🎯 Descripción del proyecto

**Instacart** es una plataforma de entrega de comestibles que permite a los usuarios realizar pedidos y recibirlos en casa, similar a servicios como Uber Eats o DoorDash.

Este proyecto se basa en un dataset publicado por Instacart en 2017 para una competencia en Kaggle, el cual contiene información detallada sobre pedidos, productos y comportamiento de los clientes.

El objetivo es analizar los hábitos de compra de los usuarios a partir de datos reales, aplicando técnicas de limpieza, procesamiento y análisis exploratorio.

---

## 🧠 Objetivo del análisis

* Limpiar y preparar los datos (Data Cleaning)
* Identificar patrones de compra de los clientes
* Analizar frecuencia y comportamiento de pedidos
* Generar insights accionables a partir de los datos

---

## 📂 Dataset

El conjunto de datos utilizado es una versión modificada del dataset original de Instacart:

* Tamaño reducido para facilitar el procesamiento
* Inclusión de valores ausentes
* Inclusión de registros duplicados
* Conservación de las distribuciones originales

---

## 🧾 Estructura de los datos

El dataset está compuesto por **5 tablas principales**, las cuales se utilizan para el preprocesamiento y análisis:

* `orders` — Información de pedidos
* `products` — Catálogo de productos
* `order_products` — Relación entre pedidos y productos
* `aisles` — Categorías de productos
* `departments` — Departamentos

---

## 🧹 Proceso de análisis

1. Limpieza de datos:

   * Tratamiento de valores ausentes
   * Eliminación de duplicados
   * Corrección de tipos de datos

2. Preparación:

   * Unificación de tablas
   * Creación de variables relevantes
   * Análisis exploratorio (EDA):
   * Frecuencia de pedidos
   * Productos más comprados
   * Patrones de recompra
   * Comportamiento por día y hora

## 📊 Visualización

Durante el análisis se generan gráficos para comunicar resultados de manera clara y efectiva.
Cada visualización incluye:

Título descriptivo
Ejes etiquetados
Uso adecuado de leyendas
Visualización con plt.show()
💼 Impacto del proyecto

Este análisis permite:
Comprender el comportamiento de compra de los usuarios
Identificar productos más demandados
Detectar patrones de recompra
Apoyar decisiones en marketing y logística
🛠️ Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

## 🚀 Enfoque del proyecto

Este proyecto se centra en el desarrollo de habilidades clave en análisis de datos, incluyendo:

Limpieza y preparación de datos reales
Exploración y visualización
Generación de insights de negocio
