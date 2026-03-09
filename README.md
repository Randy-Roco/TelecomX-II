# Telecom X — Predicción de Cancelación de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

Proyecto de **Machine Learning aplicado a la predicción de cancelación de clientes (Churn)** en una empresa de telecomunicaciones.

El objetivo es desarrollar modelos capaces de **identificar clientes con alta probabilidad de cancelar el servicio**, permitiendo implementar estrategias de retención basadas en datos.

---

# Objetivo del Proyecto

Construir un pipeline completo de análisis y modelado predictivo que permita:

- preparar los datos para modelado
- analizar variables asociadas al churn
- entrenar modelos de clasificación
- evaluar su desempeño
- interpretar los factores que influyen en la cancelación

---

# Pipeline del Proyecto

### 1. Preparación de Datos
- carga del dataset tratado
- eliminación de columnas irrelevantes
- codificación de variables categóricas (One-Hot Encoding)

### 2. Análisis Exploratorio
- distribución de churn
- análisis de correlación con churn
- boxplots de variables relevantes

### 3. Modelado Predictivo
Se entrenaron tres modelos:

- Dummy Classifier (baseline)
- Regresión Logística
- Random Forest

### 4. Evaluación de Modelos
Los modelos fueron evaluados utilizando:

- Accuracy
- Precision
- Recall
- F1-score
- matriz de confusión

### 5. Interpretación de Variables
Se analizaron las variables más influyentes mediante:

- coeficientes de **Regresión Logística**
- importancia de variables en **Random Forest**

---

# Resultados

El modelo con mejor desempeño fue **Regresión Logística**, con un **F1-score cercano a 0.59**, superando al modelo baseline.

Los resultados muestran que el modelo es capaz de identificar patrones relevantes asociados al churn.

---

# Factores Asociados a la Cancelación

El análisis identificó variables importantes relacionadas con el abandono del servicio:

- menor antigüedad del cliente
- contratos mensuales
- cargos mensuales más elevados
- menor uso de servicios adicionales

Estos factores sugieren que el churn está relacionado con el **nivel de compromiso del cliente y el valor percibido del servicio**.

---

# Estrategias de Retención

A partir de los resultados se proponen las siguientes estrategias:

- programas de retención durante los primeros meses del cliente
- incentivos para contratos de mayor duración
- optimización del valor percibido del servicio
- promoción de servicios complementarios

---

# Tecnologías Utilizadas

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

# Estructura del Repositorio

TelecomX-II
│
├── TelecomX_2.ipynb
├── datos_tratados.csv
└── README.md

# Autor

**Randy Roco Mellado**

Ingeniero en Geomensura  
Estudiante de Data Science  

GitHub  
https://github.com/Randy-Roco
