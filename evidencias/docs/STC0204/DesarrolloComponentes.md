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

El desarrollo de software no solo es codificar o implementar soluciones técnicas, sino también verificar si el análisis previo está bien hecho, si el diseño cumple con los requisitos del sistema, y seguir estándares y acuerdos de trabajo para entregar un módulo que realmente satisfaga las necesidades del producto.

En el caso de Text&Lines, las primeras historias de usuario presentaron varios defectos. Esto se debió, en gran parte, a que al inicio del semestre el equipo no le daba importancia a todo el proceso de ingeniería que implica construir software de calidad. Aunque validábamos con el socio formador lo que desarrollábamos, no éramos conscientes de que eso formaba parte de las buenas prácticas. Fue hasta depués que comenzamos a ponerle nombre y valor a esas acciones.

Una de las áreas de oportunidad donde no pude aportar tanto como hubiera querido fue en la creación de procesos de desarrollo. Me motivé por desempeñar el rol de PM, y aunque fue una muy buena experiencia, siento que descuidé la parte técnica. Un proceso de desarrollo más claro me habría ayudado a evitar varios defectos en la historia de usuario de crear producto, que resultó ser crítica para el sistema de Altertex.

Durante esa historia, tuve que validar en varias ocasiones con el socio si la historia de usuario satisfacía las reglas de negocio. Para eso, incluso analicé cómo funciona la creación de productos en plataformas como Shopify. Afortunadamente, en la primera validación salieron varios defectos en el diseño del modelo relacional, como errores en la base de datos, ya que no se había considerado que cada proveedor debía estar relacionado con un cliente específico del sistema.

Algo que consideré durante el desarrollo fue el revisar el diseño en el patrón de arquitectura limpia. Analizar esta estructura me permitió entender mejor la conexión entre los módulos y sus responsabilidades, lo cual es clave para evitar un sistema frágil o con errores. Tuve áreas de oportunidad la historia de crear producto, ya que en el frontend pudo haber una mejor modularidad para crear varianes y opciones.

El desarrollo de componentes también requiere disciplina para escribir buen código. Para lograr un sistema robusto, es esencial aplicar principios como SOLID. Uno de mis errores fue no saber cómo separar mejor los componentes para manejar el estado sin caer en prop drilling. Como solución usé un contexto que concentrara todos los estados relacionados con la creación de producto. Funcionó, pero el componente se volvió demasiado largo, y aunque necesitaba una refactorización, ya no me dio tiempo de hacerla por mis responsabilidades como PM dentro de Code&Co.

Otro aprendizaje clave fue el valor del pair programming. Al inicio del semestre pensaba que ralentizaba el desarrollo, pero estaba equivocado. En realidad, ayuda a reducir los ciclos de retroalimentación y mejora la calidad del producto. De hecho, muchos defectos se podrían haber evitado si se hubiera aplicado esta práctica desde el comienzo.

Como equipo, Text&Lines logró desarrollar 59 historias de usuario. De esas, yo desarrollé tres, de las cuales solo una fue compleja. Uno de los errores que cometimos fue no registrar en el PVG historias que sí se implementaron, como la de consultar sistema, que terminó siendo muy importante.

## Reflexión de Master Jedi en desarrollo de componentes de software

Un Master Jedi en desarrollo de componentes de software es quien construye soluciones sólidas que resisten el paso del tiempo y el crecimiento del sistema. Sabe que el desarrollo de un producto va más allá de programar, y que cada componente debe diseñarse con una intención clara, considerando tanto los requisitos funcionales como los no funcionales, la arquitectura del sistema y su mantenibilidad a largo plazo.

Comprende que un mal diseño puede comprometer todo el sistema, por eso adapta estándares internacionales a su contexto, lidera con intención, y garantiza una alta cohesión y bajo acoplamiento en cada decisión. No solo implementa, también reflexiona, documenta y justifica cada componente que entrega. Entiende que la reusabilidad y la claridad son señales de un sistema sano.

Reconoce que el desarrollo individual no significa trabajar solo, sino asumir la responsabilidad de entregar componentes bien integrados, validados y versionados, que contribuyan al MVP y a los MBI aprobados. Usa técnicas como el pair programming, la revisión por pull requests con estándares definidos y la refactorización continua, porque sabe que mantener la calidad no es una tarea ocasional, sino una práctica constante.

## Evidencias que respaldan la competencia


| Descripción de la evidencia                           | Enlace a la evidencia                                                                                                                  |
| ------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| Frontend: Desarrollo de Consultar Grupos de Empleados | [Componente Consultar Grupos de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/18)                                  |
| Frontend: Desarrollo de Consultar Lista de Empleados | [Componente Consular Lista de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/23)                                    |
| Frontend: Desarrollo de Crear Producto               | [Componente Crear Producto](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/74)                                                 |
| Backend: Desarrollo de Consultar Grupos de Empleados  | [Componente Consultar Grupos de Empleados](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/18)                                  |
| Backend: Desarrollo de Consultar Lista de Empleados  | [Componente Consular Lista de Empleados](https://github.com/CodeAnd-Co/Backend-textiles/pull/29)                                       |
| Backend: Desarrollo de Crear Producto                | [Componente Crear Producto](https://github.com/CodeAnd-Co/Backend-textiles/pull/62)                                                    |
| RTM Consultar lista de empleados                       | [Consultar lista de empleados](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF17)          |
| RTM Consultar lista de grupo de empleados              | [Consultar lista de grupo de empleados](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF22) |
| RTM Crear producto                                     | [Crear producto](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF26)                        |
