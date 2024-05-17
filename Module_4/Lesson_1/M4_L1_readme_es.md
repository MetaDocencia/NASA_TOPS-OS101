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

A menudo, las personas que hacen ciencia escriben y publican código que ayuda a otros a reproducir sus resultados, en lugar de crear paquetes de software. Pero muchas de estas personas no empiezan su código desde cero. Existen grandes bibliotecas de software de código abierto que los científicos utilizan y a las que contribuyen, como scipy, astropy, matplotlib y otras. Estas bibliotecas permiten a todo el mundo hacer ciencia más rápido y mejor porque han sido escritas, probadas y utilizadas por miles, sino cientos de miles, de personas. Estas bibliotecas han sido ampliamente adoptadas porque son de código abierto, lo que facilita la colaboración con cualquiera y en cualquier lugar.

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
| Colaboración                        | Cuando somos libres de participar, podemos mejorar el trabajo de los demás de formas inesperadas. Cuando podemos modificar lo que otras personas han compartido, desbloqueamos nuevas posibilidades. Al iniciar nuevos proyectos juntos, podemos resolver problemas que nadie puede resolver por sí solo. Y cuando aplicamos normas abiertas, permitimos que otros contribuyan en el futuro.                                            |
| Compartir temprano y frecuentemente | Los prototipos rápidos pueden conducir a descubrimientos rápidos. Un enfoque iterativo conduce a mejores soluciones con mayor rapidez. Cuando tienes libertad para experimentar, puedes plantearte los problemas de nuevas formas y buscar respuestas en nuevos lugares. Puedes aprender con la práctica.                                                                                                                               |
| Inclusivo                           | Las buenas ideas pueden venir de cualquier parte, y las mejores deben ganar. Sólo mediante la inclusión de perspectivas diversas en nuestras conversaciones podemos estar seguros de haber identificado las mejores ideas, y los buenos responsables de la toma de decisiones buscan continuamente esas perspectivas. Puede que no funcionemos por consenso, pero el éxito del trabajo determina qué proyectos reúnen apoyo y esfuerzo de la comunidad. |
| Comunidad                           | Las comunidades se forman cuando diferentes personas se unen alrededor de un propósito común. Los valores compartidos guían la toma de decisiones, y los objetivos de la comunidad prevalecen sobre los intereses y agendas individuales.                                                                                                                                                                                                                               |

Crédito: [El camino del código abierto| Opensource.com](https://opensource.com/open-source-way)

<img src="../images/media/image530.png" style="width:100%;height:auto;" />

Compartir código mejora la ciencia porque permite la reproducibilidad, la reutilización y la replicabilidad. La decisión de compartir el código beneficia a la comunidad científica porque aumenta la transparencia, la participación y la colaboración. Compartir código en cualquier punto del proceso de investigación puede ser valioso.

En la mayoría de los casos, el código fuente utilizado para generar resultados en documentos revisados por pares debe ser publicado, citado y accesible.

### Ventajas de pasarse al software abierto

La ciencia avanza más rápido cuando las personas que investigan son capaces de trabajar juntas, ayudan a corregir errores, se basan en los resultados de los demás y comparten recursos. Compartir software es una parte clave de la ciencia abierta que:

- Acelera la ciencia haciendo más fácil el uso y la construcción de software desarrollado en trabajos anteriores.
- Minimiza el tiempo y el costo del desarrollo repetido de software similar y la reproducción de cálculos científicos.
- Aumenta el número potencial de personas usuarias y desarrolladoras y ayuda a mejorar la calidad y la confianza en el software.
- Aumenta la probabilidad de que quienes desarrollan obtengan visibilidad, sostenibilidad, calidad de software y avance su empleabilidad.

### Desafíos de mudarse al software abierto

No es raro que los grupos de investigación pasen años desarrollando código, escribiendo artículos con los resultados y ganando influencia científica al no compartir el código. Cualquier persona nueva que quiera trabajar en un proyecto similar se encuentra en gran desventaja porque tendría que empezar de cero. Así, cualquiera que quiera trabajar en esa área se ve obligado a colaborar con el grupo. Este grupo conserva una ventaja competitiva muy real al mantener el código cerrado. Sin embargo, este enfoque sofoca la innovación y perjudica el progreso científico. Muchas agencias de financiación están exigiendo que el código se comparta en el momento de la publicación, si no antes. Sin embargo, siguen existiendo desafíos y temores:

- La apertura tiene costos: tiempo de documentación, publicación, respuesta a las personas usuarias/mantenimiento y limpieza/mejora de la calidad.
- Se requiere un esfuerzo para aprender a aprovechar las nuevas herramientas y conocimientos (hay recursos disponibles para facilitar este esfuerzo).

| Miedo                                                                                            | Discusión/Mitigación:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ¿Qué pasa si alguien reutiliza mi código para publicar un resultado en el que estaba trabajando? | Sí, esto puede ocurrir. Sin embargo, en muchos campos, si está claro que alguien está trabajando activamente en un problema, la decisión de otra persona de adelantarse puede significar una ganancia a corto plazo pero una pérdida a largo plazo. En la comunidad científica, las reputaciones funcionan como una moneda cultural y generalmente colaborar con otras personas conduce a mayores éxitos profesionales. Si estás compartiendo tu código, asegúrate de que tienes un identificador de objeto digital (en inglés, _Digital Object Identifier, DOI_) para obtener crédito. Esto no impide que nadie utilice ni amplíe tu análisis, pero sí garantiza que obtendrás crédito por tu contribución. Hay un buen artículo sobre esto aquí. |
| Error de interpretación o uso indebido                                                           | Proporciona suficiente información contextual (documentación) para permitir que otras personas entiendan plenamente tu código para reducir este riesgo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Mi código será usado, pero no citado                                                             | Aunque no es común que las personas investigadoras citen código, datos u otros artículos no publicados, la ética científica dicta que se debe citar si se utiliza tu trabajo. Recuerda citar adecuadamente el material de otras personas para que no agraves el problema.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| El código es demasiado sensible para compartirlo                                                 | Acceso controlado por quien usa el código para ayudar a mantener la sensibilidad y la seguridad.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| No será útil para nadie más                                                                      | Nunca sabes cómo se podrían usar los materiales. ¡Hay personas que aportaron una amplia variedad de proyectos de software, sin relación aparente, y terminaron ayudando a la NASA a aterrizar un vehículo en Marte!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

#### En última instancia, eres libre de implementar los principios y recursos del software abierto en tu investigación para maximizar su impacto y cumplir con las expectativas de tu espónsor y de tu comunidad mientras gestionas los costos.

### Actividad 1.1: Relacionando los principios con los beneficios y desafíos

Determina si cada afirmación es un beneficio o un desafío arrastrándola a la caja correcta.

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

- Hacer al software más abierto siguiendo los principios tiene beneficios y desafíos, los cuales están relacionados.
- Mayores beneficios suelen venir con mayores desafíos.
- En la mayoría de los casos, las personas que se dedican a la ciencia y la sociedad entera se beneficiarán de un software más abierto.

## Cuándo no compartir

Existen razones válidas que restringen la capacidad de una persona dedicada a la investigación para compartir su código completo o sus paquetes de software. Algunas de estas razones pueden incluir:

- El código incorpora secretos militares de un país, o su diseminación viola intereses nacionales o trae problemas de seguridad.
- El código posee propiedad intelectual o datos e información patentados.
- Las políticas institucionales o las regulaciones de la organización no permiten compartir el código.
- Piensa en lo que estás compartiendo y las implicaciones de compartirlo (por ejemplo, ¿tienes permiso de todas las personas involucradas?).

### Estableciendo una licencia para el código

El [manual colaborativo de ciencia de datos de The Turing Way](https://the-turing-way.netlify.app/reproducible-research/licensing) dice acerca de las restricciones para compartir código abierto, "Como con cualquier otra cosa en la sociedad, parte de lo que puedes hacer y de lo que no puedes hacer en el desarrollo de software (o hardware) está determinado por la ley. Por lo tanto, la definición de una licencia es un aspecto importante para compartir/publicar proyectos de código abierto ya que da claridad para cualquiera que busque reutilizar un proyecto de código abierto. Sin una licencia, cualquiera que quiera reutilizarlo tendrá ambigüedad jurídica en cuanto al estado de uso de tu propiedad intelectual".

Para ser considerado de código abierto, el software requiere una licencia que cumpla con la definición de Código Abierto. Uno de los criterios de esta definición exige que las licencias de código abierto "[deben permitir modificaciones y obras derivadas, y deben permitir que se distribuyan bajo los mismos términos que la licencia del software original](https://opensource.org/licenses/)".

En las próximas lecciones discutiremos con más detalle las licencias. Cuando trabajas en un proyecto puedes usar código desarrollado por otras personas, desarrollar tu propio código y luego compartirlo. Las licencias afectan a todos los aspectos de este proceso y es importante entender cómo diferentes licencias pueden afectar tu capacidad para compartir tu código en el momento de la publicación. También es importante que tengas en cuenta cualquier requerimiento de tu institución o de quien te financia acerca de cómo licenciar tu software.

### Planificando la apertura: usando el sistema Usar, Hacer, Compartir para Código Abierto

Las agencias de financiación y las revistas exigen cada vez más a los investigadores que compartan software.

Por ejemplo, el programa ROSES de la NASA, que solicita propuestas de investigación en ciencias de la Tierra, exige a los investigadores que pongan sus programas informáticos a disposición del público:

#### «Los datos y el software desarrollados con financiación de Oportunidades de Investigación en Ciencias Espaciales y de la Tierra (ROSES) en apoyo de una publicación revisada por pares se pondrán a disposición del público en el momento de la publicación»

[https://science.nasa.gov/researchers/sara/faqs/osdmp](https://science.nasa.gov/researchers/sara/faqs/osdmp)

La planificación de un proyecto de investigación requiere que los investigadores determinen su modo de colaboración y el método para compartir el código. Este paso suele documentarse en un Plan de Gestión del Software (SMP) dentro de una propuesta de investigación. Un SMP detalla el qué, cuándo, dónde, cómo y quién compartirá el código o el software.

## Plan de gestión de software (SMP)

Los planes de gestión de software abarcan tanto el código como el software.

|          |                                                                                                                                                                 |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ¿Qué?    | Qué:\*\* Descripción de la gestión, conservación y distribución de software.                                                    |
| ¿Cuando? | Cuándo:\*\* El cronograma para archivar y compartir software.                                                                   |
| ¿Dónde?  | Dónde:\*\* Ubicación donde se compartirá y archivará el software a largo plazo.                                                 |
| ¿Cómo?   | Cómo:\*\* Habilitar la reutilización del software mediante la asignación de un DOI, licencia, directrices de contribución, etc. |
| ¿Quién?  | Quién:\*\* Roles, funciones y responsabilidades de los miembros del equipo.                                                     |

A medida que su investigación comienza a utilizar, crear y compartir código, el SMP proporciona una guía para todos los participantes en el proyecto que establece un entendimiento común.

¿Está tu proyecto compartiendo todo el código públicamente o simplemente el código que entra en una publicación? ¿Contribuirá su equipo a los proyectos de código abierto o se limitará a escribir código basado en ellos para obtener resultados? Considerar estas cuestiones desde el principio influirá en la cantidad de tiempo y energía que quiera dedicar a la documentación y en cómo piensa compartir el código.

### El Código Abierto es un espectro

Al igual que los datos, el código puede compartirse de muchas maneras diferentes para aumentar la reusabilidad. El código puede ser compartido sin ninguna documentación, simplemente como un artefacto de reproducibilidad, o el código puede estar bien escrito, documentado y abiertamente licenciado para maximizar el reuso. Ambos enfoques tienen valor y dependen del tiempo, la energía y la financiación disponibles por los investigadores.

- Existe un espectro de apertura en lo que respecta al software libre que va desde el software de código abierto al software de código cerrado.
- Un ejemplo de algo “intermedio” podría ser un archivo ejecutable con documentación sobre cómo funciona el código.
- Algunos proyectos pueden abrirse desde el principio y compartir todo el código a lo largo del desarrollo. Otros pueden compartir parte del código en el momento de la publicación. Otros proyectos sólo pueden poner el código disponible una vez finalizada la financiación. Hay varias razones válidas que influyen en el planteamiento de un proyecto a la hora de compartir.
- Aunque algunos factores restringen el grado de apertura que puede tener el software, cada paso hacia la apertura hace avanzar el movimiento de la ciencia abierta.
- Al compartir más ideas y programas informáticos, las comunidades han impulsado el avance creativo, científico y tecnológico más rápidamente que el ritmo restringido de la ciencia cerrada. La producción entre iguales y la colaboración masiva crean un desarrollo de software más sostenible.

Aunque los investigadores y las instituciones no puedan compartir todo su código, sí pueden esforzarse por pasar del código cerrado al código y software de código abierto.

_En la actividad de abajo, arrastra cada deslizador para explorar el espectro de la apertura._

<img src="../images/media/image110.jpg" style="width:100%;height:auto;" />

### La Práctica de lo 'Abierto'

Repase cómo se cubren las tareas clave del ciclo de vida de desarrollo de software en el flujo marco "Usar, Hacer, Compartir".

<img src="../images/media/image290.png" style="width:100%;height:auto;" />

Al igual que ocurre con los datos abiertos, los distintos aspectos del software abierto se describen en términos de Uso, Creación y Puesta en común del software abierto.

Una diferencia clave con el software es que el proceso suele ser más cíclico y repetitivo que con los datos o los resultados. Por lo general, el software evoluciona constantemente. Así, los límites entre «Usar-Hacer-Compartir» son menos rígidos y el proceso suele ser más dinámico y circular que preplanificado/fijo y secuencial.

### Actividad 1.2: Cómo puede utilizar el software abierto en su trabajo para promover la ciencia abierta

En esta actividad, se le pide que reflexione sobre cómo ha utilizado y puede utilizar los principios de software abierto para hacer avanzar su trabajo.

Considera los siguientes aspectos destacados:

1. ¿Ha utilizado los principios de software abierto 1 en su trabajo?
2. ¿Cuáles son algunos de los éxitos y retos con los que se ha enfrentado?
3. ¿Qué recursos le resultaron útiles para impulsar el software abierto en su trabajo?

#### Actividad : Cómo puede utilizar el software abierto en su trabajo para promover la ciencia abierta

- El software abierto es una actividad colaborativa.
- Todos podemos aprender y beneficiarnos unos de otros haciendo que nuestro software científico sea más abierto.

## Lección 1: Resumen

En esta lección, has aprendido:

- En el software de código abierto, cualquiera puede ver el código fuente.
- Los principios del código abierto promueven la transparencia, la colaboración, el intercambio, la inclusión y las comunidades.
- El software de código abierto acelera la ciencia, minimiza el tiempo y el coste del desarrollo repetido de software similar y la reproducción de cálculos científicos, y puede mejorar la calidad y la confianza en la ciencia.
- Las licencias de los programas de código abierto dictan su compartibilidad y reutilización para los desarrolladores y posibles colaboradores. Las entidades financiadoras y las instituciones afiliadas pueden imponer restricciones a la forma en que los desarrolladores licencian su software.
- Un plan de gestión de software (SMP) es una guía del proyecto con un consenso común de las prácticas de gestión de datos a partir del cual puede trabajar un equipo de investigación.

## Lección 1: Revisión de conocimientos

Responde las siguientes preguntas para poner a prueba lo que ha aprendido hasta ahora.

Pregunta

**01/03**

Lee la siguiente afirmación y decide si es verdadera o falsa:

_Se dice que un programa informático es de código abierto cuando es de acceso público; cualquiera puede ver, modificar y distribuir el código como mejor le parezca._

- Verdadero
- Falso

Pregunta

02/03

¿Cuáles de las siguientes son razones válidas para que los científicos mantengan cerrado su código fuente? Selecciona todos los que correspondan.

- Preocupación por la seguridad nacional
- Políticas institucionales
- Protección de datos
- Problemas de atribución
- Problemas de calidad

Pregunta

03/03

¿Cuáles son las principales secciones de un plan de gestión de software?

- Tipos de código y software
- Calendario para compartir software
- Donde el software será compartido y archivado
- Qué licencia será asignada
- Roles y responsabilidades de los miembros del equipo
- Todas las anteriores
