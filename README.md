# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

---

# 📖 Descripción del proyecto

Este proyecto analiza los datos de clientes de una empresa ficticia de telecomunicaciones **Telecom X** con el objetivo de **predecir la cancelación de clientes (churn)**.

La evasión de clientes es uno de los principales problemas en empresas de telecomunicaciones, ya que implica pérdida de ingresos y aumento en los costos de adquisición de nuevos clientes.

A través de **análisis estadístico y modelos de Machine Learning**, este proyecto busca identificar los factores que influyen en la cancelación de servicios y construir un modelo predictivo que permita anticipar este comportamiento.

---

# 🎯 Objetivos

### Objetivo 1

Construir modelos predictivos que permitan anticipar la evasión de clientes.

### Objetivo 2

Responder preguntas clave del negocio:

* ¿Qué clientes tienen mayor riesgo de cancelar el servicio?
* ¿Qué variables influyen más en la evasión?
* ¿Qué perfil de cliente requiere mayor atención?

### Objetivo 3

Proporcionar información estratégica que permita a la empresa implementar **acciones de retención de clientes**.

---

# 🧰 Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter / Google Colab

---

# 📂 Estructura del proyecto

```
Telecom-X-Churn-Prediction
│
├── datos-telecom-x.csv
├── telecomx_dataset.json
├── Telecom_X_2.ipynb
├── README.md
└── requirements.txt
```

---

# 🔎 Metodología

El proyecto sigue un flujo típico de **Data Science**:

### 1️⃣ Extracción de datos

Se cargó el dataset desde un archivo CSV que contiene información de clientes, servicios contratados y estado de cancelación.

### 2️⃣ Análisis exploratorio de datos (EDA)

Se analizaron variables como:

* tipo de contrato
* método de pago
* cargos mensuales
* antigüedad del cliente
* tipo de servicio de internet

También se realizó un **análisis de correlación** entre variables para identificar relaciones relevantes.

---

### 3️⃣ Preparación de datos

Se realizaron los siguientes pasos:

* eliminación de columnas irrelevantes
* conversión de variables categóricas
* normalización de datos
* separación de datos de entrenamiento y prueba
* verificación de la proporción de cancelación

---

### 4️⃣ Modelos de Machine Learning

Se entrenaron dos modelos predictivos:

**Regresión Logística**

* Modelo interpretable
* Permite entender el impacto de cada variable

**Random Forest**

* Modelo basado en árboles de decisión
* Mayor capacidad predictiva

---

# 📊 Evaluación de modelos

Los modelos fueron evaluados utilizando:

* Accuracy
* Precision
* Recall
* F1-Score
* Matriz de confusión

El modelo **Random Forest mostró el mejor desempeño general** en la predicción de churn.

---

# 📈 Variables más importantes

El análisis de importancia de variables mostró que los factores más influyentes en la cancelación de clientes son:

* Tipo de contrato (Month-to-Month)
* Cargos mensuales
* Tipo de servicio de internet (Fiber Optic)
* Método de pago (Electronic Check)
* Antigüedad del cliente

---

# 💡 Conclusiones estratégicas

Los resultados del análisis indican que los clientes con mayor riesgo de cancelación presentan el siguiente perfil:

* contratos mensuales
* baja antigüedad en la empresa
* cargos mensuales elevados
* uso de fibra óptica
* pago mediante cheque electrónico

---

# 🚀 Recomendaciones para Telecom X

Para reducir la evasión de clientes se recomienda:

### 1️⃣ Incentivar contratos a largo plazo

Ofrecer descuentos o beneficios para contratos anuales o bianuales.

### 2️⃣ Programas de fidelización para clientes nuevos

Los primeros meses son críticos para evitar cancelaciones.

### 3️⃣ Mejorar la experiencia de clientes con fibra óptica

Revisar estabilidad del servicio y soporte técnico.

### 4️⃣ Promover métodos de pago automáticos

Los clientes con pagos automáticos presentan menor churn.

---

# 📦 Instalación

Clonar repositorio:

```
git clone https://github.com/tuusuario/Telecom-X-Churn-Prediction.git
```

Instalar dependencias:

```
pip install -r requirements.txt
```

Ejecutar notebook:

```
jupyter notebook Telecom_X_2.ipynb
```

images/
   churn_distribution.png
   feature_importance.png
   
## Distribución de churn

![Churn](images/churn_distribution.png)