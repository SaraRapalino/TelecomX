# TelecomX
**Churn de Clientes – Telecom X**
Análisis de evasión de clientes para identificar patrones y factores que contribuyen a la cancelación de servicios.

---

## 2. Descripción

Este proyecto tiene como objetivo analizar los datos de clientes de Telecom X, comprendiendo los factores que llevan al **churn** (evasión), y generar **insights estratégicos** que ayuden a reducir la pérdida de clientes.

Se incluyen:

* Limpieza y transformación de datos (ETL).
* Análisis exploratorio de datos (EDA) con métricas descriptivas y visualizaciones.
* Creación de nuevas variables como `Cuentas_Diarias` para profundizar el análisis.
* Identificación de patrones de riesgo de churn según variables categóricas y numéricas.

---

## 3. Estructura del Proyecto

```text
Churn-TelecomX/
├─ data/                   # Datos originales en formato JSON
├─ notebooks/              # Notebook de análisis en Google Colab
├─ README.md               # Este archivo
├─ requirements.txt        # Dependencias de Python
└─ visuals/                # Carpeta para guardar gráficos generados
```

---

## 4. Requisitos e Instalación

### 4.1 Dependencias de Python

* pandas
* numpy
* seaborn
* matplotlib

### 4.2 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/TuUsuario/Churn-TelecomX.git

# Entrar al directorio
cd Churn-TelecomX

# Instalar dependencias
pip install -r requirements.txt
```

> Para ejecutar en Google Colab, simplemente sube el notebook y las carpetas de datos.

---

## 5. Uso

1. Abrir el notebook `notebook/Churn_Analysis.ipynb` en Colab.
2. Ejecutar las celdas en orden:

   * Carga de datos desde la API
   * Limpieza y transformación de datos
   * Análisis exploratorio de variables categóricas y numéricas
   * Visualización de patrones de churn
3. Revisar los gráficos y estadísticas generadas para obtener insights estratégicos.

---

## 6. Problemas comunes y soluciones

* **Valores nulos en TotalFacturado o tenure:** se manejan convirtiendo a NaN y eliminando filas incompletas.
* **Duplicados en customerID:** se eliminan para garantizar consistencia.
* **Problemas con categorías de texto:** se recomienda estandarizar strings y convertir Yes/No a 1/0.

---

## 7. Contribuciones

Este proyecto puede ser extendido para:

* Construir **modelos predictivos de churn**.
* Generar dashboards interactivos con métricas de clientes.
* Analizar correlaciones entre servicios contratados y evasión.

---

## 8. Licencia

Este proyecto es **libre para fines educativos y de práctica profesional**.

