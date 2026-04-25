# Capítulo IV: Product Design

## Style Guidelines

### General Style Guidelines
[Definición de tipografías, paleta de colores, iconografía y tono de comunicación visual del producto.]

### Web Style Guidelines
[Especificaciones de diseño web: grillas, espaciado, componentes reutilizables y estándares de accesibilidad.]

## Information Architecture

### Organization Systems
[Estructura de organización del contenido: jerárquica, secuencial o matricial, según el contexto de uso.]

### Labeling Systems
Para garantizar la simplicidad y reducir la carga cognitiva de los usuarios, se utilizará un vocabulario directo, estandarizado y libre de jerga técnica compleja. Las etiquetas representan acciones claras o agrupaciones lógicas de información.

Para el Dashboard Administrativo (B2B):

    "Resumen": En lugar de "Dashboard Principal" o "Métricas Generales". Agrupa los KPIs de alto nivel.

    "Activos": En lugar de "Inventario de Máquinas Físicas".

    "Monitoreo IoT": Agrupa el estado de la red y conexión de sensores.

    "Mantenimiento": En lugar de "Gestión de Tickets y Reparaciones". Agrupa las alertas y órdenes de trabajo.

    "Reportes": Agrupa la analítica histórica y mapas de calor estáticos.

    "Finanzas": En lugar de "Calculadora de Impacto Financiero y ROI".

Para la Aplicación Móvil (Cliente B2C):

    "Mapa en Vivo": Representa la vista de disponibilidad en tiempo real.

    "Rutinas": Agrupa las sugerencias de ejercicios alternativos.

    "Reservar": Acción directa para bloquear temporalmente un equipo.


### SEO Tags and Meta Tags
Para asegurar un posicionamiento orgánico adecuado y una correcta indexación, se definen las siguientes etiquetas principales.

Landing Page (Sitio Público)

    Title: SpotTrack | Gestión Inteligente y Telemetría para Gimnasios

    Description: Optimiza la gestión de tu gimnasio con telemetría IoT. Reduce costos de mantenimiento, evita aglomeraciones y mejora la retención de tus clientes con mapas de calor en tiempo     real.

    Keywords: software para gimnasios, telemetría deportiva, mantenimiento predictivo gimnasios, sensores IoT fitness, gestión de activos deportivos, mapa de calor gimnasio, SpotTrack.

    Author: SpotTrack

Web Application (Portal de Acceso Administrativo)

    Title: SpotTrack Dashboard | Acceso Administrativo
    
    Description: Panel de control gerencial para la gestión de activos, monitoreo de hardware IoT y resolución de tickets de mantenimiento en tiempo real.
    
    Keywords: spottrack admin, login spottrack, gestión interna, dashboard gimnasios.
    
    Author: SpotTrack


### Searching Systems
Dada la alta densidad de datos (cientos de máquinas, múltiples sedes, histórico de tickets), el sistema de búsqueda es fundamental para la operatividad.

Opciones de Búsqueda y Filtros (Dashboard Administrativo):

Búsqueda Global (Barra de texto): Ubicada en el encabezado (Header). Permite búsquedas difusas ingresando el ID del equipo, nombre de la máquina o descripción de un ticket.

Filtros de Contexto (Faceted Search): * Por Sede: Dropdown global para cambiar la vista de datos entre diferentes sucursales.

Por Estado: Checkboxes rápidos para aislar máquinas (ej. Solo mostrar equipos 'En Mantenimiento' o 'Desconectados').

Por Categoría: Filtros por tipo de equipamiento (Cardio, Fuerza, Funcional).

### Navigation Systems
El sistema de navegación está diseñado para ser predecible y jerárquico, minimizando la cantidad de clics necesarios para alcanzar cualquier objetivo.

Landing Page (One-Page Scroll Navigation):

Navegación global superior fija (Sticky Top Navbar) que permite saltos rápidos (Anchor links) a las secciones clave: Inicio, Soluciones, Precios, Contacto. Incluye un Call to Action persistente ("Login") que redirige a la Web App.

Dashboard Administrativo (Desktop Web):

Navegación Estructural Permanente: Se utilizará un Sidebar (menú lateral izquierdo) persistente que contiene las etiquetas de los módulos principales (Activos, IoT, Mantenimiento, etc.). Esto permite al administrador saltar entre contextos sin perder su ubicación.

Navegación Local: Pestañas (Tabs) dentro de cada módulo para separar vistas internas (ej. dentro de "Mantenimiento", pestañas para Pendientes, En Progreso, Completados).

Aplicación Móvil (Clientes):

Bottom Navigation Bar: Barra inferior persistente con 3 o 4 íconos de acceso rápido a las funciones críticas para el usuario en movimiento (ej. Mapa, Rutinas, Perfil). Facilita el uso con una sola mano.


## Landing Page UI Design


### Landing Page Wireframe
<img src="../assets/WIREFRAMES/landing_wireframe.png" width="600">

### Landing Page Mock-up
<img src="../assets/MOCKUPS/landing_mockup.png" width="600">

## Web Applications UX/UI Design

### Web Applications Wireframes


<img src="../assets/WIREFRAMES/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png" width="600">
<img src="../assets/WIREFRAMES/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png" width="600">
<img src="../assets/WIREFRAMES/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png" width="600">
<img src="../assets/WIREFRAMES/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png" width="600">
<img src="../assets/WIREFRAMES/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png" width="600">
<img src="../assets/WIREFRAMES/US13_%20Reporte%20de%20máquina.png" width="600">
<img src="../assets/WIREFRAMES/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png" width="600">
<img src="../assets/WIREFRAMES/US20%20Exportación%20de%20analíticas%20de%20uso%20(Epic_%20EP05).png" width="600">
<img src="../assets/WIREFRAMES/US21%20Monitoreo%20de%20estado%20de%20hardware%20Edge%20IoT%20(Epic_%20EP05).png" width="600">
<img src="../assets/WIREFRAMES/US22%20Alerta%20predictiva%20de%20mantenimiento%20(Epic_%20EP06)%20CONFIGURAR%20UMBRAL.png" width="600">
<img src="../assets/WIREFRAMES/US23%20Despacho%20automatizado%20de%20tickets%20técnicos%20(Epic_%20EP06).png" width="600">
<img src="../assets/WIREFRAMES/US24%20Notificación%20de%20restablecimiento%20a%20los%20usuarios%20(Epic_%20EP06).png" width="600">
<img src="../assets/WIREFRAMES/US25%20Calendario%20inteligente%20de%20bloqueos%20de%20reserva(Epic_%20EP04).png" width="600">
<img src="../assets/WIREFRAMES/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png" width="600">
<img src="../assets/WIREFRAMES/US26%20Gestión%20de%20activos%20físicos%20y%20altas%20(Epic_%20EP07).png" width="600">
<img src="../assets/WIREFRAMES/US27%20Estadísticas%20de%20reubicación%20multisede%20(Epic_%20EP07).png" width="600">
<img src="../assets/WIREFRAMES/US29%20Calculadora%20de%20impacto%20financiero%20por%20inactividad%20(Epic_%20EP08).png" width="600">
<img src="../assets/WIREFRAMES/US30%20Analítica%20predictiva%20de%20compras%20e%20inversión%20(Epic_%20EP08).png" width="600">



### Web Applications Wireflow Diagrams
![TASKFLOW-07](../assets/TASKFLOWS/TASKFLOW-07.jpg)
![WFM-07](../assets/WIREFLOWS%20MOBILE/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png)
![WF-07](../assets/WIREFLOWS/US07%20Inicio%20de%20sesión%20con%20validación%20JWT%20(Epic_%20EP02).png)
![TASKFLOW-08](../assets/TASKFLOWS/TASKFLOW-08.jpg)
![WFM-08](../assets/WIREFLOWS%20MOBILE/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png)
![WF-08](../assets/WIREFLOWS/US08%20Gestión%20de%20preferencias%20y%20perfil%20(Epic_%20EP02).png)
![TASKFLOW-09](../assets/TASKFLOWS/TASKFLOW-09.jpg)
![WFM-09](../assets/WIREFLOWS%20MOBILE/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![WF-09](../assets/USERFLOWS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![TASKFLOW-10](../assets/TASKFLOWS/TASKFLOW-10.jpg)
![WFM-10](../assets/WIREFLOWS%20MOBILE/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![WF-10](../assets/WIREFLOWS/US09%20Y%20US10_%20MAPA%20DE%20CALOR%20Y%20FILTROS.png)
![TASKFLOW-11](../assets/TASKFLOWS/TASKFLOW-11.jpg)
![WFM-11](../assets/WIREFLOWS%20MOBILE/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png)
![WF-11](../assets/WIREFLOWS/US11%20Cambio%20de%20sucursal%20para%20revisión%20de%20aforo%20(Epic_%20EP03).png)
![TASKFLOW-12](../assets/TASKFLOWS/TASKFLOW-12.jpg)
![WFM-12](../assets/WIREFLOWS%20MOBILE/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).png)
![WF-12](../assets/WIREFLOWS/US12%20Notificaciones%20push%20de%20resolución%20de%20disponibilidad%20(Epic_%20EP03).pngQ)
![TASKFLOW-13](../assets/TASKFLOWS/TASKFLOW-13.jpg)
![WFM-13](../assets/WIREFLOWS%20MOBILE/US13_%20Reporte%20de%20máquina.png)
![WF-13](../assets/WIREFLOWS/US13_%20Reporte%20de%20máquina.png)
![TASKFLOW-14](../assets/TASKFLOWS/TASKFLOW-14.jpg)
![WFM-14](../assets/WIREFLOWS%20MOBILE/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png)
![WF-14](../assets/WIREFLOWS/US14%20Motor%20de%20sugerencia%20de%20rutinas%20alternativas%20(Epic_%20EP04).png)

### Web Applications Mock-ups
[Mock-ups de alta fidelidad de las pantallas de la aplicación web.]

### Web Applications User Flow Diagrams
    [Diagramas de flujo de usuario que representan los caminos posibles dentro de la aplicación.]

## Web Applications Prototyping
[Descripción y enlace al prototipo interactivo de la aplicación web, con escenarios de prueba definidos.]

## Domain-Driven Software Architecture

### Design-Level Event Storming
<img src="../assets/event%20storming.png" width="500">

### Software Architecture Context Diagram
<img src="../assets/c41.png" width="500">

### Software Architecture Container Diagrams
<img src="../assets/c42.png" width="500">

### Software Architecture Components Diagrams

#### Monitoring

<img src="../assets/c431.png" width="500">

#### User And Subcription

<img src="../assets/c432.png" width="500">

#### Equipment

<img src="../assets/c433.png" width="500">

#### Maintenance

<img src="../assets/c434.png" width="500">

#### Analytics

<img src="../assets/c435.png" width="500">

## Software Object-Oriented Design

### Class Diagrams


## Database Design

### Database Diagrams
[Diagramas entidad-relación o de esquema de base de datos, incluyendo tablas, claves y relaciones.]