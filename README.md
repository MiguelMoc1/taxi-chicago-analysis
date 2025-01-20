# 🚖 Análisis de Datos de Viajes en Taxi en Chicago

Este proyecto se enfoca en analizar datos relacionados con el servicio de taxis en Chicago. Incluye el análisis de la distribución de viajes por empresas, barrios más populares como destinos, y el impacto de las condiciones climáticas en la duración de los viajes.

---

## 📊 Objetivo del Proyecto

1. Identificar patrones y tendencias en el servicio de taxis en Chicago.
2. Analizar los barrios más populares para la finalización de viajes.
3. Evaluar cómo las condiciones climáticas afectan la duración promedio de los viajes.
4. Proporcionar recomendaciones basadas en el análisis para mejorar las operaciones y la satisfacción del cliente.

---

## 🔍 Metodología

### 1. Importación y Exploración de Datos
- **Archivos Importados:**
  - `project_sql_result_01.csv`: Datos de viajes por empresas de taxis (15-16 noviembre 2017).
  - `project_sql_result_04.csv`: Promedio de viajes finalizados en barrios (noviembre 2017).
  - `project_sql_result_07.csv`: Datos de duración de viajes y clima.
- Limpieza de datos y verificación de duplicados.
- Identificación de valores atípicos.

### 2. Análisis Exploratorio de Datos
- Comparación del número de viajes entre empresas.
- Identificación de los 10 barrios más populares para la finalización de viajes.

### 3. Visualización de Datos
- Gráficos de barras para destacar las empresas líderes y los barrios más populares.

### 4. Prueba de Hipótesis
- **Hipótesis nula (H0):** El clima no afecta la duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.
- **Hipótesis alternativa (H1):** El clima afecta la duración promedio de los viajes.
- Análisis estadístico usando pruebas t de Student y Levene.

---

## 🛠️ Lenguajes y Herramientas Utilizadas

- **Python**
  - pandas
  - matplotlib
  - scipy
- **Jupyter Notebook**

---

## 📈 Resultados Principales

1. **Empresas Dominantes:**
   - Flash Cab lidera con 19,558 viajes en dos días.
   - Taxi Affiliation Services y Medallion Leasing también destacan con más de 10,000 viajes cada una.

2. **Barrios Más Populares:**
   - Loop es el destino más frecuente, con un promedio de 10,727.47 viajes.
   - River North y Streeterville son también destinos destacados.

3. **Impacto del Clima en la Duración de los Viajes:**
   - Los sábados lluviosos, la duración promedio de los viajes fue 21% más larga que en días sin lluvia.
   - Pruebas estadísticas confirman que el clima lluvioso tiene un impacto significativo en la duración.

---

## 📌 Conclusiones y Recomendaciones

- **Empresas de Taxis:**
  - Las empresas dominantes podrían optimizar aún más sus operaciones en los barrios más populares.
  - Otras empresas deben analizar estrategias de éxito para competir.

- **Barrios Populares:**
  - Mejorar la disponibilidad y calidad del servicio en Loop, River North y Streeterville.

- **Impacto Climático:**
  - Ajustar la planificación operativa en días lluviosos para minimizar retrasos y mejorar la experiencia del cliente.

---

## ⚙️ Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/taxi_chicago_analysis.git
