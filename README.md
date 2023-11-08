<h1 align="center"> PROYECTO INDIVIDUAL Nº2</h1>
<h1 align="center">InterLink Telecomunicaciones</h1>

<p align="center">
  <img src="image/presentacion.jpg" style="width: 600px; height: auto;">
</p>

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

<h3>Este primer análisis general ofrece una visión clara del enfoque predominante en esta área: principalmente se centró en las cercanías de la provincia de Buenos Aires para luego expandirse hacia otras áreas adyacentes.

Una conclusión adicional que merece más investigación está relacionada con los outliers. Se destaca el notable incremento observado entre 2016 y 2020. En general, es común que cambios significativos ocurran después de inversiones e innovaciones en la infraestructura a nivel provincial. Es importante recordar que las medidas promedio pueden verse influenciadas por valores extremos.</h3>



![Alt text](/image/image3.png)

<h3>La métrica principal dentro de este intervalo temporal es el crecimiento trimestral. Es crucial que este crecimiento siga una tendencia exponencial para lograr una cobertura más amplia en todo el territorio. Debemos considerar que nuestro país cuenta con una gran población, pero actualmente solo alcanzamos, en promedio, el 67% de los hogares con conexión a las redes. En base a lo anterior, proponemos un incremento mínimo trimestral del 2% y proponemos designarlo como un KPI.
Este crecimiento gradual en la cantidad de conexiones por hogar presupone una expansión significativa hacia zonas aún no exploradas por la infraestructura de telecomunicaciones.
</h3>
<br>

---

<br>
<h3>Continuamos con el desglose de datos. Tras realizar la exploración del historial temporal, dividido por años y trimestres, procedemos a extraer información sobre el incremento porcentual trimestral. A continuación, presentaremos un gráfico que ilustra la diferencia en el porcentaje de crecimiento entre un trimestre y otro.</h3>

![Alt text](/image/image1.png)

<h3>Tomando como referencia los valores reflejados en el gráfico, se ha llegado a la conclusión de que el segundo y tercer trimestre de cada año presentan un aumento significativo en contraste con los demás.</h3>

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
<h3>El siguiente gráfico se enfoca en el análisis a nivel provincial para examinar las diferencias en el acceso promedio a Internet por cada 100 hogares. Se destaca que algunas provincias muestran un promedio notablemente superior, posiblemente debido a la falta de infraestructura. Por el contrario, las provincias con promedios más bajos podrían atribuirse a una menor densidad poblacional. Es crucial tener en cuenta que la densidad poblacional varía significativamente entre las distintas provincias</h3>

![Alt text](/image/image4.png)

<h3>Para obtener una perspectiva más precisa, generaremos el siguiente gráfico que muestra el crecimiento porcentual del acceso promedio a Internet por cada 100 habitantes.</h3>

![Alt text](/image/image5.png)

<h3>Como se puede observar en el año 2016, en Santiago del Estero se registró un incremento exponencial en el promedio de acceso a Internet por cada 100 hogares. Este aumento puede atribuirse al lanzamiento del programa 'Mi Pueblo Conectado' en Santiago del Estero.</h3>

[Visita la página oficial de la noticia Santiago del Estero](https://www.argentina.gob.ar/noticias/se-lanzo-el-programa-mi-pueblo-conectado-en-santiago-del-estero-con-entrega-de-equipamiento)

<H3>Otro valor excepcional es el incremento porcentual en la provincia de San Luis, atribuible a un programa conjunto con el gobierno nacional. Este programa tenía como objetivo extender una red inalámbrica que abarcara la mayor parte de la provincia. Evidentemente, esto provocó un aumento exponencial en el acceso a Internet por cada 100 hogares, posterior a la implementación de este programa</h3>

[Visita la página oficial de la noticia San Luis](https://agenciasanluis.com/notas/2018/07/13/el-servicio-de-wifi-gratuito-amplia-los-beneficios-transversalmente-a-todos-los-sectores-de-la-comunidad-de-san-luis/)
<br>

---

<br>
<h2>Procedemos con el enfoque provincial del promedio anual de accesos a Internet por cada 100 hogares.</h2>

![Alt text](/image/image6.png)

<h3>El propósito principal de esta visualización es comprender el valor de cada provincia y, además, crear una tabla de categorías donde clasificamos las provincias en tres sectores en relación al volumen de acceso: Alto, Medio y Bajo.</h3>

![Alt text](/image/image7.png)

<h3>Al agrupar las provincias por categorías, procedimos a clasificarlas, mostrando claramente su promedio de acceso a Internet por cada 100 hogares. En este contexto, decidimos enfocarnos en las provincias pertenecientes al grupo de volumen medio. Estas áreas destacan por su potencial de inversión y crecimiento a corto y mediano plazo, además de tener una alta densidad poblacional. Es importante destacar que, a pesar de estas características favorables, estas áreas aún tienen una gran extensión territorial por cubrir en términos de conexiones a Internet</h3>

<h2>A continuación, crearemos un gráfico comparativo por provincia que muestra el crecimiento porcentual anual en el acceso a internet por cada 100 hogares, junto con el promedio anual/trimestral de acceso a internet por cada 100 hogares</h2>

![Alt text](/image/image12.png)

![Alt text](/image/image13.png)

Se presentan únicamente las muestras más representativas con el fin de evitar el exceso de gráficos poco relevantes en el desarrollo del análisis.

<h3>En el análisis de los diagramas, se observa que la mayoría de las provincias clasificadas en el grupo de volumen medio, en términos del promedio de accesos por cada 100 hogares, experimentaron un marcado aumento en los años 2017 y 2018, lo que señala una clara tendencia en este aspecto. Sin embargo, se profundizará más sobre este punto en el análisis de las tecnologías y la velocidad, más adelante en el documento.
Estos incrementos pueden atribuirse a inversiones conjuntas con el gobierno a través de proyectos destinados a mejorar la conectividad en todo el país. No obstante, al final del documento se proporcionarán referencias bibliográficas que cuestionan esta afirmación.</h3>
<br>

---

<br>
<h1>Tecnología y Velocidad por Provincia</h1>

<h3>Siguiendo el título, abordaremos la información relacionada con la tecnología implementada en cada provincia, así como los rangos de valores de descarga presentes en las provincias con un volumen medio de acceso a Internet por cada 100 habitantes. Contar con este contexto nos permitirá abrir nuevas ventanas de exploración y comparación. El objetivo es interpretar lo que está sucediendo en esta época y, además, determinar hacia dónde dirigir nuestros esfuerzos para alcanzar objetivos a futuro</h3>

<h3>Vamos a seleccionar los gráficos de las muestras más representativas de cada tecnología aplicada en una provincia específica y comparar su crecimiento en el promedio de accesos a Internet por cada 100 hogares anual y trimestral.</h3>

![Alt text](/image/image9.png)

![Alt text](/image/image10.png)

![Alt text](/image/image11.png)

Se presentan únicamente las muestras más representativas con el fin de evitar el exceso de gráficos poco relevantes en el desarrollo del análisis.

<h3>Estos gráficos, al analizar el incremento del porcentaje de accesos por tecnología, nos brindan una visión sobre las inversiones futuras en la conectividad de las diferentes provincias. Cada provincia tiene su propio enfoque tecnológico. La única coincidencia notable es el retroceso en la tecnología de conexión ADSL, la cual se está volviendo obsoleta debido a su falta de estabilidad y su baja velocidad de transferencia de datos.</h3>
<h3>Dato relevante: la tecnología ADSL es antigua y económica.</h3>

<h2>A nivel tecnologia, hemos llegado a la conclusión de priorizar 2 KPIs:</h2>

<h2>1) Mejorar el incremento porcentual de la infraestructura inalámbrica, con posibles acciones tales como:</h2>

<h3>a. Invertir en diferentes provincias donde, por el momento, ninguna otra tecnología prevalece de manera general.</h3>

<h2>2) Reducir la disminución del uso porcentual de la tecnología ADSL, con posibles acciones como:</h3>

<h3>a. Sustituir las líneas de ADSL por fibra óptica, ya que La fibra óptica la supera con creces en velocidad, costos y estabilidad.</h3>
<br>

---

<br>
<h2>A continuación, realizaremos la visualización temporal de las velocidades que integran las infraestructuras de las provincias que se encuentran en el grupo de volumen medio de acceso a internet por cada 100 hogares.</h2>

![Alt text](/image/image14.png)

![Alt text](/image/image15.png)

![Alt text](/image/image16.png)


<h3>En una comparativa visual, se han observado los gráficos referentes a las mismas provincias mencionadas anteriormente en el gráfico de tecnologías. Esta comparación tiene como objetivo comprobar la correlación entre estos parámetros. Se puede concluir que a medida que las tecnologías son más eficientes en términos de transferencia y estabilidad, esto incide directamente en la preferencia del público en cada provincia.</h3>

![Alt text](/image/image17.png)

<h3>Un ejemplo sumamente significativo se aprecia en la Provincia de San Luis. Se revela una correlación directa entre el aumento en la velocidad de Internet y la implementación de la infraestructura inalámbrica. Este acontecimiento marcó claramente un punto de inflexión temporal, resultando en un notable aumento en las métricas al brindar acceso a esta nueva tecnología a la población. </h3>
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