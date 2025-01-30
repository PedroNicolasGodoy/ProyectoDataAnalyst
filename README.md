# Análisis de las Telecomunicaciones: Internet, Telefonía Móvil y Televisión

Este proyecto tiene como objetivo analizar el comportamiento de las tecnologías de comunicación, como internet, telefonía móvil y televisión, para ofrecer soluciones personalizadas a un cliente. Los resultados pueden ayudar a diseñar estrategias para la expansión de productos, mejorar la calidad de los servicios y brindar mayores soluciones a los clientes.

# Estructura del Proyecto
El proyecto está compuesto por los siguientes elementos:

EDA-datos: Análisis exploratorio de datos tabulares. 

      https://github.com/PedroNicolasGodoy/ProyectoDataAnalyst/blob/main/EDA-Datos.ipynb
      
georef-notebook: Utilización de API para completar Georeferencia. 

      https://github.com/PedroNicolasGodoy/ProyectoDataAnalyst/blob/main/georef-notebook.ipynb
      
FormatFile-notebook: Transformación de archivos. 

      https://github.com/PedroNicolasGodoy/ProyectoDataAnalyst/blob/main/FormatFile-notebook.ipynb
      
Dashboard: Tablero interactivo en Power BI.
README.md: Este archivo explicativo del proyecto.

# Análisis Exploratorio de Datos (EDA)
En el EDA se examinan patrones de conectividad entre las diferentes provincias. Los puntos clave incluyen:

Análisis de velocidades promedio contratadas comparadas con el ingreso per cápita por provincia.
Comparación de localidades para identificar los usos tecnológicos más comunes o predominantes.
Uso de gráficos y resúmenes estadísticos para obtener insights relevantes.

# Herramientas utilizadas
Se emplearon Python y sus librerías:

Pandas: Manejo y análisis de datos.
Matplotlib y Seaborn: Creación de visualizaciones.
os: Manejo de archivos del sistema operativo.



# Tablero en Power BI
El tablero busca ofrecer una visión interactiva de los datos, permitiendo explorar tendencias por:

Provincia.
Tipos de tecnología (internet, telefonía móvil, televisión).
Segmentaciones y accesos diferenciados.

![image](https://github.com/user-attachments/assets/7ba074a3-1033-41ab-bc9f-3b09e17212b9)

En esta imagen siguiente podemos ver el KPI donde indica la relación entre los accesos en relación a la población y el objetivo a llegar según estudios sobre el crecimiento del sector, también la distribución de los accesos a internet con los diferentes usos de tecnologías y las localidades que nos ayudará a medir la Calidad del servicio

![image](https://github.com/user-attachments/assets/052bb178-b47a-4c2f-8b97-7d7963351c9a)

En la calidad del servicio vemos cuáles son las teconologías utilizadas en ralción al Mbps contratados. Podemos ver que los Mbps de bajada, filtrados para la provincia de Buenos Aires, en el Trimestre 1 y 2, una desviación de 1 para el año 2024.

El KPI muestra la relación de la cantidad de accesos por hogar en relación a la cantidad de hogares que hay por provincia (esto se calculó a partir de un porcentaje de la población económicamente activa de cada provincia) con esto observamos como objetivo cuántos hogares nos faltan por crecer, teniendo en cuenta que tambíen existen otros productos para insertarce en el mercado y mejorar

![image](https://github.com/user-attachments/assets/bc405071-7b1f-40b1-9a9c-b43ded28d93b)

Cuando hablamos de otros productos, nos referimos a "TV por suscripción y satelital" y a "Telefonía prepago, postpago y operativo" podemos ver otro nicho con mucha oportunidad. 

Cabe aclarar que en el gráfico de TV, en el año 2024 únicamente contamos con datos del Trimestre 1 y 2, distinto a los demás años que están completos.

![image](https://github.com/user-attachments/assets/f8ba20dd-1de0-4eb4-9381-f51cb6c5c742)

Finalizando, dejamos algunos enlaces de interes para brindar un mayor contexto. Gracias.

Tamaño Mercado Argentino:      https://www.mordorintelligence.ar/industry-reports/argentina-telecom-market

Servicio de Internet:      https://faecys.org.ar/faecys/wp-content/uploads/2011/11/FAECYS_Boletin_Digital_21.pdf

Proyecciones FMI: 	https://www.forbesargentina.com/money/el-fmi-mejora-proyecciones-economicas-argentina-vuelve-elogiar-milei-n66074

Crecimiento en Argentina: 		https://www.bbc.com/mundo/articles/cv2znn270jyo

![image](https://github.com/user-attachments/assets/e571c4ff-8137-43fc-ade4-5dc981474ce7)


# Resultados Hallados
Tecnologías predominantes: La fibra óptica y el cable módem son las más utilizadas. Su prevalencia varía entre provincias.
Desigualdad de acceso: Las provincias rurales tienen menos accesos a internet, independientemente de la tecnología.
Provincias con mayor conectividad: Buenos Aires, Santa Fe, Córdoba y Mendoza son las líderes en accesos.

# Requisitos para Ejecutar el Proyecto
Python (con las siguientes librerías):

pandas

matplotlib

seaborn

os



Power BI: Para visualizar el tablero interactivo.

