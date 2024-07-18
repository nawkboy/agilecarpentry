---
title: Guía Scrum (versión LeSS)
image: /assets/images/scrum_guide/overview.png
author: James
layout: book
sitemap: false
noindex: true
---

<div style="text-align: right; font-size: smaller;">
  Descargue el <a target="_blank" href="https://less.works/scrum-guide/scrum-guide.pdf">PDF en inglés</a>
</div>

<center style="color: #1997C0;">Craig Larman & Bas Vodde</center>
<center style="color: #1997C0;">(original de Ken Schwaber y Jeff Sutherland)</center>
<center style="color: #1997C0;">julio 2024</center>
<center style="color: #1997C0;">Traducción al español de James Carpenter</center>


## Propósito de la Guía Scrum

Scrum es un marco de trabajo para desarrollar, entregar y mantener productos complejos. Esta Guía contiene la definición de Scrum. Esta definición consiste en los roles, eventos y artefactos
de Scrum y las reglas que los relacionan. Cada elemento del marco cumple un propósito específico que es esencial para el valor general y los resultados obtenidos con Scrum. Cambiar el diseño o las ideas básicas de Scrum, dejar fuera los elementos, o no seguir las reglas de Scrum, cubre los problemas y limita los beneficios de Scrum, potencialmente incluso haciéndolo inútil.

Ken Schwaber y Jeff Sutherland lideran el desarrollo del marco Scrum.

LeSS (_Large-Scale Scrum_) es un sistema organizativo que evolucionó como resultado de la aplicación de Scrum al desarrollo de productos de *múltiple equipos*. LeSS está definido por las Reglas de LeSS (_LeSS-Rules_). Las Reglas de LeSS (_LeSS-Rules_) asumen estructuras de Scrum dentro de los equipos y conceptos de Scrum en todo el nivel del producto (como se define en esta guía).

¿Por qué esta actualización de la Guía? Las últimas versiones de Scrum y LeSS han evolucionado en paralelo, lo que ha llevado a que el supuesto Scrum en *Scrum* a gran escala sea una combinación de diferentes versiones de Scrum, creando inconsistencia y potencialmente una organización más complicada y menos adaptable en un situación de múltiples equipos.

Esta versión de la Guía describe Scrum tal como se asume en LeSS. Craig Larman y Bas Vodde desarrollaron LeSS y esta versión de la Guía basada en la [Guía Scrum de Ken Schwaber] (https://scrumguides.org/).

Esta publicación se ofrece bajo la licencia Attribution Share-Alike de Creative Commons, accesible en [https://creativecommons.org/licenses/by-sa/4.0/legalcode](https://creativecommons.org/licenses/by -sa/4.0/legalcode) y también se describe en forma resumida en [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/) . Al utilizar esta Guía Scrum, usted reconoce y acepta que ha leído y acepta regirse por los términos de la licencia Attribution Share-Alike de Creative Commons.

## Definición de Scrum

Scrum es un marco liviano que ayuda a las organizaciones a entregar de manera productiva y creativa un producto del mayor valor posible que aborde problemas adaptativos complejos.

En pocas palabras, Scrum requiere:
1. Un Propietario del Producto (_Product Owner_) ordena el trabajo de un problema complejo en un _Product Backlog_.
2. El Equipo (_Team_) convierte una selección de estas ideas en un valioso Incremento (_Increment_) de producto.
3. El Equipo (_Team_), el Propietario del Producto (_Product Owner_) y sus partes interesadas (_stakeholders_) inspeccionan los resultados y realizan los ajustes necesarios para el próximo Sprint.
4. Repetir

El marco Scrum está deliberadamente incompleto. Proporciona un caparazón que requiere la inteligencia colectiva de las personas que lo utilizan para completarlo. Hace transparente la eficacia relativa de la gestión, el entorno y las técnicas de trabajo actuales, de modo que la mejora continua del producto, el equipo y el entorno de trabajo puede pasar.

Scrum es simple. En lugar de proporcionar a las personas instrucciones detalladas, las Reglas de Scrum unen los roles, eventos y artefactos, gobernando las relaciones y la interacción entre ellos. Las reglas de Scrum se describen a lo largo del cuerpo de este documento.

## Teoría del Scrum

Scrum se basa en el empirismo. El empirismo afirma que el conocimiento proviene de la experiencia y de la toma de decisiones basadas en lo observado. Scrum emplea un enfoque iterativo e incremental para optimizar la adaptabilidad y exponer los riesgos de manera temprana.

Tres pilares sostienen el empirismo: transparencia, inspección y adaptación.

### Transparencia 

Scrum permite y requiere transparencia. Permite la transparencia al definir puntos de inspección y adaptación. Pero requiere que el proceso y el producto emergentes sean transparentes tanto para quienes realizan el trabajo como para quienes reciben el producto. La transparencia permite la inspección. La inspección sin transparencia es engañosa y derrochadora.

### Inspección

El progreso y el proceso deben inspeccionarse con frecuencia y diligencia para descubrir mejoras potenciales y nuevas oportunidades para aumentar la entrega de valor, la adaptabilidad, la eficacia y la satisfacción laboral. Para ayudar con la inspección, Scrum proporciona cadencia en forma de sus cuatro eventos.

La inspección permite la adaptación. La inspección sin adaptación se considera inútil. Los eventos Scrum están diseñados para provocar cambios.

### Adaptación

Si se descubren mejoras potenciales o nuevas oportunidades, entonces se puede ajustar el proceso utilizado y/o el producto producido. El ajuste debe realizarse lo antes posible para maximizar la entrega de valor.

La adaptación se vuelve más difícil cuando las personas involucradas no están empoderadas ni son autogestionadas.

## Valores de Scrum (_Scrum Values_)

El uso exitoso de Scrum depende de que las personas se vuelvan más competentes en vivir cinco valores:

<center><b>Compromiso, Enfoque, Apertura, Respeto y Coraje</b></center>
<br>

El Equipo (_Team_) se compromete a mejorar continuamente y a apoyarse mutuamente. Su enfoque principal está en el trabajo en el Sprint para lograr el mejor progreso posible. El Equipo (_Team_), el Propietario del Producto (_Product Owner_) y sus partes interesadas (_stakeholders_) están abiertos al trabajo y los desafíos. Los miembros del equipo se respetan entre sí por ser personas capaces e independientes, y como tales son respetados por las personas con las que trabajan. Los miembros del Equipo (_Team_) tienen el coraje de hacer lo correcto, de trabajar en problemas difíciles.

Estos valores dan dirección con respecto al trabajo, las acciones y el comportamiento. Las decisiones que se toman, los pasos dados y la forma en que se utiliza Scrum deben reforzar estos valores, no disminuirlos ni socavarlos. Cuando estos valores son encarnados por el Equipo (_Team_) y las personas con las que trabajan, los pilares empíricos de Scrum de transparencia, inspección y adaptación cobran vida generando confianza.


## Roles de Scrum (_Scrum Roles_)

Scrum consta de un Scrum Master (_Scrum Master_), un Propietario del Producto (Product Owner) y un Equipo (_Team_), todos enfocados en la Visión del Producto (_Product Vision_).

El equipo (_Team_) es lo suficientemente pequeño como para seguir siendo ágil y lo suficientemente grande como para completar un trabajo importante dentro de un Sprint, generalmente de 10 personas o menos. En general, hemos descubierto que los equipos más pequeños se comunican mejor y son más productivos. Si el equipo (_Team_) se vuelve demasiado grande, deberían considerar reorganizarse en varios equipos cohesionados, cada uno centrado en el mismo producto. Por lo tanto, deben compartir la misma Visión del Producto (_Product Vision_), Pila del Producto (_Product Backlog_) y Propietario del Producto (_Product Owner_).

El Equipo (_Team_) y el Propietario del Producto (_Product Owner_) son responsables de todas las actividades relacionadas con el producto, desde la colaboración de las partes interesadas (_stakeholders_), la verificación, el mantenimiento, la operación, la experimentación, la investigación y el desarrollo, y cualquier otra cosa que pueda ser necesaria para crear el Producto. Están estructurados y facultados por la organización para gestionar su propio trabajo. Trabajar en Sprints a un ritmo sostenible mejora la concentración y la coherencia.

### Equipo (_Team_)

El Equipo (_Team_) está formado por personas que están comprometidas a crear cualquier aspecto de un Incremento de Producto (_Product Increment_) utilizable en cada Sprint.

El Equipo (_Team_) tiene las siguientes características:

* El Equipo (_Team_) es autogestionado, lo que significa que decide internamente quién hace qué, cuándo y cómo; son responsables de monitorear y gestionar el proceso y el progreso.
* El Equipo (_Team_) es multifuncional, los miembros del Equipo (_Team_) tienen o pueden adquirir todas las habilidades necesarias para crear un Incremento de Producto (_Product Increment_).
* El Equipo (_Team_) no tiene subequipos relacionados con temas como testing, arquitectura, operaciones, UX o análisis de negocio.
* Los miembros del Equipo (_Team_) pueden tener habilidades y áreas de enfoque especializadas, pero la responsabilidad pertenece al Equipo (_Team_) en su conjunto.
* El Equipo (_Team_) no reconoce títulos o roles que limiten la responsabilidad de los miembros del Equipo (_Team_).

Las habilidades específicas que necesitan los miembros del Equipo (_Team_) suelen ser amplias y variarán según el ámbito de trabajo. Sin embargo, los miembros del Equipo (_Team_) siempre son responsables de:

* Crear un plan para el Sprint (_Sprint_), el Pila del Sprint (_Sprint Backlog_);
* Inculcar calidad adhiriéndose a una Definición de Hecho (_Definition of Done_);
* Adaptar su plan cada día hacia el Meta de Sprint (_Sprint Goal_); y,
* Responsabilizarnos unos a otros como profesionales.

### Propietario del Producto (_Product Owner_)

El Propietario del Producto (_Product Owner_) es responsable de maximizar el valor del producto resultante del trabajo del Equipo (_Team_). La forma en que se hace esto puede variar ampliamente entre organizaciones.
El Propietario del Producto (_Product Owner_) también es responsable de la gestión eficaz del Pila del Producto (_Product Backlog_), que incluye:

* Desarrollar y comunicar explícitamente la Visión del Producto (_Product Vision_);
* Agregar elementos del Pila del Producto (_Product Backlog_) y comunicar claramente cómo logran la Visión del Producto (_Product Vision_);
* Ordenar elementos de la Pila del Producto (_Product Backlog_); y,
* Garantizar que la Pila del Producto (_Product Backlog_) sea transparente y comprendido.

El Propietario del Producto (_Product Owner_) puede realizar el trabajo anterior o puede delegar la responsabilidad a otros. De todos modos, el Propietario del Producto (_Product Owner_) sigue siendo responsable.

Para que los Propietarios del Productos (_Product Owners_) tengan éxito, toda la organización debe respetar sus decisiones. Estas decisiones son transparentes en el contenido y ordenamiento del Pila del Producto (_Product Backlog_), y a través del Incremento (_Increment_) inspeccionable en el Revisión del Sprint (_Sprint Review_).

El Propietario del Producto (_Product Owner_) es una persona, no un comité. El Propietario del Producto (_Product Owner_) puede representar las necesidades de muchas partes interesadas (_stakeholders_) en el Pila del Producto (_Product Backlog_). Aquellos que quieran cambiar el Pila del Producto (_Product Backlog_) pueden hacerlo intentando convencer al Propietario del Producto (_Product Owner_).

### El Scrum Master (_Scrum Master_)

El Scrum Master es responsable de establecer Scrum como se define en la Guía Scrum (_Scrum Guide_). Lo hacen ayudando a todos a comprender la teoría y la práctica de Scrum.

El Scrum Master es responsable de que el Equipo (_Team_) y el Propietario del Producto (_Product Owner_) funcionen bien, y de que la organización comprenda Scrum y lo utilice para obtener los beneficios de la entrega de valor y la adaptabilidad. Lo hacen apoyando la mejora.

Los Scrum Masters son verdaderos líderes que sirven al Equipo (_Team_), al Propietario del Producto (_Product Owner_) y a la organización en general. El Scrum Master sirve al Equipo (_Team_) de varias maneras, incluyendo:

* Entrenar a los miembros del Equipo (_Team_) en autogestión y multifuncionalidad;
* Ayudar al Equipo (_Team_) a concentrarse en crear Incrementos (_Increments_) de alto valor que cumplan con la Definición de Hecho (_Definition of Done_);
* Provocar la eliminación de impedimentos al progreso del Equipo (_Team_); y,
* Garantizar que todos los eventos de Scrum se lleven a cabo y sean positivos, productivos y se mantengan dentro del plazo establecido.

El Scrum Master sirve al Propietario del Producto (_Product Owner_) de varias maneras, que incluyen:

* Ayudar a encontrar técnicas para la definición efectiva de la Visión del Producto (_Product Vision_) y la gestión del Pila del Producto (_Product Backlog_);
* Ayudar al Propietario del Producto (_Product Owner_) y al Equipo (_Team_) a comprender la necesidad de elementos claros y concisos del Pila del Producto (_Product Backlog_);
* Ayudar a establecer una planificación empírica de productos para un entorno complejo; y,
* Facilitar la colaboración de las partes interesadas (_stakeholders_) según se solicite o sea necesario.

El Scrum Master sirve a la organización de varias maneras, que incluyen:

* Liderar, capacitar y asesorar a la organización en su adopción de Scrum;
* Planificar y asesorar adopciones de Scrum dentro de la organización;
* Ayudar a los empleados y partes interesadas (_stakeholders_) a comprender y promulgar un enfoque empírico para trabajos complejos; y,
* Eliminar barreras entre las partes interesadas (_stakeholders_) y el Equipo (_Team_) y el Propietario del Producto (_Product Owner_).

## El Sprint (_Sprint_)

Los Sprints son el corazón de Scrum, donde las ideas se convierten en valor.
Tienen una duración fija de un mes o menos para crear coherencia. Un nuevo Sprint comienza inmediatamente después de la conclusión del Sprint anterior.

Todo el trabajo necesario para lograr la Visión del Producto (_Product Vision_), incluida la Planificación del Sprint (_Sprint Planning_), los Scrums Diarios (_Daily Scrums_), la Revisión del Sprint (_Sprint Review_), la Retrospectiva del Sprint (_Sprint Retrospective_) y el Refinamiento del Pila del Producto (_Product Backlog Refinement_), se realizan dentro de los Sprints.

Durante el Sprint:

* No se realizan cambios que pongan en peligro la Meta de Sprint (_Sprint Goal_);
* La calidad no disminuye;
* El alcance puede aclararse y renegociarse con el Propietario del Producto (_Product Owner_) a medida que se aprenda más.

Los Sprints crean un ritmo y aseguran la inspección y adaptación del progreso hacia una Visión del Producto (_Product Vision_). Se pueden emplear Sprints más cortos para generar más ciclos de aprendizaje y limitar el riesgo de costo y esfuerzo a un período de tiempo más corto. Cada Sprint puede considerarse un proyecto corto.

Existen varias prácticas para pronosticar el progreso. Si bien a veces es necesario hacer pronósticos, las prácticas de pronóstico no reemplazan la importancia del empirismo. En entornos complejos, se desconoce qué sucederá. Sólo lo que ya ha sucedido puede utilizarse para la toma de decisiones con visión de futuro.

Un Sprint puede cancelarse si el objetivo del Sprint queda obsoleto. Sólo el Propietario del Producto (_Product Owner_) tiene la autoridad para cancelar el Sprint.

## Eventos Scrum (_Scrum Events_)

Cada evento en Scrum es una oportunidad formal para inspeccionar y adaptarse. Estos eventos están diseñados específicamente para permitir la transparencia requerida. No operar cualquier evento según lo prescrito da como resultado la pérdida de oportunidades para inspeccionar y adaptarse. Los eventos se utilizan en Scrum para crear regularidad y minimizar la necesidad de reuniones no definidas en Scrum. De manera óptima, todos los eventos se llevan a cabo al mismo tiempo y lugar para reducir la complejidad.

### Planificación de Sprints (_Sprint Planning_)

La Planificación del Sprint (_Sprint Planning_) inicia el Sprint estableciendo el trabajo que se realizará para el Sprint. Este plan resultante se crea mediante el trabajo colaborativo del Equipo (_Team_) y el Propietario del Producto (_Product Owner_). Es posible que se invite a otras personas a asistir a Planificación del Sprint (_Sprint Planning_) para brindar asesoramiento.

El Propietario del Producto (_Product Owner_) se asegura de que los asistentes estén preparados para discutir los elementos más importantes de la Pila del Producto (_Product Backlog_) y cómo ayudan a lograr la Visión del Producto (_Product Vision_).

Planificación del Sprint (_Sprint Planning_) aborda los siguientes temas:

**¿Por qué es valioso este Sprint?** — El Propietario del Producto (_Product Owner_) propone cómo el producto podría aumentar su valor y utilidad en el Sprint actual. Luego, el Equipo (_Team_) y el Propietario del Producto (_Product Owner_) colaboran para definir una Meta de Sprint (_Spring Goal_) que comunique por qué el Sprint es valioso para las partes interesadas (_stakeholders_) y cómo ayuda a lograr la Visión del Producto (_Product Vision_). La Meta de Sprint (_Spring Goal_) debe finalizarse antes del final de la Planificación del Sprint (_Sprint Planning_).

**¿Qué se puede hacer en este Sprint?**: a través de una discusión con el Propietario del Producto (_Product Owner_), el Equipo (_Team_) selecciona elementos de la parte superior del Pila del Producto (_Product Backlog_) para incluirlos en el Sprint actual. El Equipo (_Team_) puede refinar estos elementos durante este proceso.

**¿Cómo se realizará el trabajo elegido?**: Para cada elemento seleccionado del Pila del Producto (_Product Backlog_), el Equipo (_Team_) planifica el trabajo necesario para crear un Incremento (_Increment_) que cumpla con la Definición de Hecho (_Definition of Done_). Esto a menudo se hace descomponiendo los elementos del Pila del Producto (_Product Backlog_) en tareas más pequeñas de un día o menos. La forma en que se hace esto queda a discreción exclusiva del Equipo (_Team_).

El Meta de Sprint (_Sprint Goal_) es el único objetivo del Sprint. Proporciona flexibilidad en términos del trabajo exacto necesario para lograrlo. Si el trabajo resulta diferente a lo que esperaban, colaboran con el Propietario del Producto (_Product Owner_) para negociar el alcance de la Pila del Sprint (_Sprint Backlog_) dentro del Sprint sin afectar la Meta de Sprint (_Sprint Goal_). La Meta de Sprint (_Sprint Goal_) también crea coherencia y enfoque, animando al Equipo (_Team_) a trabajar en conjunto en lugar de en iniciativas separadas.

La Meta de Sprint (_Sprint Goal_), los elementos de la Pila del Producto (_Product Backlog_) seleccionados para el Sprint, más el plan para entregarlos, se denominan en conjunto Pila del Sprint (_Sprint Backlog_).

La Planificación del Sprint (_Sprint Planning_) tiene un límite de tiempo de un máximo de ocho horas para un Sprint de un mes. Para Sprints más cortos, el evento suele ser más corto.

### Scrum Diario (_Daily Scrum_)

El propósito del Scrum Diario (_Daily Scrum_) es inspeccionar el progreso hacia la Meta de Sprint (_Sprint Goal_) y adaptar la Pila del Sprint (_Sprint Backlog_) según sea necesario, ajustando el próximo trabajo planificado.

El Scrum Diario (_Daily Scrum_) es un evento de máximo 15 minutos para el Equipo (_Team_). Para reducir la complejidad, se lleva a cabo a la misma hora y lugar todos los días hábiles del Sprint.

El Equipo (_Team_) puede seleccionar cualquier estructura y técnica que desee, siempre y cuando su Scrum Diario (_Daily Scrum_) se centre en el progreso hacia la Meta de Sprint (_Sprint Goal_) y produzca un plan viable para las próximas 24 horas de trabajo. Esto crea concentración y mejora la autogestión.

Los Scrums Diarios (_Daily Scrums_) mejoran las comunicaciones, identifican impedimentos, promueven una toma rápida de decisiones y, en consecuencia, eliminan la necesidad de realizar otras reuniones.

El Scrum Diario (_Daily Scrum_) no es el único momento en el que al Equipo (_Team_) se le permite ajustar su plan. A menudo se reúnen a lo largo del día para discusiones más detalladas sobre cómo adaptar o replanificar el resto del trabajo del Sprint.

### Revisión de Sprint (_Sprint Review_)

El propósito de la Revisión del Sprint (_Sprint Review_) es inspeccionar el resultado del Sprint y determinar adaptaciones futuras. El Equipo (_Team_) y el Propietario del Producto (_Product Owner_) presentan el Incremento del Producto (_Product Increment_) a las partes interesadas (_stakeholders_) clave y se analiza el progreso hacia la Visión del Producto (_Product Vision_).

Durante el evento, el Equipo (_Team_), el Propietario del Producto (_Product Owner_) y las partes interesadas (_stakeholders_) revisan lo que se logró en el Sprint y lo que ha cambiado en su entorno. A partir de esta información, los asistentes colaboran sobre qué hacer a continuación. La Pila del Producto (_Product Backlog_) también puede ajustarse para aprovechar nuevas oportunidades. La Revisión del Sprint (_Sprint Review_) es una sesión de trabajo y se deben evitar solo presentaciones.

La Revisión del Sprint (_Sprint Review_) es el penúltimo evento del Sprint y tiene un límite de tiempo de un máximo de cuatro horas para un Sprint de un mes. Para Sprints más cortos, el evento suele ser más corto.

### Retrospectiva de Sprint (_Sprint Retrospective_)

El propósito de la Retrospectiva de Sprint (_Sprint Retrospective_) es planificar formas de aumentar la calidad, la efectividad y el disfrute.

El Equipo (_Team_) inspecciona cómo fue el último Sprint con respecto a personas, interacciones, procesos, herramientas y su Definición de Hecho (_Definition of Done_). Los elementos inspeccionados a menudo varían según el ámbito de trabajo. Se identifican las suposiciones que los llevaron por mal camino y se exploran sus orígenes. El Equipo (_Team_) analiza qué salió bien durante el Sprint, qué problemas encontró y cómo se resolvieron (o no) esos problemas.

El Equipo (_Team_) identifica los cambios más útiles para mejorar su efectividad. Las mejoras más impactantes se abordan lo antes posible. Incluso pueden agregarse a la Pila del Sprint (_Sprint Backlog_) para el próximo Sprint.

La Retrospectiva del Sprint (_Sprint Retrospective_) concluye el Sprint. Tiene un límite de tiempo de un máximo de tres horas para un Sprint de un mes. Para Sprints más cortos, el evento suele ser más corto.

### Refinamiento de la Pila del Productos (_Product Backlog Refinement_)

El propósito del Refinamiento de la Pila del Productos (_Product Backlog Refinement_) es garantizar que la Pila del Productos (_Product Backlog_) esté bien mantenido, preparado para la Planificación del Sprint (_Sprint Planning_) y alineado con la Visión del Producto (_Product Vision_). El refinamiento de la Pila del Productos (_Product Backlog_) se realiza como una actividad continua, parte de la Planificación del Sprint (_Sprint Planning_) o como un evento separado durante el Sprint.

Durante el Refinamiento del Product Backlog (_Product Backlog Refinement_), el Propietario del Producto (_Product Owner_) refuerza la Visión del Producto (_Product Vision_). El Equipo (_Team_) y el Propietario del Producto (_Product Owner_), junto con las partes interesadas (_stakeholders_) clave cuando sea necesario, (1) aclararán los Elementos de la Pila del Producto (_Product Backlog Items_) que probablemente se seleccionarán para los próximos Sprints, (2) dividirán los Elementos de la Pila del Producto (_Product Backlog Items_) que sean demasiado grandes y se considerarán relativamente pronto, y (3) estimar el tamaño de los nuevos Elementos de la Pila del Producto (_Product Backlog Items_) o reestimar los existentes, cuando sea necesario.

El Refinamiento del Product Backlog (_Product Backlog Refinement_) suele tomar un máximo del 10% del Sprint.

## Artefactos Scrum (_Scrum Artifacts_)

Los artefactos definidos por Scrum están diseñados específicamente para maximizar la transparencia de la información clave para que todos tengan la misma comprensión del artefacto.

### Pila del Producto (_Product Backlog_)

El Pila del Producto (_Product Backlog_) es una lista emergente y ordenada de Elementos de la Pila del Productos (_Product Backlog Items_), que describen todo lo que se necesita para evolucionar el producto. Es la única fuente de trabajo realizada por el Equipo (_Team_).

Una Pila del Producto (_Product Backlog_) nunca está completo. Evoluciona a medida que evoluciona el producto y el entorno. La Pila del Producto (_Product Backlog_) es dinámico; cambia constantemente para identificar qué necesita el producto para ser apropiado, competitivo y útil.

Los Elementos de la Pila del Producto (_Product Backlog Items_) pueden tener atributos como descripción, tamaño y valor. El Equipo (_Team_) es responsable de las estimaciones. Los Elementos de la Pila del Producto (_Product Backlog Items_) que el Equipo (_Team_) puede seleccionar generalmente se han aclarado durante un Refinamiento de la Pila del Productos (_Product Backlog Refinement_) anterior.


### Pila del Sprint (_Sprint Backlog_)

La Pila del Sprint (_Sprint Backlog_) se compone de la Meta de Sprint (_Sprint Goal_) (por qué), el conjunto de Elementos de la Pila del Producto (_Product Backlog Items_) seleccionados para el Sprint (qué), así como un plan procesable para entregar el Incremento (_Increment_) (cómo).

La Pila del Sprint (_Sprint Backlog_) es un plan por y para el Equipo (_Team_). Es una imagen muy transparente y en tiempo real del trabajo que el Equipo (_Team_) planea realizar durante el Sprint para lograr la Meta de Sprint (_Sprint Goal_). En consecuencia, la Pila del Sprint (_Sprint Backlog_) se actualiza a lo largo del Sprint a medida que se aprende más. Debe tener suficientes detalles para que puedan inspeccionar su progreso en el Scrum Diario (_Daily Scrum_).

### Incremento (_Increment_)

Un Incremento (_Increment_) es el resultado del Sprint y es un trampolín concreto hacia el logro de la Visión del Producto (_Product Vision_). Cada Incremento (_Increment_) se suma a todos los Incrementos (_Increments_) anteriores y se verifica minuciosamente. Para proporcionar valor, el Incremento (_Increment_) debe ser utilizable.

## Definición de Hecho (_Definition of Done_)

La Definición de Hecho (_Definition of Done_) es un acuerdo entre el Propietario del Producto (_Product Owner_) y el Equipo (_Team_) sobre lo que se espera para que un Elemento del Pila del Producto (_Product Backlog Item_) sea declarado Hecho. Por lo general, describe qué criterios de calidad debe cumplir el Elemento de la Pila del Productos (_Product Backlog Item_).

La Definición de Hecho (_Definition of Done_) crea transparencia al brindarles a todos una comprensión compartida de qué trabajo se completó como parte del Incremento (_Increment_). Si un Elemento de la Pila del Productos (_Product Backlog Item_) no cumple con la Definición de Hecho (_Definition of Done_), no se puede publicar ni presentar en la Revisión del Sprint (_Sprint Review_). En cambio, regresa al Pila del Producto (_Product Backlog_) para su consideración futura.

Los miembros del Equipo (_Team_) deben cumplir con la Definición de Hecho (_Definition of Done_). Si varios Equipos (_Team_) están trabajando juntos en un producto, deben definir y cumplir mutuamente con la misma Definición de Hecho (_Definition of Done_).

## Nota Final

Scrum es gratuito y se ofrece en esta guía. El marco de Scrum, como se describe aquí, es inmutable. Si bien solo es posible implementar partes de Scrum, el resultado no es Scrum. Scrum existe sólo en su totalidad y funciona bien como contenedor para otras técnicas, metodologías y prácticas.

### Agradecimientos

#### Gente

De las miles de personas que han contribuido a Scrum, debemos destacar a aquellas que fueron fundamentales al principio: Jeff Sutherland trabajó con Jeff McKenna y John Scumniotales, y Ken Schwaber trabajó con Mike Smith y Chris Martin, y todos trabajaron juntos. Muchos otros contribuyeron en los años siguientes y sin su ayuda Scrum no sería refinado como lo es hoy.

#### Historial de la Guía Scrum

Ken Schwaber y Jeff Sutherland presentaron conjuntamente Scrum por primera vez en la Conferencia OOPSLA en 1995. Básicamente, documentó el aprendizaje que Ken y Jeff obtuvieron durante los años anteriores e hizo pública la primera definición formal de Scrum.

La Guía Scrum documenta Scrum desarrollado, evolucionado y sostenido durante más de 30 años por Jeff Sutherland y Ken Schwaber. Otras fuentes proporcionan patrones, procesos y conocimientos que complementan el marco de Scrum. Estos pueden aumentar la productividad, el valor, la creatividad y la satisfacción con los resultados.

La historia completa de Scrum se describe en otra parte. Para honrar los primeros lugares donde se probó y demostró, reconocemos a Individual Inc., Newspage, Fidelity Investments e IDX (ahora GE Medical).

Esta publicación se ofrece bajo la licencia Attribution Share-Alike de Creative Commons, accesible en [https://creativecommons.org/licenses/by-sa/4.0/legalcode](https://creativecommons.org/licenses/by -sa/4.0/legalcode) y también se describe en forma resumida en [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/) . Al utilizar esta Guía Scrum, usted reconoce y acepta que ha leído y acepta regirse por los términos de la licencia Attribution Share-Alike de Creative Commons.

Este documento es una adaptación de la Guía Scrum original de Ken Schwaber y Jeff Sutherland. Craig Larman y Bas Vodde realizaron cambios en el documento original en 2024, incluidas ediciones menores y resúmenes de cambios.

© 2024 Craig Larman y Bas Vodde

## Resumen de actualizaciones en la versión LeSS

Esta actualización de la Guía Scrum tiene como base la Guía Scrum 2020, aunque algunas partes se han tomado de la Guía Scrum 2017. Los cambios más importantes son:

* Se reintrodujo el producto en lugar de "trabajar para problemas complejos".
* Se eliminó el concepto de Equipo Scrum.
* Desarrolladores renombrados a Equipo.
* Se eliminó Sprint de Eventos y lo convirtió en una cosa separada.
* Se cambió el nombre de Objetivo del producto a Visión del Producto.
* Se eliminó la "Creación y comunicación de Elementos de Pila del Producto" de Gestión del Backlog en la sección Propietario del Producto.
* Se eliminó la terminología del Tema 1/2/3 y simplemente lo llamó por qué/qué/cómo.
* Se agregó un Refinamiento de la Pila de Productos a los eventos Scrum, pero se mencionó que se puede realizar como una actividad en lugar de un evento.
* Se eliminó el lenguaje de compromiso con los artefactos.
* Se movió la Meta de Sprint a un solo lugar, dentro de Sprint Planning.
* Introdujo la Definición de Hecho, no como compromiso sino como acuerdo.

