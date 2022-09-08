---
layout: post
title: Historias de Usuario
subtitle: Una forma de generar requisitos funcionales
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [scrum, agile]
---

Las historias de usuario son utilizadas en las metodologías de desarrollo ágiles para la especificación de requisitos. Van acompañadas de las conversaciones con los usuarios y de los criterios de aceptación. 

Puesto que las historias de usuario representan los requisitos que debe implementar un software, es fundamental que las personas responsables de su escritura sean estrictas, en términos de redacción y completitud de las historias.

Además, una mala redacción de las Historias de Usuario puede tener consecuencias nefastas sobre el desarrollo de un proyecto, como por ejemplo, realizar trabajo innecesario o lo que es peor: implementar funcionalidades que no cubren de una manera eficiente los requisitos expresados por los usuarios.

En consecuencia, esta guía pretende cubrir las dudas que puedan surgir a la hora de redactar correctamente una historia de usuario.

## Definición
Una historia de usuario es la forma de plasmar requisitos en las metodologías ágiles. Deben redactarse siguiendo un lenguaje coloquial, tratando de huir de tecnicismos y de usos excesivamente formales del lenguaje.

## Componentes de una historia
Una historia de usuario puede descomponerse siguiendo las tres “ces” (3Cs), que son Card, Conversation y Confirmation. Estas partes se corresponden con el enunciado, las conversaciones con los usuarios y los criterios de aceptación.

### Card – Enunciado
El enunciado consta de un título breve y conciso y de una breve descripción, que cumple con la construcción Como [usuario o rol] quiero [funcionalidad] para [lograr algo]. Por ejemplo:

|Título | Descripción  |
| :------ |:--- |
| Responder a comentarios | Como lector del blog, quiero responder a otros usuarios  para mantener el contacto con los demás usuarios del blog |

El enunciado responde a las siguientes preguntas: ¿Quién? ¿Qué? ¿Por qué?

### Conversation – conversación

En esta sección se aclaran los detalles de la historia. Es el resultado de una conversación con los usuarios solicitantes y permite al desarrollador acometer su implementación. Puede incluir documentos, diagramas, precondiciones, postcondiciones, flujos, excepciones, etc. Su intención es dar contexto.

### Confirmation – Criterios de aceptación

Definen los requerimientos del dueño de producto (Product Owner) sobre cómo debe comportarse el sistema ante distintos eventos. Permiten al desarrollador validar que la historia de usuario está correctamente implementada (cumple los criterios de aceptación) y por lo tanto puede darse por finalizada. 

Es uno de los aspectos a tener en cuenta para cumplir el acuerdo de Definition of Done y una de las partes más importantes de una historia de usuario. Además, puede tener relación directa con técnicas de desarrollo como BDD (Behavior Driven Development) con lo que es interesante que su redacción cumpla con ciertas reglas:

- Indicar un número de escenario
- Título del escenario: Describe el contexto del escenario que define un comportamiento. Por ejemplo, si se toma el ejemplo de búsquedas de productos por categoría, un posible ejemplo pudiera ser: Categoría sin productos asociados.
- Contexto: Proporciona mayor descripción sobre las condiciones que desencadenan el escenario.
- Evento: Representa la acción que el usuario ejecuta, en el contexto definido para el escenario.
- Resultado / Comportamiento esperado: Dado el contexto y la acción ejecutada por el usuario, la consecuencia es el comportamiento del sistema en esa situación.

Ejemplo: 
Escenario 1: En caso que exista una categoría sin productos asociados, cuando el cliente despliegue el listado de categorías para realizar su búsqueda, el sistema mostrará el siguiente texto al lado de la categoría “Actualmente no poseemos productos para esta categoría”.

## Características de una historia
Una historia de usuario debe cumplir (en la medida de lo posible) con los principios INVEST:
- **I**ndependientes entre sí, para poder llevarlas a cabo en el orden que más nos convenga según las prioridades que establezca el Product Owner.
- **N**egociables con el Product Owner para establecer los limites adecuados, la parte de conversación de una historia es esencial
- **V**alor para el usuario, el PARA es fundamental. Se ha de entender la funcionalidad siempre y la tiene que entender todo el Equipo de Desarrollo
- **E**stimable. El Equipo de Desarrollo que la vaya a recoger, debe ser capaz de estimar el esfuerzo que supone realizarla.
- **S**mall. De un tamaño que el equipo de desarrollo pueda asumir en un sprint. Y a ser posible que el equipo pueda asumir varias dentro del sprint
- **T**esteable. Para poder confirmar que está correctamente implementada. O dicho de otra forma con los Criterios de Aceptación establecidos.

## Estimación de historias

Este documento no es una guía de estimación de historias de usuario, pero sí que enumeramos una serie de puntos que se deben tener en cuenta a la hora de redactar las historias.
- Se puede indicar una estimación inicial (a alto nivel) de la historia, que posteriormente será cambiada por el equipo de desarrollo durante el sprint planning.
- La estimación final de una historia siempre es responsabilidad del equipo de desarrollo
- Se busca tener un backlog estimado de forma orientativa, para tener una línea base.
  - La línea base cambiará según al experiencia de los sucesivos sprints
  - Esta estimación puede realizare por comparación con otras historias similares ya finalizadas

## Refinamiento de historias de usuario
El Product Owner puede dedicar parte de su tiempo (en torno al 10%) a refinar las historias de usuario que aún no están comprometidas en un sprint. 

En ese tiempo, se puede estimar el esfuerzo, agregar detalles, revisar dependencias etc. Durante estas sesiones no se descomponen las historias en tareas, esa parte se realiza durante la preparación del sprint (Sprint Planning). 

En algunas ocasiones, el refinamiento de historias se realiza mediante una reunión a la que acuden los llamados “[tres amigos](https://www.agilealliance.org/glossary/three-amigos/)” , que son el Product Owner, los desarrolladores y testers. No es necesario limitar la reunión a tres personas, como en otras reuniones ágiles, si hay algún otro Stakeholder que es relevante para un incremento de valor, es interesante que acuda.




