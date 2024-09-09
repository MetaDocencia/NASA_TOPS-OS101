# Lección 4: Compartir Datos Abiertos

## Contenidos

- [Cuándo compartir los datos y si hacerlo](#cu%C3%A1ndo-compartir-los-datos-y-si-hacerlo)
- [Dónde compartir datos](#d%C3%B3nde-compartir-datos)
- [Cómo habilitar el reúso de datos](#c%C3%B3mo-habilitar-el-re%C3%BAso-de-datos)
- [Quién es responsable de compartir Datos](#qui%C3%A9n-es-responsable-de-compartir-datos)
- [Lección 4: Resumen](#lecci%C3%B3n-4-resumen)
- [Lección 4: Evaluación](#lecci%C3%B3n-4-evaluaci%C3%B3n)

## Descripción general 

En esta lección aprenderás cómo compartir tus datos. La discusión comienza con una revisión del proceso de compartir y evaluar si tus datos pueden compartirse. Luego, se analizará cómo garantizar que tus datos sean accesibles viendo más de cerca los repositorios y el ciclo de vida de la accesibilidad de los datos, desde la selección de un repositorio hasta el mantenimiento y archivo de tus datos. La lección luego aborda algunos pasos para hacer los datos lo más reusables posible y concluye con una sección sobre la definición de quién ayudará con el proceso de compartir los datos.

## Objetivos de aprendizaje

Al finalizar esta lección deberías ser capaz de:

- Reconocer variables institucionales, cuestiones de seguridad y tiempo que puedan afectar tu decisión de compartir datos.
- Recordar las características, responsabilidades inherentes, consideraciones de financiamiento y requisitos de patrocinadores que las personas que investigan deberían tener en cuenta al seleccionar un repositorio para compartir datos.
- Describir las herramientas y enumerar algunas de las buenas prácticas que optimizan la práctica de compartir los datos.

## Descripción general del proceso de compartir datos

Compartir datos es una parte crítica de mejorar la reproducibilidad de los resultados. Tanto si se trata de datos nuevos que recolectamos por nuestra parte como datos que procesamos para hacer nuestro análisis, terminamos compartiendo algún tipo de dato. Tenemos que pensar qué datos vamos a compartir y cuál es la mejor manera de asegurar que será de forma abierta y usable por otras personas.

Generalmente, el intercambio de datos debe hacerse a través de un centro de datos estable o un repositorio que será responsable de ingestar, curar y distribuir/publicar tus Datos Abiertos. Tú eres responsable de proporcionar información/metadatos para ayudar a que tus datos sean fáciles de encontrar, acceder y citar. También debes considerar el costo de archivar y publicar los datos.

### Entonces: quieres compartir tus datos

Una vez que hayas decidido compartir tus datos, hay una serie de preguntas que tendrás que responder para ayudarte a planificar y que deben incluirse en tu Plan de Gestión de Datos (PGD):

|          |                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------- |
| ¿Qué?    | Formato y (si es relevante) estándares de datos                                 |
| ¿Cuándo? | Cuándo compartir datos y si hacerlo                                                                    |
| ¿Dónde?  | Los repositorios destinados a datos archivados                                                     |
| ¿Cómo?   | Cómo permite el plan el reúso de los datos                                                 |
| ¿Quién?  | Roles y responsabilidades de las personas que forman parte del equipo en la implementación del PGD |

En esta lección, explicaremos algunos pasos hacia la obtención de datos. Específicamente, nos enfocaremos en las secciones "cuándo", "dónde", "cómo" y "quién" de un PGD.

### Proceso para compartir Datos Abiertos

En general, compartir tus Datos Abiertos requiere de los siguientes pasos:

1. Asegúrate de que tus datos puedan ser compartidos
2. Selecciona o identifica un repositorio para alojar tus datos
3. Trabaja junto con tu repositorio para seguir su proceso y cumplir con sus requerimientos
4. Asegúrate de que tus datos sean fáciles de encontrar y accesibles a través del repositorio y que sean mantenidos y archivados
5. Solicita un DOI para tu conjunto de datos para que pueda ser citado fácilmente
6. Elije una licencia de datos

A veces, puede que trabajes con un repositorio bien preparado que maneje muchos de estos pasos (por ejemplo, si está trabajando con los datos de la misión de la NASA). De lo contrario, es tu responsabilidad seguir los pasos anteriores para compartir tus datos abiertamente.

## Cuándo compartir los datos y si hacerlo

### ¿Cuándo Compartir Datos?

La decisión de cuándo compartir datos debería discutirse con todas las personas del equipo y documentarse en el Plan de Gestión de Datos. Las agencias de financiamiento y organizaciones pueden tener requerimientos específicos de cuándo deben compartirse los datos, pero aquí te animamos a pensar si es posible compartir tus datos antes de que te lo exija tu espónsor. Hay distintos momentos en que los datos pueden ser compartidos:

- Compartir de forma anticipada: Compartir al momento de la recolección o poco después. Algunas agencias de financiamiento requieren que así sea o permiten un pequeño período de "embargo", pero normalmente se requiere una razón (control de calidad, calibración, etc). Esto maximiza el reúso de los datos y el impacto, y puede resultar en un aumento de colaboraciones.
- Compartir de forma intermedia: Al tiempo de la publicación. Muchas revistas (y algunas agencias de financiamiento) requieren compartir los datos necesarios para replicar los resultados al momento de la publicación.
- Compartir de forma mínima: Fin del subsidio. Todos los datos científicamente relevantes deben ser compartidos para el final del subsidio de investigación.
- No compartir: Hay muchos motivos por los que los datos pueden ser restringidos o no compartidos en absoluto.

Como ya comentamos anteriormente en este curso, hay muchos beneficios para compartir los datos lo antes posible. Compartir temprano puede llevar a nuevos e inesperados descubrimientos y a expandir tu red de colaboraciones. Recuerda que, aún cuando compartes tus datos, tú sigues siendo la persona experta a nivel mundial en esos datos. Es muy probable que cuando las personas quieran trabajar con tus datos se pongan en contacto contigo para colaborar.

### ¿Se deben compartir los datos?

Antes de compartir los conjuntos de datos, es importante que tengas en cuenta cualquier restricción de permisos para compartir y te asegures que quienes contribuyen contigo, incluyendo donantes de muestras y datos, aprueben su publicación.

Los datos deben ser tan abiertos como sea posible y tan cerrados como sea necesario.

- Los Datos Abiertos son una manera poderosa de facilitar el descubrimiento, transparencia y progreso científico
- Pero algunos datos están sujetos a leyes, regulaciones y políticas que limitan su liberación
- Tu institución local puede tener políticas y recursos adicionales; investígalos lo antes posible y regularmente

Algunas consideraciones específicas que pueden impedir que compartas tus datos son:

- Secretos militares de un país o violaciones de los intereses nacionales
- Información médica privada o datos personales de un individuo
- Cuestiones culturales/indígenas/de conservación
- Propiedad intelectual, patentes
- Otras: por favor piensa sobre lo que estás compartiendo y cuáles son las implicancias de hacerlo (por ejemplo, ¿tienes el permiso de todas las personas involucradas?)

En el primer módulo de este curso, enumeramos varias razones por las que ciertos productos de investigación no deben ser compartidos. Repasaremos algunas de estas razones y profundizaremos en algunas que son especialmente relevantes para los datos.

### Consideraciones de exportación y seguridad

Leyes y regulaciones relevantes que pueden evitar la publicación de datos incluyen, entre otras:

- [Regulación Internacional de Tráfico de Armas](https://www.pmddtc.state.gov/?id=ddtc_public_portal_itar_landing) (ITAR por su nombre en inglés), que regula la manufactura, venta, distribución y exportación de artículos y servicios relacionados con la defensa en Estados Unidos.
- [Regulaciones de Administración de Exportación](https://www.bis.doc.gov/index.cp/regulations/export-administration-regulations-ear) (EAR por su nombre en inglés), que regula la manufactura, venta, distribución y exportación de artículos comerciales y de doble uso, tecnología e información no cubiertos por ITAR.

**Ejemplo: Estándar de Protección del Sistema Espacial de la NASA**

NASA STD 1006.1 [Estándar de Protección del Sistema Espacial](https://standards.nasa.gov/standard/NASA/NASA-STD-1006), el cual establece los requisitos de protección para asegurar que las misiones de la NASA sean resistentes a amenazas intencionales.

### Consideraciones sobre información controlada

Leyes y regulaciones relevantes que pueden evitar la publicación de datos incluyen, pero no están limitadas a:

- [Ley de portabilidad y responsabilidad del seguro médico](https://www.hhs.gov/hipaa/index.html) (HIPAA por su nombre en inglés), que establece estándares para proteger a la información sensible de pacientes de la divulgación.
- [Información no clasificada controlada](https://www.archives.gov/cui) proporciona estándares para manejar información no clasificada que requiere salvaguardas o controles de divulgación acorde con leyes, regulaciones federales y políticas.
- Leyes y reglamentos federales que rigen la [información clasificada](https://www.archives.gov/isoo/faqs) o requisitos de seguridad.

### Consideraciones de propiedad intelectual

Los datos pueden estar sujetos a propiedad intelectual, derechos de autoría y licencias. Algunas de las regulaciones y políticas relevantes incluyen leyes de propiedad intelectual o patentes, incluyendo la [Ley Bayh-Dole](https://www.govinfo.gov/content/pkg/USCODE-2011-title35/html/USCODE-2011-title35-partII-chap18.htm), que permite a las universidades, instituciones de investigación sin fines de lucro y pequeñas empresas poseer, patentar y comercializar invenciones desarrolladas bajo programas de investigación con fondos federales.

**Ejemplo: Suplemento FAR de la NASA 1852.227**

[Suplemento FAR 1852.227](https://prod.nais.nasa.gov/far/far0595-nfs012617/5227.htm), que describe los derechos de patentes y datos de los contratos gubernamentales.

---

Muchas instituciones de investigación tienen personas residentes expertas en propiedad intelectual, derechos de autoría y derecho de patentes. Pueden ser un gran recurso si tienes alguna pregunta o preocupación.

## Dónde Compartir Datos

Los datos pueden compartirse en una enorme variedad de lugares. Si bien es común compartir datos a través de correos electrónicos o sitios web, estos no son medios recomendados ya que no cumplen con los requisitos de que sean fáciles de encontrar o archivados a largo plazo. Compartir datos como parte del material complementario de una publicación revisada por pares, especialmente para conjuntos pequeños de datos, es aceptable en algunos campos. Un repositorio a largo plazo que proporcione un identificador permanente es la mejor opción para compartir datos.

### Seleccionar un repositorio de datos

Si aún no tienes un repositorio de datos en mente, ten en cuenta lo siguiente para acotar tus opciones:

- ¿Quien te financia requiere un repositorio de datos específico?
- ¿Tu organización o institución recomienda un repositorio de datos específico?
- ¿Existe un repositorio de dominio específico que sea ampliamente usado en tu área de investigación?
- ¿El repositorio provee Acceso Abierto a los datos?
- ¿Crees que las herramientas que ofrece el repositorio para descubrimiento y distribución de datos son apropiadas para tus datos y los principios FAIR?
- ¿El repositorio requiere financiamiento de tu proyecto, se ajusta con tu presupuesto y requiere soporte constante más allá del ciclo de vida del proyecto?

Encuentra y compara los servicios, beneficios y limitaciones de los repositorios que estás considerando. Cada repositorio tendrá sus propios procesos y requerimientos para aceptar y albergar tus datos de acuerdo al nivel de financiamiento, propósito y base de personas usuarias.

De la misma manera, cada repositorio proporcionará un conjunto diferente de funcionalidades y servicios de acuerdo a su nivel de financiamiento, propósito y base de personas usuarias.

Los datos sensibles pueden tener procesos adicionales de anonimización o aceptación, o restricciones sobre quién puede acceder a los datos.

La Casa Blanca presenta una buena descripción general de las características deseables [aquí](https://www.whitehouse.gov/wp-content/uploads/2022/05/05-2022-Desirable-Characteristics-of-Data-Repositories.pdf) (en inglés).

### Garantizar la accesibilidad

Los buenos repositorios compartirán (u ofrecerán) los Datos Abiertos a través de protocolos estándar, como HTTPS o SFTP. Las formas más habituales de hacerlo son:

- Permitir a las personas usuarias la posibilidad de ver una lista de archivos en los que pueden hacer clic y descargar a través de una interfaz intuitiva.
- Crear una Interfaz de Programación de Aplicaciones (en inglés, _Application Programming Interface, API_) documentada para que quienes usan la herramienta generen una lista de enlaces de archivos que cumplan con los criterios de búsqueda y que se puedan descargar de forma automatizada (es decir, acceso a datos de máquina a máquina).

Adicionalmente, los repositorios pueden requerir autorización y autentificación (por ejemplo, iniciar sesión con nombre de usuario/contraseñas) para acceder a los datos. Si bien esto está permitido según los principios FAIR (Fácil de encontrar, Accesible, Interoperable y Reusable), puede violar los principios de la Ciencia Abierta si no todas las personas pueden registrarse.

### Trabajar con un repositorio

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO ☑</th>
        <th>MANTENER DATOS EN EL REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Los requisitos del repositorio pueden variar ampliamente. Revisa siempre los requisitos del repositorio para ver qué acciones necesitas llevar a cabo una vez que consideres empezar a trabajar con ellos. También ten en cuenta que algunos repositorios cuentan con personal que ayuda con el proceso de compartir datos, mientras que otros dependen de que sepas cómo compartir tus propios datos.</p>
            <p>Si usas un repositorio que tiene personal para ayudarte con el proceso, podrían solicitar revisar y comentar tu Plan de Gestión de Datos.</p>
            <p>El repositorio puede solicitar que realices algunas pruebas de tu muestra de datos para evaluar:</p>
            <ul>
            <li>Que el formato de datos que pretendes usar sea compatible.</li>
            <li>Que las variables del conjunto de datos estén nombradas como se espera.</li>
            <li>Que el vocabulario de metadatos sea correcto.</li>
            <li>Que se cumplan los requisitos específicos del repositorio.</li>
            </ul>
            <p>Esta serie de comprobaciones permite identificar errores tempranamente y dar como resultado un envío final de tus datos al repositorio sin inconvenientes.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>COMENZAR A TRABAJAR CON UN REPOSITORIO ☑</th>
        <th>MANTENER DATOS EN EL REPOSITORIO ☑</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>A medida que avanzas en el ciclo de vida de tu proyecto, usa los procesos de actualización, revisión y reenvío de tu repositorio para mantener actualizados los productos de datos archivados. Cualquier nueva versión de los datos que desees compartir a través del repositorio tendrá que pasar por un proceso similar al del conjunto de datos inicial.</p>
            <p>Todas las nuevas versiones del conjunto de datos que quieras compartir a través del repositorio deben someterse al mismo proceso de revisión del PGD, verificación de cumplimiento y procedimiento de carga que el conjunto de datos inicial.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
         <th>COMENZAR A TRABAJAR CON UN REPOSITORIO ☑</th>
        <th>MANTENER DATOS EN EL REPOSITORIO</th>
        <th>ARCHIVAR DATOS EN EL REPOSITORIO ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Cuando tu proyecto finalice, asegúrate de haber actualizado y subido cualquier documentación complementaria (discutida en la lección anterior "Hacer Datos Abiertos") con tu versión final (incluso si sólo se hizo una versión única de los datos).</p>
            <p>Asegúrate que el repositorio mantendrá tus datos (o al menos tus metadatos) en línea durante un período de tiempo razonable luego de que tu proyecto termine.</p>
            <p>Si se encuentra algún problema con los datos después de la finalización de tu proyecto, asegúrate de que el repositorio aceptará revisiones de la base de datos si son necesarias.</p>
        </td>
    </tr>
  </tbody>
</table>

## Cómo habilitar el reúso de datos

### Obtener un DOI

Por lo general, las personas no pueden solicitar un identificador de objeto digital (DOI, por sus siglas en inglés) por sí mismas, sino que deben acudir a una organización autorizada que pueda enviar la solicitud, como por ejemplo:

- El repositorio de datos
- Tu organización
- Quien realiza la edición (si el conjunto de datos es parte de una publicación)

Las personas responsables de los datos deberán facilitar información resumida para la página de inicio de DOI, si es necesario. Quiénes comparten datos deben tener en cuenta las sugerencias de quienes se responsabilizan por los datos, cumplir las reglas de DOI y así crear las páginas de destino. Si es posible, debes reservar un DOI antes de generar tus datos.

### Garantizar la facilidad de búsqueda

Los repositorios se encargan de compartir, distribuir y conservar los datos. Algunos servicios adicionales que pueden ofrecer incluyen:

- La asignación de un identificador persistente (como un DOI) a tu conjunto de datos.
- La indexación y/o registro de tus datos y metadatos en diversos servicios para que se puedan buscar y encontrar en línea (es decir, a través de motores de búsqueda).
- La provisión de retroalimentación a quienes crearon los datos para ayudarles a optimizar sus metadatos y facilitar su búsqueda.
- La coordinación con las personas responsables de datos para garantizar que los metadatos hagan referencia al DOI.
- Asegurarse que el DOI está asociado a un sitio o página con información sobre sus datos.

### Facilitar la cita de tus datos

El objetivo es facilitar la citación de tus datos. Las mejores prácticas incluyen:

- Incluir una referencia de cita que contenga tu DOI.
- Diferentes repositorios y revistas tienen diferentes estándares sobre cómo citar datos. Si tu repositorio lo permite, incluye un archivo .CFF con tus datos explicando cómo citarlos.
- Identificar claramente a las personas responsables de los datos y/o a su institución en la cita. Esto permite a quienes acceden a los datos ponerse en contacto con éstas si tienen preguntas o descubren problemas.
  - Incluir el ORCID de cada autor de los datos cuando sea posible en la cita.

Ahora que tus datos están en un repositorio y tienen una referencia de cita y un DOI, publícalo entre las personas usuarias y recuérdales que citen tus datos en sus trabajos.

## ¿Quién es responsable de compartir datos?

Compartir datos abiertamente es un esfuerzo en equipo. Una parte importante de la planificación de los Datos Abiertos es planear y acordar las funciones y responsabilidades de quien garantizará la implementación del plan.

Entonces, ¿Qué hay que hacer? ¡Documentar estos roles y responsabilidades en tu Plan de Gestión de Datos ayudará al equipo a a mantenerse organizado y hacer ciencia más rápido! Un plan detallado y bien redactado debiera incluir:

### ¿Quién se encargará de almacenar los datos en un repositorio?

Una vez que estés en condiciones de enviar tus datos al repositorio, busca las recomendaciones del mismo para cargar los datos. Determina quién trabajará con el repositorio para llevar a cabo los siguientes tipos de actividades:

- Proporcionar información sobre el volumen de datos, número de archivos y naturaleza (por ejemplo, archivos revisados).
- Verificar que el nombre del archivo siga buenas prácticas.
- ¿Cómo se moverán los datos? (especialmente cuando los archivos son grandes)
- ¡Comprobar los datos! Verificar la integridad de los datos, metadatos y transferencia de documentación.

### ¿Quién desarrollará la documentación de los datos y los metadatos?

Determina quién trabajará con el repositorio, haz un inventario de los datos transferidos, los metadatos y la documentación. Esta función podría incluir la tarea de completar los metadatos requeridos en las bases de datos para que los archivos sean fáciles de encontrar.

Es posible que algunas de estas tareas se puedan realizar a través de la interfaz del repositorio. Sin embargo, algunos tipos de repositorios pueden requerir que se interactúe con sus equipos de administración. Para este rol, el equipo debe determinar quién:

- Proporcionará sugerencias para organizar el contenido de datos y logística.
- Desarrollará los metadatos.
- Desarrollará la documentación (por ejemplo, el archivo README (LEEME) o el reporte)
- Extraerá metadatos de los archivos de datos, archivos de metadatos (si corresponde) y documentación para completar la base de datos de metadatos, y solicitará metadatos adicionales según sea necesario.

### ¿Quién ayudará con el reúso de los datos?

Una vez que el repositorio haya puesto tus datos a disposición, alguien de tu equipo debe probar el acceso a los datos (su accesibilidad) y los métodos de distribución (su disponibilidad). Si es posible, se debe identificar quién trabajará con el repositorio para optimizar o modificar herramientas para un acceso humano intuitivo y estandarizar el acceso de máquinas. Este rol requiere alguien que:

- Comunique claramente los protocolos abiertos necesarios para los datos y metadatos.
- Proporcione casos de uso de datos reales a quien edita los datos, para que pueda optimizar y/o modificar herramientas de distribución de datos basadas en los metadatos disponibles.
- Comprenda los protocolos de acceso y evalúe las implicaciones para las comunidades objetivo y las personas usuarias en general, en términos de accesibilidad.

### ¿Quién desarrollará una guía sobre privacidad y sensibilidad cultural de los datos?

La publicación de los datos debe ser respetuosa con las comunidades que puedan estar involucradas. Esto significa pensar en temas de privacidad y sensibilidades culturales. Alguna persona del equipo se encargará de identificar y desarrollar orientación sobre:

- Cuestiones de privacidad y procesos de aprobación para la publicación: ¿los datos están adecuadamente anonimizados?
- Cómo interactuar con las comunidades de referencia.
- Cómo se pueden interpretar correctamente los datos.
- ¿Existe alguna restricción de datos que pueda ser necesaria para garantizar que la publicación de los datos sea respetuosa con la comunidad a la que se refieren o pertenecen? Por ejemplo, derechos colectivos e individuales para el consentimiento libre, previo e informado de recopilación y uso de dichos datos; incluida la elaboración de políticas y protocolos para la recolección de datos.

## Lección 4: Resumen

Conclusiones principales de esta lección:

- ¿Cuándo se pueden compartir los datos? Determinar en qué punto de un proyecto tiene más sentido compartir nuestros datos. Recordar que no todos los datos pueden o deben compartirse.
- ¿Dónde compartir los datos? Se recomienda compartirlos en un repositorio de datos público, hay muchos tipos de repositorios para elegir.
- ¿Cómo permitir el reúso de los datos? Asegúrate de que los metadatos sean apropiados y aceptados por la comunidad, asigna un DOI y elabora una referencia de citación para garantizar que se pueda encontrar y citar fácilmente.
- ¿Quién ayuda a compartir los datos? Hay muchos pasos en la creación y publicación de datos, es importante pensar en quién será responsable de cada paso.

## Lección 4: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

_Pregunta_

**01/04**

Los datos no se pueden compartir si son:

- Controlados por ITAR (Regulación Internacional de Tráfico de Armas).
- Información no clasificada controlada.
- Sujeto a cuestiones de propiedad intelectual, derechos de autoría y licencias.
- Todas las anteriores.

_Pregunta_

**02/04**

Selecciona la opción que consideras correcta para completar la oración.

Es una buena práctica empezar a trabajar con un repositorio _____.

- Lo más pronto posible
- Cuando se tienen datos de prueba listos
- Después de obtener un DOI
- Cuando estés listo para publicar tus datos

_Pregunta_

**03/04**

¿Cuál de las siguientes opciones puede ayudarte a obtener un DOI para tus datos?

- El repositorio con el que estás trabajando.
- Tu organización de origen.
- Una revista a la que enviaste un manuscrito y los datos.
- Todas las anteriores.

_Pregunta_

**04/04**

¿Cuáles de los siguientes son roles a considerar al compartir datos? Selecciona todas opciones que correspondan.

- Desarrollar una guía sobre la privacidad y sensibilidad cultural de los datos.
- Desarrollar la documentación de datos y los metadatos.
- Asignar un DOI a los datos.
- Verificar la integridad de los datos, metadatos y gestión de la documentación.
