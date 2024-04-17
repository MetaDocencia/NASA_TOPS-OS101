# Lección 3: Herramientas para datos abiertos

## Índice

- [Introducción a Datos Abiertos](#introduction-to-open-data)
- [Principios FAIR](#fair-principles)
- [Herramientas para ayudar a planificar la creación de datos abiertos](#tools-to-help-with-planning-for-open-data-creation)
- [Herramientas para ayudar con el uso y la creación de datos abiertos](#tools-to-help-with-using-and-making-open-data)
- [Lección 3: Resumen](#lesson-3-summary)
- [Lección 3: Revisión De Conocimientos](#lesson-3-knowledge-check)

## Descripción general

Esta lección trata sobre los conceptos, consideraciones y herramientas para crear datos y resultados. Comienza con una mirada centrada en los principios FAIR y cómo se aplican a los datos. The lesson includes an introduction to plans, tools, data formats, and other considerations that are related to making data and sharing the results related to that data.

## Learning Objectives

After completing this lesson, you should be able to:

- Define the different types of scientific data.
- Define what the acronym FAIR means and explain how it supports the sharing of open data.
- Identify data management practices and tools to locate data in repositories.
- List and explain the purpose of the resources commonly used in making data including the data formats, inspecting data, and assessing 'FAIR'-ness of data.

## Introduction to Open Data

Data is a major part of scientific research, and why wouldn’t it be? It informs tools that we use, stories that we read, and decisions that we make on a daily basis.

For instance, the open access [Copernicus Emergency Management Service](https://emergency.copernicus.eu/) implemented by the European Commission produces 24/7 open access data collected by ESA and NASA satellites to produce maps that inform disaster preparedness and response efforts across the globe. This is only one example among many others demonstrating the value of data, particularly open and public data, in our daily life and for public good.

Data shared openly in scientific research brings tremendous value to the scientific community and beyond, from indigenous communities to urban populations. Before understanding the broad based impact of data, let’s first look at what is data in the context of scientific research. Specifically, we will discuss the definition and characteristics of open data?

### What is Data?

Scientific data is any type of information that is collected, observed, or created, in the context of research. It can be:

- Primary – Raw from measurements or instruments
- Secondary – Processed from secondary analysis and interpretations.
- Published – Final format available for use and reuse.
- Metadata – Data about your data.

It is everything that you need to validate or reproduce your research findings, as well as what is required for the understanding and handling of the data.

The following sections discuss ways to ensure that data is fully utilized and accessible to the most amount of people. These best practices center around community frameworks and tools that help researchers manage and share open data.

## FAIR Principles

<img src="../images/media/image28.png" style="width:100%;height:auto;" />

Just like driving on a road, if everyone follows agreed upon rules, everything goes much smoother. The rules don’t need to be exactly the same for every region, but share common practices based on insights about safety and efficiency.

For example, maybe you drive on the left side of the road or the right side. Either is fine, those sort of details are for different communities to decide on. However, there are overarching guidelines shared by communities across the globe, such as the rule to drive on the road not the sidewalk, use a turn signal when appropriate, adhere to lights at intersections that direct traffic, and follow speed limits. Some communities may implement stricter rules than others, or practice them differently, but these guidelines help everyone move around safely through a common understanding of how to drive on roads. For scientific data, these guidelines are called the Findable, Accessible, Interoperable, Reusable or “FAIR” principles. They do to data what their title suggests. That is, these principles make it possible for others (and yourself) to find, get , understand, and use data correctly.

**Findable**:

To be [Findable:](https://www.go-fair.org/fair-principles/f1-meta-data-assigned-globally-unique-persistent-identifiers/)

- Data and results are assigned a globally unique and persistent identifier.
- Data are described with rich metadata.
- Metadata clearly and explicitly include the identifier of the data it describes.
- Data and results are registered or indexed in a searchable resource.

Current Enabling Tech:

- [DataCite's Metadata Schema](https://schema.datacite.org/)
- PIDs: Persistent IDentifiers (additional details in the following sections)
  - [Digital Object Identifier](https://www.doi.org/) (DOI): A top-level and a mandatory field in the metadata of each record - for data, code, publications.
  - [Open Research and Contributor ID](https://orcid.org/) (ORCiD) - A code that uniquely identifies authors and contributors of research products and scholarly communication.

**Accessible**

To be [Accessible:](https://www.go-fair.org/fair-principles/metadata-retrievable-identifier-standardised-communication-protocol/)

- Data and results are retrievable by their identifiers using a standardized communication protocol.
- The protocol is open, free, and universally implementable.
- The protocol allows for an authentication and authorization procedure, where necessary. Data and results are publicly accessible and licensed under the public domain.
  - Metadata are accessible, even when the data are no longer available Data and metadata will be retained for the lifetime of the repository.
  - Metadata are stored in high-availability database servers.

Current Enabling Tech:

- [File Transfer Protocol (FTP)](https://www.w3.org/Protocols/rfc959/), File Transfer Protocol Secure (FTPS)
- [Hypertext Transfer Protocol (HTTP)](https://www.w3.org/Protocols/), Hypertext Transfer Protocol Secure (HTTPS)

Note that Microsoft Exchange Server and Skype are examples of proprietary protocols.

**Interoperable**

To be [Interoperable:](https://www.go-fair.org/fair-principles/i1-metadata-use-formal-accessible-shared-broadly-applicable-language-knowledge-representation/)

- Data uses a formal, accessible, shared, and broadly applicable language for knowledge representation.
- Data uses a known, standardized data format.
- Data use vocabularies that follow FAIR principles.
- Data include qualified references to other (meta)data.

Current Enabling Tech:

- [Zenodo](https://zenodo.org/) uses [JSON Schema](https://json-schema.org/) as internal representation of metadata and offers export to other popular formats such as [Dublin Core](https://www.dublincore.org/) or [MARCXML](https://www.loc.gov/marc/marcxml.html).
- For certain terms we refer to open, external vocabularies, e.g.: license ([Open Definition](https://opendefinition.org/)), funders ([FundRef](https://www.crossref.org/services/funder-registry/)) and grants ([OpenAIRE](https://api.openaire.eu/)).
- Each referenced external piece of data is qualified by a resolvable URL.

**Reusable**

To be [Reusable:](https://www.go-fair.org/fair-principles/r1-metadata-richly-described-plurality-accurate-relevant-attributes/)

- Data are richly described with a plurality of accurate and relevant attributes.
- Data are released with a clear and accessible data usage license.
- Data are associated with detailed provenance.
- Data meet domain-relevant community standards.

Current Enabling Tech:

- The metadata record contains a minimum of [DataCite's](https://schema.datacite.org/) mandatory terms, with optionally additional DataCite recommended terms and Zenodo's enrichments.
- [Zenodo](https://zenodo.org/) is not a domain-specific repository, yet through compliance with DataCite's Metadata Schema, metadata meets one of the broadest cross-domain standards available.

Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci.Data 3:160018, doi: [1 0 .1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18) (2016)

These are high-level guidelines, and much like open science, implementation is nuanced. Sometimes it takes a group effort and/or a long production process/funding to make data and results FAIR. For other datasets, it could be more straightforward. A well-coordinated data management plan is needed for full compliance with FAIR, and the details of this will be discussed further in Module 3 – Open Data.

## Tools to Help with Planning For Open Data Creation

### Data Management Plan

The previous lesson describes the requirements of a data management plan (DMP). Below are two open science resources to get you started or creating a data management plan:

**DMPTool**

The [DMPTool](https://dmptool.org/) in the US helps researchers by featuring a template that lists a funder's requirements for specific directorate requests for proposals (RFP). The DMPTool also publishes other open DMPs from funded projects that can be referenced to improve your own. The Research Data Management Organizer (RDMO) enables German institutions as well as researchers to plan and carry out their management of research data.

**ARGOS**

[ARGOS](https://argos.openaire.eu/home) is used to plan Research Data Management activities of European and nationally funded projects (e.g. Horizon Europe, CHIST-ERA, the Portuguese Foundation for Science and Technology - FCT). ARGOS produces and publishes FAIR and machine actionable DMPs that contain links to other outputs, e.g. publications-data-software, and minimizes the effort to create DMPs from scratch by introducing automations in the writing process. OpenAIRE provides a guide on how to create DMP.

### Data Repositories

A data repository is a digital space to house, curate, and share research outputs. Data repositories were originally used to support the needs of research communities. Ejemplos de repositorios de datos incluyen:

- [**Protein Data Bank**(Banco de Datos de Proteina)](https://www.rcsb.org/) utiliza un repositorio de datos para catalogar estructuras 3D de proteínas y ácidos nucleólicos.
- [**Genbank**](https://www.ncbi.nlm.nih.gov/genbank/) de los Institutos Nacionales de Salud utiliza una base de datos de secuencias genéticas que contiene secuencias anotadas de ácidos nucleicos disponibles públicamente.
- [**Recurso de datos de imágenes (The Image Data Resource)**](https://idr.openmicroscopy.org/) es un repositorio público de conjuntos de datos que contiene bioimágenes de microscopía procedentes de estudios publicados.
- [**Archivo de Imagen Pública de Microscopía (The Electron Microscopy Public Image Archive)**](https://www.ebi.ac.uk/empiar/) es un recurso público para las imágenes cryo-EM.
- [**OpenNeuro**](https://openneuro.org/) es una plataforma abierta para validar y compartir datos de imágenes cerebrales. Las herramientas de Open Neuro permiten un acceso fácil, la búsqueda y el análisis de conjuntos de datos.

Las herramientas de ciencia abierta, como los repositorios de datos, deben implementar los principios FAIR, especialmente en lo que respecta a la atribución de identificadores persistentes (por ejemplo, DOI), la anotación de metadatos y la capacidad de ser leídos por ordenadores.

**ZENODO**

[Zenodo](https://zenodo.org/) es un ejemplo de un repositorio de datos que permite la carga de datos de investigación y la creación de un DOI. Su popularidad entre la comunidad investigadora se debe a la simpleza de su interfaz, el apoyo a la gestión comunitaria y la función que permite a los investigadores depositar diversos tipos de resultados de investigación, desde conjuntos de datos e informes hasta publicaciones, software y contenidos multimedia.

**DATAVERSE**

[The Dataverse Project](https://dataverse. rg/) es una aplicación en línea de código abierto para compartir, preservar, citar, explorar y analizar datos de investigación, disponible gratuitamente para investigadores de todas las disciplinas del mundo.

**DRYAD**

[The Dryad Digital Repository](https://datadryad.org/) es un recurso en línea organizado que hace que los datos de investigación sean descubribles, reutilizables libremente y citables. A diferencia de las herramientas mencionadas anteriormente, opera en un esquema de membresía para organizaciones como instituciones de investigación y editores.

**DATACITE**

[Datacite](https://datacite.org/) es una organización global sin fines de lucro que proporciona DOI para datos de investigación y otros resultados de investigación, mediante una membresía.

**OSF**

[The Open Science Framework](https://osf.io/) es una plataforma de código abierto para compartir, administrar y colaborar en investigación.

---

Los servicios de datos y los recursos de apoyo a la investigación requieren una infraestructura sólida basada en la colaboración. Un ejemplo de iniciativa sobre infraestructuras de servicios de datos procede de la [EUDAT infraestructura de datos colaborativa (Collaborative Data Infrastructure)](https://www.eudat.eu/), una red sostenida de más de 20 organizaciones europeas de investigación.

Las empresas privadas también alojan y mantienen herramientas en línea para compartir datos y archivos de investigación. Por ejemplo, [Figshare](https://figshare.com/) es un ejemplo de un servicio de acceso libre y abierto operado por empresas privadas. Proporciona DOI para todo tipo de archivos y recientemente desarrolló un modelo de publicación restringido para adaptarse a los requisitos de derechos de propiedad intelectual (IP). Permite compartir las salidas sólo dentro de un grupo Figshare personalizado (podría ser su equipo de investigación) o con usuarios en un rango de IP específico. Los avances adicionales incluyen la integración con repositorios de código, como GitHub, GitLab, y Bitbucket.

Puede encontrar más repositorios de datos de investigación en el Registro de Repositorios de Datos de Investigación (Registry of Research Data Repositories), de acceso público. ](https://www.re3data.org/) [OpenAire](https://explore.openaire.eu/search/find/dataproviders), un motor de búsqueda alojado, que también ofrece una potente función de búsqueda de datos y repositorios. Dispone de un filtro por país, tipo y área temática, además de permitir la descarga de datos.

La cantidad de datos, repositorios y políticas diferentes puede resultar abrumadora. Si tiene dudas sobre qué repositorio es el más adecuado para usted, consulte a los bibliotecarios, gestores de datos y/o administradores de datos de su institución, o consulte en su disciplina específica u otra comunidad de práctica.

### Actividad 3.1: Explore Zenodo y Regístrese!

Explore los repositorios abiertos para familiarizarse con su estructura y la información disponible sobre sus productos. El repositorio más popular actualmente es Zenodo. Vea el siguiente vídeo de 4,5 minutos para obtener una visión general de Zenodo y, a continuación, regístrese para obtener una cuenta. Puede utilizar su ORCID para inscribirse si tiene uno o lo ha creado en la lección anterior.

[Watch Video](https://www.youtube.com/watch?v=BPVSErzNtME\&embeds_referring_euri=https%3A%2F%2Fopenscience101.org%2F\&feature=emb_imp_woyt)

## Herramientas para ayudar con el uso y la creación de datos abiertos

### Formato de los datos

Un formato de archivo útil puede ser leído en memoria por algún software. Piense en el formato como una herramienta para hacer accesibles los datos. Formatos fáciles de usar:

- Una estructura simple y fácil de entender.
- Una especificación clara y abierta del formato que, idealmente, no esté vinculada a un producto de software específico.
- Bibliotecas de software abiertas y APIs que pueden analizar el formato.

Los formatos que se consideran más interoperables según los criterios anteriores son los valores separados por comas (CSV), el lenguaje de marcado extensible (XML) y la notación de objetos JavaScript (JSON). Otros formatos habituales para los investigadores son los basados en matrices binarias, como Network Common Data Form (NetCDF), Hierarchical Data Format (HDF), Geotiff, Flexible Image Transport System (FITS) y otros formatos diseñados para el almacenamiento y el acceso en la nube, como [Zarr](https://zarr.dev/), [Cloud Optimized GeoTIFF](https://www.cogeo.org/) y [Parquet](https://parquet.apache.org/). Muchos de estos formatos cuentan con herramientas que verifican conjuntos de datos para cumplir con estándares y asegurar su legibilidad.

### Inspección de datos

Los formatos de datos modernos permiten almacenar mucho más que simples puntos de datos. Una vez que se adoptan estos estándares (por ejemplo, NetCDF), la búsqueda de los contenidos en cada archivo puede ser asistida por una variedad de herramientas que juntas ayudan a mapear los datos primarios y/o mostrar los metadatos asociados. Existen varias herramientas para inspeccionar datos, siendo demasiadas para mencionarlas todas aquí. Las herramientas destacables con las que comenzar incluyen:

**CSV, XML, JSON** -
Todos estos archivos se pueden abrir con los editores de texto más comunes. Hay algunas herramientas que pueden crear vistas de los archivos más fáciles de usar, como:

- csv: Hojas de Microsoft Excel y Google
- xml: La mayoría de los navegadores de Internet y con cualquier editor de texto como el Bloc de notas o Microsoft Word o Google Docs
- json: [http://json.parser.online.fr/](http://json.parser.online.fr/) y [https://jsonformatter.org/json-Chanty-print](https://jsonformatter.org/json-monety-print)

**NetCDF, HDF, FITS** -
Estos archivos requieren herramientas de software especiales para ver sus contenidos. Muchas de estas herramientas también visualizarán los datos.

- NetCDF y HDF: La mayoría de los archivos se visualizan fácilmente usando la librería de software de código abierto [Xarray](https://docs.xarray.dev/en/stable/) en Python o la biblioteca de software de código abierto [ncdf4](https://cran.r-project.org/web/packages/ncdf4/index.html) en R.
- FITS: Hay muchas opciones, hay una lista en [https://fits.gsfc.nasa.gov/fits_viewer.html](https://fits.gsfc.nasa.gov/fits_viewer.html)

**ZARR, COG, PARQUETO** -
Estos archivos requieren herramientas de software especiales para ver su contenido. Muchas de estas herramientas también visualizan los datos.

- Zarr: Los archivos se visualizan fácilmente utilizando la biblioteca de software de código abierto [Xarray](https://docs.xarray.dev/en/stable/) en Python o la biblioteca [Pizzar](https://github.com/keller-mark/pizzarr) en R.
- COG: Los archivos se visualizan utilizando la biblioteca de software de código abierto [rioXarray](https://corteva.github.io/rioxarray/html/index.html) en Python o la biblioteca [terra](https://cran.r-project.org/web/packages/terra/index.html) en R.
- Parquet: Los archivos se visualizan utilizando la biblioteca de software de código abierto [Pandas](https://pandas.pydata.org/) en Python o la biblioteca [Arrow](https://arrow.apache.org/docs/r/reference/read_parquet.html) en R.

### Evaluación FAIR

¿Qué tan "FAIR" son tus datos? Dos grupos, FAIRsharing.org (https://fairsharing.org/) y la Alianza para los Datos de Investigación (RDA (https://www.rd-alliance.org/)), han desarrollado las Métricas FAIR (https://www.nature.com/articles/sdata2018118) y el Modelo de Madurez de Datos FAIR (https://www.rd-alliance.org/group/fair-data-maturity-model-wg/outcomes/fair-data-maturity-model-specification-and-guidelines-0) para ayudar a evaluar el grado de 'FAIR'-ness de un conjunto de datos.
Existen herramientas de código abierto para ayudar a los investigadores a evaluar sus datos:

**AUSTRALIAN RESEARCH DATA COMMONS (ARDC)**

Cuestionario en línea (manual) - Ideal para:

- Desencadenar debates en las fases iniciales de estudio de la aplicación de FAIR
- Identificar áreas de mejora

Las salidas incluyen:

- Barra de progreso para cada principio FAIR
- Barra de progreso para cada principio FAIR

**FAIR-CHECKER**

Automatizado a través del sitio web o API

Mejor para:

- Escalabilidad a muchos conjuntos de datos
- Identificar áreas de mejora

Las salidas incluyen:

- Un gráfico con puntuaciones y detalles

**F-UJI**

Automatizado a través del sitio web o API

Mejor para:

- Escalabilidad a muchos conjuntos de datos
- Documentación detallada de la herramienta

Las salidas incluyen:

- Un gráfico con puntuaciones y detalles

SERVICIOS DE EVALUACIÓN FAIR

Automatizado a través del sitio web o API

Mejor para:

- Escalabilidad a muchos conjuntos de datos
- Para generar una evaluación personalizada

Las salidas incluyen:

- Un informe detallado y un gráfico

## Lección 3: Resumen

En esta lección has aprendido:

- Los diferentes tipos de datos científicos, incluyendo datos primarios, secundarios, publicados y metadatos.
- Una lista de prácticas de ciencia abierta para aplicar los principios FAIR que hacen que los datos y resultados sean fácilmente accesibles a un amplio abanico de personas.
- Herramientas digitales para ayudar a planificar la creación y el intercambio de datos abiertos.

## Lección 3: Prueba de Conocimiento

Responda a las siguientes preguntas para probar lo que has aprendido hasta ahora.

_Pregunta_

**01/03**

Seleccione los principios FAIR de la siguiente lista. Seleccione todas las opciones que correspondan.

- Reproducibilidad
- Reutilizable
- responsable
- Localizable
- Interactivo
- Interoperable
- Interpolado
- Accesible
- Autorizable

_Pregunta_

**02/03**

¿Cuál de las siguientes opciones puede ayudar a que tus datos sean FAIR? Seleccione todas las opciones que correspondan.

- Obtener una licencia para tus datos
- Asegurarse de desarrollar tus propios metadatos
- Obtener un PID para tus datos

_Pregunta_

**03/03**

¿Cuáles de los siguientes son ejemplos de repositorios? Seleccione todas las opciones que correspondan.

- Zenodo
- Dataverse
- Dryad
- Datacite
- Google
