# Demo Académico – Lab 02 (Opción A)

Proyecto en **Spring Boot** que expone una **API REST** para la gestión de estudiantes, usando **H2 en memoria** y siguiendo la **Opción A** del laboratorio: respuestas estandarizadas y uso de **DTOs** para desacoplar el contrato de la API de las entidades internas.

## Tecnologías
- Java + Spring Boot
- Spring Web
- Spring Data JPA
- Validación (Bean Validation)
- H2 Database (in-memory)
- Swagger / OpenAPI

## Funcionalidades principales
- CRUD de estudiantes (crear, listar, buscar por id, actualizar, eliminar).
- **Paginación** en el listado usando `Pageable`.
- **Validación** de datos de entrada.
- Manejo **global de excepciones** con respuestas de error claras.
- Respuestas consistentes mediante un wrapper tipo **`ApiResponse`** (Opción A).
