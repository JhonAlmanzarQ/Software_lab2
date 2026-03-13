# 📚 Demo Académico — Lab 02

Proyecto desarrollado para el **Lab 02 de Ingeniería de Software III**, orientado a la evolución del módulo **Estudiantes** sobre la base del proyecto anterior. En este laboratorio se fortaleció la API incorporando **paginación**, **manejo global de errores**, **validaciones**, **seeder con Faker** y **pruebas desde Swagger**. :contentReference[oaicite:0]{index=0}

El laboratorio propone dos caminos de implementación: **Opción A** con DTOs, `ApiResponse` y `GlobalExceptionHandler`, u **Opción B** con entidad directa, excepciones propias y manejo global de errores. En ambos casos, se busca una API más robusta, mantenible y fácil de probar. :contentReference[oaicite:1]{index=1}

## 🚀 Tecnologías usadas

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Spring Validation
- Springdoc OpenAPI / Swagger
- Java Faker
- Maven

Estas tecnologías coinciden con la configuración mínima pedida en el laboratorio para soportar persistencia, validación, documentación y generación de datos de prueba. :contentReference[oaicite:2]{index=2}

## 🏗️ Enfoque del laboratorio

Este laboratorio parte del proyecto base `demo-academico` y extiende el módulo de estudiantes con mejoras de calidad en la API. Entre los resultados esperados están la **regla de email único**, la **paginación con `Pageable`**, el **manejo global de errores**, el **seeder configurable** y la validación del funcionamiento desde Swagger. :contentReference[oaicite:3]{index=3}

## ⚙️ Funcionalidades

- Registro de estudiantes
- Listado paginado de estudiantes
- Validación de email único
- Manejo global de errores
- Validaciones de entrada
- Seeder con Faker configurable
- Pruebas desde Swagger

## ▶️ Cómo ejecutar

1. Clona el repositorio.
2. Abre el proyecto en tu IDE.
3. Verifica que tengas **Java 21** instalado.
4. Ejecuta la aplicación con Maven o directamente desde Spring Boot.
5. Prueba la API desde Swagger y revisa la base de datos en H2.

## 🔗 Rutas útiles

- `http://localhost:8080/swagger-ui.html` → Swagger UI
- `http://localhost:8080/h2-console` → Consola H2

Según el enunciado, la aplicación usa H2 en memoria con la URL `jdbc:h2:mem:demoacademico`, y Swagger debe quedar disponible en `/swagger-ui.html`. :contentReference[oaicite:4]{index=4}

## ✨ Autor

Proyecto realizado como práctica académica para la materia **Ingeniería de Software III**.
