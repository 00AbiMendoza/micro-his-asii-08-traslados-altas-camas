# Micro-HIS ASII-08 — Traslados, altas y liberación de camas

Proyecto individual para el curso Análisis de Sistemas II.

## Estudiante

- Esaú Abimael de la Cruz Mendoza
- GitHub: 00AbiMendoza

## Módulo

ASII-08 — Traslados, altas y liberación de camas.

## Flujo

Traslado o alta del paciente con liberación consistente de cama.

## Requisitos técnicos

- PHP 8.2 o superior
- PHP vanilla, sin frameworks
- Capas Presentation, Application, Domain y Persistence
- PDO con sentencias preparadas
- SQLite para persistencia local
- Pruebas automatizadas
- Datos exclusivamente ficticios

## Arquitectura

- `src/Presentation`: entrada y salida de la aplicación.
- `src/Application`: casos de uso.
- `src/Domain`: entidades, reglas e interfaces.
- `src/Persistence`: acceso a datos mediante PDO.
- `config`: configuración externa.
- `database`: scripts y base SQLite local.
- `tests`: pruebas automatizadas.
- `docs/diagramas`: fuentes editables y diagramas.
- `evidencia`: evidencia técnica y Git.
