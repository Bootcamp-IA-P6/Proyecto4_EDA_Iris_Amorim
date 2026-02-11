# Análisis Exploratorio de Datos

## 📌 Descripción del proyecto

Este proyecto tiene como objetivo realizar un **Análisis Exploratorio de Datos (EDA)** sobre un dataset clínico relacionado con **enfermedad cardíaca**, con el fin de identificar patrones, asociaciones y variables potencialmente relevantes para el diagnóstico y la prevención.

El enfoque principal es **descriptivo e interpretativo**, combinando análisis estadístico básico con visualizaciones claras y una narrativa orientada a la toma de decisiones.

---

## 🎯 Objetivos del análisis

- Comprender la distribución de las variables clínicas y demográficas
- Identificar diferencias entre personas con y sin enfermedad cardíaca
- Explorar relaciones bivariadas entre variables clave
- Analizar correlaciones entre variables numéricas
- Comunicar resultados de forma clara mediante gráficos e interpretación

---

## 📂 Estructura del repositorio

```
├── data/
│   ├── metadat/                
│       └── data_dictionary.pdf      # Dicionário variables categóricas
│   └── raw/                         # Datos originales sin modificar
│   └── processed/                   # Datos limpios / preparados (si aplica)
│
├── notebooks/
│   ├── 01_data_loading.ipynb   # Carga de datos y revisión inicial
│   ├── 02_eda.ipynb            # Análisis exploratorio (principal)
│
│├── reports/
│   └── eda_report.pdf      # Informe final en PDF (storytelling)
│
├── .python-version
├──  main.py
├──  pyproject.toml         # Dependencias del proyecto
├──  uv.lock        
└── README.md               # Documentación del proyecto
```

## 📊 Descripción de los notebooks
```
01_data_loading.ipynb
```

- Carga del dataset
- Revisión inicial de columnas y tipos de variables
- Identificación de variables numéricas y categóricas
- Preparación básica de los datos

```
02_eda.ipynb
``` 
**(Notebook principal)**

Incluye:

🔹 **Análisis univariado**

- Variables categóricas:

   - Sexo
   - Tipo de dolor en el pecho
   - Angina inducida por ejercicio
   - Enfermedad cardíaca

- Variables numéricas:

   - Edad
   - Colesterol
   - Presión arterial
   - Frecuencia cardíaca máxima

Visualizaciones:

- Gráficos de barras
- Gráficos de torta (pie charts)
- Boxplots

🔹 **Análisis bivariado**

Explora relaciones clave como:

- Edad vs enfermedad cardíaca
- Tipo de dolor en el pecho vs enfermedad
- Frecuencia cardíaca máxima vs enfermedad
- Angina inducida por ejercicio vs enfermedad
- Colesterol y presión arterial vs enfermedad

Visualizaciones:

- Boxplots comparativos
- Gráficos de barras segmentados

🔹 **Correlaciones**

- Análisis de correlación entre variables numéricas relevantes
- Visualización mediante heatmap
- Interpretación de relaciones lineales

## 🛠️ Tecnologías utilizadas

Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

## 📈 Enfoque del proyecto

- **Exploratorio**, no predictivo
- Orientado a **interpretación y comunicación**
- Pensado para audiencias:
Técnicas (data / analytics)
No técnicas (gestión, salud, negocio)

## 📄 Informe final

El análisis culmina en un informe en PDF, redactado en formato storytelling, con:
- Resumen ejecutivo
- Interpretación de gráficos
- Hallazgos clave
- Limitaciones
- Implicaciones prácticas

## ⚠️ Limitaciones

- El análisis es descriptivo
- No implica causalidad
- El dataset puede contener sesgos o limitaciones de representatividad
- No se entrenan modelos predictivos

## 👤 Autor
Proyecto desarrollado por: Iris Fernanda Amorim