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
| 4        | El usuario revisa su resumen mensual              | La aplicación genera un resumen con los gastos, intereses y pagos realizados | El usuario puede ver un desglose detallado de sus gastos           |
| 5        | El usuario consulta los reportes de gasto         | La aplicación ofrece reportes detallados con categorización de gastos y alertas |          |
---

A través de estos perfiles y escenarios, se puede comprender mejor cómo cada tipo de usuario interactúa con el sistema. Esto es esencial para diseñar una interfaz que no solo sea funcional, sino también accesible y útil para todos los usuarios, asegurando que cada uno pueda alcanzar sus objetivos financieros con facilidad y eficiencia.

# 4. Prototipo #
Se ha desarrollado un prototipo no funcional para poder apreciar la distribución y funciones de la interfaz gráfica en relación con los requisitos de usabilidad previamente declarados, buscando como objetivo el atender las principales necesidades de los usuarios y cumplir con el workflow de la aplicación.
Se muestra un gráfico circular de los gastos y el tipo de los mismos en el apartado de "Detalles de tarjeta", según el principio de visibilidad del estado del sistema de Nielsen, los usuarios necesitan comprender rápidamente en qué gastan para permitirles una mejor gestión. Además, los colores utilizados durante todos los apartados no fueron escogidos de manera aleatoria sino que cumplen una función, lograr que el contraste cumpla con el estipulado en el [estándar WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/es) de mínimo 4.5:1 que es lo necesario para que una persona con o sin daltonismo pueda percibirlo de forma correcta, tratando siempre que la aplicación sea accesible para usuarios que presenten esta condición, para lograr el contraste indicado se utilizo la herramienta online [Contrast Checker](https://webaim.org/resources/contrastchecker/) de WebAIM.

### El usuario debe ingresar sus datos para acceder a la aplicación ###
 ![image](https://github.com/user-attachments/assets/a4bf25c5-0668-4b0a-80b9-e533d4c214cc)
### Una vez dentro la primer pantalla será la de "Tarjetas" que contiene todas las tarjetas ingresadas además de la opción para ingresar alguna adicional ###
 ![image](https://github.com/user-attachments/assets/ef0cb576-6568-4554-8a9a-04c05f6dfa13) ![image](https://github.com/user-attachments/assets/3d77423e-f7de-43a7-99ee-80edcdac1940)
### Al dar click sobre una de las tarjetas previamente ingresadas se accede al apartado "Detalles de tarjeta" donde puede ver y modificar las fechas de corte y pago, además de poder ingresar manualmente los gastos asociados con la tarjeta ###
![image](https://github.com/user-attachments/assets/d4ef1d1f-6bdb-4734-9e78-33eb302cb31e)
### Si el usuario lo desea puede activar y configurar alertas de la aplicación para recordarle sus fechas de pago y corte de cada tarjeta ###
![image](https://github.com/user-attachments/assets/b7e0001e-62df-49aa-b935-9da62210c124) ![image](https://github.com/user-attachments/assets/c2225d62-eb6d-4098-920b-f9d964f42962)
### Por último, haciendo uso del menú desplegable en la parte superior izquierda de la pantalla se muestra los apartados de la aplicación (por motivos de la entrega solo se muestran dos) y se accede a "Resumen mensual" el cual es una forma global de ver el estado de las diferentes tarjetas y los gastos totales ### 
![image](https://github.com/user-attachments/assets/08ee2741-bd94-439a-b15e-ce1254a98ef1) ![image](https://github.com/user-attachments/assets/158e6edf-f104-4cec-b232-24c03866c2be)

# 5. Usability Test
## Objetivo del Test
Evaluar la usabilidad de la herramienta para la gestión de tarjetas de crédito con el propósito de verificar que los usuarios puedan cumplir tareas específicas de manera eficiente, efectiva y satisfactoria.  

## Plan de Pruebas
El test de usabilidad estará dividido en las siguientes fases:  

1. **Definición de Objetivos**  
   - Verificar que los usuarios puedan identificar información clave de sus tarjetas (fechas de corte, pagos pendientes, etc.).  
   - Evaluar si los usuarios comprenden los resúmenes mensuales y reportes financieros presentados por la aplicación.  
   - Medir la satisfacción del usuario al interactuar con la interfaz gráfica.  

2. **Participantes**  
   Se seleccionarán 6 participantes que representen los perfiles de usuario identificados en la investigación:  
   - **2 gestores manuales.**  
   - **2 usuarios digitales básicos.**  
   - **1 experimentado con múltiples tarjetas.**  
   - **1 indeciso curioso.**  

3. **Tareas a Evaluar**  
   Las tareas evaluadas serán las siguientes:  
   - **Tarea 1:** Configurar una notificación para recordar una fecha de pago.  
   - **Tarea 2:** Consultar la fecha de corte y monto pendiente de una tarjeta específica.  
   - **Tarea 3:** Visualizar un resumen mensual y entender los detalles de los gastos.  


4. **Entorno de Pruebas**  
   Las pruebas se realizarán en un entorno controlado utilizando el prototipo funcional de la aplicación, en dispositivos móviles con sistema operativo Android y iOS.  

5. **Métricas de Evaluación**  
   - **Tasa de éxito:** Porcentaje de tareas completadas correctamente por los participantes.  
   - **Tiempo de ejecución:** Tiempo promedio necesario para completar cada tarea.  
   - **Errores:** Número de errores cometidos durante la interacción.  
   - **Satisfacción del usuario:** Medida a través de una encuesta posterior al test (escala de Likert de 1 a 5).  

## Protocolo del Test

1. **Introducción**  
   - Explicar a los participantes el objetivo del test.  
   - Asegurar que no están siendo evaluados, sino la aplicación.  

2. **Realización de Tareas**  
   - Los participantes realizarán las tareas descritas sin ayuda externa.  
   - Se permitirá pensar en voz alta para entender mejor su proceso de pensamiento.  

3. **Recopilación de Datos**  
   - Registrar métricas clave durante la interacción.  
   - Tomar notas sobre dificultades o comentarios espontáneos de los participantes.  

4. **Encuesta Post-Test**  
   - Preguntar a los usuarios sobre su nivel de satisfacción y percepción general de la interfaz.  

## Resultados Esperados
- Los usuarios deben ser capaces de completar las tareas clave con una tasa de éxito del 80% o más.  
- El tiempo de ejecución promedio para cada tarea debe ser inferior a 2 minutos.  
- La satisfacción del usuario debe obtener una puntuación promedio de 4 o más en la escala de Likert.  

## Iteración  
Con base en los resultados, se realizarán ajustes en la interfaz para mejorar la experiencia del usuario y cumplir con los objetivos de usabilidad identificados. Se planeará un segundo ciclo de pruebas para verificar la efectividad de las mejoras implementadas.  


