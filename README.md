# 1. Project Definition

## Identificación de problemática
El principal inconveniente que pueden experimentar los usuarios con múltiples tarjetas de crédito para llevar el control saludable de sus finanzas es confundir, olvidar o no tener presente las fechas de corte, plazos de pago y montos para evitar intereses de cada una de sus tarjetas.

## Propuesta de solución
Para atender la problemática se sugiere la creación de una herramienta que facilite la gestión de múltiples tarjetas de crédito en un mismo sitio, no importando el banco al que pertenezcan.

# 2. User Research
Para determinar la forma correcta de abordar la problemática e implementar una solución se necesitan datos para encontrar patrones y hacer inferencias en base a los mismos, se ha usado un método cuantitativo para recopilar datos; encuestas, las cuales fueron aplicadas a un grupo de 33 personas de entre 18 y 38 años.

## Patrones identificados en la encuesta
Los resultados de la encuesta se encuentran en [este enlace](https://docs.google.com/spreadsheets/d/1Q7wf03WGnrCDZ25al0RWkHfAu8PdhWTnkij71OSLFrk/edit?gid=396728306#gid=396728306).

1. **Distribución por edad:** Los rangos más representados en la encuesta son 18-22 años y 23-27 años, lo que indica que la gestión de tarjetas de crédito es un tema relevante principalmente para jóvenes adultos.
2. **Número de tarjetas de crédito:** Una gran proporción de los encuestados posee una tarjeta o dos o más tarjetas, lo que sugiere que la necesidad de gestionar adecuadamente esta información está presente tanto para usuarios con un nivel básico como para aquellos con múltiples responsabilidades financieras.
3. **Dificultades en la gestión:** Aunque varios usuarios califican la gestión como "fácil" o "normal", hay una proporción significativa que reporta dificultades, especialmente en los rangos de menor experiencia. Esto refleja la necesidad de una solución que simplifique procesos y facilite el seguimiento de información clave.
4. **Uso actual de herramientas:** Las herramientas mencionadas incluyen métodos manuales como lápiz y papel, herramientas semidigitales como Excel, y, en menor medida, soluciones más automatizadas. Esto sugiere que los usuarios están acostumbrados a una gestión manual o no especializada, lo que representa una oportunidad para introducir sistemas que centralicen y optimicen la gestión financiera.
5. **Interés en explorar nuevas soluciones:** Las respuestas de "Tal vez" y "Sí" en cuanto al interés por alternativas reflejan una apertura entre los usuarios para explorar opciones que les permitan mejorar su experiencia de gestión de tarjetas de crédito.

## Necesidades principales identificadas
1. **Centralización de información:** Los usuarios necesitan tener a la mano las fechas importantes y
montos clave, de manera accesible y organizada.
2. **Notificaciones y recordatorios:** Evitar olvidos de fechas de pago y generar alertas sobre montos por
pagar sería un elemento clave para reducir la carga cognitiva de los usuarios.
3. **Optimización del proceso:** Herramientas que permitan ahorrar tiempo y esfuerzo, automatizando
cálculos o categorizando información financiera, podrían ser especialmente valiosas para quienes tienen
múltiples tarjetas.
4. **Facilidad de uso:** La solución debe ser intuitiva y adaptable a diferentes niveles de experiencia
financiera, desde principiantes hasta usuarios avanzados.

## Perfiles de usuario
Con base en las necesidades identificadas y los patrones encontrados se puede realizar una lista con los perfiles de usuario que permiten representar sus características para facilitar el "approach" a la solución aplicada más adelante.

| Tipo de usuario                        | Características                                                                                                                                                     | Necesidades                                                       |
|----------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|
| **1. El gestor manual**                | - Usa lápiz y papel o métodos rudimentarios. <br> - Encuentra las tarjetas fáciles de manejar, pero pierde tiempo al organizarse.                                   | - Necesita una aplicación que automatice recordatorios y cálculos. |
| **2. El usuario digital básico**       | - Usa Excel o apps de finanzas personales. <br> - Necesita una herramienta con integración específica para tarjetas de crédito y notificaciones automáticas.         | - Requiere integración con tarjetas y notificaciones automáticas.  |
| **3. El experimentado con múltiples tarjetas** | - Tiene dos o más tarjetas y un manejo avanzado de sus finanzas. <br> - Busca optimizar tiempos y procesos, prefiriendo funciones como categorización de gastos, alertas personalizadas y reportes de uso. | - Necesita funciones avanzadas como categorización, alertas y reportes. |
| **4. El indeciso curioso**             | - Responde "Tal vez" ante la posibilidad de usar una nueva herramienta. <br> - Necesita convencerse con una interfaz intuitiva y ejemplos claros del valor agregado.    | - Requiere interfaz intuitiva y ejemplos claros del valor agregado. |
# Propuesta Específica de Solución

A partir del análisis, se observa que existe una oportunidad para introducir una herramienta que responda a las necesidades de organización, automatización y accesibilidad de los usuarios al gestionar tarjetas de crédito. Esta solución podría incluir las siguientes características clave:

1. **Gestión centralizada:** Reunir información como fechas de corte, límites de pago y montos importantes en un solo lugar.
2. **Recordatorios personalizados:** Alertas configurables que informen a los usuarios sobre fechas y montos por pagar.
3. **Interfaz intuitiva:** Un diseño fácil de usar que se adapte tanto a principiantes como a usuarios avanzados.
4. **Reportes y métricas:** Posibilidad de visualizar patrones de uso o calcular opciones como pagos mínimos o montos para no generar intereses.

## Herramientas

Se tiene por objetivo principal analizar y estructurar la información recopilada durante el proceso de investigación para garantizar que la solución propuesta cumpla con las necesidades y expectativas de los usuarios en la gestión de sus tarjetas de crédito. En particular, el enfoque está orientado al diseño de una interfaz que permita la visualización clara y organizada de datos clave relacionados con las tarjetas de crédito, cumpliendo con los siguientes objetivos específicos:

### 1. Cumplir con el Requisito Funcional RF08:

Diseñar y evaluar una interfaz que muestre los datos principales de las tarjetas del usuario (banco emisor, fecha de corte y fecha de pago) en la ventana principal del sistema. Para ello:

- Asegurar que la información esté organizada de manera clara y fácilmente identificable, alineada con los principios de usabilidad.
- Realizar pruebas de usabilidad para verificar que los usuarios puedan identificar y comprender los datos sin necesidad de explicaciones adicionales.
- Medir la tasa de éxito a través de la proporción de usuarios que logren identificar correctamente la información presentada.

#### Requisito de usabilidad

| Prueba de usabilidad                                                                 | Métrica                                                                                                        |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| El sistema debe presentar los datos principales de las tarjetas en un formato claro y organizado que permita al usuario identificar fácilmente la información de cada una de sus tarjetas. | Evaluar si los usuarios identifican y comprenden los datos mostrados en la ventana sin necesidad de explicaciones adicionales. <br> Tasa de éxito = (número de usuarios que logran identificar correctamente los datos / total de usuarios que intentaron la actividad) * 100 |

### 2. Cumplir con el Requisito Funcional RF11:

Diseñar y evaluar una sección que presente un resumen mensual de las tarjetas, incluyendo gastos totale y el total pagado por mes. Para ello:

- Asegurar que la visualización sea clara, detallada y fácil de interpretar para el usuario.
- Validar mediante pruebas de usabilidad que los usuarios comprendan la información presentada en el resumen mensual y puedan identificar cada elemento relevante.
- Medir la tasa de éxito con base en el número de usuarios que logren comprender correctamente el resumen mensual.

#### Requisito de usabilidad

| Prueba de usabilidad                                                                 | Métrica                                                                                                        |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| El sistema debe ofrecer una visualización clara y detallada del resumen mensual de las tarjetas, asegurando que la información sea fácil de interpretar para el usuario. | Verificar si los usuarios comprenden la información del resumen mensual y si pueden identificar cada elemento (gastos y pagos) para cada tarjeta. <br> Tasa de éxito = (número de usuarios que logran identificar correctamente los datos / total de usuarios que intentaron la actividad) * 100 |
# 3. User Modeling

En el proceso de diseño de la herramienta de gestión de tarjetas de crédito, es fundamental tener en cuenta las características y necesidades de los usuarios. Cada persona interactúa con el sistema de manera distinta, dependiendo de su nivel de experiencia con herramientas digitales y su comportamiento financiero. Por ello, crear perfiles de usuario bien definidos es esencial para asegurar que la interfaz cumpla con las expectativas de todos los usuarios, sin importar su perfil o contexto.

A través de los perfiles de usuario, se puede comprender mejor los distintos comportamientos, expectativas y limitaciones que los usuarios pueden tener al interactuar con el sistema. Esto permite diseñar una interfaz que no solo sea funcional, sino también fácil de usar y adaptada a las necesidades reales de las personas.

## Perfiles de Usuario

Cada uno de los perfiles a continuación representa un tipo de usuario que probablemente utilizará la herramienta. Estos perfiles ayudan a guiar el diseño y desarrollo de características que satisfagan sus necesidades específicas.

### **1. El Gestor Manual**
- **Nombre:** Laura, 25 años  
- **Ocupación:** Estudiante de posgrado  
- **Tecnología utilizada:** Lápiz y papel, hojas de cálculo de Excel  
- **Comportamiento:** Laura prefiere métodos tradicionales para gestionar sus tarjetas de crédito. Utiliza lápiz y papel o Excel, pero se siente abrumada por la cantidad de tarjetas que tiene y por las fechas de pago que debe controlar manualmente.
- **Necesidades:**  
  - Se necesita un sistema sencillo que le permita centralizar toda la información sobre sus tarjetas en un solo lugar.
  - Se requieren alertas automáticas para las fechas de corte y los pagos pendientes.
  - Se busca una herramienta fácil de usar que no demande mucha configuración.
- **Escenario de uso:**  
  Laura quiere asegurarse de que sus pagos sean puntuales. Al usar la aplicación, puede ver de un vistazo las fechas de corte y los montos a pagar, y recibir notificaciones que le avisan cuando se acerca la fecha de pago.

### **2. El Usuario Digital Básico**
- **Nombre:** José, 30 años  
- **Ocupación:** Ingeniero  
- **Tecnología utilizada:** Excel, aplicaciones de finanzas personales  
- **Comportamiento:** José es un usuario intermedio, se siente cómodo utilizando herramientas digitales pero no tiene mucha experiencia en aplicaciones especializadas para la gestión de sus finanzas. Usa Excel o algunas apps de finanzas, pero busca algo más automatizado.
- **Necesidades:**  
  - Se requiere una herramienta que se integre con sus tarjetas de crédito y le envíe notificaciones automáticas sobre pagos y fechas de corte.
  - Se necesita una forma sencilla de ver sus gastos mensuales y de tomar decisiones financieras sin tener que hacer cálculos manuales.
- **Escenario de uso:**  
  José entra en la aplicación para ver los resúmenes de sus tarjetas, donde la herramienta muestra un gráfico de su gasto mensual. La app le alerta de los pagos próximos y le permite ver rápidamente cómo está distribuyendo su dinero entre las tarjetas.

### **3. El Indeciso Curioso**
- **Nombre:** Pedro, 28 años  
- **Ocupación:** Diseñador gráfico  
- **Tecnología utilizada:** Apps de gestión financiera simples  
- **Comportamiento:** Pedro no está seguro de si necesita una herramienta especializada para gestionar sus tarjetas. Está abierto a la idea, pero aún no está convencido de los beneficios que puede obtener.
- **Necesidades:**  
  - Se necesita una interfaz simple, clara e intuitiva.
  - Se requiere ver ejemplos prácticos de cómo la herramienta puede mejorar la gestión de sus finanzas antes de comprometerse completamente.
- **Escenario de uso:**  
  Pedro instala la aplicación y, después de explorar la interfaz, descubre cómo puede visualizar sus pagos pendientes y recibir notificaciones. Le gusta lo fácil que es de usar y decide comenzar a registrar sus tarjetas para ver cómo la app mejora su gestión financiera.

## Escenarios de Uso

Los escenarios de uso permiten visualizar cómo los diferentes tipos de usuarios interactuarían con el sistema en situaciones cotidianas. Estos escenarios no solo ayudan a mejorar la funcionalidad del sistema, sino que también permiten verificar si el diseño responde a las expectativas de los usuarios de manera efectiva.

### **Escenario 1: Gestión de Pagos Pendientes**
- **Usuario:** Laura (Gestora Manual)  
- **Contexto:** Laura tiene varias tarjetas, pero le cuesta recordar las fechas de corte y los pagos pendientes.  
- **Interacción:** Laura abre la aplicación y, al instante, puede ver un resumen con las fechas de corte y los montos a pagar para cada tarjeta. La aplicación le envía una alerta cuando una fecha de corte está próxima, lo que le permite planificar su pago a tiempo.  
- **Objetivo:** Organizar sus pagos de manera eficiente.  
- **Resultado esperado:** Laura paga sus tarjetas a tiempo, evitando cargos por intereses y manteniendo sus finanzas al día.

### **Escenario 2: Visualización de Gastos y Resúmenes Mensuales**
- **Usuario:** José (Usuario Digital Básico)  
- **Contexto:** José utiliza varias tarjetas y necesita ver su gasto mensual de forma clara.  
- **Interacción:** Al ingresar a la aplicación, José ve un resumen mensual que incluye los gastos por tarjeta e intereses generados . El sistema le muestra un gráfico fácil de entender que le ayuda a ver dónde está gastando más.  
- **Objetivo:** Tener un control visual sobre su gasto y sus fechas de corte.  
- **Resultado esperado:** José puede tomar decisiones informadas sobre sus finanzas y paga sus tarjetas de forma eficiente.

## Workflow de la Aplicación

A continuación, se presenta una tabla con el flujo de trabajo deseado para la aplicación, que describe los pasos que los usuarios seguirían para gestionar sus tarjetas de crédito de forma eficiente.

| **Paso** | **Acción del Usuario**                             | **Acción del Sistema**                                    | **Resultado Esperado**                                                   |
|----------|----------------------------------------------------|-----------------------------------------------------------|---------------------------------------------------------------------------|
| 1        | El usuario inicia sesión en la aplicación          | La aplicación valida las credenciales y carga el perfil    | El usuario accede a la interfaz principal con un resumen de sus tarjetas  |
| 2        | El usuario ingresa los detalles de sus tarjetas    | La aplicación muestra las tarjetas registradas con sus fechas de corte, límites y pagos pendientes | El usuario visualiza la información de todas sus tarjetas de forma clara |
| 3        | El usuario establece notificaciones de pago       | La aplicación configura alertas personalizadas para cada tarjeta | El usuario recibe notificaciones en las fechas configuradas               |
| 4        | El usuario revisa su resumen mensual              | La aplicación genera un resumen con los gastos, intereses y pagos realizados | El usuario puede ver un desglose detallado de su gasto y pagos           |
| 5        | El usuario consulta los reportes de gasto         | La aplicación ofrece reportes detallados con categorización de gastos y alertas | El usuario obtiene insights sobre su comportamiento financiero           |
---

A través de estos perfiles y escenarios, se puede comprender mejor cómo cada tipo de usuario interactúa con el sistema. Esto es esencial para diseñar una interfaz que no solo sea funcional, sino también accesible y útil para todos los usuarios, asegurando que cada uno pueda alcanzar sus objetivos financieros con facilidad y eficiencia.

# 4. Prototipo
se muestra un gráfico circular de los gastos y el tipo de los mismos en el apartado de "Detalles de tarjeta", según el principio de visibilidad del estado del sistema de Nielsen, los usuarios necesitan comprender rápidamente en qué gastan para permitirles una mejor gestión. Además, los colores utilizados durante todos los apartados no fueron escogidos de manera aleatoria sino que cumplen una función, lograr que el contraste cumpla con WCAG de mínimo 4.5:1 que es lo necesario para que una persona con o sin daltonismo pueda percibirlo de forma correcta, tratando siempre que la aplicación sea accesible para usuarios que presenten esta condición, para lograr el contraste indicado se utilizo la herramienta online [Contrast Checker](https://webaim.org/resources/contrastchecker/) de WebAIM
