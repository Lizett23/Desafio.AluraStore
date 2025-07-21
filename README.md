# Desafio.AluraStore
# Análisis de Desempeño de Tiendas

## 📌 Propósito del análisis

Este proyecto tiene como objetivo principal apoyar al Sr. Juan en una decisión estratégica: **determinar cuál de las cuatro tiendas de su cadena Alura Store debería vender** para iniciar un nuevo emprendimiento.  
Para ello, se realizó un análisis integral del desempeño de las tiendas, considerando indicadores clave como ingresos, calificaciones de clientes, ventas por categoría, costos logísticos y distribución geográfica.

---

## 📂 Estructura del proyecto

El proyecto está organizado de la siguiente manera:

📁 alura_store_analysis/
├── Alura_Store_Análisis.ipynb # Notebook principal con el análisis completo
├── README.md # Archivo explicativo del proyecto
├── /datos/ # Carpeta que contiene los archivos CSV por tienda
│ ├── tienda1.csv
│ ├── tienda2.csv
│ ├── tienda3.csv
│ └── tienda4.csv
└── /imágenes/ # Carpeta con capturas y visualizaciones exportadas


---

## 📊 Ejemplos de gráficos e insights obtenidos

Durante el análisis se generaron distintos tipos de visualizaciones para apoyar la toma de decisiones. Algunos ejemplos:

### 📈 Ingresos totales por tienda (gráfico de barras)
> Tienda 1 fue la que generó mayores ingresos, mientras que Tienda 4 presentó el menor volumen de ventas totales.

### 🥇 Productos más y menos vendidos por tienda
> Se detectaron diferencias importantes en la rotación de productos específicos, como microondas, camas box y guitarras eléctricas, revelando enfoques comerciales distintos en cada tienda.

### 🌍 Distribución geográfica de ventas (scatter plot y heatmap)
> La visualización espacial permitió identificar zonas de mayor concentración de ventas y comparar el alcance regional de cada tienda.

### 📦 Costo de envío promedio
> Tienda 4 resultó ser la más eficiente en costos logísticos, pero no logró compensar su bajo desempeño comercial general.

---

## 🧪 Instrucciones para ejecutar el notebook

1. **Requisitos**:
   - Python 3.x
   - Google Colab o Jupyter Notebook
   - Bibliotecas necesarias:
     ```
     pandas
     matplotlib
     seaborn
     ```

2. **Pasos**:
   - Abre el archivo `Alura_Store_Análisis.ipynb` en Google Colab o Jupyter Notebook.
   - Asegúrate de subir los archivos `tienda.csv`, `tienda2.csv`, `tienda3.csv` y `tienda4.csv` en la misma ruta o en la carpeta `/datos/`.
   - Ejecuta todas las celdas secuencialmente.
   - Las visualizaciones y conclusiones se irán generando paso a paso.
   - Al final del notebook se incluye una **conclusión final** y una **recomendación de cuál tienda vender**.

---

## 📝 Conclusión

Tras el análisis, se recomendó al Sr. Juan vender la **Tienda 4**, por presentar el rendimiento más bajo en términos de ingresos, baja rotación de productos clave y no destacar en indicadores de satisfacción o crecimiento, a pesar de su bajo costo de envío.

---

### ✍️ Autor: *[Lizett Tapia]*  
**Proyecto académico - Curso de Data Analysis - Alura Latam**

