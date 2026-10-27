<img width="1914" height="795" alt="imagen" src="https://github.com/user-attachments/assets/9706abc1-900f-484c-8fdb-bd9c91652f59" /># Historias de usuario

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

## Trazabilidad en GitHub

| Historia | Issue | Estado en el tablero | Pull Request asociado |
|---|---|---|---|
| HU-01 | [#3: Cargar horas diarias por proyecto](https://github.com/lucassolhaune/tpi-neoris-gestion-proyectos-recursos/issues/3) | Por Hacer | Sin PR específico |
| HU-02 | [#4: Aprobar o devolver las horas del equipo](https://github.com/lucassolhaune/tpi-neoris-gestion-proyectos-recursos/issues/4) | Por Hacer | Sin PR específico |
| HU-03 | [#5: Enviar al ERP las horas aprobadas sin duplicados](https://github.com/lucassolhaune/tpi-neoris-gestion-proyectos-recursos/issues/5) | Por Hacer | Sin PR específico |

Los PR [#1](https://github.com/lucassolhaune/tpi-neoris-gestion-proyectos-recursos/pull/1) y [#2](https://github.com/lucassolhaune/tpi-neoris-gestion-proyectos-recursos/pull/2) corresponden al BPMN, no a estas historias.

## Evidencia del tablero

La captura muestra las tres historias en la columna **Por Hacer** del tablero de GitHub Projects.

<img width="1914" height="795" alt="download" src="https://github.com/user-attachments/assets/e97f5b5a-bc67-4b46-bb3f-7761b2056df2" />
