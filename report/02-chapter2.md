# Capítulo II: Requirements Elicitation & Analysis

## Competidores

### Análisis competitivo

### 2.1.1. Análisis competitivo

**¿Por qué llevar a cabo este análisis?**
¿De qué manera la integración de hardware IoT Edge para telemetría pasiva otorga a FitNode Analytics una ventaja competitiva frente a las plataformas tradicionales de gestión de máquinas sin requerir interacción manual del usuario?

| Categoría | Criterio | FitNode Analytics | Fitco | GYMMaster | Virtuagym |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | Plataforma B2B2C con IoT Edge y visión computacional para telemetría pasiva, generación de mapas de calor en vivo y mantenimiento predictivo de maquinaria deportiva. | Software de gestión integral, enfocado en automatizar la facturación, membresías y reservas manuales de clases. | Sistema ERP global diseñado para la gestión de gimnasios con un enfoque crítico en la automatización del control de acceso físico. | Plataforma integral de coaching, gestión de clubes y retención, que combina la administración del recinto con la creación de rutinas 3D y reservas manuales. |
| **Perfil** | **Ventaja competitiva** | Manejo independiente de hardware y recolección de datos, además que no exige al usuario reservar manualmente cada máquina. | Ecosistema maduro de facturación electrónica adaptado a la región y alta familiaridad por parte de los administradores B2B. | Permite el funcionamiento continuo (24/7) de gimnasios sin necesidad de personal de recepción, bloqueando el paso a usuarios deudores. | Ofrece un ecosistema de software extremadamente profundo que hiper-personaliza el entrenamiento del usuario mediante avatares y gamificación social. |
| **Perfil de Marketing** | **Mercado objetivo** | Cadenas de gimnasios medianas y grandes en Lima, y centros deportivos universitarios que sufren por altas congestiones y presupuestos ajustados. | Centros de fitness, centros de yoga, academias de artes marciales y gimnasios que buscan digitalizar su administración básica. | Franquicias de gimnasios comerciales, locales 24 horas y centros deportivos que priorizan la reducción extrema de costos en personal. | Cadenas de gimnasios premium, entrenadores personales independientes y corporaciones que buscan un compromiso total y seguimiento nutricional del usuario. |
| **Perfil de Marketing** | **Estrategias de marketing** | Oferta de pilotos gratuitos de 30 días instalando hardware IoT en zonas críticas, para demostrar el retorno de inversión con datos tangibles. | Estrategias agresivas de Inbound Marketing, webinars para dueños de gimnasios y alianzas estratégicas con pasarelas de pago locales (Niubiz, Culqi). | Posicionamiento SEO agresivo a nivel internacional, demostraciones guiadas de software y venta combinada de su hardware. | Fuerte comunidad en redes sociales, educación gratuita para entrenadores y un modelo freemium en su aplicación móvil para captar usuarios masivamente. |
| **Perfil de Producto** | **Productos & servicios** | Dashboard gerencial B2B para decisiones de CAPEX/OPEX y aplicación web Angular B2C con visualización de aforo en tiempo real. | Plataforma ERP web alojada en la nube para gerencia y aplicación móvil B2C de marca blanca para que los usuarios aparten sus cupos manualmente. | Software Cloud complementado con hardware propietario: lectores RFID, escáneres biométricos de huella dactilar y torniquetes de acceso. | Software de gestión administrativa, motor de creación de rutinas con animaciones 3D, seguimiento de dieta y módulo de reserva de áreas/máquinas. |
| **Perfil de Producto** | **Precios & costos** | Modelo SaaS B2B con membresía mensual desde $69 USD/mes (Basic), $109 USD/mes (Mid), $189 USD/mes (Platinum). | Modelo SaaS con tarifas escalonadas: plan Lite desde $59 USD/mes, Core a $99 USD/mes y Growth a $169 USD/mes. | Costo mensual de licencia desde $89 USD/mes (Foundation), $129 USD/mes (Advanced), $209 USD/mes (Professional), en software only, con software + door accesses va desde $129 USD/mes (Foundation), $169 USD/mes (Advanced), $249 USD/mes (Professional). | Plan base desde $29 USD/mes. Estructura modular donde planes superiores encarecen la solución con precios personalizados. |
| **Perfil de Producto** | **Canales de distribución** | Web y Móvil | Web y Móvil | Web y Móvil | Web y Móvil |
| **Análisis SWOT** | **Fortalezas** | Elimina la incertidumbre del usuario mostrando disponibilidad en vivo y reduce el OPEX por reparaciones. | Interfaz de facturación probada, integración contable robusta y comunidad educada en reservas. | Control de aforo exacto y en tiempo real, erradicación de morosidad mediante barreras físicas. | Excelente gamificación comunitaria y alta capacidad para retener al cliente mediante motivación digital. |
| **Análisis SWOT** | **Debilidades** | Dependencia de la estabilidad de la red Wi-Fi del local y complejidad logística en la instalación física. | Carencia de telemetría de hardware; la medición de ocupación depende de la acción voluntaria del cliente. | Ceguera intramuros: el sistema ignora por completo qué máquinas se usan o si están averiadas. | Su sistema de reservas asume que la máquina está operativa; no detecta averías físicas reales. |
| **Análisis SWOT** | **Oportunidades** | Capitalizar el Churn Rate del 30-40% causado por la inoperatividad de equipos y frustración de filas. | Expandir sus módulos abriendo su API a startups de IoT para ofrecer datos de uso de máquinas. | Desarrollar sensores internos para complementar su dominio de las puertas o adquirir empresas de analítica. | Evolucionar su motor de rutinas para recomendar ejercicios dinámicamente según saturación real. |
| **Análisis SWOT** | **Amenazas** | Gimnasios con maquinaria de última generación con telemetría propietaria preinstalada. | Surgimiento de startups que eliminen el tedioso proceso de reservar manualmente. | Barreras arancelarias para importar hardware especializado y soporte técnico lento. | Exceso de funciones que puede abrumar a usuarios que solo buscan entrenar rápido. |

### Estrategias y tácticas frente a competidores

Desarrollar estrategias y tácticas efectivas para enfrentar a nuestros competidores requiere de un enfoque cuidadoso y planificado. A continuación se presentan algunas estrategias y tácticas que podrían ser consideradas para tener una ventaja competitiva frente a otras alternativas:

**Diferenciación por telemetría pasiva y automatización:** A diferencia de competidores como Virtuagym o Fitco, que dependen de que el usuario reserve manualmente una máquina o clase , SpotTrack se diferencia al eliminar la interacción manual mediante el uso de hardware IoT Edge. Esta ventaja permite recolectar datos reales de uso de forma pasiva, ofreciendo un mapa de calor en vivo que refleja la realidad del local sin errores humanos. Además, se aplicará un modelo B2B SaaS con planes escalables desde los $69 USD mensuales, facilitando el acceso a gimnasios medianos y grandes en Lima.

**Optimización de la rentabilidad y soporte preventivo:** 
Mientras que los sistemas tradicionales presentan una "ceguera intramuros" al ignorar si una máquina está averiada , nuestra táctica principal de acercamiento será demostrar el ahorro directo en el OPEX. Al migrar de un mantenimiento correctivo (que es de 3 a 5 veces más costoso) a uno preventivo y predictivo , los administradores logran maximizar la vida útil de sus activos. Para asegurar la adopción, se ofrecerá un piloto gratuito de 30 días instalando hardware en zonas críticas (como el área de cardio), demostrando el retorno de inversión con datos tangibles antes del cierre de venta.

**Innovación tecnológica enfocada en la privacidad y eficiencia:**
SpotTrack se posicionará como líder en tecnología Edge Computing, procesando el reconocimiento de imágenes directamente en el dispositivo para enviar únicamente paquetes ligeros de datos (JSON) a la nube. Esta táctica no solo evita la saturación de la red Wi-Fi del gimnasio —una de las debilidades identificadas frente a la competencia — sino que garantiza la privacidad total al no grabar ni transmitir video de los usuarios. Esto permite ofrecer un dashboard gerencial con métricas claras y alertas automáticas que superan la funcionalidad de los ERP tradicionales que solo gestionan accesos y membresías.

## Entrevistas

### Diseño de entrevistas

A continuación se presentan las preguntas para las entrevistas a los segmentos objetivos

Segmento 1: Administradores y Gerentes de Operaciones

Antes de las preguntas: Por favor, indícanos la siguiente información para registrar tu participación:
Nombre:
Cargo / Ocupación (confirmar si es administrador de sede o gerente de operaciones)
Edad
Gimnasio / Institución a la que pertenece:

Segmento 1: Administradores y Gerentes de Operaciones
1. Cuéntame sobre tu experiencia actual gestionando el mantenimiento y la disponibilidad de las máquinas en tu sede.
¿Cómo es el proceso exacto desde que una máquina falla hasta que el técnico la repara?
2. ¿Qué impacto financiero y operativo notas cuando una máquina de alta demanda (como una trotadora o rack de sentadillas) se avería repentinamente?
¿Tienen un presupuesto asignado para mantenimiento correctivo de emergencia o afecta directamente la rentabilidad del mes?
3. Durante las "horas pico" (mañanas o después de las 6:00 PM), ¿cómo manejan la congestión del local y las quejas de los usuarios por los tiempos de espera?
4. Si pudieras contar con un "mapa de calor" en tiempo real que te muestre qué máquinas están libres, ocupadas o en mantenimiento, ¿de qué manera utilizarías esa información en tu gestión diaria?
5. ¿Qué tan valioso sería para ti recibir alertas automáticas de "mantenimiento predictivo" (por ejemplo, saber que una cinta de correr superó las 500 horas de uso y necesita revisión) antes de que se rompa?
6. A la hora de tomar decisiones de inversión, como comprar máquinas nuevas o trasladar equipos de una sede a otra, ¿en qué información o reportes te basas actualmente?
¿Te daría más seguridad basar esas compras en estadísticas exactas de uso generadas por sensores?
7.  Si abres tu computadora el lunes por la mañana para revisar cómo le fue a tu local el fin de semana, ¿cuáles son los 3 datos principales que necesitas ver en un dashboard para sentir que tienes el control total?
8. Para implementar este sistema, planeamos usar pequeñas cámaras con procesamiento Edge (que solo detectan si la máquina está ocupada o libre, sin grabar ni guardar video de las personas). ¿Tendrías o crees que tus clientes tendrían alguna preocupación sobre la privacidad con este enfoque?
9. Pensando en tu staff de piso (entrenadores, personal de limpieza), ¿cómo crees que un sistema de alertas automatizado cambiaría la rutina de su día a día?
10. Si te ofrecemos hacer un plan piloto gratuito de FitNode Analytics durante un mes, instalando los sensores en una zona específica (como la zona de cardio), ¿cuál es el principal resultado o métrica que necesitarías ver para convencerte de pagar una suscripción mensual por el servicio?


Segmento 2: Clientes frecuentes a gimnasios
Antes de las preguntas: Por favor, indícanos la siguiente información para registrar tu participación:
Nombre:
Ocupación (confirmar si es estudiante universitario, oficinista, etc.):
Edad
Gimnasio al que asistes regularmente:

1. Cuéntame cómo es un día típico cuando vas a entrenar en "hora pico". ¿Cuál es tu primera impresión al entrar al área de musculación o cardio?
2. ¿Cómo te afecta anímica y físicamente cuando llegas con el tiempo justo para tu rutina y encuentras tu máquina principal ocupada, o peor aún, con un letrero de "fuera de servicio"?
3. ¿Alguna vez la constante saturación del local o la cantidad de máquinas averiadas ha sido un factor para que consideres cancelar tu membresía o cambiarte de gimnasio? Cuéntame sobre esa experiencia.
4. Si tuvieras una aplicación en tu celular que te mostrara un "mapa de calor" en tiempo real (es decir, ver exactamente qué máquinas están en rojo/ocupadas o verde/libres) antes de salir de tu casa, ¿de qué manera cambiaría la forma en que planificas tu visita al gimnasio?
5. En esos momentos donde tu máquina preferida está inoperativa o muy solicitada, ¿qué tan útil te resultaría que una aplicación te sugiera automáticamente una rutina alternativa con pesas libres para no perder tu ritmo de entrenamiento?
6. En nuestro proyecto estamos considerando un sistema de recompensas. ¿Qué tipo de beneficios (descuentos en membresía, suplementos, mercadería) te motivarían a actualizar manualmente en la app el estado de una máquina cuando terminas de usarla?
7. Para los equipos de altísima demanda (como poleas cruzadas o racks), ¿qué opinas de una función de "reserva exprés" que te permita separar un espacio de 15 minutos exclusivamente durante las horas de mayor afluencia?
8. ¿Te generaría valor recibir notificaciones automáticas (tipo push) en tu celular avisándote que esa trotadora o máquina que reportaste como malograda la semana pasada ya volvió a estar operativa? ¿Por qué?
9. Considerando que estarías usando esta aplicación en medio de tu entrenamiento, sudando y con poco tiempo para mirar el celular, ¿qué características visuales o de diseño considerarías obligatorias para que te resulte cómoda y rápida de leer?
10. Si tu gimnasio actual te ofreciera esta plataforma de forma totalmente gratuita a partir de mañana, ¿cuál crees que sería el principal obstáculo o motivo por el que quizás no llegarías a usarla todos los días?



### Registro de entrevistas

**Segmento 1: Administrador de Gimnasio y Gerente de Operaciones**

### Entrevista 1: Alexander Gutierrez

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Alexander Gutierrez |
| **Imagen** | <img src="../assets/EntrevistaAlexander.jpeg" alt="EntrevistaAlexander" width="400" height="150"> |
| **Edad** | 31 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://youtu.be/TloRNCtUen8](https://youtu.be/TloRNCtUen8) |
| **Resumen** | La entrevista presenta a Alexander Gutiérrez, Administrador de gimnasio en Sport Life La Molina, quien comenta que el mantenimiento actual es rápido, salvo cuando requieren repuestos importados. Reconoce que gestionan la congestión en horas pico ofreciendo ejercicios alternativos o pesos libres a los clientes. Señala que un mapa de calor le ayudaría a prever la demanda específica de ciertos días, y que las alertas automáticas de mantenimiento predictivo serían magníficas para anticipar el desgaste de piezas clave (como las fajas de las trotadoras) antes de que se rompan. En cuanto al panel de control, Alexander valora métricas sobre asignación de rutinas, ingreso de invitados y comentarios de post-venta. Considera que la tecnología de cámaras podría generar reservas en adultos mayores, aunque sería bien aceptada por los jóvenes. Finalmente, destaca que un piloto gratuito lo convencería de pagar la suscripción si en 30 días arroja datos precisos sobre los horarios pico y el uso de máquinas de alta demanda, justificando así futuras compras y optimizando la gestión del local. | 


### Entrevista 2: Luis Romero

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Luis Romero |
| **Imagen** | <img src="../assets/EntrevistaLuis.jpeg" alt="EntrevistaLuis" width="400" height="150">|
| **Edad** | 51 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://youtu.be/HjYWVshhpdE?si=Jyhb6aqMUrhtSwiW](https://youtu.be/HjYWVshhpdE?si=Jyhb6aqMUrhtSwiW) |
| **Resumen** | Luis Romero, Administrador de gimnasio en la UPC y YMCAID, destaca que la gestión en universidades es mucho más lenta que en gimnasios comerciales, donde una reparación puede tardar solo un día frente a varias semanas por burocracia. Señala que las fallas en equipos generan quejas inmediatas y afectan la renovación de membresías. Para manejar la congestión en horas pico, promueve compartir máquinas, pero considera clave el uso de mapas de calor en gimnasios grandes. Valora especialmente las alertas de mantenimiento predictivo, ya que ayudan a no olvidar revisiones. Prefiere equipos de musculación nacionales por repuestos rápidos y cardio importado. Resalta la importancia de sensores (sobre todo en trotadoras) para medir uso y anticipar fallas. En su panel ideal prioriza asistencia, quejas y renovaciones. También ve útil el uso de cámaras con procesamiento Edge para supervisión sin afectar la privacidad. Finalmente, un piloto gratuito lo convencería si ofrece datos precisos sobre afluencia y uso para tomar decisiones de mantenimiento o reemplazo. |

### Entrevista 3: Percy Baraybar

| Campo | Detalle |
| :--- | :--- |
| **Entrevistado** | Percy Baraybar |
| **Imagen** | <img src="../assets/EntrevistaPercy.jpeg" alt="EntrevistaPercy" width="400" height="150">|
| **Edad** | 30 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://youtu.be/VcaT481wHk8?si=4nAQ01GHBRMfj07z](https://youtu.be/VcaT481wHk8?si=4nAQ01GHBRMfj07z) |
| **Resumen** | Percy, administrador de Smartfit Miraflores con 5 años de experiencia, destaca que en gimnasios de alto volumen el mantenimiento correctivo es mucho más costoso y crítico para la percepción del cliente que el preventivo. Señala que las fallas en máquinas de alta demanda generan cuellos de botella y riesgos de no renovación. Para gestionar la congestión en horas pico, aplica la "gestión de piso", pero reconoce que falta una herramienta visual para que el socio entienda la capacidad del local. Valora enormemente un mapa de calor para redistribuir al staff y optimizar el mix de máquinas basado en datos reales de uso, no en percepciones subjetivas. Considera que las alertas de mantenimiento predictivo cambiarían las reglas del juego al evitar que los equipos queden fuera de servicio. En su panel de control ideal, prioriza el tiempo de inactividad (downtime), la saturación por zona y el ranking de desgaste de equipos. Finalmente, apoya el uso de cámaras con procesamiento Edge si se garantiza la transparencia sobre la privacidad, viendo un gran beneficio en que los socios consulten la disponibilidad desde una app. Un piloto de Fitnote Analytics lo convencería si logra una reducción mínima del 20% en las quejas por disponibilidad y demuestra una alta precisión en la data para mantener la credibilidad ante el usuario. |

#### Entrevistado 4
<img src="../assets/foto-entrevista-1.png" alt="foto-entrevista-1" width="400" height="150">

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Joan Steffano Quispe Gamez |
| **Ocupación** | Estudiante universitario (UPC) |
| **Frecuencia** | 3 a 4 veces por semana |
| **Horario** | Nocturno (Post-clases) |
| **Contexto** | Entrena de noche debido a su alta carga académica. |
| **Link** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414928_upc_edu_pe/IQDwUfqEP6J8Sr_AMTcZaW80AVugegqiYVjdOyG2RY3agzs?e=dymEnS&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |

#### Entrevistado 5
<img src="../assets/foto-entrevista-2.png" alt="foto-entrevista-2" width="400" height="149">

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Fabián Suárez |
| **Ocupación** | Estudiante y trabajador |
| **Frecuencia** | 3 a 4 días a la semana (interdiario) |
| **Duración** | Entre 1 a 2 horas |
| **Contexto** | Adapta sus entrenamientos según su carga laboral y académica. |
| **Link** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414928_upc_edu_pe/IQA_G4YvOVSuSrJJqjakOjOpAQnSD43pUj6g0topSDxpyg8?e=8sTjzL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D |

### Análisis de entrevistas

#### Entrevista 4:
#### Hábitos y Entorno:
Joan suele asistir en **"hora punta"**, lo que implica una saturación casi total del local. Aunque su intención es seguir una planificación rigurosa, la falta de disponibilidad de equipos lo obliga a **improvisar constantemente**, alterando el orden de su rutina según las máquinas que se van liberando.

#### Frustraciones Principales (Pain Points):
* **Pérdida de tiempo efectiva:** Esperas prolongadas para usar máquinas o necesidad de buscar pesas desordenadas entre series.
* **Interrupción del ritmo:** El enfriamiento muscular por las esperas rompe la intensidad del entrenamiento y extiende su permanencia en el gimnasio más de lo previsto.
* **Infraestructura deficiente:** La presencia de equipos "fuera de servicio" le genera frustración al tener que buscar sustitutos de última hora (ej. cambiar poleas por prensa).

#### Fidelización y Retención:
Joan manifiesta que la saturación constante y el mantenimiento deficiente de los equipos son factores determinantes para su permanencia; afirma que **preferiría migrar a otro gimnasio** si estas condiciones persisten.

#### Entrevista 5:
#### Hábitos y Entorno:
Fabián organiza sus sesiones con una **división muscular estricta** (ej. martes de brazos, jueves de pecho/piernas). Generalmente entrena en horarios de baja afluencia, lo que le permite cumplir su rutina sin interrupciones. Sin embargo, en temporadas de alta demanda (como el verano), opta por **flexibilizar su entrenamiento**, priorizando el área cardiovascular sobre las pesas para evitar aglomeraciones.

#### Frustraciones Principales (Pain Points):
* **Corte de flujo muscular:** Debido a que entrena zonas específicas por día, la indisponibilidad de una máquina crítica rompe el ritmo de su sesión, afectando la efectividad que busca.
* **Ineficiencia al compartir equipos:** Considera que alternar máquinas con otros usuarios es una fuente de pérdida de tiempo, principalmente por la necesidad de ajustar pesos y esperar tiempos de descanso ajenos.

#### Fidelización y Retención:
A diferencia de otros usuarios, Fabián muestra una **fidelidad estable** hacia su centro actual; indica que ni la saturación ocasional ni el estado técnico de los equipos son factores que lo llevarían a cancelar su membresía.



## Needfinding

### User Personas

**ADMINISTRADOR DE GIMNASIO**
![User Persona Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/User%20Persona%20Alexis%20Villanueva.png)


**CLIENTE FRECUENTE DE GIMNASIO**
![User Persona Andrea Mendoza](../assets/NEEDFINDING%20ARTEFACTS/User%20Persona%20Andrea%20Mendoza.png)

### User Task Matrix


| Tarea | Frecuencia (Alexis) | Importancia (Alexis) | Frecuencia (Andrea) | Importancia (Andrea) |
| :--- | :--- | :--- | :--- | :--- |
| Revisar disponibilidad de máquinas en tiempo real | Alta | Alta | Alta | Alta |
| Identificar máquinas con alto uso/desgaste | Alta | Alta | Baja | Media |
| Recibir alertas de mantenimiento predictivo | Media | Alta | Baja | Media |
| Planificar mantenimiento de equipos | Media | Alta | Muy Baja | Media |
| Analizar estadísticas de uso (dashboard) | Media | Alta | Baja | Media |
| Reubicar máquinas según demanda | Baja | Alta | Muy Baja | Baja |
| Consultar mapa de calor antes de ir al gym | Muy Baja | Media | Alta | Alta |
| Evitar tiempos de espera en máquinas | Baja | Media | Alta | Alta |
| Buscar máquinas libres dentro del gimnasio | Muy Baja | Baja | Alta | Alta |
| Recibir notificaciones de disponibilidad | Baja | Media | Media | Alta |
| Reportar máquinas averiadas | Baja | Media | Media | Media |
| Tomar decisiones de compra de equipos | Baja | Alta | Muy Baja | Baja |
| Optimizar distribución del espacio del gimnasio | Baja | Alta | Baja | Media |
| Reducir quejas por saturación | Media | Alta | Alta | Alta |
| Mejorar experiencia del usuario final | Media | Alta | Alta | Alta |
### User Journey Mapping


**JOURNEY MAP ADMINISTRADOR DE GIMNASIO**
![Journey Map Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/Journey%20Map%20Alexis%20Villanueva.png)


**JOURNEY MAP CLIENTE FRECUENTE DE GIMNASIO**
![Journey Map Andrea Mendoza](../assets/NEEDFINDING%20ARTEFACTS/Journey%20Map%20Andrea%20Mendoza.png)



### Empathy Mapping

![Impact Mappign Alexis Villanueva](../assets/NEEDFINDING%20ARTEFACTS/Impact%20Mapping%20Alexis%20Villanueva.png)


![Impact Mapping Andre Mendoza](../assets/NEEDFINDING%20ARTEFACTS/Impact%20Mapping%20Andre%20Mendoza.png)

## Big Picture Event Storming

[Modelado colaborativo de los eventos del dominio a alto nivel, identificando actores, comandos, políticas y sistemas externos.]

## Ubiquitous Language


Para mejorar la cohesión del equipo, adoptaremos el Ubiquitous Language. Esta herramienta facilitará la comprensión de los objetivos y agilizará la resolución de dudas en el proyecto.

**Telemetry (Telemetría)**: Recopilación automática y a distancia de datos sobre el uso físico de las máquinas de ejercicio mediante dispositivos IoT, enviando esta información a la nube.

**Heat Map (Mapa de calor)**: Representación visual y semaforizada en la aplicación que indica la disponibilidad de las máquinas en tiempo real mediante colores (ej. Verde: Libre, Rojo: Ocupado).

**IoT Edge (Procesamiento en el borde)**: Tecnología utilizada en los sensores o cámaras que procesa la información directamente en el dispositivo físico, enviando únicamente el estado en formato JSON a la base de datos para no saturar la red y respetar la privacidad de los usuarios.

**Predictive Maintenance (Mantenimiento predictivo)**: Estrategia y alertas automatizadas para realizar revisiones a los equipos antes de que fallen, basándose en el acumulado de horas límite de uso seguro reportadas por los sensores.

**Corrective Maintenance (Mantenimiento correctivo)**: Reparación de emergencia y costosa que se realiza cuando una máquina falla repentinamente durante la operación del local.

**Downtime (Tiempo de inactividad)**: Periodo crítico durante el cual una máquina de ejercicio se encuentra fuera de servicio por avería, generando tiempos de espera y molestia en los usuarios.

**Churn Rate (Tasa de abandono)**: Porcentaje anual de usuarios que deciden no renovar o cancelar su membresía del gimnasio, frecuentemente impulsado por la frustración ante instalaciones abarrotadas y máquinas inoperativas.

**Subutilization (Subutilización)**: Condición estadística en la que una máquina específica registra una tasa de uso excepcionalmente baja en comparación con otras, lo que sugiere al administrador que debe ser reubicada.

**Crowdsourcing (Colaboración masiva)**: Acción mediante la cual los propios usuarios del gimnasio actualizan el estado de disponibilidad de un equipo en la plataforma a cambio de puntos de recompensa.

