# Lección 3: Crear Código Abierto

## Contenidos

- [¿Cómo planificar para crear código?](#c%C3%B3mo-planificar-para-crear-c%C3%B3digo)
- [Importancia del control de versiones](#importancia-del-control-de-versiones)
- [Describir nuestro código para otras personas](#describir-nuestro-c%C3%B3digo-para-otras-personas)
- [¿Qué licencia deberíamos elegir para nuestro código?](#qu%C3%A9-licencia-deber%C3%ADamos-elegir-para-nuestro-c%C3%B3digo)
- [Buenas prácticas de programación](#buenas-pr%C3%A1cticas-de-programaci%C3%B3n)
- [Lección 3: Resumen](#lecci%C3%B3n-3-resumen)
- [Lección 3: Evaluación](#lecci%C3%B3n-3-evaluaci%C3%B3n)

## Descripción general

En esta lección aprenderás sobre los pasos prácticos para hacer que el código esté accesible de forma abierta. Los software bien establecidos y de gran volumen tienen necesidades diferentes a las de un proyecto incipiente. Por ejemplo, un programa escrito para crear un gráfico simple tiene requisitos diferentes a los de un paquete de software que modela el clima de la Tierra. El tamaño del equipo de investigación también puede determinar los pasos necesarios para que el código sea de acceso abierto. Esta lección cubre: el proceso para hacer que el código sea utilizable para otras personas que investigan mediante la documentación, consideraciones sobre licencias, y buenas prácticas en el desarrollo de software.

## Objetivos de aprendizaje

Al completar la lección, deberías ser capaz de:

- Describir las consideraciones clave al planificar un nuevo proyecto de software abierto.
- Enumerar tres razones por las que los proyectos deberían usar control de versiones.
- Explicar el propósito y recordar información general típicamente incluida en un archivo LEEME.
- Ser capaz de seleccionar una licencia para tu código y listar las diferencias entre licencias de software de Código Abierto permisivas y protectoras.
- Explicar las buenas prácticas en el desarrollo de software que apoyan la transparencia, la inclusión y la reproducibilidad.

## ¿Cómo planificar para crear código?

El código se escribe para resolver un desafío. Esto puede abarcar desde la producción de un gráfico, hasta procesar datos de observaciones de la Tierra, o incluso modelar el Universo. Los desafíos asociados con la escritura de código pueden variar en dificultad, desde tareas más simples como el uso de hojas de cálculo hasta actividades más complejas como la creación de extensas bibliotecas y el uso de computación de alto rendimiento o en la nube. El código puede ser desarrollado de manera individual, en equipo o en comunidad. Una vez escrito, el código puede ser usado durante décadas o nunca más.

Al iniciar un proyecto de investigación, es útil responder a las siguientes preguntas:

1. ¿Qué problema estoy tratando de resolver?, ¿alguien más en mi comunidad también lo enfrenta?
2. ¿Existen soluciones? (En la Lección 2, exploramos cómo buscar soluciones existentes).
3. ¿Encontraste código que estaba cerca de lo que deseabas pero no cumplía completamente con tus necesidades?

Podrías contribuir potencialmente, en lugar de escribir algo nuevo.

Incluso si ya existe una solución, podría haber buenas razones para desarrollar tu propio código. En situaciones como:

- El código está escrito en un lenguaje de programación diferente al que estás familiarizado.
- La licencia no es lo suficientemente abierta como para adoptarla.
- Probar nuevas técnicas o desarrollar una comprensión más profunda del problema.

<img src="../images/media/image333_es.jpg" style="width:350px;height:auto;" />

Puede llevar más tiempo iniciar un nuevo proyecto, o puede tardarse más intentando integrar el código de otra persona que escribiendo el propio. Tendrás que tomar esa decisión.

Buscamos código existente, y aunque encontramos algunas cosas que eran similares, al final decidimos que nuestras necesidades eran lo suficientemente únicas - ¡estamos comenzando un nuevo proyecto!

### Comenzar un nuevo proyecto

Al iniciar un nuevo proyecto, los aspectos clave a considerar son:

1. Definir el alcance del proyecto, sus características principales y cualquier limitación, así como el público objetivo.
2. Considerar los recursos necesarios para que el software funcione. ¿Se ejecutará en una computadora personal, en un servidor informático de alto rendimiento o en la nube?
3. ¿Cómo se gestionará?

Esta lección se centra predominantemente en la cuestión de cómo gestionar el código de acceso abierto.

¿Quién trabajará en el proyecto? ¿Cuáles son algunas de las mejores prácticas para el desarrollo? ¿Cómo se compartirá abiertamente? ¿Qué tipo de licencia se aplicará?

### Organizar un proyecto

<img src="../images/media/image353_es.png" style="width:250px;height:auto;" />

Fuente: https://xkcd.com/1459/

---

Los proyectos de software pueden organizarse de distintas maneras, cada una con consideraciones únicas sobre cómo comenzar. Muchos proyectos comienzan como un único script destinado a un solo uso. Sin embargo, un script puede convertirse en un proyecto mucho más grande, con aplicaciones imprevistas tanto en el campo de investigación original como en otros nuevos. Otros proyectos pueden comenzar con requisitos y estándares formales.

Hacer público el código tiene muchas ventajas:

- Permite la colaboración abierta.
- Invita a la retroalimentación constructiva que contribuya con la precisión y robustez del código.
- Personas con menos experiencia en el tema aprenderán más.
- Quienes tienen menos experiencia en programación pueden aprender de quienes poseen más experiencia a medida que mejoran el código.
- Proporciona un producto intermedio que puede ser citado.

Al nombrar un proyecto, realiza una búsqueda rápida del nombre previsto para ver qué aparece. Evita nombres con muchos otros usos, ya que esto dificultará que otros descubran el código. Además, no elijas nombres embarazosos o registrados.

Al alojar el producto en una plataforma con control de versiones, aseguras la perdurabilidad de tu proyecto. Si el código solo existe en tu computadora, puede desaparecer si ésta se daña o se pierde.

Documentar la producción y gestión de tu código te beneficia tanto a ti como a quienes podrían usar tu código en el futuro. Tú eres tu mejor colaborador. La documentación puede evitarte dolores de cabeza si reúsas el código en seis meses o intentas recordar detalles meticulosos sobre tu proceso más adelante.

Preguntas a considerar al elegir un lenguaje de programación:

- ¿Podrán los colaboradores potenciales contribuir en el lenguaje elegido?
- ¿Con qué lenguajes tienes más experiencia?
- ¿Existe alguna limitación en tu entorno informático que pueda afectar tu capacidad para escribir o gestionar este código?
- Los lenguajes tienen fortalezas y debilidades, ¿Cuáles son más importantes para tu proyecto?

Antes de que alguien más pueda usar tu código, seguramente hará algunas preguntas:

- ¿Dónde puedo encontrar tu código?
- ¿Está documentado tu código?
- ¿De qué maneras puedo usar tu código?
- ¿Aceptarás cambios en tu código? Si encuentro un error, ¿Qué debo hacer?
- ¿Cómo puedo confiar en que tu código funcione?
- ¿Cómo sé si el código tendrá soporte a largo plazo?

## Importancia del control de versiones

Tu código cambiará significativamente a lo largo de la vida de tu proyecto. Del mismo modo que apreciamos la capacidad de rastrear versiones anteriores de documentos o versiones creadas por diferentes personas, inevitablemente alguien querrá ser capaz de revertir, comparar y sintetizar cambios en el código.

La herramienta más popular de control de versiones es Git. Git es un sistema que rastrea los cambios en los archivos del equipo, similar a Google Docs o SharePoint, pero más aplicable a código. Git se usa generalmente junto con una plataforma de control de versiones como GitHub, Gitlab, o Bitbucket. Estas herramientas fueron cubiertas en el Módulo 2.2.

El control de versiones permite lo siguiente:

- Ayuda a los desarrolladores a realizar un seguimiento de los cambios en el código de un proyecto (además de archivos suplementarios y documentación) durante todo el curso de la evolución del proyecto.
- Las revisiones a los archivos de un proyecto pueden ser rastreadas, incluyendo las contribuciones realizadas por diferentes personas.
- Los cambios no deseados (como equivocaciones o errores de programación) pueden ser revertidos en cualquier momento.

El control de versiones es una buena práctica para programar, incluso si no se comparte el código inmediatamente. El mismo puede ser usado en un código personal de forma privada en su computadora, o alternativamente se puede usar el modo privado en los servicios de alojamiento (por ejemplo, GitHub y GitLab). Al configurar el control de versiones pronto, se prepara el código para un uso futuro esperado e inolvidable.

**Recursos adicionales en el control de versión**

- [Control de versión de carpintería de software con Git](https://swcarpentry.github.io/git-novice/)
- [The Turing Way, Versión Control](https://the-turing-way.netlify.app/reproducible-research/vcs.html)
- [Usar un repositorio accesible públicamente con control de versiones: guía para el software FAIR](https://f.Usoftware.eu/recommendations/repository/)

## Describir nuestro código para otras personas

### Archivo LEEME

La primera parada para un usuario cuando se acerque a un nuevo proyecto debería ser el archivo LEEME. Acertadamente llamado así, este archivo contiene información orientativa que ayudará al usuario a comprender el propósito de un proyecto, ofrece ejemplos de cómo puede usarse y enumera otra información importante que el creador considere pertinente.

Como mínimo, un archivo LEEME debería contener el nombre del proyecto y un párrafo muy corto de lo que es el software. Dos o tres frases en un estilo sencillo que no presuponga quién lo lee. Es el discurso de ascenso para el proyecto.

|                                         |                                                                                                                                                                                                                                                                                                                |
| --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Incorrecto** Ejemplo de archivo LEEME | "Este código recalcula el factor de permutación fundamental del flujo descendente (para J < 10, obviamente)."                                                                                                                                                               |
| **Correcto** Ejemplo de archivo LEEME   | "LeapKitten. Este paquete de Python toma cualquier foto de un gatito (JPEG, PNG) y usa inteligencia artificial para mostrar cómo se vería saltando en el aire. Además, el código tiene en cuenta los años bisiestos en la marca de tiempo de la imagen" |

Además, la siguiente información es útil para añadir al archivo LEEME especialmente si no están listados en otro lugar:

- Una lista de las dependencias de código que tiene el software, por ejemplo, "Numpy, kitten-rng y human- readable deben estar instalados para ejecutar este software"
- Cómo instalar y una breve descripción de cómo ejecutar el software.
- Descripción detallada del software, especialmente si no hay documentación externa.
- Ejemplos de cómo usar el software.
- Reconocimiento de miembros del equipo o fuentes de apoyo.

Como se vio en estos ejemplos, los archivos LEEME pueden ser útiles para una [colección de scripts de apoyo a una publicación](https://github.com/granttremblay/Tremblay2018_Code) o un [paquete de software ampliamente desarrollado](https://github.com/MillionConcepts/lhorizon).

### Pautas para los colaboradores

El archivo _CONTRIBUYENDO.md_ proporciona información sobre cómo contribuir al proyecto. En él se explica cómo funciona el proceso de contribución y qué tipo de contribuciones son necesarias. Si bien no todos los proyectos tienen un archivo _CONTRIBUTING.md_, la existencia de uno es un claro indicador de que las contribuciones son bienvenidas.

Será necesario decidir personalmente cuando tu proyecto ha progresado lo suficiente como para invitar contribuidores. Cuando lo haya hecho, un documento llamado CONTRIBUYENDO deberá ser creado en el nivel superior del informe.

Las [pautas de contribución de Astropy](https://github.com/astropy/astropy/blob/main/CONTRIBUTING.md) y las [pautas de contribución numérica](https://numpy.org/devdocs/dev/index.html) proporcionan dos ejemplos.

**Consejo extra: Aunque desarrolles tu código públicamente, esto no significa que tengas que aceptar contribuciones de otros o mantener tu código para siempre. Las pautas de contribución o el archivo LEEME son buenos lugares para indicar cuáles son las expectativas para el código. El mismo puede aclarar que el código no está siendo mantenido o que no acepta contribuciones.**

### Código de conducta

El código de conducta establece normas básicas para el comportamiento de los participantes y ayuda a facilitar un ambiente agradable y acogedor. Si bien no todos los proyectos tienen un archivo CODIGO_DE_CONDUCTA, su presencia indica que este es un proyecto agradable al que contribuir.

### Documentación de código

**Documentación sobre el código para el desarrollador**

Su software debe estar documentado dentro del código fuente. Cada función debe tener comentarios al principio que brevemente expliquen, en lenguaje sencillo, para qué sirve la función. Esto no es sólo para otros desarrolladores, sino para el desarrollador original que una semana más tarde, puede olvidar que escribió.

> **Ejemplo**
>
> \# Esta función toma la matriz de imagen y la recorta desde el centro al 50% del tamaño original.
>
> Sin entrar en detalles sobre el tipo de datos, los parámetros de llamada, etc., esta descripción sitúa inmediatamente a la persona que mira el código en el contexto de lo que la función pretende conseguir; entonces puede explorar los detalles.
>
> Si bien se debería considerar colocar una descripción al comienzo de una función, hay que usar la discreción sobre dónde poner descripciones de código similares. Al comienzo de un ciclo o análisis complejo serían buenas ideas. No te olvides - cosas como esta no son útiles:
>
> \# fijar x a 17
>
> x = 17
>
> Los nombres de variables, clases y funciones descriptivos pueden hacer que tu código sea legible. . A veces, incluso los grandes programadores trabajan rápido y nombran las variables 'a', 'temp', u otros nombres que probablemente no tendrán mucho sentido en una semana o dos cuando vuelvan a algo en lo que estaban trabajando. Nombres como 'tiempo_de_coccion' o 'velocidad' son más claros. Los nombres variables deberían ser fáciles de entender y representar claramente lo que son.
>
> Lo ideal es que alguien que no escriba en el lenguaje del código pueda leer los comentarios del archivo y hacerse una idea aproximada de lo que ocurre.
>
> Usa los comentarios para poner URLs que hagan referencia a dónde se encontró el algoritmo usado (por ejemplo, Stack Overflow) o el artículo de revista donde se encuentran la fórmula que se implementa.

### Documentación sobre el código para el usuario

Si estás desarrollando código que esperas que otras personas usen, escribe un manual sobre cómo usar el código. Como el código se desarrolla constantemente, es mucho más fácil documentarlo mientras o incluso antes de escribir cualquier código.

Si escribes la documentación dentro del propio código, hay software que pueden extraerla, formatearla y presentarla como un manual pulido. Ejemplos de documentación generada a partir del código se pueden ver para [Astropy](https://docs.astropy.org/en/latest/) o [NumPy](https://numpy.org/doc/stable/).

Se ven maravillosos, pero también muy similares. Estos sitios fueron generados por completo a partir de comentarios y documentos escritos en el código fuente. A diferencia de los comentarios escritos para las personas desarrolladoras del código, éstos comentarios fueron redactados específicamente para la audiencia de usuarios externos del código: el manual.

Aunque hay varios paquetes de software para la generación automática de documentación, los más usados son [Sphinx](https://www.sphinx-doc. rg/es/master/) para Python y [Doxygen](https://www.doxygen.nl/index.html) para casi todo lo demás. [M](https://www.markdownguide.org/)[arkdown](https://www.markdownguide.org/) también es una opción popular para el lenguaje de formato para la documentación.

### Programación y documentación

**Establecer un Entorno de Desarrollo** - Establecer un entorno de desarrollo apropiado te ayudará a escribir un código bueno, limpio y te ayudará a mantener el proyecto a medida que evoluciona.

- Configura cualquier herramienta necesaria para escribir el código. Tal vez un EDI (Entorno de Desarrollo Integrado) o editor de texto. Algunos ejemplos populares incluyen el código VS, Pycharm, R Studio, Xcode.
- Configura un gestor de paquetes. Por ejemplo, para Python, se podría usar 'anaconda' o 'poetry'.
- Crea un entorno virtual específico de tu proyecto para aislar sus dependencias (y sus versiones) de las usadas para otros proyectos

**Estructuración de archivos y carpetas** - La forma en que estructuras los archivos de tu proyecto, desde el principio, contribuirá al éxito de los resultados finales.

Los distintos lenguajes de programación tienen diferentes estructuras de carpetas estándar. Familiarízate con los estándares antes de comenzar, ya que esto ayudará a otras personas a colaborar y, probablemente, te evitará dificultades más adelante.

Hay una variedad de estructuras de código de ejemplo que se pueden usar para empezar. Por ejemplo, para Python, hay Cookiecutter y una plantilla de paquete Astropy.

## ¿Qué licencia deberíamos elegir para nuestro código?

### Consideraciones de Licencia cuando se usa Software Abierto

<img src="../images/media/image130_es.png" style="width:350px;height:auto;" />

Las licencias de software de Código Abierto son fundamentales para cómo los científicos usan, crean y comparten código y software. Entender algunos de los matices de estas licencias es importante porque afectará el modo en que tu proyecto puede licenciar y compartir código.

Una licencia de software es un documento legal que establece los derechos de las personas que desarrollan y usan una pieza de software.

Una licencia de Código Abierto es un tipo de licencia de software, aprobada por la Iniciativa de Código Abierto (en inglés, _Open Source Initiative, OSI_), conforme a la Definición de Código Abierto. Una licencia de Código Abierto otorga permisos a cualquier persona para inspeccionar, usar, modificar y distribuir el código fuente del software para cualquier propósito.

Las licencias aseguran que las personas que desarrollan el software reciban crédito y control sobre cómo se usa su trabajo. Sin licencia, se asume que el software tiene derechos de autoría y sin permisos. Las personas que programan incluyen licencias para permitir su reuso.

Las licencias toman varias formas para describir:

- Obligaciones contractuales (si existen) entre las personas que desarrollan y las que usan.
- Lo que las personas usuarias del software pueden hacer con él.
- A quiénes pueden, las personas usuarias del software, distribuirlo (si existe tal derecho).
- Periodo de tiempo durante el cual la persona usuaria tiene derecho a usar el software.

### Algunos Tipos Comunes de Licencia de Software

_Haz clic en '+' para ver más información._

<img style="width:100%;height:auto;" src="../images/media/commonsoftwarelicenses_es.png">

**Dominio Público**

Cualquier persona puede usarlo libremente.

**"Licencia Pública General Reducida**

Puede vincularse a bibliotecas de Código Abierto, y el código puede ser licenciado bajo cualquier tipo de licencia.

**Permisivo**

Ofrece a las personas usuarias del software una libertad amplia, pero no completa, para reusar o volver a otorgar licencias.

**No permisiva**

Permite a las personas usuarias reusar, pero también otorga la responsabilidad de compartir sus cambios con la comunidad.

Copyleft

Puede ser distribuido o modificado si todo el código involucrado está bajo la misma licencia.

**Propietario**

No se puede copiar, modificar ni distribuir.

---

Antes de elegir una licencia, consulta primero con tu organización o quien te emplea. Pueden tener pautas específicas acerca de qué licencia de software es la que puedes usar. Tu subsidio de investigación también puede estipular los tipos de licencia permitidos. El plan de gestión de software debe especificar qué licencia planeas usar.

Si una licencia no es compartida con un código, se asume por defecto que está protegido por derechos de autoría en los Estados Unidos (https://www.copyright.gov/help/faq/faq-general.html). No necesita ser registrado, y se asume que está automáticamente protegido por derechos de autoría en el momento en que se crea.

Para el software, la licencia se comparte en un archivo llamado LICENCIA en la parte superior del repositorio. Es una ubicación estándar que la gente sabrá que hay que mirar. No es mala práctica poner también una línea con la versión de la licencia en la parte superior de cada archivo de código, con un puntero hacia donde se podría encontrar la licencia completa.

### Tipos de licencias de software de Código Abierto

Hay dos tipos principales de licencias de Código Abierto. Permisiva y protectora (a veces denominada copy-left). La diferencia entre estos tipos de licencias está relacionada principalmente con el tipo de licencia que las personas usuarias del código pueden aplicar a sus obras derivadas.

<table>
  <thead>
    <tr>
        <th>LICENCIA PERMISIVA ☑</th>
        <th>LICENCIA PROTECTORA</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>La Iniciativa de Código Abierto define una licencia de software permisiva como aquella que garantiza las libertades de uso, modificación, redistribución y creación de obras derivadas. Un ejemplo de este tipo de licencia es la licencia Apache 2.0 de la Fundación de Software Apache (en inglés, _Apache Software Foundation_). Es la licencia permisiva más popular y ampliamente usada.</p>
            <p>Las personas usuarias tienen una amplia libertad de reúso bajo esta licencia. Generalmente son libres de incorporar el código en su proyecto o de usarlo como deseen. Las personas que usan un Código Abierto con licencia permisiva en un producto podrían volver a implementar el software de Código Abierto con una amplia gama de licencias, incluyendo el software patentado de código cerrado.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>LICENCIA PERMISIVA</th>
        <th>LICENCIA PROTECTORA ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Las licencias protectoras (copyleft) son una técnica legal para conceder ciertas libertades sobre copias de obras protegidas por derechos de autoría con el requisito de que se preserven los mismos derechos en las obras derivadas. Esto permite a los usuarios reusar, pero también requiere que compartan sus cambios con la comunidad usando la misma licencia. Un ejemplo de licencia protectora es la Licencia Pública General (en inglés, GPL) que garantiza que los usuarios tengan la libertad y responsabilidad de compartir sus cambios con la comunidad. Es la licencia de protección más usada. Estos tipos de licencias pueden dar como resultado un menor reuso por parte de los usuarios que prefieren o se les exige que usen únicamente licencias permisivas.</p>
        </td>
    </tr>
  </tbody>
</table>

### Licencias Comunes para Software Abierto

Algunas de las licencias más populares usadas en software abierto son:

<table>
  <thead>
    <tr>
        <th>PERMISIVA (PUEDE APLICAR CUALQUIER LICENCIA A OBRAS DERIVADAS) ☑</th>
        <th>PROTEGIDA/ COPYLEFT (TODAS LAS OBRAS DERIVADAS DEBEN DISTRIBUIR TODO SU CÓDIGO FUENTE BAJO LA MISMA LICENCIA)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li><a href="https://opensource.org/license/apache-2-0/">Licencia Apache</a></li>
              <li><a href="https://opensource.org/license/mit/">Licencia MIT</a></li>
              <li><a href="https://opensource.org/license/bsd-3-clause/">Licencia BSD</a></li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>PERMISIVA (PUEDE APLICAR CUALQUIER LICENCIA A OBRAS DERIVADAS)</th>
        <th>PROTEGIDA/ COPYLEFT (TODAS LAS OBRAS DERIVADAS DEBEN DISTRIBUIR TODO SU CÓDIGO FUENTE BAJO LA MISMA LICENCIA) ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <ul>
              <li>Liencia Pública General GNU (<a href="https://opensource.org/license/gpl-2-0/">GPL</a>)</li>
              <li><a href="https://opensource.org/license/mpl-2-0/">Licencia Pública de Mozilla</a> </li>
              <li>Licencia Común de Desarrollo y Distribución (<a href="https://opensource.org/license/cddl-1-0/">CDDL</a>)</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

Para obtener más información sobre los diferentes tipos de licencias, consulte la [Iniciativa de Código Abierto OSI](https://opensource.org/licenses/category).

### Actividad 3.1: Licencias

En esta actividad, te pediremos que respondas si las siguientes afirmaciones son verdaderas o falsas.

**Afirmación 1:**

Una licencia de software establece los derechos del desarrollador y del usuario sobre un software.

- Verdadero
- Falso

**Afirmación 2:**

Sin licencia, se supone que el software tiene derechos de autor y no tiene permisos.

- Verdadero
- Falso

**Afirmación 3:**

Cualquiera es libre de usar software con una licencia "permisiva" sin restricciones.

- Verdadero
- Falso

**Afirmación 4:**

Los usuarios no pueden copiar ni modificar ningún software con licencia copyleft.

- Verdadero
- Falso

## Buenas prácticas de programación

En esta sección, se proporcionan algunas prácticas recomendadas en desarrollo, incluidas la revisión de código, pruebas, seguridad y accesibilidad. Estas prácticas mejorarán la calidad del código, la reproducibilidad de los resultados y la seguridad de un proyecto. Las acciones mencionadas ayudan a mejorar la solidez del código de acceso abierto y ayudan a enfrentar los desafíos únicos que pueden surgir con múltiples contribuyentes y revisiones que ocurren durante un período prolongado de tiempo.

### Revisión de Código

El código se beneficia de la revisión por pares de la misma manera que la ciencia. Hacer que otra persona lea tu código y lo pruebe es una de las mejores formas de mejorar la calidad del código.

Muchas plataformas de control de versiones tienen herramientas integradas que permiten a los desarrolladores revisar, comentar e iterar el código de otros. Los controles se pueden hacer de forma abierta y permitir que cualquiera pueda comentar.

Aquí hay un gran ejemplo de la discusión que puede presentarse cuando el creador original de un algoritmo [comenta sobre una implementación de Python realizada por un colaborador primerizo del proyecto Astropy.](https://github.com/astropy/astropy/pull/4301) La discusión abierta y constructiva condujo a una mejor implementación del algoritmo junto con posibles mejoras futuras.

Los paquetes de software también se pueden revisar como productos propios. Muchas publicaciones científicas ahora aceptan artículos centrados en software. Hay entidades como [PyOpenSci](https://www.pyopensci.org/) y el [Journal of Open Source Software](https://joss.theoj.org/) que ofrecen revisión abierta por pares de paquetes científicos. Puedes ver más detalles sobre JOSS en la próxima lección sobre cómo compartir tu código.

### Pruebas

Un método probado para evaluar la reproducibilidad de tu software es mediante pruebas. Hay muchos tipos de pruebas que van desde probar las partes comprobables más pequeñas de un código hasta verificar si un código funciona en su totalidad en diferentes escenarios. Las pruebas de código pueden incluir una amplia gama de técnicas diferentes. La siguiente sección de la lección proporciona sólo una breve introducción al tema.

El principal objetivo de las pruebas de código es evaluar si un código hace lo que sus autores pretendían que hiciera. Probar el código de manera integral puede ser muy difícil, ya que implica probar el código para generar los resultados esperados y para fallar cuando debería.

<table>
  <thead>
    <tr>
        <th>VALIDACIÓN CIENTÍFICA ☑</th>
        <th>PRUEBAS DE REPRODUCIBILIDAD</th>
        <th>PRUEBAS INTEGRADAS</th>
        <th>PRUEBAS AUTOMATIZADAS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Ya sea que se produzca un guión o un proceso completo de procesamiento de datos, la validación del software es fundamental para garantizar la calidad y confiabilidad de los resultados científicos. Esto podría significar calcular manualmente los resultados para verificar el resultado del código o compararlos con resultados producidos anteriormente o hacer que otro miembro del equipo lo pruebe.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>VALIDACIÓN CIENTÍFICA</th>
        <th>PRUEBAS DE REPRODUCIBILIDAD ☑</th>
        <th>PRUEBAS INTEGRADAS</th>
        <th>PRUEBAS AUTOMATIZADAS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Dados los mismos insumos y parámetros, ¿se pueden producir los mismos resultados? Hacer que los archivos de configuración, los datos de entrada, etc. estén disponibles abiertamente para que los usuarios puedan ejecutarlos fácilmente y producir los mismos resultados publicados es una forma fundamental de aumentar la confianza en su código.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>VALIDACIÓN CIENTÍFICA</th>
        <th>PRUEBAS DE REPRODUCIBILIDAD</th>
        <th>PRUEBAS INTEGRADAS ☑</th>
        <th>PRUEBAS AUTOMATIZADAS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Las pruebas unitarias permiten a los desarrolladores de software reforzar su confianza en la capacidad de su código para funcionar según lo esperado. Las pruebas unitarias son pequeñas funciones que se encuentran fuera de la base del código y que prueban una función específica o ejecutan una prueba específica. Por ejemplo, si una función toma una imagen y la voltea horizontalmente, una prueba podría verificar que la imagen resultante tenga el mismo tamaño. Otro compara la salida usando una imagen conocida con el resultado esperado. Otro comprueba que se devuelva una nueva imagen.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>VALIDACIÓN CIENTÍFICA</th>
        <th>PRUEBAS DE REPRODUCIBILIDAD</th>
        <th>PRUEBAS INTEGRADAS</th>
        <th>PRUEBAS AUTOMÁTICAS ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Las pruebas integradas generalmente se pueden ejecutar tanto de forma manual como automática. La mayoría de las plataformas de control de versiones ofrecen servicios para ejecutar pruebas automáticamente. Cuando se ejecuta de esta manera, se puede verificar el código para ver si los cambios generan algún problema. Este proceso de verificar el código automáticamente a medida que se desarrolla se llama desarrollo continuo o integración continua (CI/CD). Si un pequeño cambio realizado en una parte del código da como resultado un cambio inesperado en otra parte, la ejecución de las pruebas lo descubrirá inmediatamente.</p>
        </td>
    </tr>
  </tbody>
</table>

### Minimizar el riesgo de vulnerabilidades de seguridad

Ya sea que se use software de código abierto, de código cerrado o comercial, es importante considerar los riesgos de seguridad inherentes al desarrollo de software.

- Asegúrate de que haya un código mínimo y DRY (no lo repita) (más fácil de mantener y reparar).
- Usa variables globales o administradores de claves para las credenciales. Nunca incluyas credenciales en tu código.
- Usa dependencias bien probadas y mantenidas. En los paquetes que mantiene, mantén actualizada la lista de dependencias.
- Crea software con herramientas que proporcionen escaneo y auditoría automatizados.
- Si hay dependencias no compatibles en las que confías, evalúalas para determinar cómo podrían introducir riesgos de seguridad y si sería apropiado cambiar a un paquete diferente.

<table>
  <thead>
    <tr>
        <th>HERRAMIENTAS Y VULNERABILIDADES DE SEGURIDAD ☑</th>
        <th>COMPONENTES DE PRUEBA Y DEPENDENCIAS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Se han desarrollado herramientas comerciales y de código abierto para abordar el desafío de identificar las vulnerabilidades de seguridad en distintos componentes de la fuente. Si no dispones de ninguna tecnología para asegurar el uso de código abierto, puedes considerar usar las herramientas de verificación de dependencias Dependabot o <a href="https://owasp.org/">OWASP</a>.</p>
            <p>El Proyecto de Seguridad de Aplicaciones Web Abiertas (Open Web Application Security Project, OWASP) es una comunidad en línea que produce herramientas y tecnologías gratuitas en el campo de la seguridad de aplicaciones web. La verificación de dependencias de OWASP es una herramienta creada por desarrolladores, que identifica las dependencias de un proyecto y verifica si contienen alguna vulnerabilidad conocida de código abierto que haya sido públicamente divulgada.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>HERRAMIENTAS Y VULNERABILIDADES DE SEGURIDAD</th>
        <th>COMPONENTES DE PRUEBA Y DEPENDENCIAS ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="2">
            <p>Probar la seguridad de los componentes de código abierto que estás usando es la mejor manera de garantizar la seguridad de tus aplicaciones y de tu organización. Tu compromiso con el análisis oportuno y frecuente de los componentes de código abierto debería ser el mismo que con tu propio código.</p>
            <p>Esto es especialmente cierto dado que el componente en cuestión puede tener vulnerabilidades de seguridad desconocidas o dependencias que difieren en cada caso de uso. Es posible que un componente sea seguro en una aplicación concreta, pero vulnerable en otra.</p>
        </td>
    </tr>
  </tbody>
</table>

### Creación de Software FAIR

<table>
  <thead>
    <tr>
        <th>FÁCIL DE ENCONTRAR☑</th>
        <th>ACCESIBLE</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>El software incluye un identificador persistente y único, así como metadatos completos, lo que facilita su ubicación tanto para humanos como para máquinas.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCIL DE ENCONTRAR</th>
        <th>ACCESIBLE ☑</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>El software se puede recuperar a partir de su identificador mediante protocolos de comunicación estándar.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCIL DE ENCONTRAR</th>
        <th>ACCESIBLE</th>
        <th>INTEROPERABLE ☑</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>El software es interoperable con otros programas; intercambia datos y/o metadatos usando estándares compartidos.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FÁCIL DE ENCONTRAR</th>
        <th>ACCESIBLE</th>
        <th>INTEROPERABLE</th>
        <th>REUSABLE ☑</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>Metadatos completamente descritos con su procedencia, cumpliendo con las normas de la comunidad. La licencia permite su reúso.</p>
        </td>
    </tr>
  </tbody>
</table>

### Consejos adicionales útiles

Aquí hay algunas sugerencias adicionales sobre cómo hacer que tu código sea más accesible, reproducible y transparente:

|                                  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Nombres descriptivos**         | Las variables, funciones y entidades similares deben recibir nombres descriptivos en lugar de nombres vagos. Los nombres descriptivos dan de inmediato a otros programadores una idea de lo que representa la variable o la función. Por ejemplo, el nombre de variable **ColorDeGato** es un buen nombre porque describe lo que pretende hacer, que es abarcar el color de gatos.                                                                                                                                                                                                                                                           |
| **Archivo de metadatos**         | Considera incluir un archivo de metadatos para tu software para facilitar su búsqueda. Puedes crear un archivo 'codemeta.json' empleando [Code Meta generator](https://codemeta.github.io/codemeta-generator/) para incluirlo con tu paquete.                                                                                                                                                                                                                                                                                                                                                                                                |
| **Documentación de Operaciones** | Comparte detalles sobre cómo estás ejecutando el código. Por ejemplo, documenta la versión de la biblioteca de software que estás usando o la versión del compilador. Suelen compartirse en un archivo 'environment.yml'.                                                                                                                                                                                                                                                                                                                                                                                                |
| **Automatización**               | Considera el siguiente escenario:<br><br>Estás a punto de publicar un artículo que incluye 17 gráficos que dependen de un conjunto de datos lanzado por una misión. Justo antes de enviarlo, la misión publica una versión actualizada del conjunto de datos.<br><br> ¿Qué tan fácil será recrear esos gráficos? <br><br> El software permite automatizar la secuencia de programas y alertar a los programadores cuando se ejecuten para que los archivos de entrada se codifiquen de forma rígida. Esto permite a los programadores volver a ejecutar fácilmente el código si cambia un parámetro inicial. |
| **Uso de normas**                | La mayoría de los lenguajes tienen su propio estilo de codificación adoptado por sus respectivas comunidades. Seguir esas convenciones facilita que otros contribuyan al código que construiste y hace que tu proyecto sea más inclusivo.                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Portabilidad**                 | Comparte detalles sobre cómo estás ejecutando el código, por ejemplo, la versión de una biblioteca de software que estás usando o la versión del compilador. Todo esto suele compartirse en un archivo 'environment.yml'.                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Nomenclatura**                 | Muchos términos históricos usados en el software tienen connotaciones negativas según el contexto. A la hora de considerar diferentes términos o denominaciones, hay que tener en cuenta cómo pueden reaccionar ante ellos los distintos públicos.                                                                                                                                                                                                                                                                                                                                                                                                       |

## Lección 3: Resumen

En esta lección has aprendido:

- La planificación de un nuevo proyecto requiere que los programadores tengan un propósito claramente definido, reconozcan cualquier limitación de recursos y prevean un plan de gestión de datos.
- El uso de un repositorio con control de versiones permite a los desarrolladores hacer un seguimiento de los cambios a lo largo del tiempo y de los múltiples colaboradores, lo que puede ayudar a solucionar errores y a gestionar un equipo de programadores.
- Un archivo LEEME debe incluir el nombre del proyecto y una descripción breve pero clara del software.
- Las licencias aseguran que las personas que desarrollan el software reciben crédito y control sobre cómo se usa su trabajo. Sin licencia, se supone que el software tiene derechos de autor y no tiene permisos
- La realización de pruebas, etiquetar y aplicar medidas de seguridad son ejemplos de buenas prácticas de programación que favorecen la Ciencia Abierta.

Además de aprender a compartir tu código en la próxima lección, también tendrás algunas oportunidades para poner esta lección en práctica.

## Lección 3: Evaluación

Responde las siguientes preguntas para poner a prueba lo que has aprendido hasta ahora.

_Pregunta_

**01/05**

¿Cuál de los siguientes aspectos debe tenerse en cuenta a la hora de planificar un proyecto de software abierto? Seleccione todas las opciones que correspondan.

- El público al que va dirigido.
- Qué protocolo se usará para sincronizar cambios entre los colaboradores individuales y el repositorio central.
- El lenguaje de programación que se usará.
- Quién se beneficiará económicamente de las ventas del software.

_Pregunta_

**02/05**

¿Cuál de las siguientes es una ventaja de usar un sistema de control de versiones en tu software?

- Los nuevos cambios son registrados automáticamente.
- Diferentes colaboradores pueden agregar o editar código al mismo tiempo.
- Los cambios no deseados pueden revertirse rápidamente.
- Todas las anteriores.

_Pregunta_

**03/05**

Selecciona de la siguiente lista dos elementos que serían buenos incluir en un archivo LEEME:

- Instrucciones de instalación/compilación
- Historial de desarrollo de código
- Las partes más importantes del código
- Instrucciones de uso y ejemplos

_Pregunta_

**04/05**

¿Cuál de las siguientes licencias permite a los usuarios reusar, pero también requiere que compartan sus cambios con la comunidad usando la misma licencia?

- Dominio Público
- Licencia Pública General Reducida
- Licencia Permisiva
- Licencia protectora
- Licencia Comercial

_Pregunta_

**05/05**

¿Cuál de las siguientes prácticas hace que tu proyecto sea más inclusivo?

- Incluir un Código de Conducta.
- Referenciar eventos históricos en el nombre de tu proyecto.
- Seguir las normas del lenguaje de programación usado.
- Desarrollar el proyecto de forma privada.
- Incluir una guía para los colaboradores.
