# API REST de Artículos – Spring Boot + MySQL

**Alumno:** José Carlos Peralta
**Curso:** Talento Tech – Back-End Java – Comisión 26223

##  Video demostrativo
https://drive.google.com/file/d/1oJbJiuLACnj7WtDO8Z_hrlvlqsKyVLno/view?usp=sharing 

## Descripción
API REST que permite crear, listar, consultar, modificar y eliminar artículos (CRUD), con persistencia en una base de datos MySQL. Está organizada con el patrón Modelo-Vista-Controlador: controller, service, repository y model.

## Tecnologías
- Java 17
- Spring Boot 3.2.5
- Spring Web
- Spring Data JPA (Hibernate)
- MySQL
- Maven

## Endpoints
| Método | Ruta | Acción |
|---|---|---|
| GET | /api/articulos | Listar todos |
| GET | /api/articulos/{id} | Obtener por ID |
| POST | /api/articulos | Crear |
| PUT | /api/articulos/{id} | Actualizar |
| DELETE | /api/articulos/{id} | Eliminar |

## Cómo ejecutarlo
1. Crear la base de datos: `CREATE DATABASE articulos_db;`
2. Configurar usuario y contraseña en `src/main/resources/application.properties`
3. Ejecutar `ArticuloApiApplication.java`
4. La API queda disponible en `http://localhost:8080/api/articulos`
