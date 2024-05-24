# Lección 4: Compartir Código abierto

## Contenidos

- [Descripción general](#descripcion-general)
- [Objetivos de Aprendizaje](#objetivos-de-aprendizaje)
- [Planificación para compartir tu código](#planning-to-share-your-code)
- [Preocupaciones legales y de seguridad](./Lesson_4#legal-and-security-concerns)
- [Cuando: El Cronograma para Archivar y Compartir Código.](./Lesson_4#when-the-schedule-for-code-archiving-and-sharing)
- [Dónde: Dónde Compartir Código Abierto](./Lesson_4#where-to-share-open-code)
- [Cómo: Cómo habilitar la reusabilidad del código](./Lesson_4#how-to-enable-reuse-of-code)
- [Quién: Roles y Responsibilidades de los Miembros del Equipo en la Implementación del SMP](./Lesson_4#who-roles-and-responsibilities-of-the-team-members-in-implementing-the-smp)
- [Lección 4: Resumen](#lesson-4-summary)
- [Lección 4: Evaluación](#leccion-4-evaluacion)

## Descripción general

En esta lección aprenderás los pasos para compartir el software que desarrollaste. Estos pasos incluyen determinar si el software debe compartirse, cuándo y dónde, qué funciones son necesarias y cómo permitir que otros utilicen el código.

## Objetivos de aprendizaje

Después de completar este módulo, deberías ser capaz de:

- Describir lo que significa compartir código: para archivar o para desarrollar código.
- Evaluar si se debe compartir el código y enumerar las consideraciones importantes en materia de seguridad.
- Describir las mejores prácticas para cuándo y dónde compartir código.
- Recordar las prácticas más habituales para ayudar a otros a reusar tu código.
- Enumerar los roles y las responsabilidades para compartir y mantener el código compartido.

## Planificación para compartir tu código

<img src="../images/media/image540.png" style="width:350px;height:auto;" />

Estuve trabajando en un código y ahora un nuevo colaborador quiere utilizarlo. ¡Genial! ¿Cuál es la mejor manera de compartir el código? ¿Por correo electrónico? ¿Cuándo debo compartir el código y qué debo incluir para asegurar que esta persona pueda utilizarlo fácilmente?"

### ¿Qué significa "Compartir" tu código?

Para compartir, existen dos categorías principales: el compartir para el desarrollo y el proporcionar un registro a largo plazo.

### Desarrollo de código abierto

Escribir código científico suele ser un proceso dinámico y colaborativo en el que contribuyen varias personas y el código evoluciona con el tiempo. En este tipo de proyectos, es beneficioso desarrollar código abierto en una plataforma pública de alojamiento de repositorios como Github, Bitbucket, GitLab, etc. desde el principio del proyecto. Esto garantiza que todas las actualizaciones se compartan abiertamente en la web y puedan llegar a colaboradores y usuarios potencialmente interesados casi en tiempo real.

### Archivado Código Abierto

El archivado garantiza que tu código científico sea accesible a largo plazo y pueda cumplir con los requisitos de archivado de organismos de financiación e instituciones. La accesibilidad a largo plazo ayuda a otros a reproducir tus resultados mucho tiempo después de tu publicación. El archivado por sí solo no fomenta el desarrollo continuo ni la colaboración. Se trata de preservar el software de forma estática y a largo plazo, no de hacerlo evolucionar.

### ¿Deberías compartir tu software?

Hay varias cuestiones legales y de seguridad que hay que tener en cuenta a la hora de crear o usar software abierto.

- Por lo general, cualquier software que crees se considera propiedad intelectual y puede estar controlado por las políticas de tu institución.
- Tales políticas pueden influir en cuán abiertamente se puede compartir el software y, por lo tanto, su licencia.
- La descarga y contribución a proyectos de software libre puede estar regulada por las políticas de seguridad informática de tu institución.

En cambio, si el software se desarrolló con financiación externa (del gobierno), algunos organismos de financiamiento pueden exigir que el software se comparta abiertamente.

### Plan de gestión de software (PGS)

¿Recuerdas las partes del Plan de Gestión de Software? ¿Qué debemos tener en cuenta a la hora de compartir?

- **Qué:** Descripción de la gestión, conservación y distribución de software.
- **Cuándo:** El cronograma para archivar y compartir software.
- **Dónde:** Ubicación donde se compartirá y archivará el software a largo plazo.
- **Cómo:** Habilitar la reutilización del software mediante la asignación de un DOI, licencia, directrices de contribución, etc.
- **Quién:** Roles, funciones y responsabilidades de los miembros del equipo.

## Cuestiones legales y de seguridad

<table>
  <thead>
    <tr>
        <th>CUESTIONES LEGALES ☑</th>
        <th>CUESTIONES DE SEGURIDAD</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Todo aquel que escriba código y software de investigación debe familiarizarse con las políticas de su institución en materia de compartir y publicar software. Las organismos de financiamiento, gubernamentales o privados, pueden tener requisitos estrictos en cuanto a software abierto. En otras ocasiones, la institución puede no permitir que se comparta el software.</p>
            <p>Las cuestiones legales pueden incluir preguntas como:</p>
            <ul>
                <li>¿Es un desarrollador o una institución el propietario del software?</li>
                <li>¿El compartir (o no compartir) el software viola las políticas del organismo de financiamiento?</li>
                <li>¿Existen leyes o normas en tu zona que regulen compartir la propiedad intelectual?</li>
                <li>¿Qué licencia de software se necesita?</li>
            </ul>
            <p><strong>Cuando decidas participar o iniciar un nuevo proyecto de software libre, familiarízate con las políticas y prácticas de tu institución.</strong></p>
            <p>Más información sobre los aspectos legales <a href="https://opensource.guide/legal/">aquí</a>.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>CONCIONES LEGALES</th>
        <th>CUESTIONES DE SEGURIDAD ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>La seguridad es una preocupación a la hora de compartir software. Los malhechores pueden adjuntar códigos maliciosos a los programas informáticos en un intento de infiltrarse en los sistemas informáticos a través de las vulnerabilidades de seguridad, exponiendo potencialmente información sensible y privada que puede acarrear grandes pérdidas económicas a los usuarios. La seguridad es una preocupación a la hora de compartir software.</p>
            <p>Las cuestiones de seguridad pueden incluir:</p>
            <ul>
                <li>¿Permite la política de Tecnologías de la Información (TI) de tu organización que compruebes el código que quieres utilizar en tu máquina?</li>
                <li>¿Tiene buena reputación el repositorio al que desea contribuir?</li>
                <li>¿Hay algún problema abierto relacionado con la seguridad del código?</li>
            </ul>
            <p><strong>Una vez que decida participar o iniciar un nuevo proyecto de software abierto, familiarícese con las políticas y prácticas de su organización.</strong></p>
            <p>Más información sobre los aspectos legales <a href="https://opensource.guide/legal/">aquí</a>.</p>
        </td>
    </tr>
  </tbody>
</table>

### Compartir programas informáticos creados con fondos de agencias estadounidenses

Muchos organismos federales ya permiten (si no exigen) compartir el código creado en el marco de sus programas de subsidios. Por ejemplo:

- [NASA](https://www.nasa.gov/open/open-source-development.html) "...estamos llegando activamente a proyectos dentro de la NASA para hacer uso de ...recursos para publicar código abierto."
- [Departamento de Comercio de EE.UU.](https://www.commerce.gov/about/policies/source-code) «...requiere que las agencias desarrollen planes para liberar al menos el 20 por ciento del nuevo código fuente desarrollado a medida como Software de Código Abierto (OSS) al encargar nuevo software a medida».
- [USGS](https://www.usgs.gov/survey-manual/im-osqi-2019-01-review-and-approval-scientific-software-release) «...las versiones de software se consideran bienes de dominio público y, por lo general, están disponibles sin restricciones».

¿Está financiado por un subsidio? Lea la convocatoria original de la subvención para ver si se permite/requiere la publicación de su código y compruebe si contiene algún texto sobre la gestión del software y alguna condición para publicar su código. En caso de duda, póngase en contacto con su organización para obtener información adicional.

### Actividad 4.1: Encuentra las políticas de lanzamiento de software de tu organización

<img style="width:350px;height:auto;" src="../images/media/lightbulb.png">

Supongamos que desea iniciar un nuevo proyecto de código abierto:

- Conozca las políticas de su organización en materia de publicación de software.
- ¿Cuál es el proceso para liberar su software?
- ¿Alguien en su organización tiene que aprobar esta versión?
- ¿Existen políticas con respecto a los contribuyentes externos?
- ¿Su organización requiere una atribución o crédito específico?

#### Puntos clave: Conozca las políticas de publicación de software de su organización

Las políticas de liberación de software difieren según la organización y cada pieza de software es diferente. Por lo tanto, es importante que no hagamos suposiciones sobre las políticas de publicación de software basadas en experiencias anteriores.

## Cuándo:\*\* El cronograma para archivar y compartir software

Planear para compartir tu código al comienzo de tu proyecto hace que compartir sea más fácil cuando estés listo. Exactamente cuando en tu flujo de trabajo decides compartir públicamente tu código depende de tu trabajo y de los requisitos de la agencia de financiación, organización, o publicador.

Como ejemplo, ¿qué dice la NASA?

Si está escribiendo software científico para un proyecto financiado por el Directorio de Misión de Ciencia de la NASA (NASA Science Mission Directorate) entonces:

El software científico necesario para validar las conclusiones científicas de los manuscritos revisados por pares resultantes de las actividades científicas financiadas por el SMD se pondrá a disposición del público a más tardar en la fecha de publicación del correspondiente artículo revisado por pares. Esto incluye software necesario para derivar los hallazgos comunicados en cifras, mapas y tablas, así como software científicamente útil de modelos y simulaciones".

\- [\*\*Guía científica de código abierto (NASA SMD's Open-Source Science Guidance)](https://smd-cms.nasa.gov/wp-content/uploads/2023/07/smd-open-source-science-guidance-v2-20230407.pdf)

Otras organizaciones pueden tener orientaciones diferentes, por lo que siempre es mejor comprobar lo que exige la agencia u organización financiadora.

## Donde: Donde Compartir Código Abierto

### Consideraciones generales

<img src="../images/media/image197.png" style="width:100%;height:auto;" />

Al igual que los datos, el código puede compartirse de muchas maneras, por ejemplo por correo electrónico o en un sitio web personal, pero estos métodos no son recomendables. Entonces, ¿dónde debería compartir su código abierto?

En primer lugar, considere las políticas de su institución o agencia de financiación, que pueden dictar dónde debe compartir y dónde puede hacerlo. Por ejemplo, algunas agencias de financiación especifican los depósitos a largo plazo donde debe archivarse su código, y pueden restringirle el uso compartido en otras formas de repositorios. Su disciplina científica puede tener un repositorio específico para código abierto.

#### ¿Cuáles son las mejores opciones y prácticas para archivar el código?

- Archivar código abierto con un artículo de revista de acceso abierto.
- Si el código abierto está en un repositorio de desarrollo en línea activo como Github, cree una versión y archive el código en un repositorio a largo plazo con un DOI como Zenodo, que puede integrarse con Github (más detalles sobre este proceso más adelante).
- Archive el código en otros repositorios públicos a largo plazo, como Software Heritage.

#### Es su código un paquete de software importante y de interés para un número signiﬁcativo de usuarios de diversas disciplinas? ¿Dónde más puede compartirse su código abierto?

<img src="../images/media/image332.png" style="width:350px;height:auto;" />

- Desarrollar tu software en un repositorio público como GitHub.
- Publicar en un repositorio de software usado por los gestores de paquetes comunes para facilitar la instalación del software (ej. Anaconda, CRAN, PyPI).
- Presentar el software en conferencias.
- Publicar el software en un Journal dedicado al software abierto (ej. JOSS).
- Consigue que tu software sea revisado por expertos a través de comunidades como PyOpenSci.

#### Para compartir mi código, sólo tengo que añadirlo a github, ¿verdad?

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
8. Desplázate hacia abajo y haz clic en el botón verde 'publicar lanzamiento' (en inglés, _publish release_)

<img src="../images/media/zenododoi8.jpg" style="width:100%;height:auto" />

9. Navega a la [Zenodo GitHub page](https://sandbox.zenodo.org/account/settings/github/) y ve el DOI para 'os-test'.
10. A continuación, comparte tu DOI.

<img src="../images/media/zenododoi10.jpg" style="width:100%;height:auto" />

Zenodo archiva tu repositorio y emite un nuevo DOI cada vez que creas un nuevo [lanzamiento](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) GitHub. Sigue los pasos en "[Administrar lanzamientos en un repositorio](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)" para crear una nueva.

### Haciendo Fácil Citar tu Código

La información sobre cómo citar el software puede ser añadida a su LÉEME (en inglés, _README_) u otra documentación en tu repositorio. Otro paso útil para hacer accesible la información de citas de tu repositorio es añadir un archivo CITACIÓN (en inglés _CITATION_) al repositorio.

### ¿Por qué usar archivos CITACIÓN?

Los archivos CITACIÓN son un medio para hacer que la información de citas sea fácilmente accesible en repositorios de software de código abierto. Un [formato de archivo de citas (en inglés, _Citation File Format, CFF_)](https://citation-file-format.github.io/) es un formato estándar legible por humanos y máquinas que se ha desarrollado para los archivos CITACIÓN.

### Pautas para Colaborar

<img src="../images/media/image419.png" style="width:100%;height:auto;" />

Si espera que la comunidad contribuya a su software, es una buena práctica incluir archivos COLABORAR (en inglés, _CONTRIBUTING_) y CÓDIGO DE CONDUCTA (en inglés, _CODE_OF_CONDUCT_) en su repositorio que describan las expectativas para las interacciones de los participantes.

No entraremos en detalles aquí, pero puedes consultar el [repositorio github del paquete Xarray](https://github.com/pydata/xarray/tree/main) para ver un buen ejemplo.

## ¿Cuáles son los roles y las responsabilidades de quienes participan del equipo en la implementación del PGS?

Cuando se escribe un Plan de Gestión de Software (PGS) (en inglés, _Software Management Plan, SMP_), es importante incluir un plan para los roles y responsabilidades necesarios para compartir y (si corresponde) mantener tu código. Tu comunidad estará formada por personas con diferentes roles: algunos participarán activamente, otras sólo tendrán un interés pasajero. A veces, una sola persona puede desempeñar fácilmente varias funciones (por ejemplo, si sólo estás archivando una pieza de código).

Algunos roles podrían incluir:

**¿Quién añadirá el código a un repositorio público?**

- Subiendo el código
- Asignando una licencia

**¿Quién se encargará de la documentación del código?**

- Escribiendo un archivo LÉEME
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
- ¿Cómo permitir la reutilización? Habilita la reutilización mediante la asignación de un DOI e incluye una licencia, información de citas y pautas para colaboradores.
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

¿Cuáles de los siguientes son roles que deberías planificar al escribir un PGS? Selecciona todos los que correspondan.

- Quién ayudará a mantener el software
- Quién creará el repositorio y añadirá los archivos necesarios
- Quién contribuirá al software después de que se comparta
- Quién agregará documentación al software
