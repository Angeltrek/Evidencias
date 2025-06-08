---
sidebar_position: 1
title: Elaboración de pruebas de software
---
# Elaboración de pruebas de software


| Elabora pruebas que validen el cumplimiento de los requerimientos iniciales del sistema computacional. |
| ------------------------------------------------------------------------------------------------------ |

## Retroalimentación del profesor(a)

Por favor, agrega tus observaciones, sugerencias y comentarios sobre esta competencia en el siguiente enlace:  [Haz clic aquí para dejar tu retroalimentación](https://docs.google.com/document/d/1HmS7eCVm8DKHZVYCX3EJeBuvmihCK87ttF6DXPFLAP4/edit?usp=sharing)

## Reflexión de mi estado en la competencia

Durante este semestre entendí que realizar pruebas es fundamental para asegurar la calidad del producto, ya que se enfocan en verificar que las cosas se están haciendo de la manera correcta.

Al inicio del semestre, en el equipo de Text&Lines, se empezaron a definir distintos tipos de pruebas para asegurar la calidad del proyecto. En ese momento, no comprendía del todo su valor, ya que pensaba que eran necesarias solo porque formaban parte del ciclo de desarrollo de software. Sin embargo, se propusieron varias pruebas dentro del WBS como pruebas de seguridad, conectividad, integración, arquitectura y pruebas heurísticas en voz alta.

Diego Alfaro desempeñó el rol de AO durante el primer y segundo periodo del semestre, y se encargó de coordinar las pruebas de arquitectura. Al principio, no entendía la necesidad de realizar una prueba de arquitectura tan exhaustiva, pero más adelante comprendí su importancia. Gracias a esa verificación temprana, cuando el equipo tuvo que cambiar de una base de datos no relacional a una relacional, el impacto fue mínimo. Si Diego no hubiera considerado estos aspectos desde la elección del stack tecnológico, el proyecto se habría atrasado al menos una semana. Además, las pruebas permitieron verificar que todo funcionara correctamente y evaluar los patrones de diseño para asegurar alta cohesión con el estilo arquitectónico del software.

En esa prueba de arquitectura también aporté realizando pruebas de seguridad para verificar que nuestro sistema estuviera protegido contra ataques CSRF. Para ello, investigué y realicé simulaciones usando la herramienta Burp Suite, lo que me permitió validar con éxito este tipo de vulnerabilidades.

Uno de nuestros requisitos no funcionales más importantes era la seguridad del sistema, pues se desarrolla un sistema multicliente que maneja datos sensibles de los trabajadores de los clientes de Altertex. Por esta razón, priorizamos las pruebas de seguridad durante la prueba de arquitectura.

Con el tiempo, nos dimos cuenta de que no teníamos un plan de pruebas formal, por lo que mi compañero Hiram propuso usar la tabla de casos de prueba que ya habíamos utilizado en semestres anteriores. Esta decisión fue acertada, ya que posteriormente facilitó el control de pruebas realizadas y permitió ejecutar pruebas de regresión de manera más efectiva.

Al realizar una historia de usuario, le tenía que realizar pruebas unitarias considerando todas las posibles validaciones para los campos de los formularios como entrada de datos válidos, rangos permitidos o condiciones específicas de negocio como en la historia de usuario de crear producto que permite crear un producto sin puntos asignados.

Además, era importante verificar que el sistema proporcionara respuestas de retroalimentación claras y adecuadas al usuario en caso de errores, como mensajes que indicaran campos inválidos, datos faltantes o acciones no permitidas.

También se habían comprometido requisitos como rendimiento y escalabilidad, por lo que las pruebas de estrés fueron clave para garantizar la calidad del software.

Además, realicé pruebas de usabilidad incluso antes de que estuvieran formalizadas en nuestro plan. Consideré que era mejor ejecutarlas en fases tempranas del desarrollo para facilitar las adaptaciones necesarias. Para ello, conté con el apoyo de Benjamín Arauz, un compañero del otro departamento, quien me ayudó a detectar problemas de experiencia de usuario. Aunque no pude documentarlas de la mejor forma, implementé los cambios necesarios y validé con mi equipo que no representaban un riesgo para el sistema ni para los costos del proyecto.

Más adelante, tuvimos la oportunidad de hacer pruebas heurísticas en voz alta directamente con el socio formador y a su vez pudimos realizar pruebas beta con Mao quien se encarga de comunicar los avances al socio formador, en las que yo estuve presente para validar una historia de usuario relacionada con la creación de productos dentro del sistema. Estas pruebas fueron útiles, ya que permitieron confirmar que estábamos construyendo el producto correcto.

Cuando cambié de rol a PM, el equipo de Text&Lines realizó verificaciones junto con los profes Alex y Denisse, quienes ayudaron a descubrir vulnerabilidades de seguridad y pusieron a prueba varios requisitos no funcionales como rendimiento, usabilidad, seguridad y disponibilidad. Gracias a ello, me dí cuenta que le tuvimos que dar más importancia a las pruebas de caja negra, y entendí que si hubiéramos hecho esto antes, habríamos ahorrado mucho tiempo en obtener retroalimentación valiosa.

Posteriormente, dentro del equipo de Text&Lines se pudieron realizar pruebas de caja negra con dos miembros del equipo de Technebrios y pudieron acortar los ciclos de retroalimentación, lo cual es positivo porque dentro del equipo se pudo mejorar la manera en la que se hacen pruebas.

Cuando asumí mi rol como PM, surgieron varios problemas en la historia de usuario relacionada con la creación de productos. Esto se debió a que el formulario incluía demasiados campos que debían completarse correctamente, lo que aumentaba su complejidad. Además, este componente resultó ser sumamente crítico dentro del sistema, ya que está directamente relacionado con la gestión de uniformes, y los uniformes en sí son considerados productos dentro del sistema

Comprendí que hay historias de usuario que requieren un mayor número de pruebas para garantizar su estabilidad y correcto funcionamiento a lo largo del tiempo. Aunque actualmente no puedo hacer nada para cambiar lo que ya pasó, me llevo ese aprendizaje para aplicarlo en futuros proyectos.

Además, valoro mucho el apoyo de mi equipo, ya que gracias a ellos logré comprender la verdadera importancia de las pruebas dentro del ciclo de desarrollo de software. Su compromiso con el proyecto me permitió fortalecer mi enfoque y reconocer que probar no es solo una etapa más, sino una práctica continua que asegura el éxito del producto final.

## Reflexión de Master Jedi en elaboración de pruebas

Un Master Jedi en elaboración de pruebas es quien garantiza que el producto se construya de la manera correcta, identificando y eliminando defectos que podrían afectar negativamente la experiencia de los usuarios finales. No solo considera los requisitos funcionales, sino que también pone atención en verificar los requisitos no funcionales.

Comprende la importancia de las reglas de negocio, asegurando que la lógica del sistema sea suficientemente necesaria para cumplir con las necesidades del cliente y el contexto del proyecto por lo que se asegura de que las historias de usuario cumplan con sus criterios de aceptación, y que las verificaciones estén cubiertas mediante distintas pruebas que aseguren la calidad del producto. No solo se limita a verificar que el sistema funcione, sino que busca romperlo hazta hacerlo más fuerte y aprende a realizar pruebas más robustas con el tiempo.

## Evidencias que respaldan la competencia


| Descripción de la evidencia                                                           | Enlace a la evidencia                                                                                                                       |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Pruebas Beta y Heurísticas en Voz alta con el Socio Formador Parte 1                 | [Parte 1](https://drive.google.com/file/d/16SxtqPJLbQrQOase0Smmej8d9QiaGBbV/view?usp=sharing)                                               |
| Pruebas Beta y Heurísticas en Voz alta con el Socio Formador Parte 2                 | [Parte 2](https://drive.google.com/file/d/1Ff9YA06SScfiE82j1bbtNFZ-2cOhre-b/view?usp=sharing)                                               |
| Pull request de Atender correcciones de Pruebas de Usabilidad                          | [Pull Request de Correcciones de Usabilidad](https://github.com/CodeAnd-Co/Frontend-Text-Lines/pull/24)                                     |
| Pruebas unitarias de consultar lista de empleados                                      | [Prueba unitaria](https://docs.google.com/spreadsheets/d/1NLGwGrGA5PVOEzLaqxa8Ts1D_Ng3QzzqNKWJYUzxD-M/edit?gid=233812011#gid=233812011)     |
| Pruebas unitarias de consultar lista de grupo de empleados                            | [Prueba unitaria](https://docs.google.com/spreadsheets/d/1NLGwGrGA5PVOEzLaqxa8Ts1D_Ng3QzzqNKWJYUzxD-M/edit?gid=1228526650#gid=1228526650)   |
| Pruebas unitarias de crear producto                                                    | [Prueba unitaria](https://docs.google.com/spreadsheets/d/1NLGwGrGA5PVOEzLaqxa8Ts1D_Ng3QzzqNKWJYUzxD-M/edit?gid=233812011#gid=233812011)     |
| Aportación en prueba de arquitectura evaluando el requisito no funcional de seguridad | [Prueba de arquitectura](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/prueba-de-arquitectura#ataques-csrf) |
| RTM Consultar lista de empleados                                                       | [Consultar lista de empleados](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF17)               |
| RTM Consultar lista de grupo de empleados                                              | [Consultar lista de grupo de empleados](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF22)      |
| RTM Crear producto                                                                     | [Crear producto](https://codeandco-wiki.netlify.app/docs/next/proyectos/textiles/documentacion/requisitos/RF26)                             |
