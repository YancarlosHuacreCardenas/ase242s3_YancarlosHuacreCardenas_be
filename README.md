# ase242s3_YancarlosHuacreCardenas_be

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
<img width="1920" height="999" alt="image" src="https://github.com/user-attachments/assets/e87753b4-a3ec-409f-8f88-3dbbe196b1d8" />
<img width="1868" height="563" alt="image" src="https://github.com/user-attachments/assets/66c8f0d4-6b3a-41ef-8b56-0d3bf9b20833" />

---

## 📜 Licencia
Este proyecto es solo para fines educativos.
