# Sistema de Gestión de Proyectos y Recursos — Neoris

**Trabajo Práctico Integrador y Progresivo (TPI)** · Organización Empresarial
Tecnicatura Universitaria en Programación (a distancia) · Universidad Tecnológica Nacional

## Descripción del sistema

Módulo interno de **Gestión de Proyectos y Recursos** para Neoris, una consultora de transformación digital y desarrollo de software. Permite asignar consultores a proyectos, registrar y aprobar las horas trabajadas y enviar las horas aprobadas al ERP para facturarlas, con trazabilidad y sin doble facturación.

Este repositorio aloja la **documentación técnica** del proyecto; todavía no contiene código.

## Integrantes

| Integrante | Comisión |
|---|---|
| Lucas Solhaune | Comisión 4, R – Rosario |

**Docente titular:** Gabriela Martínez · **Docente tutor:** Roberto Fabián Regner

## Enlaces

- Tablero de gestión (GitHub Projects): https://github.com/users/lucassolhaune/projects/3/views/1

## Contenido

| Ruta | Descripción |
|---|---|
| `docs/entregas/` | Entregas 1, 2, 3 y 4 del TPI (PDF) |
| `docs/bpmn/` | Diagrama BPMN del proceso de registro, aprobación y facturación de horas |
| `docs/diccionario-de-datos.md` | Entidades y campos del módulo |
| `docs/historias-de-usuario.md` | Las tres historias de usuario y sus criterios de aceptación |
| `docs/indicadores-de-control.md` | Indicadores de control y estándares de desempeño |
| `docs/flujo-de-trabajo.md` | Ramas, mensajes de commit y Pull Requests |

![Proceso en BPMN](docs/bpmn/proceso-facturacion-horas.png)

## Flujo de trabajo

La rama `main` contiene la versión estable. Para nuevos cambios se utilizan ramas temáticas y mensajes de commit descriptivos que indiquen qué se modificó. Los PR #1 y #2 del BPMN se crearon desde `image-BPMN` e `Image-BPMN`, respectivamente; ambas ramas se eliminaron después de integrarlos. La rama `docs/bpmn-proceso-facturacion` también existe, pero es distinta de las ramas usadas en esos PR. El detalle está en `docs/flujo-de-trabajo.md`.

## Declaración de Uso de IA

Se usó **Claude (Anthropic, Claude Sonnet 5.5)** como asistente en la elaboración de las entregas 2, 3 y 4 y de este repositorio.

### Prompts utilizados y justificación

  | Prompt (resumen) | Para qué | Revisión |
|---|---|---|
| Apoyo en la elaboración de la Entrega 1 a partir de la consigna y de información pública. | Descripción de la organización y revisión de la redacción - FODA, objetivos, metas y Gantt | Se revisó el contenido y se ajustó según la consigna. |
| Apoyo en el desarrollo de la Entrega 2, tomando como referencia el trabajo anterior. | Organigrama y diccionario de datos | Se revisaron la claridad y la coherencia de la propuesta |
| Apoyo en la organización de la Entrega 3 sobre la base del proyecto ya definido.| Estructura del área y organización de los datos. | Las propuestas se revisaron y adaptaron al trabajo. |
| Apoyo en el desarrollo y la consolidación de la Entrega 4.| Modelado del proceso e indicadores de desempeño.| Se revisó el material y se incorporaron ajustes propios.|

## Correcciones humanas sobre los resultados de la IA

A partir de los resultados iniciales proporcionados por la IA, se realizaron las siguientes revisiones y mejoras manuales:

- **Organización del README:** se reorganizó la información y se presentó en formato de tabla para facilitar su lectura.
- **Ajustes del diagrama BPMN:** se reorganizaron los elementos y flujos para representar con claridad el proceso.
- **Corrección de las historias de usuario:** se revisaron la redacción, la ortografía y el formato.
- **Mejoras de presentación:** se ajustó la estructura y el formato general para facilitar la lectura del documento.
  
### Responsabilidad

La asistencia de IA no exime de la veracidad del contenido: los errores del modelo son responsabilidad del autor. La estructura organizacional y los datos del diccionario son propuestas hipotéticas y no corresponden a información interna de Neoris.
