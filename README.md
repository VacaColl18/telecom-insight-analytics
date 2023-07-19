# telecom-insight-analytics

**Proyecto de Análisis de Acceso a Internet en Argentina**

Este proyecto tiene como objetivo analizar el acceso a Internet en Argentina y proporcionar información sobre la evolución de la cantidad de habitantes con acceso a Internet, las tecnologías de conexión más utilizadas y la distribución de las velocidades de conexión en el país.

**Conjuntos de datos utilizados:**

1. **Acceso por cada 100 habitantes:** Este conjunto de datos proporciona información sobre la evolución de la cantidad de habitantes con acceso a Internet por cada 100 habitantes en el país a lo largo del tiempo.

2. **Acceso por cada 100 hogares:** Este conjunto de datos muestra la evolución de la cantidad de accesos a Internet por cada 100 hogares en diferentes provincias de Argentina.

3. **Tecnologías de conexión:** Este conjunto de datos detalla las diferentes tecnologías de conexión utilizadas en Argentina, como ADSL, cablemodem, fibra óptica, entre otras.

4. **Velocidades de conexión:** Este conjunto de datos presenta la distribución de las velocidades de conexión en el país, desglosadas por rangos de velocidad.

5. **Población por provincia:** Proporciona información sobre la cantidad de habitantes por provincia en Argentina.

6. **Conexiones totales por provincia:** Muestra la evolución de la cantidad total de conexiones a Internet en cada provincia.

7. **Alcance de la fibra óptica:** Proporciona información sobre el porcentaje de hogares que tienen acceso a la tecnología de fibra óptica en diferentes provincias.

**Conclusiones:**

- La cantidad de habitantes con acceso a Internet por cada 100 habitantes en Argentina ha mantenido una tendencia constante en los últimos años.

- Se observa una variación en la evolución del acceso por cada 100 hogares en diferentes provincias. Algunas provincias, como Misiones, Santa Cruz, Santiago del Estero, Formosa y Corrientes, tienen una baja cantidad de acceso por hogar. En cambio, provincias como Córdoba, Santa Fe y Neuquén han experimentado un crecimiento constante.

- La tecnología de fibra óptica ha experimentado un crecimiento constante, a diferencia de otras tecnologías de conexión como el cablemodem.

- La mayoría de las conexiones se encuentran en el rango de 6 a 10 Mbps, mientras que las conexiones de alta velocidad no tienen una participación significativa en provincias excluyendo BS AS

- Se observa una correlación negativa entre la evolución de las conexiones de mas 30mb y las de menos de 30mb

- El alcance de la fibra óptica es relativamente bajo, cubriendo solo alrededor del 30% de las localidades en las provincias analizadas.

**Visualizaciones:**

En el analisis exploratorio, se han utilizado diferentes visualizaciones para representar los datos y resaltar los insights obtenidos. A continuación se muestran algunas de las visualizaciones utilizadas:

**Recomendaciones y Próximos Pasos:**

Basado en los hallazgos y conclusiones del análisis exploratorio de datos, se pueden plantear algunas recomendaciones y próximos pasos para mejorar el acceso a Internet en Argentina:

1. **Ampliar la cobertura de fibra óptica:** Dado que la fibra óptica es la tecnología que muestra un crecimiento constante y ofrece velocidades más altas, se recomienda invertir en la expansión de la infraestructura de fibra óptica en la provincia de Cordoba, donde el procentaje de hogares con acceso a internet es alto, pero la velocidad de conexion es baja.

2. **Mejorar el acceso en provincias con baja conexión por hogar:** Las provincias Chaco presentan una baja cantidad de accesos por hogar cada 100 hogares. Se deben realizar mejoras en la infraestructura y promover el acceso a Internet en esta region.

3. **Impulsar conexiones de alta velocidad:** La mayoría de las conexiones se encuentran en el rango de 6 a 10 Mbps, se debe promover la adopción de velocidades más altas, especialmente en provincias como Ccorrientes, donde se observa que no hay velocidades de conexion de mas de 30mb.

**KPIs:**

1. **Cobertura de fibra óptica en la provincia de Córdoba:** Medir el porcentaje de hogares en la provincia de Córdoba que tienen acceso a Internet a través de fibra óptica. El objetivo es aumentar esta cobertura para mejorar la velocidad y calidad de conexión en la provincia.

2. **Accesos por cada 100 hogares en la provincia de Chaco:** Seguimiento de la cantidad de accesos por cada 100 hogares en la provincia de Chaco. El objetivo es aumentar esta cifra para garantizar un mayor alcance. 

3. **Conexiones de mas de 30mb en Corrientes:** Medir el porcentaje de conexiones de Internet que superan los 30 Mbps, especialmente en provinciasla provincia de Corrientes donde la velocidad de conexión es baja. El objetivo es aumentar este porcentaje para proporcionar una mejor experiencia de navegación.

**Herramientas y Tecnologías utilizadas:**

Durante el desarrollo de este proyecto de análisis exploratorio de datos y visualización, se utilizaron las siguientes herramientas y tecnologías:

1. **Python:** Se empleó el lenguaje de programación Python para realizar el análisis de datos, manipulación de los conjuntos de datos y generación de gráficos. Se utilizaron bibliotecas como Pandas, seaborn, NumPy y Matplotlib para llevar a cabo estas tareas.

2. **Power BI:** Se utilizó Power BI, una herramienta de visualización de datos de Microsoft, para crear el dashboard interactivo.

3. **GitHub:** Se utilizó este repositorio https://github.com/VacaColl18/telecom-insight-analytics como sistema de control de versiones para el seguimiento de los cambios realizados en el proyecto.


**Estructura del repositorio:**

El repositorio está organizado de la siguiente manera:

- **README.md:** Archivo que contiene la descripción del proyecto, las conclusiones, las visualizaciones y las recomendaciones.

- **datasets:** Carpeta que contiene los conjuntos de datos originales utilizados en el proyecto.

- **db_eda:** Carpeta que contiene los conjuntos de datos limpios y procesados utilizados para el análisis exploratorio de datos y la visualización.

- **pbi:** Carpeta que contiene los archivos excel utilizados en el dashboard interactivo de Power BI.

- **notebooks:** ETL: contiene la limpieza de los datos y armado de nuevos dataframes. EDA: contiene el analisis exploratorio de datos y las visualizaciones.

Feedback:

Este proyecto es un trabajo en progreso y siempre es bienvenido cualquier feedback, contribución o sugerencia para mejorarlo.

