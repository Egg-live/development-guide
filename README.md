# Development guide

## Acerca de esta guía

El propósito de esta guía es establecer los estándares y procesos aplicables a cada desarrollador, al equipo de desarrollo y al producto resultante de sus esfuerzos.

Cada punto detallado en esta guía tiene el objetivo de asegurar y garantizar lo siguiente:

- La salud tanto del equipo de desarrollo como de cada individuo en él.
- La calidad del producto desarrollado.
- El desarrollo ágil y eficiente, con entregas constantes.
- La escalabilidad del equipo, manteniendo su salud y estándares de calidad.
- La distribución del conocimiento a todos los miembros del equipo.
- El crecimiento individual y sostenido de cada integrante del equipo.

> Esta guía se encuentra en constante ampliación y evolución. Es responsabilidad de cada miembro del equipo mantenerse informado sobre los cambios y las últimas actualizaciones. Se sugiere suscribirse, leer y colaborar en su mantenimiento y mejora.

## Índice de contenido

- [Development guide](#development-guide)
  - [Acerca de esta guía](#acerca-de-esta-guía)
  - [Índice de contenido](#índice-de-contenido)
  - [El desarrollador](#el-desarrollador)
    - [Habilidades Requeridas](#habilidades-requeridas)
      - [Habilidades Mínimas Requeridas](#habilidades-mínimas-requeridas)
  - [El equipo de desarrollo](#el-equipo-de-desarrollo)
    - [Revisión de Código](#revisión-de-código)
      - [Obligaciones del Desarrollador](#obligaciones-del-desarrollador)
      - [Responsabilidades del Revisor](#responsabilidades-del-revisor)
    - [Sesiones de Pair Programming](#sesiones-de-pair-programming)
      - [Convocatoria a Pair Programming](#convocatoria-a-pair-programming)
      - [Metodología de Trabajo](#metodología-de-trabajo)
      - [Consideraciones Adicionales](#consideraciones-adicionales)
    - [Sesiones de Conocimiento](#sesiones-de-conocimiento)
      - [Objetivos](#objetivos)
      - [Estructura y Formato](#estructura-y-formato)
      - [Organización y Participación](#organización-y-participación)
      - [Recursos y Seguimiento](#recursos-y-seguimiento)
      - [Beneficios Esperados](#beneficios-esperados)
  - [Work flow](#work-flow)
  - [Las ceremonias](#las-ceremonias)
    - [Daily Stand-up](#daily-stand-up)
      - [¿Qué hice ayer?](#qué-hice-ayer)
      - [¿Qué haré hoy?](#qué-haré-hoy)
      - [¿Hay algún impedimento que esté obstaculizando mi trabajo?](#hay-algún-impedimento-que-esté-obstaculizando-mi-trabajo)
    - [Architecture Meeting](#architecture-meeting)
      - [Frecuencia](#frecuencia)
      - [Temas](#temas)
      - [Solicitante](#solicitante)
      - [Participación](#participación)
      - [Accionable](#accionable)
      - [Duración](#duración)
    - [Retrospectiva](#retrospectiva)
      - [Frecuencia](#frecuencia-1)
      - [Objetivos](#objetivos-1)
      - [Participantes](#participantes)
      - [Estructura de la Reunión](#estructura-de-la-reunión)
      - [Duración](#duración-1)
      - [Importancia del Ambiente](#importancia-del-ambiente)
    - [Planificación Ad-hoc](#planificación-ad-hoc)
      - [Objetivo](#objetivo)
      - [Frecuencia](#frecuencia-2)
      - [Participantes](#participantes-1)
      - [Estructura de la Reunión](#estructura-de-la-reunión-1)
      - [Duración](#duración-2)
      - [Importancia](#importancia)
  - [Stack Tecnológico](#stack-tecnológico)
    - [Asignación de puertos y servicios](#asignación-de-puertos-y-servicios)
    - [Frontend Stack](#frontend-stack)
    - [Backend Stack](#backend-stack)
    - [Database Stack](#database-stack)
    - [Cloud Stack](#cloud-stack)
    - [DevOps Stack:](#devops-stack)
  - [Repositorios](#repositorios)
    - [README.md](#readmemd)
    - [Modo Desarrollo](#modo-desarrollo)
    - [Scripts del Repositorio](#scripts-del-repositorio)
      - [Basic Scripts](#basic-scripts)
    - [Estilo de Código y Formato](#estilo-de-código-y-formato)

## El desarrollador

Esta sección establece los estándares y habilidades esenciales para cada miembro del equipo de desarrollo, sirviendo como referencia para resolver dudas y revisar los estándares y herramientas diseñadas para ellos.

### Habilidades Requeridas

La siguiente lista detalla las habilidades mínimas necesarias para garantizar la adaptación exitosa del desarrollador en cualquier equipo o proyecto actual y futuro.

Estas habilidades son complementarias a los requisitos específicos de cada posición y deben ser solicitadas y validadas durante el proceso de contratación. Cada miembro del equipo de desarrollo debe poseer todas las habilidades mencionadas, con el nivel especificado a continuación:

#### Habilidades Mínimas Requeridas

1. **Español:** Intermedio
2. **Inglés:** Intermedio
3. **JavaScript, TypeScript y Python:** Intermedio
4. **Node, React:** Intermedio
5. **Bases de Datos:** Intermedio
6. **Git:** Intermedio

## El equipo de desarrollo

Esta sección establece los estándares y procesos aplicables a todo el equipo de desarrollo, sirviendo como referencia para resolver dudas y revisar los estándares y herramientas diseñadas para ellos y haciendo foco en la distribución del conocimiento, la optimización del mismo y su capacidad para crecer incorporando nuevos miembros de forma orgánica.

### Revisión de Código

El propósito de las revisiones de código es fomentar la distribución de conocimientos entre los desarrolladores y maximizar la eficiencia del aprendizaje.

Es esencial que todo software desarrollado sea examinado por al menos un integrante del equipo antes de su implementación.

> La asignación del revisor debe ser realizada de manera aleatoria y justa, evitando favoritismos o excepciones.

Para la revisión de código, se deben emplear las herramientas que Github ofrece específicamente para este proceso, facilitando el intercambio de ideas, la resolución de problemas y la implementación de mejoras.

#### Obligaciones del Desarrollador

1. Crear el Pull Request (PR) con el código a ser revisado.
2. Elegir y asignar un revisor de forma aleatoria.
3. Incluir en la descripción del PR un vínculo al ticket correspondiente.
4. Marcar el PR como `Ready for Review` una vez esté preparado para revisión.
5. Aportar comentarios y sugerencias pertinentes para la evaluación del PR.
6. Cerrar el PR si los cambios propuestos no son necesarios.
7. Reabrir el PR si se requieren modificaciones.

#### Responsabilidades del Revisor

1. Asegurar el cumplimiento de los estándares de calidad y la ejecución de tests rutinarios.
2. Proporcionar comentarios y sugerencias para optimizar el código.
3. Integrar los cambios en la rama destinada.
4. Avanzar el ticket a la siguiente fase del flujo de trabajo.
5. Comunicar cualquier observación relevante a todos los desarrolladores involucrados.

### Sesiones de Pair Programming

El objetivo del Pair Programming (PP) es distribuir el conocimiento entre los desarrolladores y optimizar el tiempo de aprendizaje. Se requiere que cada desarrollador complete al menos 10 horas de PP al mes, con la posibilidad de exceder este mínimo si se considera prudente o necesario.

#### Convocatoria a Pair Programming

1. Un desarrollador elige una tarea adecuada para PP de su lista de pendientes.
2. La tarea se etiqueta como "Pair Programming".
3. Se anuncia en un grupo con todos los desarrolladores de la organización la disponibilidad de la tarea para PP, indicando la fecha de inicio, el tiempo estimado de desarrollo y el enlace al ticket correspondiente.
4. Otro desarrollador interesado se apunta para las sesiones de PP.
5. Ambos desarrolladores coordinan días y horarios para trabajar juntos y programan las reuniones necesarias, bloqueando ambas agendas.

> Nota: Es importante que los desarrolladores colaboren equitativamente con todos los miembros del equipo, independientemente de su experiencia o lenguaje de programación preferido.

#### Metodología de Trabajo

> El `Owner` es el responsable de la tarea y el `Guest` es el desarrollador que se une al PP.

- Antes del inicio, el Guest debe tener el repositorio clonado y el entorno de desarrollo preparado.
- El Owner presenta el alcance de la tarea, la estrategia general para la solución óptima, las herramientas y tecnologías a usar, y cualquier otra información relevante.
- El Guest comparte el enlace para la sesión y el Owner se une.
- El Owner guía al Guest durante el desarrollo, explicando cada decisión y sus fundamentos.
- El Guest hace preguntas y sugiere alternativas, participando activamente en la toma de decisiones.
- Las sesiones de PP continúan hasta que la tarea esté lista para avanzar al siguiente estadio de desarrollo.
- Ambos desarrolladores registran el tiempo empleado en la tarea.

> Objetivo: Que el Guest aprenda y comprenda el proceso de desarrollo de principio a fin para su futura aplicación.

> Se sugiere combinar PP con otras técnicas de desarrollo, como TDD.

#### Consideraciones Adicionales

- El propósito de las sesiones de PP es la distribución del conocimiento, no para resolver problemas urgentes o específicos.
- Las convocatorias a PP deben anunciarse con antelación para permitir la participación de todos los desarrolladores, especificando si se requieren conocimientos o herramientas particulares.
- Si un desarrollador no puede asistir a una sesión de PP o necesita terminarla antes, debe informarlo con anticipación y re programar la sesión o el tiempo restante. Incumplimientos reiterados deben ser comunicados al líder del equipo.
- No cumplir con las horas mensuales de PP o las normas establecidas será considerado negativamente en la evaluación de desempeño.

### Sesiones de Conocimiento

Las Sesiones de Conocimiento son reuniones diseñadas para fomentar el intercambio de información, habilidades y experiencias dentro del equipo de desarrollo. Su objetivo es crear un espacio de aprendizaje colaborativo donde los miembros del equipo puedan compartir conocimientos, explorar nuevas tecnologías y discutir soluciones a problemas comunes. Estas sesiones no solo promueven el crecimiento profesional individual, sino que también mejoran la cohesión y la sinergia del equipo.

#### Objetivos

1. **Compartir Conocimientos Específicos:** Permitir a los miembros del equipo presentar temas en los que son expertos o han adquirido conocimientos recientes.
2. **Fomentar la Innovación:** Explorar nuevas tecnologías, metodologías y prácticas que puedan ser beneficiosas para el equipo y la organización.
3. **Resolver Problemas en Común:** Discutir desafíos técnicos actuales y encontrar soluciones colaborativas.

#### Estructura y Formato

1. **Frecuencia:** La frecuencia dependerá de la disponibilidad y las necesidades del equipo.
2. **Duración:** Generalmente de 1 a 2 horas, para permitir una discusión detallada sin interrumpir significativamente las actividades regulares del equipo.
3. **Formato:** Pueden variar entre presentaciones formales, talleres prácticos, sesiones de brainstorming o discusiones abiertas.
4. **Temas:** Seleccionados por los miembros del equipo, pueden incluir desde actualizaciones tecnológicas hasta lecciones aprendidas en proyectos recientes.

#### Organización y Participación

1. **Calendario de Sesiones:** Se establece una agenda para cada sección con anticipación, permitiendo a los miembros del equipo planificar su participación.
2. **Rotación de Presentadores:** Todos los miembros del equipo deben tener la oportunidad de presentar, asegurando una diversidad de temas y perspectivas.
3. **Participación Activa:** Se fomenta la participación activa de todos los asistentes a través de preguntas, comentarios y discusiones.

#### Recursos y Seguimiento

1. **Material de Apoyo:** Los presentadores pueden proporcionar diapositivas, códigos de ejemplo, o recursos adicionales para complementar sus presentaciones.
2. **Acciones Posteriores:** Identificar acciones o proyectos que surjan como resultado de las discusiones en las sesiones.

#### Beneficios Esperados

- **Mejora Continua:** Actualización constante de habilidades y conocimientos técnicos.
- **Cohesión del Equipo:** Fortalecimiento de la colaboración y el sentido de comunidad dentro del equipo.
- **Innovación y Creatividad:** Generación de nuevas ideas y enfoques para los proyectos en curso y futuros.

Incorporando las Sesiones de Conocimiento en la rutina del equipo, se crea un ambiente de aprendizaje continuo y se promueve un espacio donde el compartir y la colaboración son la norma, llevando a un equipo más unido, informado y efectivo.

## Work flow

Este documento detalla el proceso de trabajo desde la asignación de una tarea al desarrollador hasta su implementación en producción.

1. **Start**:

   - **Selección**: El desarrollador elige la tarea de mayor prioridad de su lista asignada o la primera en su tablero Kanban.
   - **Alternativas**: Si la tarea seleccionada no puede ser realizada, se debe consensuar con el equipo de producto o el líder directo para elegir una alternativa.

2. **Development**:

   1. Mover la tarea al estado `In progress`.
   2. Crear una rama de características (`feature branch`) con el formato `[ticket-id]/[task-type]/title` partiendo desde `develop`.
   3. Registrar la tarea en el archivo `CHANGELOG.md`, vinculándola con el ticket correspondiente.
   4. Crear subtareas para cualquier configuración extra o variables de entorno necesarias, especificando detalles y responsables. Las variables de entorno necesarias deberán ser establecidas para todos los ambientes necesarios a la vez.
   5. En caso de necesitar ayuda de otro desarrollador, crear una subtarea detallando la necesidad y los criterios de aceptación.
   6. Implementar la funcionalidad.
   7. Realizar commits regulares y atómicos, y subir los cambios a la rama remota asegurándose que se ejecuten correctamente.
   8. Registrar el tiempo empleado regularmente.
   9. Informar en la reunión diaria o al líder si el plazo de entrega está en riesgo, y preparar un plan de acción.
   10. Verificar que se cumplan adecuadamente.
   11. Marcar el PR (Pull Request) para revisión y asignar al menos un revisor.

3. **Review**:

   - Los desarrolladores asignados revisan, comentan y sugieren mejoras para asegurar la calidad del código.

4. **Merge**:

   - El revisor principal verifica los tests, aprueba el PR, realiza el merge a `develop` y `staging`, y actualiza el estado de la tarea en Jira para el proceso de QA (Quality Assurance).

5. **QA**:

   - **Validación**: El equipo de QA realiza pruebas para asegurar el cumplimiento de los criterios de aceptación.
   - **Gestión de Errores**: En caso de encontrar errores, reportarlo en Jira mediante un comentario en la tarea especifica, incluyendo los pasos y credenciales necesarias para su reproducción, mover la tarea nuevamente a `In progress` e informar al desarrollador para que elimine el código defectuoso de la rama `staging` y resuelva el problema.
   - **Registro de tiempo empleado**: En ambos casos, las horas empleadas deben ser registradas en la tarea.

6. **Pre-Production**:

   - Integrar semanalmente todas las tareas con estado `QA passed` a la rama `demo` para su última revisión y aprobación por el departamento de Producto y mover dichas tareas al estado `Demo`.

7. **Production-Ready**:

   - El departamento de producto actualiza manuales, genera la comunicación y actualiza la documentación necesaria, revisa las características a desplegar y marca el lanzamiento como `Production Ready`.

8. **Deploy**:

   - Seguir el cronograma establecido por el roadmap del producto para el despliegue, informando a todos los stakeholders durante una ceremonia especial de lanzamiento.

9. **Product update**:

   - Informar a los stakeholders sobre la actualización del producto, proporcionando enlaces a la documentación actualizada.

10. **Monitoring**:
    - Supervisar el comportamiento del sistema y asegurar su correcto funcionamiento.
    - En caso de errores, implementar un plan de contingencia que puede incluir un hotfix o la reversión del release desplegado.
    - Programar guardias para monitorear el sistema en momentos de alta demanda de ser necesario.

## Las ceremonias

En esta sección estipularemos las ceremonias que realizará el equipo de desarrollo y estableceremos las pautas a seguir para lograr el óptimo desarrollo de las mismas.

### Daily Stand-up

En esta ceremonia de frecuencia diaria se espera que cada desarrollador responda tres preguntas claves en un tiempo no mayor a 4 minutos.

Estas preguntas están diseñadas para proporcionar una actualización rápida y eficiente sobre el progreso y los posibles impedimentos en el trabajo del equipo.

Las preguntas son:

#### ¿Qué hice ayer?

Aquí, cada miembro del equipo informa sobre lo que logró el día anterior. Esto ayuda a entender el progreso y fomenta la responsabilidad individual.

#### ¿Qué haré hoy?

En esta parte, cada desarrollador describe las tareas en las que planea trabajar durante el día. Esto sirve para establecer expectativas y ayuda al equipo a estar al tanto de lo que está sucediendo, lo que puede promover la colaboración y la ayuda mutua.

#### ¿Hay algún impedimento que esté obstaculizando mi trabajo?

Finalmente, se discuten los desafíos o bloqueos que el desarrollador está enfrentando. El objetivo es identificar rápidamente cualquier obstáculo que pueda retrasar el trabajo establecido, y buscar soluciones en equipo o apoyo del Scrum Master para resolver estos impedimentos.

Durante la ronda de actualización de estad del equipo, ningún desarrollador deberá ser interrumpido y la ronda de actualización deberá fluir de la manera más ágil posible.

Cualquier necesidad de profundizar sobre algún tema, consulta o tema a tratar deberá realizarse luego de la ronda de actualización, para lo cuál, quien lo requiera deberá solicitar que permanezcan en la reunión aquellos integrantes que considere necesario. O fijar una reunión especial para tratar dicho tema.

### Architecture Meeting

La reunión de Arquitectura es un encuentro focalizado en la mejora y discusión de la arquitectura del sistema o de secciones específicas del mismo. A la vez que es una herramienta muy potente en la distribución del conocimiento y la optimización del tiempo de aprendizaje.

#### Frecuencia

- **Solicitud según necesidad**: Esta reunión debe ser convocada según la necesidad de discutir o mejorar aspectos particulares de la arquitectura del sistema.
- **Mínimo cada 20 días**: Independientemente de las necesidades específicas, se debe agendar al menos una reunión de este tipo cada 20 días para asegurar un seguimiento y mejora continua de la arquitectura del sistema.

#### Temas

- **Enfoque único**: Cada reunión debe centrarse en un único tema para garantizar una discusión en profundidad y efectiva.
- **Mejoras y soluciones**: El objetivo principal es debatir soluciones o mejoras en la arquitectura del sistema o de alguna de sus secciones.

#### Solicitante

- **Iniciativa abierta**: Cualquier miembro del equipo de desarrollo puede solicitar una reunión, estableciendo la agenda y los temas a tratar.
- **Participación opcional pero específica**: La reunión es abierta a todo el equipo pero opcional, con la posibilidad de requerir la asistencia obligatoria de ciertos miembros.
- **Responsabilidad del solicitante**: Es deber del solicitante especificar claramente el tema y los resultados esperados de la reunión.

#### Participación

- **Aportes de todos los presentes**: Se fomenta la contribución activa de todos los asistentes, ofreciendo soluciones o sugerencias de mejora.

#### Accionable

- **Definición de tareas**: Al concluir la reunión, se debe tener una tarea claramente definida o una descripción de los pasos a seguir para implementar la solución acordada.

#### Duración

- **Estimación del solicitante**: La duración de la reunión será definida por el solicitante, quien debe estimar el tiempo necesario para abordar el tema, discutir soluciones y definir los resultados esperados. En este punto en muy importante que el solicitante acote el alcance del tema a tratar para garantizar el éxito de la reunión.

Esta estructura busca mantener el enfoque y la eficiencia, asegurando que las discusiones sobre la arquitectura del sistema sean productivas y contribuyan al desarrollo continuo y a la mejora del proyecto.

### Retrospectiva

La ceremonia de Retrospectiva es un espacio esencial para la reflexión y mejora continua del equipo de desarrollo. Se enfoca en analizar cómo está funcionando el equipo y los procesos, y en identificar acciones para mejorar en el ciclo de trabajo.

#### Frecuencia

- **Al final de cada sprint**: La Retrospectiva se lleva a cabo regularmente al final de cada sprint, asegurando un análisis oportuno y pertinente de las actividades recientes. En caso de que la metodología de trabajo no sea por sprint, se debe realizar al menos una vez al mes.

#### Objetivos

- **Evaluación del sprint**: Revisar qué tan bien funcionó el sprint o el período comprendido desde la última reunión de **Retrospectiva**, identificando tanto los logros como los desafíos.
- **Identificar mejoras**: Destacar áreas de mejora y proponer acciones concretas para implementar en los próximos sprints.
- **Fomentar la comunicación**: Crear un espacio seguro donde todos los miembros del equipo puedan compartir sus opiniones y experiencias de manera abierta y respetuosa.

#### Participantes

- **Todo el equipo involucrado**: Incluye a los miembros del equipo de desarrollo, asegurando una perspectiva integral de todas las partes involucradas.

#### Estructura de la Reunión

1. **Preparación**: El Scrum Master o quien lidere la reunión prepara la reunión, definiendo una estructura clara y asegurando que el ambiente sea propicio para una discusión abierta y honesta.

2. **Revisión del sprint**: Comenzar con una revisión general del sprint o ciclo de trabajo posterior a la reunion anterior, incluyendo logros y desafíos.

3. **Discusión abierta**: Utilizar técnicas como "Lo que fue bien/Lo que se puede mejorar" para guiar la discusión. Se anima a todos a contribuir con sus puntos de vista.

4. **Identificación de Acciones de Mejora**: Con base en la discusión, identificar acciones concretas que el equipo puede implementar para mejorar en el próximo sprint o ciclo de trabajo.

5. **Documentación y Compromiso**: Registrar las acciones de mejora acordadas y asignar responsabilidades para su seguimiento.

6. **Retroalimentación sobre la reunión**: Finalmente, recoger comentarios sobre cómo se desarrolló la retrospectiva misma, para mejorar continuamente esta ceremonia.

#### Duración

- **Tiempo estimado**: La duración recomendada es de una hora.

#### Importancia del Ambiente

- **Confianza y Respeto**: Es fundamental que la Retrospectiva se desarrolle en un ambiente de confianza y respeto, donde todos se sientan cómodos para expresar sus opiniones sin temor a represalias o críticas.

La Retrospectiva es una herramienta clave para el desarrollo ágil, pues permite al equipo reflexionar sobre su manera de trabajar y buscar activamente formas de mejorar. Su éxito depende de la participación honesta y abierta de todos los miembros del equipo y del compromiso conjunto hacia la mejora continua.

### Planificación Ad-hoc

La reunión de Planificación Ad-hoc es una ceremonia clave en el marco de trabajo de Kanban, diseñada para abordar la planificación de trabajos y proyectos específicos que requieren atención y coordinación especial. Esta reunión se convoca según sea necesario, en lugar de seguir un horario regular, y sirve para asegurar que el equipo aborde de manera efectiva los desafíos emergentes o las oportunidades únicas que se presentan.

#### Objetivo

- **Planificación específica**: Centrarse en la planificación y discusión de tareas o proyectos nuevos y significativos que no forman parte del flujo de trabajo diario regular.
- **Respuesta a cambios o necesidades**: Proporcionar un foro para abordar rápidamente los cambios en las prioridades o para discutir trabajos que requieren una planificación especial.

#### Frecuencia

- **Según sea necesario**: No hay un horario fijo para estas reuniones. Se convocan en respuesta a necesidades específicas del equipo o del proyecto.

#### Participantes

- **Equipo de Desarrollo**: Todos los miembros del equipo de desarrollo relevantes para el trabajo o proyecto en cuestión.
- **Stakeholders clave**: Incluyendo al Product Owner, y posiblemente a clientes o usuarios finales, dependiendo de la naturaleza del proyecto o tarea.
- **Facilitador**: Generalmente, el Scrum Master o un líder de equipo que guía la discusión y mantiene el enfoque en los objetivos de la reunión.

#### Estructura de la Reunión

1. **Definición de Objetivos**: Comenzar con una clara definición de los objetivos de la reunión y los resultados esperados.
2. **Presentación de Proyectos/Tareas**: Introducir y discutir los nuevos ítems de trabajo, proyectos o cambios que requieren planificación.
3. **Análisis y Discusión**: Evaluar las implicaciones, recursos necesarios, posibles desafíos y estrategias para abordar el trabajo.
4. **Planificación y Asignación de Tareas**: Desglosar el trabajo en tareas más pequeñas y asignar responsabilidades y plazos.
5. **Establecimiento de Prioridades**: Priorizar las tareas y determinar cómo se integrarán en el flujo de trabajo actual del tablero Kanban.
6. **Revisión y Confirmación**: Asegurarse de que todos entiendan y estén de acuerdo con el plan y los próximos pasos.

#### Duración

- **Variable según la complejidad**: La duración dependerá de la complejidad y el alcance del trabajo a planificar. Puede variar desde una breve discusión hasta una sesión de varias horas para proyectos más grandes.

#### Importancia

- **Flexibilidad y Respuesta Rápida**: Esta reunión permite al equipo de Kanban ser ágil y responder rápidamente a las oportunidades o desafíos inesperados.
- **Enfoque en la Calidad y Eficiencia**: Ayuda a asegurar que el trabajo nuevo o complejo se aborde de manera efectiva, manteniendo la calidad y eficiencia del proceso de desarrollo.

La reunión de Planificación Ad-hoc es crucial para mantener la flexibilidad y adaptabilidad en un entorno de Kanban, permitiendo al equipo responder de manera efectiva a las necesidades cambiantes y a los retos específicos del proyecto.

## Stack Tecnológico

En esta sección, se establecen los estándares, tecnologías y herramientas que conforman nuestro Stack Tecnológico.

Cada nuevo proyecto diseñado o desarrollado debe adaptarse y utilizar el Stack Tecnológico definido a continuación.

En casos donde la implementación con este Stack no sea posible, los desarrolladores a cargo del proyecto deben solicitar una reunión de arquitectura ("Architecture Meet"). Durante esta reunión, expondrán los impedimentos para utilizar uno de los Stacks definidos y justificarán las herramientas y tecnologías sugeridas. Solo si la reunión de arquitectura concluye que es necesario incumplir los estándares especificados, se permitirá iniciar el desarrollo o la implementación.

> La convocatoria a la "Architecture Meet" debe cumplir con las pautas establecidas en este documento.

### Asignación de puertos y servicios

A continuación se detallarán en una tabla, las aplicaciones y servios y los puertos asignados para su ejecución.

| Aplicación/Servicio | Puerto |
| ------------------- | ------ |
| App                 | 8000   |
| SDK                 | 8001   |
| WIDGET              | 8002   |
| ADM                 | 8083   |
| BO                  | 8084   |
| ADMIN               | 8085   |
| BACKOFFICE          | 8086   |
| MEET                | 8087   |
| AUTH                | 8088   |
| API-SIGNUP          | 3000   |
| API-EGG             | 3001   |
| API-WEBSOCKET       | 3002   |
| API-AUTH            | 3003   |
| API-USER            | 3004   |
| API-ECOSISTEM       | 3005   |

### Frontend Stack

- Vite
- React
- Gatsby
- NextJS
- React Router
- TanStack Query
- TypeScript
- Styled Components

### Backend Stack

- Next.js
- Fastify
- TypeScript
- Python
- Prisma

### Database Stack

- MySQL
- MongoDB
- Redis

### Cloud Stack

- AWS

### DevOps Stack:

- Grafana
- Kubernetes
- Docker

## Repositorios

En esta sección, se establecen las especificaciones y requerimientos que deben cumplir los nuevos repositorios de software.

Para repositorios existentes, se debe estimar el esfuerzo necesario para adaptarlos a estos estándares y programar dichas tareas en caso de ser viable. Cada repositorio tendrá asignado un "owner" que será responsable de garantizar el cumplimiento de los estándares actuales y futuros detallados en esta guía.

### README.md

Todas las secciones descritas a continuación deben estar presentes en el archivo README.md, salvo que **no** sea necesario o **no** aplique.

````md
# Description:

Breve descripción de la aplicación, su funcionalidad principal y a quien va dirigida.

# Owner

Nombre de la persona responsable del repositorio y enlace a su correo electrónico. Ej: [Nombre](maitlto:user@mail.com)

# Branches

| branch      | description                     | url                                        |
| ----------- | ------------------------------- | ------------------------------------------ |
| main        | A production released branch    | [visit](https://repo-name.egg.live)             |
| demo        | A pre production branch         | [visit](https://demo.repo-name.egg.live)        |
| staging     | A quality assurance test branch | [visit](https://staging.repo-name.egg.live)     |
| development | A development branch            | [visit](https://development.repo-name.egg.live) |

# Development mode:

```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
npm i
npm run dev
```

# Basic Scripts:

- **npm run dev**: Iniciar modo de desarrollo
- **npm run start**: Iniciar aplicación
- **npm run build**: Construir aplicación
- **npm run test:all**: Ejecutar todas las pruebas en modo desarrollo
- **npm run test:ci**: Ejecutar todas las pruebas en modo CI

# Other Scripts

Lista y breve descripción de los demás scripts disponibles en el repositorio.

# Adicional Information

Información adicional que no aplique en las secciones anteriores.
````

### Modo Desarrollo

Todo repositorio de software debe iniciar en modo desarrollo, con todas las configuraciones apuntando al entorno de desarrollo, utilizando solo los comandos especificados a continuación:

```bash
git clone [repo]
cd [repo]
npm i
npm dev
```

### Scripts del Repositorio

Todos los repositorios de software deben contar con los scripts detallados a continuación. Aunque estas funcionalidades no estén disponibles, el script debe enviar un mensaje en consola con la leyenda "No available yet!"

> Esto tiene como objetivo la estandarización y simplificación de los procesos de CI/CD.

El resto de los scripts específicos de cada repositorio y una breve explicación de su funcionalidad deben documentarse en la sección "Other Scripts" del `README.md` del mismo.

#### Basic Scripts

- **npm dev**: Iniciar modo de desarrollo
- **npm start**: Iniciar aplicación en modo producción
- **npm build**: Construir aplicación en modo producción
- **npm test:all**: Ejecutar todas las pruebas en modo desarrollo
- **npm test:ci**: Ejecutar todas las pruebas en modo CI

### Estilo de Código y Formato

Con el fin de estandarizar todo el código generado, todos los repositorios deben contar con herramientas de linteo y formato de código que homogenicen el código según los estándares definidos a continuación:

- **Estilo de código**: JavaScript Standard Style

`.prettierrc.json`

  ```json
  {
      "printWidth": 100,
      "tabWidth": 4,
      "singleQuote": true,
      "semi": false,
      "trailingComma": "all",
      "arrowParens": "always"
  }
  ```

- **Reglas del Linter**:

`eslint.config.js`

  ```json
  {
    "rules": {
      indent: ['error', 4],
      'comma-dangle': 'off',
      "no-console": "warn",
      "no-undef": "warn",
      "no-unused-vars": "warn",
      "no-var": "error",
      "prefer-const": "error",
      "semi": ["error", "never"]
    }
  }
  ```
