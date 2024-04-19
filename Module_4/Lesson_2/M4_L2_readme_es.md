# Lesson 2: Using Open Code

## Navigation

- [Overview](#overview)
- [Learning Objectives](#learning-objectives)
- [Discovering Open Code and Software](#discovering-open-code-and-software)
- [Assessing Open Code and Software](#assessing-open-code-and-software)
- [Reusing Open Code](#reusing-open-code)
- [Citing and Acknowledging Open Code Use](#citing-and-acknowledging-open-code-use)
- [Lesson 2: Summary](#lesson-2-summary)
- [Lesson 2: Knowledge Check](#lesson-2-knowledge-check)

## Overview

In this lesson, you learn the steps for using existing open code in your work. These steps include discovering, assessing, reusing, citing, and acknowledging.

## Learning Objectives

After completing this lesson, you should be able to:

- Describe the process of using open code and list some key elements of discovering code.
- Describe the four key considerations when assessing open software: functionality, interoperability, security, and licenses.
- List some common problems that arise when reusing Open Code and best practices to resolve them.
- Describe how, where, and under what circumstances one should acknowledge (cite) code.

## Discovering Open Code and Software

Many people discover code through discussions with their colleagues or by reading journal articles and attending talks at conferences. This is a great way to find out about code that might have applications for your scientific problem.

What other ways can someone search for open code? As a first step, look for code that already exists because chances are that someone else has already had a similar problem and published their code online. A common way to search for existing code is with a general search engine. Search engines offer one indicator of a code’s relevancy, how recently it was updated, and how frequently others reference it.

|          |                                                                                                                                                                                                                                                                                                                       |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Example  | I'm a new graduate student starting to work on modeling turbulence in the Southern Ocean to better understand sea surface temperature (or ocean heat uptake) and climate change. Is there some software available to model how eddies in the ocean affect sea-surface temperature? |
| Exercise | General Search on the term "Software for ocean turbulence modeling"                                                                                                                                                                                                                                                   |
| Result   | General Ocean Turbulence Model (GOTM)                                                                                                                                                                                                                                                              |

This successful search is predicated on the developers of GOTM making their code open.

### Open Software Discovery Depends on Developers Following FAIR Principles

Discovering open software depends on developers making their software easy to find. The Findable, Accessible, Interoperable and Reusable (FAIR) Principles for research software suggest:

- Software and its associated metadata must be easy for humans and machines to find.
- Software must be described with rich, searchable, and indexable metadata.
- Software must be findable from all relevant search points

**Reference:** "The FAIR Guiding Principles for scientific data management and stewardship" Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016). See also Module 1.

However, you may have more specific needs. The following sections cover additional ways to help discover relevant software that meets specific research demands.

### How to Search for Open Code

A successful search for open code demands a clearly defined purpose. Developers must first determine the tasks they expect their code to carry out. The requirements associated with these tasks can determine the best suited programming language.

Next, familiarize yourself with the terminology of others who created open software with similar requirements to your own. The keywords affiliated with your programming purpose or requirements can serve as a starting point when searching for relevant code. These keywords can be found in community forums about open source programming and in related scientific journal articles. With adoption of open access principles by many academic journals, prospective programmers can peruse scientific papers from fields related to their research in order to find, and sometimes make use of, existing code that will fulfill their requirements.

### Know Where to Search

The open software ecosystem is vast, organic, multifaceted, and highly distributed.

If you are looking for scientific software, community standards increasingly require code to be published and linked to scientific papers.

<img src="../images/media/image333.jpg" style="width:350px;height:auto;" />

Thus, the scientific literature and its ancillary code archives are increasingly a great place to look for scientific open code.

Most open code is not developed by or for scientists. However, open code enables research every day.

### Where to Look Depends on What You Need

There are several popular search engines for code snippets. First, you can simply search on Google. Other commonly used search engines include GitHub Code Search and Stack Overflow. These search engines allow you to search for specific code snippets by programming language, keyword, or other criteria. GitHub Code Search allows you to search GitHub, a popular code repository for scientific software. Stack Overflow allows you to search forums, where users discuss solutions to coding problems.

#### Examples of code repositories:

<table>
<colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/examplecoderepo1.png"></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo2.png"></td>
        <td><img style="width:98%" src="../images/media/examplecoderepo3.png"></td>
    </tr>
    <tr>
        <td>GitHub</td>
        <td>GitLab</td>
        <td>Bitbucket</td>
    </tr>
</tbody>
</table>

**Example - GitHub Code Search**

In this example, we will practice searching for open access code on GitHub. Let's work through a scenario in which you would like to search for the Lomb and Scargle method for estimating a power spectrum.

**Example background**

GitHub enables users to collaborate on a shared project and track their changes with version control. Users can create a repository and grant others access, or make it open access. GitHub involves a large community of open access users who make their code available for free.

**Example instruction**

Begin by visiting the GitHub website to search for openly available software packages. You will need to create a free account for this action. Navigate to the Search Code page to begin your search and access tutorials on the interface and capabilities of the search portal. Alternatively, you can simply input your search terms in the search bar while on your profile page. Next, input the related keywords into the search bar. Search for "Lomb Scargle" and find several repositories with relevant code in various languages, along with thousands of related snippets of code. Congratulations! You have begun your open access software journey and can now view the work of thousands of others who once were where you are now. Upwards and onwards!

<img src="../images/media/image335.jpg" style="width:100%;height:auto;" />

Screenshot of the repositories returned from our search

<img src="../images/media/image496.jpg" style="width:100%;height:auto;" />

Screenshot of the code snippets returned from our search

---

With open software, knowing where to search and what to search for can be a challenging problem. You can always start with a Google Search. However, it can be valuable to think through some of the questions that guide the discovery process. If the user lacks relevant experience, it can also be helpful to engage experienced colleagues at this stage.

Review the flow chart that illustrates how the search follows the definition of the need.

<img src="../images/media/image128.jpg" style="width:6.23514in;height:3.24979in" />

### Open Software is Aggregated and Searchable in Repositories

A software repository is an online collection of stand-alone application software packages. Repositories typically control access and track the deployments/downloads of packages.

Software packages are often provided as executables without code.

The collection typically includes metadata, documentation, and licensing restrictions on each package. Puede incluir diferentes versiones de paquetes de software y las plataformas o entornos en los que se puede ejecutar el paquete de software.

La mayoría de los códigos de investigación deberían ser software de código abierto, el cual se almacena en repositorios de código.

#### Son ejemplos de repositorios de software:

<table>
<colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
</colgroup>
<tbody>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo1.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo2.png"></td>
    </tr>
    <tr>
        <td>Heritage Software</td>
        <td>Open Source Development Network (OSDN)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo3.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo4.png"></td>
    </tr>
    <tr>
        <td>SourceForge</td>
        <td>Free and Open-Source Software Hub (FOSSHUB)</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo5.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo6.png"></td>
    </tr>
    <tr>
        <td>Googlecode</td>
        <td>Comprehensive Perl Archive Network</td>
    </tr>
    <tr>
        <td><img style="width:98%" src="../images/media/softwarerepo7.png"></td>
        <td><img style="width:98%" src="../images/media/softwarerepo8.jpg"></td>
    </tr>
    <tr>
        <td>PyPl</td>
        <td>CRAN</td>
    </tr>
</tbody>
</table>

**Recursos de la NASA para descubrir Software Abierto**

Estos son algunos enlaces a repositorios específicos de la NASA que pueden ser de interés:

- [Software de código abierto de la NASA](https://code.nasa.gov/)
- [APIs abiertas de la NASA](https://api.nasa.gov/)
- [Science Discovery Engine Astrophysics Data System](https://sciencediscoveryengine.nasa.gov/app/nasa-sba-smd/)
- [Portal de Desarrollador de Earthdata](https://www.earthdata.nasa.gov/engage/open-data-services-and-software/api)
  [Centro de Modelos y Análisis de Exoplaneta](https://www.earthdata.nasa.gov/engage/open-data-services-and-software/api)

## Evaluación de código abierto y software

Así que has descubierto un código abierto emocionante que puede ayudarte a resolver tu problema científico. ¿Puedes confiar en este código que descubriste en la red? ¿Será útil? ¿Cuánto tiempo llevará aprenderlo? ¿Podría el código contener un programa maligno? ¿Podrías tener problemas legales por usarlo?

**Ejemplos:** Has encontrado el “General Ocean Turbulence Model (GOTM)” en Internet, y parece prometedor. O bien, acabas de encontrar muchos fragmentos de código y funciones relacionadas con el espectro de potencia Lomb-Scargle. Ahora te gustaría evaluar estas piezas de código para ayudarte a decidir si debes usarlas. En esta sección se tratan algunas buenas prácticas para evaluar si el código le ayudará.

### Cuatro consideraciones generales para evaluar el software abierto

Los criterios de evaluación del software son similares, para cualquier nivel de apertura:

- **Funcionalidad:** ¿Será de utilidad para tu problema científico?
- **Interoperabilidad:** ¿Cuán difícil será de usar?
- **Seguridad:** ¿Es seguro? ¿El uso del software crearía un riesgo para la seguridad?
- **Licencias/restricciones:** ¿Puedes utilizarlo? ¿Es legal utilizar el software en su proyecto?

### Funcionalidad: Evaluación de la utilidad científica

#### ¿El software satisface sus necesidades científicas?\*\*

- ¿Aborda tu pregunta científica específica?
- ¿Los estudios similares a los tuyos lo usan?
- ¿Qué documentos lo citan y cómo lo utilizan?
- Habla con tus asesores o colegas que puedan tener experiencia con él.

#### Probando la compatibilidad científica

- ¿El software contiene casos de prueba científica? Si es así, reproduzca un caso que sea aplicable a su problema; asegúrese de que los resultados son los esperados.
- Si ha hecho un análisis científico similar o modelado anteriormente, reproduzca sus resultados previos con el nuevo software. ¿Son consistentes los resultados?
- Modifica cada vez más un caso de prueba dado para abordar nuevas preguntas científicas. Alternativamente, desarrolle su propio caso, si es necesario, siguiendo ejemplos relevantes.

### Interoperabilidad: Facilidad de Uso

#### ¿Está escrito el código en un idioma con el que estás familiarizado?

Puede ser más fácil usar lenguajes de codificación con los que estás familiarizado. entonces importa el código al software existente en lugar de intentar usar un nuevo idioma. Por otro lado, el uso de paquetes y ejecutables existentes puede acelerar tu trabajo.

#### Busca buena documentación

Lee el archivo LEEME. ¿Cumple el software con sus requerimientos funcionales? ¿Están bien definidas y razonables las dependencias medioambientales?

#### Compruebe la evidencia de interoperabilidad con otros proyectos y códigos

Es una buena señal si puede encontrar evidencia de que el código ha sido utilizado con éxito por otros usuarios que tienen necesidades científicas o técnicas similares.

### Factores para evaluar la calidad del software de código abierto

Para evaluar rápidamente el uso de la comunidad y la calidad del repositorio de software, utilice las herramientas del repositorio donde lo encontró. GitHub, por ejemplo, permite un rápido escaneo de la actividad de desarrollo como lo demuestra el número de veces que el código ha sido descargado o “bifurcado” en el lenguaje de GitHub. También puedes ver la cantidad de actividad en una comunidad. GitHub también proporciona información sobre la calidad del software.

<img src="../images/media/image291.jpg" style="width:100%;height:auto;" />

### La importancia del Archivo LEEME

- Ejemplo anterior: [Astropy](https://github.com/astropy/astropy/blob/main/README.rst)
- Siempre el punto de partida cuando se evalúa un software.
- Explica qué hace el software, cómo instalarlo y usarlo, o apunta a archivos con esa información.
- Asume conocimientos previos limitados por el lector/potencial usuario.
- Incluye una descripción de la compatibilidad, por ejemplo, dependencias.
- Incluye ejemplos de uso y/o casos de prueba.

### Seguridad: Consideraciones cuando se utiliza código abierto

Has encontrado un código abierto que te ayudará a resolver tu problema científico y parece fácil de usar. Sin embargo, es posible que tenga todavía algunas reservas. Tal vez no esté seguro de si el código plantea un riesgo para la seguridad, por ejemplo.

Los riesgos son relativamente bajos para pequeños fragmentos de código que son fáciles de entender para ti. Sin embargo, es posible que no pueda entender completamente todos los componentes de un Paquete de Software Abierto de gran tamaño.

Se considera que el software abierto tiene más riesgos para la seguridad. Esto generalmente es un problema menor para el código fuente abierto que los ejecutables porque el código puede ser auditado en búsquedas de vulnerabilidades de seguridad por la comunidad. ¿Cómo se puede evaluar la seguridad en este caso?

- Consulta con tus políticas institucionales de software abierto y personal de tecnología de la información
- Utilice fuentes confiables para minimizar los riesgos de seguridad
- Establezca reglas y estándares de seguridad estrictos al usar una dependencia
- Utilice herramientas de seguridad para comprobar si hay vulnerabilidades (por ejemplo, [Open Worldwide Application Security</u> Project®️](https://owasp.org/))
- Evite el software de código abierto sin soporte. Cambie a componentes desarrollados activamente o desarrolle sus propios
- Comprueba tus políticas institucionales más recientes sobre el uso de las herramientas de aprendizaje automático e inteligencia artificial
- Tenga cuidado cuando utilice herramientas externas con datos de acceso seguro o cerrado. Puede ser posible que la herramienta externa comparta públicamente lo que debería ser información restringida

### Licencias

Así que, quiere reutilizar algún código abierto que haya descubierto. Es esencial comprobar las restricciones legales y los requisitos impuestos a los usuarios, que generalmente se proporcionan en la licencia.

Aunque la licencia es un tema con matices sobre el que aprenderás más en la lección 3, es útil saber que generalmente hay dos clases de licencia: permisiva y no permisiva. Permissive licenses, most commonly Apache 2.0, MIT, or BSD, will generally allow you to use the code for your scientific research with little restriction, whereas non-permissive licenses such as copy-left licenses, impose substantial restrictions on how you use the code and require more careful consideration.

## Reutilizando Código Abierto

El software se puede reutilizar de varias maneras. Un paquete de software puede ser ejecutado por sí mismo para proporcionar un análisis completo o modelos dependiendo de los parámetros de entrada. Alternativamente, el paquete podría ser importado como parte de una biblioteca más grande para proporcionar una funcionalidad específica. Además, los fragmentos de código pueden copiarse en el código existente, si se permite, o el código podría reescribirse e incorporarse a un nuevo software.

Si simplemente tiene la intención de reutilizar un fragmento de código, pruebe continuamente que su código seleccionado funciona como espera. Si está reutilizando un código más complejo, hay consideraciones adicionales.

### Seleccionando la versión aprobada para la reutilización

Considere lo siguiente cuando seleccione entre múltiples versiones del software de código abierto.

|                                                      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Utilice la última versión estable cuando sea posible | Al igual que ocurre con las actualizaciones de software del sistema operativo o las aplicaciones del teléfono o el ordenador, es importante utilizar la última versión estable. Los desarrolladores de software suelen publicar versiones aún en desarrollo que incluyen nuevas funciones o correcciones de errores que no se han probado por completo. Por este motivo, en general, no se recomienda la utilización de versiones que se encuentren aún en desarrollo. |
| Determine el origen de la versión que desea utilizar | Determine si la versión que pretende utilizar procede de un proyecto de código abierto personalizado o de su fuente original. Con esta información determine qué fuente es más apropiada para su proyecto.                                                                                                                                                                                                                                                                             |
| Comprobación de problemas y bugs                     | Comprueba si la versión que has seleccionado presenta problemas o errores de programación conocidos. Encuentra información actualizada sobre problemas o errores de programación consultando las notas adjuntas de la versión, en sistemas de seguimiento de incidentes y foros de desarrolladores.                                                                                                                                                                                    |

### Resuelve los problemas en software reutilizado

- Implementa pruebas para verificar que el software funciona como esperas en tu aplicación.
- Si tienes problemas, consulta las notas adjuntas de la versión, al sistema de seguimiento de incidentes y/o a los foros de usuarios y desarrolladores.
- No tengas miedo de pedir ayuda a tus colegas con experiencia.
- Es mejor buscar y obtener ayuda en un foro público que en medio privado (por ejemplo, por correo electrónico). Parte del propósito de la ciencia abierta consiste en trabajar abiertamente. A menudo, a través de una búsqueda, puedes descubrir que otros usuarios tienen preguntas similares. Puede que alguien ya haya ofrecido una solución. Si no es el caso, es probable que otros se beneficien de que tu pregunta se responda en público.

### Activity 2.1: Ways to Get Help Using Open Software

In this activity, you are asked to select from a list of ways you can resolve some common problems that arise when using open software.

#### Exercise 1

Select how you can resolve this problem when using open software: Difficulty finding open software that meets your needs.

Select all that apply.

- Reach out to expert colleagues
- Read related peer reviewed literature
- Conduct a search of various popular repositories
- Read the README file
- Read the license file

#### Exercise 2

Select how you can resolve the problem when using open software: installation difficulties.

Select all that apply.

- Reach out to the developers on a public forum
- Read related peer reviewed literature
- Conduct a search of various popular repositories
- Read the README file
- Read the license file

#### Exercise 3

Select how you can resolve the problem when using open software: software is not working as expected.

Select all that apply.

- Reach out to the developers on a public forum
- Read related peer reviewed literature
- Conduct a search of various popular repositories
- Read the README file
- Read the license file
- Consult the release notes, issue trackers, and public forums

#### Exercise 4

After answering the questions above, work through some specific examples of how you would resolve problems on your own. For example, navigate to the astropy code repository on GitHub or another repository of your choice, and find the README and LICENSE files. Determine how you would contact the developers for help, etc.

## Citing and Acknowledging Open Code Use

Imagine that you’ve used Open Code pulled from the web and it made a big difference for your project research paper. How should you provide due credit for the open access code that contributed to your research?

**Example:** You managed to implement GOTM to learn something new about ocean turbulence in the Southern Ocean, or you managed to compute a Lomb-Scargle periodogram using astropy. Here are some questions to consider:

### Should you cite the Open Code?

Cite any code that you view as having contributed to your research:

- Did the code play a critical part in your research?
- Did the code provide something novel?

In most cases, a code snippet on Stack Overflow does not constitute a citable research contribution. However, an author can still decide to cite it if they chose.

Instances when shared code directly impacts the scientific results and requires a detailed description include:

- Numerical modeling or simulation
- Automated analysis, such as image processing or optical recognition

See the journal where you are publishing if they have any specific instructions on how to cite software (e.g., [AAS Software Citation Suggestions](https://journals.aas.org/news/software-citation-suggestions/)).

In some cases, a software’s licensing terms and conditions require acknowledgement or citation in the references or bibliography of any publications based on research that made use of the software.

### How to cite?

Ideally, use and cite code that is archived in a long-term repository with a persistent DOI. Follow the guidance about the preferred citation format, which is provided in the long- term repository and may appear in a README or a CITATION file.

DOIs provide a persistent identifier/link for research outputs. Thus, it is preferable to cite code in long-term repositories linked to a DOI. URLs (e.g., Stack Overflow) and active repositories (e.g., on GitHub) are mutable but can be used if there is no alternative.

Packages may provide a way to cite individual versions as well. For reproducibility, cite both the overall package and the version that is used in your work. As functionality of a package may evolve with the release of new versions, this helps provide a specific description of your work.

If you are writing software, you can also cite in the comments and documentation of the software that you have used.

## Lesson 2: Summary

In this lesson, you learned that:

- Open code exists in a vast, organic, and distributed ecosystem. Discovering Open Code depends on defining your requirements, knowing where to look, and developers using FAIR principles.
- Scientific papers are now a good place to discover scientific Open Code, since many journals require the code used in the paper to be linked via a DOI.
- Before use, it is important to assess open software for functionality, quality, interoperability, security, and license/reuse restrictions. Your first step should be to look for a README file.
- When reusing open software, use the latest supported version and test the software to ensure it functions as expected. If problems arise, reach out to the developers or user community, ideally via a public forum.
- It is important to cite and acknowledge open software that significantly contributes to your work, as well as share your lessons learned and any contributions with the developers and user community.

## Lesson 2: Knowledge Check

Answer the following questions to test what you have learned so far.

_Question_

**01/03**

Discovering open software successfully depends on which of the following:

Select all that apply.

- Well defined requirements
- Knowing where to search
- FAIR open software exists to meet your needs
- All of the above

_Question_

**02/03**

Read the statement and decide whether it's true or false:

_It is best to reach out to the developers of open access software via private communication if you run into problems._

- True
- False

_Question_

**03/03**

When citing Open Code, it is best practice to cite:

- The primary working repository, e.g. on GitHub. It has the most recent version of the code, including any updates since your paper was written.
- A long-term code repository linked to a DOI, e.g. on Zenodo. This repository contains a persistent version of the code that you used.
