<div align="center">

![Universidad Peruana de Ciencias Aplicadas](https://github.com/user-attachments/assets/246a4dfb-6dd5-4909-a472-6cdce8319986){width=300px height=300px}

# Universidad Peruana de Ciencias Aplicadas

## Facultad de Ingeniería

## Programa Académico de Ingeniería de Software

**Ciclo:** 2026-10  

**Código del curso:** 1ASI0729

**Curso:** Desarrollo de Aplicaciones Open Source


**NRC:** 11881

**Docente del curso:** Efraín Ricardo Bautista Ubillús

---

# Informe de Trabajo Final

**Nombre de la Startup:** SpotTrack  

**Nombre del producto:** SpotTrack

---

## Integrantes

u20241d317 - Atoche Gonzales, Nicolas Fernando  
u202411310 - Azama Fukuda, Juan Pablo  
u202413214 - Jesús Miguel Cataño Zárate 
u202414928 - Alvaro Sebastian Fernanadez Linares
u202410344 - Valentino Andre Espinoza Orrego
---

*Abril, 2026*

</div>

---

# Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|--------|------|------|-----------------------------|
|1.0.0 | 25/04/26 | Azama, Atoche, Cataño, Espinoza, Fernández | Se realizaron todos los incisos realizados a Lean UX, Needfidining, UI/UX Design y DDD|
|2.0.0 | 10/05/26 | Azama, Atoche, Cataño, Espinoza, Fernández | Se completó el despliegue de la Landing Page en GitHub Pages con todas sus secciones (Hero, Features, Pricing, Contact, Footer). Se implementó el desarrollo frontend de la Web Application en Angular con Fake RESTful API (JSON Server desplegado en Azure), cubriendo los bounded contexts de Equipment, IoT Monitoring, Heatmap, Authentication, Maintenance, Analytics, Routines y Booking. Se documentó el Sprint 2 Planning, Aspect Leaders, Sprint Backlog, Development Evidence, Services Documentation y Software Deployment Evidence. Se aplicó la corrección de artefactos pendientes del Sprint 1, incluyendo diagrama ERD, diagrama de clases, Big Picture EventStorming, evidencias de colaboración y estandarización de entrevistas. Se incorporaron las secciones de Conclusiones y Recomendaciones para ambos sprints. |

---



## Project Report Collaboration Insights

(https://github.com/SpotTrack-1ASI0729-2610-11881/Project-Report-New.git)

---

\tableofcontents

---

## Student Outcome
| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Azama Fukuda, Juan Pablo**<br>**AV1:** Dirigí las sesiones de sincronización del equipo, explicando la visión del proyecto y asignando responsabilidades para la estructuración inicial de Lean UX y la arquitectura de la Landing Page. Articulé las metas del sprint planning de manera clara para alinear el trabajo del equipo de desarrollo.<br>**TB1:** Lideré la reunión de Sprint 2 Planning, exponiendo ante el equipo la estrategia dual de trabajo: correcciones del Sprint 1 en paralelo al inicio del desarrollo del frontend Angular. Presenté la arquitectura de carpetas por Bounded Context (`auth/`, `heatmap/`, `equipment/`, `maintenance/`) y argumenté su alineación con el Domain-Driven Design previamente modelado, logrando que todos los integrantes comprendieran la organización del proyecto antes de comenzar a codificar. Expliqué asimismo el funcionamiento del JSON Server desplegado en Azure como Fake API compartida, articulando por qué una URL pública elimina los errores de integración del tipo "funciona en mi máquina".<br><br>**Atoche Gonzales, Nicolas Fernando**<br>**AV1:** Lideré la exposición técnica de la arquitectura de contenedores (C4 Model) ante el equipo de desarrollo, detallando la integración entre los nodos IoT Edge y el backend en Spring Boot. Expliqué la lógica de los triggers de auditoría en SQL Server para asegurar que los stakeholders comprendieran los mecanismos de integridad de datos.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Expuse los resultados del análisis del problema, entrevistas y validación de la solución, adaptando el mensaje tanto para usuarios finales como para administradores de gimnasios. Expliqué de forma clara el valor de la propuesta (mapas de calor, IoT y mantenimiento predictivo), facilitando la comprensión técnica y comercial según la audiencia.<br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Dirigí las sesiones de diseño y estructuración del frontend, sustentando las decisiones de la Interfaz de Usuario (UI) ante el equipo de desarrollo. Expliqué de forma clara la aplicación de principios Lean UX y evaluaciones heurísticas, adaptando el lenguaje para asegurar que mis compañeros comprendieran cómo los requerimientos de negocio de SpotTrack se traducirían en una navegación intuitiva y funcional. | Se ha logrado establecer una comunicación oral altamente efectiva que permite articular con claridad la visión técnica y comercial de SpotTrack. Mediante el liderazgo en sesiones de planificación, exposiciones de arquitectura, validaciones con usuarios y sustentación de decisiones de diseño UI, el equipo demostró la capacidad de adaptar el lenguaje a las necesidades de diversas audiencias (técnicas, administrativas y finales). En el TB1, esta competencia se consolidó al comunicar decisiones de arquitectura frontend (Bounded Contexts en Angular) y de infraestructura (Fake API en Azure) de forma comprensible para perfiles tanto técnicos como no técnicos, garantizando el alineamiento del equipo en ambos frentes de trabajo del Sprint 2. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Azama Fukuda, Juan Pablo**<br>**AV1:** Redacté y estructuré el documento *Sprint Planning 1*, documentando las asignaciones de tareas y la configuración del entorno de desarrollo. Desarrollé la arquitectura de información del proyecto utilizando markdown y aplicando jerarquías visuales para facilitar su lectura técnica.<br>**TB1:** Redacté el *Sprint 2 Planning*, la tabla de *Aspect Leaders* y el *Sprint Backlog* completo, documentando las 15 tareas de corrección (CORR), 3 tareas de infraestructura (SETUP) y las tareas de User Stories y Technical Stories con sus estimaciones, responsables y estados. Documenté la configuración del pipeline CI/CD en GitHub Actions para el despliegue continuo de la Landing Page en GitHub Pages y del Web App en Azure Static Web Apps. Elaboré además la sección de *Services Documentation Evidence*, describiendo los endpoints del Mock API con ejemplos de response y códigos HTTP, y el *Software Deployment Evidence* con la tabla de URLs de producción, asegurando la trazabilidad técnica del sprint para audiencias tanto técnicas como gerenciales.<br><br>**Atoche Gonzales, Nicolas Fernando**<br>**AV1:** Documenté exhaustivamente la arquitectura de software bajo los estándares de Domain-Driven Design (DDD) y el modelo C4. Redacté las especificaciones técnicas de los procedimientos almacenados y la lógica de los triggers de base de datos, además de estructurar las User Stories técnicas (US21-US31) enfocadas en la persistencia y analítica.<br><br>**Espinoza Orrego, Valentino Andre**<br>**AV1:** Documenté de manera estructurada el proceso de segmentación, entrevistas, user personas, journey maps y requerimientos. Redacté entregables formales como el análisis competitivo y el glosario, asegurando que los hallazgos de negocio y las necesidades de usuario fueran claros para perfiles técnicos y de gestión.<br><br>**Fernández Linares, Alvaro Sebastian**<br>**AV1:** Redacté y estructuré la documentación de la experiencia de usuario utilizando Markdown, aplicando jerarquías visuales para facilitar su lectura en el repositorio. Elaboré y documenté artefactos de diseño clave, incluyendo guiones de entrevistas, User Flows y Wireframes, plasmando gráficamente la navegación del sistema para que sirvieran como guía exacta para la implementación técnica. | La documentación producida destaca por su rigor profesional, precisión técnica y enfoque en el usuario. Al combinar diagramas arquitectónicos de alta complejidad (C4, DDD) con artefactos de experiencia de usuario (Journey Maps, Personas, User Flows, Wireframes) y requerimientos de negocio, se ha estructurado un ecosistema documental sólido que sirve como "única fuente de verdad". En el TB1, esta competencia se amplió con la redacción del Sprint 2 Backlog, la documentación de endpoints del Mock API con ejemplos estructurados y el registro del pipeline de despliegue CI/CD, evidenciando la capacidad de comunicar por escrito artefactos técnicos complejos de forma comprensible para distintos rangos de audiencia. |
