# A) SELECCIÓN DE USABILIDAD NFRs

## NFRs (Requerimientos no funcionales) de usabilidad seleccionados:

1. **Eficiencia en la realización de tareas comunes (RNF02):** Los usuarios deben poder agregar tarjetas y visualizar su gasto por tarjeta de forma rápzida y sin complicaciones.
2. **Claridad de la información (RNF03):** La información presentada debe ser clara, concisa y fácil de comprender, evitando sobrecarga de información.

## Requerimientos funcionales asociados

* **Agregar tarjetas (RF04):** El usuario debe poder añadir tarjetas fácilmente, seleccionando su banco, ingresando el nombre de la tarjeta y personalizando la información como fecha de corte y fecha de pago.
* **Edición de valores asociados a la tarjeta (Pago PNGI, Saldo Actual, Saldo Posterior al pago) (RF23):** El usuario podrá editar sus gastos que se encuentren en el periodo corriente. De esta forma se visualizará el total de adeudo de sus tarjetas.


## Criterio de evaluación

* **Para el RF04 (Agregar tarjetas):** Evaluar que los usuarios pueden completar el proceso de agregar una tarjeta en un tiempo razonable, sin ayuda y sin errores. El sistema debe ser intuitivo para que cualquier usuario pueda realizar esta acción sin capacitación.
* **Para el RF23 (Edición de valores asociados a la tarjeta):** Evaluar si los usuarios pueden seleccionar la tarjeta y añadir los valores de sus gastos, asegurando que puedan hacerlo en el primer intento.

# B) Plan de Pruebas

## 1. Selección y número de participantes:
* **Perfil:** Se necesitan usuarios que representen tanto al usuario primario (como Francisco, con experiencia moderada en el uso de tecnología y finanzas) como al usuario secundario (como Leopoldo, quien tiene menos experiencia tecnológica).
* **Número de participantes:** 8 a 10 participantes. Esto incluye un balance de usuarios de diferentes niveles de experiencia con tecnología y finanzas personales para obtener una perspectiva amplia sobre la usabilidad de la aplicación.

## 2. Tareas ajustadas y escenarios de prueba:
* **Tarea 1:** Registro y configuración inicial de una tarjeta de crédito.
  * **Escenario:** El usuario descarga la aplicación, se registra y añade una tarjeta de crédito, completando todos los campos necesarios.
  * **Objetivo:** Evaluar la facilidad de uso y comprensión del proceso de registro y adición de tarjeta.
* **Tarea 2:** Editar valores asociados
  *  **Escenario:** Un usuario edita los valores de una tarjeta previamente registrada.
  *  **Objetivo:** Evaluar si el usuario puede completar esta acción sin dificultad.

## 3. Tiempo de estimación por tarea:
* **Tarea 1 (Registro y configuración):** 5-7 minutos considerando que el usuario navegue por la aplicación por primera vez.
* **Tarea 2 (Visualización de gráficos):** 3-5 minutos, incluyendo el tiempo para analizar la información y realizar consultas adicionales si lo considera necesario.


# C) Métricas de usabilidad

1. **Tasa de éxito:**
   * Definición: Porcentaje de participantes que completan la tarea sin errores.
   * Usabilidad Nivel:
     * Inaceptable: Menos del 70% completa la tarea.
     * Aceptable: Entre 70% y 90% completa la tarea.
     * Excelente: Más del 90% completa la tarea.
2. **Tiempo de finalización:**
   * Definición: Tiempo promedio que los usuarios tardan en completar cada tarea.
     * Inaceptable: Más de 120% del tiempo esperado.
     * Aceptable: Entre 100% y 120% del tiempo esperado.
     * Excelente: Menos del 100% del tiempo esperado.
3. **Claridad de la Información:**
   * Definición: Porcentaje de usuarios que comprenden claramente las instrucciones y etiquetas en la interfaz.
   * Usabilidad Nivel:
     * Unacceptable: Menos del 70% comprende la información.
     * Acceptable: Entre 70% y 90% comprende la información.
     * Excellent: Más del 90% comprende la información.
4. **Satisfacción del Usuario:**
    * Definición: Promedio de calificaciones de satisfacción obtenidas en una escala de Likert (1-5).
    * Usabilidad Nivel:
       * Unacceptable: Menos de 3.
       * Acceptable: Entre 3 y 4.
       * Excellent: Más de 4.


# D) Protocolo de Pruebas de Usabilidad

## Objetivo:
Evaluar la usabilidad de la aplicación en las funciones de agregar tarjetas de crédito y visualizar gráficos de gasto, con el fin de garantizar que los usuarios puedan navegar y utilizar la app de manera intuitiva y eficiente.

### Fase 1: Preparación
1. **Selección de participantes:** Reclutar de 2 a 3 usuarios representativos (usuarios primarios y secundarios).
2. **Configuración del entorno:** Asegurarse de que la app esté instalada y lista para las pruebas. Preparar dispositivos y herramientas para registrar el tiempo de tarea y los comentarios de los usuarios.
3. **Instrucciones iniciales:** Explicar a los participantes que el propósito es probar la aplicación, no evaluar sus habilidades, para reducir la presión.

### Fase 2: Ejecución
1. **Introducción:** Explicar brevemente las funciones principales de la aplicación sin entrar en detalles de cada tarea.
2. **Tarea 1 (Registro y configuración):** Pedir al usuario que realice el proceso de registro y añada una tarjeta de crédito. Registrar el tiempo y observar cualquier dificultad o error que ocurra.
3. **Tarea 2 (Edición de valores asociados):** Pedir al usuario que una vez la tarjeta esté registrada, seleccione la opción para poder editar sus valores asociados (Pago PNGI y Saldo Actual). Dejar que el usuario interactúe con la interfaz directamente para realizar esta tarea.
4. **Comentarios en tiempo real:** Animar a los participantes a "pensar en voz alta" para comprender sus decisiones y puntos de confusión.

### Fase 3: Evaluación y Retroalimentación
1. **Encuesta de satisfacción:** Al finalizar ambas tareas, solicitar a los usuarios que califiquen su experiencia general con cada tarea en una escala de Likert del 1 al 5.
2. **Entrevista corta:** Realizar una breve entrevista para obtener impresiones adicionales y sugerencias sobre posibles mejoras de la interfaz y el flujo de trabajo.

### Fase 4: Análisis y Reporte
1. **Análisis de datos:** Calcular las métricas de usabilidad (tasa de éxito, tiempo de finalización, tasa de errores, satisfacción y tasa de abandono) para cada tarea.
2. **Identificación de problemas clave:** Resumir los problemas comunes y áreas donde los usuarios experimentaron dificultades.
3. **Recomendaciones:** Generar recomendaciones para mejorar la interfaz de usuario y simplificar las tareas basadas en el feedback y resultados.
4. **Reporte final:** Crear un informe de usabilidad que detalle los resultados y recomendaciones, y compartirlo con el equipo de desarrollo para que consideren los ajustes necesarios en el sistema.
