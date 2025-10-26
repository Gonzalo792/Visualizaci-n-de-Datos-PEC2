Autor: Gonzalo Sánchez López.
Asignatura: Visualización de Datos.

- Este repositorio recoge las tres visualizaciones elaboradas para la PEC 2 de la asignatura de Visualización de Datos.
- El propósito principal de la práctica es conocer y aplicar tres técnicas diferentes, analizando qué tipo de datos se adapta mejor a cada una y cómo pueden ayudarnos a representar información de forma clara y comprensible.


Las tres técnicas utilizadas son:
1) Word Cloud o nube de palabras.
2) ain Cloud Plot.
3) Bump Chart.
- Cada visualización se ha desarrollado en RStudio con librerías específicas y datos simulados, buscando que el resultado sea comprensible y visualmente atractivo.


1. Word Cloud o nube de palabras (castellano):
La nube de palabras es una técnica muy conocida en visualización de datos. Consiste en mostrar las palabras más relevantes de un texto o conjunto de datos, de modo que las más frecuentes aparecen en mayor tamaño. Es una forma visual de identificar rápidamente los conceptos más repetidos o importantes dentro de un corpus textual.
En este caso, la visualización representa una lista de 14 disciplinas académicas, como Ingeniería, Medicina, Derecho, Psicología o Arte. Las palabras se muestran dentro de la silueta de un ordenador, con diferentes tamaños, colores y orientaciones. De esta forma, la visualización resulta más dinámica y fácil de interpretar.
La idea es que el tamaño de cada palabra refleja su frecuencia o nivel de relevancia dentro del conjunto. Aunque no permite hacer análisis cuantitativos complejos, es una herramienta muy útil para resúmenes visuales, presentaciones o informes en los que se quiere destacar la importancia relativa de distintos temas de forma inmediata.


2. Rain Cloud Plot:
El Rain Cloud Plot es una técnica relativamente reciente que combina tres elementos en una sola visualización: un violin plot, un boxplot y los puntos individuales de los datos. Esto permite ver tanto la forma de la distribución como la dispersión y los valores concretos.
En esta práctica, el gráfico se ha utilizado para representar la satisfacción laboral (en una escala del 0 al 10) en diferentes carreras universitarias. Cada grupo representa una carrera y muestra su distribución de valores. Los datos son simulados, pero reflejan patrones coherentes con situaciones reales.
La visualización permite comparar fácilmente las diferencias entre grupos. Por ejemplo, en el gráfico se observa que Medicina presenta una media de satisfacción más alta y una menor dispersión, mientras que Arquitectura tiene una variabilidad mayor.
Este tipo de gráfico es muy útil en contextos de investigación o análisis de encuestas, ya que muestra de forma conjunta la tendencia central, la variabilidad y la forma de los datos.


3. Bump Chart:
El Bump Chart se emplea para mostrar cómo cambian las posiciones relativas de distintas categorías a lo largo del tiempo. Es una técnica que suele usarse para representar rankings o clasificaciones que evolucionan en varios periodos.
En este caso, se ha representado la evolución del ranking de satisfacción laboral entre 2019 y 2024 para seis carreras diferentes: Medicina, Derecho, Ingeniería, Psicología, Economía y Arquitectura. Cada línea representa una carrera, y su posición vertical indica su lugar en el ranking en cada año.
El gráfico permite ver de forma clara cómo algunas carreras mantienen posiciones estables mientras otras suben o bajan con el paso del tiempo. Por ejemplo, Medicina se mantiene en primer lugar durante todo el periodo, mientras que Ingeniería y Psicología cambian sus posiciones en los puestos intermedios.
Es una visualización muy eficaz cuando se quiere mostrar la evolución de tendencias o cambios de liderazgo sin necesidad de centrarse en los valores absolutos.



Conclusiones generales:
Las tres visualizaciones aplicadas en esta práctica muestran enfoques diferentes dentro del análisis de datos:
La Word Cloud ofrece una visión general y visual del contenido, destacando las palabras más frecuentes de manera intuitiva.
El Rain Cloud Plot permite analizar con detalle la distribución y la variabilidad de los datos cuantitativos.
El Bump Chart muestra de forma muy clara la evolución de las posiciones a lo largo del tiempo, ideal para analizar cambios en rankings o clasificaciones.
Cada técnica tiene su utilidad según el tipo de información que se quiera comunicar. En conjunto, permiten combinar lo visual, lo estadístico y lo temporal para obtener una comprensión más completa de los datos.



Herramientas utilizadas:
- Lenguaje: R.
- Entorno: RStudio.
