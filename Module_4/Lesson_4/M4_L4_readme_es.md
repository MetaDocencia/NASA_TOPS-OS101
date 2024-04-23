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

En esta lección aprenderás los pasos para compartir el software que desarrollaste. These steps include determining if, when, and where software should be shared, which roles are needed, and how to enable others to use the code.

## Learning Objectives

After completing this lesson, you should be able to:

- Describe what it means to share code: for archiving or for code development.
- Evaluate whether you should share your code and list important security considerations.
- Describe best practices for when and where to share code.
- Recall commonly used practices to help others reuse your code.
- List the roles and responsibilities for sharing and maintaining shared code.

## Planning to Share Your Code

<img src="../images/media/image540.png" style="width:350px;height:auto;" />

"I've been working on code, and now a new collaborator wants to use the code. Awesome! What is the best way to share the code? By email? When should I share the code, and what should I include to ensure the colleague can easily use it?"

### What Does it Mean to "Share" Your Code?

There are two major categories of sharing: sharing for development and providing a long-term record.

### Open Source Code Development

Writing scientific code is often a dynamic and collaborative process in which multiple people contribute and the code evolves over time. In such projects, it is beneficial to develop open code within a public repository hosting platform such as Github, Bitbucket, GitLab etc. from the beginning of a project. This ensures that all updates are shared openly on the web and can reach potentially interested collaborators and users in near real time.

### Archiving Open Code

Archiving ensures your scientific code is accessible for the long-term, and may satisfy archiving requirements from funding agencies and organizations. Long-term accessibility helps others to reproduce your results long after publication. Archiving alone does not promote continued development or collaboration. Archiving is a static and long-term preservation of your software, not an evolution of it.

### Should You Share Your Software?

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

No necesariamente. Se alienta a compartir en un repositorio, pero la organización de financiamiento del investigador puede requerir un DOI de un repositorio de archivo, como Zenodo, para la preservación a largo plazo de su código en el momento de la publicación o lanzamiento de versiones.

<img src="../images/media/image425.png" style="width:350px;height:auto;" />

## ¿Cómo habilitar la reutilización del código?

Ahora que has compartido tu código de la forma adecuada, es importante considerar si has facilitado a otros (o a tu yo del futuro) la reutilización de tu código.

### Asignando una Licencia

Como recordarás de la lección anterior, asignar una licencia adecuada es necesario para que otros sepan cómo utilizar tu código.

Por ejemplo, aquí te mostramos cómo asignar una licencia a un repositorio de GitHub:

Elige la licencia de uso compartido de software adecuada que cumpla con los requisitos de tu organización. Para crear una plantilla de licencia en GitHub, añade un nuevo archivo y escribe "LICENSE" en el campo de nombre, entonces aparecerá la opción "Elegir una plantilla de licencia".

<img src="../images/media/image78.jpg" style="width:350px;height:auto;" />

Asegúrate de que tu repositorio de GitHub sea público, para que cualquiera pueda realizar búsquedas en él.

### Haciendo el código citable

No todo el código tiene que ser citable. Cuando se publica de forma independiente, sin embargo, existen algunas prácticas recomendadas sobre cómo hacer que tu código sea citable.

Añadir el código a un repositorio de GitHub no es suficiente para archivar código. Para archivar, debemos asignar un identificador persistente.

Producir un identificador persistente para tu código es la mejor manera de hacerlo citable. Esto podría hacerse mediante una publicación revisada por pares que describa el software o archivando el software en un repositorio a largo plazo que produzca un DOI o un identificador similar. Para el código compartido en GitHub, un [DOI se puede producir fácilmente para cada versión del software de Zenodo.](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content#issuing-a-persistent-identifier-for-your-repository-with-zenodo)

### Actividad 4.2: Crear un DOI para un Archivo de Código de Prueba

Puedes crear Identificadores de Objetos Digitales (en inglés, _Digital Object Identifier, DOIs_) para tu código que lo hacen citable. Para hacer esto, archiva un repositorio de código GitHub en Zenodo y emite un DOI para el registro.

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

Zenodo archives your repository and issues a new DOI each time you create a new GitHub [release](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases). Follow the steps at "[Managing releases in a repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)" to create a new one.

### Making it Easy to Cite Your Code

Information about how to cite the software can then be added to your README or other documentation in your repository. Another useful step for making your repository citation information accessible is to add a CITATION file to the repository.

### Why use CITATION files?

CITATION files are a means to make citation information easily accessible in open source software repositories. A [citation file format (CFF)](https://citation-file-format.github.io/) is a human and machine-readable standard format that has been developed for CITATION files.

### Adding Contributor Guidelines

<img src="../images/media/image419.png" style="width:100%;height:auto;" />

If you are hoping for community input on your software, it is a best practice to include CONTRIBUTING and CODE_OF_CONDUCT files in your repository that outline expectations for member interactions.

We won't go into these in detail here, but you can check out the [Xarray package's github repository](https://github.com/pydata/xarray/tree/main) for a good example.

## Who: Roles and Responsibilities of the Team Members in Implementing the SMP

When writing a SMP, it's important to include a plan for the roles and responsibilities needed to share and (if applicable) maintain your code. Your community will consist of members in different roles – some actively engaged, some with only a passing interest. Sometimes, multiple roles can easily be done by one person (e.g. if you are just archiving a piece of code).

Some roles might include:

**Who will add the code to a public repository?**

- Uploading the code
- Assigning a license

**Who will take care of code documentation**

- Writing a README
- Adding explanatory comments to the code

**Who will help with code reuse?**

Adding CITATION, CONTRIBUTING, and CODE_OF_CONDUCT files

**Who will maintain the software (if applicable)?**

- Who will respond to community input (e.g. via GitHub issues)?
- Who will be responsible for making decisions about which code to add/update from other contributors? (e.g. via GitHub pull requests)

---

All of these roles may or may not be needed, depending on the size of your project. Have a transparent process for assigning any roles to community members.

### Responsibilities after Sharing

If the software is meant for others to use, then the developer should maintain the software.

- It is polite for the developer to let users know whether or not they intend to maintain the software/code.
- Do this in the documentation where you discuss the development status of the project.
- This will help users know if it will continue to be supported in the future and allow them to make choices about basing ongoing work off your project.
- In the case that a developer/researcher may not have the time or continued funding to keep up with a project but others are interested in keeping it maintained, consider handing ownership of the software to another researcher/developer, involved user or entity invested in its continued use.
- Users of software that is no longer maintained may consider contacting the owner/developer and volunteering either as a maintainer or to take over ownership of the project.
- If you decide to maintain your software, you should respond to requests for features and fixes as you are able.

## Lesson 4: Summary

In this lesson, you learned the key steps in sharing open software:

- Should you share? When sharing software, the policies of your institution and funding agency must be followed. These may limit the openness of the software. Software sharing policies also vary by organization.
- When to share? Follow guidance from your organization, funding agency, or publisher.
- Where to share? It depends on whether you are archiving or sharing for community input. Use domain-specific repositories where appropriate.
- How to enable reuse? Habilita la reutilización mediante la asignación de un DOI e incluye una licencia, información de citas y directrices para colaboradores.
- ¿Quién ayuda a compartir? Planifica los roles y responsabilidades cuando se comparta y (si es aplicable) para mantener el software.

## Lección 4: Evaluación

Answer the following questions to test what you have learned so far.

_Question_

**01/06**

Read the statement and decide whether it's true or false:

_I don’t need to share my code if I don't plan to continue developing it._

- True
- False

_Question_

**02/06**

Read the statement and decide whether it's true or false:

_Adding code to a GitHub repository is sufficient for archiving my code._

- True
- False

_Question_

**03/06**

Read the statement and decide whether it's true or false:

_Organization and government software-sharing policies follow a standard practice._

- True
- False

_Question_

**04/06**

Read the statement and decide whether it's true or false:

_Publishing your software to a software repository used by common package managers makes it easier for users to install your software._

- True
- False

_Question_

**05/06**

Which, if any, of the following are ways you can help others to reuse your code? Select all that apply.

- Assign an appropriate license
- Add a file named "CONTRIBUTING" with contributor guidelines
- Add a "CITATION" file with citation information

_Question_

**06/06**

Which of the following are roles that you should plan for when writing a SMP? Select all that apply.

- Who will help maintain the software
- Who will create the repository and add the necessary files
- Who will contribute to the software after it is shared
- Who will add documentation to the software
