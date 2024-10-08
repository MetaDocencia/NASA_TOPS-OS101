# Lección 3: Herramientas para Datos Abiertos

## Contenidos

-   [Introducción a los Datos Abiertos](#introducci%C3%B3n-a-los-datos-abiertos)
-   [Principios FAIR](#principios-FAIR)
-   [Herramientas para ayudar con la planificación de la creación de Datos Abiertos](#herramientas-para-ayudar-con-la-planificaci%C3%B3n-de-la-creaci%C3%B3n-de-datos-abiertos)
-   [Herramientas para ayudar con el uso y manejo de Datos Abiertos](#herramientas-para-ayudar-con-el-uso-y-manejo-de-datos-abiertos)
-   [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
-   [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)

## Descripción general

Esta lección trata sobre los conceptos, consideraciones y herramientas para crear datos y resultados. Comienza con una mirada centrada en los principios FAIR y cómo se aplican a los datos. La lección incluye una introducción a los planes, las herramientas, los formatos de datos y otras consideraciones asociadas a la creación de datos y a la difusión de los resultados relacionados con esos datos.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

-   Definir los diferentes tipos de datos científicos.
-   Definir qué significa el acrónimo FAIR y explicar cómo apoya a que se compartan Datos Abiertos.
-   Identificar prácticas de gestión de datos y herramientas para ubicar datos en repositorios.
-   Listar y explicar el propósito de los recursos usados comúnmente en la creación de datos, incluyendo los formatos de datos, la inspección de datos y la evaluación del ajuste de los datos a los principios FAIR.

## Introducción a los Datos Abiertos 

Los datos son una parte importante de la investigación científica y ¿por qué no lo serían? Son la base de las herramientas que usamos, las historias que leemos y las decisiones que tomamos a diario.

Por ejemplo, el [Servicio de Gestión de Emergencias de Copernicus](https://emergency.copernicus.eu/) (en inglés, *Copernicus Emergency Management Service*), de Acceso Abierto e implementado por la Comisión Europea, produce Datos Abiertos 24/7, que son recogidos por los satélites de la Agencia Espacial Europea (ESA, por las siglas en inglés de *European Space Agency*) y la NASA para producir mapas que informan sobre los esfuerzos en la preparación y la respuesta a desastres en todo el mundo. Este es sólo un ejemplo entre muchos otros que demuestran el valor de los datos, particularmente los datos públicos y abiertos, en nuestra vida cotidiana y para el bien público.

Los datos compartidos abiertamente en la investigación científica aportan un valor enorme a la comunidad científica y más allá, desde las comunidades indígenas hasta las poblaciones urbanas. Antes de entender el impacto general de los datos, veamos primero qué son los datos en el contexto de la investigación científica. Específicamente, discutiremos la definición y las características de los Datos Abiertos.

### ¿Qué son los datos?

Los datos científicos son cualquier tipo de información recopilada, observada o creada en un contexto de investigación. Pueden ser:

-   Primarios -- Sin procesar, de mediciones o instrumentos
-   Secundarios -- Procesados a partir de análisis e interpretaciones secundarias.
-   Publicados -- Formato final disponible para uso y reutilización.
-   Metadatos -- Datos sobre tus datos.

Es todo aquello que necesitas para validar o reproducir los resultados de tu investigación, así como lo que se requiere para la comprensión y el manejo de los datos.

Las siguientes secciones discuten formas de asegurar que los datos sean totalmente utilizados y accesibles para la mayor cantidad de personas. Estas buenas prácticas se centran en marcos de trabajo comunitarios y herramientas que ayudan a quienes investigan a administrar y compartir Datos Abiertos.

## Principios FAIR  

<img src="../images/media/image28.png" style="width:100%;height:auto;"/>

Al igual que al conducir en una carretera, si todo el mundo sigue las normas acordadas, todo va mucho mejor. Las reglas no necesitan ser exactamente las mismas en todas las regiones, pero sí deben compartir prácticas comunes basadas en información sobre seguridad y eficiencia.

Por ejemplo, puede que conduzcas en el lado izquierdo o en el lado derecho de la carretera. Los dos están bien, esos detalles deben decidirse en las diferentes comunidades. Sin embargo, existen pautas generales compartidas por comunidades de todo el mundo, como la regla de conducir en la carretera y no en la acera, usar una señal de giro cuando sea apropiado, respetar los semáforos que dirigen el tráfico en los cruces de calles y seguir los límites de velocidad. Algunas comunidades pueden aplicar reglas de manera más estricta que otras, o ponerlas en práctica de forma diferente, pero estas pautas ayudan a todo el mundo a moverse de forma segura a través de un acuerdo común sobre cómo conducir por las carreteras. Para los datos científicos, estas pautas son los principios Fácil de encontrar (*Findable*), Accesible (*Accesible*), Interoperable (*Interoperable*) y Reusable (*Reusable*), llamados Principios FAIR por sus siglas en inglés. Hacen por los datos lo que su título sugiere. Es decir, estos principios permiten a las demás personas (y a ti) encontrar, obtener, entender y usar correctamente los datos.

**Fácil de encontrar**:

Para que sean [fáciles de encontrar:](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/)

-   Se asigna a los datos y a los resultados un identificador único y persistente a nivel global.
-   Los datos se describen con metadatos enriquecidos.
-   Los metadatos incluyen de forma clara y explícita el identificador de los datos que describen.
-   Los datos y los resultados se registran o se indexan en un recurso que permite realizar búsquedas.

Tecnología actual que lo permite:

-   [Esquema de metadatos de DataCite (*DataCite's Metadata Schema*)](https://schema.datacite.org/)
-   PIDs: siglas en inglés de *Persistent IDentifiers*, Identificadores Persistentes (detalles adicionales en las siguientes secciones)
    -   [Identificador de objeto digital (*Digital Object Identifier*](https://www.doi.org/), DOI): Un campo de nivel superior y obligatorio en los metadatos de cada registro: para datos, código, publicaciones.
    -   [Identificador abierto de investigación y contribuyente (*Open Research and Contributor ID*](https://orcid.org/), ORCiD): Un código que identifica de forma unívoca a las personas autoras y contribuyentes de productos de investigación y comunicación del conocimiento.

**Accesible**

Para ser [accesibles:](https://www.go-fair.org/fair-principles/metadata-retrievable-identifier-standardised-communication-protocol/)

-   Los datos y los resultados son recuperables mediante sus identificadores utilizando un protocolo de comunicación estandarizado.
-   El protocolo es abierto, libre y universalmente implementable.
-   El protocolo permite un procedimiento de autenticación y autorización, cuando sea necesario.
-   Los datos y los resultados son accesibles al público y están licenciados bajo el dominio público.
    -   Los metadatos son accesibles, incluso cuando los datos ya no están disponibles. Los datos y metadatos se conservarán durante toda la vida del repositorio.
    -   Los metadatos se almacenan en servidores de bases de datos de alta disponibilidad.

Tecnología actual que lo permite:

-   [Protocolo de transferencia de archivos (*File Transfer Protocol*, FTP)](https://www.w3.org/Protocols/rfc959/), Protocolo seguro de transferencia de archivos (*File Transfer Protocol Secure*, FTPS)
-   [Protocolo de transferencia de hipertexto (*Hypertext Transfer Protocol*, HTTP)](https://www.w3.org/Protocols/), Protocolo seguro de transferencia de hipertexto (*Hypertext Transfer Protocol Secure*, HTTPS)

Ten en cuenta que Microsoft Exchange Server y Skype son ejemplos de protocolos propietarios.

**Interoperable**

Para ser [interoperable:](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/)

-   Los datos usan un lenguaje formal, accesible, compartido y ampliamente aplicable para la representación del conocimiento.
-   Los datos usan un formato conocido y estandarizado.
-   Los datos utilizan vocabularios que siguen principios FAIR.
-   Los datos incluyen referencias calificadas a otros (meta)datos.

Tecnología actual que lo permite:

-   [Zenodo](https://zenodo.org/) usa [JSON Schema](https://json-schema.org/) como representación interna de los metadatos y permite exportar a otros formatos populares como [Dublin Core](https://www.dublincore.org/) o [MARCXML](https://www.loc.gov/marc/marcxml.html).
-   Para ciertos términos hacemos referencia a vocabularios externos abiertos, por ejemplo: licencia ([Open Definition](https://opendefinition.org/od/2.1/es/)), financiadoras ([FundRef](https://www.crossref.org/services/funder-registry/)) y subsidios ([OpenAIRE](https://api.openaire.eu/)).
-   Cada referencia a una pieza de datos externos es calificada por una URL que puede ser resuelta.

**Reusable**

Para ser [reusable:](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/)

-   Los datos se describen en detalle, con una pluralidad de atributos precisos y relevantes.
-   Los datos se publican con una licencia de uso de datos clara y accesible.
-   Los datos se asocian a una procedencia detallada.
-   Los datos cumplen los estándares comunitarios relevantes para el dominio.

Tecnología actual que lo permite:

-   El registro de metadatos contiene como mínimo los términos obligatorios de [DataCite](https://schema.datacite.org/), y suma opcionalmente los términos recomendados por DataCite y los enriquecimientos de Zenodo.
-   [Zenodo](https://zenodo.org/) no es un repositorio específico de un dominio pero, a través del cumplimiento del Esquema de metadatos de DataCite (*DataCite's Metadata Schema*), los metadatos se ajustan a uno de los estándares interdominio más amplios disponibles.

Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship [Los principios guía FAIR para la gestión y administración de datos científicos]. Sci.Data 3:160018, doi: [1 0 .1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18) (2016)

Estas pautas son de alto nivel y, al igual que la Ciencia Abierta, tienen matices en su aplicación. A veces se necesita un esfuerzo grupal y/o un largo proceso de producción/financiación para que datos y resultados sean FAIR. Para otros conjuntos de datos podría ser más sencillo. Se necesita un Plan de Gestión de Datos bien coordinado para cumplir plenamente con los principios FAIR y los detalles de esto se discutirán más en profundidad en el Módulo 3 - Datos Abiertos.

## Herramientas para ayudar con la planificación de la creación de Datos Abiertos 
### Plan de Gestión de Datos

La lección anterior describe los requisitos de un Plan de Gestión de Datos (PGD) (en inglés, *Data Management Plan*, DMP). Debajo encontrarás dos recursos científicos abiertos para empezar a crear un Plan de Gestión de Datos:

**DMPTool**

[DMPTool](https://dmptool.org/) asiste a quienes investigan en EE.UU. mediante una plantilla que lista los requisitos de una determinada financiadora para solicitudes de propuestas (en inglés, *requests for proposals*, RFP). La herramienta DMPTool también publica PGD abiertos de otros proyectos financiados que pueden tomarse como referencia para mejorar los propios. El Organizador de Gestión de Datos de Investigación (OGDI) (en inglés, *Research Data Management Organizer*, RDMO) permite a las instituciones alemanas y sus equipos de investigación, planificar y llevar a cabo la gestión de datos de investigación.

**ARGOS**

[ARGOS](https://argos.openaire.eu/home) se usa para planificar las actividades de gestión de datos de investigación de proyectos financiados nacionalmente y por Europa (por ejemplo, *Horizon Europe*, CHIST-ERA, la Fundación Portuguesa de Ciencia y Tecnología - FCT). ARGOS produce y publica PGD compatibles con prácticas FAIR y procesables por máquina, que contienen enlaces a otros productos, por ej. publicaciones-datos-software, y minimiza el esfuerzo de crear PGD desde cero introduciendo automatizaciones en el proceso de escritura. OpenAIRE proporciona una guía sobre cómo crear PGD.

### Repositorios de datos

Un repositorio de datos es un espacio digital para alojar, curar y compartir resultados de investigación. Los repositorios de datos se usaron originalmente para apoyar las necesidades de las comunidades de investigación. Ejemplos de repositorios de datos incluyen:

-   [**Banco de Datos de Proteina (Protein Data Bank)**](https://www.rcsb.org/) utiliza un repositorio de datos para catalogar estructuras 3D de proteínas y ácidos nucleicos.
-   [**Genbank**](https://www.ncbi.nlm.nih.gov/genbank/) de los Institutos Nacionales de la Salud (NIH, por sus siglas en inglés) utiliza una base de datos de secuencias genéticas que contiene secuencias anotadas de ácidos nucleicos disponibles públicamente.
-   [**Recurso de datos de imágenes (The Image Data Resource)**](https://idr.openmicroscopy.org/) es un repositorio público de conjuntos de datos que contiene bioimágenes de microscopía procedentes de estudios publicados.
-   [**Archivo público de imágenes de microscopía electrónica (The Electron Microscopy Public Image Archive)**](https://www.ebi.ac.uk/empiar/) es un recurso público para imágenes cryo-EM sin procesar.
-   [**OpenNeuro**](https://openneuro.org/) es una plataforma abierta para validar y compartir datos de imágenes cerebrales. Las herramientas de Open Neuro permiten el fácil acceso, búsqueda y análisis de conjuntos de datos.

Las herramientas de Ciencia Abierta, como los repositorios de datos, deben implementar los principios FAIR, especialmente en lo que respecta a la atribución de identificadores persistentes (por ejemplo, DOI), la anotación de metadatos y la capacidad de ser leídos por computadoras.

**ZENODO**

[Zenodo](https://zenodo.org/) es un ejemplo de un repositorio de datos que permite la carga de datos de investigación y la creación de un DOI. Su popularidad entre la comunidad investigadora se debe a la simpleza de su interfaz, el apoyo a la gestión comunitaria y la función que permite a los investigadores depositar diversos tipos de resultados de investigación, desde conjuntos de datos e informes hasta publicaciones, software y contenidos multimedia.

**DATAVERSE**

[The Dataverse Project](https://dataverse.org/) es una aplicación en línea de Código Abierto para compartir, preservar, citar, explorar y analizar datos de investigación, disponible gratuitamente para investigadores de todas las disciplinas del mundo.

**DRYAD**

[The Dryad Digital Repository](https://datadryad.org/) es un recurso en línea curado que hace que los datos de investigación sean fáciles de encontrar, reusables libremente y citables. A diferencia de las herramientas mencionadas anteriormente, opera en un esquema de membresía para organizaciones como instituciones de investigación y editores.

**DATACITE**

[Datacite](https://datacite.org/) es una organización global sin fines de lucro que proporciona DOI para datos de investigación y otros resultados de investigación mediante una membresía.

**OSF**

[The Open Science Framework](https://osf.io/) es una plataforma de Código Abierto para compartir, administrar y colaborar en investigación.

------------------------------------------------------------------------

Los servicios de datos y los recursos de apoyo a la investigación requieren una infraestructura sólida basada en la colaboración. Un ejemplo de iniciativa sobre infraestructuras de servicios de datos procede de la [EUDAT infraestructura de datos colaborativa (Collaborative Data Infrastructure)](https://www.eudat.eu/), una red sostenida de más de 20 organizaciones europeas de investigación.

Las empresas privadas también alojan y mantienen herramientas en línea para compartir datos y archivos de investigación. Por ejemplo, [Figshare](https://figshare.com/) es un ejemplo de un servicio de acceso libre y abierto operado por empresas privadas. Proporciona DOI para todo tipo de archivos y recientemente desarrolló un modelo de publicación restringido para adaptarse a los requisitos de derechos de propiedad intelectual. Permite compartir los productos sólo dentro de un grupo Figshare personalizado (podría ser tu equipo de investigación) o con personas usuarias en un rango de IP específico. Los avances adicionales incluyen la integración con repositorios de código, como GitHub, GitLab, y Bitbucket.

Puede encontrar más repositorios de datos de investigación en el [Registro de Repositorios de Datos de Investigación (*Registry of Research Data Repositories*)](https://www.re3data.org/) de acceso público. [OpenAire](https://explore.openaire.eu/search/find/dataproviders), es un motor de búsqueda alojado que también ofrece una potente función de búsqueda de datos y repositorios. Dispone de un filtro por país, tipo y área temática, además de permitir la descarga de datos.

La cantidad de datos, repositorios y políticas diferentes puede resultar abrumadora. Si tienes dudas sobre qué repositorio es el más adecuado para ti, consulta a las personas responsables de la biblioteca, quienes gestionan los datos y/o administran datos de tu institución, o consulta en tu disciplina específica u otra comunidad de práctica.

### Actividad 3.1: ¡Explora Zenodo y regístrate!

Explora los repositorios abiertos para familiarizarte con su estructura y la información disponible sobre sus productos. El repositorio más popular actualmente es Zenodo. Ve el siguiente vídeo de 4,5 minutos para obtener una visión general de Zenodo y, a continuación, regístrate para obtener una cuenta. Puedes utilizar tu ORCID para inscribirte si tienes uno o lo has creado en la lección anterior.

[Mira el video](https://www.youtube.com/watch?v=gEnq_RpVdAM).

## Herramientas para ayudar con el uso y manejo de Datos Abiertos 

### Formato de los datos

Un formato de archivo útil puede ser leído en memoria por algún software. Piensa en el formato como una herramienta para hacer accesibles tus datos. 

Los formatos fáciles de usar tienen:

-   Una estructura simple y fácil de entender.
-   Una especificación clara y abierta del formato que, idealmente, no esté vinculada a un producto de software específico.
-   Bibliotecas o librerías de software abiertas y APIs que pueden analizar el formato.

Los formatos que se consideran más interoperables según los criterios anteriores son los valores separados por comas (CSV), el lenguaje de marcado extensible (XML) y la notación de objetos JavaScript (JSON). Otros formatos habituales para las personas investigadoras son los basados en matrices binarias, como Network Common Data Form (NetCDF), Hierarchical Data Format (HDF), Geotiff, Flexible Image Transport System (FITS) y otros formatos diseñados para el almacenamiento y el acceso en la nube, como [Zarr](https://zarr.dev/), [Cloud Optimized GeoTIFF](https://www.cogeo.org/) y [Parquet](https://parquet.apache.org/). Muchos de estos formatos cuentan con herramientas que verifican que los conjuntos de datos cumplen con los estándares y son legibles.

### Inspección de datos

Los formatos de datos modernos permiten almacenar mucho más que datos puntuales. Una vez que se adoptan estos estándares (por ejemplo, NetCDF), la búsqueda de los contenidos en cada archivo puede ser asistida por una variedad de herramientas que juntas ayudan a mapear los datos primarios y/o mostrar los metadatos asociados. Existen varias herramientas para inspeccionar datos, demasiadas para mencionarlas todas aquí. 

Herramientas recomendadas para comenzar:

**CSV, XML, JSON** - Los archivos con estos formatos se pueden abrir con los editores de texto más comunes. Hay algunas herramientas que pueden crear vistas de los archivos que son más fáciles de usar, como:

-   CSV: Hojas de cálculo de Microsoft Excel y Google.
-   XML: La mayoría de los navegadores de Internet y cualquier editor de texto como el Bloc de notas, Microsoft Word, LibreOffice o Google Docs.
-   JSON: <http://json.parser.online.fr/> y <https://jsonformatter.org/json-pretty-print>.

**NetCDF, HDF, FITS** - Estos archivos requieren herramientas de software especiales para ver sus contenidos. Muchas de estas herramientas también visualizan los datos.

-   NetCDF y HDF: la mayoría de los archivos se visualizan fácilmente usando software de Código Abierto, como la librería [Xarray](https://docs.xarray.dev/en/stable/) en Python o [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) en R.
-   FITS: hay muchas opciones de software que permiten visualizar y trabajar con este formato de archivo. En <https://fits.gsfc.nasa.gov/fits_viewer.html> se ofrece una lista exhaustiva (en inglés).

**ZARR, COG, PARQUET** - Estos archivos requieren herramientas de software especiales para ver su contenido. Muchas de estas herramientas permiten también visualizar los datos.

-   Zarr: los archivos se visualizan fácilmente utilizando software de Código Abierto, como las librerías [Xarray](https://docs.xarray.dev/en/stable/) de Python o [Pizzar](https://github.com/keller-mark/pizzarr) en R.
-   COG: los archivos se visualizan utilizando la librería [rioXarray](https://corteva.github.io/rioxarray/html/index.html) en Python o la librería [terra](https://cran.r-project.org/web/packages/terra/index.html) en R.
-   Parquet: los archivos se visualizan utilizando software de Código Abierto, como las librerías [Pandas](https://pandas.pydata.org/) en Python o [Arrow](https://arrow.apache.org/docs/r/reference/read_parquet.html) en R.

### Evaluación FAIR

¿Qué tan "FAIR" son tus datos? Dos grupos -[FAIRsharing.org](https://fairsharing.org/) y la [Research Data Alliance (RDA)](https://www.rd-alliance.org/) (en español, Alianza para los Datos de Investigación)- han desarrollado las [Métricas FAIR](https://www.nature.com/articles/sdata2018118) y el [Modelo de Madurez de Datos FAIR](https://www.rd-alliance.org/group/fair-data-maturity-model-wg/outcomes/fair-data-maturity-model-specification-and-guidelines-0) para ayudar a evaluar que tan "FAIR" es un conjunto de datos. Existen herramientas de Código Abierto para ayudar a quienes investigamos a evaluar sus datos:

**AUSTRALIAN RESEARCH DATA COMMONS (ARDC)**

Cuestionario en línea (manual) - Ideal para:

-   Desencadenar debates en las fases iniciales de estudio, considerando la implementación de los principios FAIR.
-   Identificar áreas de mejora.

Los resultados incluyen:

-   Barra de progreso para cada principio FAIR.
-   Barra de progreso agregada para todos los principios.

**FAIR-CHECKER**

Herramienta automatizada a través del sitio web o API - Ideal para:

-   Escalabilidad a muchos conjuntos de datos.
-   Identificar áreas de mejora.

Los resultados incluyen:

-   Un gráfico con puntuaciones y detalles.

**F-UJI**

Herramienta automatizada a través del sitio web o API - Ideal para:

-   Escalabilidad a muchos conjuntos de datos.
-   Documentación detallada de la herramienta.

Los resultados incluyen:

-   Un informe y gráfico con puntuaciones y detalles.

**FAIR EVALUATION SERVICES**

Herramienta automatizada a través del sitio web o API - Ideal para:

-   Escalabilidad a muchos conjuntos de datos.
-   Generación de una evaluación personalizada.

Los resultados incluyen:

-   Un informe detallado y un gráfico.

## Lección 3: Resumen  

En esta lección has aprendido:

-   Los diferentes tipos de datos científicos, incluyendo datos primarios, secundarios, publicados y metadatos.
-   Una lista de prácticas de Ciencia Abierta para aplicar los principios FAIR que hacen que los datos y resultados sean fácilmente accesibles a muchas personas.
-   Herramientas digitales que facilitan la planificación, creación e intercambio de Datos Abiertos.

## Lección 3: Evaluación 

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

*Pregunta*

**01/03**

Selecciona los principios FAIR de la siguiente lista. Elige todas las opciones que correspondan.

-   Reproducibilidad
-   Reusable
-   Responsable
-   Fácil de encontrar
-   Interactivo
-   Interoperable
-   Intercalado
-   Accesible
-   Autorizable

*Pregunta*

**02/03**

¿Cuál de las siguientes opciones puede ayudar a que tus datos sean FAIR? Selecciona todas las opciones que correspondan.

-   Obtener una licencia para tus datos
-   Desarrollar tus propios metadatos
-   Obtener un PID para tus datos

*Pregunta*

**03/03**

¿Cuáles de los siguientes son ejemplos de repositorios? Selecciona todas las opciones que correspondan.

-   Zenodo
-   Dataverse
-   Dryad
-   Datacite
-   Google
