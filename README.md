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

## Índice

- [Development guide](#development-guide)
  - [Acerca de esta guía](#acerca-de-esta-guía)
  - [Índice](#índice)
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
  - [Stack Tecnológico](#stack-tecnológico)
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
- Si un desarrollador no puede asistir a una sesión de PP o necesita terminarla antes, debe informarlo con anticipación y reprogramar la sesión o el tiempo restante. Incumplimientos reiterados deben ser comunicados al líder del equipo.
- No cumplir con las horas mensuales de PP o las normas establecidas será considerado negativamente en la evaluación de desempeño.

## Stack Tecnológico

En esta sección, se establecen los estándares, tecnologías y herramientas que conforman nuestro Stack Tecnológico.

Cada nuevo proyecto diseñado o desarrollado debe adaptarse y utilizar el Stack Tecnológico definido a continuación.

En casos donde la implementación con este Stack no sea posible, los desarrolladores a cargo del proyecto deben solicitar una reunión de arquitectura ("Architecture Meet"). Durante esta reunión, expondrán los impedimentos para utilizar uno de los Stacks definidos y justificarán las herramientas y tecnologías sugeridas. Solo si la reunión de arquitectura concluye que es necesario incumplir los estándares especificados, se permitirá iniciar el desarrollo o la implementación.

> La convocatoria a la "Architecture Meet" debe cumplir con las pautas establecidas en este documento.

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

```md
# Description:

Breve descripción de la aplicación, su funcionalidad principal y a quien va dirigida.

# Owner

Nombre de la persona responsable del repositorio y enlace a su correo electrónico.

# Main Branches

- **development**: A development branch
- **staging**: A quality assurance test branch
- **demo**: A pre production branch
- **main**: A production released branch

# Development mode:

Instrucciones para clonar y lanzar el modo desarrollo del repositorio.

# Basic Scripts:

- **npm dev**: Iniciar modo de desarrollo
- **npm start**: Iniciar aplicación
- **npm build**: Construir aplicación
- **npm test:all**: Ejecutar todas las pruebas en modo desarrollo
- **npm test:ci**: Ejecutar todas las pruebas en modo CI

# Other Scripts

Lista y breve descripción de los demás scripts disponibles en el repositorio.

# Adicional Information

Información adicional que no aplique en las secciones anteriores.
```

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

Con el fin de estandarizar todo el código generado, todos los repositorios deben contar con herramientas de linteo y formateadores de código que homogenicen el código según los estándares definidos a continuación:

- **Estilo de código**: JavaScript Standard Style
- **Reglas del Linter**:

  ```json
  {
    "rules": {
      "semi": [2, "never"],
      "no-var": "warn",
      "no-console": "warn",
      "no-unused-vars": "warn",
      "no-undef": "warn"
    }
  }
  ```
