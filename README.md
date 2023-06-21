# Proyecto individual 2: "MOOCs" (Data Analyst)
### Por Miguel Vázquez Bernat
---------------------
## Introducción
Segundo proyecto de la parte de Labs del Bootcamp SoyHenry.

Se realizó un análisis exploratorio de distintos datasets provenientes de páginas web cuyo servicio principal son los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés).

Se generó un Dashboard sobre las métricas mas importantes en Power BI, al igual que se establecieron 4 KPIs con el fin de monitorear la eficacia de los objetivos.

------------------
## Contexto

Los MOOCs (cursos masivos abiertos y online, por sus siglas en inglés) han revolucionado el mundo de la educación desde principios de la década pasada, cuando el profesor Sebastian Thrun comenzó con la transmisión online de su curso introductorio a la Inteligencia Artificial. Poco tiempo después, Thrun fundó Udacity y con el pasar de los años se han ido sumando otras plataformas como edX y Coursera, brindando servicios similares: acceso a contenido específico, de calidad y de manera práctica, desde la comodidad del hogar. 

Muchas de estas plataformas tienen contenido gratuito, mientras que el modelo de negocio en general se basa en el pago de suscripciones recurrentes para acceso general o únicas, para acceder a certificaciones o a cursos premium. Con el aumento de la popularidad de los MOOCs, no solo han aparecido nuevas plataformas privadas como las mencionadas anteriormente, sino que también muchas universidades y organizaciones sin fines de lucro han sumado a la oferta haciendo el mercado mucho más competitivo. 

En este contexto, resulta imperante para cada plataforma ajustar sus modelos de negocio, los cursos y el contenido que se ofrece en ellos para lograr captar y retener a la mayor cantidad de clientes.

----------------
## EDA
Primero se extrayeron los datasets desde el siguiente [repositorio.](https://drive.google.com/drive/folders/13qDuB5dQobnJd5FovrGV5pdiycvVGmed?usp=sharing)


Se realizó un EDA (Exploratory Data Analysis) para tener un acercamiento mas profundo hacia este servicio, conociendo sus variables, las palabras que mas se repiten en las reseñas de los cursos, la correlación entre las variables y el porcentaje de personas que se inscriben a cursos introductorios, intermedios y avanzados.

---------------
## Dashboard

Se generó un dashboard interactivo en Power BI sobre el dataset de Udemy, ya que este es el mas completo y nos da una mejor noción de cuales son las métricas mas importantes en un servicio de MOOCs.

En este dashboard se hace énfasis en los cursos con mayor demanda, los cursos con menos demanda y se gráfica por años la cantidad de suscriptores en las diferentes áreas de aprendizaje que existen dentro de este servicio.

Una vez identificadas cuales son las métricas mas importantes, se proponen los siguientes KPIs:

* Tasa de conversión de inscriptos gratuitos a inscriptos pagados con el objetivo de incrementar la tasa en un 15% a comparación con el año anterior.
* Cantidad de suscriptores con el objetivo de incrementar la cantidad de estos un 5% a comparación con el año anterior.
* Promedio de cantidad de clases por curso con el objetivo de estandarizar la cantidad de clases a 27.
* Cantidad de reseñas por curso con el objetivo que cada en cada curso al menos el 5.5% de los suscriptores hagan una reseña.