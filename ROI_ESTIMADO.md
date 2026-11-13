# Estimación de tiempo y rentabilidad

María informa que recibe más de 25 consultas por día y que trabaja sola. No tiene un registro exacto del volumen ni de la duración de cada respuesta. El siguiente escenario usa supuestos para poder evaluar el proyecto; no son resultados medidos.

| Dato | Valor de trabajo | Origen |
| --- | ---: | --- |
| Consultas por día | 25 | Base conservadora respecto de lo informado por María. |
| Días de atención por mes | 22 | Supuesto. |
| Consultas mensuales | 550 | 25 × 22. |
| Respuesta manual | 3 minutos por consulta | Supuesto por medir. |
| Revisión con asistencia | 1 minuto por consulta en promedio | Objetivo por validar; incluye consultas que necesitan intervención. |
| Mantenimiento mensual | 2 horas | Supuesto. |
| Configuración inicial | 12 horas | Presupuesto estimado de esfuerzo, no registro de horas efectivas. |

Atender 550 consultas de forma manual demandaría 27,5 horas al mes. Revisar los borradores demandaría aproximadamente 9,17 horas. Al descontar 2 horas de mantenimiento, quedarían **16,33 horas mensuales disponibles para otras tareas**. El ahorro de atención antes del mantenimiento sería del 66,7 %; el ahorro neto de tiempo sería del 59,4 %.

Para evitar presentar precios de proveedores o el valor del trabajo como datos confirmados, se definen:

- `H`: valor estimado de una hora de trabajo, en una moneda elegida.
- `C`: costo mensual total de n8n, IA, embeddings y almacenamiento, en esa misma moneda.
- Beneficio mensual estimado: `16,33 × H − C`.
- Inversión inicial estimada: `12 × H`, más cualquier desembolso inicial real.
- ROI del primer año: `(12 × beneficio mensual − inversión inicial) / inversión inicial × 100`, si la inversión inicial es mayor que cero.
- Recuperación: `inversión inicial / beneficio mensual`, si el beneficio es positivo.

Ejemplo didáctico, usando unidades monetarias ficticias: si H = 10 y C = 30, el beneficio mensual sería 133,33, la inversión inicial 120 y la recuperación aproximadamente 0,90 meses. El ROI del primer año sería aproximadamente 1.233 %. Esta cifra depende de supuestos; no demuestra ingresos ni rentabilidad reales.

Con esos mismos valores ilustrativos, el equilibrio operativo se alcanza cerca de 150 consultas al mes: cada consulta ahorra 2 minutos, y deben cubrirse 2 horas de mantenimiento más el equivalente de 3 horas de herramientas. A ese volumen no sobra beneficio para recuperar la inversión inicial. Con menos consultas, mayores costos o revisiones tan largas como la respuesta manual, la automatización podría dejar de convenir.

Antes de usar estas cifras para una decisión de gasto, medir durante una semana el tiempo manual y el tiempo de revisión, registrar los costos efectivos y reemplazar los supuestos. Los créditos de prueba no se considerarán gratuidad permanente.
