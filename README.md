# ✈️ Flight Finder App

Aplicación web para la búsqueda de vuelos económicos desarrollada bajo una arquitectura de microservicios.  
El sistema permite a los usuarios registrarse, autenticarse y realizar búsquedas de vuelos aplicando distintos filtros como destino, fecha y precio.

---

## 🏗️ Arquitectura del Proyecto

El sistema está dividido en microservicios independientes que se comunican mediante API REST, permitiendo escalabilidad, mantenimiento modular y separación de responsabilidades.

Estructura general:

- 📦 [flight-finder-ms-bd](https://github.com/tu-usuario/flight-finder-ms-bd)
- 🔐 [flight-finder-ms-login](https://github.com/tu-usuario/flight-finder-ms-login)
- 🔎 [flight-finder-ms-search](https://github.com/tu-usuario/flight-finder-ms-search)
- 👤 [flight-finder-ms-users](https://github.com/tu-usuario/flight-finder-ms-users)
- 🎨 [flight-finder-front](https://github.com/tu-usuario/flight-finder-front)


Cada servicio puede ejecutarse de manera independiente.

---

## 📚 Descripción de Servicios

### 🗄️ flight-finder-ms-bd
Microservicio encargado de:
- Configuración y conexión a la base de datos
- Definición de modelos y entidades
- Gestión de persistencia de información

### 🔐 flight-finder-ms-login
Servicio encargado de:
- Autenticación de usuarios
- Generación y validación de tokens JWT
- Protección de rutas privadas

### 🔎 flight-finder-ms-search
Microservicio encargado de:
- Lógica de búsqueda de vuelos
- Aplicación de filtros (destino, precio, fecha, categoría)
- Consulta de información en la base de datos

### 👤 flight-finder-ms-users
Servicio encargado de:
- Registro de usuarios
- Consulta y actualización de perfiles
- Gestión básica de información del usuario

### 🎨 flight-finder-front
Aplicación frontend desarrollada en Angular para:
- Registro e inicio de sesión
- Búsqueda y visualización de vuelos
- Gestión de perfil de usuario

---

## ⚙️ Tecnologías Utilizadas

### 🔹 Backend
- Java y Spring Boot
- JPA (Hibernate)
- Arquitectura REST
- JWT (JSON Web Token)
- Microservicios feign para comunicación entre servicios

### 🔹 Base de Datos
- (Especificar: PostgreSQL)

### 🔹 Frontend
- Angular

### 🔹 Arquitectura
- Microservicios desacoplados
- Separación de responsabilidades
- Comunicación vía HTTP (REST APIs)

---

## 🔐 Seguridad

- Autenticación basada en JWT
- Validación de datos en cada servicio
- Protección de endpoints privados
- Manejo independiente de responsabilidades por microservicio

---
