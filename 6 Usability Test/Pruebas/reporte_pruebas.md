Requisitos funcionales evaluados:
RF20: Notificación sobre fechas de pago

El sistema detecta 7 días naturales restantes antes de la próxima fecha de pago de una tarjeta y envía una notificación al dispositivo del usuario con el nombre de la tarjeta, los días restantes y el monto a pagar, calculado con el Costo Anual Total (CAT).
RF23: Visualización gráfica de fechas de corte y pago

El sistema permite visualizar gráficamente la fecha actual, junto con la fecha de corte y la fecha de pago de cada tarjeta registrada, para que el usuario vea fácilmente cuántos días le quedan para pagar.
RF24: Visualización de los períodos de pago y gasto

El sistema muestra una gráfica que indica los períodos de pago y gasto de cada tarjeta, lo que facilita la gestión de pagos y gastos del usuario.
Análisis de Datos de las Pruebas
Tarea 1: Notificación sobre fechas de pago (RF20)
Tasa de éxito promedio: 100%
Tiempo promedio de finalización: 6 minutos
Tasa de errores promedio: 0 errores
Satisfacción promedio: 4.33/5
Tasa de abandono: 0%

Puntos fuertes:
La notificación se presentó correctamente en todos los casos y fue entendida de manera clara por los usuarios.
La información sobre los días restantes y el monto a pagar fue claramente legible, y el botón de acción ("Pagar ahora" o "Recordar más tarde") fue fácil de identificar.
Problemas identificados:
No se reportaron problemas significativos relacionados con las notificaciones. La funcionalidad está bien implementada, pero algunos usuarios mencionaron que podría ser útil incluir más detalles sobre el pago total al final del período.
Tarea 2: Visualización gráfica de fechas de corte y pago (RF23)
Tasa de éxito promedio: 90%
Tiempo promedio de finalización: 7 minutos
Tasa de errores promedio: 0.5 errores
Satisfacción promedio: 3.67/5
Tasa de abandono: 0%

Puntos fuertes:
La visualización de la fecha actual, junto con las fechas de corte y pago, fue entendida sin dificultad por la mayoría de los usuarios.
Los usuarios pudieron ver claramente cuántos días faltaban para pagar cada tarjeta.
Problemas identificados:
Aunque la visualización fue funcional, algunos usuarios mencionaron que la gráfica podría mejorarse. Algunos sugirieron que el diseño podría ser más intuitivo y que las escalas de tiempo no siempre eran claras, especialmente en los días cercanos a la fecha de pago.
Se recomendó hacer más evidente la actualización en tiempo real de las fechas.
Tarea 3: Visualización de los períodos de pago y gasto (RF24)
Tasa de éxito promedio: 95%
Tiempo promedio de finalización: 5 minutos
Tasa de errores promedio: 0.2 errores
Satisfacción promedio: 4.0/5
Tasa de abandono: 0%

Puntos fuertes:

La gráfica de los períodos de pago y gasto fue comprendida rápidamente por los usuarios. La mayoría de ellos indicó que esta funcionalidad les ayudó a organizar mejor sus pagos y gastos.
La interfaz fue clara en la presentación de los dos períodos (pago y gasto).
Problemas identificados:

Algunos usuarios sugirieron que la gráfica podría beneficiarse de una mayor distinción visual entre los períodos de pago y gasto, usando colores o patrones diferenciados.
También se señaló la falta de una leyenda explicativa, lo que podría ayudar a clarificar aún más los elementos visuales de la gráfica.
Identificación de Problemas Clave
RF20: Notificación sobre fechas de pago

Puntos fuertes:
Las notificaciones funcionaron correctamente y los usuarios recibieron la información de forma clara.
Problemas identificados:
Aunque no hubo errores significativos, algunos usuarios indicaron que les gustaría que la notificación incluya más detalles sobre el monto total a pagar.
RF23: Visualización gráfica de fechas de corte y pago

Puntos fuertes:
La funcionalidad de mostrar las fechas de corte y pago fue clara y útil para los usuarios.
Problemas identificados:
La escala de tiempo en la gráfica no siempre era evidente, especialmente cuando las fechas de corte o pago se acercaban.
Se sugirió mejorar la actualización en tiempo real de las fechas.
RF24: Visualización de los períodos de pago y gasto

Puntos fuertes:
La gráfica de los períodos de pago y gasto fue bien recibida y comprendida por la mayoría de los usuarios.
Problemas identificados:
La gráfica podría beneficiarse de un diseño visual más intuitivo, con mayor diferenciación de colores y una leyenda explicativa.
Manejo de tarjetas registradas:

Puntos fuertes:
Los usuarios pudieron interactuar con las tarjetas registradas sin dificultades importantes.
Problemas identificados:
Hubo algunas sugerencias para que la interfaz sea un poco más intuitiva en cuanto a la gestión de las tarjetas registradas, como mejorar la visibilidad de las opciones y facilitar la navegación.
Recomendaciones
Mejorar la retroalimentación visual de las gráficas (RF23, RF24):

Utilizar colores o patrones diferenciados para los períodos de pago y gasto, e incluir una leyenda explicativa para que los usuarios comprendan rápidamente los elementos de la gráfica.
Asegurarse de que las fechas en las gráficas se actualicen en tiempo real y de que la escala de tiempo sea más clara, especialmente cerca de las fechas de pago.
Mejorar la notificación (RF20):

Incluir más detalles sobre el monto total a pagar al final del período, no solo el monto calculado con el Costo Anual Total (CAT), para ofrecer un resumen más completo del pago pendiente.
Mejorar la intuitividad en el manejo de tarjetas (RF23, RF24):

Hacer más visibles las opciones para gestionar las tarjetas registradas y mejorar la navegación entre las diferentes funcionalidades para que el manejo sea aún más intuitivo.