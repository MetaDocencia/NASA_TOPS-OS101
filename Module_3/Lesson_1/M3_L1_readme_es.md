# Lección 1: Introducción a los Datos Abiertos

## Contenidos

- [Resumen](#resumen)
- [Objetivos de Aprendizaje](#objetivos-de-aprendizaje)
- [Introducción](#introduccion)
- [Definición y Consideraciones de Datos Abiertos](#definicion-y-consideraciones-de-datos-abiertos)
- [Beneficios de los Datos Abiertos](#beneficios-de-los-datos-abiertos)
- [Desafíos de los Datos Abiertos](#desafios-de-los-datos-abiertos)
- [Aplicando Principios FAIR](#aplicando-principios-fair)
- [Planificando la Apertura: Usando el Sistema Usar, Hacer, Compartir para los Datos Abiertos](#planificando-la-apertura-usando-el-sistema-usar-hacer-compartir-para-los-datos-abiertos)
- [Lección 1: Resumen](#leccion-1-resumen)
- [Lección 1: Revisión De Conocimientos](#leccion-1-revision-de-conocimientos)

## Resumen

Esta lección define los datos abiertos, sus beneficios y las prácticas que permiten que los datos sean abiertos. In addition, the lesson takes a closer look at how FAIR applies to open data as well as at the criticall role of metadata. It wraps up with a brief discussion on how to plan for open data in the scientific workflow and tasks guided by the use, make, share framework.

## Objetivos de aprendizaje

After completing this lesson, you should be able to:

- Define what open data is and how the FAIR and CARE principles are used to guide open data practices
- List the benefits of open data
- Explain how the use, make, share framework can be used to modify the scientific plan for open data

## Introduction

Data drives science forward. Data are stored electronically to enable further analysis and research. Digital technologies integrated into every aspect of modern scientific research has led to the production of large amounts of data.

Open data is an essential pillar of open science. In many ways, open data are a natural expansion of open science beyond scholarly publications to include digital research outputs. It has since become an integral part of the open science movement as open data allows anyone to see, use, and verify published results. Open data makes science more accessible, inclusive, and reproducible. In order to support this, data needs to be made available in formats that others can use, include metadata that describes the data, and provided with helpful documentation. When made available, open data enables new discoveries and unforeseen uses.

### Example: How Will Humans Live on the Moon or Travel to Mars When the Space Environment Threatens Human Health in Multiple Ways?

Bone loss, vertigo, anemia, muscle atrophy, increased risk for cancer - these are just some of the human side effects of space travel. To study these human health risks of space travel, scientists around the world use NASA's open-source GeneLab platform. GeneLab aggregates large volumes of space biology data on human and model organism samples exposed to spaceflight conditions. Their digital and physical repositories include cell info as well as DNA, RNA, and proteins. As an open-source platform, GeneLab data are publicly accessible at no cost.

<img src="../images/media/image2.jpeg" style="width:100%;height:auto;" />

**Example:** Using astronaut biological data from GeneLab, [scientists recently found](https://www.nature.com/articles/s41576-020-00322-8) what may be the culprit behind many of the side effects from travel to space: mitochondrial stress.

[Watch Video](https://www.youtube.com/watch?v=c9moR-KQpDQ\&embeds_referring_euri=https%3A%2F%2Fopenscience101.org%2F\&feature=emb_imp_woyt)

Mitochondria are components within our cells that affect respiratory and energy function. This discovery could be crucial to overcoming human health- related problems in space. Understanding the source of this issue could help scientists develop countermeasures and therapies to keep people healthy in space for longer periods of time.

## Definition and Considerations of Open Data

### What is Data?

<img src="../images/media/image3.jpeg" style="width:350px;height:auto;" />

The Turing Way Community. This illustration is created by Scriberia with The Turing Way community, used under a CC-BY 4.0 licence. DOI: 10.5281/zenodo.3332807

---

Data are any type of information that is collected, observed, or created in the context of research. Today, data are increasingly stored electronically in a digital format.

Data includes:

**Primary (raw) data** – Primary data refers to data that are directly collected or created by researchers. Research questions guide the collection of the data. Typically, a researcher will formulate a question, develop a methodology and start collecting the data. Some examples of primary data include:

- Responses to interviews, questionnaires, and surveys.
- Data acquired from recorded measurements, including remote sensing data.
- Data acquired from physical samples and specimens form the base of many studies.
- Data generated from models and simulations.

**Secondary & Processed data** – Secondary data typically refers to data that is used by someone different than who collected or generated the data. Often, this may include data that has been processed from its raw state to be more readily usable by others.

**Published data** – Published data are the data shared to address a particular scientific study and/or for general use. While published data can overlap with primary and secondary data types, we have "published data" as its own category to emphasize that such datasets are ideally well-documented and easy to use.

**Metadata** – Metadata are a special type of data that describe other data or objects (e.g. samples). They are often used to provide a standard set of information about a dataset to enable easy use and interpretation of the data.

The term open data are defined in the open data handbook from the Open Knowledge Foundation:

<img style="width:100%;height:auto;" src="../images/media/opendatahandbookquote.jpg">

"Open data are data that can be freely used, reused and redistributed by anyone – subject only, at most, to the requirement to attribute and share alike."

**Open Data Handbook from the Open Knowledge Foundation**

---

When talking about data in the context of this module, we focus on the data that you are preparing to share, such as data affiliated with a scientific publication, regardless of what type that is. While you could share (and many do) laboratory notebooks, preliminary analyses, intermediate data products, drafts of scientific papers, plans for future research and similar items, these aren't usually required by funding agencies or institutions and thus won’t be in focus for this module.

To quote from a [published paper about data reuse](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9542848/), researchers are mostly looking for data which is "comprehensive, easy to obtain, easy to manipulate, and believable." For these criteria to be fulfilled, the data should:

- Be sufficiently described with appropriate metadata, which greatly affects open data reusability. There is no one size fits all for metadata as its collection is guided by your data.
- Have the appropriate license, copyright, and citation information.
- Have appropriate access information.
- Be findable in an accredited or trustworthy resource.
- Be accompanied with history of changes and versioning.
- Include details of all processing steps.

Not all data may be shared or shared with all this information. There are different reasons why it might not be possible. However, the more information shared about data helps increase the reliability and reusability of the information.

## Beneﬁts of Open Data

Data underpins almost all of science. Openly sharing data with others enables reproducibility, transparency, validation, reuse, and collaborations. Data plays a significant role in our day-to-day lives. Open data, in particular, plays a key role. Open data are only common in our society and you have likely already benefited from this form in some way. The impacts of open data include facilitating:

---

**Greater Good** – Data plays a significant role in our day-to-day lives. Open data, in particular, has played a key role. Si hace una pausa y piensa en ello, puede darse cuenta de que los datos abiertos no solo son comunes en nuestra sociedad, sino que usted mismo podría haberse beneficiado y utilizado los datos abiertos.

Cada país o territorio a menudo proporciona acceso abierto a una variedad de información socioeconómica sobre la población, la comunidad y los negocios en su jurisdicción. Estos datos a menudo se llaman datos de encuestas censales y pueden incluir estadísticas agregadas de género, raza, etnicidad, educación, ingresos y datos de salud de una comunidad. Estos datos se utilizan a menudo para entender la composición de un vecindario local y son críticos para las decisiones informadas sobre la asignación de recursos para asegurar la calidad de vida de la comunidad.

#### Ejemplo: los datos abiertos ayudan a proporcionar información que salva vidas frente al cambio climático

El cambio climático plantea un riesgo importante para nuestra vida diaria y ha sido responsable de la intensificación de las sequías, el aumento de las inundaciones y los devastadores incendios en todo el mundo. Por lo tanto, los datos abiertos son fundamentales para proporcionar información que salve vidas para adaptarse al cambio climático y ayudar a evaluar los riesgos climáticos donde vivimos. Las agencias gubernamentales han estado proporcionando acceso público a información meteorológica y climática a largo plazo durante décadas (p.ej. National Oceanic Atmospheric Administration in the U.S., UK Met Office, European Centre for Medium-Range Weather Forecasts). Una iniciativa más reciente surge de organizaciones que desarrollan productos de datos abiertos con valor agregado para asesorar a la sociedad sobre el riesgo de un clima cambiante. Un ejemplo reciente es el riesgo de inundación e incendio en los Estados Unidos desarrollado por una organización sin fines de lucro [First Street Foundation.](https://firststreet.org/)

**Cambio de Política**

#### Ejemplo: Predicción de los efectos del cambio climático en las comunidades árticas

Los datos abiertos pueden llevar al cambio de políticas que impacten directamente en las vidas de las comunidades, como aquellas destinadas a sufrir primero los lentos cambios en el Ártico. Un estudio (https://www.nature.com/articles/s41467-018-07557-4) publicado en Nature empleó [OpenStreetMap](https://www.openstreetmap.org/about) datos para ayudar a producir mapas de los cambios ambientales proyectados en el Ártico. Estos mapas ayudaron a enfatizar la necesidad de políticas basadas en la adaptación a nivel comunitario y regional para evitar el estancamiento del cambio a la luz de una situación que empeora repentina y dramáticamente impulsada por el cambio climático.

**Respuesta global de emergencia**

#### Ejemplo: COVID-19

La pandemia COVID-19 demostró al mundo, en tiempo real, cómo el movimiento colectivo de las personas que investigan compartiendo sus datos como el intercambio de datos del genoma del coronavirus
(https://www.nature.com/articles/d41586-021-00305-7#:~:text=Other%20researchers%20say%20that%20restrictions,while%20protecting%20data%20providers) puede conducir a una cantidad sin precedentes de descubrimientos en un período de tiempo relativamente corto. Esto afectó directamente los esfuerzos radicales de desarrollo de vacunas y al control oportuno de la infección COVID-19. Estos conocimientos seguirán dando sus frutos y esta investigación estimulará desarrollos futuros.

El intercambio de datos tiene muchos beneficios y puede ayudar al acceso al conocimiento. Sin embargo, es importante considerar de dónde proceden los datos, quién debería tener voz y voto en su interpretación y uso, y cómo los datos pueden ser compartidos de forma responsable.

**Ciencia Ciudadana**

#### Ejemplo: Pruebas de calidad del agua en Beirut

La persona que realiza ciencia ciudadana es ciudadana o cientítica amateur, que colabora con el equipo investigador profesional para ayudar a recopilar o interpretar datos a una escala espacial y temporal más amplia de lo que el equipo podrían lograr por sí solo. Esta subcontratación de la responsabilidad ayuda a los miembros del público a emprender actividades científicas que les beneficien en última instancia y permiten la investigación a gran escala, lo que podría únicamente llevarse a cabo con profesionales de la investigación. La ciencia ciudadana está ganando popularidad y reconocimiento como una contribución valiosa a los avances científicos.

Por ejemplo, personas voluntarias científicas ciudadanas de Beirut fueron reclutados de 50 aldeas para ayudar a probar la calidad del agua[cito: capítulo 5 de [Contextualizar
Abierta: Situación de Open Science](https://idrc-crdi. /es/libro/contextualizing-openness-situating-open-science)]. Estas personas voluntarias fueron formadas para poder llevar a cabo las pruebas y, a su vez, no sólo los datos fueron recogidos para informar de los avances científicos, sino que las personas científicas ciudadanas tuvieron la oportunidad de aprender a gestionar mejor sus recursos hídricos y pudieron mejorar las condiciones, creando una interacción mutuamente beneficiosa.

**Datos abiertos e intercambio equitativo de conocimientos**

La libre distribución del conocimiento aumenta la participación en la ciencia. Los datos abiertos son fundamentales para fomentar la ciencia que es inclusiva y diversa, con beneficios directos y relevantes para las personas y las comunidades afectadas. Esta integración con las comunidades es particularmente importante en la misión de compartir el conocimiento de manera equitativa.

En un ecosistema de investigación donde el conocimiento es una mercancía, cuya principal moneda son los artículos publicados y conjuntos de datos acaparados, la exclusión de la investigación puede limitar el progreso científico y afectar negativamente los resultados de la comunidad. Las personas excluidas de los recursos científicos tradicionales suelen pertenecer a países de ingresos medios bajos y bajos. Abrir nuestros datos de una manera inclusiva y fácilmente reutilizable es un paso hacia la inclusión intencionada de grupos subrepresentados en la ciencia.

#### Example: Recognition and Compensation for the Work of African Ebola Researchers

During the West African Ebola outbreak from 2014-2016, West African researchers actively worked to collect blood sample data to better understand the Ebola virus and to help put a stop to the rapid spread of the virus. However, most of the blood samples were sent overseas to the US and Europe, where researchers used those data samples to author papers about Ebola. According to the paper ["Science under fire: Ebola researchers fight to test drugs and vaccines in a war zone",](https://www.nature.com/articles/d41586-019-02258-4) "This frustrated researchers in the countries ravaged by the virus, who had hoped that studying aspects of the epidemic would strengthen their ability to respond to future infectious- disease outbreaks."

By fostering a global research culture of transparency and validation, where the work of underrepresented groups is celebrated and compensated, we will create a sustainable model that ensures under-represented communities (such as women, under-represented communities, indigenous scholars, non- Anglophone scholars) a voice in how the global and nuanced narrative of science is developed.

---

Open data that are purposefully inclusive and open to scrutiny, benefit scientific innovation by allowing for a more diverse and robust scientific process that draws from multiple perspectives. This openness also allows for the early identification of mistaken insights as well as early intervention for unforeseen harms to impacted communities.

Open data allows non-traditional researchers to contribute to scientific development and bring their unique insights to the table. With these benefits in mind, we should always bear in mind that Open Data requires careful consideration of its potential downsides that results from failure to provide due credit and consultation with potentially vulnerable and/or marginalized communities. The next lesson “Using Open Data” discusses important considerations for the responsible management, collection, and use of open data by all stakeholders.

### Beneﬁts to You

Open data also benefits your research and career. For starters, you are your own future collaborator!

Doing open science not only lets other people understand and reproduce your results, but lets you do so as well! Implementing open science principles like good documentation and version control helps you, potential collaborators, and everyone else to understand your results. In 2 hours, 2 weeks, or 2 years, you will still be able to understand what you did.

Specific benefits of opening data for you as an individual:

- You will never lose access to your previous work, no matter what institute you are affiliated with. Many researchers move around institutions and organizations and by having your data publicly accessible in repositories, you will always have access to them.
- Your data can be cited and you will get credit.
- Publications that include links to data are cited more, according to a 2020 [study.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0230416)

Implementing best practices for open science can strengthen your funding proposals. Funding agencies are realizing that openly sharing research provides more return on their investment. Well-documented research products also demonstrate the quality of your work, which helps with public communication and can also attract quality collaborators. Everybody prefers to work with people who are reliable and do a good job.

### Activity 1.1 Open Data Review

Take a moment to reflect on what data sharing means to you.

<img style="width:100%;height:auto;" src="../images/media/image6.jpeg">

Image source: CC-by [openaire](https://www.openaire.eu/blogs/open-research-data-the-fairest-data-is-the-future-of-science-estonia-national-openaire-event-1)

---

The word cloud showcases the variety of meanings and interpretations that people have about open data. How many terms in the word cloud do you
recognize? Are any of them new to you?

## Challenges of Open Data

While open data has many benefits, there can also be challenges to its creation and use. Throughout this Module, we discuss many of these challenges and possible solutions. In this section, we discuss a few of the most common concerns along with actions to mitigate them.

**Example: Are There Any Harms to Open Data?**

Open data has been demonstrated to further marginalize or exploit small- scale and community driven initiatives, such as in [the case](https://thebulletin.org/2022/05/how-a-dispute-over-sharing-coronavirus-genomes-is-threatening-a-vital-tool-for-tracking-variants/) of African researchers neither receiving due credit nor compensation for their genome sequencing during the COVID-19 pandemic. This is further explored in the next section as we introduce ways of mitigating harms that could happen via unthoughtful and irresponsible sharing of data.

### Restrictions on Sharing Data

Some data should only be shared very carefully or not at all. Reasons not to share can include:

- Data includes a country’s military secrets or violations of national interests.
- Data includes private medical information or an individual’s personally identifiable data.
- Indigenous/cultural/conservation concerns.
- Data includes intellectual property.

It is important to be familiar with the policies around sharing of your data and policies from your funding agency, institution, or laws around data protection. These are further discussed in later modules.

### Common Fears Around Sharing Open Data

#### <img style="width:20px;height:auto;" src="../images/media/image7.png"> NOTE: We will discuss many of the concepts mentioned in the discussion/mitigation column later in this module.

|                                                                                                                       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fear: Scooping: What if someone re-uses my data to publish a result I was working on? | Yes, this can happen. But, in many fields, if it is clear that someone is actively working on a problem, the decision by another to scoop may have a short term gain but long-term loss. In science, reputations are very important and being collaborative generally leads to increased career successes. If you are sharing your data, ensure it has a digital object identifier (DOI). This does not prevent someone from using your data without attribution, but it helps make it easy for others to cite your data. There is a nice article about this [here](https://datascience.codata.org/articles/10.5334/dsj-2017-029). |
| Fear: Misinterpretation or Misuse                                                                     | Provide sufficient contextual information (documentation) to allow others to understand your data fully to reduce this risk.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Fear: My data will be used but not cited                                                              | While it is not common for researchers to cite data, science ethics dictates that you should be cited if your work is used. And remember to cite others' data, so you’re not adding to the problem!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Fear: Data are too sensitive to share                                                                 | Use controlled access to help maintain sensitivity and security.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Fear: My data won't be useful to anyone else                                                          | You never know how materials might be used! [Sailors in the 1800s collected temperature data](https://www.npr.org/templates/story/story.php?storyId=113916471) that is an important part of our ocean climate record today!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

These are all valid concerns when sharing data openly, but as indicated by the global move towards open science, the overall benefits outweigh the concerns.

Ultimately, you are free to deploy the open data principles and resources in your research to maximize its impact and meet the expectations of your sponsors and community while managing costs.

## Applying FAIR Principles

<img src="../images/media/image9.png" style="width:100%;height:auto;" />

Image by Patrick Hochstenbach, CC0 1.0; image illustrates the each FAIR principle

---

### FAIR: Findable, Accessible, Interoperable, Reusable

The vast majority of data today is shared online. FAIR principles help researchers make better use of, and engage with a broader audience with, their scientific data than outdated techniques would allow. FAIR data are more valuable for science because they are easier to use. Data can be FAIR regardless of whether it is openly shared or not. If data are openly shared, being FAIR helps with reuse and expands the scientific impact of the data.

FAIR principles don’t encompass comprehensive implementation instructions for every type of data, but offer general insights to improve shareability and reusability. Sometimes it takes a group effort and/or a long production process to make data and results FAIR. The process starts in the planning stage of a research project. A well-coordinated open science and data management plan is often needed for full compliance with FAIR, depending on the size and type of project the data are used for.

**Up-to-date information about FAIR Principles can be found at the GO FAIR Initiative website**

[CLICK TO LEARN](https://www.go-fair.org/)

Let's review how to make data FAIR for your community.

_Select each tab to find out more information._

<table>
  <thead>
    <tr>
        <th>FINDABLE ☑</th>
        <th>ACCESSIBLE</th>
        <th>INTER-OPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data are findable by those in your community:</p>
            <ul>
            <li>Deposit data in repositories to preserve the data over time.</li>
            <li>Assign your dataset a persistent identifier (PID), such as a digital object identifier (DOI).</li>
            <li>Add rich, self-describing metadata in your data files and register the metadata in a metadata catalog that will enable your data to be properly curated.</li>
                <ul>
                <li>Note that some images or binary files cannot be readily indexed or searched and will need to have companion metadata files or dictionaries to ensure they can be discovered in a search.</li>
                </ul>
            <li>Automate the sharing of your metadata with targeted communities, if applicable.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE ☑</th>
        <th>INTER-OPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data can be accessed by those in your community:</p>
            <ul>
                <li>Archive in a data repository/data center with standardized access protocols.</li>
                <li>Repository access protocols should be well-defined and ideally should support machine-to-machine access.</li>
                <li>Provide information on how users can access your data, ideally in an automated, machine-based fashion.</li>
                <li>If the full content cannot be made openly available for any reason (data sensitivity, infrequent data access, file storage issues), the metadata can still be made openly available so that users can find out who they need to contact to request the data (if possible).</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE</th>
        <th>INTER-OPERABLE ☑</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data are interoperable for those in your community:</p>
            <ul>
                <li>Report the data in community standard format.</li>
                <li>Use existing standardized metadata if available to minimize "lost in translation" issues and support machine-readability.</li>
                <li>El uso de terminologías controladas, vocabularios y ontologías es necesario para respaldar la interoperabilidad, pero puede que aún no estén disponibles en todos los campos de investigación.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>LOCALIZABLE</th>
        <th>ACCESIBLE</th>
        <th>INTEROPERABLE</th>
        <th>REUTILIZABLE ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Garantizar que los datos sean reutilizables por los miembros de tu comunidad:</p>
            <ul>
                <li>Asegúrate de que los metadatos describan con precisión los datos y sus variables, así como cualquier particularidad o limitación.</li>
                <li>Especifica licencias de uso claras para tus datos.</li>
                <li>Proporciona información precisa sobre la procedencia en tus metadatos.</li>
                <li>Agrega suficiente información en los metadatos para que tus datos puedan ser citados correctamente cuando se utilicen.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### El papel central de los metadatos en la aplicación de los principios FAIR

Los metadatos son importantes para que los motores de búsqueda encuentren datos y para que las personas puedan comparar fácilmente lo que se devuelve.

- Los metadatos son esenciales para la aplicación de los Principios FAIR y permiten que los datos sean utilizados por las máquinas de forma automatizada.
- Cuanto más ricos y autodescriptivos sean los metadatos, mejor serán manejados por cualquiera que esté interesado en tus datos.

### Licencias de datos

Una licencia es un documento legal que indica a los usuarios cómo pueden utilizar un conjunto de datos en particular. Si no licencias tu trabajo, otros no podrán o no deberían reutilizarlo, ¡aunque lo quieras! Es imprescindible conocer las condiciones de licencia de un conjunto de datos antes de reutilizarlos. Sin una buena comprensión de lo que permite una licencia, los usuarios de datos pueden enfrentarse a problemas de infracción de derechos de autor u otros problemas de propiedad intelectual.

Para asegurar la reutilización libre de tus datos, puedes recurrir a una licencia abierta. Una licencia abierta contiene un lenguaje que describe la capacidad del usuario para acceder, reutilizar y redistribuir el conjunto de datos. Hay muchos tipos de licencias de datos que tienen distintos grados de apertura, y que se tratarán con más detalle en la lección "Creación de datos abiertos".

## Planificar la apertura: Utilización del marco "Usar, hacer, compartir" para Código Abierto

### Planificar proyectos de ciencia abierta y gestión de datos

La mayoría de las agencias y organismos de financiamiento científico solicitan un plan de difusión de los resultados cuando se propone un proyecto de investigación. Un ejemplo de un plan de ciencia abierto es el Plan de Ciencia Abierta y Gestión de Datos ([OSDMP](https://science.nasa. ov/investigadores/sara/faqs/osdmp)) de la Dirección de Misión de Ciencia de la NASA (SMD) que describe cómo se gestionará y pondrá a disposición del público la información producida a partir de las actividades científicas. El OSDMP incluye secciones sobre gestión de datos, gestión de software e intercambio de publicaciones; estas dos últimas se tratarán en futuros módulos. Si tu estudio tiene otros tipos de resultados, como muestras físicas, hardware o cualquier otra cosa, también debes incluirlos en el plan. Puedes encontrar más información y modelos [aquí](https://github.com/nasa/smd-open-science-guidelines/blob/main/OSS_Guidance/OSDMP.md#osdmp-templates).

Una buena práctica al comenzar tu viaje con datos abiertos es crear un Plan de Gestión de Datos (PGD). En él se describe cómo se gestionarán, preservarán y publicarán los datos durante y después de un proyecto de investigación. Los elementos comunes a todos los Planes de Gestión de Datos (PGD) relevantes para datos abiertos incluyen una descripción teniendo en cuenta lo siguiente:

|           |                                                                                                                     |
| --------- | ------------------------------------------------------------------------------------------------------------------- |
| ¿Qué?     | Formato y (si es relevante) estándares de datos.                                 |
| ¿Cuando?  | El cronograma para archivar y compartir.                                                            |
| ¿Dónde?   | Los repositorios destinados a datos archivados.                                                     |
| ¿Cómo?    | Cómo el plan permite la conservación a largo plazo de los datos.                                    |
| ¿Quiénes? | Roles y responsabilidades de las personas que forman parte del equipo en la implementación del PGD. |

Consulta si tu institución o tu organismo de financiación dispone de pautas, normas o modelos para PGDs. Sino, hay entidades que también disponen de guías y muestras de PGD, como ser:

- [USGS](https://www.usgs.gov/data-management/data-management-plans)
- [NOAA](https://marinedebris.noaa.gov/sites/default/files/DataManagementPlanGuidance%26Sample.pdf)
- [NSF](https://new.nsf.gov/funding/data-management-plan)

Se proporcionarán más detalles sobre cómo crear estos planes en la lección "De la teoría a la práctica".

### Scientiﬁc Workﬂow

There are a variety of scientific workflow models that explain open science. Data plays a central role in the scientific workflow, where users can propose to create new data, collect and package their data during their project, then archive it for long term storage/use/reuse.

For this curriculum, we use the workflow model from [Opensciency](https://opensciency.github.io/sprint-content/open-results/lesson1-research-process-and-results.html#what-research-objects-are-commonly-associated-with-research-stages). It is used to illustrate that regardless of the workflow model you use, the adoption of open data is performed throughout the entire workflow and production of associated deliverables.

If your project is already in progress, it is a good idea to update future data releases to adhere to open data principles as much as possible. For new projects, your proposals should include creating open data from the start of your project.

<img src="../images/media/image10.jpeg" style="width:100%;height:auto;" />

In this curriculum, content is organized by how you might use it, make it, and share it. Part of doing open science is building on others’ materials (using), creating materials yourself (making), and sharing those so others can use those results (sharing). The lessons are all organized around these steps in the scientific workflow.

The "Use, Make, Share" framework categorizes the tasks commonly used in the practice of open science.

<img src="../images/media/image11.png" style="width:100%;height:auto;" />

### Roles in Use, Make, Share

Individuals interacting with data at various points in the scientific workflow can take on different roles. It is possible that these roles can overlap depending on project requirements, the size of your team, and even funding. All should be using open data principles to perform their tasks. Generally, roles include:

_Select each tab to find out more information._

<table>
  <thead>
    <tr>
        <th>DATA USERS ☑</th>
        <th>DATA MAKERS (DATA PROVIDERS)</th>
        <th>DATA SHARERS (DATA PUBLISHERS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data users primarily discover, assess, and utilize data in research projects.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>DATA USERS</th>
        <th>DATA MAKERS (DATA PROVIDERS) ☑</th>
        <th>DATA SHARERS (DATA PUBLISHERS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data makers often process data collected by a project/activity and package it according to open science principles.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>DATA USERS</th>
        <th>DATA MAKERS (DATA PROVIDERS)</th>
        <th>DATA SHARERS (DATA PUBLISHERS) ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data sharers bear the responsibility of disseminating and building awareness of the data to the public.</p>
        </td>
    </tr>
  </tbody>
</table>

Making data open (and FAIR) is a group effort – everybody in the data pipeline has a role to play.

## Lección 1: Resumen

En esta lección, aprendiste:

- Los datos abiertos son un pilar esencial de la ciencia abierta. Compartir abiertamente los datos con otros permite la reproducibilidad, la transparencia, la validación, la reutilización y colaboraciones.
- Hay varios retos para la creación de datos abiertos, pero la mayoría tienen medidas sencillas de solución.
- Los principios FAIR se pueden aplicar a los datos para hacerlos más abiertos.
- Los principios y tareas relacionados con los datos abiertos se utilizan en todo el flujo del trabajo científico.

## Lección 1: Evaluación

Responde las siguientes preguntas para poner a prueba lo que ha aprendido hasta ahora.

_Pregunta_

**01/04**

Lee la siguiente afirmación e indica si es Verdadera o Falsa.

_Los datos abiertos pueden ser libremente utilizados, reutilizados y redistribuidos por cualquiera, sujeto, como mucho, al requisito de atribuir y compartir por igual._

- Verdadero
- Falso

_Pregunta_

**02/04**

Termina esa frase:

_Hacer que los datos estén abiertos te ayuda porque _____._

- tus datos pueden ser citados y se te reconocerá el mérito
- no perderás el acceso a tus datos, incluso si cambias de institución
- tus publicaciones tienen más probabilidades de ser citadas cuando se vinculan a datos abiertos
- todas las anteriores

_Pregunta_

**03/04**

Seleccione los principios FAIR de la siguiente lista. Selecciona todos los que correspondan.

- Reproducibilidad
- Reutilizable
- Responsable
- Localizable
- Interactivo
- Interoperable
- Interpolado
- Accesible
- Autorizable

_Pregunta_

**04/04**

¿Cuál de las siguientes opciones puede ayudar a que tus datos sean FAIR? Selecciona todos los que correspondan.

- Obtener una licencia para tus datos
- Desarrollar tus propios metadatos
- Obtener un PID para tus datos
