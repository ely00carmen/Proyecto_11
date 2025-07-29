# 🛢️ Proyecto_11: Selección Óptima de Regiones para Nuevos Pozos Petroleros

### 📌 Descripción

Trabajas en **OilyGiant**, una compañía de extracción de petróleo. Este proyecto tiene como objetivo **identificar las ubicaciones más rentables** para desarrollar **200 nuevos pozos petroleros**, utilizando datos históricos y modelos de regresión lineal.

El análisis se realiza a partir de datos recolectados en **tres regiones diferentes**, evaluando el rendimiento esperado y el riesgo financiero de cada una.

---

### 🎯 Objetivos del Proyecto

- Leer los datos de calidad de crudo y volumen de reservas por pozo.
- Entrenar un modelo de **regresión lineal** para predecir el volumen de reservas.
- Seleccionar los **200 pozos más prometedores** por región.
- Calcular el **beneficio total esperado** para cada región.
- Evaluar los **riesgos de pérdida** utilizando **bootstrapping**.
- Elegir la región óptima según el mayor beneficio esperado y riesgo aceptable.

---

### 📊 Descripción de los Datos

Cada archivo contiene:

- `id`: identificador del pozo
- `f0`, `f1`, `f2`: características numéricas
- `product`: volumen de reservas (en miles de barriles)

---

### 💰 Supuestos Financieros

- Se evalúan 500 pozos por región.
- Se seleccionan los mejores 200 pozos según la predicción del modelo.
- Presupuesto disponible: **100 millones USD**.
- Cada unidad de producto (mil barriles) genera **$4,500 USD**.
- Solo se consideran regiones con **riesgo de pérdida < 2.5%**.

---

### ⚙️ Tecnologías Utilizadas

- Python 3
- pandas
- numpy
- scikit-learn (LinearRegression, métricas, split, etc.)

---

### 🧪 Enfoque

1. Carga y análisis exploratorio de datos
2. Entrenamiento del modelo de regresión lineal
3. Predicción del volumen de reservas
4. Selección de los pozos más rentables
5. Evaluación del beneficio esperado por región
6. Estimación del riesgo con bootstrapping
7. Selección final de la región más favorable

---

### ▶️ Cómo Ejecutar

1. Clona este repositorio:
   git clone https://github.com/ely00carmen/Proyecto_11.git
2. Instala las dependencias:
   pip install -r requirements.txt
3. Ejecuta el script o abre el notebook:
   jupyter notebook
