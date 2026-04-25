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

[Estrategias diferenciadas para posicionarse frente a la competencia identificada.]

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
| **Imagen** | *[Espacio para la imagen]* |
| **Edad** | 31 |
| **Ocupación** | Administrador de Gimnasio |
| **Link** | [https://youtu.be/TloRNCtUen8](https://youtu.be/TloRNCtUen8) |
| **Resumen** | La entrevista presenta a Alexander Gutiérrez, Administrador de gimnasio en Sport Life La Molina, quien comenta que el mantenimiento actual es rápido, salvo cuando requieren repuestos importados. Reconoce que gestionan la congestión en horas pico ofreciendo ejercicios alternativos o pesos libres a los clientes. Señala que un mapa de calor le ayudaría a prever la demanda específica de ciertos días, y que las alertas automáticas de mantenimiento predictivo serían magníficas para anticipar el desgaste de piezas clave (como las fajas de las trotadoras) antes de que se rompan. En cuanto al panel de control, Alexander valora métricas sobre asignación de rutinas, ingreso de invitados y comentarios de post-venta. Considera que la tecnología de cámaras podría generar reservas en adultos mayores, aunque sería bien aceptada por los jóvenes. Finalmente, destaca que un piloto gratuito lo convencería de pagar la suscripción si en 30 días arroja datos precisos sobre los horarios pico y el uso de máquinas de alta demanda, justificando así futuras compras y optimizando la gestión del local. | 




### Análisis de entrevistas

[Síntesis de los hallazgos obtenidos, patrones identificados y conclusiones por segmento.]

## Needfinding

### User Personas

[Fichas de User Personas representativas de cada segmento objetivo, incluyendo motivaciones, frustraciones y comportamientos.]

### User Task Matrix

[Matriz de tareas por usuario, indicando frecuencia e importancia de cada actividad.]

### User Journey Mapping

[Mapas de viaje del usuario que ilustran las etapas, acciones, emociones y puntos de dolor en la experiencia actual.]

### Empathy Mapping

[Mapas de empatía por segmento: qué piensan, sienten, dicen y hacen los usuarios.]

## Big Picture Event Storming

[Modelado colaborativo de los eventos del dominio a alto nivel, identificando actores, comandos, políticas y sistemas externos.]

## Ubiquitous Language

[Glosario de términos del dominio acordados por el equipo para asegurar una comunicación uniforme.]