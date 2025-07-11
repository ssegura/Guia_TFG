# Guía para Proyectos Fin de Grado sobre Desarrollo de Software

[Sergio Segura Rueda](https://personales.us.es/sergiosegura/) <br>
Departamento de Lenguajes y Sistemas Informáticos <br> 
Escuela Técnica Superior de Ingeniería Informática <br> 
Universidad de Sevilla

## Sobre este documento

Este documento no constituye una guía oficial. Su contenido refleja únicamente la opinión y experiencia del autor, y debe utilizarse con fines informativos y orientativos. La información aquí presentada debe contrastarse siempre con la documentación oficial de la asignatura de Proyecto Fin de Grado y con las indicaciones del tutor o tutora asignado/a.


## Resumen

El objetivo de este documento es proporcionar a los estudiantes de grados en Informática guías y recomendaciones para la elaboración del Proyecto fin de Grado (TfG) sobre desarrollo de software. Se abordan aspectos clave como la elección de la temática, la elaboración de la documentación y el contenido de los apartados más relevantes. Las orientaciones aquí recogidas deben interpretarse como pautas generales, adaptándolas siempre a las características de cada TfG, la normativa vigente, y las indicaciones del tutor/a. Dado que la naturaleza de este tipo de trabajos es la de un proyecto software en adelante se utilizarán los términos _proyecto_ y _trabajo_ indistintamente.


## Índice

1. [Temática](#1-temática)
2. [Documentación](#2-documentación)
3. [Resumen](#3-resumen)
4. [Motivación](#4-motivación)
5. [Planificación](#5-planificación)
6. [Metodología](#6-metodología)
7. [Ecosistema de desarrollo](#7-ecosistema-de-desarrollo)
8. [Requisitos](#8-requisitos)
9. [Diseño](#9-diseño)
10. [Implementación](#10-implementación)
11. [Pruebas](#11-pruebas)
12. [Referencias](#12-referencias)
13. [Uso de Inteligencia Artificial](#13-uso-de-inteligencia-artificial)
14. [Video demostración](#14-video-demostración)
15. [Presentación](#15-presentación)


## 1 Temática

La temática del proyecto debe seleccionarse teniendo en cuenta su originalidad, utilidad y
complejidad. Deben evitarse proyectos que no aporten nada novedoso, o que pudieran ser
realizados sin mayores dificultades con herramientas existentes (ej. gestores de contenido). Los
siguientes son ejemplos de proyectos potencialmente interesantes:

- **Proyectos con un cliente real**. Los proyectos que abordan las necesidades de un cliente
    real, una ONG o una empresa familiar, por ejemplo, suelen valorarse de forma positiva.
    La interacción necesaria entre el estudiante y las personas que necesitan la aplicación
    enriquece el proceso de aprendizaje y lo acerca a contextos profesionales reales,
    promoviendo el desarrollo de competencias clave.
- **Proyectos con orientación social**. Se suele valorar de forma positiva a aquellos proyectos
    que intentan resolver problemas relevantes para la sociedad como, por ejemplo, aquellos
    relacionados con los [Objetivos de Desarrollo Sostenible](https://www.un.org/sustainabledevelopment/es/objetivos-de-desarrollo-sostenible/) definidos por la ONU (ej.
    promover la economía circular). También se pueden encuadrar en este tipo de proyecto
    aquellos que abordan las necesidades de una ONG, por ejemplo. Estos trabajos van más
    allá de una simple experimentación con la tecnología y, aunque en la mayoría de los casos
    queden en una prueba de concepto, se consideran adecuados.
- **Proyectos con tecnologías novedosas**. Una de las dimensiones en las que puede destacar
    un proyecto es en el conjunto de tecnologías que utiliza. El uso de tecnologías y
    herramientas novedosas añade dificultad al proyecto a la vez que demuestran la
    capacidad de autoaprendizaje del estudiante, fundamental en el ámbito de la
    informática, lo cual se suele considerar un aspecto positivo.
- **Proyectos multidisciplinares**. Los proyectos que combinan conocimientos de distintas
    disciplinas o áreas son especialmente interesantes pues requieren que el estudiante
    investigue temáticas muy diferentes y consiga integrarlas de manera efectiva para dar
    respuesta a un problema concreto. Un posible ejemplo sería una aplicación capaz de
    analizar vídeos de mítines políticos e identificar automáticamente afirmaciones falsas
    mediante el uso de modelos de inteligencia artificial. Este tipo de proyectos suelen ser
    valorados de forma muy positiva.

Nótese que los tipos de proyectos mencionados anteriormente no son excluyentes entre sí. Así,
sería posible, y recomendable, desarrollar un proyecto con un enfoque social que, al mismo
tiempo, proponga una solución original que involucre tecnologías novedosas y combine
conocimientos de distintas áreas de conocimiento.

## 2 Documentación

La documentación del proyecto debe seguir un **estilo formal y riguroso**. Es común que existan
plantillas predefinidas propuestas por la propia asignatura, el departamento o la escuela.
Independientemente del uso de plantillas, existen dos alternativas principales para su
elaboración:

- **Editores de texto** convencionales como Microsoft Word o Google Drive. Su uso es sencillo
    y no requiere formación específica. Con este tipo de herramientas el estudiante debe
    encargarse del formato visual y la maquetación (colores, márgenes, referencias, etc) lo
    que suele ser un proceso bastante laborioso. Existen plantillas predefinidas que facilitan
    el proceso, pero sigue siendo necesario invertir un tiempo significativo en la
    maquetación.


- **Sistemas de marcas** como LaTeX a través de editores como [Overleaf](https://www.overleaf.com/) o [Typst](https://typst.app/). Estas
    herramientas utilizan sistemas de marcas que permiten independizar el contenido del
    formato visual. De esta manera, el estudiante puede concentrarse en el contenido y
    delegar la maquetación y el aspecto visual a la herramienta, normalmente a partir de
    plantillas predefinidas. El aspecto negativo de esta alternativa suele ser su complejidad,
    ya que familiarizarse con el sistema de marcas suele requerir tiempo.

Independientemente de la herramienta seleccionada, es fundamental que el estilo visual del
documento sea **profesional, coherente y homogéneo**. Es recomendable dedicar tiempo al inicio
del proyecto para definir cuidadosamente la maquetación y el formato visual. De lo contrario, es
probable que más adelante sea necesario realizar modificaciones de estilo que impliquen rehacer
parte del proyecto ya realizado.

El documento debe incluir **índices** de contenidos, tablas y figuras. Todos deben generarse de
forma automática mediante el uso de referencias cruzadas. Todas las tablas y figuras deben incluir
un pie descriptivo y deben referenciarse desde el texto (ej.: "La Figura X muestra el prototipo de
la vista de...").

Deben emplearse **imágenes de alta calidad**. No deben incluirse imágenes pixeladas, nunca, y en
ningún caso se deben salir de los márgenes del documento. Todas las imágenes deben
referenciarse desde el texto. En el caso de diagramas de software, estos deben explicarse de
forma detallada. En el caso de que una imagen contenga texto, el tamaño de éste debe ser lo más
parecido posible al tamaño del texto del documento.

Los fragmentos de código deben incluirse preferiblemente con **fondo blanco y líneas numeradas**
para poder hacer referencia a las mismas desde el texto.

La **redacción** debe ser **formal y cuidada**. Todo el contenido debe tener un objetivo claro evitando
añadir "relleno". El texto debe estar justificado. Es posible copiar textos de otros autores de
forma ocasional siempre y cuando se enmarque el texto entre comillas, con letra cursiva, y se
indique el autor y la referencia a la fuente (ver Apartado 12).

## 3 Resumen

El resumen es probablemente la parte más importante de la documentación. Será el primer
contacto del lector con el proyecto y en el que se basará gran parte de su opinión sobre el mismo.
Aunque resulta útil redactar un borrador en las fases iniciales del proyecto, se recomienda
elaborar la versión definitiva una vez finalizado, para reflejar con mayor precisión el resultado. En
algunos casos, puede haber limitaciones de espacio, pero lo más habitual es que el resumen
ocupe aproximadamente una página.

Independientemente del enfoque utilizado y su extensión, el resumen debería contestar a cuatro
preguntas clave: **1) ¿cuál es el problema que se ha abordado? 2) ¿por qué es un problema
relevante? 3) ¿cuál es la solución propuesta?, y 4) ¿por qué es una buena solución?** El resumen
debería dar respuesta a estas preguntas de forma clara y directa. Suele ser buena idea mencionar
las tecnologías utilizadas y la metodología de desarrollo, así como cualquier aspecto diferenciador
del proyecto: enfoque social, validación con usuarios reales, automatización de pruebas, etc.

En ocasiones se suele recomendar el uso de un resumen estructurado que cubra aspectos
específicos. Por ejemplo, es habitual ver resúmenes estructurados en **contexto, objetivo, método,
resultados y conclusiones**.


## 4 Motivación

El capítulo de introducción o motivación debe describir el contexto del proyecto de forma tan
detallada como sea posible utilizando referencias bibliográficas, notas de prensa, imágenes, etc.
Por ejemplo, supongamos que el objetivo del proyecto es desarrollar una aplicación móvil para
gestionar tickets de compra digitales y evitar el gasto de papel. El desarrollo del contexto podría
incluir, por ejemplo, datos o estimaciones sobre el consumo de papel que suponen los tickets
tradicionales, relación con los Objetivos de Desarrollo Sostenible o los planes públicos de
transformación digital.

Este capítulo debería incluir también una descripción detallada del problema explicando por qué
se trata de un problema relevante, así como de la solución propuesta y su relevancia dentro del
contexto presentado.

Salvo casos excepcionales, será habitual que existan aplicaciones similares a la que se va a
desarrollar en el proyecto. En tal caso, es recomendable incluir una sección de **"soluciones
existentes"** describiendo las aplicaciones relacionadas y cómo se diferencian del producto que se
va a desarrollar en el proyecto, destacando los aspectos diferenciadores del mismo. En este
apartado suele resultar útil incluir una tabla comparativa.

## 5 Planificación

El proyecto debe incluir una **planificación temporal y de costes** aplicando los conocimientos
adquiridos en el grado. La planificación temporal debe realizarse teniendo en cuenta el número
de horas de proyecto esperados para completar el TfG por normativa. En el momento de escribir
este documento, esto se corresponde con 300h en grado y 450 h en doble grado. Es importante
identificar y describir los hitos principales del proyecto, abarcando no solo tareas de desarrollo,
sino también aquellas relacionadas con investigación, documentación, elaboración de manuales
y preparación de la presentación, entre otras.

La planificación de costes debe tener en cuenta los costes de personal y de material. Es
recomendable incluir un porcentaje para contingencias y otro de beneficios.

El proyecto debe incluir un **análisis detallado de la desviación** con respecto a la planificación inicial
tanto en tiempo como en coste. Este análisis puede incluirse en el mismo capítulo o en un capítulo
independiente. Es muy recomendable utilizar herramientas de monitorización de tiempo como
[Clockify](https://clockify.me/) o similar y adjuntar los informes generados como anexo para justificar el tiempo invertido
en las distintas tareas. Es normal, incluso esperado, que se hayan producido pequeñas
desviaciones al tratarse de uno de los primeros proyectos desarrollados por el estudiante. En caso
de existir, las desviaciones deben ser siempre positivas, es decir, en ningún caso se debe invertir
un número de horas inferior al requerido por la normativa. Por último, es recomendable que las
potenciales desviaciones vayan acompañadas de una serie de **lecciones aprendidas**.

## 6 Metodología

El proyecto debe describir en detalle la metodología empleada. En el caso de proyectos de
desarrollo es habitual el uso de metodologías ágiles como Scrum. En tal caso, es necesario
describir la metodología utilizada y como se ha seguido en el contexto del proyecto: número de
iteraciones, duración de las iteracciones, roles, etc.

De igual forma, deben describirse las **herramientas** que se han utilizado para la gestión del
proyecto utilizando la metodología indicada. Por ejemplo, en el caso de una metodología ágil, es
posible utilizar herramientas como [GitHub Project](https://github.com/), [Jira](https://www.atlassian.com/es/software/jira), y/o [Trello](https://trello.com/), por ejemplo.


## 7 Ecosistema de desarrollo

El proyecto debe incluir una descripción detallada del ecosistema de desarrollo, incluyendo los
lenguajes de programación y las herramientas empleadas para la **implementación** (ej. Python), la
**documentación** (ej. Overleaf) y la **gestión del proyecto** (ej. Zenhub). También debe especificarse
la política de gestión del código fuente, estrategia de integración continua, despliegue y el uso de
asistentes de Inteligencia Artificial (ver Apartado 13 ), por ejemplo. Cada uno de estos puntos debe
ir acompañado de una breve explicación que permita al lector comprender cómo se ha
desarrollado el proyecto en la práctica. No se deben incluir datos irrelevantes como los logos de
las herramientas.

## 8 Requisitos

El proyecto debe incluir una descripción de los objetivos del sistema y sus requisitos incluyendo,
al menos, **requisitos funcionales, requisitos de información y requisitos no funcionales**. Es muy
recomendable que los requisitos vayan acompañados de criterios de aceptación, que
posteriormente deberán documentarse con las correspondientes pruebas de aceptación. Se debe
prestar especial atención a la descripción de los requisitos no funcionales para que sean medibles.
En función de las características del proyecto, opcionalmente, se pueden incluir otro tipo de
artefactos como un modelo conceptual para representar los requisitos de información y detectar
posibles inconsistencias o un modelo de proceso para poder entender mejor el dominio del
problema. Junto a los requisitos se deben incluir prototipos de interfaz usuario, incluyendo
descripciones textuales detalladas e indicando el software utilizado para su diseño (ej. [figma](https://www.figma.com/)).

## 9 Diseño

El apartado de diseño debe incluir una descripción general de la arquitectura, por ejemplo,
utilizando un diagrama de bloques informal o similar. Una vez presentada de forma general se
debe proporcionar información más específica a través de una descripción de las **vistas más
relevantes**. Se recomienda incluir una vista funcional o lógica (ej. a través de un diagrama UML
de componentes), una vista de despliegue (ej. diagrama UML de despliegue) y una vista de datos
(ej. diagrama UML de clases con perfil de datos). Opcionalmente, se pueden incluir otro tipo de
vistas como una vista de contexto o una vista de comportamiento (ej. usando un diagrama UML
de secuencia).

## 10 Implementación

La documentación debe hacer referencia a los detalles de implementación más relevantes. Es
recomendable utilizar listados de código cuando sea necesario, pero no se debe abusar de ellos.
En caso de incluirlos, es recomendable que los listados tengan fondo blanco y que las líneas estén
numeradas para poder hacer referencias a ellas desde el texto.

## 11 Pruebas

La realización y documentación de pruebas es un requisito imprescindible. Debe quedar claro qué
**tipo de pruebas** se han realizado (unitarias, integración, sistema, API, GUI, etc.) y cuántas se han
realizado documentando, al menos, las más relevantes (ej. pruebas de aceptación). Es muy
recomendable automatizar al menos un subconjunto de las pruebas. En tal caso, debe quedar
claro cuántas se han automatizado, cómo se ha realizado dicha automatización y con qué
herramientas. También es aconsejable **incluir métricas** que permitan valorar la adecuación de las
pruebas, como el nivel de cobertura alcanzado.


En el caso de que no se haya podido automatizar ninguna de las pruebas, por ejemplo, en
dominios complejos como chatbots, es recomendable **documentar las pruebas** manuales más
significativas e incluir capturas o enlaces a vídeos ilustrando la realización de la prueba.

Es conveniente utilizar **sistemas de integración continua** que permitan la ejecución automática
de las pruebas y/o análisis estático del código fuente al realizar cambios en el repositorio. En tal
caso, se debe documentar las herramientas utilizadas (ej. GitHub Actions) y la estrategia
implementada.

## 12 Referencias

Se deben añadir referencias a las fuentes bibliográficas utilizadas usando un estilo uniforme, por
ejemplo, números entre corchetes (IEEE), ej.: "Drupal [2,4,6] es un framework para..." Todas las
referencias (libros, enlaces, etc.) deben ser debidamente detalladas en la sección de bibliografía,
al final del documento. Para la gestión de las referencias es recomendable utilizar herramientas
como [Zotero](https://www.zotero.org/) o [Mendeley](https://www.mendeley.com). Ambas herramientas tienen conectores para Microsoft Word y
permiten exportar las referencias en formato bibtex para su uso en documentos LaTeX.

En el caso de figuras tomadas de otras fuentes, es necesario indicar la referencia en el pie de
figura, ej. "Metodología Scrum [5]".

## 13 Uso de Inteligencia Artificial

El uso de herramientas de Inteligencia Artificial (IA) en proyectos académicos es un tema
complejo para el cual aún no existen directrices ampliamente aceptadas. En el momento de
redactar este documento, en línea con las guías éticas de editoriales como [Elsevier](https://www.elsevier.com/about/policies-and-standards/the-use-of-generative-ai-and-ai-assisted-technologies-in-writing-for-elsevier) y [ACM](https://www.acm.org/publications/policies/frequently-asked-questions), su uso
se considera admisible siempre que se realice de forma **limitada, transparente y responsable**. En
particular, se deben seguir las siguientes recomendaciones:

- El uso de la IA debe realizarse siempre para **mejorar el contenido previamente redactado**
    por el estudiante, pero nunca para generar contenido desde cero. Se recomienda que su
    uso se limite a las partes más relevantes del documento.
- **No se debe confiar en los resultados** proporcionados por la herramienta. Si la
    herramienta proporciona un resultado como una cifra, un dato o la referencia a un
    artículo, se debe asumir que es incorrecto hasta verificarlo con otra fuente confiable.
- Se debe **indicar claramente las herramientas utilizadas** y para qué, de manera que se
    puedan entender los resultados y el alcance de la contribución del estudiante.

## 14 Video demostración

Se recomienda la creación de un vídeo demo ilustrando el producto desarrollado. En el momento
de escribir este documento, este vídeo es un requisito obligatorio para la entrega del TfG en la
ETSII de Sevilla y debe tener una duración máxima de tres minutos.

El vídeo debe cubrir las funcionalidades más importantes de la aplicación y debe estar explicado
por el propio estudiante cuya voz se escuchará de fondo. **La calidad del vídeo y del audio son
fundamentales**. Se recomienda el uso de un micrófono dedicado. Si se trata de una aplicación
grande en la que se desea mostrar mucha funcionalidad, es recomendable acelerar un poco el
vídeo (nunca la voz).

Todos los datos que aparezcan durante la demostración deben ser realistas.


## 15 Presentación

Según la normativa vigente, el proyecto debe ser expuesto ante un tribunal compuesto por al
menos dos profesores, en una presentación oral con una duración máxima de 15 minutos. A
continuación, el tribunal formulará comentarios y preguntas relacionadas con el trabajo
realizado. Para ello, el estudiante deberá preparar y enviar con antelación una presentación,
normalmente en formato Powerpoint.

Se recomienda utilizar una plantilla con **fondo blanco** lo más limpia posible y usar formato 4:3 (el
formato panorámico no se ve bien en pantallas pequeñas). Se debe **utilizar la menor cantidad de
texto posible y usar imágenes de muy buena calidad**.

Es conveniente comenzar siempre la presentación explicando de forma muy breve el problema
abordado y el resultado del proyecto. Esto permite que los miembros del tribunal puedan tener
una idea clara del proyecto realizado sin tener que esperar hasta el final de la exposición.

Como material de referencia, se recomienda la lectura de los libros [PresentationZen](https://amzn.eu/d/2wav8R1), de Garr
Reynolds y/o [Slide:ology](https://amzn.eu/d/fqfC9r4), de Nancy Duarte (disponible online en la [biblioteca de la US](https://fama.us.es/)).


