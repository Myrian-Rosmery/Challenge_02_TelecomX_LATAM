# Telecom X - Análisis

## 📌 Descripción
Este proyecto tiene como objetivo analizar la **evasión de cliente** en Telecom X. La empresa enfrenta una alta tasa de cancelaciones, y a través de este análisis se busca:

- Identificar patrones de comportamiento de los clientes.
- Determinar factores que influyen en la decisión de cancelar el servicio.
- Generar insights que ayuden a implementar estrategias de retención.

El proyecto se desarrolla utilizando **Python**, con librerías como `pandas`, `numpy`, `matplotlib` y `seaborn`.

---

## 📂 Contenido del Repositorio

- `TelecomX_Churn_Analysis.ipynb` : Notebook con todo el análisis exploratorio, limpieza de datos y visualizaciones.
- `TelecomX_Data.json` : Dataset original extraído desde la API.
- `README.md` : Este archivo, con la descripción del proyecto.

---

## 🛠 Metodología

1. **Extracción de datos:** Se cargan los datos desde la API en formato JSON y se convierten en un DataFrame de Pandas.
2. **Limpieza y corrección de datos:** Se detectan y corrigen valores nulos, duplicados e inconsistencias en las columnas.
3. **Transformación de datos:**  
   - Variables categóricas binarias convertidas a 0/1.  
   - Creación de la columna `Cuentas_Diarias` a partir de `MonthlyCharges`.
4. **Análisis exploratorio de datos (EDA):**  
   - Distribución de churn.  
   - Relación de churn con variables categóricas (género, contrato, método de pago, servicios contratados).  
   - Análisis de variables numéricas (gasto total, gasto mensual, tenure, cuentas diarias).
5. **Visualizaciones:** Gráficos de barras, pasteles y boxplots para detectar patrones de evasión.
6. **Conclusiones e insights:** Se destacan los factores que más influyen en el churn.
7. **Recomendaciones:** Estrategias sugeridas para reducir la tasa de cancelación.

---

## 📊 Herramientas Utilizadas

- **Lenguaje:** Python 3.x  
- **Librerías principales:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  

---

## 📝 Conclusión
El análisis permite identificar los clientes con mayor riesgo de cancelación y proporciona una base para estrategias de **retención segmentadas**, ofreciendo insights accionables para el equipo de Telecom X.

---

## 🔗 Referencias
- [Dataset Telecom X](https://github.com/ingridcristh/challenge2-data-science-LATAM)
- [Documentación Pandas](https://pandas.pydata.org/)
- [Documentación Seaborn](https://seaborn.pydata.org/)
