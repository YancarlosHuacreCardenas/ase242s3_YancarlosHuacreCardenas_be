# ase242s3_YancarlosHuacreCardenas_be
# ASE242S3 - Yancarlos Huacre Cardenas - Backend

Este proyecto es un ejemplo básico de un **endpoint en Spring Boot** que devuelve un mensaje "Hola Mundo".

---

## 🚀 Tecnologías usadas
- Java 17
- Spring Boot 3.5.4
- Maven

---

## 📌 Pasos realizados para la actividad

1. Ingresé a [Spring Initializr](https://start.spring.io/) y configuré el proyecto con:
   - **Project:** Maven
   - **Language:** Java
   - **Spring Boot:** 3.5.4
   - **Group:** vallegrande.edu.pe
   - **Artifact:** demo
   - **Packaging:** Jar
   - **Java:** 17
2. Añadí la dependencia `spring-boot-starter-web` en el archivo `pom.xml`.
3. Creé el controlador `HolaMundoController.java` con la anotación `@RestController` y el método `@GetMapping("/hola")` que devuelve `"Hola Mundo!"`.
4. Ejecuté el proyecto con `mvn spring-boot:run` y probé en el navegador [http://localhost:8080/hola](http://localhost:8080/hola).
5. Subí el código fuente al repositorio de GitHub con el nombre **ase242s3_YancarlosHuacreCardenas_be**.

---

## 📷 Evidencia de ejecución
*(Aquí puedes poner capturas de pantalla del endpoint funcionando)*

---

## 📜 Licencia
Este proyecto es solo para fines educativos.
