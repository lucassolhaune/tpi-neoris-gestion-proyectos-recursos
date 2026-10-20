# Flujo de trabajo

## Ramas
`main` es la versión estable y no se trabaja directamente sobre ella. Cada tema va en una rama secundaria con prefijo `docs/`:

| Rama | Contenido | Integración |
|---|---|---|
| `docs/entregas-1-a-3` | Entregas 1 a 3 | Merge directo |
| `docs/diccionario-de-datos` | Diccionario de datos | Merge directo |
| `docs/historias-de-usuario` | Historias de usuario | Merge directo |
| `docs/bpmn-proceso-facturacion` | Diagrama BPMN | Pull Request con revisión de un par |
| `docs/indicadores-control` | Indicadores de control | Pull Request |

## Mensajes de commit
Formato `tipo: descripción en imperativo`, con tipo `docs`, `fix` o `chore`.
Ejemplos: `docs: agrega el diagrama BPMN del proceso de facturación de horas` · `fix: corrige el nombre del flujo de reintento al ERP`.

## Pull Requests
1. Crear la rama, hacer commits y subirla (`git push -u origin <rama>`).
2. Abrir el PR hacia `main` completando la plantilla.
3. Una persona revisa y deja comentarios en el PR.
4. Responder y ajustar en la misma rama.
5. Con la aprobación, hacer el merge.
