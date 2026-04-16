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

Para garantizar la claridad y cohesión del código fuente, se han adoptado rigurosas convenciones de codificación y una nomenclatura estrictamente en **idioma inglés**. 

En el **frontend**, los estilos se rigen por la *Google HTML/CSS Style Guide*, priorizando el uso de minúsculas y **kebab-case** (ej. `machine-status-badge`). La lógica sigue la *Google TypeScript Style Guide* y la *Angular Coding Style Guide*, aplicando **lowerCamelCase** para variables y funciones.

En el **backend**, el código se alinea con la *Google Java Style Guide*, estableciendo el uso de **UpperCamelCase (PascalCase)** para entidades y controladores (ej. `MaintenanceTicketController`). Finalmente, se utilizan las *Gherkin Conventions* para el modelado de historias de usuario bajo la sintaxis **Given/When/Then**.

### Software Deployment Configuration

[Descripción de la configuración de despliegue: entornos, pipelines CI/CD y servicios en la nube utilizados.]

## Landing Page, Services & Applications Implementation

### Sprint 1

#### Sprint Planning 1
[Objetivos del sprint, elementos seleccionados del backlog, velocidad del equipo y acuerdos de trabajo.]

#### Aspect Leaders and Collaborators
[Tabla de líderes y colaboradores por aspecto del sprint, con responsabilidades asignadas.]

#### Sprint Backlog 1
[Listado de tareas del sprint con estado, responsable y estimación de horas.]

#### Development Evidence for Sprint Review
[Evidencia del desarrollo: commits, pull requests y capturas de avance por cada ítem completado.]

#### Execution Evidence for Sprint Review
[Capturas o videos que evidencian la ejecución funcional de los entregables del sprint.]

#### Services Documentation Evidence for Sprint Review
[Documentación de los servicios o APIs desarrolladas durante el sprint.]

#### Software Deployment Evidence for Sprint Review
[Evidencia del despliegue realizado: capturas, URLs y configuraciones aplicadas.]

#### Team Collaboration Insights during Sprint
[Análisis de la colaboración del equipo: métricas de contribución, reuniones y herramientas utilizadas.]

## Validation Interviews

### Diseño de Entrevistas
[Guía de entrevistas de validación: objetivos, perfil de participantes y protocolo de ejecución.]

### Registro de Entrevistas
[Registro de las entrevistas de validación realizadas con usuarios reales del producto.]

### Evaluaciones según heurísticas
[Evaluación heurística de la interfaz basada en los principios de Nielsen u otro marco de referencia adoptado.]

## Video About-the-Product
[Enlace y descripción del video de presentación del producto, destacando sus principales funcionalidades.]