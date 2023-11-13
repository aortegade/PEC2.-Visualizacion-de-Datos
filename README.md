# PEC2. Tecnicas de Visualizacion de Datos
A continuación se presentan tres visualizaciones, elaboradas a través de la herramienta en línea Rawgraph.

# 1. Bubble Chart
Un Bubble Chart (gráfico de burbujas) es una representación visual de datos que utiliza burbujas o círculos para mostrar puntos de datos. Cada burbuja tiene un tamaño proporcional a la variable que estás representando. Además de las coordenadas en el eje X e Y, el tercer eje se representa mediante el tamaño de las burbujas. Esto es útil cuando quieres mostrar tres variables en una sola visualización. Por ejemplo, si estás representando defunciones (eje Y), nacimientos (eje X) y la población (tamaño de burbujas), puedes tener una idea rápida de cómo diferentes categorías se comparan entre sí.

El conjunto de datos se ha obtenido de cruzar distintos ficheros del INE (nacimientos, defunciones y población) de 2021. 
Se encuentran en el siguiente enlace: https://www.ine.es/dynt3/inebase/index.htm?padre=7993&capsel=8053

# 2. Voronoi Diagram
Un Voronoi Diagram es una forma de dividir un plano en regiones basándose en la proximidad a un conjunto de puntos específicos. Cada región en el diagrama contiene todos los puntos más cercanos a uno de esos puntos específicos. Esto crea polígonos llamados celdas de Voronoi, que son útiles en diversos campos. En visualización, se pueden utilizar para resaltar patrones de agrupación y distribución espacial. En el ejemplo propuesto se visualizan los puntos de recarga por barrios en el ayuntamiento de Vigo.

El conjunto de datos se ha obtenido de datos.gob a través del siguiente enlace: https://datos.gob.es/es/catalogo/l01360577-puntos-de-recarga-de-coche-electrico1

# 3. Beeswarm Plot
Un Beeswarm Plot es un tipo de gráfico de dispersión en el que los puntos de datos son colocados a lo largo de un solo eje, evitando superposiciones tanto como sea posible. Cada punto representa un valor de una variable y la posición a lo largo del eje indica la distribución. En lugar de estar alineados en una línea, los puntos se esparcen para evitar la congestión y mejorar la legibilidad. Este tipo de gráfico es especialmente útil cuando tienes muchos puntos y deseas visualizar su distribución sin que se superpongan demasiado. Los gráficos de enjambre a menudo se utilizan en situaciones donde la densidad de datos es alta, y la dispersión de los puntos es crucial para entender la distribución de la variable.

El conjunto se obtiene del INE, obteniendo datos trimestrales de paro, desde 2002 hasta 2023. Se visualizan datos de población activa a lo largo del tiempo, agrupados por CCAA.
Enlace: https://www.ine.es/dynt3/inebase/index.htm?padre=979&capsel=994

Los datos trimestrales se han agrupado en anuales, con datos de tasa de paro promedios. El código se encuentra en el script poblacion_activa.ipynb.
