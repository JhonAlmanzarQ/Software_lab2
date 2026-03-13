# 📚 Demo Académico — Lab 02

Proyecto desarrollado para el **Lab 02 de Ingeniería de Software III**, orientado a la evolución del módulo **Estudiantes** sobre la base del proyecto anterior. En este laboratorio se fortaleció la API incorporando **paginación**, **manejo global de errores**, **validaciones**, **seeder con Faker** y **pruebas desde Swagger**.

El objetivo es construir una API más robusta, mantenible y fácil de probar, aplicando buenas prácticas en la organización del código y en el tratamiento de errores y validaciones.

## 🚀 Tecnologías usadas

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Spring Validation
- Swagger / OpenAPI
- Java Faker
- Maven

## 🏗️ Enfoque del laboratorio

Este laboratorio parte del proyecto base `demo-academico` y extiende el módulo de estudiantes con mejoras de calidad en la API. Entre los principales cambios se encuentran la **paginación con `Pageable`**, el **manejo global de errores**, la **validación de datos de entrada**, la **regla de email único** y la generación de datos de prueba con **Faker**.

## ⚙️ Funcionalidades

- Registrar estudiantes
- Listar estudiantes con paginación
- Validar email único
- Manejar errores de forma global
- Validar datos de entrada
- Precargar datos de prueba
- Probar endpoints desde Swagger

## ▶️ Cómo ejecutar

1. Clona el repositorio.
2. Abre el proyecto en tu IDE.
3. Verifica que tengas **Java 21** instalado.
4. Ejecuta la aplicación con Maven o directamente desde Spring Boot.
5. Accede a Swagger y H2 para probar y revisar el funcionamiento del proyecto.

## 🔗 Rutas útiles

- `http://localhost:8080/swagger-ui.html` → Swagger UI
- `http://localhost:8080/h2-console` → Consola H2

## ✨ Autor

Proyecto realizado como práctica académica para la materia **Ingeniería de Software III**.
