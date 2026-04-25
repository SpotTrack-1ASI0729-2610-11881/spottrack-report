# Capítulo V: Product Implementation, Validation & Deployment

## Software Configuration Management

### Software Development Environment Configuration

**Figma**

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjih1p5gfTNIjPJ8wUgngz7_k8tUFdhHG42g&s" alt="Figma-logo" width="150">
</p>

Producto SaaS utilizado para la elaboración de la propuesta de diseño de interfaces (UX/UI), incluyendo la creación de Wireframes, Mock-ups y Prototipos interactivos para el Landing Page y las aplicaciones web. Permite la colaboración en tiempo real del equipo de diseño.

* **Ruta de referencia:** [https://www.figma.com/](https://www.figma.com/)

**HTML5 & CSS3**

<p align="center">
  <img src="https://i.pinimg.com/736x/fe/57/10/fe571020f2e476bca20e1ae6441569ec.jpg" alt="html_css-logo" width="150">
</p>

Lenguajes estándar de marcado y hojas de estilo utilizados para definir la estructura semántica y el diseño visual estático de los templates en el Landing Page y los componentes de las Frontend Web Applications.

* **Documentación de referencia:** [https://developer.mozilla.org/](https://developer.mozilla.org/)

**Angular Framework**

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVUcQofbdW28AoTCjLFzojT7sSZQVsEurWQA&s" alt="angular-logo" width="150">
</p>

Framework de desarrollo principal para la construcción de las Frontend Web Applications en formato SPA (Single Page Application). Se encarga de la lógica de presentación en el lado del cliente, el enrutamiento y el consumo de la API RESTful utilizando TypeScript como lenguaje de programación.

* **Ruta de descarga:** [https://angular.io/cli](https://angular.io/cli)

**Miro**

<p align="center">
  <img src="https://asset.brandfetch.io/idAnDTFapY/idDdbxxs3M.png" alt="miro-logo" width="150">
</p>

Plataforma de pizarra virtual (SaaS) empleada para las sesiones colaborativas de análisis de dominio y la elaboración de los diagramas de Big Picture EventStorming y Design-Level EventStorming.

* **Ruta de referencia:** [https://miro.com/](https://miro.com/)

**Structurizr**

<p align="center">
  <img src="https://www.nuget.org/profiles/structurizr/avatar?imageSize=512" alt="structurizr-logo" width="150">
</p>

Herramienta de modelado utilizada para el diseño y la documentación de la arquitectura de software de la solución, aplicando estrictamente el C4 Model (Context, Container y Component diagrams).

* **Ruta de referencia:** [https://structurizr.com/](https://structurizr.com/)

**Microsoft SQL Server**

<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/5968/5968364.png" alt="sql-logo" width="150">
</p>

Sistema de Gestión de Bases de Datos Relacionales (RDBMS) utilizado para el diseño y almacenamiento persistente de los datos transaccionales de los Bounded Contexts del sistema. Soporta la integridad referencial y las consultas estructuradas necesarias para la lógica del backend.

* **Ruta de descarga:** [https://www.microsoft.com/sql-server/sql-server-downloads](https://www.microsoft.com/sql-server/sql-server-downloads)

**Spring Boot (Java)**

<p align="center">
  <img src="https://e4developer.com/posts/microservices-toolbox-spring-boot/images/spring-boot.png" alt="springboot-logo" width="150">
</p>

Framework backend basado en Java utilizado para la construcción, configuración y despliegue de los RESTful Web Services. Gestiona la lógica de negocio, la seguridad, las transacciones y la exposición de los endpoints que serán consumidos por las aplicaciones web.

* **Ruta de descarga:** [https://spring.io/projects/spring-boot](https://spring.io/projects/spring-boot)

### Source Code Management

El proyecto utiliza **GitHub** como sistema de control de versiones mediante un repositorio público. Se adoptó una estrategia basada en **GitFlow**:
* La rama `main` contiene versiones estables del sistema.
* La rama `develop` funciona como entorno de integración.
* Las nuevas funcionalidades se desarrollan en ramas `feature/*`.

La integración de cambios se realiza mediante **Pull Requests** hacia la rama `develop`, asegurando un control previo antes de incorporar modificaciones. Se emplea una convención de commits semánticos (`feat`, `fix`).

### Source Code Style Guide & Conventions

### Source Code Style Guide & Conventions

Para garantizar la claridad y cohesión del código fuente en el desarrollo de la plataforma, el equipo ha adoptado rigurosas convenciones de codificación y una nomenclatura estrictamente en idioma inglés, aplicándose esto a todas las tecnologías de la solución. 

En relación al **frontend**, la estructura semántica y los estilos se rigen por la *Google HTML/CSS Style Guide*, priorizando el uso exclusivo de minúsculas y la separación de palabras mediante guiones (**kebab-case**) para identificadores y clases, tal como se evidencia en selectores estructurales tipo `machine-status-badge` o `asset-detail-card` (Google, s.f.). Asimismo, la lógica de la interfaz y la arquitectura siguen los lineamientos de la *Google TypeScript Style Guide* (Google, s.f.) y la *Angular Coding Style Guide* (Angular, s.f.), aplicando **lowerCamelCase** para la declaración de variables y funciones (por ejemplo, `reportMachineIssue()`) y estandarizando la denominación de archivos por responsabilidades separadas por puntos (ej., `equipment-list.component.ts`). 

Por otro lado, en la **arquitectura del lado del servidor**, el código se alinea con la *Google Java Style Guide* y las directrices de *Spring Boot Features* (Google, s.f.), estableciendo el uso innegociable de **UpperCamelCase (PascalCase)** para la definición de entidades y controladores (ej., `MaintenanceTicketController`), además de seguir patrones arquitectónicos definidos por el framework para la inyección de dependencias. 

Finalmente, para asegurar una trazabilidad transparente entre los requerimientos del gimnasio y las pruebas automatizadas, el equipo utiliza las *Gherkin Conventions for Readable Specifications*, modelando historias de usuario bajo la sintaxis declarativa de comportamiento (**Given, When, Then**), lo que unifica el entendimiento funcional entre desarrolladores y stakeholders (Cucumber, s.f.).
### Software Deployment Configuration

[Descripción de la configuración de despliegue: entornos, pipelines CI/CD y servicios en la nube utilizados.]

## Landing Page, Services & Applications Implementation

### Sprint 1
#### Sprint Planning 1

El presente apartado detalla los acuerdos y objetivos definidos durante el Sprint Planning Meeting de nuestra primera iteración. Para este Sprint inicial de SpotTrack, nuestro esfuerzo se centró en sentar las bases estratégicas y técnicas del proyecto. Esto abarcó desde la elaboración de los artefactos fundacionales de Lean UX y la especificación de requerimientos, hasta el modelado de la arquitectura usando Domain-Driven Design (DDD) y el diseño lógico de la base de datos. Asimismo, priorizamos el prototipado de interfaces en Figma y el despliegue de nuestra Landing Page comercial para asegurar una presencia web temprana orientada a gimnasios y centros deportivos.

| Aspect | Details |
| :--- | :--- |
| **Sprint #** | Sprint 1 |
| **Date** | 2026-04-23 |
| **Time** | 10:00 AM |
| **Location** | Reunión Virtual (Discord / Microsoft Teams) |
| **Prepared By** | Azama Fukuda, Juan Pablo |
| **Attendees (to planning meeting)** | Atoche Gonzales, Nicolas Fernando / Azama Fukuda, Juan Pablo / Cataño Zarate, Jesus Miguel / Espinoza Orrego, Valentino Andre / Fernández Linares, Alvaro Sebastian |
| **Sprint n – 1 Review Summary** | No aplica (Primer Sprint del proyecto). |
| **Sprint n – 1 Retrospective Summary** | No aplica (Primer Sprint del proyecto). |
| **Sprint Goal** | Nuestro enfoque principal es establecer el diseño fundamental de UX/UI, la arquitectura de dominio bajo DDD y el despliegue de la Landing Page de SpotTrack. Consideramos que esto nos entrega una estructura de proyecto clara, los artefactos IoT correctamente modelados y un primer punto de contacto digital para gimnasios y administradores de centros deportivos. Esto se confirmará cuando los artefactos de Lean UX, base de datos, DDD y Figma estén completados, y la Landing Page se encuentre desplegada y funcional en producción. |
| **Sprint n Velocity** | 45 Story Points |
| **Sum of Story Points** | 45 |

#### Aspect Leaders and Collaborators

Durante este sprint, la dinámica de trabajo exigió una división estratégica de los integrantes. Para optimizar el flujo de desarrollo, conformamos subequipos especializados que pudieran concentrarse íntegramente en el ecosistema frontend, la investigación de usuarios y la estructuración de la Landing Page de SpotTrack. Esta organización nos permitió mantener un avance continuo y evitar la fragmentación en microtareas, lo cual habría ocasionado que perdiéramos la perspectiva general de la solución IoT orientada a gimnasios.

| Team Member (Last Name, First Name) | GitHub Username | Aspect Name 1 Leader (L) / Collaborator (C) | Aspect Name 2 Leader (L) / Collaborator (C) | Aspect Name 3 Leader (L) / Collaborator (C) | Aspect Name 4 Leader (L) / Collaborator (C) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Azama Fukuda, Juan Pablo | llummo | Landing Page Elaboration (L) | Bounded Context Development (C) | Prototyping (L) | Scrum Master Role (L) |
| Atoche Gonzales, Nicolas Fernando | THECOMAX | Landing Page Elaboration (C) | Bounded Context Development (C) | Prototyping (C) | UX Research (L) |
| Cataño Zarate, Jesus Miguel | jcuz1510 | Landing Page Elaboration (C) | Bounded Context Development (L) | Database & Class Diagram (L) | UX Research (C) |
| Espinoza Orrego, Valentino Andre | valentinoespinoza13 | Landing Page Elaboration (C) | Bounded Context Development (C) | Database & Class Diagram (C) | UX Research (C) |
| Fernández Linares, Alvaro Sebastian | ORION-tech-c | Landing Page Elaboration (C) | Bounded Context Development (C) | Prototyping (C) | UX Research (C) |

### Sprint Backlog

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| | | T01 | UX Research & Entrevistas | Realizar entrevistas a administradores de gimnasios y clientes frecuentes; crear User Personas y Empathy Maps orientados al dominio IoT de SpotTrack. | 6 hrs | Atoche / Espinoza / Azama / Fernández | Done |
| | | T02 | Diseño UX/UI de Landing Page | Diseñar Wireframes, Mockups y User Flows para la presentación comercial web de SpotTrack dirigida a gimnasios B2B. | 5 hrs | Cataño / Azama / Espinoza | Done |
| | | T03 | Domain-Driven Design Artifacts | Elaborar EventStorming, Bounded Contexts y Context Mapping para la lógica de telemetría IoT y gestión de activos. | 5 hrs | Fernández / Atoche | Done |
| | | T04 | Database & Class Diagram | Diseñar el Diagrama de Clases (UML) y el Diagrama Entidad-Relación (ERD) del sistema SpotTrack. | 5 hrs | Fernández / Atoche | To-Do |
| | | T05 | Software Development Environment | Configurar el entorno de desarrollo y dependencias locales para el framework Angular (frontend) y ASP.NET Core (backend). | 2 hrs | Azama | Done |
| | | T06 | Source Code Management & Styles | Definir el Style Guide del código, convenciones de commits y la arquitectura de información base bajo GitFlow. | 2 hrs | Cataño | Done |
| | | T07 | Segmento objetivo & Lean UX Process | Definir segmentos objetivo (administradores de gimnasios y clientes frecuentes), Lean UX Canvas y la matriz de tareas del usuario. | 2 hrs | Cataño | Done |
| | | T08 | Software Deployment Configuration | Configurar el servicio de hosting cloud estático para la Landing Page de SpotTrack (Vercel/Netlify/GitHub Pages). | 3 hrs | Azama | To-Do |
| | | T09 | Sprint 1 Planning & Backlog | Redactar el Sprint Planning, Aspect Leaders y el Backlog en el documento académico del proyecto. | 2 hrs | Espinoza | To-Do |
| | | T10 | Development & Execution Evidence | Recolectar capturas de commits y evidencia gráfica de la ejecución de la Landing Page de SpotTrack. | 2 hrs | Cataño | To-Do |
| | | T11 | Deployment & Services Evidence | Documentar los enlaces de producción desplegados y las métricas de colaboración del equipo en GitHub. | 2 hrs | Fernández | To-Do |
| US-01 | Descripción principal en el Hero Section | T12 | Desarrollo: Hero Section | Maquetar en HTML/CSS/JS la cabecera principal con el mensaje sobre optimización IoT de gimnasios y los CTAs de acceso al portal. | 4 hrs | Azama | Done |
| US-03 | Visualización de Soluciones y Características | T13 | Desarrollo: Módulos del Sistema | Programar la sección responsiva que detalla los seis módulos del sistema: telemetría, mapa de calor, analíticas, mantenimiento predictivo, reservas y reportes. | 4 hrs | Cataño | To-Do |
| US-04 | Selección de planes de suscripción SaaS | T14 | Desarrollo: Pricing Table | Maquetar la tabla de precios interactiva para los planes SaaS (Basic, Mid, Platinum) dirigidos a centros deportivos. | 4 hrs | Espinoza | To-Do |
| US-05 | Envío de formulario de Contacto | T15 | Desarrollo: Formulario & Validaciones | Codificar el formulario de contacto para leads comerciales con validaciones en JavaScript. | 4 hrs | Atoche | To-Do |
| US-06 | Acceso al portal desde la navegación | T16 | Desarrollo: Navbar & Footer | Implementar la barra de navegación superior con botones de Login y Demo visibles, y el footer con enlaces institucionales. | 3 hrs | Fernández | To-Do |

#### Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/hero-section | e480ef9 | feat(hero-section): add background animations | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/header | ed84ec5 | feat: add header | - | 2026-04-19 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | develop | 6a2919f | chore: project-setup | - | 2026-04-18 |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | main | 3871093 | Initial commit | - | 2026-04-18 |

#### Execution Evidence for Sprint Review

A lo largo de esta primera iteración del proyecto SpotTrack, logramos consolidar el diseño estratégico del sistema apoyándonos en la elaboración de artefactos de Domain-Driven Design orientados al dominio de telemetría IoT para gimnasios, así como en el modelado estructural de la base de datos. Esta arquitectura, diseñada para integrarse con sensores Edge que capturan el estado de ocupación de las máquinas en tiempo real, se complementó con una exhaustiva investigación de Experiencia de Usuario (UX/UI) enfocada en los dolores reales de administradores de centros deportivos y clientes frecuentes de gimnasio.


#### Team Collaboration Insights during Sprint

