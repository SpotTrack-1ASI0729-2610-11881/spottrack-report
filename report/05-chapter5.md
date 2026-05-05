# Capítulo V: Product Implementation, Validation & Deployment

## Software Configuration Management

### Software Development Environment Configuration

**Figma**

![Figma-logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjih1p5gfTNIjPJ8wUgngz7_k8tUFdhHG42g&s){width=150px}

Producto SaaS utilizado para la elaboración de la propuesta de diseño de interfaces (UX/UI), incluyendo la creación de Wireframes, Mock-ups y Prototipos interactivos para el Landing Page y las aplicaciones web. Permite la colaboración en tiempo real del equipo de diseño.

* **Ruta de referencia:** [https://www.figma.com/](https://www.figma.com/)

**HTML5 & CSS3**

![html_css-logo](https://i.pinimg.com/736x/fe/57/10/fe571020f2e476bca20e1ae6441569ec.jpg){width=150px}

Lenguajes estándar de marcado y hojas de estilo utilizados para definir la estructura semántica y el diseño visual estático de los templates en el Landing Page y los componentes de las Frontend Web Applications.

* **Documentación de referencia:** [https://developer.mozilla.org/](https://developer.mozilla.org/)

**Angular Framework**

![angular-logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQVUcQofbdW28AoTCjLFzojT7sSZQVsEurWQA&s){width=150px}

Framework de desarrollo principal para la construcción de las Frontend Web Applications en formato SPA (Single Page Application). Se encarga de la lógica de presentación en el lado del cliente, el enrutamiento y el consumo de la API RESTful utilizando TypeScript como lenguaje de programación.

* **Ruta de descarga:** [https://angular.io/cli](https://angular.io/cli)

**Miro**

![miro-logo](https://asset.brandfetch.io/idAnDTFapY/idDdbxxs3M.png){width=150px}

Plataforma de pizarra virtual (SaaS) empleada para las sesiones colaborativas de análisis de dominio y la elaboración de los diagramas de Big Picture EventStorming y Design-Level EventStorming.

* **Ruta de referencia:** [https://miro.com/](https://miro.com/)

**Structurizr**

![structurizr-logo](https://www.nuget.org/profiles/structurizr/avatar?imageSize=512){width=150px}

Herramienta de modelado utilizada para el diseño y la documentación de la arquitectura de software de la solución, aplicando estrictamente el C4 Model (Context, Container y Component diagrams).

* **Ruta de referencia:** [https://structurizr.com/](https://structurizr.com/)

**Microsoft SQL Server**

![sql-logo](https://cdn-icons-png.flaticon.com/512/5968/5968364.png){width=150px}

Sistema de Gestión de Bases de Datos Relacionales (RDBMS) utilizado para el diseño y almacenamiento persistente de los datos transaccionales de los Bounded Contexts del sistema. Soporta la integridad referencial y las consultas estructuradas necesarias para la lógica del backend.

* **Ruta de descarga:** [https://www.microsoft.com/sql-server/sql-server-downloads](https://www.microsoft.com/sql-server/sql-server-downloads)

**Spring Boot (Java)**

![springboot-logo](https://e4developer.com/posts/microservices-toolbox-spring-boot/images/spring-boot.png){width=150px}

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

### Sprint 2

#### Sprint Planning 2

El presente apartado detalla los acuerdos y objetivos definidos durante el Sprint Planning Meeting de nuestra segunda iteración. Para este Sprint, el equipo se enfocó en dos frentes de trabajo simultáneos: (1) la corrección y completitud de todos los artefactos pendientes del Sprint 1, incluyendo el despliegue completo de la Landing Page; y (2) el inicio del desarrollo frontend de la Web Application principal (Angular), empleando una Fake API (JSON Server) como capa de datos simulada para desacoplar el desarrollo frontend del backend real, cuya implementación se reserva para el Sprint 3.

| Aspect | Details |
| :--- | :--- |
| **Sprint #** | Sprint 2 |
| **Date** | 2026-05-08 |
| **Time** | 10:00 AM |
| **Location** | Reunión Virtual (Discord / Microsoft Teams) |
| **Prepared By** | Azama Fukuda, Juan Pablo |
| **Attendees (to planning meeting)** | Atoche Gonzales, Nicolas Fernando / Azama Fukuda, Juan Pablo / Cataño Zarate, Jesus Miguel / Espinoza Orrego, Valentino Andre / Fernández Linares, Alvaro Sebastian |
| **Sprint n – 1 Review Summary** | Sprint 1 entregó los artefactos fundacionales de Lean UX, DDD, diseño UX/UI en Figma y el inicio de la Landing Page (Hero Section y Header). Sin embargo, quedaron pendientes el despliegue, las secciones de módulos, precios y contacto de la Landing Page, así como diversas secciones de documentación del informe. |
| **Sprint n – 1 Retrospective Summary** | El equipo identificó que la carga de trabajo de documentación y diseño subestimó el tiempo necesario. Para este Sprint 2 se priorizará paralelizar la corrección de Sprint 1 con el inicio del desarrollo de la Web App, asignando responsables claros por cada frente. |
| **Sprint Goal** | Nuestro enfoque es completar todos los artefactos pendientes del Sprint 1 (correcciones de documentación y Landing Page completa) e iniciar el desarrollo frontend de la Web Application de SpotTrack consumiendo una Fake API, implementando las vistas de autenticación, mapa de calor, gestión de activos, alertas de mantenimiento y sugerencias de rutinas. Esto se confirmará cuando la Landing Page esté desplegada y funcional con todas sus secciones, y las vistas frontend de las User Stories priorizadas estén implementadas y navegables en el entorno de desarrollo local. |
| **Sprint n Velocity** | 58 Story Points |
| **Sum of Story Points** | 58 |

#### Aspect Leaders and Collaborators

Para este Sprint 2, el equipo adoptó una estructura dual de trabajo: un subequipo dedicado a las correcciones del Sprint 1 (documentación + Landing Page) y otro enfocado en el desarrollo frontend de la Web Application. Esta división permite avanzar en paralelo sin bloqueos entre tareas de distinta naturaleza.

| Team Member (Last Name, First Name) | GitHub Username | Aspect 1: Sprint 1 Corrections Leader (L) / Collaborator (C) | Aspect 2: Angular App Setup & Auth Leader (L) / Collaborator (C) | Aspect 3: Client App Frontend (Heatmap & Routines) Leader (L) / Collaborator (C) | Aspect 4: Admin Dashboard Frontend Leader (L) / Collaborator (C) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Azama Fukuda, Juan Pablo | llummo | Corrections (C) | Angular App Setup (L) | Client App (C) | Admin Dashboard (C) |
| Atoche Gonzales, Nicolas Fernando | THECOMAX | Corrections (C) | Fake API Config (L) | Client App (C) | Admin Dashboard (C) |
| Cataño Zarate, Jesus Miguel | jcuz1510 | Landing Page Completion (L) | Angular App Setup (C) | Client App (C) | Admin Dashboard (C) |
| Espinoza Orrego, Valentino Andre | valentinoespinoza13 | Corrections (C) | Angular App Setup (C) | Client App (C) | Admin Dashboard (L) |
| Fernández Linares, Alvaro Sebastian | ORION-tech-c | Corrections (L) | Angular App Setup (C) | Client App (L) | Admin Dashboard (C) |

#### Sprint Backlog

> **Nota:** Las tareas de corrección (prefijo `CORR-`) y las de infraestructura (prefijo `SETUP-`) son **storyless** — no corresponden a ninguna User Story y no tienen Story Points asignados, pero son obligatorias para subsanar deficiencias del Sprint anterior y preparar el entorno de desarrollo.

---

**Tareas de Corrección Sprint 1 (Storyless)**

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| - | Corrección Sprint 1 | CORR-01 | Completar sección "The Solution" en Landing Page | Maquetar las seis tarjetas de soluciones del sistema (US-03 pendiente) con HTML/CSS responsivo. | 3 hrs | Cataño | To-Do |
| - | Corrección Sprint 1 | CORR-02 | Completar Pricing Table en Landing Page | Implementar la tabla comparativa de planes SaaS Basic/Mid/Platinum con CTAs (US-04 pendiente). | 3 hrs | Cataño | To-Do |
| - | Corrección Sprint 1 | CORR-03 | Completar formulario de Contacto en Landing Page | Codificar el formulario de contacto con validaciones JavaScript (US-05 pendiente). | 3 hrs | Espinoza | To-Do |
| - | Corrección Sprint 1 | CORR-04 | Completar Navbar y Footer de Landing Page | Implementar la barra de navegación sticky con anchor links y el footer con enlaces institucionales (US-06 pendiente). | 3 hrs | Fernández | To-Do |
| - | Corrección Sprint 1 | CORR-05 | Despliegue de Landing Page en producción | Configurar y publicar la Landing Page en Vercel o GitHub Pages (T08 pendiente). Documentar el enlace de producción. | 2 hrs | Azama | To-Do |
| - | Corrección Sprint 1 | CORR-06 | Completar Diagrama de Base de Datos ERD y Diagrama de Clases | Finalizar y subir el ERD y el Diagrama de Clases UML al repositorio (T04 pendiente). Actualizar referencias en el informe. | 4 hrs | Atoche / Cataño | To-Do |
| - | Corrección Sprint 1 | CORR-07 | Completar evidencias del Sprint 1 en el informe | Añadir capturas de pantalla de la Landing Page, commits reales y métricas de GitHub Insights en las secciones Development Evidence, Execution Evidence y Team Collaboration Insights. | 2 hrs | Espinoza / Fernández | To-Do |
| - | Corrección Sprint 1 | CORR-08 | Completar Big Picture Event Storming (Capítulo II) | Elaborar y añadir el Big Picture Event Storming al Capítulo II (sección actualmente vacía). | 3 hrs | Atoche | To-Do |
| - | Corrección Sprint 1 | CORR-09 | Completar sección Software Deployment Configuration (Capítulo V) | Redactar la descripción del entorno de despliegue, pipelines CI/CD y hosting utilizados. | 1 hr | Azama | To-Do |
| - | Corrección Sprint 1 | CORR-10 | Completar Project Report Collaboration Insights (Capítulo 0) | Añadir la descripción de la colaboración del equipo en el desarrollo del informe con evidencia de GitHub. | 1 hr | Espinoza | To-Do |
| - | Corrección Sprint 1 | CORR-11 | Agregar Student Outcome de Cataño Zárate (Capítulo 0) | Añadir las entradas de "Comunica oralmente" y "Comunica por escrito" para Jesús Miguel Cataño Zárate, actualmente ausentes de la tabla. | 1 hr | Cataño | To-Do |
| - | Corrección Sprint 1 | CORR-12 | Estandarizar análisis de entrevistas 4 y 5 | Añadir el campo "Resumen" completo a las entrevistas de Joan Steffano Quispe (Entrevistado 4) y Fabián Suárez (Entrevistado 5), siguiendo el mismo formato de las entrevistas 1–3. | 2 hrs | Fernández | To-Do |
| - | Corrección Sprint 1 | CORR-13 | Subir fotos faltantes de integrantes del equipo | Agregar al repositorio las imágenes `foto-valentino.jpeg`, `foto-nicolas.png` y `foto-jesus-c.png`, referenciadas en el Capítulo I pero ausentes en la carpeta assets. | 1 hr | Azama / Cataño | To-Do |
| - | Corrección Sprint 1 | CORR-14 | Corregir inconsistencia de tech stack (ASP.NET vs Spring Boot) | En el Sprint 1 Backlog, la tarea T05 menciona "ASP.NET Core" como backend, pero el tech stack oficial declara Spring Boot. Corregir la descripción de T05 en el informe. | 0.5 hrs | Azama | To-Do |
| - | Corrección Sprint 1 | CORR-15 | Corregir nombre de marca en análisis competitivo | La tabla de análisis competitivo usa "FitNode Analytics" (nombre antiguo) en lugar de "SpotTrack". Actualizar todas las instancias en el Capítulo II. | 0.5 hrs | Espinoza | To-Do |

---

**Tareas de Infraestructura y Setup (Storyless)**

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| - | Setup Web App | SETUP-01 | Crear proyecto Angular con estructura por Bounded Contexts | Inicializar el proyecto Angular (ng new spottrack-app), configurar la estructura de carpetas por bounded context: `auth/`, `heatmap/`, `admin/`, `maintenance/`, `assets-management/`, `routines/`, `shared/`. | 3 hrs | Azama | To-Do |
| - | Setup Web App | SETUP-02 | Configurar JSON Server como Fake API | Instalar y configurar `json-server` con un `db.json` que contenga datos seed para: `users`, `machines`, `branches`, `alerts`, `tickets`, `reservations`, `routines/alternatives`, `telemetry`. Exponer en `localhost:3000`. | 3 hrs | Atoche | To-Do |
| - | Setup Web App | SETUP-03 | Configurar routing, guards e interceptores HTTP en Angular | Configurar `AppRoutingModule` con rutas protegidas para los módulos admin y client, implementar `AuthGuard`, `RoleGuard` y el `JwtInterceptor` que añade el token al header. Configurar `HttpClientModule` con `baseUrl` apuntando a JSON Server. | 4 hrs | Azama / Atoche | To-Do |
| - | Setup Web App | SETUP-04 | Documentar Sprint 2 Planning, Backlog y evidencias en el informe | Redactar las secciones de Sprint Planning 2, Aspect Leaders y Sprint Backlog en el Capítulo V. Al finalizar el sprint, completar Development Evidence, Execution Evidence y Team Collaboration Insights. | 3 hrs | Espinoza | To-Do |

---

**User Stories — Desarrollo Frontend con Fake API**

| Id | Title | Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US-07 | Inicio de sesión con validación JWT | T-S2-01 | Componente LoginComponent | Implementar el formulario de login con campos email y password, validaciones reactivas (Validators.required, Validators.email) y estados de error visual. Maquetar según el mockup US07. | 4 hrs | Azama | To-Do |
| US-07 | Inicio de sesión con validación JWT | T-S2-02 | AuthService + Fake API /users | Implementar `AuthService` con método `login(email, password)` que consulta `GET /users` en JSON Server, simula validación de credenciales, genera un mock JWT y guarda el token en `localStorage`. | 3 hrs | Atoche | To-Do |
| US-07 | Inicio de sesión con validación JWT | T-S2-03 | AuthGuard y redirección por rol | Implementar `AuthGuard` que lee el token del `localStorage` y `RoleGuard` que redirige al admin al dashboard (`/admin`) y al cliente al mapa de calor (`/app/heatmap`). | 2 hrs | Azama | To-Do |
| US-08 | Gestión de preferencias y perfil | T-S2-04 | Componente ProfileComponent | Implementar la vista de perfil con formulario de edición de datos personales (nombre, teléfono, idioma) y sección de plan activo. Maquetar según el mockup US08. | 3 hrs | Fernández | To-Do |
| US-08 | Gestión de preferencias y perfil | T-S2-05 | ProfileService + Fake API /users/{id} | Implementar `ProfileService` con métodos `getProfile(id)` (`GET /users/:id`) y `updateProfile(id, data)` (`PUT /users/:id`) contra JSON Server. | 2 hrs | Atoche | To-Do |
| US-09 | Visualización del mapa de calor en vivo | T-S2-06 | Componente HeatMapComponent | Implementar el grid visual de máquinas con indicadores de color semaforizado: verde (libre), rojo (ocupado), amarillo (reservado), gris (mantenimiento). Maquetar según mockup US09. Diseño responsivo con grid CSS. | 6 hrs | Fernández | To-Do |
| US-09 | Visualización del mapa de calor en vivo | T-S2-07 | MachineService + Fake API /machines?branchId | Implementar `MachineService` con `getMachines(branchId)` (`GET /machines?branchId=1`) y `getMachineById(id)` (`GET /machines/:id`). | 2 hrs | Atoche | To-Do |
| US-09 | Visualización del mapa de calor en vivo | T-S2-08 | Polling para simulación de tiempo real | Implementar un intervalo de polling con `rxjs/interval` + `switchMap` cada 5 segundos al endpoint de máquinas para simular actualizaciones en tiempo real del estado del mapa. | 2 hrs | Fernández | To-Do |
| US-10 | Filtrado del inventario por tipo de máquina | T-S2-09 | Componente FilterChipsComponent | Implementar el componente de chips de filtro con opciones: "Todos", "Fuerza", "Cardio", "Funcional". Al seleccionar, emite un evento con la categoría activa. | 2 hrs | Espinoza | To-Do |
| US-10 | Filtrado del inventario por tipo de máquina | T-S2-10 | Integración de filtros reactivos en HeatMapComponent | Conectar `FilterChipsComponent` con `HeatMapComponent` usando un `BehaviorSubject` para filtrar el array de máquinas reactivamente sin nueva petición al servidor. | 2 hrs | Espinoza | To-Do |
| US-14 | Motor de sugerencia de rutinas alternativas | T-S2-11 | Componente RoutineSuggestionsComponent | Implementar el modal/panel de sugerencias de rutinas alternativas que recibe el grupo muscular objetivo y lista los ejercicios sugeridos con máquinas disponibles. Maquetar según mockup US14. | 4 hrs | Fernández | To-Do |
| US-14 | Motor de sugerencia de rutinas alternativas | T-S2-12 | RoutineService + Fake API /routines/alternatives | Implementar `RoutineService` con `getAlternatives(muscleGroup, branchId)` que consulta `GET /routines/alternatives?muscleGroup=chest` en JSON Server con datos seed de ejercicios por grupo muscular. | 3 hrs | Atoche | To-Do |
| US-16 | Sistema de reserva exprés en horas pico | T-S2-13 | Botón "Separar" y estado visual amarillo | Implementar el botón "Separar" en la tarjeta de máquina del HeatMapComponent que cambia el estado de la máquina a amarillo (reservado) en la UI al ser pulsado. | 2 hrs | Fernández | To-Do |
| US-16 | Sistema de reserva exprés en horas pico | T-S2-14 | Countdown timer de 10 minutos con liberación automática | Implementar un countdown timer visible (MM:SS) usando `rxjs/timer` que, al expirar, llama al servicio para cancelar la reserva y revierte el estado de la máquina a verde (libre). | 3 hrs | Espinoza | To-Do |
| US-16 | Sistema de reserva exprés en horas pico | T-S2-15 | ReservationService + Fake API /reservations | Implementar `ReservationService` con `createReservation(machineId)` (`POST /reservations`) y `cancelReservation(id)` (`DELETE /reservations/:id`) contra JSON Server. | 2 hrs | Atoche | To-Do |
| US-17 | Acumulación automática de horas de uso | T-S2-16 | Componente UsageStatsComponent | Implementar el componente de estadísticas con un gráfico de barras por máquina (ng2-charts / chart.js) que muestra horas de uso acumuladas. Incluye filtro de rango de fechas. Maquetar según mockup US17. | 5 hrs | Espinoza | To-Do |
| US-17 | Acumulación automática de horas de uso | T-S2-17 | TelemetryService + Fake API /telemetry | Implementar `TelemetryService` con `getUsageHistory(branchId, startDate, endDate)` (`GET /telemetry?branchId=1&_gte=...&_lte=...`) contra JSON Server. | 2 hrs | Atoche | To-Do |
| US-22 | Alerta predictiva de mantenimiento | T-S2-18 | Componente AlertsPanelComponent | Implementar el panel de alertas de mantenimiento predictivo con lista de alertas (prioridad alta/media/baja), nombre de máquina, horas acumuladas y acción "Asignar a soporte". Maquetar según mockup US22. | 4 hrs | Espinoza | To-Do |
| US-22 | Alerta predictiva de mantenimiento | T-S2-19 | AlertService + Fake API /alerts | Implementar `AlertService` con `getAlerts(branchId)` (`GET /alerts?branchId=1`) y `acknowledgeAlert(id)` (`PATCH /alerts/:id`) contra JSON Server. Incluir seed de alertas de prueba con distintos niveles de urgencia. | 3 hrs | Atoche | To-Do |
| US-26 | Gestión de activos físicos y altas | T-S2-20 | Componente AssetManagementComponent | Implementar la tabla de inventario de máquinas con acciones de alta (modal de formulario), edición y baja lógica. Incluir columnas: ID, nombre, tipo, sede, estado IoT, horas totales. Maquetar según mockup US26. | 5 hrs | Cataño | To-Do |
| US-26 | Gestión de activos físicos y altas | T-S2-21 | AssetService + Fake API /machines CRUD | Implementar `AssetService` con `createMachine(data)` (`POST /machines`), `updateMachine(id, data)` (`PUT /machines/:id`) y `deleteMachine(id)` (`DELETE /machines/:id`) contra JSON Server. | 3 hrs | Atoche | To-Do |

#### Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/solution-section | - | feat(solution): add solution modules section | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/pricing-section | - | feat(pricing): add pricing table SaaS plans | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/contact-form | - | feat(contact): add contact form with validations | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Landing-Page | feature/navbar-footer | - | feat(nav): add sticky navbar and footer | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Web-App | feature/app-setup | - | chore: initialize angular project structure | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Web-App | feature/fake-api | - | chore(api): add json-server fake api with seed data | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Web-App | feature/auth | - | feat(auth): implement login component and auth service | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Web-App | feature/heatmap | - | feat(heatmap): implement heat map component with machine status | - | - |
| SpotTrack-1ASI0729-2610-11881/SpotTrack-Web-App | feature/admin-dashboard | - | feat(admin): implement alerts panel and asset management | - | - |

#### Execution Evidence for Sprint Review

[Añadir capturas de pantalla de la Landing Page desplegada con todas sus secciones, y del Web App Angular mostrando: vista de Login, Mapa de Calor con indicadores semaforizados, panel de Alertas de Mantenimiento y tabla de Gestión de Activos.]

#### Services Documentation Evidence for Sprint Review

[Documentar los endpoints de la Fake API (JSON Server) con sus rutas, métodos HTTP, ejemplos de request y response, y el `db.json` con estructura de datos seed utilizada para el desarrollo frontend.]

#### Software Deployment Evidence for Sprint Review

[Documentar el enlace de producción de la Landing Page desplegada (Vercel/GitHub Pages) y el repositorio del Web App Angular con instrucciones para levantar el entorno local (`json-server` + `ng serve`).]

#### Team Collaboration Insights during Sprint

[Añadir capturas del gráfico de contribuciones de GitHub (Insights > Contributors) para los repositorios SpotTrack-Landing-Page y SpotTrack-Web-App durante el periodo del Sprint 2.]



## Bibliography

<p style="padding-left: 30px; text-indent: -30px;">DINGG Team. (2025, 26 de noviembre). *Your 5-step operational plan to handle equipment failures*. DINGG. https://dingg.app/blogs/your-5-step-operational-plan-to-handle-equipment-failures</p>

<p style="padding-left: 30px; text-indent: -30px;">Maintainnow. (2025, 19 de octubre). *MRO: Maintenance, repair, & operations - A practical guide*. https://www.maintainnow.app/learn/guides/mro-maintenance-repair-operations-a-practical-guide</p>

<p style="padding-left: 30px; text-indent: -30px;">Energym. (2023). *Why do gym members cancel their memberships?* https://energym.io/blogs/braingains/why-do-gym-members-cancel-their-memberships</p>

<p style="padding-left: 30px; text-indent: -30px;">Oxmaint. (2023). *Corrective vs. preventive work orders*. https://www.oxmaint.com/blog/post/corrective-vs-preventive-work-orders</p>

<p style="padding-left: 30px; text-indent: -30px;">Fitness Store. (2024). *Commercial & professional treadmills*. https://www.topfitness.com/collections/commercial-treadmills</p>


## Annexes

### Annex A : Videos de Exposiciones

| Entrega | Título de la Exposición | Hipervínculo al Video (Microsoft Stream) |
| :--- | :--- | :--- |
| **AV1** | Sprint Review - Semana 4 | [Enlace al video AV1 - SpotTrack](URL_AQUI) |
| **TB1** | Stage Review - Semana 7 | (Pendiente) |
| **AV2** | Sprint Review - Semana 12 | (Pendiente) |
| **TB2** | Release Review - Semana 15 | (Pendiente) |


