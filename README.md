# Módulo 3: Optimización del Talento y Retención de Empleados

---

## 🚀 Resumen del Proyecto

En el competitivo panorama empresarial actual, la **retención de empleados** y la **satisfacción laboral** son factores críticos que impactan directamente la productividad, la moral y la rentabilidad de una organización. Este proyecto aborda estas problemáticas, desarrollando un análisis de datos exhaustivo para **ABC Corporation**, una consultora tecnológica fundada en 1980 en California, especializada en soluciones de IA y Machine Learning.

Nuestro objetivo principal es **identificar los factores clave que influyen en la satisfacción en el trabajo y la retención de empleados**, proporcionando a ABC Corporation información valiosa para la toma de decisiones estratégicas.

---

## 🎯 Objetivos del Proyecto

Este proyecto académico busca consolidar y aplicar conocimientos clave en diversas áreas:

* **Consolidar conocimientos de Python y SQL:** Aplicando técnicas de manipulación, análisis y visualización de datos, así como diseño y gestión de bases de datos.
* **Control de versiones en equipo:** Aprender las ventajas y gestionar los conflictos inherentes al trabajo colaborativo con Git y GitHub.
* **Implementar Scrum y Agile:** Trabajar bajo el marco de Scrum, fomentando la mejora continua, la transparencia y la adaptación.
* **Mejorar la comunicación:** Fortalecer la comunicación interna del equipo y las habilidades de presentación pública.

---

## 📋 Fases del Proyecto

El proyecto se estructura en varias fases:

### Fase 1: Análisis Exploratorio de Datos (EDA)

Comprender a fondo el conjunto de datos `hr_raw_data.csv`. Esta fase implica un análisis detallado para familiarizarnos con la información disponible, identificar patrones iniciales y detectar posibles problemas de calidad de datos.

### Fase 2: Transformación de Datos

Preparación de los datos para el análisis. Se realizarán diversas transformaciones mediante funciones de Python para asegurar la integridad y consistencia de la información. Algunas transformaciones clave incluyen:

* **Estandarización de `Gender`:** Reemplazo de valores numéricos (0, 1) por etiquetas intuitivas ("Male", "Female").
* **Conversión de tipos de datos:** Corrección de la columna `Total_working_years` (y otras similares) de tipo numérico 'int'.
* **Manejo de duplicados:** Evaluación y, si es necesario, eliminación de filas duplicadas.
* **Corrección de inconsistencias:** Solución de valores negativos en `DistanceFromHome`.
* **Normalización de errores tipográficos:** Unificación de valores inconsistentes (ej. "Marreid" a "Married" en `MaritalStatus`).
* **Identificación y eliminación de columnas redundantes.**

### Fase 3: Visualización de Datos

Generación de un informe con visualizaciones en Python (utilizando librerías como `matplotlib`, `seaborn`, etc.) para ofrecer a ABC Corporation una comprensión profunda del contexto general de la empresa. Este informe destacará tendencias, áreas de mejora y fortalezas.


## 📊 Conjunto de Datos

El análisis se basa en el archivo `hr_raw_data.csv`, que contiene información relevante sobre los empleados. Las columnas clave incluyen:

* `Age`: Edad del empleado.
* `Attrition`: Indica si el empleado dejó la empresa (Yes/No).
* `BusinessTravel`: Frecuencia de viajes laborales.
* `DailyRate`: Tarifa diaria estimada.
* `Department`: Departamento del empleado.
* `DistanceFromHome`: Distancia desde el hogar al trabajo.
* `Education`: Nivel educativo.
* `EducationField`: Campo de estudio.
* `employeecount`: Valor constante "1".
* `employeenumber`: Número de identificación del empleado.
* `EnvironmentSatisfaction`: Satisfacción con el ambiente laboral.
* `Gender`: Género.
* `HourlyRate`: Tarifa por hora.
* `JobInvolvement`: Nivel de compromiso.
* `JobLevel`: Nivel jerárquico.
* `JobRole`: Función específica.
* `JobSatisfaction`: Satisfacción general en el puesto.
* `MaritalStatus`: Estado civil.
* `MonthlyIncome`: Ingreso mensual.
* `MonthlyRate`: Tarifa mensual.
* `NUMCOMPANIESWORKED`: Número de empresas previas.
* `OverTime`: Horas extras (Yes/No).
* `PercentSalaryHike`: Incremento salarial porcentual.
* `PerformanceRating`: Evaluación de desempeño.
* `RelationshipSatisfaction`: Satisfacción con relaciones interpersonales.
* `StandardHours`: Clasificación de jornada.
* `StockOptionLevel`: Nivel de opciones sobre acciones.
* `TOTALWORKINGYEARS`: Años totales de experiencia laboral.
* `TrainingTimesLastYear`: Sesiones de entrenamiento.
* `WORKLIFEBALANCE`: Balance vida personal y laboral.
* `YearsAtCompany`: Años en la empresa actual.
* `YearsInCurrentRole`: Años en el rol actual.
* `YearsSinceLastPromotion`: Años desde la última promoción.
* `YEARSWITHCURRMANAGER`: Años con el mismo gerente.
* `DateBirth`: Año de nacimiento.
* `Salary`: Salario anual.
* `RoleDepartament`: Combinación de rol y departamento.
* `NUMBERCHILDREN`: Número de hijos.
* `RemoteWork`: Trabajo remoto (Yes/No).

* ---

## 📅 Planificación del Proyecto (Scrum)

El proyecto se desarrollará en **2 Sprints**. 

* **Sprint Planning:** Sesión inicial para definir el alcance y los objetivos del sprint.
* **Desarrollo:** Trabajo en las tareas asignadas durante el sprint.
* **Sprint Review:** Presentación de los resultados obtenidos y recopilación de *feedback*.
* **Retrospectiva:** Análisis del desempeño del equipo y mejora continua.

### Historias de Usuario

La gestión del proyecto se realiza a través de **Historias de Usuario** para asegurar que el equipo entienda y satisfaga las necesidades del negocio:

* Como analista, quiero **explorar el DataFrame** para entender los datos disponibles.
* Como analista, quiero **realizar un EDA exhaustivo** para identificar las transformaciones necesarias en los datos.
* Como ingeniero de datos, quiero **transformar los datos** para asegurar su calidad y consistencia.
* Como analista, quiero **decidir qué visualizaciones** serán más efectivas para comunicar los hallazgos.

---

## 🤝 Colaboración

¡Agradecemos la colaboración de todos los miembros del equipo en este emocionante proyecto!

  Gemma, Beatriz, Génesis, Irantzu(irurme)
