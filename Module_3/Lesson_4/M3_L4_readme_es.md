# Lección 4: Compartir Datos Abiertos

## Contenidos

- [Resumen](#resumen)
- [Objetivos de Aprendizaje](#objetivos-de-aprendizaje)
- [Cuándo y si compartir datos](#cuando-y-si-compartir-datos)
- [Dónde compartir datos](#dónde-compartir-datos)
- [Cómo Habilitar la Reutilización de Datos](#como-habilitar-la-reutilizacion-de-datos)
- [Quién es Responsable de Compartir los Datos](#quien-es-responsable-de-compartir-los-datos)
- [Lección 4: Resumen](#leccion-4-resumen)
- [Lección 4: Revisión De Conocimientos](#leccion-4-revision-de-conocimientos)

## Resumen

En esta lección aprenderás sobre la práctica de compartir tus datos. La discusión comienza con una revisión del proceso de compartir y cómo evaluar si sus datos son compartibles. Después, asegurate de que tus datos sean accesibles controlando de cerca los respositorios y el ciclo de vida de la accesibilidad de los datos, desde la selección de un repositorio hasta mantener y archivar tus datos. La lección luego discute algunos pasos para hacer los datos lo más reutilizables posible y concluye con una sección sobre la definición de quién ayudará con el proceso de compartir los datos.

## Objetivos de Aprendizaje

Después de completar esta lección, deberías ser capaz de:

- Reconocer variables institucionales, cuestiones de seguridad y tiempo que puedan afectar tu decisión de compartir datos.
- Recordar las características, responsabilidades inherentes, consideraciones de financiamiento y requisitos de patrocinadores que las personas que investigan deberían tener en cuenta al seleccionar un repositorio para compartir datos.
- Describir las herramientas y enumerar algunas de las buenas prácticas que optimizan la compartibilidad de los datos.

## Resumen del Proceso de Compartir Datos

Compartir datos es una parte crítica de mejorar la reproducibilidad de los resultados. Tanto si se trata de datos nuevos que recolectamos por nuestra parte como datos que procesamos para hacer nuestro análisis, terminamos compartiendo algún tipo de dato. Tenemos que pensar qué datos vamos a compartir y cuál es la mejor manera de asegurar que será de forma abierta y utilizable por otras personas.

Normalmente, el intercambio de datos debe hacerse a través de un centro de datos estable o un repositorio que será responsable de ingestar, curar y distribuir/publicar tus datos abiertos. Tú eres responsable de proporcionar información/metadatos para ayudar a que tus datos sean fáciles de encontrar, acceder y citar. El costo de archivar y publicar datos también debe ser considerado.

### Así que Quieres Compartir Tus Datos

Una vez que hayas decidido compartir tus datos, hay una serie de preguntas que tendrás que responder para ayudarte a planificar y que deben incluirse en tu plan de gestión de datos (PGD):

|          |                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------- |
| ¿Qué?    | Formato y (si es relevante) estándares de datos                                 |
| ¿Cuándo? | Cuándo y si compartir datos                                                                        |
| ¿Dónde?  | Los repositorios destinados a datos archivados                                                     |
| ¿Cómo?   | Cómo el plan permite la reutilización de los datos                                                 |
| ¿Quién?  | Roles y responsabilidades de las personas que forman parte del equipo en la implementación del PGD |

En esta lección, cubriremos algunos pasos hacia la obtención de datos. Específicamente, nos enfocaremos en las secciones "cuándo", "dónde", "cómo" y "quién" de un DMP.

### Proceso para Compartir Datos Abiertos

En general, compartir tus datos abiertos requiere de los siguientes pasos:

1. Asegúrate de que tus datos puedan ser compartidos
2. Selecciona o identifica un repositorio para alojar tus datos
3. Trabaja junto con tu repositorio para seguir su proceso y cumplir con sus requerimientos
4. Asegúrate de que tus datos sean encontrables y accesibles a través del repositorio y que sean mantenidos y archivados
5. Solicita un DOI para tu conjunto de datos para que pueda ser citado fácilmente
6. Choose a data license

Sometimes, you may be able to work with a well-staffed repository that will handle many of these steps for you (for instance, if you are working with NASA mission data). Otherwise, it is your responsibility to follow the above steps to share your data openly.

## When and If to Share Data

### When to Share Data?

The decision of when to share should be discussed with everyone on the team and documented in the data management plan. Funding agencies and organizations may have specific requirements about when data must be shared, but here we encourage you to think about whether it is feasible or possible to share even earlier than required by your funder. There are different times when data could be shared:

- Advanced Sharing: Sharing at the time of collection, or soon after. Some funding agencies require this, or allow for a short ‘embargo’ period, but a reason (quality checks, calibrations, etc.) is usually required. This maximizes data reuse and impact and can result in increased collaborations.
- Intermediate Sharing: At the time of publication. Many publications (and some funding agencies) require sharing data that is needed to reproduce results at the time of publication.
- Minimum Sharing: End of grant. All scientifically useful data should be shared by the end of the research grant.
- No Sharing: There are many reasons data should either be restricted or not shared at all.

As discussed previously in this curriculum, there are many benefits to sharing as early as possible. Early (advanced) sharing can lead to new and unexpected discoveries and expand your collaboration network. Remember, that even when you share data, you are still the world expert on that data! So often, when people want to work with the data, they will reach out to you to collaborate.

### Should the Data be Shared?

Before datasets are shared, it’s important to consider any restrictions to your permission to share and ensure that your contributors – including sample and data donors – approve its release.

Data should be as open as possible and as closed as necessary.

- Opening our data is a powerful way to enable discovery, transparency, and scientific progress.
- Some data are subject to laws, regulations, and policies which limit the release of the data.
- Your local institution may have additional policies and resources – investigate them early and often.

### Verify Your Data is Sharable

Before you decide where to share your data, you must make sure you can share your data.

Data needs to be as open as possible and as closed as necessary...

- Open data is a powerful way to enable discovery, transparency, and scientific progress
- But, some data are subject to laws, regulations, and policies which limit the release of the data
- Your local institution may have additional policies and resources – investigate them early and often

Specific considerations that might prevent the sharing of your data include:

- A country's military secrets or violations of national interests
- Private medical information or an individual’s personal data
- Indigenous/cultural/conservation concerns
- Intellectual Property, Patented
- Other - please think about what you are sharing and the implications of sharing it (for example - do you have permission from everyone involved?)

In the first module of this curriculum, we listed several reasons why certain research products should not be shared. We will review some of these reasons, and go into more detail on a few that are particularly relevant to data.

### Export and Security Considerations

Relevant laws and regulations that may prevent the release of data include but are not limited to:

- [International Traffic in Arms Regulation](https://www.pmddtc.state.gov/?id=ddtc_public_portal_itar_landing) (ITAR), which regulates the manufacture, sale, distribution, and export of defense-related articles and services.
- [Export Administration Regulations](https://www.bis.doc.gov/index.php/regulations/export-administration-regulations-ear) (EAR), which regulates the manufacture, sale, distribution, and export of commercial and dual- use items, technology, and information not already covered by ITAR.

**Example: NASA Space System Protection Standard**

NASA STD 1006.1 [Space System Protection Standard](https://standards.nasa.gov/standard/NASA/NASA-STD-1006), which establishes protection requirements to ensure NASA missions are resilient to purposeful threats.

### Controlled Information Considerations

Some regulations and policies that may prevent the sharing of data include but are not limited to:

- [Health Insurance Portability and Accountability Act](https://www.hhs.gov/hipaa/index.html) (HIPAA), which established standards to protect sensitive patient health information from disclosure.
- [Controlled Unclassified Information](https://www.archives.gov/cui) provides standards for handling unclassified information that requires safeguarding or dissemination controls consistent with laws, federal regulations, and policies.
- Federal laws and regulations governing [classified information](https://www.archives.gov/isoo/faqs) or security requirements.

### Intellectual Property Considerations

Data may be subject to intellectual property, copyright, and licensing concerns. A few of the relevant regulations and policies include patent or intellectual property laws including the [Bayh-Dole Act](https://www.govinfo.gov/content/pkg/USCODE-2011-title35/html/USCODE-2011-title35-partII-chap18.htm), which enables universities, nonprofit research institutions, and small businesses to own, patent, and commercialize inventions developed under federally funded research programs.

**Example: NASA FAR Supplement 1852.227**

[NASA FAR Supplement 1852.227](https://prod.nais.nasa.gov/far/far0595-nfs012617/5227.htm), which outlines patent and data rights for government contracts.

---

Many research institutions have resident experts in intellectual property, copyright, and patent law. They can be a great resource if you have any questions or concerns.

## Where to Share Data

Data can be shared in a variety of locations. While sharing data via email or websites is popular, they are not recommended as they do not meet the requirements for findability or long-term archival support. Sharing data as part of the supplemental material of a peer reviewed publication, especially for small data sets, is acceptable in some fields. A long term repository that provides a permanent identifier is the best option for sharing of data.

### Selecting a Data Repository

If you do not already have a data repository in mind, consider the following to narrow down your options:

- Does your funding sponsor require a specific data repository?
- Does your organization/institution recommend a specific data repository?
- Is there a domain-specific repository that is widely-used in your research field?
- Does the repository provide open data access?
- Do you think the tools offered by the repository for data discovery and distribution are suitable for your data and FAIR?
- Does the repository require funding from your project, does it fit within your budget and does it require sustained support beyond the project life cycle?

Find and compare the services, beneﬁts and limitations of the repositories you are considering. Each repository will have its own processes and requirements for accepting and hosting your data depending on their level of funding, purpose, and user base.

Similarly, each repository will provide a different set of functionality and services depending on their level of funding, purpose, and user base.

Data with privacy concerns may have additional anonymization or approval processes or restrictions on who can access the data.

La Casa Blanca presenta una buena descripción general de las características deseables [aquí](https://www.whitehouse.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf) (en inglés).

### Garantizar la accesibilidad

Los buenos repositorios compartirán (u ofrecerán) sus datos abiertos a través de protocolos estándar, como HTTPS o SFTP. Las formas comunes de hacer esto son:

- Permitir a las personas usuarias la posibilidad de ver una lista de archivos en los que pueden hacer clic y descargar a través de una interfaz intuitiva.
- Crear una API documentada para que quienes utilizan la herramienta generen una lista de enlaces de archivos que cumplan con los criterios de búsqueda y que se puedan descargar de forma automatizada (es decir, acceso a datos de máquina a máquina).

Adicionalmente, los repositorios pueden requerir autorización y autentificación (por ejemplo, iniciar sesión con nombre de usuario/contraseñas) para acceder a los datos. Si bien esto está permitido según los principios FAIR, puede violar los principios de la Ciencia Abierta si no todas las personas pueden registrarse.

### Trabajar con un repositorio

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO ☑</th>
        <th>MANTENIMIENTO DE DATOS EN EL REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los requisitos del repositorio pueden variar ampliamente. Revisa siempre los requisitos del repositorio para ver qué acciones necesitas llevar a cabo una vez cuando consideres empezar a trabajar con ellos. También ten en cuenta que algunos repositorios cuentan con personal que ayuda con el proceso de compartir datos, mientras que otros dependen de que sepas cómo compartir tus propios datos.</p>
            <p>Si utilizas un repositorio que tiene personal para ayudarte con el proceso, podrían solicitar revisar y comentar tu plan de gestión de datos.</p>
            <p>El repositorio puede solicitar que realice algunas pruebas de su muestra de datos para evaluar:</p>
            <ul>
            <li>That the data format you intend to use is supported.</li>
            <li>That data variables are named as expected.</li>
            <li>That metadata vocabulary is correct.</li>
            <li>That repository-specific requirements are met.</li>
            </ul>
            <p>This conformity check can identify misunderstandings early and result in a smooth final submission of your data to the repository.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>START WORKING WITH A REPOSITORY</th>
        <th>MAINTAINING DATA AT A REPOSITORY ☑</th>
        <th>ARCHIVING DATA AT A REPOSITORY</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>As you progress through your project lifecycle, utilize your repository's update, revision and resubmission processes to keep the archived data products up to date. Any new versions of the data you want to share through the repository will need to go through a similar process as your initial data set.</p>
            <p>Any new versions of the data you want to share through the repository should go through the same DMP review, compliance check, and upload procedure as your initial data set.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>START WORKING WITH A REPOSITORY</th>
        <th>MAINTAINING DATA AT A REPOSITORY</th>
        <th>ARCHIVING DATA AT A REPOSITORY ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>When your project ends, ensure you’ve updated and uploaded any companion documentation (discussed in the previous lesson "Making Open Data") with your final version (even if only a single version of the data was made).</p>
            <p>Make sure the repository will keep your data (or at least your metadata) on- line for a reasonable period of time after your project ends.</p>
            <p>If any data issues are found after the conclusion of your project, make sure the repository will still accept data revisions, if they are needed.</p>
        </td>
    </tr>
  </tbody>
</table>

## How to Enable Reuse of Data

### Obtaining a DOI

Individuals cannot typically request a DOI (digital object identifier) themselves but rather have to go through an authorized organization that can submit the request, such as:

- The data repository
- Your organization
- The publisher (if the data set is part of a publication)

Data makers should provide summary information for DOI landing page(s) if required. Data sharers should accommodate data providers' suggestions and comply with DOI guidelines and create landing page(s). If possible, reserve a DOI for you ahead of creating your data.

### Ensuring Findability

Repositories handle the sharing, distribution, and curation of data. Additional services they may provide include:

- The assignment of a persistent identifier (like a DOI) to your data set
- The indexing and/or registration of your data and metadata in various services so that they can be searched and found online (i.e., through search engines).
- The provision of feedback to data makers to help them optimize their metadata for findability.
- Coordinating with data makers to ensure metadata refers to the DOI.
- Ensuring the DOI is associated with a landing page with information about your data.

### Making it Easy to Cite Your Data

The goal is to make it easy to cite your data. Best practices include:

- Include a citation statement that includes your DOI.
- Different repositories and journals have different standards for how to cite data. If your repository encourages it, include a .CFF file with your data that explains how to cite your data.
- Clearly identify the data creators and/or their institution in your citation.
  - This allows users to follow up with the creators if they have questions or discover issues.
  - Include ORCiD of data authors where possible in the citation.

Now that your data are at a repository and have a citation statement and DOI, publicize it to your users and remind them to cite your data in their work!

## Who is Responsible for Sharing Data

Sharing data openly is a team effort. An important part of planning for open data is planning and agreeing to roles and responsibilities of who will ensure implementation of the plan.

So what needs to be done? Documenting these roles and responsibilities in your Data Management Plan will help your team stay organized and do science faster! A well-written, detailed plan should include:

### Who Will Move Data to a Repository

Once you are ready to send your data to your repository, find the repository's recommendations for uploading data. Determine who will work with your repository to accomplish the following types of activities:

- Provide information on data volume, number of files, and nature (e.g., revised files)
- Check that the file name follows best practices
- How will the data be moved? (especially when files are large)
- Check the data! Verify the integrity of the data, metadata, and documentation transfer

### Who Will Develop the Data Documentation and Metadata

Determine who will work with your repository, inventory the transferred data, metadata, and documentation. This role might include the task of populating any required metadata in databases to make the data findable.

You may be able to accomplish some of these tasks through a repository's interface. However, some types of repositories may require you to interact with their administration teams. For this role, determine who will:

- Provide suggestions to organize data content and logistics-
- Develop the metadata
- Develop the documentation (e.g., README file or report)
- Extract metadata from data files, metadata files (if applicable), and documentation to populate the metadata database and request additional metadata as necessary

### Who Will Help With Data Reuse

Once the repository has made your data available, someone from your team must test access to the data (its accessibility) and distribution methods (its findability). If possible, identify who will work with your repository to optimize/modify tools for intuitive human access and standardize machine access. This role requires someone who to:

- Clearly communicate the open protocols needed for the data/metadata.
- Provide actual data use cases to data publisher to optimize/modify data distribution tools based on available metadata.
- Understand the access protocol(s) and evaluate implications to targeted communities and user communities at large in terms of accessibility.

### Who Will Develop Guidance on Privacy and Cultural Sensitivity of Data

Sharing data should be respectful of the communities that may be involved. This means thinking about privacy issues and cultural sensitivities. Who on your team will identify and develop guidance on:

- Privacy concerns and approval processes for release - is the data appropriately anonymized?
- How to engage with communities that data may be about.
- How data can be correctly interpreted.
- Are there any data restrictions that may be necessary to ensure the sharing is respectful of the community the data involves, eg. collective and individual rights to free, prior, and informed consent in the collection and use of such data, including the development of data policies and protocols for collection?

## Lesson 4: Summary

The following are the key takeaways from this lesson:

- When and if to share data? Determine at what point in a project it makes the most sense to share our data. Remember, not all data can or should be shared.
- Where to share data? Sharing in a public data repository is recommended, and there are many types of repositories to choose from.
- How to enable reuse? Ensure appropriate, community-accepted metadata, assign a DOI, and develop a citation statement to make sure it can be easily found and cited.
- Who helps share data? There are many steps in making and sharing data and it’s important to think about who will be responsible for each step.

## Lesson 4: Knowledge Check

Answer the following questions to test what you have learned so far.

_Question_

**01/04**

Data cannot be shared if it is:

- ITAR controlled
- Controlled Unclassified Information
- Subject to intellectual property, copyright, and licensing concerns
- All of the above

_Question_

**02/04**

Select the option you think is correct to complete the sentence.

It is best practice to start working with a repository _____.

- As early as possible
- When you have test data ready
- After you obtain a DOI
- When you are ready to release your data

_Question_

**03/04**

Which one of the following might be able to help you get a DOI for your data:

- The repository you are working with
- Your home organization
- A journal you are submitting a manuscript and data to
- All of the above

_Question_

**04/04**

Which of the following are roles to consider when sharing data? Select all that apply.

- Develop guidance on privacy and cultural sensitivity of the data
- Develop the data documentation and metadata
- Assign the data a DOI
- Verify the integrity of the data, metadata, and documentation transfer
