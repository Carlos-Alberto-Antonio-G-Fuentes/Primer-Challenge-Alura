# Primer-Challenge-Alura
 
Para este primer Challenge se procedió a crear código en Phyton para analizar los datos de las bases dadas en DataFrames, para lo cual se importó la librería pandas.
La finalidad de este Challenge es ayudar al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, se analizaron los datos de ventas, rendimiento y reseñas de las 4 tiendas de Alura Store. El objetivo fue identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.

Los principales tópicos para medir son los siguientes:

Los ingresos totales de las tiendas.

Las categorías de productos más y menos vendidas.

Las calificaciones promedio de los clientes por tienda.

Los productos más y menos vendidos.

El coste de envío promedio para cada tienda.


Para el código se crearon funciones, se utilizó groupby para agrupar datos, se crearon listas, se utilizó sentencia for, se ordenaron datos de forma ascendente y descendente.
También se generaron gráficos para visualizar los resultados más importantes como: Los ingresos totales de las tiendas, Las calificaciones promedio de los clientes por tienda y El coste de envío promedio para cada tienda, para lo cual se importó la librería matplotlib.pyplot y para matplotlib.ticker se importó FuncFormatter.
Para generar el mapa de calos se importó la librería folium y para folium.plugins se importó HeatMap.

Las conclusiones fueron las siguientes:

•	Si la decisión de vender una tienda o no, se basa exclusivamente en las ventas de la misma, la tienda que presenta los menores ingresos por venta corresponde a la tienda 4, con una venta total de $ 1.038.375.700, con una diferencia de $ 120.000.000 menos respecto de la que lidera las ventas totales por venta, que es la tienda 1, esto es un 10,83% menos. Para más información ver gráfico Total de Ventas por Tienda en el código.

•	Si la decisión se basa por la gestión de cada tienda, la tienda 1 es la que presenta la más baja calificación por tienda dada por los clientes, además de tener los mayores costos promedios de envío por tienda (sus costos exceden en un 10,9% respecto de la tienda con menores costos). Para más información ver gráficos de Promedio de Calificación por Tienda y Promedio de Costo de Envío por Tienda en el código.



