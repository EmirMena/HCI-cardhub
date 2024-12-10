# A) SELECCIÓN DE USABILIDAD NFRs

NFRs (Requerimientos no funcionales) seleccionados:

1.	Claridad de la información (RNF03): La información presentada debe ser clara, concisa y fácil de comprender, evitando la sobrecarga de datos.

2.	Interacción intuitiva (RNF04): El sistema debe ser fácil de usar, con una curva de aprendizaje mínima.
Requerimientos funcionales asociados:
•	RF20: Envío de notificaciones sobre próximas fechas de pago, mostrando nombre de la tarjeta, días restantes y monto calculado basado en el CAT.
•	RF23: Visualización gráfica de la fecha actual, fecha de corte y fecha de pago de las tarjetas registradas.
•	RF24: Visualización de un gráfico que muestra los periodos de pago y gasto.

Criterios de evaluación:
1.	RF20 (Notificaciones): Evaluar si los usuarios entienden claramente el contenido de la notificación y pueden interactuar con las acciones disponibles (pagar ahora, recordar más tarde).
2.	RF23 y RF24 (Gráficos): Evaluar si los usuarios pueden interpretar correctamente las fechas de corte y pago y entender el periodo restante para el pago.

# B) PLAN DE PRUEBAS

1. Selección y número de participantes:
•	Perfil:
o	Usuarios primarios con experiencia moderada en tecnología y finanzas personales.
o	Usuarios secundarios con menor experiencia tecnológica.
•	Número: 2 participantes.

2. Tareas ajustadas y escenarios de prueba:
•	Tarea 1 (RF20):
o	Escenario: Recibir una notificación sobre un pago pendiente y realizar una acción ("Pagar ahora" o "Recordar más tarde").
o	Objetivo: Evaluar la claridad de la información y la accesibilidad de las opciones.
•	Tarea 2 (RF23):
o	Escenario: Ver un gráfico de fechas para identificar las fechas de corte y pago.
o	Objetivo: Medir la claridad y organización visual del gráfico.
•	Tarea 3 (RF24):
o	Escenario: Consultar el gráfico que muestra los periodos de pago y gasto.
o	Objetivo: Evaluar la facilidad para interpretar los periodos indicados.

3. Tiempo estimado por tarea:
•	Tarea 1: 2-3 minutos por notificación.
•	Tarea 2 y 3: 3-5 minutos por gráfico.

# C) MÉTRICAS DE USABILIDAD

Tasa de éxito:
•	Definición: Porcentaje de participantes que completan cada tarea sin errores.
•	Niveles de usabilidad:
o	Inaceptable: Menos del 70% completa la tarea.
o	Aceptable: Entre 70% y 90% completa la tarea.
o	Excelente: Más del 90% completa la tarea.
Tiempo de finalización:
•	Definición: Tiempo promedio que los usuarios tardan en completar cada tarea.
•	Niveles de usabilidad:
o	Inaceptable: Más del 120% del tiempo esperado.
o	Aceptable: Entre 100% y 120% del tiempo esperado.
o	Excelente: Menos del 100% del tiempo esperado.
Claridad de la información:
•	Definición: Porcentaje de usuarios que comprenden claramente las etiquetas e instrucciones.
•	Niveles de usabilidad:
o	Inaceptable: Menos del 70% comprende la información.
o	Aceptable: Entre 70% y 90% comprende la información.
o	Excelente: Más del 90% comprende la información.
Satisfacción del usuario:
•	Definición: Promedio de calificaciones en una escala de Likert (1-5).
•	Niveles de usabilidad:
o	Inaceptable: Menos de 3.
o	Aceptable: Entre 3 y 4.
o	Excelente: Más de 4.


# D) PROTOCOLO DE PRUEBAS

Fase 1: Preparación

1.	Selección de participantes representativos.
2.	Configuración del entorno de pruebas (dispositivo con la app instalada).
3.	Explicación del propósito de las pruebas.
Fase 2: Ejecución
1.	RF20: Simular la recepción de notificaciones y evaluar interacciones.
2.	RF23: Mostrar gráficos de fechas para identificar claridad y organización.
3.	RF24: Presentar gráficos de periodos de pago y gasto para verificar comprensión.
Fase 3: Evaluación y retroalimentación
1.	Encuestas de satisfacción con escala de Likert.
2.	Entrevistas cortas para recolectar impresiones y sugerencias.
Fase 4: Análisis y reporte
1.	Analizar métricas de usabilidad (tasa de éxito, tiempo de finalización, etc.).
2.	Identificar problemas clave y generar recomendaciones.
3.	Elaborar un informe para el equipo de desarrollo.


