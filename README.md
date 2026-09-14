# Curso de Bases de Datos — Relacionales, No Relacionales y Automatización

Curso organizado por concepto, no por motor de base de datos. Cada módulo presenta la teoría de forma agnóstica y luego muestra su implementación en distintas tecnologías (SQL Server, PostgreSQL, MySQL, MongoDB, Redis).

## Requisitos previos

- Conocimientos básicos de lógica y estructuras de datos
- Docker Desktop instalado (para nivel avanzado)
- Cliente SQL de tu preferencia (SSMS, Azure Data Studio, DBeaver, pgAdmin, etc.)

## Cómo usar este repositorio

1. Cloná el repositorio: `git clone <url-del-repo>`
2. Cada carpeta numerada es un módulo, a recorrer en orden
3. Empezá por `teoria.md` dentro de cada módulo antes de ver el código
4. Los ejercicios están en `ejercicios/`, las soluciones en `ejercicios/soluciones/` (no las mires antes de intentarlo)
5. El proyecto final integra los conceptos de todo el curso

## Índice

### Nivel básico

| Módulo | Tema |
|--------|------|
| [00 - Fundamentos](nivel-basico/00-fundamentos) | Bases de datos relacionales vs no relacionales |
| [01 - Modelo relacional](nivel-basico/01-modelo-relacional) | Tablas, claves, normalización, modelo ER |
| [02 - CRUD básico](nivel-basico/02-crud-basico) | INSERT, UPDATE, DELETE, SELECT |
| [03 - Transacciones](nivel-basico/03-transacciones) | ACID, COMMIT, ROLLBACK |
| [04 - Consultas avanzadas](nivel-basico/04-consultas-avanzadas) | JOINs, subconsultas, agregaciones |
| [05 - Modelado no relacional](nivel-basico/05-modelado-no-relacional) | Documentos, clave-valor |
| [06 - Índices y performance](nivel-basico/06-indices-y-performance) | Índices, planes de ejecución |
| [07 - Programabilidad](nivel-basico/07-programabilidad) | Procedimientos, funciones, triggers |

### Nivel avanzado

| Módulo | Tema |
|--------|------|
| [08 - Triggers y Jobs](nivel-avanzado/08-triggers-y-jobs) | Automatización nativa del motor |
| [09 - Contenedores (Docker)](nivel-avanzado/09-contenedores-docker) | Levantar entornos de BD con Docker |
| [10 - Automatización con n8n](nivel-avanzado/10-automatizacion-n8n) | Workflows, orquestación externa |
| [11 - IA aplicada a datos](nivel-avanzado/11-ia-aplicada-a-datos) | Prompts para validación, consultas y auditoría |

## Proyecto final

[Proyecto final](proyecto-final) - Integra modelado, CRUD, transacciones, automatización e IA

## Convenciones del repositorio

- Cada módulo mantiene la misma estructura: `teoria.md`, subcarpetas por motor/herramienta, `ejercicios/`
- Los scripts SQL dentro de cada módulo están numerados (01-, 02-) para respetar el orden de ejecución
- Las soluciones de ejercicios están siempre en una subcarpeta separada (`ejercicios/soluciones/`)
- Los datasets pesados no se versionan en el repo; los links de descarga están en `00-fundamentos/recursos`
