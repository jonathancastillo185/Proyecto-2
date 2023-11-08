<h1 align="center"> PROYECTO INDIVIDUAL Nº2</h1>
<h1 align="center">InterLink Telecomunicaciones</h1>

## Nuestro Rol:

<h3>En esta ocasión, la empresa InterLink de telecomunicaciones se ha comunicado con nuestra consultora especializada en el análisis de datos, con el fin de obtener una visión integral y detallada sobre el estado actual de las diversas tecnologías, velocidades y tendencias que imperan en el mercado de las telecomunicaciones a lo largo y ancho del país.

En consecuencia, se nos ha brindado acceso a la web oficial de [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)
, la cual contiene registros y estadísticas vitales para comprender el panorama global de las telecomunicaciones en territorio nacional Argentino. Estos registros abarcan aspectos esenciales, desde la evolución de la infraestructura tecnológica hasta los patrones de uso y adopción de servicios por parte de los usuarios.

Nuestro objetivo se enfoca en llevar a cabo un análisis profundo de estos datos, empleando técnicas de exploración, procesamiento y visualización. La finalidad de esta iniciativa radica en presentar a la empresa un informe exhaustivo y analítico que permita identificar patrones, proponer mejoras y, en última instancia, respaldar la toma de decisiones estratégicas en el ámbito de las telecomunicaciones.</h3>

## ETL:

![Alt text](/image/image2.png)

<h3>Hemos realizado los correspondientes procesos de limpieza, normalización y análisis detallado de la información proporcionada. Se han llevado a cabo tareas para identificar y gestionar valores nulos, así como para verificar la presencia de registros duplicados. También se ha trabajado en la estructuración de los datos, preparándolos para su interpretación y análisis subsiguientes.</h3>

## Analisis Exploratorio de los Datos:

<h3>Hemos realizado un análisis exploratorio de los datos (EDA) mediante la utilización de una variedad de herramientas y librerías, que incluyen Pandas, NumPy, Matplotlib y Seaborn. Este análisis ha permitido visualizar y comprender la distribución de variables, identificar tendencias y explorar posibles correlaciones entre los distintos parámetros relevantes en el sector de las telecomunicaciones.

El análisis exploratorio de los datos se realizó desde un enfoque objetivo, centrándose en la descomposición en capas de la información proporcionada. Iniciamos con el historial temporal, abordando la notable expansión de las redes de conexión a lo largo de los años, específicamente desde 2014 hasta el cuarto trimestre del año en curso, 2022.</h3>

![Alt text](/image/image.png)

<h3>Este primer vistazo general nos ofrece una imagen clara del enfoque predominante en esta área: principalmente se centró en las cercanías de la provincia de Buenos Aires para luego expandirse hacia otras áreas adyacentes.
Otra conclusion por la cual mas adelante indagaremos en outliers, habla sobre el gran incremento ocurrido entre el 2016 al 2020, a manera de spoiler en general suele suceder que los grandes cambios surgen luego de inversiones e innovacion de infraestructuras a nivel provincial, recordemos que las medidas promedio son sensibles a los valores extremos.</h3>



![Alt text](/image/image3.png)

<h3>La métrica principal dentro de este intervalo temporal es el crecimiento trimestral. Es crucial que este crecimiento siga una tendencia exponencial para lograr una cobertura más amplia en todo el territorio. Debemos considerar que nuestro país cuenta con una gran población, pero actualmente solo alcanzamos, en promedio, el 67% de los hogares con conexión a las redes. En base a lo anterior, proponemos un incremento mínimo trimestral del 2% y proponemos designarlo como un KPI.
Este crecimiento gradual en la cantidad de conexiones por hogar presupone una expansión significativa hacia zonas aún no exploradas por la infraestructura de telecomunicaciones.
</h3>

---

<h3>Seguimos con el desgloze, luego de realizar la exploracion sobre el historial temporal, diviendolo por anios y trimestres, procedemos a extraer informacion sobre el incremento porcentual trimestral, a continuacion les vamos a mostrar una grafica haciendo referencia a la diferencia entre el porcentaje incrementado entre un trimestre y otro.</h3>

![Alt text](/image/image1.png)

<h3>Tomando como referencia los valores reflejados en el grafico, se llego a la conclusion de que el segundo y tercer trimestre de cada anio tienen un aumento significativo a diferencia del resto.</h3>

<h3>Informacion adicional: 

- A finales del 2019, ocurrio un cambio de gobierno en la nacion argentina.

- El 20 de marzo del 2020 inicio la etapa de pandemia.</h3>


<h2>A nivel global, hemos llegado a la conclusión de priorizar 2 KPIs:</h2>

<h2>1) Incrementar el porcentaje de adquisición en los trimestres 1 y 4, con posibles acciones tales como:</h2>

<h3>a. Priorizar la publicidad en las etapas escolares al comienzo del trimestre 1.</h3>
<h3>b. Ofrecer descuentos durante las festividades de fin de año en el trimestre 4.</h3>

<h2>2) Aumentar el porcentaje de adquisición de internet durante situaciones de cambios gubernamentales, con posibles acciones como:</h2>

<h3>a. Centrar la publicidad en la continuidad de las suscripciones a largo plazo (para reducir costos a largo plazo).</h3>

---

<h3>En el siquiente grafico se analizo la informacion a nivel provincial, este enfoque trata de explicar un poco mas a fondo diferencias entre el promedio de acceso a internet por cada 100 hogares, claramente tenemos provincias en las que el promedio es mucho mas alto, puede ser por falta de infraestructura o quizas por falta de poblacion, tengamos en cuenta que no todas las provincias cuentan con una densidad poblacional similar.</h3>

![Alt text](/image/image4.png)

<h3>Para poder tener un angulo mas exacto vamos a realizar la siguiente grafica en donde vemos el crecimiento porcentual del promedio de acceso a internet por cada 100 habitantes</h3>

![Alt text](/image/image5.png)

<h3>Como podemos obserbar en el año 2016 Santiago del Estero tenemos un incremento exponencial del promedio de acceso a internet por cada 100 hogares, y lo podemos atribuir a que Se lanzó el programa "Mi Pueblo Conectado" en Santiago del Estero.</h3>

[Visita la página oficial de la noticia Santiago del Estero](https://www.argentina.gob.ar/noticias/se-lanzo-el-programa-mi-pueblo-conectado-en-santiago-del-estero-con-entrega-de-equipamiento)

<H3>Otro valor fuera de lo comun es el incremento porcentual de la provincia de San Luis, pero esto de deve a un programa creado en conjunto con el gobierno nacional, su finalidad fue extender una red inalambrica que abarca la mayor parte de la provincia, claramente esto provoco que el acceso por cada 100 hogares incremente su valor de forma exponencial luego de este periodo</h3>

[Visita la página oficial de la noticia San Luis](https://agenciasanluis.com/notas/2018/07/13/el-servicio-de-wifi-gratuito-amplia-los-beneficios-transversalmente-a-todos-los-sectores-de-la-comunidad-de-san-luis/)

---

<h2>Procedemos con el enfoque Provincial del promedio de accesos a internet por cada 100 hogares anual</h2>

![Alt text](/image/image6.png)

<h3>El principal fin de esta visualizacion es comprender el valor de cada provincia, y ademas poder crear una tabla de categorias en donde clasificamos las provincias en 3 sectores en relacion al Volumen de acceso Alto, Medio y Bajo.</h3>

![Alt text](/image/image7.png)

<h3></h3>