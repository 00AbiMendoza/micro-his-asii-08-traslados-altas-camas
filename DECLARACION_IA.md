# DECLARACION DE USO DE INTELIGENCIA ARTIFICIAL

## Herramienta utilizada

ChatGPT de OpenAI.

## Proposito de uso

La herramienta de inteligencia artificial fue utilizada como apoyo durante el desarrollo del ejercicio "Micro-HIS Traslados, altas y liberacion de camas".

Su uso se concentro en:

- orientar la estructura inicial del proyecto;
- proponer una separacion entre Presentation, Application, Domain y Persistence;
- apoyar la implementacion de los casos de uso de traslado y alta;
- revisar la aplicacion de transacciones con PDO;
- proponer pruebas automatizadas;
- apoyar la documentacion tecnica y los diagramas PlantUML;
- orientar el uso de Git para conservar evidencia del desarrollo.

## Prompts relevantes utilizados

Entre las solicitudes realizadas a la herramienta se encuentran:

1. Solicitar una guia paso a paso para construir un Micro-HIS en PHP 8.2 o superior sin utilizar frameworks.
2. Solicitar una estructura que separara las capas Presentation, Application, Domain y Persistence.
3. Solicitar apoyo para implementar el traslado de un paciente liberando consistentemente la cama de origen.
4. Solicitar apoyo para implementar el alta de un paciente y el cambio de estado de la cama.
5. Solicitar pruebas para camino feliz, regla de dominio y error de persistencia.
6. Solicitar diagramas editables en PlantUML de la arquitectura y del flujo funcional.

## Partes aceptadas y modificadas

Se aceptaron como base varias propuestas de estructura, nombres de clases, casos de uso, repositorios, pruebas y diagramas.

Las propuestas fueron ejecutadas y revisadas manualmente durante el desarrollo. Se realizaron ajustes cuando fue necesario, por ejemplo en la sintaxis del diagrama PlantUML para lograr compatibilidad con la herramienta instalada.

## Validacion humana

El estudiante realizo la validacion de los resultados mediante:

- ejecucion de PHP desde consola;
- validacion de sintaxis con `php -l`;
- ejecucion real de un traslado sobre SQLite;
- consulta posterior del estado de las camas y la admision;
- ejecucion de pruebas automatizadas;
- verificacion de 4 pruebas aprobadas y 0 fallidas;
- generacion local de los diagramas PlantUML;
- revision del historial y estado del repositorio Git.

La inteligencia artificial fue utilizada como herramienta de apoyo. La revision, ejecucion, validacion y entrega final son responsabilidad del estudiante.
