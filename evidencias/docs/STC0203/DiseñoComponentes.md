---
sidebar_position: 1
title: Diseño de componentes de software
---
# Diseño de componentes de software


| Diseña componentes de software, a partir de requerimientos, con base en estándares internacionales. |
| :---------------------------------------------------------------------------------------------------- |

## Retroalimentación del profesor(a)

Por favor, agrega tus observaciones, sugerencias y comentarios sobre esta competencia en el siguiente enlace:  [Haz clic aquí para dejar tu retroalimentación](https://docs.google.com/document/d/1DS8nw5wONIA2Hsyyu9oGleLhGe4syc6xH5qRi6aSWro/edit?usp=sharing)

## Reflexión de mi estado actual en la competencia

Al inicio del semestre no sabía qué era un patrón de arquitectura y tenía la idea errónea de que un patrón de diseño como MVC era una arquitectura de software. Con el tiempo entendí que una arquitectura va mucho más allá de solo distribuir responsabilidades y su objetivo principal es permitir que el sistema cumpla con los requisitos funcionales y no funcionales.

Una arquitectura de software define cómo se organiza el sistema para asegurar requisitos no funcionales como rendimiento, seguridad, escalabilidad o disponibilidad. En una presentación del profesor Claud se mostraba una analogía útil. Así como el cuerpo humano tiene diferentes sistemas (nervioso, óseo, etc.), una arquitectura debe diseñarse considerando lo que se quiere lograr. No hay una arquitectura única o perfecta, todo depende de las necesidades específicas del sistema.

En el caso de Text&Lines, identificamos desde el principio que el socio formador necesitaba una solución tipo SaaS, ya que no contaba con infraestructura propia. También requería que el sistema tuviera buen rendimiento, disponibilidad, escalabilidad, portabilidad y seguridad.

Por eso, analizamos distintas opciones. Sabíamos que una arquitectura monolítica no era viable por sus limitaciones de escalabilidad (solo vertical). También descartamos microservicios porque, aunque resuelven muchos problemas, son costosos y complejos de implementar. Finalmente, nos decidimos por un patrón de arquitectura limpia, ya que ofrece modularidad, separación de responsabilidades, y permite escalar horizontalmente. También se consideró un patrón hexagonal porque en un inicio se pensaba integrar con sistemas externos como Mercado Pago, pero al final no fue necesario conectar múltiples interfaces.

El sistema diseñado para Altertex implementa un patrón de arquitectura limpia, cuyo objetivo principal es separar los módulos y dividir el sistema en componentes con responsabilidades únicas. Esta separación facilita el mantenimiento, las pruebas y la comprensión del código. Por ejemplo, en el frontend, los componentes obtienen los datos a través de los estados cuando el usuario interactúa, luego se valida la información mediante los casos de uso y las reglas de negocio en los hooks y finalmente se envía a las interfaces correspondientes de cada módulo.

El diagrama de arquitectura y los diagramas de paquetes reflejan cómo está organizado el sistema siguiendo el patrón de arquitectura limpia. Se puede observar cómo los distintos elementos del sistema siguen patrones de comportamiento bien definidos para cumplir con los principios de separación de responsabilidades.

Tenemos el frontend y el backend completamente separados, lo que permite escalar, mantener y probar cada parte por separado. En el frontend, por ejemplo, los componentes y hooks se conectan a través de repositorios a los casos de uso, y estos a su vez se comunican con las reglas de negocio. Esta estructura modular ayuda a que cualquier cambio en una parte no afecte negativamente a las demás.

En los diagramas también se nota cómo los adaptadores y modelos se usan para transformar los datos, manteniendo la independencia entre la lógica del negocio y los detalles de implementación. Eso permite sustituir fuentes de datos o proveedores de servicios (como Mercado Pago) sin tener que reescribir toda la lógica.

Todo esto demuestra que el sistema no solo tiene una arquitectura limpia bien implementada, sino también una visión clara de cómo adaptarse a cambios futuros con el menor impacto posible.

Esta decisión agilizó considerablemente el diseño de componentes y el desarrollo del sistema. La arquitectura modular simplificó la creación de los diagramas de secuencia, ya que cada componente se encarga de una única tarea bien definida. Los diagramas de secuencia, a su vez, facilitan la refactorización del código de forma más eficiente, permitiendo el análisis de partes modulares sin generar interferencias con otros componentes. Esto promueve una alta reusabilidad de componentes, alta cohesión y bajo acoplamiento.

La documentación de los componentes mantiene una trazabilidad clara entre el diseño y el desarrollo, lo que contribuye a una mejor comprensión de la arquitectura, incluso durante la implementación de los componentes.

El diseño efectivo de los diagramas de secuencia requiere una comprensión profunda de la arquitectura del proyecto y la justificación de cada interacción modelada. La creación de estos diagramas se alinea con estándares internacionales como:

* UML (Unified Modeling Language) - ISO/IEC 19505: Los diagramas de secuencia son un elemento central de UML, el estándar internacional para el modelado de sistemas de software. Su uso asegura una representación visual clara y estandarizada de las interacciones entre componentes a lo largo del tiempo.
* Las mejores prácticas de la industria en diseño de software también recomiendan el uso de diagramas de secuencia como una herramienta eficaz para comunicar y validar la interacción entre componentes, especialmente en arquitecturas modulares como la hexagonal, donde las responsabilidades están claramente delimitadas.

Si tuviera que evaluar lo que sabía al inicio del semestre y lo que sé ahora, puedo decir con seguridad que ahora comprendo mucho mejor la importancia de diseñar componentes que respondan a los requisitos no funcionales y a las reglas de negocio. Esto representa un gran avance, ya que al principio pensaba que un sistema podía simplemente cumplir con todo sin mucho análisis. Con el tiempo entendí que ignorar esos aspectos puede causar defectos de arquitectura que luego requieren muchas horas para ser corregidos.

Aún tengo dudas sobre si lo que se implementó fue lo mejor para el proyecto, pero algo que sí me queda claro es que lo único que puedo hacer es seguir leyendo, aprendiendo y desaprendiendo. Solo así podré mejorar mi forma de ver las cosas y comprender de manera más profunda lo que implica diseñar un buen sistema.

## Reflexión de Master Jedi en diseño de componentes de software

Un Master Jedi en diseño de componentes no se trata solo de seguir un estándar al pie de la letra, sino que es alguien que entiende para qué existen esos estándares y cuándo tiene sentido adaptarlos al contexto de un proyecto. No diseña solo para cumplir, diseña para que lo que construye sea útil y se alínea con los requerimientos del sistema.

Sabe que cada decisión arquitectónica tiene un costo, por eso las justifica con necesidades reales por lo que procura identificar los involucrados en el proyecto y evalúa cúal puede ser el mejor diseño de los componentes para satisfacer los requerimientos.

Por último, sabe que la fase de diseño es crítica en el proceso de ingeniería, porque un mal diseño puede convertirse en un problema enorme en el futuro, por lo que es importante acortar los cíclos de retroalimentación con los involucrados constantemente y validar sí lo que se está diseñando realmente satisface las necesidades y se encuentra dentro de los costos del proyecto.

## Evidencias que respaldan la competencia


| Descripción de la evidencia                           | Enlace a la evidencia                                                                                             |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| Diagrama de secuencia de Consultar Grupos de Empleados | [Diagrama de Secuencia](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/requisitos/RF22) |
| Diagrama de secuencia de Consultar Lista de Empleados  | [Diagrama de Secuencia](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/requisitos/RF17) |
| Diagrama de secuencia de Crear Producto                | [Diagrama de Secuencia](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/requisitos/RF26) |
| Modelo Relacional                                      | [MR](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/diagrama-mer)                       |
