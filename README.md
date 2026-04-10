# 💻 Portafolio de Programación

¡Hola! 👋 Soy Alfredo Sobrados, apasionado por la programación, la tecnología y el desarrollo de software. Esto es una recopilación de proyectos y prácticas académicas y extraacadémicas que reflejan mi progreso, aprendizajes y habilidades en diversas tecnologías. 🚀  

## 📂 Índice de Proyectos

### 1. Human Perform Platform  
🔗 Mobile App: [HumanPerformApp](https://github.com/asobrados03/HumanPerformApp)  
🔗 REST API Backend: [api_rest_human_app](https://github.com/asobrados03/api_rest_human_app)

**Descripción:**  
Plataforma completa para la gestión integral de un centro deportivo, desarrollada como proyecto real durante mis prácticas en **Fransdata Tech Ventures** y posteriormente ampliada y finalizada como **Trabajo Final de Grado (TFG)**.  
El sistema está compuesto por una aplicación móvil multiplataforma (Android/iOS) y una API REST segura y escalable que centraliza la lógica de negocio y acceso a datos.

**Tecnologías:**  
- Frontend: Kotlin Multiplatform Mobile (KMM), Jetpack Compose, SwiftUI  
- Backend: Node.js, Express.js  
- Base de datos: MariaDB  
- Seguridad: JWT + Refresh Tokens  
- Arquitectura: Clean Architecture + Hexagonal Architecture

**Objetivo:**  
Diseñar e implementar una solución software multiplataforma real en producción, reutilizando más del 70% del código entre Android e iOS y separando claramente frontend y backend mediante arquitectura desacoplada.

**Características destacadas:**  
- Registro e inicio de sesión seguro con JWT  
- Persistencia cifrada de sesión y credenciales  
- Gestión avanzada de perfiles con subida/edición de imágenes  
- Sistema de entrenadores/profesionales favoritos  
- Backend REST desacoplado con autenticación robusta  
- Interfaz moderna responsive con Material Design 3 y soporte dark mode  

**Qué aprendí:**  
- Desarrollo full-stack móvil + backend en entorno real  
- Diseño de APIs REST seguras y escalables con Node.js  
- Integración KMM compartiendo lógica entre Android/iOS  
- Aplicación práctica de Clean Architecture y principios hexagonales  
- Gestión de un proyecto académico-profesional de gran escala como TFG  

📄 Documentación académica (TFG): Próximamente disponible

---

### 2. [Landing Page: Geotecnia y Servicios](https://github.com/asobrados03/geotecnia-servicios-landing)

**Descripción:** Landing page profesional para empresa de ingeniería geotécnica con sistema completo de generación de leads. La página presenta servicios (estudios geotécnicos, sondeos, ensayos) y cuenta con un formulario de contacto que activa un flujo automatizado de notificaciones por email y almacenamiento de datos.

**Tecnologías:** React 18, TypeScript, Vite, Tailwind CSS, shadcn/ui, Zod, React Hook Form, Vercel (hosting + serverless functions), Supabase (PostgreSQL), Resend (emails), Google reCAPTCHA v3.

**Características destacadas:**
- **Arquitectura Jamstack** con frontend estático y backend serverless completamente separados
- **Sistema anti-spam multicapa** con reCAPTCHA v3 invisible + campo honeypot oculto
- **Validación consistente** usando esquemas Zod compartidos entre cliente y servidor
- **Flujo automatizado completo**: validación → verificación captcha → almacenamiento BD → envío de emails (notificación + confirmación)
- **Optimización de rendimiento** con lazy loading de imágenes, code splitting y CDN de Vercel
- **Manejo robusto de errores** con feedback inmediato al usuario y logging detallado
- **Escalabilidad automática** gracias a funciones serverless y servicios cloud gestionados

**API REST documentada:** Endpoint `POST /api/contact` con validación de entrada, verificación reCAPTCHA, persistencia en Supabase y envío de correos transaccionales. Incluye pruebas unitarias completas con Vitest.

**Implementé:** Integración completa de servicios externos, validación de formularios robusta, arquitectura serverless escalable, y sistema de notificaciones automáticas end-to-end.

---

### 3. [Finanzas Personales](https://github.com/asobrados03/Finanzas_Personales)

**Descripción:** Finanzas Personales es una aplicación Android, diseñada para facilitar la gestión de tus finanzas personales. Implementa la arquitectura MVVM (Model-View-ViewModel) junto con el patrón Repository para garantizar un diseño modular, escalable y fácilmente mantenible. Esta app es mi Práctica Final de Plataformas de Software Móviles.  

**Tecnologías:** Kotlin, Jetpack Compose, Material Design 3, Gradle KTS y Android Studio.

**Puntos clave:**  
- Esta app resuelve el problema de unas finanzas personales mal gestionadas.  
- Principales funcionalidades: Ver, Añadir, Editar y Eliminar tanto transacciones de gasto o ingreso como presupuestos asignados a un mes, año y categoría concreta. Estadísticas para visualizar nuestras finanzas y una página principal que nos da un saldo, ingresos y gastos totales.

---

### 4. [App: HotelManagementAPI](https://github.com/asobrados03/HotelManagementAPI)  
**Descripción:**  
HotelManagementAPI es una API RESTful diseñada para gestionar un hotel, permitiendo la administración de clientes, habitaciones, reservas, pagos y administradores. Implementa autenticación con JWT y sigue una arquitectura limpia para separar la lógica de negocio, la infraestructura y los adaptadores.  

**Motivación:**  
Este proyecto nació como un ejercicio de la comunidad Skool DeHaroHub. Aunque la comunidad ya no está activa, decidí desarrollarlo y publicarlo por mi cuenta como una oportunidad para mejorar mis habilidades en el diseño de APIs RESTful, el manejo de bases de datos con JDBC y la aplicación de buenas prácticas en arquitectura de software.  

**Tecnologías:**  
- **Lenguaje y Framework:** Java 21+ con Spring Boot  
- **Seguridad:** Spring Security con JWT  
- **Base de Datos:** MariaDB en Docker  
- **Persistencia:** JDBC (sin ORM)  
- **Contenedores:** Docker para la base de datos y Adminer  
- **Documentación:** Swagger/OpenAPI  
- **Pruebas:** JUnit5, Mockito, Testcontainers y Postman 
- **Herramientas de construcción:** Gradle  

**Características destacadas:**  
- CRUD completo para clientes, habitaciones, reservas, pagos y administradores.  
- Implementación de autenticación y autorización con JWT.  
- Uso de JDBC en lugar de ORM para mayor control sobre las consultas SQL.  
- Arquitectura limpia y modular basada en principios hexagonales.  
- Configuración con Docker para facilitar la instalación y ejecución.  
- Documentación interactiva con Swagger/OpenAPI.  
- Pruebas unitarias y de integración para garantizar la estabilidad del sistema.  

**¿Qué aprendí con este proyecto?**
- Profundicé en la arquitectura hexagonal y su aplicación en APIs REST.  
- Mejoré el manejo de bases de datos sin ORM utilizando JDBC.  
- Implementé autenticación segura con JWT en Spring Boot.  
- Aprendí a optimizar la estructura del código para mejorar la mantenibilidad y escalabilidad.  

---

### 5. [Práctica Final: Centro de Convenciones](https://github.com/asobrados03/Practica_FINAL_CentroDeConvenciones)

**Descripción:** Este proyecto implementa un sistema de gestión para un Centro de Convenciones utilizando los principios de la Programación Orientada a Objetos (POO) y varios patrones de diseño. Proporciona funcionalidades para gestionar espacios, reservas, productos y aspectos económicos del centro.  

**Objetivo:** En esta práctica aprendí los pilares de la programación orientada a objetos (herencia, polimorfismo y encapsulación) e implemente varios patrones de diseño. 

**Herramientas:** Java y el IDE NetBeans.  

---

### 6. [Práctica Final: Notificador de Avisos](https://github.com/asobrados03/TWEB-Notificador-Avisos)

**Descripción:** La aplicación web permite a los profesores de Tecnologías Web notificar avisos a sus alumnos.

**Tecnologías:** HTML, CSS, PHP, JavaScript, jQuery y un entorno virtual LAMP (Linux, Apache, MySQL y PHP).  

**Objetivo:** Aprender a desarrollar una aplicación web básica y a prepar el entorno virtual de desarrollo.   

---

### 7. [Prácticas sobre Estructuras de Datos](https://github.com/asobrados03/Practicas-Programacion-y-Estructuras-de-Datos)

**Descripción:** Ejercicios y ejemplos prácticos de estructuras de datos en Java.  

**Objetivo:** Fortalecer habilidades en lógica y resolución de problemas.  

**Temas cubiertos:**  
- Listas enlazadas, pilas, colas, árboles binarios, etc.

---

### 8. [Prácticas: Sistemas Distrubuidos](https://github.com/asobrados03/Practicas_Sistemas_Distribuidos)

**Descripción:** Ejercicios prácticos para entender conceptos fundamentales de los Sistemas Distribuidos. 

**Objetivo:** Aprender algunos fundamentos prácticos básicos como la ejecución concurrente de hilos o el paso de mensajes de manera bidireccional entre cliente y servidor.

**Temas cubiertos:** 
- Implementación de tareas concurrentes utilizando la clase `Thread` de Java.
- Uso de la interfaz `Runnable` para manejar tareas concurrentes.
- Implementación de un servidor y cliente de Web Sockets en Java.

---

### 9. [Práctica Final: Arkanoid](https://github.com/asobrados03/PracticaFinalArkanoid)

**Descripción:** Este práctica final es una replica del mítico juego Arkanoid desarrollado en Java.

**Tecnologías:** Java, Swing Java y AWT GUI  

**Objetivo:** Aprender a desarrollar una aplicación de escritorio visual en Java para entender y aplicar el diseño de interfaces de usuario de manera práctica. 

---

## 🌱 Sobre mí
Soy un desarrollador en constante aprendizaje, con interés en desarrollo de aplicaciones web y móviles, inteligencia artificial, ciberseguridad y tecnología blockchain. En este portafolio encontrarás desde prácticas básicas hasta proyectos más avanzados, reflejando mi evolución en este duro pero bonito camino.  

## 📫 Contacto
- 💼 **LinkedIn:** [Mi Perfil de LinkedIn](https://www.linkedin.com/in/alfredo-sobrados-gonzalez/)  
- 📧 **Contacto:** [Mi correo electrónico](mailto:alfredo.sobrados.gonzalez@gmail.com)

¡Gracias por visitar mi portafolio! 😊


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
**Tecnologías:** Lista de herramientas y tecnologías utilizadas. 
-->

<!--
**asobrados03/asobrados03** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
