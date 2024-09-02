# Lección 5: De la teoría a la práctica

## Contenidos

- [Planes de Gestión de Datos y Ciencia Abierta](#planes-de-gesti%C3%B3n-de-datos-y-ciencia-abierta)
- [¿Cómo planificar abrir nuestro código?](#c%C3%B3mo-planeamos-hacer-nuestro-c%C3%B3digo-abierto)
- [Generar interés y construir comunidades](#generar-inter%C3%A9s-y-construir-comunidades)
- [Contribuir a proyectos de software de Código Abierto](#contribuir-a-proyectos-de-software-de-c%C3%B3digo-abierto)
- [Recursos adicionales](#recursos-adicionales)
- [Lección 5: Resumen](#lecci%C3%B3n-5-resumen)
- [Lección 5: Evaluación](#lecci%C3%B3n-5-evaluaci%C3%B3n)
- [Resumen del Módulo 4: Código Abierto](#resumen-del-m%C3%B3dulo-4-c%C3%B3digo-abierto)

## Descripción general

Esta lección relaciona los conceptos de desarrollo de software de Acceso o de Código Abierto con el funcionamiento de un Plan de Gestión de Software. La lección presenta, además, el aspecto comunitario del software de Código Abierto. Comienza con una discusión sobre cómo redactar Planes de Gestión de Software, luego continúa con información sobre cómo conectarse con comunidades de software de Código Abierto. Esta información se contextualiza con una introducción a los beneficios de una comunidad de software y los roles que se desempeñan en estos grupos. También se presenta una lista de comunidades y te solicitamos que explores e interactúes con algunas de ellas. La lección concluye con sugerencias útiles para contribuir al software de Código Abierto y recursos adicionales.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Recordar la definición de un Plan de Gestión de Software, potencialmente como parte de un Plan de Gestión de Datos y de Ciencia Abierta, y dónde encontrar recursos útiles.
- Enumerar formas de interactuar y contribuir en las comunidades de software de Código Abierto.

## Planes de Gestión de Datos y Ciencia Abierta

<img style="width: 100%; height: auto;" src="../images/media/codebg_es.jpg">

"Un Plan de Gestión de Datos y Ciencia Abierta de la NASA (PGDCA) describe cómo se gestionará y se pondrá a disposición abiertamente la información científica producida a partir de actividades científicas financiadas por la NASA. El PGDCA debe incluir secciones sobre gestión de datos, gestión de software y uso compartido de publicaciones".

Fuente: **[https://science.nasa.gov/researchers/sara/faqs/](https://science.nasa.gov/researchers/sara/faqs/)** (en inglés).

---

Secciones de ejemplo para incluir en un PGDCA:

- Plan de Gestión de Datos (PGD)
- Plan de Gestión de Software (PGS)
- Cómo compartir publicaciones
- Otras actividades de Ciencia Abierta
- Roles y responsabilidades

#### Recuerde los pasos para un PGS de las lecciones anteriores

- **Qué:** Descripción de la gestión, conservación y distribución del software.
- **Cuándo:** El cronograma para archivar y compartir software.
- **Dónde:** Ubicación donde se compartirá y archivará el software a largo plazo.
- **Cómo:** Habilitar la reusabilidad del software mediante la asignación de un DOI, licencia, pautas de contribución, etc.
- **Quién:** Roles, funciones y responsabilidades de las personas que participan del equipo.

<img style="width: 350px; height: auto;" src="../images/media/recallsteps_es.jpg">

## ¿Cómo planificar abrir nuestro código?

### ¿Debería redactarse un Plan de Gestión de Datos o Software?

Si está planificando un proyecto que requiere un Plan de Gestión de Datos, redactar ese plan es un buen primer paso. Existe un umbral por encima del cual se debe redactar un Plan de Gestión de Datos/Software. "Software" aquí significa programas informáticos científica o técnicamente relevantes, tanto como código fuente como software ejecutable.

|                                      |                                                                                                                                                                                                                                                                                                                |
| ------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Se requiere PGS       | Necesita un PGS para: <ul><li>Solicitar financiación (por ejemplo, NASA, NSF y probablemente, pronto en todas partes)</li><li>Colaborar en un equipo que pretende publicar código para el público</li> <li>Gestionar con éxito cualquier misión o proyecto grande</li></ul>    |
| No se requiere PGS | Probablemente no necesites un PGS si estás trabajando en: <ul><li>Un artículo que escribes sólo (o con un grupo muy pequeño de personas colaboradoras)</li><li>La exploración inicial de ideas o la experimentación con código de análisis</li><li>Actividades centradas en la educación</li></ul> |

Quizás tu proyecto no encaje en estas categorías. Por ejemplo, si tu objetivo es que otras personas reproduzcan tus resultados, entonces redactar un PGS queda a tu decisión.

El siguiente material supone que has alcanzado el umbral/nivel y estás escribiendo un Plan de Gestión de Datos/Software.

### Lápiz y papel: cómo empezar a escribir un plan

Si solicita financiación, es casi seguro que habrá requisitos específicos de gestión de datos detallados en la oportunidad de financiación. Por ejemplo, el financiador puede exigir una determinada licencia o el uso de un repositorio específico. Asegúrate de hacer una referencia cruzada de tu plan con estos requisitos.

**Ejemplos de Planes de Gestión de Software**

- [software.ac.uk/resources/guides/software-management-plans](https://www.software.ac.uk/resources/guides/software-management-plans) (en inglés).
- [software.ac.uk/software-management-plans](https://www.software.ac.uk/resources/guides/software-management-plans) (en inglés).
- [esciencecenter.nl/national-guidelines-for-software-management-plans/](https://www.esciencecenter.nl/national-guidelines-for-software-management-plans/) (en inglés).
- [https://zenodo.org/record/7589725](https://zenodo.org/record/7589725) (en inglés).

**Políticas**

¿Cuáles son las políticas para un PGS? (¿Qué dice la agencia de financiamiento que hagamos?)

- Formatos de datos
- Plan para archivo/preservación de datos/códigos
- Roles y responsabilidades

### Agencias de financiamiento

Las agencias de financiamiento científico generalmente solicitan revisiones por pares para respaldar sus decisiones. Estas revisiones evalúan explícita o implícitamente el software de Código Abierto relacionado. La participación de la comunidad es necesaria para llegar a un consenso sobre los estándares comunitarios sobre financiación.

Por ejemplo: Las [políticas de la NASA](https://science.nasa.gov/spd-41) (en inglés) establecen explícitamente que "el software financiado debe seguir las mejores prácticas en las comunidades de investigación y de Código Abierto relevantes".

### Políticas de Software Abierto establecidas por sociedades profesionales

Las sociedades profesionales como AAAS, AGU, AAS, etc. influyen en las políticas de las agencias de financiación e influyen directamente en las políticas relativas al software usado para generar publicaciones. Es importante interactuar con la comunidad a través de documentos de consenso y sociedades profesionales para guiar las decisiones políticas relacionadas con el software de Código Abierto en la ciencia.

Science/AAAS establece explícitamente que "en general, todo el código informático fundamental para los hallazgos que se informan debe estar disponible para los lectores para garantizar la reproducibilidad".

### Instituciones

Las instituciones individuales donde trabajamos imponen restricciones muy variables al software de Código Abierto debido a preocupaciones de seguridad, privacidad, propiedad intelectual, comerciales u otras que no necesariamente se alinean con el espíritu de la Ciencia Abierta. Es importante colaborar con la comunidad institucional para facilitar el movimiento hacia políticas que faciliten el software de Código Abierto como base de la Ciencia Abierta.

### Actividad 5.1: Escribir un PGS

En esta actividad revisa el PGS y piensa en estas preguntas:

- ¿Qué tipos de software describe el PGS?
- ¿Cuándo se compartirá?
- ¿Dónde se compartirá?
- ¿Cómo se compartirá para que sea un artículo citable?
- ¿Quién será responsable de los diferentes aspectos del software?
- ¿Cuáles son las limitaciones de algunos programas?
- ¿Cómo puede afectar en el futuro el hecho de no tener un plan acordado al inicio del desarrollo del código?
- ¿Los resultados son reproducibles sin el código IDL (lenguaje usado para el análisis de datos) original?
- ¿Hay cosas que agregarías en el plan del ejemplo o sobre las que serías más específico?

#### Ejemplo de Plan de Gestión de Software (PGS)

**1. Tipos de software esperados**

usaremos modelos de simulación establecidos para realizar simulaciones iniciales para este trabajo. Estos modelos de simulación están escritos en Fortran y fueron desarrollados durante la última década. Si bien no están disponibles para el público, sí lo están para que los use el proyecto (comunicación privada). Los modelos de simulación conducirán a la generación de archivos de salida como se describe en el Plan de Gestión de Datos (PGD). Desarrollaremos software de análisis en Python para analizar los archivos de salida del modelo, lo que permitirá el desarrollo de productos de datos derivados, mapas y figuras. El desarrollo del software de análisis en Python se compartirá en un repositorio de GitHub.

**2. Desarrollo de análisis de software**

Todo el desarrollo nuevo del código en Python será desarrollado por las personas participantes en el proyecto de manera abierta en GitHub. Publicaremos y seguiremos el código de conducta establecido para el desarrollo de software de nuestro proyecto de investigación, que incluye pautas para las contribuciones de miembros adicionales de la comunidad científica.

**3. Repositorios y cronogramas para compartir software**

Este trabajo apoyará el desarrollo de dos artículos de revistas revisados ​​por pares. Todo el código fuente desarrollado en Python para respaldar cada artículo se archivará en Zenodo a más tardar en la fecha de publicación del artículo. El software estará disponible bajo una licencia Apache 2.0 permisiva. Zenodo asignará un DOI al software archivado cuando se archive.

**4. Exención para compartir software**

Este trabajo no respalda el desarrollo posterior de los modelos de simulación de Fortran existentes, que se mantienen de forma independiente. No tenemos permiso para compartir públicamente el código fuente de Fortran para los modelos de simulación.

**5. Roles y responsabilidades**

Los estudiantes de doctorado y postdoctorados completarán el modelado de simulación inicial y el desarrollo del software de análisis Python. Quien dirija este proyecto tiene la responsabilidad general de la ejecución de este plan.

## Generar interés y construir comunidades

Las comunidades de Software Abierto son espacios de aprendizaje social donde las personas se reúnen para aprender una nueva habilidad, intercambiar conocimientos y experiencias, y luego aplicar lo que han aprendido de la comunidad en su trabajo diario.

#### Las comunidades ofrecen:

- Un punto de entrada accesible para aprender y mejorar el uso del software en la investigación.
- Una oportunidad para compartir experiencias individuales, identificar obstáculos comunes y mejorar de manera iterativa el conocimiento y resolver problemas.
- Una forma de fomentar la cultura del software de Código Abierto en la ciencia y una excelente manera de mantenerse actualizado sobre las últimas herramientas y prácticas.
- Una comunidad de prácticas no jerárquica donde todos los miembros de la comunidad deben ser tratados de manera igualitaria.

### Conectarse con las comunidades

Aquí hay algunas comunidades que pueden ayudarte a comenzar (algunas de ellas, con capítulos o participantes de todo el mundo):

- [PyData](https://pydata.org/)
- [SPEC](https://scientific-python.org/specs/)
- [rOpenSci](https://ropensci.org/)
- [pyOpenSci](https://www.pyopensci.org/)
- [PyHC](https://heliopython.org/)
- [Research Software Engineering](https://society-rse.org/)
- [NumFOCUS](https://numfocus.org/)
- [R-Ladies](https://rladies.org/)
- [PyLadies](https://pyladies.com/)
- [WoCCode](https://woccode.github.io/)
- [Pangeo](https://pangeo.io/)
- [ObsPy](https://discourse.obspy.org/)

Suscríbete y/o participa en foros (por ejemplo, discusiones en GitHub, Stack Overflow, o específicos de tu disciplina/software), talleres presenciales, conferencias, encuentros de hackatón, etc., relacionados con tu disciplina o con el software al que contribuyes o que usas. Conéctate en redes sociales. Y por último, pero no menos importante, ¡habla con tus colegas!

**Explora: The Turing Way**

**Pulsa el botón para obtener más información sobre la construcción de una comunidad.**

[HAZ CLIC PARA APRENDER MÁS](https://the-turing-way.netlify.app/collaboration/new-community.html) (en inglés)

### Actividad 5.2: Navega por algunas comunidades de práctica

<img style="width:350px;height:auto;" src="../images/media/lightbulb_es.png">

- Encuentra y navega por los sitios web asociados con dos comunidades de práctica enumeradas en la sección anterior "Conectando con Comunidades".
- Identifica al menos dos puntos de entrada para participar, por ejemplo, un evento próximo (virtual o presencial), formas en las que podrías contribuir, foros, etc.

#### Conclusiones clave: Navega por algunas de las comunidades de práctica

- Hay muchas oportunidades para involucrarse con comunidades que trabajan en Software Abierto.
- Involucrarse con comunidades de Software Abierto puede enriquecer y mejorar tu software.

## Contribuir a proyectos de software de Código Abierto

Contribuir al software de Código Abierto ofrece muchas ventajas y abre las puertas a una serie de oportunidades muy provechosas. Hay pocas industrias que puedan presumir del enorme número de contribuciones globales como lo hace la comunidad de Código Abierto. Contribuir al software de Código Abierto es una excelente manera de mejorar tus habilidades de programación y documentar tu trabajo mientras haces crecer tu comunidad.

Existen varios tipos de contribuciones al software de Código Abierto. No todas requieren escribir código:

|                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Añadir nuevas características**                                       | El caso más evidente para contribuir al software de Código Abierto es mejorar su funcionalidad incorporando nuevas características.                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Corregir errores**                                                    | También, puedes responder a una incidencia (error) ya abierta corrigiéndola.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Reportar un problema y hacer sugerencias que mejoren el código**      | Informar sobre un problema es una contribución valiosa incluso si no sabes cómo solucionarlo. Por ejemplo, es posible que estés usando un navegador diferente en el que el software aún no se ha probado, hayas descubierto un particular mensaje de error poco informativo, seas daltónico o puedas proporcionar una experiencia de uso valiosa que ayude a mejorar la funcionalidad general del software.                                                                                                                          |
| **Mejorar y contribuir a la documentación**                             | Contribuir a la documentación constituye un gran punto de partida para colaborar con el software de Código Abierto y con frecuencia se ignora su importancia. Escribir documentación te permite familiarizarte con el uso del software, al mismo tiempo que ayuda a que otras personas aprendan.                                                                                                                                                                                                                                                  |
| **Crear tutoriales, casos y ejemplos de uso o vídeos**                      | Otra forma de contribuir es hacer que tu experiencia y uso del software estén disponibles públicamente. Por ejemplo, podrías crear un tutorial basado en tu uso del software, resumir un caso de uso o proporcionar un resumen de tu experiencia en formato gráfico. Esta parte de la contribución es especialmente atractiva porque no requiere mucho trabajo adicional, simplemente publicar para qué has usado el software.                                                                                       |
| **Mejorar el diseño, la automatización y la estructura del código**     | Además de crear nuevo código, una buena forma de contribuir al software de Código Abierto también puede ser mejorar, reestructurar o automatizar el código existente. Esto se llama refactorización y ayuda a hacer que el proyecto de software sea más eficiente, operativo y estable.                                                                                                                                                                                                                                                  |
| **Organizar y asistir a un encuentro de la comunidad:** | Otra manera de contribuir al software de Código Abierto es a través del desarrollo de comunidades. Muchos productos y herramientas de software tienen una comunidad activa de personas que se reúnen regularmente de forma presencial y/o en línea para discutir y/o mejorar el software y su uso. Participar o incluso organizar una de estas reuniones puede ser una buena manera para mejorar el conocimiento acerca del software, conocer a tu comunidad de personas usuarias y contribuir en proyectos de Código Abierto. |
| **Revisión de código**                                                  | Las solicitudes para integrar nuevas contribuciones en el código principal generalmente requieren una revisión de la contribución por parte de al menos otra persona usuaria. Similar a una revisión de pares, la revisión de un código implica escribir un breve resumen sobre la calidad del código y hacer sugerencias de mejoras.                                                                                                                                                                                                            |

## Recursos adicionales

### Referencias y Guías

Además de los recursos mencionados en otras partes de este curso, los siguientes recursos comunitarios son excelentes fuentes de información sobre software de Código Abierto.

- [OpenSciency](https://zenodo.org/record/7662732) (en inglés).
- [Dirección de Misiones Científicas de la NASA: Guía científica de Código Abierto (NASA SMD's Open-Source Science Guidance)](https://smd-cms.nasa.gov/wp-content/uploads/2023/12/smd-open-source-science-guidance-v2.1-20231211-2.pdf) (en inglés).
- [Guía práctica para la gestión de software (Practical Guide to Software Management:)](https://zenodo.org/record/7589725) (en inglés).
- [Principios FAIR para el Software de Investigación (Principios FAIR - _FAIR Principles for Research Software_)](https://zenodo.org/record/6623556) (en inglés).
- [Opciones de Política de Software de Código Abierto para Ciencias de la Tierra y del Espacio de la NASA (_Open Source Software Policy Options for NASA Earth and Space Sciences_)](https://doi.org/10.17226/25217) (en inglés).
- [Manual de Turing Way para la ciencia de datos reproducible, ética y colaborativa](https://the-turing-way.netlify.app/index.html) (en inglés).
- [Diez reglas simples para documentar software científico](https://doi.org/10.1371/journal.pcbi.1006561) (en inglés).
- [Journal of Open Source Software](https://joss.theoj.org/) (en inglés).

### Entrenamiento adicional

Además de los recursos mencionados en otras partes de esta capacitación, los siguientes recursos representan capacitación adicional sobre software de Código Abierto.

- [Software Carpentries](https://software-carpentry.org/lessons/) (en inglés).
- [Cómo contribuir a proyectos de Código Abierto - Una guía para principiantes](https://www.freecodecamp.org/news/how-to-contribute-to-open-source-projects-beginners-guide/) (en inglés).

### Una revista con miles de historias de éxito de sofware de investigación de Código Abierto

[The Journal of Open Source Software (JOOS)](https://joss.theoj.org/) (en inglés). ofrece un espacio para mejorar la calidad y reducir el esfuerzo al publicar software de investigación de Código Abierto:

- Es una "revista" de Código Abierto revisada por pares que cubre softwares de investigación de Código Abierto publicado a través de GitHub.
- Tiene su énfasis puesto en el software.
- Ha publicado una gran cantidad de proyectos de software de investigación de Código Abierto, varios de ellos muy citados. JOSS es una de varias revistas. Haz clic [aquí](https://www.software.ac.uk/which-journals-should-i-publish-my-software) (en inglés) para ver una lista de muchas más revistas que publican software.

## Lección 5: Resumen

En esta lección has aprendido:

- Cuándo se debería redactar un Plan de Gestión de Software y que el organismo o institución de financiamiento puede tener reglas sobre cómo desarrollar y compartir el código.
- Que unirse a comunidades de software puede ser una forma excelente de intercambiar conocimientos y aprender nuevas habilidades en torno al Código Abierto.
- Que hay muchas maneras de contribuir al Código Abierto, y que no todas requieren escribir código.

## Lección 5: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

_Pregunta_

**01/02**

Lee la siguiente afirmación y decide si es Verdadera o Falsa:

_El compromiso de la comunidad con el Software Abierto no es jerárquico; todas las personas de la comunidad deben ser tratadas de la misma manera._

- Verdadero
- Falso

_Pregunta_

**02/02**

Selecciona la o las maneras beneficiosas de contribuir al software de Código Abierto.

- Añadir nuevas características
- Corregir errores
- Documentar el trabajo
- Refactorizar el codigo
- Todas las anteriores

## Resumen del Módulo 4: Código Abierto

¡Felicitaciones! Ahora que has completado el módulo, deberías poder hacer lo siguiente:

- Explicar lo qué significa el software de Código Abierto, incluyendo el ciclo de desarrollo de software, los beneficios del Software Abierto y algunas limitaciones comunes y cómo se abordan.
- Evaluar el software de Código Abierto para su reusación mediante el análisis de la documentación proporcionada, incluyendo archivos README y detalles de licencia, y poder, además, citar el software apropiadamente.
- Crear un Plan de Gestión de Software de Código Abierto que incluyan, por un lado, la estrategia para seleccionar dependencias de Software Abierto y repositorios abiertos como GIT, y también, cómo se incluirán elementos abiertos como metadatos, archivos README y control de versiones para hacer que el software sea reusable y localizable.
- Evaluar si tu software de Código Abierto puede ser compartido y cuáles son las mejores opciones para compartirlo para aumentar su visibilidad.
- Enumerar las responsabilidades que tiene una persona que desarrolla software una vez que el software de Código Abierto es compartido, incluyendo la gestión de los requisitos legales y la garantía del mantenimiento del software.
