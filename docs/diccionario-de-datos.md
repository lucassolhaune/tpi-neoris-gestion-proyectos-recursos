# Diccionario de datos inicial

PK = clave primaria · FK = clave foránea.

## Consultor
| Campo | Tipo | Descripción |
|---|---|---|
| id_consultor | Integer | Identificador único (PK). |
| legajo | String | Número de legajo asignado por Recursos Humanos. |
| nombre_apellido | String | Nombre completo del consultor. |
| rol | String | Perfil: desarrollador, arquitecto, analista funcional o QA. |
| seniority | String | Nivel (Junior, Semi Senior, Senior); determina la tarifa. |
| costo_hora_interno | Decimal | Costo interno por hora en USD. |
| fecha_ingreso | Date | Fecha de alta. |
| activo | Boolean | Vigente (true) o dado de baja (false). |

## Proyecto
| Campo | Tipo | Descripción |
|---|---|---|
| id_proyecto | Integer | Identificador único (PK). |
| cliente | String | Cliente corporativo. |
| codigo_sow | String | Código del contrato o SOW. |
| modalidad_cobro | String | Tiempo y materiales, o precio fijo por hitos. |
| presupuesto_horas | Integer | Horas presupuestadas en el SOW. |
| fecha_inicio | Date | Inicio previsto. |
| fecha_fin | Date | Fin previsto. |
| activo | Boolean | Admite imputación de horas (true) o está cerrado (false). |

## Asignacion
| Campo | Tipo | Descripción |
|---|---|---|
| id_asignacion | Integer | Identificador único (PK). |
| id_consultor | Integer | Consultor asignado (FK a Consultor). |
| id_proyecto | Integer | Proyecto (FK a Proyecto). |
| rol_en_proyecto | String | Perfil con el que participa; debe coincidir con el SOW. |
| porcentaje_dedicacion | Integer | Porcentaje de la jornada (1 a 100); la suma por consultor no supera 100. |
| tarifa_venta | Decimal | Tarifa por hora en USD aplicada al cliente. |
| fecha_inicio_vigencia | Date | Inicio de la vigencia. |
| fecha_fin_vigencia | Date | Fin de la vigencia. |

## RegistroHoras
| Campo | Tipo | Descripción |
|---|---|---|
| id_registro | Integer | Identificador único (PK). |
| id_asignacion | Integer | Asignación sobre la que se imputan las horas (FK a Asignacion). |
| fecha | Date | Día trabajado. |
| cantidad_horas | Decimal | Horas imputadas; no superan el máximo diario. |
| es_facturable | Boolean | Facturable (true) o no (false). |
| estado | String | borrador, enviado, aprobado o facturado. |
| nro_comprobante | String | Comprobante del ERP; vacío hasta facturar. |
