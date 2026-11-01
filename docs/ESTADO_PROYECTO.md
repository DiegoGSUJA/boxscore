# Boxscore — Estado del proyecto

| Control | Valor |
|---|---|
| Fecha | 01/11/2026 |
| Revisión | Consolidación documental de contexto, estado y requisitos |
| Responsable | Diego Gómez Sánchez — responsable del proyecto y desarrollador |

Leer junto con `PROYECTO_CONTEXTO.md` y `REQUISITOS.md`. Se distinguen hechos comprobados, criterios provisionales, propuestas y pendientes.

## 1. Resumen actual

- Fase: planificación y especificación inicial.
- El repositorio contiene documentación; no contiene todavía la aplicación implementada.
- Se incorpora `REQUISITOS.md` como borrador de un primer incremento de listado diario y detalle de partidos finalizados.
- La incorporación documental no aprueba requisitos, proveedores, bibliotecas, alojamiento ni implementación.
- Siguiente actividad propuesta: revisar la coherencia del alcance y aprobar explícitamente los requisitos del primer incremento antes de pasar a bocetos y diseño.

## 2. Resultado de esta actualización

El contenido de este apartado describe los archivos incluidos en el mismo commit, no operaciones locales del responsable ni cambios en el Project.

| Archivo | Resultado documental |
|---|---|
| `README.md` | Corrige la presentación como proyecto académico con cuentas y enlaza la documentación. |
| `docs/REQUISITOS.md` | Incorpora requisitos propuestos, recorrido de consulta, Mermaid, condiciones de aceptación y pendientes. |
| `docs/PROYECTO_CONTEXTO.md` | Consolida criterios y preferencias de redacción; conserva una referencia recuperable a la versión anterior. |
| `docs/ESTADO_PROYECTO.md` | Registra el avance documental sin afirmar implementación ni pruebas no revisadas. |

La solicitud de actualización directa consta en la conversación del 01/11/2026. La evidencia de publicación será el commit que contiene estos archivos. No se afirma que se haya realizado el pull en el equipo local.

## 3. Criterios registrados

Conservan su carácter provisional cuando no existe aprobación específica para implementar:

- Portal NBA, no juego ni fantasy, desarrollado de manera unipersonal con finalidad formativa.
- Presupuesto de 0 euros y prioridad local. Demo privada opcional y condicionada.
- Stack provisional: Java y Spring Boot, PostgreSQL y React con TypeScript.
- Docker Compose y GitHub Actions como aprendizaje prioritario; Kubernetes después del MVP.
- Fuentes, bibliotecas de acceso, proveedores, alojamiento y versiones concretas pendientes.
- Datos reales como prioridad de evaluación; datos ficticios como apoyo o alternativa explícita, identificados.
- Validación con participantes reales y límites de la evidencia documentados.
- Markdown y Mermaid en GitHub; copias del Project como respaldo sin sincronización automática.

Criterio editorial confirmado en la sesión: lenguaje técnico e impersonal, sin narración del chat ni equipos ficticios. Se solicitan entregables completos y revisados.

## 4. Evidencia disponible y límites

### 4.1 Comprobado en esta revisión

Antes de la escritura se consultaron el README, el contexto, el estado y el inventario de la rama `main`. La referencia previa es `6855fdd3e6e4b5489fa3005a8ed61c6fa5653307`.

El inventario previo contenía `README.md`, `docs/PROYECTO_CONTEXTO.md` y `docs/ESTADO_PROYECTO.md`. El primer borrador de requisitos no estaba incorporado.

### 4.2 Antecedentes conservados

La versión previa del estado registra la creación y clonación del repositorio, documentación inicial, revisiones U1–U4 e investigaciones de fuentes. Su contenido completo y referencias se conservan en el commit anterior, ruta `docs/ESTADO_PROYECTO.md`. SHA del archivo anterior: `fd7c76e1d462952998852178c8a7db90d8c25333`.

No se revalidan aquí las evidencias externas del Project ni los archivos de pruebas ausentes. La sustitución previa de copias del Project consta en el histórico, pero no demuestra su sincronización actual.

### 4.3 No acreditado en esta revisión

- Implementación de backend, frontend, persistencia, Docker o CI/CD.
- Resultados de pruebas locales o de aceptación.
- Versiones de herramientas utilizadas en pruebas no incorporadas.
- Envío de consultas externas, respuestas o autorización de uso de datos.
- Entrevistas realizadas o hipótesis validadas con participantes.

La falta de evidencia revisada no equivale a afirmar que esas actuaciones no hayan ocurrido. Se requiere su registro antes de tratarlas como verificadas.

## 5. Pendientes

Orden propuesto, no aprobado como planificación cerrada:

1. Revisar diferencias entre los candidatos generales al MVP y el incremento de `REQUISITOS.md`; aprobar una línea base explícita.
2. Revisar e incorporar, cuando se autorice, evidencia técnica de datos y condiciones aplicables. No aprobar la integración solo por una respuesta técnica satisfactoria.
3. Concretar cobertura y temporada actual; prórrogas; jugadores sin participación; valores ausentes; clasificación de competición y fase.
4. Definir criterios de accesibilidad, rendimiento y terminado proporcionados.
5. Elaborar bocetos de listado y detalle cuando el alcance esté confirmado.
6. Preparar entrevistas y buscar participantes reales, revisando privacidad antes de recoger datos personales.
7. Resolver integración, caché, persistencia y papel de PostgreSQL durante el diseño.
8. Decidir la incorporación de `VIABILIDAD_DATOS.md`, `PLAN_MAESTRO.md` y registros externos. No se reconstruyen sus contenidos sin los originales.
9. Revisar individualmente las correcciones C1–C18 y E1–E7 y la organización mediante issues; no declararlas cerradas por esta consolidación.

## 6. Correcciones históricas pendientes

| Grupo | Tema | Estado |
|---|---|---|
| C1–C7 | Fuentes y datos | Pendiente de revisión individual. |
| C8–C10 | Lesiones, exportación y récords | Pendiente de revisión individual. |
| C11 | Actualización después de partidos | Pendiente; no se aprueba automatización periódica. |
| C12–C15 | Versiones, importador, JWT y Kubernetes | Criterios parciales en contexto; sin cierre global. |
| C16 | Calidad verificable | Pendiente; requisitos de calidad todavía propuestos. |
| C17–C18 | Flujo de trabajo y checklist | Pendiente de revisión individual. |
| E1–E7 | Datos, evidencias, registro y planificación | Pendiente de revisión individual. |

## 7. Copias del Project y equipo local

Las copias anteriores de contexto y estado del Project quedan desactualizadas respecto a esta revisión. No se han sustituido mediante este commit; hacerlo requiere autorización expresa.

El equipo local no se modifica con la escritura remota. La actualización local queda pendiente de pull. Cualquier cambio local no publicado deberá preservarse antes de resolver un posible conflicto.

## 8. Registro de sesión

| Fecha | Actuación | Alcance y límites |
|---|---|---|
| 01/11/2026 | Revisión editorial de entregables y preparación de actualización documental en GitHub. | Estilo profesional unipersonal; corrección de atribuciones no contrastadas; requisitos como borrador. No implica implementación, autorización de datos ni pruebas superadas. |

## 9. Asistencia automatizada

Se ha utilizado asistencia de IA para redactar y consolidar documentación. El responsable del proyecto conserva la responsabilidad de revisión y aprobación.
