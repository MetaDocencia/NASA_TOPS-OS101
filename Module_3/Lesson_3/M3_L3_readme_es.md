# Haciendo datos abiertos (open data)

## Índice

- [Descripción general](#resumen)
- [Objetivos de Aprendizaje](#learning-objectives)
- [Planificando para los Datos Abiertos](#planning-for-open-data)
- [Seleccionando Formatos y Herramientas de Datos para la Interoperabilidad](#selecting-data-formats-and-tools-for-interoperability)
- [Haciendo los Datos Reusables Mediante la Documentación](#making-the-data-reusable-through-documentation)
- [Haciendo los Datos Reusables Mediante Licencias](#making-the-data-reusable-through-licensing)
- [Lección 3: Resumen](#lesson-3-summary)
- [Lección 3: Revisión De Conocimientos](#lesson-3-knowledge-check)

## Descripción general

En esta lección, aprendes los criterios y las tareas necesarias para asegurar que los conjuntos de datos que creas sean abiertos y reutilizables. La lección comienza con una discusión sobre la creación de un plan de gestión de datos, continúa con temas sobre la selección de formatos de datos abiertos y cómo incluir metadatos, archivos Readme y control de versiones para sus datos. Se completa con una discusión sobre licencias abiertas para datos.

## Objetivos de aprendizaje

Después de completar este módulo, deberías poder:

- Evaluar y seleccionar formatos de datos abiertos.
- Añadir documentación que permita a otros investigadores evaluar la relevancia de los datos. Esto incluye metadatos, archivos README y control de versiones.
- Listar dos licencias abiertas comunes utilizadas para conjuntos de datos.

## Planificación de datos abiertos

La mejor práctica al comenzar su viaje de datos abiertos es crear un Plan de Gestión de Datos (PGD). Esto describe cómo administrará, preservará y publicará sus datos durante y después de un proyecto de investigación. Elementos comunes en los PGD relevantes para datos abiertos incluyen una descripción de lo siguiente:

|          |                                                                                   |
| -------- | --------------------------------------------------------------------------------- |
| ¿Qué?    | Formatos de datos y (cuando sea relevante) estándares          |
| ¿Cuándo? | Cuando y si compartir datos                                                       |
| ¿Dónde?  | Los repositorios previstos para archivar los datos                                |
| ¿Cómo?   | Cómo permite el plan la reutilización de datos                                    |
| ¿Quién?  | Roles y responsabilidades de los miembros del equipo en la implementación del PGD |

En esta lección, abordaremos algunas pasos comunes para generar datos. Específicamente, nos centraremos en el "qué" de hacer datos. Esto incluye, qué formatos de datos deben utilizarse y los estándares a seguir para que los datos sean tan abiertos y tan fáciles de usar como sea posible.

Como primer paso, compruebe si su institución o fuente de financiamiento tiene guías, estándares o plantillas para PGDs.

## Selección de Formatos de Datos y Herramientas para Interoperabilidad

### Consideraciones de Formato de Datos

Son preferibles los formatos de datos que son compatibles con los usados por la comunidad, legibles por computadora, libres, modificables y abiertos. Puede parecer que hay tantos formatos de datos como diferentes tipos de datos. Cuando piense en seleccionar un formato de datos, considere lo siguiente:

- ¿Es el formato compatible con el tipo, forma y tamaño de los datos?
- ¿El formato de datos tiene soporte adecuado para metadatos?
- ¿Hay herramientas disponibles para leer fácilmente el formato de los datos o se necesitan herramientas especializadas?
- ¿Se utiliza el formato de datos de forma rutinaria en su disciplina? Los estándares comunitarios garantizan compatibilidad, interoperabilidad y facilidad de uso al intercambiar o compartir datos entre investigadores u organizaciones de la misma comunidad.

<img src="../images/media/image31.png" style="width:100%;height:auto;" />

Investiga si tu agencia de financiación, instituciones y/o repositorio de datos tiene requisitos adicionales o alguna guía sobre los formatos de datos.

### Formatos de datos no abiertos

Un formato de datos cerrado (sin soporte y o de propiedad privada) se refiere a un formato de archivo al que no se puede acceder libremente, no está estandarizado o ampliamente soportado por diferentes aplicaciones de software. Aquí hay algunos ejemplos de formatos de datos cerrados/con derechos de propiedad:

- **Adobe Photoshop (.psd):** El formato de archivo es propiedad de Adobe Photoshop, un popular software de edición de imágenes.
- **Microsoft Word (.doc/.docx):** Un formato de archivo con derechos de propiedad usado para almacenar datos de procesamiento de texto.
- **Dibujo automático (.dwg):** Un formato de datos con derechos de propiedad utilizado para el diseño asistido por ordenador (CAD).

Las aplicaciones de software que pueden leer pero no crear datos con formato DOC, PSD o DWG normalmente no soportan todas las características, capas, especificaciones y el funcionamiento interno del archivo original.

Algunos desafíos del uso de datos en formatos no abiertos incluyen:

- Problema al abrir el archivo debido a problemas de compatibilidad.
- La necesidad de instalar software o convertidores adicionales, lo que conduce a frustración y molestias.
- El contratiempo inicial atenúa el entusiasmo por usar tus datos.
- Convertir los datos a un formato universal puede llevar a un formato único o características que no se traducen bien, haciendo que los datos pierdan parte de su valor.
- Las nuevas políticas de datos abiertos pueden limitar el intercambio de datos privados, ya que a menudo no es compatible con el concepto de fácil distribución.

### Ejemplos de Formatos de Datos Abiertos

Algunos ejemplos de formatos de datos abiertos incluyen:

_Selecciona cada tarjeta para obtener más información._

|                                                                                                       |                                                                                                                                                                                                                  |
| ----------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Valores separados por comas (CSV)                                                  | Por simplicidad, legibilidad, compatibilidad, fácil intercambio de datos.                                                                                                                        |
| Formato de datos jerárquicos (HDF)                                                 | Para almacenar y recuperar datos de forma eficiente, compresión y soporte multidimensional.                                                                                                      |
| Formulario de datos comunes de red (NetCDF)                                        | Para autodescripción y portabilidad, subconjunto de datos eficiente (extracción de porciones específicas de conjuntos de datos grandes), estandarización e interoperabilidad. |
| Modelo de investigación-estudio- ensayo (ISA) para estudios de ciencias de la vida | Para la organización estructurada de datos, integración de datos e interoperabilidad entre experimentos, reproducibilidad y transparencia.                                                       |
| Sistema de transporte de imágenes flexible (FITS)                                  | Como estándar para datos astronómicos, metadatos y cabeceras de imagen flexibles y extenibles, compresión eficiente de datos y archivado de grandes conjuntos de datos.                          |
| Formato común de datos (CDF)                                                       | Para un formato auto-descriptivo legible en múltiples sistemas operativos, lenguajes de programación y entornos de software, datos multidimensionales e inclusión de metadatos.                  |

Al incorporar estándares abiertos, los autores pueden evitar barreras innecesarias y maximizar sus posibilidades de hacer que los datos sean útiles para sus comunidades.

## Hacer los datos reutilizables a través de la documentación

### Incorporación de documentación y metadatos para facilitar la reutilización

Los metadatos y la documentación de datos describen los datos para que otros y nosotros podamos usarlos y entenderlos mejor. Aunque los metadatos y la documentación están relacionados, hay una distinción importante. Los metadatos están estructurados, estandarizados y son legibles por computadora. La documentación no está estructurada y puede ser cualquier formato (a menudo un archivo de texto que acompaña los datos).

Para comprender mejor la documentación y los metadatos, tomemos un ejemplo de una receta de internet. Muchas de estas recetas comienzan con una larga descripción e historia de la receta, y tal vez consejos de cocina o repostería para el plato, antes de enumerar los ingredientes e instrucciones de cocción paso a paso.

- Los ingredientes e instrucciones son como los metadatas. Se pueden indexar y buscar a través de Google y otros motores de búsqueda.
- El texto descriptivo que incluye el fondo y el contexto de la receta son como la documentación. Son más libres, y no estandarizados.

Ya discutimos los metadatos antes en este módulo, ¡pero es lo suficientemente importante como para que nos repitamos un poco! También discutiremos otros tipos de documentación, como los archivos README.

### Metadatos: para humanos y máquinas

Los metadatos pueden facilitar la evaluación de la calidad del conjunto de datos y el intercambio de datos respondiendo a preguntas clave. También es la principal forma en que los usuarios encontrarán información sobre su conjunto de datos. Incluye información clave sobre temas, como:

- Cómo se recolectaron y procesaron los datos
- Qué variables/parámetros se incluyen en el conjunto de datos
- Qué variables están incluidas y con qué variables están relacionadas
- Quién recopiló los datos (equipo científico, organización, etc.)
- Cómo y dónde encontrar los datos (p. ej., DOI)
- Cómo citar los datos
- Qué región espacio-temporal / tiempo cubren los datos
- Toda información legal, directriz o estándar sobre los datos

### ¿Por qué añadir metadatos?

Los metadatos mejoran la búsqueda y la accesibilidad de los datos permitiendo potencialmente tanto a los humanos como a las computadoras leer e interpretar los conjuntos de datos. Los beneficios de crear metadatos sobre tus datos incluyen:

- Ayuda a los usuarios a entender los datos y si/cómo pueden ser usados/citados.
- Ayuda a los usuarios a ubicar los datos, especialmente cuando los metadatos son legibles y están estandarizados para ser interpretados por aplicaciones.
- Puede facilitar el análisis con herramientas de software que interpretan metadatos estandarizados (por ejemplo, Xarray).

Para ser legibles por las computadoras, los metadatos deben haber sido estandarizados. Un ejemplo de un estándar aceptado por la comunidad para etiquetar conjuntos de datos climáticos son las [Convenciones de CF](http://cfconventions.org/).

También hay paquetes de software que pueden leer metadatos y mejorar la experiencia del usuario de manera significativa. Por ejemplo, [Xarray](https://docs.xarray.dev/en/stable/index.html) es un paquete de software desarrollado por la comunidad de código abierto que se utiliza ampliamente en la climatología y la biomédicina, entre muchas otras disciplinas. Según su sitio web, "¡Xarray hace que trabajar con matrices multidimensionales con etiquetas en Python sea simple, eficiente y divertido!". ¡Es la parte "etiquetada" donde entran los metadatos estandarizados! Xarray puede interpretar los nombres de las variables y las dimensiones sin el aporte del usuario, haciendo el flujo de trabajo más fácil y menos propenso a cometerse errores (Ej. Los usuarios no tienen que recordar qué eje corresponde al "tiempo" - sólo tienen que llamar al eje con la etiqueta "tiempo").

Existen muchos estándares para los campos y estructuras de los metadatos para describir la información general de los datos. Utilice un estándar de su dominio cuando corresponda, o uno que sea solicitado por su repositorio de datos.

### Mejores prácticas de etiquetado de los metadatos

Metadatos útiles e informativos:

- Utiliza estándares que se usan comúnmente en tu campo.
- Cumple con los principios FAIR (Encontrable, Accesible, Interoperable y Reutilizable).
- Es lo más descriptivo posible.
- Es autodescriptivo.

Recuerda que cuantos más metadatos añadas, más fácil será para los usuarios de tus datos utilizarlos de manera eficaz. Cuando dudes:

- Busca y cumple con los estándares de repositorio/comunidad.
- Investiga recursos de ciencia abierta en línea para los metadatos, por ejemplo, [Turing Way.] (Vía Turística.)(https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-metadata.html)

**Anexo de etiquetado de metadatos de la NASA**

SPD-41a requiere campos de los metadatos que validen las conclusiones científicas de las publicaciones. Los metadatos deben:

- Ser robustos, cumplir con los estándares y describir los datos de forma clara y explícita.
- Tener replicabilidad y/o poder combinarse en diferentes ajustes.
- Incluir información sobre cómo se recolectaron los datos (por ejemplo, qué equipo/instrumentos se utilizaron).
- Incluir información sobre qué variables/parámetros fueron incluidos en este conjunto de datos.

### Documentación de acompañamiento

Al crear sus datos, además de añadir metadatos, es una buena práctica crear un documento al que los usuarios puedan hacer referencia. El documento puede hacerse como un archivo README, una guía de usuario o incluso de inicio rápido (o bien los tres).

README y otros archivos de documentación pueden incluir información como:

- Datos de contacto
- Información acerca de las variables
- Información sobre la incertidumbre
- Métodos de recogida de datos
- Referencias de versión y licencia
- Información sobre la estructura y el nombre de archivo de los datos
- Referencias a publicaciones que describen el conjunto de datos y/o su procesamiento

La intención es ayudar a los usuarios a entender rápidamente cómo pueden usar los datos y responder a preguntas comunes que se hagan sobre tus datos. Puede leer más información y ver una plantilla de README junto con un ejemplo (particularmente relevante para las ciencias médicas) en [this Harvard Medical School website.] (este sitio web de la Escuela Médica de Harvard.) (https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata/readme-files)

### Directrices para la versiones de datos

Establece un esquema de versiones para tus datos. Este es un método para mantener un seguimiento de las iteraciones de los datos que muestran el seguimiento de los cambios y la capacidad de revertir a una revisión anterior.

La versión adecuada genera una copia cambiada de un objeto de datos que está únicamente etiquetado con un número de versión. Esto permite a los usuarios rastrear cambios y corregir los errores.

La versión adecuada preserva la calidad y la procedencia de los datos (el origen, la historia y los pasos de procesamiento que conducen al conjunto de datos) por:

- Proporcionando un registro de trazabilidad desde la fuente de los datos a través de todos los aspectos de su transmisión, almacenamiento y procesamiento hasta su forma final.
- Guardando archivos de datos en pasos clave a lo largo del proceso.
- Apuntando a la verificación/validación de la descarga respecto a los hallazgos originales.

## Hacer los datos reutilizables a través de licencias

<img src="../images/media/image32.jpeg" style="width:100%;height:auto;" />

Fuente de la imagen: [xkcd.com](https://www.explainxkcd.com/wiki/index.php/File:copyright.jpg)

---

Los datos son propiedad intelectual de quienes investigan, o posiblemente de quien financia o la/s institución/es. Los datos son propiedad intelectual, pero eso no significa que no puedan ser utilizados por otros investigadores (con una atribución apropiada).

<img style="width:100%;height:auto;" src="../images/media/applylicensetoyourwork.jpg">

"Al aplicar una licencia a tu trabajo, dejas claro lo que otros pueden hacer con las cosas que estás compartiendo, y también las condiciones bajo las que los estás proporcionando (como citarte). También puedes exigir a quienes copien tu trabajo que hagan cosas a cambio".

**Base de Conocimiento de Ciencia Abierta [Open Science Knowledge Base](https://www.cos.io/)**

---

Si no licencias tu trabajo, otros no pueden o no deberían volver a usarlo- aunque quisieras. Como se mencionó previamente en este módulo, una licencia es un documento legal que le dice a las personas usuarias cómo pueden utilizar el conjunto de datos. Es importante entender las condiciones de la licencia de un conjunto de datos antes de la reutilización de esos datos para evitar cualquier infracción de derechos de autor u otras cuestiones de propiedad intelectual.

Un conjunto de datos sin licencia no significa que los datos estén abiertos; el uso de un conjunto de datos sin licencia no es algo ético. Contactar con quien haya creado los datos y obtener los permisos explícitos, suponiendo que aplican una licencia, es el mejor camino a seguir.

Es crucial entender cuándo y dónde se aplica la licencia. Por ejemplo, los datos creados con fondos públicos de investigación del Gobierno de los Estados Unidos son, por defecto, de dominio público. Sin embargo, esto solo aplica a la jurisdicción de los Estados Unidos. Para que esto se aplique internacionalmente, quienes sean creadores de datos deben seleccionar una licencia abierta.

<img src="../images/media/image34.jpeg" style="width:100%;height:auto;" />

Existen varios tipos diferentes de licencias que se construyen entre sí. Las licencias "Creative Commons" (CC) son utilizadas a menudo para conjuntos de datos. CC0 (también conocido como "dominio público") es la licencia que permite la mayor reutilización porque tiene las menores restricciones sobre lo que los usuarios pueden hacer. Aunque la licencia CC0 no requiere explícitamente de citas, debes seguir las mejores prácticas de la comunidad y citar la fuente de los datos. CC-BY es otra licencia común utilizada para datos científicos que requiere citación. A partir de ahí, puedes añadir restricciones sobre el uso comercial, la capacidad de adaptar o modificar los datos o requisitos para compartir con la misma licencia. Estos otros aditivos reducen la usabilidad al añadir restricciones, para que otras personas de ciencia no puedan utilizar los datos debido a restricciones institucionales o legales. Las agencias de financiación pueden requerir el uso de una licencia en específico. Para las agencias públicas, a menudo es CC-0 o CC-BY, para maximizar su rentabilidad de la inversión y asegurar la reutilización más amplia posible.

### Ejemplo de Licencias de Datos y su Reutilización

Aquí hay un ejemplo de cómo una licencia de datos puede afectar a la reutilización. La Fase 6 del Proyecto de Intercomparación de Modelo Acoplado (Coupled Model Intercomparison Project Phase 6 [CMIP6]) consiste en el "correr" alrededor de 100 distintos modelos climáticos que se están produciendo mediante 49 diferentes grupos de modelado. Estos son los datos que son utilizados para entender cómo podría ser nuestro futuro clima. Tú probablemente hayas visto imágenes que usan estos datos en artículos sobre el cambio climático de la Tierra y cómo puede impactar en nuestras vidas. Las versiones anteriores de estos datos contaban con licencia CC-BY-NC-SA (cite-noncommercial- sharealike).

<img src="../images/media/image35.jpeg" style="width:100%;height:auto;" />

Cita de Figura: IPCC (Ecuadre y contexto en: En: Calentamiento global de 1.5 °C. Un Reporte Especial de IPCC) "[Framing and Context in : In: Global warming of 1.5°C. An IPCC Special Report](https://www.researchgate.net/publication/369301788_Framing_and_Context_in_In_Global_warming_of_15C_An_IPCC_Special_Report?_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6Il9kaXJlY3QiLCJwYWdlIjoiX2RpcmVjdCJ9fQ)" 2020

---

Esto significó que cualquier uso comercial estaba restringido. Empresas de seguro, corporaciones globales, y cualquier tipo de organización que quería utilizarlos para fines comerciales - estaban teniendo que hacer su propio modelado o simplemente decidiendo no desarrollar recursos relacionados con proyecciones climáticas (como riesgo de incendios, riesgo de inundaciones, y cómo eso puede afectar al transporte, al comercio y al lugar donde vivimos). Esto afectó directamente a la reutilización de estos datos y creó trabajo adicional. La última versión de los datos CMIP se está moviendo a CC-BY [latest version of CMIP data is moving to CC-BY](https://pcmdi.llnl.gov/CMIP6/TermsOfUse/TermsOfUse6-2.html) debido a los impactos negativos de las restricciones -NC-SA.

## Lección 3: Resumen

A continuación se exponen los aportes principales de esta lección:

- Es una buena práctica crear un plan abierto de gestión de datos que incluya temas abiertos.
- Un paso crítico para hacer datos abiertos es la evaluación y la selección de formatos de datos abiertos.
- Siempre añadir documentación que permita a otras personas que investigan evaluar la relevancia y la reutilización de tu producto. Esto incluye a los metadatos, archivos README y los detalles del control de versiones.
- Es importante asignar una licencia abierta a tus datos para permitir su reutilización.

## Lección 3: Prueba de Conocimiento

Responde las siguientes preguntas para probar lo que has aprendido hasta ahora.

_Pregunta_

**01/04**

¿Cuál de los siguientes son los pasos que debes tomar al crear un plan de gestión de datos?

- Evaluar diferentes formatos de datos
- Probar tus metadatos para que cumplan
- Crear una pequeña colección de datos de prueba

_Pregunta_

**02/04**

¿Cuál de las siguientes son consideraciones al elegir un formato de archivo?

- El formato tiene soporte adecuado para los metadatos
- Las herramientas están disponibles para leer el formato de datos
- El formato de datos es ampliamente utilizado en tu comunidad
- Todas las anteriores

_Pregunta_

**03/04**

Lee la siguiente afirmación e indica si es Verdadera o Falsa.

_Los metadatos sólo son útiles para el uso de datos en herramientas interoperables y no mejoran la búsqueda y el encontrar los datos._

- Verdadero
- Falso

_Pregunta_

**04/04**

Lee la siguiente afirmación e indica si es Verdadera o Falsa.

_Cuando un conjunto de datos no requiere explícitamente citas, como la licencia CC0, igualmente se recomienda que cites la fuente de datos._

- Verdadero
- Falso
