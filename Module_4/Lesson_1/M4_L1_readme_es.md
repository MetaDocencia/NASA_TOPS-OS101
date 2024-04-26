# Lección 1: Introducción al Código Abierto

## Contenidos

- [Descripción general](#descripcióngeneral)
- [Objetivos de aprendizaje](#objetivos-de-aprendizaje)
- [Historias de éxito](#historias-de-éxito)
- [Definición y consideraciones sobre los datos abiertos](./Lesson_1#definición-y-consideraciones-sobre-los-datos-abiertos)
- [Principios, beneficios, y desafíos](./Lección_1#principios-beneficios-y-desafíos)
- [Cuándo no compartir](#cuando-no-compartir)
- [Planes de gestión de software (PGS)](./Lección_1#planes-de-gestión-de-software-pgs)
- [Lección 1: Resumen](#leccion-1-resumen)
- [Lección 1: Revisión De Conocimientos](#lesson-1-revisión-de-conocimientos)

## Descripción general

Esta lección define los términos clave, los principios básicos, las ventajas y los retos del código abierto. La práctica de desarrollar código y ponerlo a disposición del público se da dentro de un espectro que va de más a menos protegido. La condiciones éticas y legales pueden limitar el grado de apertura que que pueden permitirse los investigadores. En esta lección se presentarán las preguntas críticas que hay que tener en cuenta a la hora de determinar la accesibilidad adecuada del código para los usuarios externos, junto con las mejores prácticas para superar las limitaciones habituales y maximizar la disponibilidad. La lección finaliza con una discusión sobre el ciclo de vida del software y cómo encaja en el marco de "Usar, Hacer, Compartir" y su relación a un plan de gestión.

## Objetivos de aprendizaje

Al completar la lección, podremos:

- Definir software de código abierto y distinguirlo del software de código cerrado.
- Enumerar los beneficios y los retos más comunes de la producción de código abierto y describir cómo pueden responder los investigadores a algunos de los desafíos al tiempo que maximizan la apertura, cuando esto aplique.
- Describir la función y el propósito de un Plan de Gestión de Software, y su uso como una guía para todos los involucrados en un proyecto científico.

## Historias de éxito

¿Por qué el buen quehacer científico demanda que los investigadores abran el acceso a su código? Compartir el código (y los datos) facilita que otros reproduzcan los resultados, lo que ayuda a validar los descubrimientos y a reducir los recursos necesarios para duplicar los experimentos. Como un bonus, esta decisión puede dar lugar a nuevas colaboraciones, posibles gracias a un conjunto de datos compartido y a una comprensión común de un material científico.

Muchas revistas y agencias de financiación exigen compartir el código en el momento de la publicación. Sin embargo, la perspectiva de abrir el código a la crítica, no recibir reconocimiento o no participar de un resultado que descubran investigadores externos puede disuadir a los científicos de hacer su código de acceso abierto. ¿Qué pasaría si alguien encuentra un error? ¿Y si critican el estilo de codificación? ¿Y si usan el código y publican un nuevo resultado sin incluirnos? Este módulo está orientado a ayudarnos a ganar confianza a la hora de compartir nuestro código, ya que recorreremos los detalles básicos a tener en cuenta cuando se practica la ciencia abierta.

Repasemos algunos ejemplos conocidos de grupos que compartieron su código, y cuáles fueron los impactos:

Los botones pueden utilizarse para navegar entre los ejemplos.

<img src="../images/media/image394.jpg" style="width:350px;height:auto;" />

La primera imagen de un agujero negro no habría sido posible en esta década si todo el código necesario hubiera tenido que ser escrito únicamente por los científicos implicados. Estos científicos pudieron utilizar un software de código abierto bien probado y aceptado por la comunidad para realizar sus análisis y crear esta imagen ahora famosa. La Dra. Katie Bouman y su equipo elogiaron el papel fundamental que desempeñaron los colaboradores de código abierto en el esfuerzo de su equipo por obtener imágenes del primer agujero negro. Este avance fue posible gracias a las bibliotecas de código abierto, que ofrecían un código robusto y de libre acceso. El código utilizado para capturar esta imagen fue creado por 21.485 colaboradores. Los sofisticados algoritmos y pipelines iterativos de procesamiento de datos utilizados por el equipo de la Dra. Bouman fueron desarrollados y probados por la comunidad, lo que hizo posible una ciencia robusta y reproducible sin tener que reescribir cada pieza de software necesaria.

<img src="../images/media/image553.png" style="width:350px;height:auto;" />

Este es el helicóptero Ingenio, o como lo llaman los ingenieros, Ginny. Llegó a Marte haciendo autostop en el explorador Perseverance, que aterrizó en el cráter Jezero en 2021.

Este es un vídeo del primer vuelo de Ginny. Despegó, se elevó unos tres metros del suelo, dio una vuelta y aterrizó. Este vuelo pionero demostró que es posible volar a Marte con propulsión y abrió las puertas a una nueva era de exploración.

Pero los logros de Ginny también reflejan otra nueva era, la de una ciencia verdaderamente abierta e inclusiva.

Detrás de ese helicóptero de 4 libras hay más de 12.000 personas que contribuyeron con código, documentación, diseño y mucho más gracias al software de código abierto que se utilizó para impulsarlo. Todos los que contribuyeron a las bibliotecas de software de código abierto que Ginny utilizó recibieron una insignia en su página de GitHub que mostraba que habían ayudado a pilotar el primer helicóptero en Marte.

Además, el software final de Ginny desarrollado en el Jet Propulsion Lab, llamado F prime, era a su vez de código abierto y se ha utilizado desde entonces en la investigación de vuelos, drones y nanosatélites (CubeSats). De hecho, F prime se había copiado en repositorios de otras personas más de 1.200 veces.

<img src="../images/media/image408.jpg" style="width:350px;height:auto;" />

La mayoría de los datos de los telescopios espaciales se embargan durante 12 meses y sólo el equipo científico principal puede trabajar con ellos. En un caso único, se ofreció la liberación anticipada de una pequeña porción de los datos del nuevo telescopio espacial James Webb (JWST) de la NASA. Estos datos del JWST estuvieron disponibles inmediatamente.

¿Cuán aterrador es eso? Saber que todos todas las personas van a tener acceso exactamente al mismo tiempo. La ansiedad y el estrés de sentir que si no publicamos primero, puede que no tengamos trabajo, o que no tengamos el siguiente trabajo que deseamos.

En un caso, un equipo decidió trabajar totalmente en abierto y colaborar con estos datos de publicación temprana. ¿Cuál fue el resultado? Más de 20 artículos planeados y el primer descubrimiento de dióxido de carbono en otro planeta, lo que insinúa la posibilidad de descubrir nueva vida.

La Dra. Natasha Batalha, coautora del estudio, empleó principios de ciencia abierta para hacer posible este rápido descubrimiento utilizando los nuevos datos del JWST. En los años anteriores al lanzamiento del JWST, el equipo del Dr. Batalha formó un grupo colaborativo de 341 miembros. Una vez que los datos del JWST se hicieron públicos, la reducción de los datos y la interpretación científica se pudieron reproducir mediante software abierto y luego archivarse. El primer artículo del equipo de investigación estuvo disponible en acceso abierto en formato preprint y luego se publicó en Nature.

De este modo, el equipo de la Dra. Batalha publicó la primera identificación de CO2 en la atmósfera de un exoplaneta a partir de espectros tomados con JWST. Esto se llevó a cabo con los datos del Programa Científico de Liberación Temprana del JWST, los primeros datos científicos tomados por la instalación. El equipo trabajó en un formato abierto, desde la idea al análisis, pasando por la publicación y la comunicación.

Este ejemplo ilustra los beneficios de aplicar principios de ciencia abierta para producir rápidamente investigaciones significativas. El equipo trabajó en un formato abierto, desde la idea al análisis, pasando por la publicación y la comunicación.

<img src="../images/media/image168.jpg" style="width:350px;height:auto;" />

Los nuevos conjuntos de modelos climáticos de código abierto incorporan características que pretenden hacer la investigación climática más colaborativa, eficiente y fiable.

Las personas que participan de la investigación han publicado un marco de modelos climáticos de código abierto (Isca) que contiene modelos fáciles de obtener, totalmente gratuitos, documentados y con programas informáticos que facilitan su instalación y funcionamiento. Todos los cambios están documentados y pueden revertirse. Por lo tanto, cualquiera puede utilizar fácilmente los mismos modelos.

Aunque el modelo Isca se utilizó inicialmente para examinar la atmósfera tropical superior, las personas investigadoras de otros campos de la ciencia lo han empleado para estudiar el ciclo vital de los sistemas meteorológicos, el monzón indio y el efecto de las erupciones volcánicas en el clima.

Tan sólo un año después de la primera publicación del Isca fue posible realizar nuevas investigaciones en todos estos campos. ¡Así es como nos gustaría que funcione toda la ciencia!

Crédito:

[https://theconversation.com/making-climate-models-open-source-makes-them-even-more-useful-90929](https://theconversation.com/making-climate-models-open-source-makes-them-even-more-useful-90929)

## Definiciones y consideraciones del código abierto

Toda ciencia se construye en base a lo que ya se ha logrado. El código no es la excepción. Muchos científicos utilizan código para realizar análisis de datos. Este proceso comienza con la adquisición de datos, ya sea ejecutando un experimento o modelo que genere datos o identificando datos observacionales que puedan ser útiles para probar una hipótesis. A continuación se analizan los datos. Es muy probable que el código necesario para leer o analizar un nuevo conjunto de datos ya haya sido creado por alguien. Sin embargo, el código existente puede requerir cierto grado de modificación para ajustarse a los parámetros específicos de un investigador. Incluso el desarrollo de un nuevo modelo puede incorporar elementos específicos de códigos existentes de distintas fuentes.

Entender cómo encontrar y utilizar el código de otros, crear el propio y compartirlo es una parte importante del avance de la ciencia abierta. Al igual que las buenas prácticas de gestión de datos, conocer algunos detalles sobre cómo compartirlos no sólo te ayudará a utilizarlos más adelante, sino también a que otros sepan cómo utilizarlos y citarlos para que se te reconozca el mérito.

<img src="../images/media/image247.jpg" style="width:100%;height:auto;" />

Ejemplo de código de [https://github.com/UCB-stat-159-s23/site/blob/main/lectures/climate-data.ipynb](https://github.com/UCB-stat-159-s23/site/blob/main/lectures/climate-data.ipynb)

### ¿Qué es el código versus el software?

<img src="../images/media/image109.png" style="width:350px;height:auto;" />

Cuando escribimos "software", en realidad estamos escribiendo código de texto y utilizando un intérprete o compilador para traducirlo en un programa que la máquina pueda ejecutar. El código es un lenguaje que los humanos pueden escribir y entender. El software, suele ser un conjunto de programas, datos y otra información que un sistema informático utiliza para realizar tareas específicas. Un ejemplo es una biblioteca de software, que es un conjunto de datos y código de programación que se utiliza para desarrollar programas y aplicaciones de software.

Often, scientists write and publish code that helps others reproduce their results rather than creating software packages. But many scientists aren’t starting their code from scratch. There are large open- source software libraries that scientists use and contribute to, such as scipy, astropy, matplotlib, and others. Estas bibliotecas permiten a todo el mundo hacer ciencia más rápido y mejor porque han sido escritas, probadas y utilizadas por miles, sino cientos de miles, de personas. Estas bibliotecas han sido ampliamente adoptadas porque son de código abierto, lo que facilita la colaboración con cualquiera y en cualquier lugar.

### Qué es software de código abierto (Open Source Software)

**El software de código abierto (Open-source software)** se distribuye con su código fuente sin coste alguno, poniéndolo a disposición de las personas para que lo utilicen, modifiquen y distribuyan con sus derechos y permisos originales.

A menudo, el software de código abierto se comparte de forma transparente en un repositorio público y, en ocasiones, se mantiene gracias a la colaboración. A menudo, el software de código abierto se comparte de forma transparente en un repositorio público y, en ocasiones, se mantiene gracias a la colaboración.

Hay una variedad de opciones de licencia que se pueden elegir para el software abierto, las cuales pueden permitir al autor conservar diferentes niveles de propiedad y derechos. La elección de la licencia tiene un impacto en la reutilización por otros. Pero antes, vamos a desglosar los principales tipos de software que utiliza la comunidad científica en función de su propósito, mostrando ejemplos de cada tipo.

### Tipos de software

Las personas que investigan utilizan y producen una gran variedad de programas informáticos durante sus proyectos. Si bien muchas personas que investigan pueden simplemente usar ecuaciones en una hoja de cálculo, otros pueden utilizar bibliotecas de código abierto para el desarrollo avanzado de modelos de aprendizaje automático y para graficar resultados, mientras que otros pueden contribuir a bibliotecas de código abierto en su campo y aumentar así su reputación e impacto. Aquí tienes algunos ejemplos de diferentes tipos de software que podrías encontrar:

**Software de propósito general** - El software de propósito general se produce para un uso amplio y no para fines científicos especializados. Esto incluye software comercial y software de código abierto. Muchos de los programas de productividad más utilizados son éxitos del código abierto:

- Núcleo Linux (Linux kernel), espacio de usuario GNU, y varias distribuciones Linux y UNIX
- PostgreSQL: base de datos de nivel empresarial empresarial con código abierto
- Herramientas de alojamiento web para WordPress y Apache
- Firefox y Chrome
  - El motor de Chrome es Chromium, que es una bifurcación de WebKit, que a su vez es una bifurcación de KHTML Esto fue posible porque tenía una licencia que permitía este tipo de reutilización.  Todos los principales navegadores actuales, excepto Firefox, se remontan a KHTML.
- Sistema operativo Android, entre otros
  - Puedes mirar el código fuente de Android, pero no puedes modificarlo e instalarlo en un dispositivo. Y, aunque pudieras, no podrías utilizar ninguno de los servicios estándar (por ejemplo, Google Store) con él. Así que es "abierto" en el mismo sentido que los números de la lotería de anoche son "abiertos".

**Software Operativo**- El software operativo es utilizado por centros de datos y grandes instalaciones de tecnología de la información para proporcionar servicios de datos. Por ejemplo:

- [Fprime](https://nasa.github.io/fprime/) – Software de vuelo para misiones espaciales

**Software de infraestructura** - Los centros de datos y las grandes instalaciones de tecnología de la información utilizan software de infraestructura para proporcionar servicios de datos. Los ejemplos incluyen:

- [Fprime](https://nasa.github.io/fprime/) – Software de vuelo para misiones espaciales
- [PODAAC](https://github.com/podaac) – Software de archivo y procesamiento distribuido
- [UFS](https://github.com/ufs-community) – Software de modelos operativos de pronóstico del tiempo
- Verificador de Cumplimiento de Metadatos (Metadata Compliance Checker), APIs, Aplicaciones web, [Giovanni](https://www.earthdata.nasa.gov/technology/giovanni), [McIDAS](https://en.wikipedia.org/wiki/McIDAS)

**Bibliotecas** - Las bibliotecas son herramientas genéricas para implementar algoritmos conocidos, proporcionar análisis estadísticos o visualización de datos que se incorporan a otras categorías de software.
Los ejemplos incluyen:

- [NumPy](https://github.com/numpy) – Informática científica con python
- [scikit-image](https://github.com/scikit-image/) - Algoritmos de procesamiento de imágenes en python
- [deal.II](https://github.com/dealii/dealii) - Biblioteca de algoritmos para resolver ecuaciones diferenciales parciales con elementos finitos

**Software de modelización y simulación** - El software de modelización y simulación implementa soluciones a ecuaciones matemáticas a partir de datos de entrada y condiciones límite, o infiere modelos a partir de datos.
A menudo usan bibliotecas.
Algunos ejemplos incluyen: modelos de primeros principios, herramientas de asimilación de datos, modelos empíricos, aprendizaje de máquinas, planificación de misiones y herramientas de ingeniería, entre otros.

- [OpenFOAM](https://github.com/OpenFOAM) – Software de dinámica de fluidos computacional
- [MOM6](https://github.com/)[video] -ocean/MOM6) – Modelo de circulación oceánica general
- [ASPECT](https://github.com/geodynamics/aspect) – Software de convección planetaria
- Transferencia radiativa atmosférica, evolución estelar, turbulencia oceánica superior, predicciones del viento solar, propagación orbital (por ejemplo, OpenGGCM, MESA)

**Software de análisis** - El software de análisis se desarrolla para manipular mediciones o resultados de modelos con el fin de visualizarlos o comprenderlos mejor.
Este software suele evolucionar a partir del software utilitario de un solo uso y puede incorporar bibliotecas.

- [Photutils](https://photutils.readthedocs.io/en/stable/index.html) – herramientas para detectar y realizar fotometría de fuentes astronómicas

**Software de utilidad de uso único** - El software de utilidad de un solo uso está escrito para su uso en casos únicos, como hacer un gráfico para un artículo o manipular datos de una manera específica.
Este tipo de código a menudo utiliza bibliotecas para análisis, visualización o lectura de datos. Este tipo de software es el más común que se incluye en los Planes de Gestión de Ciencia Abierta y Datos (Open Science and Data Management Plans- OSDMP), sobre los cuales hablaremos en breve. Los ejemplos incluyen:

- [Angus et al. 2019](https://ui.adsabs.harvard.edu/abs/2019AJ....158..173A/abstract) - [Ajustando una relación giroscópica a Praesepe](https://github.com/RuthAngus/stardate/blob/master/paper/code/Fitting_Praesepe.ipynb)
- [El telescopio espacial Webb detecta CO2 en un exoplaneta por primera vez: qué significa para encontrar vida extraterrestre](https://www.nature.com/articles/d41586-022-02350-2). Todos los datos y modelos presentados en esta publicación pueden consultarse [aquí](https://doi.org/10.5281/zenodo.6959427).
- [Limitando el aumento de la frecuencia de las precipitaciones extremas en el mundo bajo el calentamiento global](https://www.nature.com/articles/s41558-022-01329-1)
- Código disponible en: [https://doi.org/10.5281/zenodo.6288035](https://doi.org/10.5281/zenodo.6288035) (2022)

## Principios, ventajas y retos

### Principios del Código Abierto

Los principios del software abierto se derivan de las mejores prácticas del software de código abierto. Establecen directrices que hacen avanzar la ciencia abierta y pretenden aumentar el valor y el impacto de la investigación.

|                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Transparencia                       | Ya sea que estemos desarrollando software o resolviendo un problema empresarial, todos tenemos acceso a la información y los materiales necesarios para hacer mejor nuestro trabajo. Cuando estos materiales son accesibles, podemos basarnos en las ideas y descubrimientos de los demás. Podemos tomar decisiones más eficaces y entender cómo nos afectan esas decisiones.                                                                           |
| Colaboración                        | Cuando somos libres de participar, podemos mejorar el trabajo de los demás de formas inesperadas. Cuando podemos modificar lo que otros han compartido, desbloqueamos nuevas posibilidades. Al iniciar nuevos proyectos juntos, podemos resolver problemas que nadie puede resolver por sí solo.  Y cuando aplicamos normas abiertas, permitimos que otros contribuyan en el futuro.                                                    |
| Compartir temprano y frecuentemente | Los prototipos rápidos pueden conducir a descubrimientos rápidos. Un enfoque iterativo conduce a mejores soluciones con mayor rapidez. Cuando tienes libertad para experimentar, puedes plantearte los problemas de nuevas formas y buscar respuestas en nuevos lugares. Puedes aprender haciendo.                                                                                                                                      |
| Inclusivo                           | Las buenas ideas pueden venir de cualquier parte, y las mejores deben ganar. Sólo mediante la inclusión de perspectivas diversas en nuestras conversaciones podemos estar seguros de haber identificado las mejores ideas, y los buenos responsables de la toma de decisiones buscan continuamente esas perspectivas. Puede que no funcionemos por consenso, pero el éxito del trabajo determina qué proyectos reúnen apoyo y esfuerzo de la comunidad. |
| Comunidad                           | Las comunidades se forman cuando diferentes personas se unen alrededor de un propósito común. Los valores compartidos guían la toma de decisiones y los objetivos de la comunidad prevalecen sobre los intereses y agendas individuales.                                                                                                                                                                                                                                |

Crédito: [The open source way | Opensource.com](https://opensource.com/open-source-way)

<img src="../images/media/image530.png" style="width:100%;height:auto;" />

Compartir código mejora la ciencia porque permite la reproducibilidad, la reutilización y la replicabilidad. La decisión de compartir el código beneficia a la comunidad científica porque aumenta la transparencia, la participación y la colaboración.  Compartir código en cualquier punto del proceso de investigación puede ser valioso.

En la mayoría de los casos, el código fuente utilizado para generar resultados en documentos revisados por pares debe ser publicado, citado y accesible.

### Ventajas de pasarse al software abierto

La ciencia avanza más rápido cuando las personas que investigan son capaces de trabajar juntos, ayudan a corregir errores, se basan en los resultados de los demás y comparten recursos. Compartir software es una parte clave de la ciencia abierta que:

- Acelera la ciencia haciendo más fácil el uso y la construcción de software desarrollado en trabajos anteriores.
- Minimiza el tiempo y el costo del desarrollo repetido de software similar y la reproducción de cálculos científicos.
- Aumenta el número potencial de personas usuarias y desarrolladores y ayuda a mejorar la calidad y la confianza en el software.
- Aumenta la probabilidad de que los sujetos desarrolladores obtengan visibilidad, sostenibilidad, calidad de software y avance su empleabilidad.

### Desafíos de mudarse al software abierto

No es raro que los grupos de investigación pasen años desarrollando código, escribiendo artículos con los resultados y ganando influencia científica al no compartir el código. Cualquier persona nueva que quiera trabajar en un proyecto similar se encuentra en gran desventaja porque tendría que empezar de cero.  Así, cualquiera que quiera trabajar en esa área se ve obligado a colaborar con el grupo.  Este grupo conserva una ventaja competitiva muy real al mantener el código cerrado. Sin embargo, este enfoque sofoca la innovación y perjudica el progreso científico. Muchas agencias de financiación están exigiendo que el código se comparta en el momento de la publicación, si no antes. Sin embargo, siguen existiendo desafíos y temores:

- La apertura tiene costes: tiempo de documentación, publicación, respuesta a los usuarios/mantenimiento y limpieza / mejora de la calidad.
- Se requiere un esfuerzo para aprender a aprovechar las nuevas herramientas y conocimientos (hay recursos disponibles para facilitar este esfuerzo).

| Miedo                                                                                            | Discusión/Mitigación:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ¿Qué pasa si alguien reutiliza mi código para publicar un resultado en el que estaba trabajando? | Sí, esto puede ocurrir. Sin embargo, en muchos campos, si está claro que alguien está trabajando activamente en un problema, la decisión de otro de adelantarse puede significar una ganancia a corto plazo pero una pérdida a largo plazo. En la comunidad científica, las reputaciones funcionan como una moneda cultural y generalmente colaborar con otros conduce a mayores éxitos profesionales. Si está compartiendo su código, asegúrese de que tiene un identificador de objeto digital (DOI) para obtener crédito. Esto no impide que nadie utilice ni amplíe su análisis, pero sí garantiza que obtendrá crédito por su contribución. Hay un buen artículo sobre esto aquí. |
| Error de interpretación o uso indebido                                                           | Proporcione suficiente información contextual (documentación) para permitir que otros entiendan plenamente su código para reducir este riesgo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Mi código será usado, pero no citado                                                             | Aunque no es común que la comunidad de investigadores citen código, datos u otros artículos no publicados, la ética científica dicta que se debe citar si se utiliza su trabajo. Recuerda citar adecuadamente el material de otras personas para que no agraves el problema.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| El código es demasiado sensible para compartirlo                                                 | Acceso controlado por quien usa el código para ayudar a mantener la sensibilidad y la seguridad.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| No será útil para nadie más                                                                      | Nunca sabes cómo se podrían usar los materiales. ¡Hay personas que aportaron una amplia variedad de proyectos de software, sin relación aparente entre ellos, y terminaron ayudando a la NASA a aterrizar un vehículo en Marte!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

#### En última instancia, eres libre de implementar los principios y recursos del software abierto en tu investigación para maximizar su impacto y cumplir con las expectativas de tu espónsor y de tu comunidad mientras gestionas los costos.

### Actividad 1.1: Relacionando los principios con los beneficios y desafíos

Determine si cada afirmación es un beneficio o un desafío arrastrándola a la caja correcta.

<table>
  <thead>
    <tr>
      <th colspan="2">Beneficios</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Hace más fácil el uso y la construcción de software desarrollado en trabajos anteriores.</td>
      <td>Las personas que usan Software Abierto son libres de usarlo y modificarlo, minimizando la duplicación de esfuerzos.</td>
    </tr>
    <tr>
      <td>Puede aumentar el uso del software, lo que puede ayudar a mejorar su calidad.</td>
      <td>Las personas que desarrollan Software Abierto pueden ganar visibilidad y sostenibilidad para su software.</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th colspan="2">Desafíos</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Requiere tiempo extra para actividades como documentación, publicación y mantenimiento.</td>
      <td>Se necesita esfuerzo para aprender a aprovechar las nuevas herramientas y conocimientos.</td>
    </tr>
  </tbody>
</table>

**Conclusiones principales: Relacionando los principios con los beneficios y desafíos**

- Hacer al software más abierto siguiendo los principios tiene beneficios y desafíos, que están relacionados.
- Mayores beneficios suelen venir con mayores desafíos.
- En la mayoría de los casos, las personas que se dedican a la ciencia y la sociedad entera se beneficiarán de un software más abierto.

## Cuándo no compartir

Existen razones válidas que restringen la capacidad de una persona dedicada a la investigación para compartir su código completo o sus paquetes de software. Algunas de estas razones pueden incluir:

- El código incorpora secretos militares de un país, o su diseminación viola intereses nacionales o trae problemas de seguridad.
- El código posee propiedad intelectual o datos e información patentados.
- Las políticas institucionales o las regulaciones de la organización no permiten compartir el código.
- Piensa en lo que estás compartiendo y las implicaciones de compartirlo (por ejemplo, ¿tienes permiso de todas las personas involucradas?).

### Estableciendo una licencia para el código

The [collaborative data science handbook by The Turing Way](https://the-turing-way.netlify.app/reproducible-research/licensing) says of restrictions to open source sharing, "As with anything else in society, some of what you can and cannot do in software (or hardware) development is determined by the law. Licensing is therefore an important aspect of sharing/publishing open source projects as it provides clarity for anyone looking to reuse an open source project. Without licenses in place, anyone who wants to reuse it will be left with legal ambiguity as to the status of using your intellectual property."

To be considered open source, software requires a license that complies with the Open Source Definition. One criteria of this definition demands that open source licenses "[must allow modifications and derived works, and must allow them to be distributed under the same terms as the license of the original software](https://opensource.org/licenses/)."

In the next lessons, licenses will be discussed in more detail. As you are working on a project, you may want to use code developed by others, develop your own code, and then share it. Licenses affect all aspects of this process and it is important to understand how different licenses may affect your ability to share your code at the time of publication. It is also important to consider any requirements from your funder or institution about how you license your software.

### Planning for Openness: Using the Use, Make, Share Framework for Open Code

Funding agencies and journals are increasingly requiring researchers to share software.

For example, NASA's ROSES, which solicits Earth science research proposals, requires researchers to make their software publicly available:

#### "Data and software developed using Research Opportunities in Space and Earth Sciences (ROSES) funding in support of a peer-reviewed publication shall be made publicly available at the time of publication"

[https://science.nasa.gov/researchers/sara/faqs/osdmp](https://science.nasa.gov/researchers/sara/faqs/osdmp)

Planning for a research project requires researchers to determine their mode of collaboration and method of sharing code. This step is often documented in a Software Management Plan (SMP) within a research proposal. An SMP details the what, when, where, how, and who will be sharing the code or software.

## Software Management Plans (SMP)

Software management plans encompass both code and software.

|        |                                                                                                          |
| ------ | -------------------------------------------------------------------------------------------------------- |
| What?  | Description of types, management, preservation, and release of software.                 |
| When?  | The schedule for software archiving and sharing.                                         |
| Where? | Location where software will be shared and archived over the long term.                  |
| How?   | Enable reuse of software through assigning a DOI, license, contribution guidelines, etc. |
| Who?   | Roles and responsibilities of the team members.                                          |

As your research starts using, creating, and sharing code, the SMP provides a guidebook for everyone on the project that establishes a common understanding.

Is your project sharing all code publicly or just code that goes into a publication? Will your team be contributing back to open-source projects or just writing code that builds on them to produce results? Considering these questions early will influence how much time and energy you may want to spend on documentation and how you plan to share the code.

### Open Code is a Spectrum

Just like data, code can be shared in many different ways to increase reusability. Code can be shared without any documentation, purely as a reproducibility artifact, or code can be well-written, documented, and openly-licensed to maximize re-use. Both of these approaches have value and depend on the time, energy, and funding that researchers have available.

- There is a spectrum of openness when it comes to open software that ranges from open- source software to closed source software.
- An example of something “in between” could be an executable file with documentation on how the code works.
- Some projects may be open from inception and continuously share all code throughout development. Others may share some of the code at the time of publication. Other projects may only make code available once funding ends. A variety of valid reasons factor into a project’s approach to sharing.
- While some factors restrict the degree of openness that software can be, each step towards sharing advances the open science movement.
- By sharing more ideas and software, communities have driven creative, scientific, and technological advancement faster than the restricted pace of closed science. Peer production and mass collaboration creates more sustainable software development.

While researchers and institutions may not be able to share all their code, they can make efforts to shift on the openness spectrum from closed code to open-source code and software.

_In the activity below, drag each slider to explore the spectrum of openness._

<img src="../images/media/image110.jpg" style="width:100%;height:auto;" />

### The Practice of 'Open'

Review how the key tasks in the software development life cycle are covered in the "Use, Make, Share" framework flow.

<img src="../images/media/image290.png" style="width:100%;height:auto;" />

As with open data, different aspects of open software are described in terms of Using, Making, and Sharing of open software.

A key difference with software is that the process is typically more cyclical and repetitive than with data or results. Typically, software constantly evolves. Thus, the boundaries between "Use-Make- Share" are less rigid and the process is typically more dynamic and circular than pre-planned/fixed and sequential.

### Activity 1.2: How Can You Use Open Software in Your Work to Advance Open Science

In this activity, you are asked to reflect on how you have used and can use the open software principles to advance your work.

Consider the following questions:

1. Have you used open software principles 1 in your work?
2. What are some of the successes and challenges you have encountered?
3. What resources did you find useful for advancing open software in your work?

#### Key Takeaways: How Can You Use Open Software in Your Work to Advance Open Science

- Open software is a collaborative activity.
- We can all learn and benefit from each other in making our scientific software more open.

## Lesson 1: Summary

In this lesson, you learned that:

- In open-source software, anyone can see the underlying source-code.
- Open-source principles promote transparency, collaboration, sharing, inclusiveness, and communities.
- Open-source software accelerates science, minimizes time and cost of repeated development of similar software and reproducing scientific computations, and can improve quality and trust in science.
- Licenses for open-source software dictate its shareability and reusability to developers and prospective contributors. Funding entities and affiliated institutions may impose restrictions on how developers license their software.
- A software management plan (SMP) is a project guidebook with a common understanding of data management practices that a research team can work from.

## Lesson 1: Knowledge Check

Answer the following questions to test what you have learned so far.

_Question_

**01/03**

Read the statement below and decide whether it's true or false:

_Software is referred to as open source when it is publicly accessible; anyone can see, modify, and distribute the code as they see fit._

- True
- False

_Question_

**02/03**

Which of the following are valid reasons why scientists keep their source code closed? Select all that apply.

- National security concerns
- Institutional policies
- Data privacy concerns
- Attribution concerns
- Quality concerns

_Question_

**03/03**

What are the main sections in a software management plan?

- Types of code and software
- Schedule for sharing software
- Where software will be shared and archived
- What license it will be assigned
- Roles and responsibilities of team members
- All of the above
