---
sidebar_position: 2
title:Análisis de Autoevaluación: STC0203 Diseño de componentes de software
---
# Análisis de Autoevaluación: STC0203 Diseño de componentes de software

## Instrucciones

Marca con una X los elementos que cumples actualmente y completa las columnas de justificación y áreas de oportunidad para cada nivel. Debes evaluar cada nivel de forma secuencial: si no cumples completamente con un nivel, no puedes pasar al siguiente.

## Nivel 1: Incipiente (15%) - "No conoce la fuerza"


| Criterio                                                                             | Cumple (X) | Justificación                                                                     | Áreas de oportunidad |
| ------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------- | --------------------- |
| No he diseñado componentes de software basados en estándares internacionales       |            | He diseñado diagramas de secuencia usando UML e ISO/IEC 19505                     | —                    |
| No comprendo los principios básicos de arquitectura de software                     |            | Sugerí implementar el patrón arquitectonico hexagonal y comprendo su propósito | —                    |
| No he creado diagramas de paquetes ni de despliegue                                  | X          | En los diagramas de secuencia no se modelan carpetas                               | —                    |
| No conozco los patrones arquitectónicos para el desarrollo de software              |            | Conozco varios patrones arquitectónicos para el desarrollo de software.           | —                    |
| No he documentado componentes de software ni justificado decisiones arquitectónicas |            | La documentación y justificación están presentes en el proyecto                 | —                    |

**Evaluación nivel 1: No Superado**

## Nivel 2: Básico (70%) - "Padawan"


| Criterio                                                                    | Cumple (X) | Justificación                                                                   | Áreas de oportunidad                       |
| --------------------------------------------------------------------------- | ---------- | -------------------------------------------------------------------------------- | ------------------------------------------- |
| He diseñado al menos un componente con base en estándares internacionales | X          | Usé UML para diseñar diagramas de secuencia conforme a ISO/IEC 19505           | —                                          |
| Puedo explicar la arquitectura de mi proyecto, aunque con algunas omisiones | X          | Puedo explicar la arquitectura hexagonal y la separación de responsabilidades   | Profundizar en patrones de comportamiento.  |
| He creado y puedo explicar el diagrama de paquetes de mi proyecto           | X          | El diseño modular se representó a través de diagramas de paquetes             | Crear diagramas más detallados por módulo |
| He creado y puedo explicar el diagrama de despliegue de mi proyecto         |            | No aporté a la creación del diagrama de despliegue de mi proyecto.             | —                                          |
| Utilizo patrones arquitectónicos para lograr:                              | X          | Hexagonal para cohesión, reusabilidad y desacoplamiento                         | —                                          |
| - Reusabilidad de componentes                                               | X          | Cada componente tiene una responsabilidad única y puede reutilizarse            | —                                          |
| - Alta cohesión dentro de los componentes                                  | X          | La arquitectura asegura que cada módulo se enfoque en una tarea específica     | —                                          |
| - Bajo acoplamiento entre componentes                                       | X          | Las interfaces delimitan la comunicación entre módulos externos e internos     | —                                          |
| He documentado los componentes y patrones utilizados en mi proyecto         | X          | Se documentaron los componentes con trazabilidad entre diseño y desarrollo      | —                                          |
| Puedo justificar las decisiones arquitectónicas tomadas en mi proyecto     | X          | La elección de la arquitectura se fundamenta en los requisitos de escalabilidad | —                                          |

**Evaluación nivel 2: No Superado**

## Nivel 3: Sólido (85%) - "Jedi"


| Criterio                                                                                            | Cumple (X) | Justificación                                                               | Áreas de oportunidad                                |
| --------------------------------------------------------------------------------------------------- | ---------- | ---------------------------------------------------------------------------- | ---------------------------------------------------- |
| Participo activamente en el diseño de componentes de mi proyecto                                   | X          | Propuse y ayude a moldear la arquitectura y componentes del sistema Altertex | —                                                   |
| Aplico con pulcritud los estándares internacionales en mis diseños, sin omisiones                 |            | Hay fallos de pulcritud en los diagramas.                                    | Revisar nuevamente los diagramas hechos.             |
| He propuesto o mejorado al menos uno de los siguientes elementos:                                   | X          | Propuse la arquitectura hexagonal y desarrollé diagramas de secuencia.      | —                                                   |
| - La arquitectura general del proyecto                                                              | X          | Propuesta por mí para cumplir con los requerimientos no funcionales         | —                                                   |
| - El diagrama de paquetes                                                                           |            |                                                                              | —                                                   |
| - El diagrama de despliegue                                                                         |            |                                                                              | —                                                   |
| Mis propuestas o mejoras han sido incorporadas en la especificación de diseño de software         | X          | La arquitectura modular fue adoptada por el equipo                           | —                                                   |
| Utilizo patrones arquitectónicos avanzados para optimizar:                                         | X          | La arquitectura hexagonal permite lograr todos estos objetivos               | —                                                   |
| - Reusabilidad de componentes                                                                       | X          | Diseñados como módulos independientes                                      | —                                                   |
| - Alta cohesión dentro de los componentes                                                          | X          | Cada módulo tiene una responsabilidad específica                           | —                                                   |
| - Bajo acoplamiento entre componentes                                                               | X          | Comunicación vía interfaces y adaptadores                                  | —                                                   |
| Mi documentación incluye explicaciones detalladas de los componentes y patrones                    | X          | Existe documentación alineada a los diagramas y decisiones tomadas          | —                                                   |
| Justifico de manera sólida las decisiones arquitectónicas con referencias a principios de diseño | X          | Se usaron principios como SRP, alta cohesión y bajo acoplamiento            | —                                                   |
| Aplico técnicas de refactorización para mejorar la calidad del producto de manera consistente     | X          | El diseño permite refactorizaciones modulares sin afectar otras partes      | Incluir casos de refactorización con impacto medido |

**Evaluación nivel 3: No Superado**

## Nivel 4: Destacado (100%) - "Master Jedi"


| Criterio                                                                                       | Cumple (X) | Justificación                                                                | Áreas de oportunidad                        |
| ---------------------------------------------------------------------------------------------- | ---------- | ----------------------------------------------------------------------------- | -------------------------------------------- |
| Participo activamente en el diseño de todos los componentes críticos de mi proyecto          | X          | Propuse la arquitectura general y sus componentes clave                       | —                                           |
| Adapto los estándares internacionales de acuerdo al contexto específico del proyecto         |            | Ajusté UML para modelar la interacción en un sistema modular                | Documentar adaptaciones explícitamente      |
| Puedo justificar técnicamente todas las adaptaciones realizadas a los estándares             | X          | Las decisiones se justifican en función de la escalabilidad y mantenibilidad | —                                           |
| Lidero propuestas de mejora en:                                                                | X          | Propuse mejoras en arquitectura, despliegue e interacción de módulos        | —                                           |
| - La arquitectura general del proyecto                                                         | X          | Arquitectura hexagonal propuesta y adoptada                                   | —                                           |
| - El diagrama de paquetes                                                                      |            |                                                                               | —                                           |
| - El diagrama de despliegue                                                                    |            |                                                                               | Agregar escenarios futuros de despliegue     |
| Implemento patrones arquitectónicos innovadores que resultan en:                              | X          | Uso de arquitectura hexagonal para optimizar el sistema                       | —                                           |
| - Mayor reusabilidad de componentes                                                            | X          | Los módulos pueden escalarse o usarse en otros proyectos                     | —                                           |
| - Cohesión óptima dentro de los componentes                                                  | X          | Cada módulo tiene tareas bien definidas                                      | —                                           |
| - Acoplamiento mínimo entre componentes                                                       | X          | Se comunican a través de puertos y adaptadores                               | —                                           |
| Mi documentación es considerada un modelo a seguir por otros miembros del equipo              | X          | Se mantiene clara trazabilidad entre diseño y código                        | Incluir ejemplos para facilitar comprensión |
| Mis justificaciones arquitectónicas influyen en las decisiones estratégicas del proyecto     | X          | La arquitectura define cómo se integrarán los clientes actuales             | —                                           |
| Aplico técnicas de refactorización sistemáticamente y promuevo su adopción entre el equipo | X          | Refactorización facilitada por el diseño modular                            | Crear una guía interna de refactorización  |

**Evaluación nivel 4: No Superada**

## Resumen de evaluación


| Nivel               | Porcentaje | Estado actual | Observaciones                                      |
| ------------------- | ---------- | ------------- | -------------------------------------------------- |
| Nivel 1: Incipiente | 15%        | No Superado   | Realizar diagrama de paquetes o de secuencia       |
| Nivel 2: Básico    | 70%        | No Superado   | Involucrarme en el diagrama de despliegue          |
| Nivel 3: Sólido    | 85%        | No Superado   | Revisar la creación de los diagramas de secuencia |
| Nivel 4: Destacado  | 100%       | No Superado   | —                                                 |

**Nivel actual alcanzado:** Nivel 1: Incipiente
****Plan de acción para mejorar:****

* Involucrarme más en el diseño de los diagramas de despliegue del sistema
* Corregir los defectos de los diagramas de secuencia
