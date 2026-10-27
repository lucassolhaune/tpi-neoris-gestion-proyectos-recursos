# Flujo de trabajo

## Ramas

`main` es la versión estable. Los cambios se desarrollan en ramas secundarias. En el historial del BPMN se usaron tanto ramas con prefijo `docs/` como otras con nombres distintos.

| Rama | Contenido | Estado o integración |
|---|---|---|
| `docs/entregas-1-a-3` | Entregas 1 a 3 | Integrada en `main` |
| `docs/diccionario-de-datos` | Diccionario de datos | Integrada en `main` |
| `docs/historias-de-usuario` | Historias de usuario | Integrada en `main` |
| `docs/bpmn-proceso-facturacion` | Diagrama BPMN | Rama existente; no fue la rama fuente de los PR #1 y #2 |
| `image-BPMN` | Primera incorporación del BPMN | Rama fuente del PR #1; eliminada después del merge |
| `Image-BPMN` | Imagen del BPMN | Rama fuente del PR #2; eliminada después del merge |
| `docs/indicadores-control` | Indicadores y Entrega 4 | Rama existente; no encontré un PR asociado |

Los PR #1 y #2 se integraron en `main`. Las ramas `image-BPMN` e `Image-BPMN` se eliminaron después. Por eso sus nombres se conservan aquí como historial.

## Mensajes de commit

Usá el formato `tipo: descripción concreta`, con tipos como `docs`, `fix` o `chore`. El mensaje debe decir qué cambió y para qué.

Ejemplo: `docs: agrega el diagrama BPMN del proceso de facturación de horas`.

## Pull Requests

1. Crear una rama para el cambio y subirla (`git push -u origin <rama>`).
2. Abrir un PR hacia `main` con un título descriptivo y una descripción del cambio.
3. Solicitar una revisión y responder los comentarios recibidos.
4. Integrar el PR en `main` una vez completada la revisión.
