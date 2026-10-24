# Hola, soy Roycer Cervantes

**Desarrollador de software junior · Backend con Java (Spring Boot) y Node.js · Bases de datos MySQL**

Santa Marta, Colombia · Español nativo · Inglés B1

Me formo como **Tecnólogo en Análisis y Desarrollo de Software (SENA)** y estudio **Ingeniería Ambiental y Sanitaria en la Universidad del Magdalena**. Esa mezcla es lo que me diferencia: construyo software para problemas reales, sobre todo de gestión ambiental, entendiendo tanto el código como el tema que resuelve.

También soy **Técnico en Diseño e Integración de Multimedia (SENA)**, así que cuido la parte visual y la experiencia de usuario de lo que hago.

---

### Tecnologías

**Backend:** ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white)

**Bases de datos:** ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

**Otros lenguajes:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

**Pruebas y documentación:** ![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?logo=postman&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black)

**Herramientas:** ![Maven](https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

---

### Proyecto principal: Plataforma Digital para la Gestión de Proyectos de Impacto Ambiental

Un sistema completo, construido por módulos, para que las empresas y consultores ambientales registren sus proyectos, evalúen los impactos, planeen las medidas de manejo y controlen el cumplimiento de la norma en sus monitoreos. Todos los módulos comparten la misma base de datos MySQL.

| Módulo | Qué hace | Tecnologías |
|---|---|---|
| [API REST](https://github.com/royzeer/plataforma-impacto-ambiental-api) | Backend de toda la plataforma: 34 servicios con JWT, roles, matriz de impactos, monitoreos y reportes | Node.js, Express, MySQL, Swagger, Jest |
| [Monitoreo ambiental](https://github.com/royzeer/plataforma-ambiental-monitoreo) | Aplicación web para registrar mediciones (pH, DBO5, oxígeno disuelto...) y alertar incumplimientos de norma | Java 17, Spring Boot 3, Thymeleaf, JPA, JUnit 5 |
| [Gestión de proyectos web](https://github.com/royzeer/plataforma-ambiental-servlets) | CRUD web de proyectos ambientales con búsqueda y validaciones del lado del servidor | Java, Servlets, JSP, JSTL, JDBC, Tomcat |
| [Núcleo de proyectos (consola)](https://github.com/royzeer/plataforma-impacto-ambiental-jdbc) | Primera versión del módulo de proyectos con patrón DAO y JDBC puro | Java, JDBC, MySQL, Maven |

#### Detalle de la [API REST](https://github.com/royzeer/plataforma-impacto-ambiental-api)

API para gestionar proyectos ambientales de principio a fin: identificación de impactos, plan de manejo y monitoreos de calidad del agua.

- Autenticación con **JWT + bcrypt** y permisos por rol (admin, gestor, consultor).
- **34 servicios REST** con filtros, paginación y un formato de respuesta único.
- Lógica del dominio ambiental: la API calcula la **importancia del impacto** (magnitud × probabilidad) y evalúa si cada monitoreo (pH, oxígeno disuelto, DBO5…) **cumple la norma**.
- Arquitectura por capas (rutas → controladores → modelos → MySQL) y consultas parametrizadas contra inyección SQL.
- Documentada con **Swagger (OpenAPI 3)**, probada con **Postman/Newman** y con **pruebas automáticas en Jest** que corren en **GitHub Actions**.

`Node.js` `Express` `MySQL` `JWT` `Swagger` `Jest`

---

### Lo que estoy aprendiendo ahora

- Pruebas automáticas y buenas prácticas de APIs.
- Desplegar mis proyectos en la nube para que se puedan probar en línea.
- Seguir mejorando mi inglés técnico.

---

### Contacto

<!-- Pon aquí tu LinkedIn y el correo donde quieres que te escriban las empresas -->
- LinkedIn: _(agrega tu enlace)_
- Correo: _(agrega tu correo de trabajo)_

Abierto a **prácticas (etapa productiva SENA)** y oportunidades como **desarrollador junior**.
