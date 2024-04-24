# Lección 4: Compartiendo Código abierto

## Índice

- [Resumen](#resumen)
- [Objetivos de Aprendizaje](#objetivos-de-aprendizaje)
- [Planeando compartir tu código](#planning-to-share-your-code)
- [Preocupaciones legales y de seguridad](./Lesson_4#legal-and-security-concerns)
- [Cuando: El Cronograma para Archivar y Compartir Código.](./Lesson_4#when-the-schedule-for-code-archiving-and-sharing)
- [Dónde: Dónde Compartir Código Abierto](./Lesson_4#where-to-share-open-code)
- [Cómo: Cómo habilitar la reutilización del código](./Lesson_4#how-to-enable-reuse-of-code)
- [Quién: Roles y Responsibilidades de los Miembros del Equipo en la Implementación del SMP](./Lesson_4#who-roles-and-responsibilities-of-the-team-members-in-implementing-the-smp)
- [Lección 4: Resumen](#lesson-4-summary)
- [Lección 4: Revisión De Conocimientos](#lección-4-revisión-de-conocimientos)

## Resumen

En esta lección aprenderás los pasos para compartir el software que desarrollaste. Estos pasos incluyen determinar si el software debe compartirse, cuándo y dónde, qué funciones son necesarias y cómo permitir que otros utilicen el código.

## Objetivos de Aprendizaje del Módulo

Después de completar este módulo, deberías ser capaz de:

- Describir lo que significa compartir código: para archivar o para desarrollar código.
- Evaluar si debe compartir su código y listar consideraciones de seguridad importantes.
- Describir las mejores prácticas para cuándo y dónde compartir código.
- Recordar las prácticas más habituales para ayudar a otros a reutilizar tu código.
- Listar los roles y responsabilidades para compartir y mantener código compartido.

## Planificar para compartir tu código

<img src="../images/media/image540.png" style="width:350px;height:auto;" />

He estado trabajando en un código y ahora un nuevo colaborador quiere utilizarlo. ¡Genial! ¿Cuál es la mejor manera de compartir el código? ¿Por correo electrónico? ¿Cuándo debo compartir el código y qué debo incluir para asegurar que esta persona pueda utilizarlo fácilmente?"

### ¿Qué significa "Compartir" tu código?

Hay dos categorías principales de compartir: compartir el desarrollo y el suministro de un registro a largo plazo.

### Desarrollo de código abierto

Escribir código científico suele ser un proceso dinámico y colaborativo en el que contribuyen varias personas y el código evoluciona con el tiempo. En este tipo de proyectos, es beneficioso desarrollar código abierto en una plataforma de alojamiento de repositorios públicos como Github, Bitbucket, GitLab, etc. desde el principio del proyecto. Esto garantiza que todas las actualizaciones se compartan abiertamente en la web y puedan llegar a colaboradores y usuarios potencialmente interesados casi en tiempo real.

### Compartir Código Abierto

El archivado garantiza que su código científico sea accesible a largo plazo y puede satisfacer los requisitos de archivado de organismos y organizaciones de financiación. La accesibilidad a largo plazo ayuda a otras personas a reproducir sus resultados mucho después de la publicación. Archivar por sí solo no promueve el desarrollo continuo ni la colaboración. El archivado es una conservación estática y a largo plazo de su software, no una evolución del mismo.

### ¿Debe compartir su software?

There are several legal and security concerns to keep in mind when creating or using open software.

- Any software you create is usually considered intellectual property and might be controlled by your organization’s policies.
- Such policies may influence how openly the software can be shared, and therefore, its license.
- Downloading and contributing to open software projects can be regulated by your organization's IT security policies.

In contrast, if the software was created with external (government) funding, some funding agencies may require the software be openly shared.

### Deep dive: Software Management Plans (SMP)

Remember the parts of the Software Management Plan? What do we need to consider when it comes to sharing?

- **What:** Description of management, preservation, and release of software.
- **When:** The schedule for code archiving and sharing.
- **Where:** Location where software will be shared and archived over the long-term.
- **How:** Enable reuse of software through assigning a DOI, license, contribution guidelines, etc.
- **Who:** Roles and responsibilities of the team members.

## Legal and Security Concerns

<table>
  <thead>
    <tr>
        <th>LEGAL CONCERNS ☑</th>
        <th>SECURITY CONCERNS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Anyone writing research code and software should familiarize themselves with their organization's policies on sharing and publishing software. Funding agencies, government or private, may have strict software openness requirements. In other cases, sharing software may not be allowed by the organization.</p>
            <p>Legal concerns can include questions such as:</p>
            <ul>
                <li>Does a developer or institution own the software?</li>
                <li>Does sharing (or not sharing) the software violate the funding agency’s policies?</li>
                <li>Are there any local laws or regulations in your area that govern the sharing of intellectual property?</li>
                <li>What software license is required?</li>
            </ul>
            <p><strong>Once you decide to participate in or begin a new open software project, familiarize yourself with your organization’s policies and practices.</strong></p>
            <p>Find out more about the legal concerns <a href="https://opensource.guide/legal/">here</a>.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>LEGAL CONCERNS</th>
        <th>SECURITY CONCERNS ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Security is a concern when sharing software. Bad actors can attach malicious code to software in an attempt to infiltrate computer systems through security vulnerabilities, potentially exposing sensitive and proprietary information that can lead to great financial loss for users. Security risks must be considered when sharing software.</p>
            <p>Security concerns can include:</p>
            <ul>
                <li>Does your organization’s Information Technology (IT) policy allow you to checkout the code you want to use on your machine?</li>
                <li>Is the repository you want to contribute to reputable?</li>
                <li>Are there any open security-related issues with the code?</li>
            </ul>
            <p><strong>Once you decide to participate in or begin a new open software project, familiarize yourself with your organization's IT policies.</strong></p>
            <p>Find out more about the security concerns <a href="https://opensciency.github.io/sprint-content/open-software/lesson2-pros-cons.html#security-concerns">here</a>.</p>
        </td>
    </tr>
  </tbody>
</table>

### Sharing Software Created with US Agency Funding

Many federal agencies are now allowing (if not requiring) the sharing of code created under their grant programs. For example:

- [NASA](https://www.nasa.gov/open/open-source-development.html) "...we are actively reaching out to projects within NASA to make use of ...resources for publishing open source."
- [US Department of Commerce](https://www.commerce.gov/about/policies/source-code) "...requires agencies to develop plans to release at least 20 percent of new custom-developed source code as Open Source Software (OSS) when commissioning new custom software."
- [USGS](https://www.usgs.gov/survey-manual/im-osqi-2019-01-review-and-approval-scientific-software-release) "...software releases are considered to be public domain assets and are generally made available free of restrictions."

Are you funded by a grant? Read the original grant call to see if publishing your code is allowed/required and check whether it has any language about software management and any conditions to publish your code. When in doubt, contact your organization for additional information.

### Activity 4.1: Find Your Organization’s Software Release Policies

<img style="width:350px;height:auto;" src="../images/media/lightbulb.png">

Assume you want to start a new open-source project:

- Find your organization's policies on software releases.
- What is the process for releasing your software?
- Does anybody in your organization have to approve this release?
- Are there any policies regarding external contributors?
- Does your organization require a specific attribution or credit?

#### Key Takeaways: Find Your Organization’s Software Release Policies

Software release policies differ by organization and each piece of software is different. Therefore, it is important that we do not make assumptions about the software release policies based on previous experience.

## When: The Schedule for Code Archiving and Sharing

Planning to share your code at the beginning of your project makes sharing easier to do when you are ready. Exactly when in your workflow you decide to publicly share your code depends on your work and the requirements of the funding agency, organization, or publisher.

As an example, what does NASA say?

If you are writing scientific software for a project funded by the NASA Science Mission Directorate then:

"Scientific software needed to validate the scientific conclusions of peer-reviewed manuscripts resulting from SMD-funded scientific activities shall become publicly available no later than the publication date of the corresponding peer-reviewed article. This includes software required to derive the findings communicated in figures, maps, and tables, as well as scientifically useful software from models and simulations."

\- [**Open-Source Science Guidance**](https://smd-cms.nasa.gov/wp-content/uploads/2023/07/smd-open-source-science-guidance-v2-20230407.pdf)

Other organizations may have different guidance, so it is always best to check what the funding agency or organization requires.

## Where: Where To Share Open Code

### General Considerations

<img src="../images/media/image197.png" style="width:100%;height:auto;" />

Like data, code can be shared in many ways, for example over email or on a personal website, but these methods are not recommended. So, where should you share your Open Code?

First, consider your institutional or funding agency policies that may dictate where you must share and where you can share. For example, some funding agencies specify long-term repositories where your code must be archived, and they may restrict you from sharing in other forms of repositories. Your scientific discipline may have a specific repository for open code.

#### What are some good options and best practices for archiving your code?

- Archive open code with an open access journal article.
- If the open code is in an active online development repository such as Github, then create a version and archive the code at a long-term repository with a DOI such as Zenodo, which can be integrated with Github (more details on this process later).
- Archive the code in other long-term public repositories, such as Software Heritage.

#### Is your code a substantial software package and of interest to a signiﬁcant number of users from various disciplines? Where else can your open code be shared?

<img src="../images/media/image332.png" style="width:350px;height:auto;" />

- Develop your software on a public repository such as GitHub.
- Publish to a software repository used by common package managers to make the software easy for users to install (ex. Anaconda, CRAN, PyPI).
- Present the software at conferences.
- Publish the software in a Journal dedicated to open software (ex. JOSS).
- Get your software peer reviewed through communities like PyOpenSci.

#### To share my code, I can just add it to github, right?

No necesariamente. Se alienta a compartir en un repositorio, pero la organización de financiamiento de la persona que investiga puede requerir un DOI de un repositorio de archivo, como Zenodo, para la preservación a largo plazo de su código en el momento de la publicación o lanzamiento de versiones.

<img src="../images/media/image425.png" style="width:350px;height:auto;" />

## ¿Cómo habilitar la reutilización del código?

Ahora que has compartido tu código de la forma adecuada, es importante considerar si has facilitado a otros participantes (o a tu yo del futuro) la reutilización de tu código.

### Asignando una Licencia

Como recordarás de la lección anterior, asignar una licencia adecuada es necesario para que otras personas sepan cómo utilizar tu código.

Por ejemplo, aquí te mostramos cómo asignar una licencia a un repositorio de GitHub:

Elige la licencia de uso compartido de software adecuada que cumpla con los requisitos de tu organización. Para crear una plantilla de licencia en GitHub, añade un nuevo archivo y escribe "LICENCIA" (en inglés, _LICENCE_) en el campo de nombre, entonces aparecerá la opción "Elegir una plantilla de licencia".

<img src="../images/media/image78.jpg" style="width:350px;height:auto;" />

Asegúrate de que tu repositorio de GitHub sea público, para que cualquiera pueda realizar búsquedas en él.

### Haciendo el código citable

No todo el código tiene que ser citable. Cuando se publica de forma independiente, sin embargo, existen algunas prácticas recomendadas sobre cómo hacer que tu código sea citable.

Añadir el código a un repositorio de GitHub no es suficiente para archivar código. Para archivar, debemos asignar un identificador persistente.

Producir un identificador persistente para tu código es la mejor manera de hacerlo citable. Esto podría hacerse mediante una publicación revisada por pares que describa el software o archivando el software en un repositorio a largo plazo que produzca un DOI o un identificador similar. Para el código compartido en GitHub, un [DOI se puede producir fácilmente para cada versión del software de Zenodo.](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content#issuing-a-persistent-identifier-for-your-repository-with-zenodo)

### Actividad 4.2: Crear un DOI para un Archivo de Código de Prueba

Puedes crear Identificadores de Objetos Digitales (en inglés, _Digital Object Identifiers, DOIs_) para tu código que lo hacen citable. Para hacer esto, archiva un repositorio de código GitHub en Zenodo y emite un DOI para el registro.

Pasos para esta actividad:

**Parte 1: Crear un repositorio GitHub público de prueba.**

1. Ve a la página de inicio de sesión para [GitHub](https://github.com/) e inicia sesión. Si aún no lo has hecho, crea una cuenta de usuario gratuita.
2. Crea un nuevo repositorio con este [enlace](https://github.com/new).
3. Escribe un nombre breve y recordable para tu repositorio. Por ejemplo, "os-test".
4. Establece como 'Pública' la visibilidad del repositorio seleccionando esta opción debajo de la descripción del repositorio.
5. En la siguiente sección 'Inicializar este repositorio con:' selecciona 'Añadir un archivo README'.
6. Selecciona cualquier licencia.
7. Haz clic en 'Crear repositorio'.
8. Serás redirigido automáticamente a tu nueva página web del repositorio.
9. Ahora obtendremos un DOI de la aplicación Zenodo. Ten en cuenta que vamos a usar [https://sandbox.zenodo.org/](https://sandbox.zenodo.org/) para hacer esto. ¡Esto ofrece todas las mismas posibilidades que [https://zenodo.org](https://zenodo.org/) pero es un sitio de pruebas! Crea una cuenta gratuita si aún no lo has hecho.

**Parte 2: Crear un repositorio archivado y DOI afiliados.**

1. Ve a la [página de Zenodo GitHub](https://sandbox.zenodo.org/account/settings/github/). Haz clic en el botón 'Conectar' para permitir que Zenodo acceda a sus repositorios de GitHub.

<img src="../images/media/zenododoi1.jpg" style="width:100%;height:auto" />

2. Revisa la información sobre los permisos de acceso y haz clic en 'Autorizar Zenodo'.
3. Sincroniza tu GitHub con Zenodo haciendo clic en 'Sincronizar ahora' en la esquina superior derecha.

<img src="../images/media/zenododoi3.jpg" style="width:100%;height:auto" />

4. A la derecha del nombre del repositorio que desea archivar ('os-test'), cambia el botón a Encendido (en inglés, _On_).
5. Haz clic en el nombre del repositorio.
6. Haz clic en el botón verde grande que tiene 'username/os-test'

<img src="../images/media/zenododoi6.jpg" style="width:100%;height:auto" />

7. Añade una etiqueta 'test'. Es posible que tengas que crear una nueva etiqueta para 'test' si se te solicita.
8. Desplázate hacia abajo y haz clic en el botón verde 'publicar publicación' (en inglés, _publish release_)

<img src="../images/media/zenododoi8.jpg" style="width:100%;height:auto" />

9. Navega a la [Zenodo GitHub page](https://sandbox.zenodo.org/account/settings/github/) y ve el DOI para 'os-test'.
10. A continuación, comparte tu DOI.

<img src="../images/media/zenododoi10.jpg" style="width:100%;height:auto" />

Zenodo archiva tu repositorio y emite un nuevo DOI cada vez que creas un nuevo GitHub [versión](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases). Sigue los pasos en "[Administrar versiones en un repositorio](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)" para crear una nueva.

### Haciendo Fácil Citar tu Código

La información sobre cómo citar el software puede ser añadida a su LÉEME (en inglés, _README_) u otra documentación en tu repositorio. Otro paso útil para hacer accesible la información de citas de tu repositorio es añadir un archivo CITACIÓN (en inglés _CITATION_) al repositorio.

### ¿Por qué usar archivos CITACIÓN?

Los archivos CITACIÓN son un medio para hacer que la información de citas sea fácilmente accesible en repositorios de software de código abierto. Un [formato de archivo de citas (en inglés, _Citation File Format, CFF_)](https://citation-file-format.github.io/) es un formato estándar legible por humanos y máquinas que se ha desarrollado para los archivos CITACIÓN.

### Pautas para Colaborar

<img src="../images/media/image419.png" style="width:100%;height:auto;" />

Si espera que la comunidad contribuya a su software, es una buena práctica incluir archivos COLABORAR (en inglés, _CONTRIBUTING_) y CÓDIGO DE CONDUCTA (en inglés, _CODE_OF_CONDUCT_) en su repositorio que describan las expectativas para las interacciones de los participantes.

No entraremos en detalles aquí, pero puedes consultar el [repositorio github del paquete Xarray](https://github.com/pydata/xarray/tree/main) para ver un buen ejemplo.

## ¿Cuáles son los roles y las responsabilidades de quienes participan del equipo en la implementación del SMP?

Cuando se escribe un SMP, es importante incluir un plan para los roles y responsabilidades necesarios para compartir y (si corresponde) mantener tu código. Tu comunidad estará formada por personas con diferentes roles: algunos participarán activamente, otras sólo tendrán un interés pasajero. A veces, varios roles pueden ser hechos fácilmente por una persona (por ejemplo, si sólo estás archivando una pieza de código).

Algunos roles podrían incluir:

**¿Quién añadirá el código a un repositorio público?**

- Subiendo el código
- Asignando una licencia

**¿Quién se encargará de la documentación del código?**

- Escribiendo un LÉEME
- Añadiendo comentarios explicativos al código

**¿Quién ayudará con la reutilización del código?**

Añadiendo archivos CITACIÓN, COLABORAR, y CÓDIGO DE CONDUCTA

**¿Quién mantendrá el software (si corresponde)?**

- ¿Quién responderá a la retroalimentación de la comunidad (por ejemplo, a través de problemas en GitHub)?
- ¿Quién será responsable de decidir qué código añadir/actualizar de otras personas colaboradoras? (por ejemplo, mediante solicitudes de extracción de GitHub)

---

Todos estos roles pueden o no ser necesarios, dependiendo del tamaño de tu proyecto. Es necesario tener un proceso transparente para asignar cualquier rol a los miembros de la comunidad.

### Responsibilidades después de Compartir

Si el software está pensado para que otras personas lo usen, entonces quien desarrolla debería mantener el software.

- Es cortés por parte de quien desarrolla informar a las personas que hagan uso si tienen la intención de mantener el software/código o no.
- Haz esto en la documentación donde se discuta el estado de desarrollo del proyecto.
- Esto ayudará a quienes lo utilicen a saber si seguirán recibiendo apoyo en el futuro, y les permitirá tomar decisiones sobre la posibilidad de basar el trabajo en curso en tu proyecto.
- En caso de que quien desarrolle/investigue no disponga del tiempo o la financiación necesaria para seguir adelante con su proyecto, pero otras personas estén interesadas en mantenerlo, considera la posibilidad de ceder la propiedad del software a quienes investiguen/desarrollen/participen, o entidad interesada en su uso continuado.
- Quienes utilicen software que ya no está siendo mantenido pueden considerar contactar a la persona dueña/desarrolladora y ofrecerse voluntariamente para mantenerlo, o para asumir la propiedad del proyecto.
- Si decides mantener tu software, deberías responder a las solicitudes de características y correcciones en la medida de tus posibilidades.

## Lección 4: Resumen

En esta lección, aprendiste los pasos clave para compartir software abierto:

- ¿Deberías compartir? Al compartir software, se deben seguir las políticas de tu institución y agencia de financiamiento. Éstas pueden limitar la apertura del software. Las políticas de intercambio de software también varían según la organización.
- ¿Cuándo compartir? Sigue las indicaciones de tu organización, agencia de financiamiento o editorial.
- ¿Dónde compartir? Depende de si se trata de archivar o de compartir para que la comunidad opine. Utiliza repositorios específicos de dominio cuando sea apropiado.
- ¿Cómo permitir la reutilización? Habilita la reutilización mediante la asignación de un DOI e incluye una licencia, información de citas y directrices para colaboradores.
- ¿Quién ayuda a compartir? Planifica los roles y responsabilidades cuando se comparta y (si es aplicable) para mantener el software.

## Lección 4: Evaluación

Responde las siguientes preguntas para poner a prueba lo que ha aprendido hasta ahora.

_Pregunta_

**01/06**

Lee la siguiente afirmación e indica si es Verdadera o Falsa:

_No necesito compartir mi código si no tengo intención de seguir desarrollándolo._

- Verdadero
- Falso

Pregunta

**02/06**

Lee la siguiente afirmación e indica si es Verdadera o Falsa:

_Añadir el código a un repositorio de GitHub no es suficiente para archivar mi código._

- Verdadero
- Falso

Pregunta

**03/06**

Lee la siguiente afirmación e indica si es Verdadera o Falsa:

_Las políticas de uso compartido de software de organizaciones y gobiernos siguen una práctica estándar._

- Verdadero
- Falso

_Pregunta_

**04/06**

Lee la siguiente afirmación e indica si es Verdadera o Falsa:

_Publicar tu software en un repositorio de software utilizado por los gestores de paquetes habituales facilita a las personas usuarias la instalación de su software._

- Verdadero
- Falso

_Pregunta_

**05/06**

¿Cuáles de las siguientes, si las hay, son formas en las que puedes ayudar a otras personas a reutilizar tu código? Selecciona todos los que correspondan.

- Asignar una licencia adecuada
- Añadir un archivo llamado "CONTRIBUTING" con pautas de colaboradores
- Añadir un archivo "CITATION" con información de citas

_Pregunta_

**06/06**

¿Cuáles de los siguientes son roles que deberías planificar al escribir un SMP? Selecciona todos los que correspondan.

- Quién ayudará a mantener el software
- Quién creará el repositorio y añadirá los archivos necesarios
- Quién contribuirá al software después de que se comparta
- Quién agregará documentación al software
