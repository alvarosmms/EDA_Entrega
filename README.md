<h1 align="center">📞 EDA del Rendimiento del Call Center 📞</h1>

### <div align="center">📊 Descripción del Proyecto 📊

En la era de la transformación digital, el análisis de datos se ha convertido en una herramienta esencial para optimizar procesos y tomar decisiones informadas. Este proyecto se centra en realizar un Análisis Exploratorio de Datos (EDA) sobre el rendimiento de un Call Center, evaluando la eficiencia de los canales de comunicación y los centros de llamadas. A través de visualizaciones y métricas clave, buscamos identificar patrones, ineficiencias y áreas de mejora que permitan aumentar la satisfacción del cliente y optimizar los recursos.

</div>
-------------------------

### 🎯 **Objetivo del Proyecto** 🎯

El objetivo principal de este proyecto es analizar el rendimiento de los centros de llamadas y los canales de comunicación para responder a las siguientes preguntas clave:

1. ¿Qué canales ofrecen mejor rendimiento en términos de satisfacción del cliente y duración de las llamadas?
2. ¿Cuáles son los centros de llamadas más eficientes?
3. ¿Qué motivos generan mayor volumen y frustración entre los clientes?

-------------------------

### 📊 **Metodología:** 📊

A través de un **EDA** exhaustivo, hemos evaluado las siguientes dimensiones clave:

**Análisis por Canales:**
- Volumen de contactos por canal (Call-Center, Chatbot, Email, Web).
- Duración promedio de las llamadas.
- Distribución de satisfacción (Positivo, Neutral, Negativo).

**Análisis por Centros de Llamadas:**
- Comparación de eficiencia entre los 4 centros principales.
- Relación entre duración promedio, volumen y satisfacción.

**Análisis por Motivo de Contacto:**
- Impacto de razones específicas (Billing Question, Payments, Service Outage).
- Identificación de áreas problemáticas.

-------------------------

### 📌 Contexto y Relevancia 📌

Para entender la necesidad de este análisis, veamos de dónde surge. La transformación digital en la atención al cliente ha generado un debate constante:
- ¿Son realmente efectivos los canales automáticos como Chatbot y Web?
- ¿Los sistemas automatizados están sustituyendo a las personas solo para reducir costos?

La percepción general es que la atención humana proporciona mejores resultados y mayor satisfacción al cliente. Las respuestas a estas preguntas no solo afectan la percepción de los clientes, sino que también tienen implicaciones significativas para la eficiencia y los costos del negocio. Con este análisis, exploraremos si estas percepciones se alinean con la realidad de los datos.

-------------------------

### Descripción de las columnas del dataframe

| **Variable**                     | **Descripción**                                                                 |
|----------------------------------|--------------------------------------------------------------------------------|
| **id**                           | Identificador único de cada registro.                                          |
| **customer_name**                | Nombre del cliente.                                                           |
| **sentiment**                    | Nivel de satisfacción del cliente: Negativo, Neutral o Positivo.                |
| **csat_score**                   | Puntuación de satisfacción del cliente (1-10).                                 |
| **call_timestamp**               | Fecha y hora de la llamada.                                                   |
| **reason**                       | Motivo del contacto (Billing Question, Payments, Service Outage).             |
| **city**                         | Ciudad del cliente.                                                           |
| **state**                        | Estado del cliente.                                                           |
| **channel**                      | Canal utilizado: Call-Center, Chatbot, Email, Web.                            |
| **response_time**                | Tiempo de respuesta: Dentro o fuera del SLA.                                  |
| **call duration in minutes**     | Duración de la llamada en minutos.                                             |
| **call_center**                  | Centro de llamadas asociado.                                                  |

-------------------------

### 🌐 Visualizaciones Clave 🌐

#### **Distribución de Satisfacción por Canal:**
- Un gráfico de barras apiladas muestra que los canales automatizados (Chatbot y Web) tienen un rendimiento comparable al Call-Center humano en consultas simples.

#### **Duración Promedio y Volumen por Centro:**
- Centros con mayor volumen tienden a tener duraciones más largas y una mayor proporción de comentarios negativos.

#### **Impacto del Motivo de Contacto:**
- Consultas relacionadas con "Billing Question" generan los mayores tiempos de llamada y sentimientos negativos.

-------------------------

### 📈 Conclusiones y Propuestas de Mejora 📈

1. **Optimizar Canales Automatizados:**
   - Mejorar la funcionalidad del Chatbot para manejar consultas simples como "Payments".

2. **Entrenamiento para Agentes:**
   - Capacitar a los agentes de centros con bajo rendimiento para resolver eficientemente consultas complejas como "Billing Question".

3. **Redistribución de Recursos:**
   - Reasignar personal y priorizar horarios pico en centros con mayor volumen y duraciones más largas.

4. **Monitoreo Continuo:**
   - Implementar un dashboard interactivo para monitorear en tiempo real el rendimiento de los canales y centros de llamadas.

-------------------------

### 🔧 Construido con 🔧

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-003b57?style=flat-square&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-9A1B30?style=flat-square&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

-------------------------

### ✍️ Autor ✍️

- Alvaro Sanchez Martin.

