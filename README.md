# 📊 Análisis de Evasión de Clientes (Churn) - TelecomX

Este proyecto tiene como objetivo analizar los datos de clientes de una empresa de telecomunicaciones para entender los factores que influyen en la cancelación del servicio (churn). El análisis se realizó utilizando Python, pandas, seaborn y matplotlib, siguiendo las etapas típicas de un flujo de ciencia de datos.

---

## 📌 Objetivo

Detectar patrones y variables clave que expliquen por qué los clientes cancelan su contrato, y generar recomendaciones que ayuden a **reducir la evasión de clientes**.

---

## 🛠️ Tecnologías y Librerías Utilizadas

- Python 3
- pandas
- seaborn
- matplotlib
- numpy
- Jupyter Notebook / Google Colab

---

## 🧪 Flujo del Proyecto

### 1. **Importación y limpieza de datos**
- Lectura de datos desde un archivo `.json`.
- Normalización de campos anidados.
- Conversión de columnas numéricas.
- Eliminación de valores nulos o inconsistentes.
- Transformación de variables categóricas (`Yes/No → 1/0`).
- Creación de nuevas variables como `Cuentas_Diarias`.

### 2. **Análisis Exploratorio de Datos (EDA)**
- Distribución de clientes por churn (`Yes` / `No`).
- Comparaciones por variables categóricas: género, contrato, método de pago, tipo de internet.
- Análisis de `tenure` (meses como cliente) y su relación con el churn.
- Estudio detallado del gasto total (`TotalCharges`) y su relación con cancelaciones.

### 3. **Visualizaciones**
- Matrices de subgráficos para comparar churn por categoría.
- Histogramas, boxplots, violines, dispersión y tasas de churn por grupos.

### 4. **Conclusiones**
- Mayor churn en contratos mensuales y clientes nuevos.
- Alta evasión en clientes que pagan con cheque electrónico o tienen fibra óptica.
- Los clientes con más tiempo y mayor gasto son más estables.

---

## 🔍 Principales Insights

- **Retención tempra**
