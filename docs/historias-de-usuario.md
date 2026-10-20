# Historias de usuario

**HU-01.** Como consultor, quiero cargar mis horas diarias sobre los proyectos en los que tengo una asignación vigente, para que mi trabajo quede registrado y pueda facturarse correctamente.
- Solo permite imputar a proyectos con asignación vigente.
- Rechaza jornadas que superan el máximo diario.
- Guarda el registro en estado borrador o enviado.

**HU-02.** Como líder de proyecto, quiero aprobar o devolver con observaciones las horas cargadas por mi equipo, para que solo se facturen horas validadas.
- Muestra las horas enviadas por consultor y proyecto.
- Permite aprobar o devolver con un comentario.
- Las horas devueltas vuelven al consultor para corregirlas.

**HU-03.** Como analista de Finanzas, quiero que las horas aprobadas se envíen al ERP al cierre del período, para emitir la factura sin carga manual y sin duplicados.
- Solo se envían horas en estado aprobado.
- Cada envío tiene un identificador único y queda en un log.
- El módulo registra el comprobante y bloquea las horas facturadas.
