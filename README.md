# ⚽ Proyecto EDA: Análisis de Fútbol Europeo (2025)

## 📌 Introducción

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre el **European Soccer Database** de Kaggle.
El objetivo es explorar información de ligas, equipos y jugadores europeos entre 2008 y 2016, para identificar patrones, comparaciones entre ligas y atributos clave en el rendimiento de los jugadores.

Este trabajo combina **SQL, Pandas y visualizaciones** en Python para obtener insights relevantes del fútbol europeo.

---

## 📂 Dataset

* **Nombre:** European Soccer Database
* **Fuente:** [Kaggle – European Soccer Database](https://www.kaggle.com/datasets/hugomathien/soccer)
* **Formato:** SQLite Database
* **Contenido:**

  * +25,000 partidos
  * Datos de ligas, países y equipos
  * Atributos técnicos y físicos de jugadores

---

## 🎯 Preguntas de investigación

1. ¿Qué atributos determinan el rendimiento general de un jugador?
2. ¿Cómo varía el estilo de juego entre ligas europeas?
3. ¿Qué ligas tienen mayor promedio de goles?
4. ¿Qué relaciones existen entre estadísticas ofensivas y rendimiento de equipos?

---

## 🛠️ Tecnologías utilizadas

* **Python 3**
* **SQLite / SQL**
* **Pandas / Numpy**
* **Matplotlib / Seaborn**
* **Google Colab / Jupyter Notebook**

---

## 📊 Resultados e Insights

* El **overall_rating** y el **potential** son los mejores predictores del rendimiento de jugadores.
* Ligas como **Bundesliga** y **Eredivisie** presentan más goles promedio, mientras que **Serie A** muestra un estilo más defensivo.
* Equipos con mayor **posesión y precisión de pase** suelen obtener mejores resultados.
* Se detectaron **valores nulos** en estadísticas de porteros y atributos técnicos, lo que confirma la necesidad de limpiar los datos antes de modelos predictivos.

---

## 📌 Conclusiones

El análisis confirma que:

* Los **atributos individuales** (técnicos y físicos) influyen de manera significativa en el rendimiento.
* Las **ligas europeas** presentan estilos de juego diversos y contrastantes.
* El **EDA deportivo** es una herramienta clave para scouting, preparación de partidos y predicción de tendencias.

Este trabajo abre la puerta a futuros análisis como:

* Modelos de **predicción de resultados**.
* Identificación de **talentos emergentes** con machine learning.

---

# Autor

**Daniel Morales López**
Proyecto de análisis de datos deportivos (2025).
