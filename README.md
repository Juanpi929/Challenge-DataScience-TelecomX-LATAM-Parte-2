# 📊 TelecomX LATAM – Predicción de Cancelación de Clientes

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Descripción del Proyecto

Este proyecto desarrolla un **análisis exploratorio y predictivo de datos (EDA + Machine Learning)** sobre el comportamiento de clientes de **TelecomX LATAM**, con el objetivo de **identificar los factores que influyen en la cancelación del servicio (Churn)**.

La evasión de clientes representa uno de los mayores desafíos para las empresas de telecomunicaciones, ya que impacta directamente en:

* 📉 los ingresos
* 📊 la estabilidad del negocio
* 📈 los costos de adquisición de nuevos clientes

A través del **análisis de datos, visualizaciones y modelos predictivos**, este proyecto busca identificar **patrones que expliquen por qué los clientes cancelan el servicio y cómo prevenirlo**.

---

# 🎯 Objetivo del Análisis

Analizar el comportamiento de los clientes de TelecomX para **predecir la cancelación del servicio y descubrir los factores más influyentes**.

El análisis evalúa variables como:

📈 Distribución de clientes que cancelan el servicio
📑 Tipo de contrato
💳 Método de pago
🌐 Tipo de servicio de internet
⏳ Tiempo de permanencia del cliente
💰 Cargos mensuales y gasto total

El propósito final es generar **insights estratégicos que permitan mejorar la retención de clientes**.

---

# 🗂️ Estructura del Proyecto

```
📦 Challenge-DataScience-TelecomX-LATAM-Parte-2
 ┣ 📊 datos_tratados.csv
 ┣ 📓 TelecomX_LATAM_Parte_2.ipynb
 ┣ 📜 README.md
```

### Archivos principales

**datos_tratados** → Dataset con información de clientes

**TelecomX_LATAM_Parte_2.ipynb** → Notebook con el análisis exploratorio, visualizaciones y modelos de Machine Learning

**README.md** → Documentación del proyecto

---

# 📊 Principales Hallazgos

## 📉 1. Distribución de Cancelación

El análisis muestra que aproximadamente:

| Estado del Cliente | Proporción |
| ------------------ | ---------- |
| Permanecen         | ~73%       |
| Cancelan servicio  | ~27%       |

Esto indica que **casi 1 de cada 4 clientes abandona el servicio**, lo que representa un desafío importante para la empresa.

---

## 📑 2. Tipo de Contrato

Los clientes con contrato **Month-to-Month** presentan la mayor tasa de cancelación.

| Tipo de contrato | Tendencia de churn |
| ---------------- | ------------------ |
| Month-to-Month   | Alta               |
| One Year         | Media              |
| Two Year         | Baja               |

💡 **Insight:**
Los contratos de largo plazo **reducen significativamente la evasión de clientes**.

---

## 💳 3. Método de Pago

Se observó que los clientes que utilizan **Electronic Check** presentan una **mayor tasa de cancelación** en comparación con:

* tarjeta de crédito
* transferencia bancaria
* cheque por correo

Esto puede indicar **menor fidelización o menor automatización de pagos**.

---

## 🌐 4. Tipo de Servicio de Internet

El análisis muestra que los clientes con **fibra óptica** presentan una tendencia ligeramente mayor a cancelar el servicio.

Posibles causas:

* costos más elevados
* expectativas de servicio más altas

---

## ⏳ 5. Tiempo de Permanencia del Cliente (Tenure)

Uno de los patrones más claros encontrados fue que:

* los clientes que cancelan el servicio **tienen menor tiempo en la empresa**
* los clientes con mayor antigüedad presentan **mayor estabilidad**

💡 **Insight clave:**
La evasión ocurre **principalmente durante los primeros meses del servicio**.

---

## 💰 6. Cargos Mensuales y Gasto Total

El análisis también muestra que:

* algunos clientes con **cargos mensuales elevados presentan mayor probabilidad de cancelar**
* los clientes que permanecen tienen **mayor gasto total acumulado**

Esto es consistente con su **mayor tiempo de permanencia en la empresa**.

---

# 🤖 Modelos de Machine Learning

Para predecir la cancelación de clientes se implementaron **dos modelos de clasificación**:

### 1️⃣ Regresión Logística

Modelo estadístico utilizado para estimar la probabilidad de cancelación.

Características:

* requiere normalización de datos
* permite interpretar el peso de cada variable

### 2️⃣ Random Forest

Modelo basado en árboles de decisión que permite:

* capturar relaciones no lineales
* identificar la **importancia de las variables**

Este modelo **no requiere normalización de los datos**.

---

# 📈 Evaluación de Modelos

Los modelos fueron evaluados utilizando métricas estándar de clasificación:

* Accuracy
* Precision
* Recall
* F1-score
* Matriz de Confusión

Estas métricas permiten evaluar qué tan bien el modelo identifica a los clientes con riesgo de cancelar el servicio.

---

# 🔎 Variables Más Influyentes en la Cancelación

El análisis de los modelos predictivos indica que las variables más relevantes son:

1️⃣ Tipo de contrato
2️⃣ Tiempo de permanencia del cliente
3️⃣ Cargos mensuales
4️⃣ Método de pago
5️⃣ Tipo de servicio de internet

Estas variables presentan **la mayor relación con la probabilidad de churn**.

---

# 🏆 Conclusión Estratégica

El análisis de datos y los modelos predictivos muestran que la cancelación de clientes está fuertemente asociada con:

* contratos flexibles de corto plazo
* baja antigüedad del cliente
* cargos mensuales elevados
* métodos de pago menos automatizados

En particular, **los clientes nuevos con contratos Month-to-Month presentan el mayor riesgo de cancelación**.

---

# 🛠️ Tecnologías Utilizadas

* Python 3
* Pandas
* Matplotlib
* Scikit-Learn
* Google Colab / Jupyter Notebook

---

# ▶️ Cómo Ejecutar el Proyecto

Este proyecto fue desarrollado en **Google Colab**.

### Pasos para ejecutarlo

1️⃣ Clonar el repositorio

```
git clone https://github.com/Juanpi929/Challenge-DataScience-TelecomX-LATAM-Parte-2
```

2️⃣ Abrir el archivo:

```
TelecomX_LATAM_Parte_2.ipynb
```

3️⃣ Ejecutar las celdas en orden.

Google Colab ya incluye las dependencias necesarias como:

* pandas
* matplotlib
* scikit-learn

---

# 👨‍💻 Autor

**Juan Pablo Quispe Carhuancota**

Interesado en **Data Science, análisis de datos y desarrollo tecnológico**.

📧 Correo
[j18081247@gmail.com](mailto:j18081247@gmail.com)

🔗 GitHub
https://github.com/Juanpi929

🔗 LinkedIn
https://linkedin.com/in/juan-pablo-quispe-917b8a355

Proyecto desarrollado como parte del
**Challenge de Data Science – Alura Latam.**
