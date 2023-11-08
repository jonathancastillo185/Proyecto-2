<h1 align="center"> PROYECTO INDIVIDUAL Nº2</h1>
<h1 align="center">InterLink Telecomunicaciones</h1>

## Nuestro Rol:

<h3>En esta ocasión, la empresa InterLink de telecomunicaciones se ha comunicado con nuestra consultora especializada en el análisis de datos, con el fin de obtener una visión integral y detallada sobre el estado actual de las diversas tecnologías, velocidades y tendencias que imperan en el mercado de las telecomunicaciones a lo largo y ancho del país.

En consecuencia, se nos ha brindado acceso a la web oficial de [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)
, la cual contiene registros y estadísticas vitales para comprender el panorama global de las telecomunicaciones en territorio nacional Argentino. Estos registros abarcan aspectos esenciales, desde la evolución de la infraestructura tecnológica hasta los patrones de uso y adopción de servicios por parte de los usuarios.

Nuestro objetivo se enfoca en llevar a cabo un análisis profundo de estos datos, empleando técnicas de exploración, procesamiento y visualización. La finalidad de esta iniciativa radica en presentar a la empresa un informe exhaustivo y analítico que permita identificar patrones, proponer mejoras y, en última instancia, respaldar la toma de decisiones estratégicas en el ámbito de las telecomunicaciones.</h3>

## ETL:

![Alt text](/image/image2.png)

<h3>Hemos llevado a cabo rigurosos procesos de limpieza, normalización y análisis minucioso de la información suministrada. Estas tareas incluyeron la identificación y gestión de valores nulos, así como la verificación de registros duplicados. Además, nos hemos enfocado en la reestructuración de los datos, preparándolos para su interpretación y análisis posteriores.</h3>

<h3>Gestión de valores nulos, duplicados y outliers:

En particular, respecto a los valores nulos, se procedió a su eliminación siempre y cuando no afectaran el resto del análisis. En todos los conjuntos de datos revisados, no se encontraron valores duplicados. En cuanto a los outliers, se llevó a cabo una búsqueda exhaustiva de explicaciones lógicas, proporcionando contexto y fundamentos para su aparición..</h3>

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
<br>

---

<br>
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
<br>

---

<br>
<h3>En el siquiente grafico se analizo la informacion a nivel provincial, este enfoque trata de explicar un poco mas a fondo diferencias entre el promedio de acceso a internet por cada 100 hogares, claramente tenemos provincias en las que el promedio es mucho mas alto, puede ser por falta de infraestructura o quizas por falta de poblacion, tengamos en cuenta que no todas las provincias cuentan con una densidad poblacional similar.</h3>

![Alt text](/image/image4.png)

<h3>Para poder tener un angulo mas exacto vamos a realizar la siguiente grafica en donde vemos el crecimiento porcentual del promedio de acceso a internet por cada 100 habitantes</h3>

![Alt text](/image/image5.png)

<h3>Como podemos obserbar en el año 2016 Santiago del Estero tenemos un incremento exponencial del promedio de acceso a internet por cada 100 hogares, y lo podemos atribuir a que Se lanzó el programa "Mi Pueblo Conectado" en Santiago del Estero.</h3>

[Visita la página oficial de la noticia Santiago del Estero](https://www.argentina.gob.ar/noticias/se-lanzo-el-programa-mi-pueblo-conectado-en-santiago-del-estero-con-entrega-de-equipamiento)

<H3>Otro valor fuera de lo comun es el incremento porcentual de la provincia de San Luis, pero esto de deve a un programa creado en conjunto con el gobierno nacional, su finalidad fue extender una red de fibra óptica en más de 500 kilómetros que abarca la mayor parte de la provincia, claramente esto provoco que el acceso por cada 100 hogares incremente su valor de forma exponencial luego de este periodo</h3>

[Visita la página oficial de la noticia San Luis](https://agenciasanluis.com/notas/2018/07/13/el-servicio-de-wifi-gratuito-amplia-los-beneficios-transversalmente-a-todos-los-sectores-de-la-comunidad-de-san-luis/)
<br>

---

<br>
<h2>Procedemos con el enfoque Provincial del promedio de accesos a internet por cada 100 hogares anual</h2>

![Alt text](/image/image6.png)

<h3>El principal fin de esta visualizacion es comprender el valor de cada provincia, y ademas poder crear una tabla de categorias en donde clasificamos las provincias en 3 sectores en relacion al Volumen de acceso Alto, Medio y Bajo.</h3>

![Alt text](/image/image7.png)

<h3>Agrupamos las provincias por sus categorias, y procedimos a clasificar las provincias dejando a la vista su promedio de acceso a internet por cada 100 hogares. En este contexto, optamos por seleccionar las provincias pertenecientes al grupo de volumen medio. Este grupo se destaca por su potencial de inversión y crecimiento a corto y mediano plazo, además de su alta densidad poblacional. Es importante resaltar que, a pesar de estas características favorables, estas áreas aún presentan una gran extensión territorial por cubrir en términos de conexiones a internet.</h3>

<h2>A continuacion vamos a realizar un grafico por Provincia comparando su crecimiento porcentual anual en acceso a internet por cada 100 hogares, con el promedio de acceso a internet por cada 100 hogares anual\trimestral</h2>

![Alt text](/image/image12.png)

![Alt text](/image/image13.png)

Solo se visualizan las muestras mas representativas con el fin de no contaminar el desarrollo con graficos poco referentes.

<h3>Como podemos observar en el estudio de los diagramas, la mayoría de las provincias pertenecientes al grupo de volumen medio en la categoría de promedio de accesos por cada 100 hogares experimentaron un aumento exponencial en los años 2017/2018, indicando una clara tendencia en este aspecto. Sin embargo, este punto será abordado más detalladamente en breve, durante el análisis de las tecnologías y la velocidad. Aunque muchos de estos aumentos pueden atribuirse a inversiones conjuntas con el gobierno a través de proyectos destinados a mejorar la conectividad en todo el país, al final del documento se adjuntarán bibliografías que refutan esta afirmación.</h3>
<br>

---

<br>
<h1>Tecnologia y Velocidad por Provincia Anual</h1>

<h3>Como lo dice el titulo ahora abordaremos la informacion en base a la tecnologia implementada en cada provincia, asi como tambien los rangos de valores de descarga con los que cuentan estan provincias del volumen medio de acceso a internet por cada 100 habitantes. Tener este contexto nos va a abrir nuevas ventanas de exploracion y comparacion, todo con el fin de interpretar que esta pasando en esta epoca, y tambien hacia a donde dirigir el esfuerzo para lograr objetivos a futuro.</h3>

<h3>Vamos a tomar los graficos de las muestras mas representativas de cada tecnologia aplicada a una provincia en especifico y realizar la comparacion con su crecimiento en promedio de accesos a internet por cada 100 hogares anial\trimestral.</h3>

![Alt text](/image/image9.png)

![Alt text](/image/image10.png)

![Alt text](/image/image11.png)

Solo se visualizan las muestras mas representativas con el fin de no contaminar el desarrollo con graficos poco referentes.

<h3>Estos graficos analizando el incremento del porcentaje de accesos por tecnologia, nos dan un panorama de hacia a donde van encaminadas las inversiones a futuro en relacion a la conectividad en las diferentes provincias, cada una tiene su nucleo fuerte en tecnologia, en lo unico que podemos afirmar que coinciden es en retrotraer el tipo de coneccion ADSL, ya que es el mas antiguo y esta quedando obsoleto por su falta de estabilidad, asi como tambien por su poca velocidad de transferencia de datos.</h3>
<h3>Dato de color no menor: la tecnologia ADSL es la mas economica.</h3>

<h2>A nivel tecnologia, hemos llegado a la conclusión de priorizar 2 KPIs:</h2>

<h2>1) Aumentar el incremento porcentual de infraestructura Wireless, con posibles acciones tales como:</h2>

<h3>a. Realizar inversiones en diferentes provincias en las cuales por el momento no domina ninguna otra tecnologia a grandes rasgos.</h3>

<h2>2) Aumentar la disminucion porcentual del uso de la tecnologia ADSL, con posibles acciones tales como:</h3>

<h3>a. Reemplazar tirajes de lineas con la tecnologia Fibra optica, la supera con creces en velocidad, costo y estabilidad.</h3>
<br>

---

<br>
<h2>A continuacion vamos a realizar la visualizacion en rango temporal, de las velocidades que forman parte de la infraestructuras de las Provincias pertenecientes al volumen medio de acceso a internet por cada 100 hogares.</h2>

![Alt text](/image/image14.png)

![Alt text](/image/image15.png)

![Alt text](/image/image16.png)


<h3>A modo de comparativa se visualizaron los graficos referentes a las mismas provincias mencionadas anteriormente en el grafico de tecnologias, para comprobar la correlacion que vinculan estos parametros, podemos llegar a la conclusion de que a medida que las tecnologias son mas eficientes a nivel transferencia y estabilidad, afecta directamente en como decanta el publico ubicado en cada Provincia.</h3>

![Alt text](/image/image17.png)

<h3>Un ejemplo sumamente significativo se observa en el caso de la Provincia de San Luis. Se evidencia una correlación directa entre el aumento en la velocidad de internet y la implementación de la infraestructura inalámbrica. Este evento marcó claramente un punto de inflexión temporal, generando un notable incremento en las métricas al proporcionar acceso a esta nueva tecnología a la población. </h3>
<br>

---

<br>

### Tras completar este exhaustivo análisis exploratorio de los datos relacionados con [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/), la empresa de telecomunicaciones, se extraen conclusiones valiosas que servirán como base fundamental para futuros pasos. Estas conclusiones y las hipótesis desarrolladas se utilizarán como cimientos sólidos para la creación de un dashboard informativo. Este dashboard, en conjunto con una narrativa visual a través de storytelling, no solo respaldará múltiples perspectivas, sino que también ofrecerá recomendaciones fundamentadas.

<h3>La visualización de datos proporcionará una ventana a la comprensión más profunda de los patrones, tendencias y posibles oportunidades dentro del entorno de las telecomunicaciones. La presentación de los datos a través de un storytelling persuasivo permitirá explorar y comunicar hallazgos de una manera impactante y efectiva.</h3>

<h3>El objetivo principal radica en aprovechar este análisis para tomar decisiones informadas y estratégicas. Las recomendaciones resultantes de este proceso no solo servirán para optimizar la eficiencia operativa de ENACOM, sino también para guiar el desarrollo de estrategias de crecimiento sostenible.</h3>

<h3>Este análisis no es solo un fin en sí mismo, sino un punto de partida hacia un entendimiento más profundo y una toma de decisiones más informada en el ámbito de las telecomunicaciones. Este cierre marca el comienzo de una fase crucial en la transformación de datos en acciones concretas y significativas.</h3>


<br>
<br>


## Para realizar este estudio de mercado se utiliaron los siguientes Datasets extraidos de la web oficial de [ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/):

- [Historico_velocidad_internet.csv](/Data/historico_velocidad_internet.csv): Este dataset contiene los valores promedio de bajada por provincia, agrupandolos en trimestres y años.

- [Internet_Accesos-por-tecnologia.csv](/Data/Internet_Accesos-por-tecnologia.csv): Este dataset contiene los valores de acceso a cada tecnologia (ADSL, Wireless, Cablemodem, Fibra optica), agrupados por provincia, trimestre y año.

- [Internet_Accesos-por-Velocidad.csv](/Data/Internet_Accesos-por-velocidad.csv): Este dataset contiene los valores de velocidad de bajada en Mbps agrupados por rango, provincia, trimestre y año.

- [Internet_Penetracion_hogares.csv](/Data/Internet_Penetracion_hogares.csv): Este dataset contiene los valores de penetracion de acceso a internet por cada 100 hogares, agrupados por provincia, trimestre y año.

estos fueron los datasets principales utilizados en el analisis, el resto (diferencia_porcentual_anio.csv | Volumen_acceso.csv) son filtros creados para poder trabajar mas eficientemente con la realizacion del dashboard en la aplicacion Power Bi.




Bibliografia:
- https://ushuaia24.com.ar/contenido/1816/mejora-el-servicio-tierra-del-fuego-se-une-a-la-red-de-fibra-optica
- https://agenciasanluis.com/notas/2018/07/13/el-servicio-de-wifi-gratuito-amplia-los-beneficios-transversalmente-a-todos-los-sectores-de-la-comunidad-de-san-luis/
- https://www.argentina.gob.ar/noticias/se-lanzo-el-programa-mi-pueblo-conectado-en-santiago-del-estero-con-entrega-de-equipamiento