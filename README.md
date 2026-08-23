# 📊 Análisis de Matrícula UNFV 2026

> **¿Qué nos dicen los datos sobre los estudiantes matriculados de la Universidad Nacional Federico Villarreal?**

Este proyecto presenta un análisis exploratorio y visual de la **matrícula estudiantil de la Universidad Nacional Federico Villarreal (UNFV) para 2026**. El objetivo no fue únicamente contar estudiantes, sino transformar los datos en información que permita entender mejor la composición de la población universitaria.

El análisis fue desarrollado con **Python, Pandas, Matplotlib y Seaborn**, combinando estadística descriptiva, análisis exploratorio de datos (EDA) y visualización para identificar patrones relacionados con **facultad, ciclo académico, sexo y edad**.

---

## 🎯 Objetivo

Analizar la estructura de los estudiantes matriculados y responder preguntas como:

* ¿Qué facultades concentran mayor cantidad de estudiantes?
* ¿Cómo se distribuye la matrícula entre los diferentes ciclos?
* ¿Existe equilibrio entre estudiantes mujeres y hombres?
* ¿Cuál es la edad típica del estudiante universitario?
* ¿Qué patrones o concentraciones pueden observarse en la población analizada?

La idea central es pasar de **datos → análisis → evidencia → comunicación visual**.

---

## 📌 Principales resultados

### 👥 16,442 estudiantes

El dataset contiene **16,442 registros asociados al ciclo académico**, constituyendo la base principal del análisis.

### ⚖️ Distribución por sexo

| Sexo      | Estudiantes | Participación |
| --------- | ----------: | ------------: |
| Femenino  |       8,226 |        50.03% |
| Masculino |       8,216 |        49.97% |
| **Total** |  **16,442** |      **100%** |

La diferencia entre ambos grupos es de apenas **10 estudiantes**, lo que muestra una distribución prácticamente equilibrada dentro del conjunto analizado.

### 🎓 Ciclo académico

El ciclo promedio es **3.03**, mientras que la mediana se ubica en el **3.er ciclo**.

| Estadístico         | Ciclo |
| ------------------- | ----: |
| Promedio            |  3.03 |
| Mediana             |     3 |
| Mínimo              |     1 |
| Máximo              |     7 |
| Desviación estándar |  1.49 |

Esto refleja una concentración importante de estudiantes en los primeros ciclos, aunque existen registros que alcanzan hasta el séptimo ciclo.

### 🎂 Edad

Para la variable edad se dispone de **16,433 registros válidos**.

| Estadístico         |           Edad |
| ------------------- | -------------: |
| Promedio            | **22.92 años** |
| Mediana             |    **22 años** |
| Q1                  |        20 años |
| Q3                  |        24 años |
| Mínimo              |        16 años |
| Máximo              |        78 años |
| Desviación estándar |           5.05 |

El dato más representativo es la **mediana de 22 años**: la mitad de los estudiantes tiene 22 años o menos.

Además, el 50% central de la población se encuentra entre **20 y 24 años**, lo que permite identificar un perfil predominantemente joven.

El máximo de 78 años también evidencia la presencia de registros alejados del comportamiento central, por lo que la edad debe analizarse considerando posibles valores atípicos y el contexto académico.

---

## 🔎 Hallazgos

### 1. Una matrícula prácticamente equilibrada por sexo

La distribución 50.03% vs. 49.97% muestra que, en términos agregados, no existe una diferencia significativa entre mujeres y hombres.

### 2. La población se concentra en edades tempranas

Con una mediana de **22 años** y un rango intercuartílico de **20 a 24 años**, los datos muestran una fuerte concentración alrededor de la etapa universitaria tradicional.

### 3. El ciclo 3 representa el centro de la distribución

El promedio de **3.03 ciclos** y la mediana de **3** indican que el punto central de la población se encuentra alrededor del tercer ciclo.

### 4. Los promedios no cuentan toda la historia

La diferencia entre el promedio de edad (**22.92**) y la mediana (**22**) es una señal de que existen valores superiores que elevan ligeramente la media. Esto demuestra la importancia de complementar los promedios con **mediana, cuartiles y dispersión**.

---

## 🧠 Metodología

El proyecto siguió un flujo básico de análisis de datos:

```text
Datos
  ↓
Limpieza y preparación
  ↓
Exploración (EDA)
  ↓
Estadística descriptiva
  ↓
Identificación de patrones
  ↓
Visualización
  ↓
Interpretación
  ↓
Infografía final
```

### Herramientas utilizadas

* 🐍 **Python**
* 🐼 **Pandas**
* 📊 **Matplotlib**
* 📈 **Seaborn**
* 📓 **Jupyter Notebook**

---

## 📊 Visualización

Los resultados fueron sintetizados en una infografía diseñada para comunicar los principales hallazgos de manera clara y accesible.

La visualización busca aplicar un principio fundamental del análisis de datos:

> **No se trata de mostrar todos los datos, sino de mostrar aquello que ayuda a entenderlos.**

---

## 📁 Estructura del proyecto

```text
DATA_ANAYLISIS_UNFVMATRICULADOS/
│
├── data/
│   └── ...
│
├── notebooks/
│   └── analisis_matricula.ipynb
│
├── images/
│   └── infografia-unfv-2026.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚠️ Consideraciones

Los resultados presentados corresponden al **dataset utilizado para este proyecto** y deben interpretarse dentro de su alcance.

No se incluyen datos personales identificables de estudiantes.

La UNFV establece que la información de matrícula es procesada por la Oficina Central de Registros Académicos (OCRAC) y que la información académica adquiere carácter oficial una vez culminado el proceso de validación y consolidación correspondiente.

Por ello, este proyecto debe entenderse como un **ejercicio de análisis y visualización de datos**, y no como una publicación estadística oficial de la universidad.

---

## 🚀 Próximos pasos

Este análisis puede ampliarse incorporando:

* Análisis por escuela profesional.
* Comparación entre facultades.
* Evolución histórica de la matrícula.
* Análisis de estudiantes por rango de edad.
* Detección estadística de valores atípicos.
* Dashboard interactivo con **Power BI** o **Plotly**.
* Modelos predictivos para estudiar tendencias futuras de matrícula.

---

## 👨‍💻 Autor

**Sandro Miñope**

Proyecto personal de **Data Analytics & Data Visualization**.

---

### 📚 Referencia institucional

Universidad Nacional Federico Villarreal. (2026). Estudiantes matriculados 2026 - Universidad Nacional Federico Villarreal - UNFV [Conjunto de datos]. Plataforma Nacional de Datos Abiertos.
https://www.datosabiertos.gob.pe/dataset/estudiantes-matriculados-2026-universidad-nacional-federico-villarreal-unfv
