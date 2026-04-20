# ¡Hola! Soy Ariel Zarate 👋

### 🚀 Fullstack Developer | Backend Engineer | Fintech & Architecture Specialist | AI & GenAI Explorer

Ingeniero de software con sólida experiencia en el ecosistema **JVM (Java/Kotlin)** y el stack **Modern JS (TypeScript, React, Node)**. Mi especialidad es construir servicios altamente escalables para el sector **Fintech**, garantizando la integridad de los datos y el cumplimiento de estándares de arquitectura limpia (**Clean Architecture**).

Actualmente, potencio el ciclo de vida de desarrollo integrando **Agentes de IA** y modelos LLM de código abierto (**OpenCode / Client IA**) para optimizar la eficiencia y la calidad del código.
---

### 🚀 Perfil Profesional & Core Expertise

* **🏦 Fintech & Resilient Engineering:** Implementación de flujos transaccionales con control de **Idempotencia** (Caffeine/Redis), patrones **Retry/Circuit Breaker** e integraciones críticas con **Prisma, Coelsa y Western Union**.
* **🏗️ Architecture & Patterns:** Aplicación rigurosa de **Clean Architecture** y **Arquitectura Hexagonal**. Experto en diseño por capas: **Domain Model, Repositories, Mappers y DTOs**.
* **🤖 AI-Driven Development:** Integración de flujos autónomos mediante agentes de IA. Uso de motores LLM como **OpenCode** y **Client IA** para optimización de código y análisis técnico.
* **🔭 Observabilidad & Infra:** Monitoreo con **Prometheus, Grafana y Loki**. Gestión de secretos en **Azure Key Vault** y despliegues GitOps con **Argo CD**.
* **✅ Ciclo de Vida (SDLC):** Testing en entornos de **Dev, Stage y Pre-prod**, operando bajo **SCRUM** (Sprints de 15 días) con Jira y Confluence.

---
### 🛠️ Stack Tecnológico & Ecosystem

| **Backend & Core** | **Frontend & Modern JS** | **Cloud, DevOps & AI** |
| :--- | :--- | :--- |
| ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Spring](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=spring&logoColor=white) | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) | ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![ArgoCD](https://img.shields.io/badge/-ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white) |
| **Frameworks:** Spring Boot 3, Express, Next.js | **State:** Redux, Context API, Hooks | **AI:** OpenCode LLM, Client IA |
| **Data:** JPA, Hibernate, JPQL, Liquibase | **Styling:** Tailwind CSS, Material UI | **Observability:** Prometheus, Grafana, Loki |
| **DBs:** PostgreSQL, MySQL, MongoDB | **Build:** NPM, NPX, Maven, Gradle | **CI/CD:** GitHub Actions, Azure Pipelines |

### 🧪 Testing & Quality Assurance
* **Kotlin:** Kotest & MockK.
* **Java:** JUnit 5, Mockito & AssertJ.
* **Node/JS:** Jest & Supertest (Integration Testing).
* **Standards:** Manejo de errores bajo **RFC 7807** y Logs estructurados con **Logger**.

### ⚙️ Engineering Workflow
* **Methodologies:** SCRUM, Sprints 15 días, Code Reviews.
* **Tools:** Jira, Confluence, Postman (Advanced), Swagger/OpenAPI.
* **Environment:** Linux Console (Zsh/Bash), Azure Key Vault, IntelliJ IDEA.


---
## 🏗️ Proyectos en los que estoy trabajando

### 🏗️ Arquitectura de Sistemas & Cloud Native

#### 🚀 [Microservices Architecture Lab - E-commerce](https://github.com/arielZarate/microservices-architecture-ecommerce-lab)
Laboratorio avanzado de diseño de sistemas distribuidos, enfocado en escalabilidad, observabilidad y resiliencia mediante una arquitectura políglota.

- **Stack Técnico:** Java (Spring Boot 3), Kotlin, Node.js (Express) y TypeScript.
- **Comunicación & Arquitectura:** - Implementación de **Arquitectura Hexagonal** en cada microservicio para desacoplamiento total.
  - Comunicación asíncrona mediante **Apache Kafka** (event-driven).
  - API Gateway centralizado para gestión de tráfico.
- **DevOps & Infraestructura:** - Contenerización con **Docker** y orquestación con **Kubernetes (Minikube)**.
  - Implementación de patrones de resiliencia (**Retry**) y **Redis** para caching distribuido.
  - Observabilidad configurada con **Prometheus y Grafana**.
- **CI/CD:** Automatización de builds y despliegues mediante **GitHub Actions**.

---


#### 🔧 [Workshop Management System (Garage)](https://github.com/arielZarate/GarageManagementSystem)
Sistema integral para la gestión de talleres mecánicos, diseñado para optimizar el flujo desde la recepción hasta la entrega final del vehículo.

- **Stack:** Java, Spring Boot 3, Spring Data JPA y PostgreSQL.
- **Frontend:** Interfaz administrativa moderna con **Thymeleaf** y **Tailwind CSS**.
- **Lógica de Negocio:** - Gestión de Órdenes de Reparación y Presupuestos independientes.
  - Trazabilidad de mecánicos por legajo y control de estados en tiempo real.
  - Consulta pública de estado del vehículo mediante número de patente.
- **Infraestructura:** Backups automatizados mediante tareas **CRON** y sincronización JSON.
- **Arquitectura:** Implementación profesional del patrón **MVC** con separación de responsabilidades y DTOs.

---

### 🏛️ Arquitectura y Patrones (Hexagonal con  DDD) 

#### [Clean Architecture & Hexagonal Samples](https://github.com/arielZarate/cleanArchitecture)
Repositorio especializado en la implementación de **Arquitectura Hexagonal (Ports & Adapters)** y **Clean Architecture** para demostrar el desacoplamiento de componentes y alta testeabilidad.

- **Stack:** Java 17+, Kotlin, Spring Boot, MapStruct, JUnit 5 & MockK/Mockito.
- **Conceptos aplicados:** Inyección de dependencias por constructor, Domain-Driven Design (DDD), manejo de excepciones global y documentación con OpenAPI/Swagger.
- **Infraestructura:** Docker Compose para entornos simulados y persistencia en PostgreSQL/H2.
- **Estado:** Demos sanitizadas enfocadas en buenas prácticas y mantenibilidad.

---

### 🤖 AI & Generative Engineering
Explorando la integración de Inteligencia Artificial en el ciclo de vida del desarrollo y aplicaciones finales.

- **Agentes de IA:** Implementación de flujos de trabajo autónomos utilizando agentes para automatización de tareas y análisis de código.
- **LLMs Locales:** Configuración y despliegue de modelos Open Source (**OpenCode**, Llama 3, Mistral) para asegurar la privacidad de los datos y soberanía tecnológica.
- **AI-Driven Development:** Uso estratégico de herramientas de IA para optimizar la refactorización de código, generación de tests unitarios y documentación técnica.

---

### ✅ Proyectos Finalizados 2024

#### 🧭 Parking - Sistema Gestor de Estadía
Sistema para la gestión de vehículos con arquitectura profesional.
- **Backend:** Java con Spring Boot, Data-JPA, implementación de Patrones de Diseño y Spring Security.
- **Frontend:** React con Next.js y TypeScript.
- [Ver Repositorio](https://github.com/arielZarate/ParkingProyectJavaReactV2)


**ChicCloset - Ecommerce de Indumentaria**
*Colaboración en equipo interdisciplinario.*
- **Tecnologías:** MERN Stack (Mongo, Express, React, Node), Auth0, Mercado Pago.
- [Visitar Sitio](https://chiccloset-service.web.app/) | [Repositorio](https://github.com/rdtaipe/Henry-PF)

---

### 📫 Contacto e Intereses
- **Pasatiempos:** Apasionado del Bushcraft, los viajes y la vida al aire libre. 🏕️🏍️
- **Ubicación:** Argentina. 📍

<a href="https://www.linkedin.com/in/ariel-zarate-0959184b/" target="_blank">
<img src="https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/arielZarate" target="_blank">
<img src="https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white" />
</a>

![Estadísticas de Ariel](https://komarev.com/ghpvc/?username=arielZarate&color=blue&style=flat-square)
