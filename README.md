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

## Índice de temas:
1. El desarrollador
    1. Habilidades requeridas
    2. Crecimiento y Performance
3. El equipo de desarrollo 
4. El stack tecnológico   
5. Los repositorios
    1. Modo desarrollo
    2. Repository sripts
    3. Code styling & format
    4. README.md
7. Las ceremonias
    1. Daily meet
    2. Retrospective Meet
    3. Architecture Meet
    4. Refinement Meet
9. El flujo de trabajo
    1. Pair programming
11. El producto desarrollado

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

## Stack Tecnológico

En esta sección, se establecen los estándares, tecnologías y herramientas que conforman nuestro Stack Tecnológico.

Cada nuevo proyecto diseñado o desarrollado debe adaptarse y utilizar el Stack Tecnológico definido a continuación.

En casos donde la implementación con este Stack no sea posible, los desarrolladores a cargo del proyecto deben solicitar una reunión de arquitectura ("Architecture Meet"). Durante esta reunión, expondrán los impedimentos para utilizar uno de los Stacks definidos y justificarán las herramientas y tecnologías sugeridas. Solo si la reunión de arquitectura concluye que es necesario incumplir los estándares especificados, se permitirá iniciar el desarrollo o la implementación.

> La convocatoria a la "Architecture Meet" debe cumplir con las pautas establecidas en este documento.

### Frontend Stack:
- Vite
- React
- Gatsby
- NextJS
- React Router
- TanStack Query
- TypeScript
- Styled Components

### Backend Stack:
- Next.js
- Fastify
- TypeScript
- Python
- Prisma

### Database Stack:
- MySQL
- MongoDB
- Redis

### Cloud Stack:
- AWS

### DevOps Stack:
- Grafana
- Kubernetes
- Docker


## Repositorios

En esta sección, se establecen las especificaciones y requerimientos que deben cumplir los nuevos repositorios de software.

Para repositorios existentes, se debe estimar el esfuerzo necesario para adaptarlos a estos estándares y programar dichas tareas en caso de ser viable. Cada repositorio tendrá asignado un "owner" que será responsable de garantizar el cumplimiento de los estándares actuales y futuros detallados en esta guía.

### README.md

En esta sección se definen la anatomía básica del archivo README de cada repositorio con el objetivo de facilitar su uso.

Todas las secciones descritas a continuación deben estar presentes en el archivo README.md, salvo que no sea necesario o aplique.

```md
# Description:
Breve descripción de la aplicación y su funcionalidad principal.

# Owner
Nombre de la persona responsable del repositorio y su correo electrónico.

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
- **npm start**: Iniciar aplicación
- **npm build**: Construir aplicación
- **npm test:all**: Ejecutar todas las pruebas en modo desarrollo
- **npm test:ci**: Ejecutar todas las pruebas en modo CI

### Estilo de Código y Formato

Con el fin de estandarizar todo el código generado, todos los repositorios deben contar con herramientas de linteo y formateadores de código que homogenicen el código según los estándares definidos a continuación:

Estilo de código: JavaScript Standard Style
Reglas del Linter:

```json
{
    "rules": {
        "no-console": "warn",
    }
}
```
