# Laboratorios AWS SageMaker 3.1, 3.2 y 3.3

## Información del estudiante

**Estudiante:** Juan Pablo Sánchez Nieto
**Programa:** Ingeniería de Software
**Universidad:** Universidad de La Salle
**Actividad:** Análisis exploratorio de datos y preprocesamiento
**Entorno:** Amazon SageMaker / AWS Academy

---

## 1. Descripción de la actividad

La presente actividad corresponde al desarrollo práctico de los laboratorios 3.1, 3.2 y 3.3 de Amazon SageMaker, orientados al proceso inicial de preparación y análisis de datos para aplicaciones de aprendizaje automático.

El trabajo integra actividades de carga e importación de datos, exploración de la estructura y calidad de un conjunto de datos, análisis estadístico y visualización, además de técnicas básicas de transformación y codificación de datos categóricos.

El desarrollo se realizó individualmente en el entorno de laboratorio proporcionado por AWS Academy, utilizando notebooks de Jupyter ejecutados en Amazon SageMaker.

---

## 2. Objetivo

Desarrollar la capacidad de realizar un análisis exploratorio de datos (EDA) y aplicar técnicas básicas de preprocesamiento en un entorno real de trabajo, integrando la carga, limpieza, exploración, transformación y visualización de datos para comprender su estructura y calidad antes de utilizarlos en procesos de aprendizaje automático.

---

## 3. Entorno de trabajo

Para el desarrollo de la actividad se utilizaron los siguientes recursos:

* AWS Academy.
* Amazon SageMaker.
* JupyterLab.
* Python.
* Pandas.
* NumPy.
* SciPy.
* Matplotlib.
* Seaborn.
* Git.
* GitHub.

Durante el desarrollo de los notebooks fue necesario instalar algunas dependencias de Python que no se encontraban disponibles inicialmente en el entorno de ejecución, utilizando el administrador de paquetes de Python desde el notebook.

---

# 4. Laboratorio 3.1 — Creación e importación de datos

## 4.1 Propósito

El Laboratorio 3.1 tuvo como propósito familiarizarse con el entorno de Amazon SageMaker y realizar la creación, importación y preparación inicial de datos dentro de un notebook.

Esta etapa permitió establecer el entorno de trabajo que posteriormente fue utilizado para las actividades de exploración y preprocesamiento.

## 4.2 Desarrollo

Durante este laboratorio se realizó el acceso al entorno de laboratorio de AWS Academy y se trabajó con una instancia de Amazon SageMaker.

Se creó y ejecutó un notebook de Jupyter, realizando las operaciones necesarias para importar y trabajar con los datos proporcionados por el laboratorio.

El notebook correspondiente al desarrollo es:

`Untitled1.ipynb`

## 4.3 Resultado

Como resultado se obtuvo un notebook funcional con las actividades correspondientes al Laboratorio 3.1.

El archivo fue incorporado al repositorio GitHub y versionado mediante Git desde la instancia de trabajo.

---

# 5. Laboratorio 3.2 — Exploración de datos

## 5.1 Propósito

El Laboratorio 3.2 tuvo como objetivo realizar un análisis exploratorio de datos (EDA), utilizando herramientas de Python para conocer la estructura, distribución, dispersión y relaciones entre las variables del conjunto de datos.

## 5.2 Dataset utilizado

El laboratorio trabaja con el conjunto de datos **Vertebral Column**, relacionado con pacientes ortopédicos.

El conjunto contiene seis variables biomecánicas:

* `pelvic_incidence`
* `pelvic_tilt`
* `lumbar_lordosis_angle`
* `sacral_slope`
* `pelvic_radius`
* `degree_spondylolisthesis`

Además, contiene una variable de clasificación denominada `class`.

Las categorías originales permiten distinguir entre pacientes normales y diferentes tipos de anomalías de la columna vertebral. Para determinadas actividades del laboratorio se utiliza una clasificación binaria entre **Normal** y **Abnormal**.

## 5.3 Exploración realizada

Durante el laboratorio se utilizaron herramientas de Pandas para examinar:

* Dimensiones del conjunto de datos.
* Nombres de las variables.
* Tipos de datos.
* Estadísticas descriptivas.
* Distribución de las clases.
* Posibles valores atípicos.
* Distribución de las variables.
* Relaciones entre las variables.
* Correlaciones entre características y variable objetivo.

También se utilizaron gráficos para facilitar la interpretación de los datos, incluyendo:

* Gráficos de líneas.
* Gráficos de densidad.
* Histogramas.
* Diagramas de caja.
* Gráficos de dispersión.
* Matrices de dispersión.
* Mapa de calor de correlaciones.

## 5.4 Resultado

El análisis permitió comprender la estructura y características estadísticas del conjunto de datos antes de aplicar procesos posteriores de aprendizaje automático.

En particular, se pudo observar la distribución de las variables biomecánicas, identificar posibles valores atípicos y analizar la relación existente entre las características y la variable de clasificación.

El notebook correspondiente es:

`3_2-machinelearning.ipynb`

---

# 6. Laboratorio 3.3 — Codificación de datos categóricos

## 6.1 Propósito

El Laboratorio 3.3 estuvo orientado al tratamiento y codificación de variables categóricas como parte del proceso básico de preprocesamiento de datos.

La codificación es necesaria porque muchos algoritmos de aprendizaje automático trabajan con representaciones numéricas y, por esta razón, las categorías deben transformarse de una manera adecuada antes de ser utilizadas por los modelos.

## 6.2 Desarrollo

Durante el laboratorio se trabajó con las instrucciones proporcionadas en el notebook oficial de AWS Academy y se realizaron las transformaciones necesarias sobre los datos categóricos.

El proceso permitió comprender la importancia de identificar correctamente las variables categóricas y seleccionar una representación numérica apropiada para su posterior utilización en procesos de aprendizaje automático.

## 6.3 Resultado

Como resultado se obtuvo un notebook funcional con las actividades correspondientes al proceso de codificación de datos categóricos.

El notebook utilizado es:

`3_3-machinelearning.ipynb`

---

# 7. Gestión del código mediante Git y GitHub

El desarrollo de los laboratorios fue acompañado por un proceso de control de versiones utilizando Git.

El repositorio utilizado para centralizar los resultados es:

**AWS-Lab-3.1-3.2-3.3**

Los notebooks fueron incorporados progresivamente al repositorio desde la instancia de Amazon SageMaker.

Se realizaron commits independientes para mantener trazabilidad sobre el desarrollo de cada laboratorio.

### Historial de trabajo

* Laboratorio 3.1 — incorporación del notebook correspondiente.
* Laboratorio 3.2 — incorporación y actualización del notebook.
* Laboratorio 3.3 — incorporación del notebook correspondiente.
* README — documentación final de la actividad.

La utilización de Git permitió mantener un historial de cambios y disponer de una copia versionada del trabajo realizado durante el laboratorio.

---

# 8. Estructura del repositorio

Actualmente el repositorio contiene los principales archivos correspondientes al desarrollo:

```text
AWS-Lab-3.1-3.2-3.3/
│
├── README.md
├── Untitled1.ipynb
├── 3_2-machinelearning.ipynb
└── 3_3-machinelearning.ipynb
```

---

# 9. Evidencias

De acuerdo con las indicaciones de la actividad, se deben documentar mediante capturas de pantalla las principales etapas del desarrollo.

Las evidencias deben permitir verificar:

1. Acceso a la plataforma de AWS Academy.
2. Configuración y acceso a la instancia de Amazon SageMaker.
3. Ejecución del Laboratorio 3.1.
4. Ejecución del Laboratorio 3.2.
5. Ejecución del Laboratorio 3.3.
6. Resultados finales de cada laboratorio.
7. Gestión del repositorio mediante Git.
8. Commits realizados desde la instancia de laboratorio.

Las capturas correspondientes deberán incorporarse a este repositorio y relacionarse con las secciones respectivas de este documento.

---

# 10. Reflexión final

El desarrollo de los tres laboratorios permitió comprender que el trabajo con datos constituye una etapa fundamental dentro del desarrollo de soluciones de aprendizaje automático. Antes de construir un modelo, es necesario conocer la estructura y calidad de los datos, identificar sus características, analizar su distribución y realizar las transformaciones necesarias.

El Laboratorio 3.1 permitió establecer una base práctica para trabajar con datos dentro de Amazon SageMaker. Posteriormente, el Laboratorio 3.2 permitió aplicar técnicas de análisis exploratorio mediante Python, utilizando estadísticas descriptivas y diferentes visualizaciones para interpretar el comportamiento de las variables.

Finalmente, el Laboratorio 3.3 permitió comprender la importancia del preprocesamiento de las variables categóricas y su transformación a representaciones que puedan ser utilizadas posteriormente por algoritmos de aprendizaje automático.

Desde una perspectiva de ingeniería de software, la actividad también permitió fortalecer el uso de herramientas de desarrollo y control de versiones en un entorno de computación en la nube. La utilización conjunta de SageMaker, Jupyter, Python, Git y GitHub permitió establecer un flujo de trabajo reproducible y organizado.

---

# 11. Conclusiones

Los laboratorios permitieron integrar diferentes etapas iniciales del procesamiento de datos: carga, exploración, análisis y transformación.

El análisis exploratorio permitió obtener una visión más clara de la estructura del conjunto de datos y de las relaciones entre sus variables. Asimismo, las actividades de preprocesamiento demostraron la importancia de preparar correctamente los datos antes de utilizarlos en modelos de aprendizaje automático.

El desarrollo en Amazon SageMaker permitió trasladar estos conceptos a un entorno práctico de computación en la nube, mientras que Git y GitHub facilitaron la organización, trazabilidad y conservación del trabajo realizado.

En conjunto, la actividad fortaleció las competencias necesarias para desarrollar flujos iniciales de trabajo en proyectos de ciencia de datos y aprendizaje automático, especialmente en las etapas de preparación y comprensión de los datos.
