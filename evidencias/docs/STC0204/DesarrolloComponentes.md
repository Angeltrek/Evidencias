---
sidebar_position: 1
title: Desarrollo de componentes de software
---
# Desarrollo de componentes de software

| Desarrolla todos los componentes diseñados de un sistema computacional, con base en estándares internacionales. |
| :---------------------------------------------------------------------------------------------------------------- |

## Retroalimentación del profesor(a)

Por favor, agrega tus observaciones, sugerencias y comentarios sobre esta competencia en el siguiente enlace:  [Haz clic aquí para dejar tu retroalimentación](https://docs.google.com/document/d/1xm_M5vunXw_bH4wOiuPd6hGk5HVsXdd6ssWe9VoPqxM/edit?usp=sharing)

## Reflexión de mi estado actual en la competencia

La necesidad principal de Altertex es llegar al usuario final sin depender de intermediarios, lo que representa un cambio estratégico importante para su modelo de negocio. Por ello, la propuesta de valor del software desarrollado se centra en hacer este proyecto viable desde el punto de vista técnico, eliminando los cuellos de botella generados por los intermediarios.

El Producto Mínimo Viable MVP fue diseñado considerando que los intermediarios actuales se comuniquen directamente con Altertex y con los usuarios finales, sin generar retrasos en los procesos. Esta visión orienta cada decisión técnica, priorizando la funcionalidad esencial para resolver el problema real de la empresa.

Un ejemplo del impacto de esta problemática es Toyota, uno de los clientes de Altertex, donde actualmente los empleados deben generar solicitudes manuales para obtener uniformes, lo cual es ineficiente y genera costos operativos. El sistema que estamos desarrollando busca digitalizar y automatizar este tipo de interacciones.

En términos técnicos, los requerimientos funcionales y no funcionales del sistema están enfocados principalmente en la seguridad y la escalabilidad. Por esta razón, se implementó una arquitectura hexagonal, que garantiza una separación clara de responsabilidades, alta cohesión dentro de cada componente y bajo acoplamiento entre ellos. Esto facilita la reutilización, el mantenimiento y la evolución del sistema, permitiendo que escale sin comprometer su estabilidad.

Para asegurar una trazabilidad clara entre el diseño y el desarrollo, se ha mantenido una documentación continua y efectiva. En los dos componentes que tengo asignados, me he asegurado de mantener los estándares de calidad y de seguir buenas prácticas de codificación, como la validación de reglas de negocio (por ejemplo, los permisos del sistema) y la encapsulación adecuada de la lógica.

El desarrollo de componentes sigue un proceso estrictuo ya que los pull requests deben pasar por una checklist que incluye la ejecución de pruebas unitarias, lo cual garantiza que no se integre código sin validar.

Desde mi rol como QA, priorizo la calidad del producto. Una de las estrategias que implementamos para esto es el pair programming. Normalmente, participo como navegador del código, revisando cuidadosamente que se cumplan los estándares y se respeten las buenas prácticas. Sin embargo, cuando me toca ser conductor, valoro mucho que mis compañeros detecten posibles defectos que yo no habría notado por mi cuenta. Este enfoque ha elevado la calidad del software de manera consistente.

Finalmente, siempre tengo presente que la seguridad requerimiento no funcional muy importante del proyecto. Gracias a la arquitectura modular, es sencillo identificar componentes sensibles que podrían representar riesgos y se aplican medidas para evitar brechas de seguridad. Esto también contribuye a la trazabilidad y mantenibilidad del sistema, alineándose con las expectativas del socio formador y con los estándares internacionales de diseño de software.

## Evidencias que respaldan la competencia

| Descripción de la evidencia                           | Enlace a la evidencia                                                                              |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| Frontend: Desarrollo de Consultar Grupos de Empleados | [Componente Consultar Grupos de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/18) |
| Frontend: Desarrollo de Consultar Lista de Empleados | [Componente Consular Lista de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/23)   |
| Backend: Desarrollo de Consultar Grupos de Empleados  | [Componente Consultar Grupos de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/18) |
| Backend: Desarrollo de Consultar Lista de Empleados  | [Componente Consular Lista de Empleados](https://github.com/CodeAnd-Co/Backend-textiles/pull/29)      |