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

El sistema diseñado para Altertex implementa una arquitectura hexagonal con el objetivo de separar los módulos y dividir el sistema en partes donde cada una tiene una única responsabilidad. Esta separación facilita significativamente el mantenimiento, las pruebas y la comprensión del código.

Inicialmente, propuse la implementación de este patrón arquitectónico para lograr una alta modularidad y reutilización de los módulos. Esta decisión se fundamentó en uno de los requerimientos no funcionales clave que especificaba la necesidad de escalabilidad del sistema, anticipando su uso por miles de usuarios. Además, Altertex tiene planes futuros para integrar a todos sus clientes, actualmente gestionados en sistemas separados, dentro de la aplicación que mi equipo y yo estamos desarrollando.

Esta decisión agilizó considerablemente el diseño de componentes y el desarrollo del sistema. La arquitectura modular simplificó la creación de los diagramas de secuencia, ya que cada componente se encarga de una única tarea bien definida. Los diagramas de secuencia, a su vez, facilitan la refactorización del código de forma más eficiente, permitiendo el análisis de partes modulares sin generar interferencias con otros componentes. Esto promueve una alta reusabilidad de componentes, alta cohesión y bajo acoplamiento.

La documentación de los componentes mantiene una trazabilidad clara entre el diseño y el desarrollo, lo que contribuye a una mejor comprensión de la arquitectura, incluso durante la implementación de los componentes.

El diseño efectivo de los diagramas de secuencia requiere una comprensión profunda de la arquitectura del proyecto y la justificación de cada interacción modelada. La creación de estos diagramas se alinea con estándares internacionales como:

* UML (Unified Modeling Language) - ISO/IEC 19505: Los diagramas de secuencia son un elemento central de UML, el estándar internacional para el modelado de sistemas de software. Su uso asegura una representación visual clara y estandarizada de las interacciones entre componentes a lo largo del tiempo.
* Las mejores prácticas de la industria en diseño de software también recomiendan el uso de diagramas de secuencia como una herramienta eficaz para comunicar y validar la interacción entre componentes, especialmente en arquitecturas modulares como la hexagonal, donde las responsabilidades están claramente delimitadas.

Desde la perspectiva de QA, esta claridad en el diseño es esencial para poder asegurar la calidad del proyecto. La creación de estos diagramas se alinea con estándares internacionales que proporcionan herramientas para describir el comportamiento y la estructura del sistema.

## Evidencias que respaldan la competencia

| Descripción de la evidencia                           | Enlace a la evidencia                                                                                             |
| ------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| Diagrama de secuencia de Consultar Grupos de Empleados | [Diagrama de Secuencia](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/requisitos/RF22) |
| Diagrama de secuencia de Consultar Lista de Empleados  | [Diagrama de Secuencia](https://codeandco-wiki.netlify.app/docs/proyectos/textiles/documentacion/requisitos/RF17) |

## Análisis del nivel de la competencia

[Análisis de Autoevaluación: STC0203 Diseño de componentes de software](/docs/STC0203/Analisis)

