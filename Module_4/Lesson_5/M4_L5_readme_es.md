# Lesson 5: From Theory to Practice

## Navigation

- [Overview](#overview)
- [Learning Objectives](#learning-objectives)
- [Open Science and Data Management Plans](#open-science-and-data-management-plans)
- [How Do We Plan for Making our Code Open?](#how-do-we-plan-for-making-our-code-open)
- [Engage and Build Communities](#engage-and-build-communities)
- [Contribute to Open-Source Software](#contribute-to-open-source-software)
- [Additional Resources](#additional-resources)
- [Lesson 5: Summary](#lesson-5-summary)
- [Lesson 5: Knowledge Check](#lesson-5-knowledge-check)
- [Open Code Summary](#open-code-summary)

## Overview

This lesson ties the concepts of open access software development to the operation of a software management plan. The lesson also introduces you to the community aspect of open software. It begins with a discussion on writing software management plans, then continues with information on how to connect with open software communities. This information is contextualized with an introduction to the benefits of a software community and the roles involved in these groups. A list of communities is also presented, and you are asked to explore and engage with some of them. The lesson wraps up with helpful suggestions to contribute to open software and additional resources.

## Learning Objectives

After completing this lesson, you should be able to:

- Recall the definition of a software management plan, potentially as part of an open science and data management plan, and where to find helpful resources.
- List ways to engage with and contribute to open software communities.

## Open Science and Data Management Plans

<img style="width: 100%; height: auto;" src="../images/media/codebg.jpg">

"A NASA Open Science and Data Management Plan (OSDMP) describes how the scientific information that will be produced from NASA-funded scientific activities will be managed and made openly available. The OSDMP should include sections on data management, software management, and publication sharing."

**[https://science.nasa.gov/researchers/sara/faqs/](https://science.nasa.gov/researchers/sara/faqs/)**

---

Example sections to include in an OSDMP:

- Data Management Plan (DMP)
- Software Management Plan (SMP)
- Publication sharing
- Other open science activities
- Roles and responsibilities

#### Recall the steps for an SMP from the previous lessons

- **What:** Description of management, preservation, and release of software.
- **When:** The schedule for software archiving and sharing.
- **Where:** Location where software will be shared and archived over the long-term.
- **How:** Enable reuse of software through assigning a DOI, license, contribution guidelines, etc.
- **Who:** Roles and responsibilities of the team members.

<img style="width: 350px; height: auto;" src="../images/media/recallsteps.jpg">

## How Do We Plan for Making our Code Open?

### Should a Software or Data Management Plan be Written?

If you are planning a project that requires a data management plan, writing that plan is a good first step. There is a threshold above which you should write a software/data management plan. “Software” here means scientifically or technically relevant computer programs as both source code and executable software.

|                     |                                                                                                                                                                                                                                                                                                             |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SMP is required     | You need a SMP to: <ul><li>Propose for funding (e.g., NASA, NSF, and likely everywhere soon)</li><li>Collaborate on a team that intends to release code to the public</li><li>Successfully manage any large mission or project</li></ul> |
| SMP is not required | You probably don't need a SMP if you are working on: <ul><li>A paper by yourself (or with a very small group of collaborators)</li><li>The initial exploration of ideas or experimentation with analysis code</li><li>Education-focused activities</li></ul>             |

Perhaps your project does not fit into these categories. For example, if your aim is for your results to be reproduced by others then writing a SMP is your discretion.

The following material assumes that you have met the threshold and are writing a data/software management plan.

### Pen to Paper: Getting Started Writing a Plan

If you are applying for funding, it is almost guaranteed that there will be specific data management requirements detailed in the funding opportunity. For example, the funder may require a certain license or use of a specific repository. Make sure to cross reference your plan with these requirements.

**Examples of Software Management Plans**

- [software.ac.uk/resources/guides/software-management-plans](https://www.software.ac.uk/resources/guides/software-management-plans)
- [software.ac.uk/software-management-plans](https://www.software.ac.uk/resources/guides/software-management-plans)
- [esciencecenter.nl/national-guidelines-for-software-management-plans/](https://www.esciencecenter.nl/national-guidelines-for-software-management-plans/)
- [https://zenodo.org/record/7589725](https://zenodo.org/record/7589725)

**Policies**

What are the policies for a SMP? (what does the funding agency say to do?)

- Data formats
- Plan for data/code archival/preservation
- Roles and responsibilities

### Funding Agencies

Scientific funding agencies generally solicit peer reviews to support funding decisions. These reviews explicitly or implicitly evaluate related open software. Community participation is necessary to arrive at consensus regarding community standards for funding.

For example: [NASA policy](https://science.nasa.gov/spd-41) explicitly states that "funded software should follow best practices in the relevant open source and research communities."

### Established Open Software Policies of Professional Societies

Professional societies such as AAAS, AGU, AAS, etc., influence funding agency policies and directly influence the policies surrounding software used to generate publications. It is important to engage with the community via consensus papers and professional societies to guide policy decisions regarding open source software in science.

Science/AAAS explicitly states that "In general, all computer code central to the findings being reported should be available to readers to ensure reproducibility."

### Institutions

The individual institutions where we work impose highly variable restrictions on open source software due to security, privacy, intellectual property, commercial, or other concerns which do not necessarily align with the ethos of open science. It is important to engage with the institutional community to facilitate the movement toward policies that facilitate open source software as a foundation of open science.

### Activity 5.1: Writing an SMP

In this activity, review the SMP below and think about these questions:

- What kinds of software does the SMP describe?
- When will it be shared?
- Where will it be shared?
- How will it be shared so it is a citable artifact?
- Who will be responsible for different aspects of the software?
- What are some of the limitations for some of the software?
- How does not having an agreed upon plan when you start code development have impacts years down the line?
- Are results reproducible without the original IDL code?
- Are there things in the example plan that you would add or be more specific about?

#### Example Software Management Plan

**1. Expected Software Types**

We will use established simulation models to conduct initial simulations for this work. These simulation models are written in Fortran and developed over the last decade. While not publicly available, they are available for the project to use (private communication). The simulation models will lead to the generation of output files as described in the Data Management Plan (DMP). We will develop analysis software in Python to analyze the model output files, which will enable the development of derived data products, maps, and figures. Development of the Python analysis software will be shared on a GitHub repository.

**2. Development of Analysis Software**

All new development of Python code will be conducted openly on GitHub by members of this project. We will post and follow the established Code of Conduct for software development for our research project, which includes guidelines for contributions by additional members of the scientific community.

**3. Repositories and Timeline for Sharing Software**

This work will support the development of two peer-reviewed journal articles. All source code developed in Python to support each article will be archived on Zenodo no later than the article’s publication date. The software will be made available under a permissive Apache License 2.0. Zenodo will assign a DOI to the archived software when it is archived.

**4. Software Sharing Exemptions**

This work does not support further development of the existing Fortran simulation models, which are maintained independently. We do not have permission to publicly share the Fortran source code for the simulation models.

**5. Roles and Responsibilities**

Initial simulation modeling and the development of Python analysis software will be completed by PhD students and postdocs. The PI of this project holds overall responsibility for the execution of this plan.

## Engage and Build Communities

Las comunidades de software abierto son espacios de aprendizaje social donde las personas se reúnen para aprender una nueva habilidad, intercambiar conocimientos y experiencias, y luego aplicar lo que han aprendido de la comunidad en su trabajo diario.

#### Las comunidades ofrecen:

- Un punto de entrada accesible para aprender y mejorar el uso del software en la investigación.
- Una oportunidad para compartir experiencias individuales, identificar obstáculos comunes y mejorar de manera iterativa el conocimiento y resolver problemas.
- Una forma de fomentar la cultura del software de código abierto en la ciencia y una excelente manera de mantenerse actualizado sobre las últimas herramientas y prácticas.
- Una comunidad de prácticas no jerárquica donde todos los miembros de la comunidad deben ser tratados de manera igualitaria.

### Conectarse con las comunidades

Aquí hay algunas comunidades que pueden ayudarte a comenzar:

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

Subscríbete y/o participa en foros (por ejemplo, discusiones en GitHub, Stack Overflow, o específicos de tu disciplina/software), talleres presenciales, conferencias, encuentros de hackatón, etc., relacionados con tu disciplina o con el software al que contribuyes o utilizas. Conéctate en redes sociales. Y por último, pero no menos importante, ¡habla con tus colegas!

**Explora: The Turing Way**

**Pulsa el botón para obtener más información sobre la construcción de una comunidad.**

[HAZ CLIC PARA APRENDER MÁS](https://the-turing-way.netlify.app/collaboration/new-community.html)

### Actividad 5.2: Navega por Algunas Comunidades de Práctica

<img style="width:350px;height:auto;" src="../images/media/lightbulb.png">

- Encuentra y navega por los sitios web asociados con dos comunidades de práctica enumeradas en la sección anterior "Conectando con Comunidades".
- Identifica al menos dos puntos de entrada para participar, por ejemplo, un evento próximo (virtual o presencial), cómo podrías contribuir, foros, etc.

#### Puntos clave: Navega por algunas de las comunidades de práctica

- Hay muchas oportunidades para involucrarse con comunidades que trabajan en software abierto.
- Involucrarse con comunidades de software abierto puede enriquecer y mejorar tu software.

## Contribuir al Software de Código Abierto

Contribuir al software de código abierto ofrece muchas ventajas y abre las puertas a una serie de oportunidades muy provechosas. Hay pocas industrias que puedan presumir del enorme número de contribuciones globales como lo hace la comunidad de código abierto. Contribuir al software de código abierto es una excelente manera de mejorar tus habilidades de programación y documentar tu trabajo mientras creces en tu comunidad.

Existen varios tipos de contribuciones al software de código abierto. No todas requieren escribir código real:

|                                                                         |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Añadir nuevas características**                                       | El caso más evidente para contribuir al software de código abierto es mejorar su funcionalidad incorporando nuevas características.                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Corregir errores**                                                    | También, puedes responder a un problema ya abierto corrigiéndolo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Reportar un problema y hacer sugerencias que mejoren el código**      | Informar sobre un problema es una contribución valiosa incluso si no sabes cómo solucionarlo. Por ejemplo, es posible que estés usando un navegador diferente en el que el software aún no se ha probado, hayas descubierto un particular mensaje de error poco informativo, seas daltónico u puedas proporcionar una experiencia de usuario valiosa que ayude a mejorar la funcionalidad general del software.                                                                                                                          |
| **Mejorar y contribuir a la documentación**                             | Contribuir a la documentación constituye un gran punto de partida para colaborar con el software de código abierto y con frecuencia se ignora su importancia. Escribir documentación te permite familiarizarte con el uso del software, al mismo tiempo que ayuda a que otros aprendan.                                                                                                                                                                                                                                                  |
| Crear tutoriales, casos y ejemplos de uso o vídeos                      | Otra forma de contribuir es hacer que tu experiencia y uso del software estén disponibles públicamente. Por ejemplo, podrías crear un tutorial basado en tu uso del software, resumir un caso de uso o proporcionar un resumen de tu experiencia en formato gráfico. Esta parte de la contribución es especialmente atractiva porque no requiere mucho trabajo adicional, simplemente publicar para qué has utilizado el software.                                                                                       |
| **Mejorar el diseño, la automatización y la estructura del código**     | Además de crear nuevo código, una buena forma de contribuir al software de código abierto también puede ser mejorar, reestructurar o automatizar el código existente. Esto se llama refactorización y ayuda a hacer que el proyecto de software sea más eficiente, operativo y estable.                                                                                                                                                                                                                                                  |
| **Organizar y asistir a un encuentro de la comunidad:** | Otra manera de contribuir al software de código abierto es a través del desarrollo de comunidades. Muchos productos y herramientas de software tienen una comunidad activa de usuarios que se reúnen regularmente de forma presencial y/o en línea para discutir y/o mejorar el software y su empleo. Participar o incluso organizar una de estas reuniones puede ser una buena manera para mejorar el conocimiento acerca del software, conocer a su comunidad de usuarios y contribuir en proyectos de código abierto. |
| **Revisión de código**                                                  | Las solicitudes para integrar nuevas contribuciones en el código principal generalmente requieren una revisión de la contribución por parte de al menos otro usuario. Similar a una revisión de pares, la revisión de un código implica escribir un breve resumen sobre la calidad del código y hacer sugerencias de mejoras.                                                                                                                                                                                                            |

## Recursos adicionales

### Referencias y Guías

Además de los recursos mencionados en otras partes de esta capacitación, los siguientes recursos comunitarios son excelentes fuentes de información sobre software de código abierto.

- [OpenSciency](https://zenodo.org/record/7662732)
- [Dirección de Misiones Científicas de la NASA: Guía científica de código abierton (NASA SMD's Open-Source Science Guidance)](https://science.nasa.gov/science-red/s3fs-public/atoms/files/SMD%20Open-Source%20Science%20Guidance%20v1%2020221208.pdf)
- [Guía práctica para la gestión de software (Practical Guide to Software Management)](https://zenodo.org/record/7589725)
- [Principios FAIR para el Software de Investigación (Principios FAIR4RS - FAIR Principles for Research Software)](https://zenodo.org/record/6623556)
- [Opciones de Política de Software de Código Abierto para Ciencias de la Tierra y del Espacio de la NASA (Open Source Software Policy Options for NASA Earth and Space Sciences)](https://doi.org/10.17226/25217)
- [Manual de Turing Way para la ciencia de datos reproducible, ética y colaborativa](https://the-turing-way.netlify.app/index.html)
- [Diez reglas simples para documentar software científico](https://doi.org/10.1371/journal.pcbi.1006561)
- [Journal of Open Source Software](https://joss.theoj.org/)

### Entrenamiento adicional

Además de los recursos mencionados en otras partes de esta capacitación, los siguientes recursos representan capacitación adicional sobre Software de Código Abierto.

- [Software Carpentries](https://software-carpentry.org/lessons/)
- [Cómo contribuir a proyectos de Código Abierto - Una guía para principiantes](https://www.freecodecamp.org/news/how-to-contribute-to-open-source-projects-beginners-guide/)

### Una Revista con Miles de Historias de Éxito de Sofware de Investigación de Código Abierto

[The Journal of Open Source Software](https://joss.theoj.org/) ofrece un espacio para mejorar la calidad y reducir el esfuerzo al publicar software de investigación de código abierto:

- Es una "revista" de código abierto revisada por pares que cubre softwares de investigación de código abierto publicado a través de GitHub.
- The emphasis is on the software.
- Published thousands of open source research software projects, several of which are highly cited. JOSS is one of several journals. Click [here](https://www.software.ac.uk/which-journals-should-i-publish-my-software) for a list of many more journals that publish software.

## Lesson 5: Summary

In this lesson, you learned:

- When a SMP should be written and that your funding organization or institution may have rules around how you develop and share your code.
- That joining software communities can be a great way to exchange knowledge and learn new skills around open code.
- That there are many ways to contribute to open code, and that not all of them require writing code."

## Lesson 5: Knowledge Check

Answer the following questions to test what you have learned so far.

_Question_

**01/02**

Read the statement and decide whether it's true or false:

_Community engagement with open software is non-hierarchical; all members of the community should be treated the same._

- True
- False

_Question_

**02/02**

Select the beneficial way(s) to contribute to open sources software.

- Add new features
- Fix bugs
- Document your work
- Refactoring
- All of the above

## Open Code Summary

Congratulations! Now you should be able to:

- Explain what open source software means, including the software development cycle, the benefits of open software, and some common limitations and how they are addressed.
- Discover open source software and assess it for reuse by evaluating provided documentation, including README files and licensing details; cite the software when appropriate.
- Create an open source software management plan that includes the strategy for selecting open software dependencies and open repositories such as GIT, and how open elements including metadata, README files and version control, will be included to make the software reusable and findable.
- Evaluate whether your open source software can be shared and the best options for sharing to increase visibility.
- List the responsibilities a software developer has once the open source software is shared including managing legal requirements and ensuring the software is maintained.
