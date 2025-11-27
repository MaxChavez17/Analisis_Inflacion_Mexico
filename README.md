# 🇲🇽 Análisis Econométrico: La Dinámica Monetaria de la Inflación en México (2010-2025)

### 📋 Descripción
Este proyecto valida empíricamente la **Teoría Cuantitativa del Dinero** de Milton Friedman aplicada al contexto mexicano moderno. Utilizando **Python y Econometría**, se analizó si la emisión monetaria sigue siendo el principal motor de la inflación o si ha sido desplazada por otros factores como el tipo de cambio.

### 🧠 Hallazgos Principales
1.  **Friedman tenía razón (con matices):** Existe una correlación positiva y significativa entre la oferta monetaria y la inflación.
2.  **El "Lag" de 12 Meses:** El dinero impreso hoy no sube los precios inmediatamente; el impacto máximo se observa **1 año después**.
3.  **Calidad del Dinero:** El dinero líquido (**M1**) es **3 veces más inflacionario** que la oferta amplia (**M2**), debido a que el ahorro amortigua el impacto en precios.
4.  **Duelo de Variables:** Mediante regresión múltiple, se demostró que aunque el **Tipo de Cambio** es relevante, la **Oferta Monetaria** mantiene su significancia estadística como causante de la inflación.

### 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías:** * `Pandas` (Manipulación de series de tiempo financieras)
    * `Statsmodels` (Modelado OLS y pruebas de hipótesis)
    * `Seaborn / Matplotlib` (Visualización de datos)
* **Datos:** Banco de México (Banxico) - API SIE.

### 📊 Metodología del Código
El Notebook (`.ipynb`) sigue un flujo riguroso:
1.  **Extracción:** Conexión a fuentes oficiales.
2.  **Transformación:** Cálculo de tasas de crecimiento anual y limpieza de datos diarios/mensuales.
3.  **Visualización:** Gráficos de dispersión y tendencias.
4.  **Modelado:** * Regresión Lineal Simple y Múltiple.
    * **Lag Analysis:** Detección automática del tiempo de rezago óptimo.
5.  **Validación:** Pruebas de normalidad en residuos (Jarque-Bera) para asegurar robustez.
6.  **Proyección:** Calculadora interactiva basada en el promedio histórico.

---
*Autor:Maximiliano Velarde Chavez*
*Datos actualizados a: Noviembre 2025*
