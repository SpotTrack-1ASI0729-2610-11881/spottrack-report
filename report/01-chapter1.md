# Capítulo I: Introducción

## Startup Profile

### Descripción de la Startup

**Descripción general:**
LocalSync nace para cerrar la brecha entre la gestión tradicional de recintos deportivos y la innovación tecnológica impulsada por el Internet de las Cosas (IoT). Somos una startup comprometida con la optimización de los activos físicos y la mejora de la experiencia del usuario en gimnasios, asegurando que la toma de decisiones basada en datos reemplace a la intuición, maximizando la rentabilidad y la satisfacción del cliente.

**Misión:**
La misión de LocalSync es ofrecer un servicio inteligente de monitoreo y analítica de uso de equipos deportivos, orientado a gimnasios y centros de fitness universitarios. Buscamos optimizar sus procesos operativos y de mantenimiento mediante el uso de IoT (cámaras con visión computacional y sensores en el Edge) para transformar el uso físico de las máquinas en datos accionables gestionados eficientemente en la nube.

**Visión:**
La visión de LocalSync es ser la plataforma líder en telemetría y gestión de activos deportivos en Perú, promoviendo una administración moderna y predictiva que impulse a los gimnasios hacia una transformación digital eficiente y a la vanguardia de la tecnología.

### Perfiles de integrantes del equipo

![foto-juan-pablo-azama](../assets/foto-juan-pablo-azama.png)

Soy **Juan Pablo Azama Fukuda** (Código: u202411310), estudiante de quinto ciclo de Ingeniería de Software. En el ámbito técnico, poseo una base sólida en lenguajes como C++, Java y Unity. Para este proyecto, mi contribución principal tendrá un foco en la parte de diseño/frontend de la aplicación, tanto en la aplicación web y el landing page. Para ello, me respaldo en mis conocimientos decentes en Figma, HTML y CSS, además de mi manejo de React.js, competencias que seguiré escalando a lo largo del curso. A nivel de gestión, asumo el rol de team leader, con la responsabilidad de articular los esfuerzos del equipo, guiar el desarrollo y garantizar una metodología de trabajo eficiente.


Soy **Valentino Andre Espinoza Orrego** (código: u202410344), "Estudiante de Ingeniería de Software en la UPC apasionado por la tecnología y el aprendizaje constante. Me especializo en potenciar mis capacidades técnicas y analíticas, trabajando colaborativamente para resolver problemas con eficiencia. Busco oportunidades prácticas donde aplicar mis conocimientos, contribuir responsablemente y desarrollar soluciones funcionales de alto impacto

![foto-nicolas](../assets/foto-nicolas.png)

Soy **Nicolas Fernando Atoche Gonzales**, actualmente estoy en el tercer ciclo de la carrera de ingeniería de software. Poseo un conocimiento básico/intermedio en programación con C++, java y Lua. Además, cuento con conocimientos en el desarrollo de videojuegos. Dentro del equipo, estoy encargado en el desarrollo del backend  del proyecto utilizando el entorno Angular. A su vez suelo orientarme por el conocimiento y el pensamiento lógico, con lo cual suelo buscar la solución más óptima y ágil dentro de un problema a través de pasos sencillos y definidos que construyan una base sólida donde pueda desarrollar respuestas claras y efectivas.


## Solution Profile

### Antecedentes y problemática

La gestión operativa y el mantenimiento de equipos en centros deportivos representan un desafío crítico en la actualidad. Una administración deficiente, caracterizada por el desconocimiento del estado real y la disponibilidad de las máquinas, desencadena consecuencias operativas y financieras severas para las empresas. De acuerdo con ResQ (s.f.), cuando se producen fallas repentinas en los equipos por falta de monitoreo, los costos de reparación suelen ser entre 3 y 5 veces más altos en comparación con los gastos de un mantenimiento preventivo programado.

Además del impacto económico directo, la experiencia del cliente se ve profundamente perjudicada. El 70% de los usuarios finales manifiesta una alta insatisfacción al descubrir que su máquina preferida se encuentra averiada en el momento de su entrenamiento (Athletic Business, 2024, como se citó en DINGG, 2025). Esta falta de visibilidad impide que los usuarios organicen su tiempo adecuadamente, generando desánimo e incrementando significativamente la probabilidad de que cancelen sus suscripciones. Paralelamente, para la administración del establecimiento, esta carencia de información centralizada y en tiempo real se traduce en una planificación de mantenimiento ineficiente y en una toma de decisiones imprecisa respecto a la reubicación, reparación o compra de nuevos equipos.

### Lean UX Process


#### Lean UX Problem Statements

Nuestro servicio ofrece una plataforma de telemetría y visualización en tiempo real para monitorear el uso, desgaste y disponibilidad de las máquinas de ejercicio. Hemos observado que los gimnasios enfrentan sobrecostos por mantenimientos reactivos y tiempos prolongados de equipos inoperativos, a la par que los usuarios experimentan largos tiempos de espera para entrenar durante las horas pico, reduciendo la tasa de retención. ¿De qué manera podemos visibilizar la ocupación y el estado de los activos para optimizar la planificación preventiva de la gerencia y permitir a los usuarios ejecutar sus rutinas sin tiempos muertos?


#### Lean UX Assumptions

¿Quién es el usuario?
Nuestros usuarios principales son los administradores/dueños de gimnasios y los usuarios finales (clientes). El administrador utilizará el sistema para ver reportes y alertas, mientras que el cliente lo usará para ver la disponibilidad en tiempo real.
¿Dónde encaja nuestro producto en su trabajo o vida?
Para el cliente, encaja en su rutina diaria de planificación de entrenamiento (antes de ir al gimnasio o mientras descansa entre series). Para el administrador, es una herramienta de gestión diaria y de planificación financiera mensual.
¿Qué problemas tiene nuestro producto que resolver?
La saturación de máquinas, la pérdida de tiempo de los usuarios, las averías imprevistas de equipos costosos y la mala distribución del inventario de máquinas entre diferentes locales.
¿Cuándo y cómo es usado nuestro producto?
Los clientes lo usarán en sus smartphones principalmente en horas pico o minutos antes de dirigirse al local. Los administradores lo usarán en computadoras de escritorio o tablets durante su jornada laboral para revisar el estado del local.
¿Qué características son importantes?
Mapa de calor de disponibilidad en tiempo real, registro automático de horas de uso vía IoT, notificaciones de mantenimiento predictivo, panel estadístico de máquinas más/menos usadas, e interfaz responsiva.
¿Cómo debe verse nuestro producto y cómo debe comportarse?
Debe tener un aspecto moderno, deportivo y ágil. Para los usuarios, debe ser extremadamente visual (uso de semaforización: verde, amarillo, rojo). Para los administradores, debe lucir como una herramienta profesional y gerencial (dashboards claros, tablas ordenadas y alertas visibles).

Creo que mi cliente necesita una mejora en la organización de sus tiempos de rutina y, por el lado administrativo, una reducción en costos de mantenimiento.
Estas necesidades se pueden resolver con la implementación de nuestra plataforma IoT de telemetría y mapas de calor.
Nuestros clientes iniciales son las cadenas medianas de gimnasios en Lima, regiones cercanas a Lima y centros deportivos universitarios.
El mayor valor que prioriza mi cliente (usuario) es no hacer filas; y para el administrador, maximizar la vida útil de sus activos y tener menos pérdidas.
El cliente también puede obtener beneficios adicionales como tener certeza de cómo invertir su capital de manera más precisa, enfocar la labor operativa del staff hacia los clientes en vez de perder tiempo en la inspección de máquinas. Esto es por la parte administrativa. Por otro lado, con respecto a los usuarios finales, estos podrán tomar decisiones más inteligentes a la hora de planificar sus rutinas, lo que mejora drásticamente la conveniencia y la utilidad percibida de su membresía.
Obtendremos clientes ofreciendo un piloto gratuito de un mes instalando hardware básico en una zona específica (ej. zona de cardio) para demostrar el valor de la data obtenida.
Generamos ingresos mediante un modelo B2B SaaS: cobramos a los gimnasios una suscripción mensual por el uso del panel analítico y un costo de instalación inicial del hardware IoT.
Nuestra competencia principal serían las aplicaciones genéricas de reservas de gimnasios, pero los venceremos mediante nuestro valor diferencial. No requerimos que el usuario reserve una máquina manualmente, sino que usamos hardware IoT (cámaras/sensores) para reportar la realidad de forma automática y pasiva.
Los venceremos debido a que proponemos una solución utilizando diversos dispositivos IoT que permiten una recopilación de datos eficiente, además de que estos datos luego son convertidos a mapas de calor y gráficos estadísticos. Todo esto permite mejorar la administración de las máquinas y la satisfacción del cliente, lo que significa más ingresos y menos pérdidas para la empresa.
Nuestros mayores riesgos son la complejidad en la instalación física del hardware y la dependencia de la red Wi-Fi del local. 
Esto lo resolveremos utilizando protocolos ligeros (como MQTT o peticiones HTTP optimizadas hacia Spring Boot) y dispositivos Edge que puedan guardar temporalmente la data si se cae la red.
Otras suposiciones que tenemos es que ciertos gimnasios ya tengan este tipo de sistemas o que cierta maquinaria venga con telemetría ya incluída. En consecuencia, nuestra idea carecería de valor. Por ende, es importante tener en mente que si un gimnasio ya posee este sistema debemos proponer una mejora.
#### Lean UX Hypothesis Statements

[Hipótesis formuladas a partir de los supuestos, con métricas de éxito definidas.]

#### Lean UX Canvas

Business Outcomes:
Sabremos que nuestra solución funcionó cuando:
Los administradores logren reducir sus gastos en mantenimiento correctivo en un 20%.
La cantidad de máquinas reportadas como "Fuera de Servicio" disminuya significativamente.
Los administradores utilicen el panel estadístico para trasladar máquinas poco usadas a locales con mayor demanda.
Users:
Nuestro servicio será utilizado de forma B2B por administradores de sedes, gerentes de operaciones y técnicos de mantenimiento de gimnasios. De forma B2C, será consumido por jóvenes y adultos que pagan membresías y desean optimizar su tiempo de entrenamiento. Se espera que los gimnasios asuman el costo de la suscripción para brindar la aplicación móvil como un valor agregado gratuito a sus clientes.
User Outcomes & Benefits:
Los administradores adquirirán el beneficio de una plataforma predictiva que les evitará gastos sorpresa y mejorará el ROI de sus máquinas. Sabremos que han logrado su objetivo cuando logren anticipar el desgaste de una máquina y programar su engrase antes de que falle. Los usuarios finales obtendrán el beneficio de la previsibilidad y la gestión del tiempo, logrando terminar sus rutinas más rápido al evitar los "cuellos de botella" en el gimnasio.
Features:
Integración IoT Edge: Cámaras o sensores que detectan ocupación y envían estados JSON a la API RESTful.
Mapa de Calor en Vivo: Interfaz en Angular que muestra por colores la disponibilidad de máquinas por sede.

Tracker de Horas de Uso: Acumulación automática de minutos de uso por máquina en la base de datos (PostgreSQL).
Mantenimiento Predictivo: Alertas automatizadas cuando una máquina supera su umbral seguro de uso.
Estadísticas de Reubicación: Gráficos comparativos que identifican máquinas subutilizadas frente a máquinas sobreexplotadas.
Gestión Multisede: Filtros para que el usuario o administrador cambie de local y vea el inventario respectivo.



Despacho automatizado de tickets técnicos: Asignación y notificación inmediata de órdenes de trabajo al equipo de mantenimiento ante una falla.
Trazabilidad del ciclo de vida (ROI del activo): Registro histórico de costos de reparación vs. depreciación para justificar el reemplazo o compra de máquinas.
Motor de sugerencia de rutinas alternativas: Algoritmo que recomienda ejercicios con pesas libres cuando la máquina requerida está inoperativa.
Notificaciones push de resolución: Avisos automáticos a los usuarios cuando un equipo que reportaron vuelve a estar operativo.
Analítica predictiva de compras: Reportes basados en la tasa de uso para sugerir qué equipos exactos se deben adquirir o descartar.
Sistema de recompensas (Crowdsourcing): Asignación de puntos canjeables a los usuarios que actualicen el estado de disponibilidad de los equipos.
Calculadora de impacto financiero por inactividad: Dashboard que cuantifica la pérdida de dinero estimada por cada hora que una máquina crítica está rota.
Gestión automatizada de stock de repuestos: Control de inventario de piezas clave (cables, poleas) con alertas automáticas de reabastecimiento.
Calendario inteligente de bloqueos: Programador que agenda los mantenimientos preventivos exclusivamente en los horarios de menor afluencia histórica.
Directorio de garantías y proveedores: Base de datos centralizada con fechas de caducidad de garantías y SLA de tiempos de respuesta de fabricantes externos.
Sistema de reserva exprés: Función para separar slots de 15 minutos en equipos de altísima demanda (ej. racks de sentadillas) durante horas pico.

## Segmentos objetivo

El modelo de negocio es B2B2C (Business to Business to Consumer), por lo que identificamos dos segmentos objetivo principales:
Administradores y Gerentes de Operaciones
Aspectos demográficos:
Sexo: Masculino o femenino.
Edad: 30 – 55 años.
Nivel socioeconómico: A, B y C (alta, media-alta).
Ocupación: Gerentes de operaciones, jefes de mantenimiento o administradores de sede.
Aspectos geográficos:
Nacionalidad: Peruana o extranjera.
Zona geográfica: Urbana.
Departamento: Lima Metropolitana y ciudades a nivel nacional con presencia de gimnasios comerciales.



Aspectos psicográficos:
Son los responsables directos de rendir cuentas sobre los presupuestos operativos (OPEX) y salvaguardar el valor de los equipos (CAPEX).
Sienten frustración al operar a ciegas y depender de la intuición o reportes en papel.
Buscan herramientas y plataformas que les permitan tomar decisiones basadas en datos duros, ahorrar dinero y evitar los mantenimientos de emergencia.
Clientes frecuentes de gimnasio 
Aspectos demográficos:
Sexo: Masculino o femenino.
Edad: 18 – 40 años.
Nivel socioeconómico: A, B, C y D (transversal, dependiendo si asisten a sedes premium o cadenas low-cost).
Ocupación: Estudiantes universitarios, oficinistas y profesionales jóvenes.
Aspectos geográficos:
Nacionalidad: Peruana o extranjera.
Zona geográfica: Urbana.
Departamento: Lima Metropolitana y ciudades a nivel nacional con presencia de gimnasios comerciales.
Aspectos psicográficos:
Tienen una agenda apretada y disponen de poco tiempo libre, obligándolos a entrenar en horarios de alta afluencia (picos de mañana y noche).
Su principal dolor es el tiempo perdido; se frustran rápidamente al encontrar máquinas ocupadas, hacinamiento o equipos con carteles de "fuera de servicio".
Valoran la eficiencia de su rutina y priorizan la operatividad del local por encima de otros factores al decidir si renuevan su membresía.
