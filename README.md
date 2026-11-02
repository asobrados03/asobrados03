# Alfredo Sobrados González

### Backend Engineer · APIs · Software Architecture · AI-assisted Systems

Desarrollo APIs y servicios backend con **Java, Spring Boot, Python, FastAPI y Node.js**, prestando especial atención a la seguridad, la arquitectura y las pruebas automatizadas. También tengo experiencia desarrollando aplicaciones web y multiplataforma con **React, TypeScript y Kotlin Multiplatform** para Android e iOS.

Me interesa construir software fácil de entender, probar y evolucionar, tomando decisiones técnicas que faciliten su mantenimiento a largo plazo. También me interesa explorar aplicaciones prácticas de la inteligencia artificial con evaluación reproducible, revisión humana y controles de seguridad.

[**🌐 Portfolio web**](https://alfredo-sobrados-portfolio.vercel.app/) **·** [**💼 LinkedIn**](https://www.linkedin.com/in/alfredo-sobrados-gonzalez/)

---

## Proyectos destacados

Estos proyectos representan distintas facetas de mi experiencia: diseño de APIs backend, sistemas de triaje asistido por IA, desarrollo multiplataforma e integración de servicios web. En mi [portfolio web](https://alfredo-sobrados-portfolio.vercel.app/) puedes conocer más detalles sobre mi trabajo.

### 1. Sistema inteligente de triaje de incidencias

MVP para registrar incidencias, generar una propuesta automática de triaje y permitir que una persona la acepte o la corrija.

El proyecto separa la entrada, el análisis, la persistencia y la revisión humana. Incluye un analizador determinista basado en reglas, integración opcional con Ollama, autenticación JWT con roles, auditoría, retención de datos, evaluación offline y un frontend para consultar y revisar incidencias.

**Tecnologías:** Python, FastAPI, Pydantic, SQLAlchemy, SQLite, React, TypeScript, Vite, Tailwind CSS, TanStack Query, JWT, Ollama, pytest, Vitest, Docker y GitHub Actions.

[Consultar el repositorio](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/ai-incident-triage" label="asobrados03/ai-incident-triage" />)

### 2. Human Perform Platform

Plataforma para la gestión integral de un centro deportivo, iniciada durante mis prácticas profesionales y ampliada posteriormente como Trabajo Fin de Grado (TFG).

Combina una aplicación multiplataforma para Android e iOS con una API REST desacoplada. Comparte más del 70 % del código entre ambas plataformas y aplica principios de Clean Architecture y arquitectura hexagonal.

**Tecnologías:** Kotlin Multiplatform, Jetpack Compose, SwiftUI, Node.js, Express, MariaDB y JWT.

- [Aplicación multiplataforma](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/HumanPerformApp" label="asobrados03/HumanPerformApp" />)
- [API REST](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/api_rest_human_app" label="asobrados03/api_rest_human_app" />)
- [Documentación del TFG](https://uvadoc.uva.es/handle/10324/84418)

### 3. Landing Page: Geotecnia y Servicios

Landing page profesional para presentar servicios, proyectos y trabajos de geotecnia, con un sistema de contacto orientado a la captación de potenciales clientes.

Integra un flujo de contacto de extremo a extremo: validación compartida entre cliente y servidor, protección antispam, envío de correos y archivado opcional de solicitudes. La arquitectura combina un frontend estático con funciones serverless y servicios externos.

**Tecnologías:** React 19, TypeScript, Vite, Tailwind CSS, shadcn/ui, Zod, Vercel, Supabase, Resend, Google reCAPTCHA v3 y Vitest.

[Consultar el repositorio](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/geotecnia-servicios-landing" label="asobrados03/geotecnia-servicios-landing" />)

### 4. HotelManagementAPI

API REST para gestionar clientes, habitaciones, reservas, pagos y administradores. Un proyecto personal con el que profundizo en el diseño de servicios backend seguros, la arquitectura y la calidad del código.

Utiliza JDBC directamente, sin ORM, y una arquitectura hexagonal que separa el dominio, los casos de uso y la infraestructura. También incorpora Redis para la caché de disponibilidad y RabbitMQ para desacoplar el procesamiento de notificaciones.

**Tecnologías:** Java 21, Spring Boot, Spring Security, JWT, JDBC, MariaDB, Redis, RabbitMQ, Docker, OpenAPI, JUnit 5, Mockito y Testcontainers.

[Consultar el repositorio](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/HotelManagementAPI" label="asobrados03/HotelManagementAPI" />)

---

## Competencias técnicas

| Área | Tecnologías y conocimientos |
| --- | --- |
| Backend | Java, Spring Boot, Python, FastAPI, Node.js, Express, APIs REST |
| Arquitectura y calidad | Arquitectura hexagonal, Clean Architecture, separación de responsabilidades, diseño por capas, pruebas automatizadas |
| Inteligencia artificial | Integración con Ollama, análisis estructurado, evaluación offline, métricas de clasificación, revisión humana |
| Seguridad | Spring Security, autenticación y autorización con JWT, roles, validación de configuración, auditoría |
| Bases de datos | SQL, MariaDB, PostgreSQL, SQLite, SQLAlchemy, JDBC |
| Mensajería y caché | RabbitMQ, Redis |
| Frontend | React, TypeScript, Vite, Tailwind CSS, shadcn/ui, TanStack Query |
| Infraestructura y herramientas | Docker, GitHub Actions, Gradle, Git, OpenAPI/Swagger |
| Desarrollo multiplataforma | Kotlin Multiplatform, Jetpack Compose, SwiftUI |

---

## Otros proyectos y prácticas

Además de los proyectos destacados, he desarrollado proyectos personales y académicos que me han permitido trabajar con distintas tecnologías y reforzar mis fundamentos de ingeniería de software.

- [**Banana Bank — experiencia de hackathon**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/banana-bank-hackathon-case-study" label="asobrados03/banana-bank-hackathon-case-study" />) — Caso de estudio de una aplicación bancaria ficticia con asistente de IA. Trabajé en la confirmación de transferencias, la prevención de duplicados, la recuperación ante fallos y la trazabilidad de las fuentes de información.
- [**Energy Deficit**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/energy-deficit" label="asobrados03/energy-deficit" />) — Herramienta CLI en Python para calcular la energía adicional necesaria para cubrir la demanda eléctrica española cuando la generación eólica es la única fuente disponible, utilizando datos de ESIOS/REE.
- [**Finanzas Personales**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/Finanzas_Personales" label="asobrados03/Finanzas_Personales" />) — Aplicación Android en Kotlin y Jetpack Compose para gestionar ingresos, gastos, presupuestos y estadísticas, siguiendo MVVM y Repository.
- [**PetAdopt**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/PetAdopt" label="asobrados03/PetAdopt" />) — Aplicación web empresarial para facilitar la adopción de mascotas, desarrollada en equipo con Java EE 7, PrimeFaces, JPA y PostgreSQL.
- [**Centro de Convenciones**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/Practica_FINAL_CentroDeConvenciones" label="asobrados03/Practica_FINAL_CentroDeConvenciones" />) — Aplicación Java para gestionar espacios, reservas, productos y aspectos económicos mediante programación orientada a objetos y patrones de diseño.
- [**Notificador de Avisos**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/TWEB-Notificador-Avisos" label="asobrados03/TWEB-Notificador-Avisos" />) — Aplicación web para que los profesores publiquen avisos dirigidos a sus estudiantes, desarrollada con PHP y tecnologías web.
- [**Estructuras de Datos**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/Practicas-Programacion-y-Estructuras-de-Datos" label="asobrados03/Practicas-Programacion-y-Estructuras-de-Datos" />) — Colección de ejercicios de Java sobre listas enlazadas, pilas, colas, árboles y otras estructuras de datos.
- [**Sistemas Distribuidos**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/Practicas_Sistemas_Distribuidos" label="asobrados03/Practicas_Sistemas_Distribuidos" />) — Prácticas de concurrencia y comunicación cliente-servidor con Java, `Thread`, `Runnable` y WebSockets.
- [**Arkanoid**](<copilot-ref kind="repo" target-id="https://github.com/asobrados03/PracticaFinalArkanoid" label="asobrados03/PracticaFinalArkanoid" />) — Recreación del clásico videojuego con Java, Swing y AWT, como práctica de desarrollo de aplicaciones de escritorio.

---

## Sobre mí

Soy ingeniero informático orientado al desarrollo backend, el diseño de APIs y la arquitectura de software. Me interesa participar en decisiones técnicas y construir servicios seguros, mantenibles y fáciles de probar.

Mi experiencia abarca Java y Spring Boot, Python y FastAPI, Node.js, desarrollo frontend con React y TypeScript, así como desarrollo multiplataforma con Kotlin Multiplatform. También me interesa aplicar la inteligencia artificial de forma responsable, con contratos estructurados, evaluación reproducible, trazabilidad y revisión humana.

Valoro el código legible, la separación clara de responsabilidades y las pruebas que permiten evolucionar un sistema con confianza. Mi experiencia en desarrollo multiplataforma y web también me ayuda a comprender cómo se integran los servicios backend con las aplicaciones que utilizan las personas.

### ¿Quieres conocer mejor mi trabajo?

Visita mi [**portfolio web**](https://alfredo-sobrados-portfolio.vercel.app/) para explorar mis proyectos destacados y conocer más sobre las decisiones técnicas detrás de cada uno.

También puedes contactar conmigo a través de [LinkedIn](https://www.linkedin.com/in/alfredo-sobrados-gonzalez/).

<!-- 

### 3. [App: Nombre de la App](enlace-al-repositorio)

**Descripción:** Un breve resumen de la aplicación.  
**Tecnologías:** Herramientas y lenguajes utilizados.  
**Características destacadas:**  

- Funcionalidades principales de la app.  
- Qué aprendí o implementé nuevo en este proyecto.

### 5. [Proyecto Personal: Nombre del Proyecto](enlace-al-repositorio)

**Descripción:** Explicación breve del proyecto personal.  
**Motivación:** Por qué lo creé y qué buscaba lograr.  
**Tecnologías:** Lista de herramientas y lenguajes utilizados. 
-->

<!--
**asobrados03/asobrados03** is a ✨ *special* ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
