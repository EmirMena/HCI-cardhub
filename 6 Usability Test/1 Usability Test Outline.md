# A) SELECCIÓN DE USABILIDAD NFRs

## NFRs (Requerimientos no funcionales) de usabilidad seleccionados:

1. **Eficiencia en la realización de tareas comunes (RNF02):** Los usuarios deben poder agregar tarjetas y visualizar su gasto por tarjeta de forma rápzida y sin complicaciones.
2. **Claridad de la información (RNF03):** La información presentada debe ser clara, concisa y fácil de comprender, evitando sobrecarga de información.

## Requerimientos funcionales asociados

* **Agregar tarjetas (RF04):** El usuario debe poder añadir tarjetas fácilmente, seleccionando su banco, ingresando el nombre de la tarjeta y personalizando la información como fecha de corte y fecha de pago.
* **Visualización de gráficos de gasto por tarjeta (RF23):** El usuario podrá ver gráficos con información relevante sobre su gasto y periodo de pago, lo cual facilita el análisis de su situación financiera.

## Criterio de evaluación

* **Para el RF04 (Agregar tarjetas):** Evaluar que los usuarios pueden completar el proceso de agregar una tarjeta en un tiempo razonable, sin ayuda y sin errores. El sistema debe ser intuitivo para que cualquier usuario pueda realizar esta acción sin capacitación.
* **Para el RF23 (Visualización de gráficos):** Evaluar si los usuarios pueden interpretar y extraer conclusiones del gráfico de gasto por tarjeta, asegurando que la información sea clara y comprensible.


# B) Plan de Pruebas

## 1. Selección y número de participantes:
* **Perfil:** Se necesitan usuarios que representen tanto al usuario primario (como Francisco, con experiencia moderada en el uso de tecnología y finanzas) como al usuario secundario (como Leopoldo, quien tiene menos experiencia tecnológica).
* **Número de participantes:** 8 a 10 participantes. Esto incluye un balance de usuarios de diferentes niveles de experiencia con tecnología y finanzas personales para obtener una perspectiva amplia sobre la usabilidad de la aplicación.

## 2. Tareas ajustadas y escenarios de prueba:
* **Tarea 1:** Registro y configuración inicial de una tarjeta de crédito.
  * **Escenario:** El usuario descarga la aplicación, se registra y añade una tarjeta de crédito, completando todos los campos necesarios.
  * **Objetivo:** Evaluar la facilidad de uso y comprensión del proceso de registro y adición de tarjeta.
* **Tarea 2:** Visualización del gráfico de gasto por tarjeta.
  *  **Escenario:** El usuario quiere revisar su gasto total y el periodo de pago a través de un gráfico para planificar sus finanzas.
  *  **Objetivo:** Evaluar si el usuario entiende la información presentada en el gráfico y puede extraer conclusiones claras de su gasto y periodos.

## 3. Tiempo de estimación por tarea:
* **Tarea 1 (Registro y configuración):** 5-7 minutos, considerando que el usuario navegue por la aplicación por primera vez.
* **Tarea 2 (Visualización de gráficos):** 3-5 minutos, incluyendo el tiempo para analizar la información y realizar consultas adicionales si lo considera necesario.


# C) Métricas de usabilidad

1. **Tasa de éxito:** Porcentaje de usuarios que completan cada tarea correctamente sin ayuda ni errores.
2. **Tiempo de finalización:** Tiempo promedio que los usuarios tardan en completar cada tarea.
3. **Tasa de errores:** Número de errores cometidos por los usuarios durante cada tarea (por ejemplo, seleccionar un campo incorrecto o dificultad en la navegación).
4. **Satisfacción del usuario**: Calificación promedio de satisfacción general sobre la facilidad de uso de la aplicación (medida mediante una escala de Likert del 1 al 5).
5. **Tasa de abandono:** Porcentaje de usuarios que abandonan la tarea o se frustran al no poder completarla.


# D) Protocolo de Pruebas de Usabilidad

## Objetivo:
Evaluar la usabilidad de la aplicación en las funciones de agregar tarjetas de crédito y visualizar gráficos de gasto, con el fin de garantizar que los usuarios puedan navegar y utilizar la app de manera intuitiva y eficiente.

### Fase 1: Preparación
1. **Selección de participantes:** Reclutar de 8 a 10 usuarios representativos (usuarios primarios y secundarios).
2. **Configuración del entorno:** Asegurarse de que la app esté instalada y lista para las pruebas. Preparar dispositivos y herramientas para registrar el tiempo de tarea y los comentarios de los usuarios.
3. **Instrucciones iniciales:** Explicar a los participantes que el propósito es probar la aplicación, no evaluar sus habilidades, para reducir la presión.

### Fase 2: Ejecución
1. **Introducción:** Explicar brevemente las funciones principales de la aplicación sin entrar en detalles de cada tarea.
2. **Tarea 1 (Registro y configuración):** Pedir al usuario que realice el proceso de registro y añada una tarjeta de crédito. Registrar el tiempo y observar cualquier dificultad o error que ocurra.
3. **Tarea 2 (Visualización de gráficos):** Pedir al usuario que acceda a la sección de gráficos de gasto por tarjeta y consulte la información presentada. Observar su comprensión y registrar el tiempo necesario.
4. **Comentarios en tiempo real:** Animar a los participantes a "pensar en voz alta" para comprender sus decisiones y puntos de confusión.

### Fase 3: Evaluación y Retroalimentación
1. **Encuesta de satisfacción:** Al finalizar ambas tareas, solicitar a los usuarios que califiquen su experiencia general con cada tarea en una escala de Likert del 1 al 5.
2. **Entrevista corta:** Realizar una breve entrevista para obtener impresiones adicionales y sugerencias sobre posibles mejoras de la interfaz y el flujo de trabajo.

### Fase 4: Análisis y Reporte
1. **Análisis de datos:** Calcular las métricas de usabilidad (tasa de éxito, tiempo de finalización, tasa de errores, satisfacción y tasa de abandono) para cada tarea.
2. **Identificación de problemas clave:** Resumir los problemas comunes y áreas donde los usuarios experimentaron dificultades.
3. **Recomendaciones:** Generar recomendaciones para mejorar la interfaz de usuario y simplificar las tareas basadas en el feedback y resultados.
4. **Reporte final:** Crear un informe de usabilidad que detalle los resultados y recomendaciones, y compartirlo con el equipo de desarrollo para que consideren los ajustes necesarios en el sistema.
