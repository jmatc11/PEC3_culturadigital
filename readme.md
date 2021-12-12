# **PEC3: Visionando el futuro con las gafas de Manovich** 
### **Recurso de aprendizaje de Cultura Digital**
Autor: Antonio Mato 
Fecha: 10/12/2021

## **Introducción** 


En un mundo globalizado y en constante evolución, donde los factores económicos son muy relevantes, he querído aportar dos ejemplos de hibridación con una motivación de economía circular asociado al sector AEC –Architecture, Engineering & Construction-, el segundo mercado industrial más grande del mundo.

![IMAGE ALT TEXT HERE](https://i2.wp.com/blog.esri.es/wp-content/uploads/2021/06/sdgs_poster_936_es.png?resize=768%2C381&ssl=1)


Según el Parlamento Europeo, 
>‘la economía circular es un modelo de producción y consumo que implica compartir, alquilar, reutilizar, reparar, renovar y reciclar materiales y productos existentes todas las veces que sea posible para crear un valor añadido. De esta forma, el ciclo de vida de los productos se extiende’.
<p>
Los dos ejemplos que planteo para identificar la hibridación son SIG (Sistema de Información Geografica) y BIM (Building Information Modeling), los observo desde diferentes aspectos;
</p>
1. Por una parte la creación mediante aplicaciones software de soluciones para la mejora en la gestión de un proyecto, en este caso pondré un ejemplo de una aplicación Software para cada caso. 


<p>Siguiendo la visión de Manovich, podemos observar la evolución de las diferentes herramientas que se utilizaban para la elaboración de un proyecto. Para un pequeño proyecto constructivo se necesitaban un conjunto de herramientas software para la elaboración de un dibujo en 2D con CAD, un calculo de estructuras, instalaciones, iluminación, un renderizado en 3D para su visualización con texturas y vistas, y en resúmen un conjunto de aplicaciones que, aunque aprovechando datos parciales entre ellas, no realizaban un flujo único dentro del proyecto. En estos nuevos desarrollos software el cambio es total, y se unifica en un único Software que incorpora todas las herramientas necesarias para el ciclo de vida del proyecto.


>“Desde esta perspectiva, la nueva especie de medios (un único proyecto, servicio web o programa de software) representa el encuentro de diversas técnicas que anteriormente pertenecían a medios distintos..”

>(Manovich Lev, 2013)
</p>
2. Pero como aspecto más relevante, quiero centrarme en el tratamiento que se realiza de los datos. Esto es un factor determinante en los modelos constructivos durante toda la fase de proyecto. Se genera un estilo predeterminado de metadatos que unidos en un contexto forman un catálogo con información que aporta mejoras sustanciales frente a los antiguos medios utilizados.
<br>

>"... observamos un proceso ininterrumpido de invención de novedades, pero lo que se inventa no son clases totalmente nuevas de medios, sino más bien nuevos elementos (nuevas técnicas para crear, modificar y compartir datos de medios..."

>(Manovich Lev, 2013)

En esta línea, muchos desarrolladores de software plantean diferentes soluciones en los ejemplos que planteo, Graphisoft, Nemetscheck, Autodesk, ARCGIS, QGIS,..

La explotación de datos en el proyecto genera múltipes beneficios en todas sus fases, no solo en el diseño inicial, si no en los procesos posteriores que redunda en una mayor eficiencia en todo el proceso de inicio a fin.

Analicemos los ejemplos a continuación:

## **Re-descubriendo la hibridacion: SIG** 
## SISTEMA DE INFORMACIÓN GEOGRÁFICA

<br>

> Un sistema de información geográfica (SIG), también habitualmente citado como GIS por las siglas de su nombre en inglés Geographical Information System, es un conjunto de herramientas que integra y relaciona diversos componentes que permiten la organización, almacenamiento, manipulación, análisis y modelización de grandes cantidades de datos procedentes del mundo real que están vinculados a una referencia espacial, facilitando la incorporación de aspectos sociales-culturales, económicos y ambientales que conducen a la toma de decisiones de una manera más eficaz.


> La tecnología de los SIG puede ser utilizada para investigaciones científicas, la gestión de los recursos, la gestión de activos, la arqueología, la evaluación del impacto ambiental, la planificación urbana, la cartografía, la sociología, la geografía histórica, el marketing, la logística por nombrar unos pocos. Por ejemplo, un SIG podría permitir a los grupos de emergencia calculando fácilmente los tiempos de respuesta en caso de un desastre natural, o encontrar los humedales que necesitan protección contra la contaminación, o pueden ser utilizados por una empresa para ubicar un nuevo negocio y aprovechar las ventajas de una zona de mercado con escasa competencia.

>Wikipedia_

Las posibilidades de uso de un SIG son inmensas, disponer de información geográfica, vinculada a otros datos genera multiples posibilidades de uso. Es destacable la posibilidad de monitorización de activos que permite optimizar los recursos disponibles mediante las tomas de datos en campo con IoT. La capacidad de analizar los datos disponibles permiten explotar el gran potencial del sistema.

[![IMAGE ALT TEXT HERE](https://upload.wikimedia.org/wikipedia/commons/e/ef/Sig.jpg)](https://es.wikipedia.org/wiki/Sistema_de_informaci%C3%B3n_geogr%C3%A1fica)

En el sector AEC –Architecture, Engineering & Construction- tiene una gran relevancia, y desde áreas como el Urbanismo y el Catastro, a aplicaciones de Emergencia y Seguridad vinculadas a Protección Civil, se obtienen grandes beneficios con esta herramienta.

### **Software: Aplicación QGIS**
En este caso, el ejemplo expuesto es un software Libre y de código Abierto. QGIS es multiplataforma y soporta datos vector, ráster y bases de datos, dispone de una comunidad que da soporte a este proyecto.

Esta aplicación dispone de complementos que aportan más funcionalidades y dispone de una consola Phyton integrada.

El entorno principal consta de cinco tipos de componentes

[![IMAGE ALT TEXT HERE](https://docs.qgis.org/3.16/es/_images/startup.png)](https://www.qgis.org/es/site/about/index.html)

1. Barra de menú
2. Barras de herramientas
3. Paneles
4. Vista de mapa
5. Barra de estado

Todas las funcionalidades de aplicación se estructuran y dotan de las funcionalidades de Menú, Paneles y Barras de herramientas, Vista del Mapa, Vista del Mapa 3D y Barra de Estado, esto representa un conjunto de soluciones que anteriormente se diversificaban en diferentes aplicaciones y que unificadas toman mayor relevancia.

### **Caso de uso**
QGIS para la planificación de redes FTTH/GPON debido a la implementación de la Agenda Digital Europea.

En la implantación de un proyecto para el desarrollo de mapas conceptuales de red FTTH, 
Estos retos necesitaron de la incorporación de varios componentes funcionales aparte de la plataforma SIG estándar:
- GRASS - una colección de algoritmos vectoriales y de red,
- Complementos QGIS - OpenLayer, QuickOSM, Scipy Point Clustering, WorkContextTracer,
- QGIS modeler – herramienta para el modelado gráfico de flujo,
- SpatiaLite - una base de datos local para almacenar datos de entrada y salida. 

La usabilidad de la aplicación, combina información sobre la infraestructura civil existente, red de carreteras, puntos de planificación de red, todo esto presentado en capas separadas.Tras el procesado por los algoritmos, se presentan cables planificados y segmentos de red con sus características. Desde el entorno de aplicación se generan informes de datos con los cálculos desde diferentes perspectivas.
[![IMAGE ALT TEXT HERE](https://www.qgis.org/en/_images/step4_results.png)](https://www.qgis.org/en/site/about/case_studies/poland_ffth.html)

Con esta solución de código abierto, se permite a los operadores preparar documentación y soluciones de planificación de comunicaciones con muchos beneficios como desarrollo automático de planes de red, informes y documentación de las diferentes fases de elaboración de proyecto, evaluación de indicadores económicos,
en resumen una solución global.

## **Re-descubriendo la hibridacion: BIM**
## BUILDING INFORMATION MODELING
Buscando una definición de BIM, en Wikipedia encontramos: 

>El modelado de información de construcción (BIM, Building Information Modelling), también llamado modelado de información para la edificación, es un conjunto de procesos y metodologías para la generación y gestión de datos de un edificio u obra de ingeniería civil durante su ciclo de vida, utilizando para ello un modelo digital compartido entre distintos actores de la cadena de valor. El objetivo es reducir tiempo y recursos en el diseño, la construcción y la gestión del activo. BIM se fundamenta en la colaboración interdisciplinar y el intercambio de información con otras herramientas de software, como GIS, etc. Para asegurar una gestión coherente de la información y facilitar el intercambio de datos, BIM se basa en diversos estándares internacionales

Navegando en la web de Autodesk, empresa de referencia en soluciones software para este sector, hacen referencia a la necesidad de evolución en este sector.

>Según la ONU, la población mundial llegará a los 9700 millones de personas en 2050. El sector AEC mundial debe buscar formas más inteligentes y eficientes de diseñar y construir; no solo a fin de atender la demanda global, sino también para contribuir a crear espacios más inteligentes y con mayor capacidad de adaptación.
Gracias a BIM, los equipos de diseño y construcción pueden trabajar de manera más eficiente y capturar además los datos que generan durante el proceso. Esto supone una ventaja para las operaciones y las actividades de mantenimiento. Esta es la razón por la que cada vez se exige más el uso de BIM en todo el mundo.
>Autodesk
### **Software: Aplicación Revit**

![IMAGE ALT Global](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/images/world-map-r1-white-1920x1000.png)
![IMAGE ALT Planificación](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/fy21/plan-thumb-580x290.jpg)
![IMAGE ALT Diseño](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/fy21/design-thumb-580x290.jpg)
![IMAGE ALT Construcción](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/fy21/build-thumb-580x290.jpg)
![IMAGE ALT Operaciones](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/fy21/operate-thumb-580x290.jpg)



[![IMAGE ALT TEXT HERE](https://damassets.autodesk.net/content/dam/autodesk/www/solutions/bim/fy21/plan-thumb-580x290.jpg)](https://videos.autodesk.com/zencoder/content/dam/autodesk/www/solutions/bim/fy21/what-is-bim-used-for-video-1920x1080.mp4)



## **Conclusiones**

La elección de estos dos casos está pensada por la interrelación y posible hibridación entre ellos en un futuro, de hecho la empresa Autodesk tiene una visión sobre los beneficios de la explotación de datos cruzados sobre los casos que vamos a ver a continuación.




[![IMAGE ALT TEXT HERE](https://www.esri.com/content/dam/esrisites/en-us/arcgis/products/arcgis-geobim/assets/arcgis-geobim-banner-fg.png)](https://www.esri.com/es-es/arcgis/products/arcgis-geobim/overview)

SIG descripción enlace video youtube 



#### ** Referencias y Bibliografía **

* Manovich, Lev. (2013). **El Software toma el mando**. Barcelona: Editorial UOC. 
* http://europa.eu/rapid/press-release_MEMO-10-200_en.htm - información sobre la Agenda Digital Europea
* http://www.ftthcouncil.eu/ - Sitio web de FTTH Council Europe
* https://ksavinetworkinventory.com/en/download-geospatial-network-inventory-free/ - página web de descarga de herramientas.

----


