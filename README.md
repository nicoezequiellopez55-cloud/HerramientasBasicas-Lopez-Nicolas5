# HerramientasBasicas-Nicolas-Lopez
## Metodología de trabajo
El presente proyecto se desarrolló siguiendo un enfoque estructurado de análisis de datos, combinando herramientas de programación y visualización para obtener conclusiones relevantes a partir del dataset de acciones del S&P 500. Para esto primeramente definimos nuestro objetivos y preguntas para definir el desarrollo del trabajo

## Dataset seleccionado
Link:https://mavenanalytics.io/data-playground/s-p-500-stock-prices

## Objetivo y preguntas iniciales
Objetivo: Analisis del valor de las acciones de S&P 500 entre 2014 y 2017
Preguntas:¿como evoluciona el valor general de las acciones a lo largo del tiempo?¿Cuales fueron las de mejor rendimiento en todo este tiempo y las de peor?¿Podemos observar correlación entre las mejores acciones?

### Exploración
En una primera etapa, se llevó a cabo un análisis exploratorio inicial con el objetivo de comprender la estructura del dataset y detectar patrones generales en el comportamiento de las variables. 

### Ingesta y Limpieza
Posteriormente, se verifico la correcta tipificación de los ddatos y asegurando la calidad de la información. Esto incluyó la conversión de fechas y la eliminacion de valores nulos ya que representaban un bajo porcentaje dentro del total y segun nuestro analisis no era necesario conservarlos.

### Exploración y visualización
A continuación, se calcularon métricas clave para el análisis, destacándose el rendimiento porcentual de cada acción, obtenido a partir de la comparación entre su valor inicial y final dentro del período considerado. Este cálculo permitió identificar las empresas con mejor y peor desempeño, facilitando su posterior comparación.En paralelo, se analizó la evolución general del mercado mediante el cálculo del precio promedio de las acciones a lo largo del tiempo, lo que permitió observar tendencias, fluctuaciones y posibles cambios en el comportamiento global.

Asimismo, se profundizó el análisis mediante el estudio de la correlación entre las acciones con mejor rendimiento, utilizando una matriz de correlación representada a través de un heatmap. Esta herramienta permitió identificar relaciones entre los movimientos de los precios y detectar comportamientos similares o independientes entre distintas empresas.

### Construcción de Dashboard
Finalmente, todos los resultados obtenidos fueron integrados en un dashboard interactivo desarrollado en Power BI, el cual permite visualizar de manera clara y dinámica la evolución del mercado, comparar el rendimiento de las acciones y analizar sus relaciones, facilitando la interpretación de los datos y la comunicación de los hallazgos.
## Bibliografia
GitHub Docs. (s.f.). Administrar archivos en un repositorio. https://docs.github.com/es/repositories/working-with-files/managing-files
Pandas documentation — pandas 2.3.2 documentation. (s/f). Pydata.org. Recuperado el 14 de septiembre de 2025, de https://pandas.pydata.org/docs/
Microsoft Learn. (s.f.). Crear medidas en Power BI Desktop. https://learn.microsoft.com/es-es/power-bi/transform-model/desktop-tutorial-create-measures
