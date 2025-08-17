# 📉 Telecom X – Predicción de Cancelación de Clientes (Churn Prediction)

Proyecto de análisis y modelado predictivo para identificar clientes con alta probabilidad de cancelar los servicios de **Telecom X**, con el fin de tomar acciones proactivas y reducir la tasa de cancelación (churn rate).

---

### 📁 Estructura del Repositorio

- **README.md:** Este archivo, que explica el proyecto.
- **TelecomX_parte2.ipynb:** El notebook de Jupyter con el análisis completo, modelado y conclusiones.
- **datos_tratados.csv:** El conjunto de datos limpio y preparado para el análisis.

---

### 🧠 Objetivos del Proyecto

- Realizar el preprocesamiento de los datos, incluyendo el tratamiento de valores, la codificación de variables y la normalización.
- Analizar correlaciones y seleccionar variables relevantes para el modelo.
- Entrenar y evaluar distintos modelos de clasificación.
- Medir el rendimiento mediante métricas adecuadas.
- Interpretar la importancia de las variables y extraer conclusiones estratégicas.

---

### 🧪 Proceso de Desarrollo

- **Preparación de datos:** Limpieza, transformación y balanceo de clases (utilizando `SMOTE`).
- **Modelado:** Comparación de algoritmos de clasificación.
- **Evaluación:** Análisis de métricas y ajuste de hiperparámetros.
- **Resultados:** Identificación de los factores clave de la cancelación de clientes.

---

### 🏆 Resultados y Conclusiones

Se evaluaron varios modelos, y el modelo **Random Forest** fue seleccionado como el modelo final debido a su equilibrio entre la detección de clientes propensos a la cancelación y la estabilidad general.

**Los factores clave que influyen en la cancelación de clientes son:**
- Clientes con contratos de tipo **"month to month"**.
- El método de pago **`Electronic check`**.
- La **antigüedad** del cliente (pocos meses en la empresa).
- La ausencia de **servicios adicionales** como seguridad en línea, respaldo, protección del dispositivo o soporte técnico.
- **Cargos mensuales elevados** y bajo engagement.

---

### 💡 Estrategias de Retención Sugeridas

- **Incentivar contratos de largo plazo** (1-2 años) a través de promociones.
- **Ofrecer bundles de servicios adicionales** con pruebas gratuitas.
- **Detectar a los clientes que usan `Electronic check`** y migrarlos a métodos de pago más leales.
- **Crear programas de lealtad** para clientes con baja antigüedad.
- **Realizar un seguimiento activo** a los clientes con cargos mensuales altos.

---

### ⚙️ Requisitos

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imblearn
- shap

---

### ▶️ Cómo Ejecutar el Proyecto

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/JenniferFranco/desafio_telecomX_parte2.git](https://github.com/JenniferFranco/desafio_telecomX_parte2.git)
    cd desafio_telecomX_parte2
    ```

2.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Abre el notebook:**
    ```bash
    jupyter notebook TelecomX_parte2.ipynb
    ```

---

### ✅ Estado del Proyecto

✔️ Finalizado | 📅 Agosto 2025

---

### 🙇 Autora

Jennifer Franco
