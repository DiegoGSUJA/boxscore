# ESTADO_PROYECTO - Histórico de avance (Boxscore)

> Se actualiza **cuando Diego lo solicita**, revisando antes el texto, y solo con lo que se pueda comprobar. El procedimiento definitivo está pendiente de decidir. Una IA nueva debe leerlo junto a `PROYECTO_CONTEXTO.md`.
> Etiquetas: **[Diego]** decisión provisional · **[Propuesta]** sin aprobar · **[Hecho]** verificado · **[Pendiente]**.

## Resumen actual

- **Fase actual:** 0 - Planificación. Decisiones provisionales tomadas; todavía no se ha implementado la aplicación.
- **Última sesión:** 2026-10-31.
- **Próximo paso:** revisar y aprobar los textos de U1-U3. Después, revisar una a una las correcciones C1-C18 y E1-E7.
- **Recordatorios:**
  - **No están aprobados:** las **fuentes y bibliotecas de acceso a datos**, los **proveedores de datos** y el **alojamiento**. El stack elegido (Java + Spring Boot, PostgreSQL, React + TypeScript) es una decisión provisional aparte.
  - Los bloques del MVP son candidatos.
  - La demo privada es opcional y condicionada.

## Decisiones

> Todas son **provisionales**: sirven de referencia, pero no están aprobadas para implementar.

| Fecha | Decisión | Estado | Motivo o nota |
|---|---|---|---|
| 2026-10-31 | Portal informativo de baloncesto NBA (no fantasy ni juego) | [Diego] Vigente | Interés personal |
| 2026-10-31 | Nombre: Boxscore (repo `boxscore`) | [Diego] Vigente | Simple, sin marcas NBA |
| 2026-10-31 | Herramientas: VS Code + GitHub Desktop; interfaz gráfica antes que terminal | [Diego] Vigente | Preferencia personal |
| 2026-10-31 | Docs en GitHub `/docs` (Markdown + Mermaid) | [Diego] Vigente | Docs-as-code |
| 2026-10-31 | Planificación en GitHub Projects y GitHub como única fuente de verdad | [Propuesta] Pendiente | Forma de trabajar sin aprobar |
| 2026-10-31 | ~~Datos: balldontlie (principal) + nba_api (complemento)~~ | **Sustituida** | Era una propuesta de IA. Según la [documentación de balldontlie](https://docs.balldontlie.io/) (consultada el 2026-10-31), el plan gratuito no incluye estadísticas por partido. No hay ninguna fuente de datos aprobada |
| 2026-10-31 | ~~Ingestor en Python, backend en Java/Spring Boot~~ | **Sustituida** | Python queda condicionado a la fuente; no hay importador separado aprobado |
| 2026-10-31 | Proyecto personal de formación, sin fecha obligatoria ni supervisión académica | [Diego] Provisional | Objetivo: recorrer el ciclo completo |
| 2026-10-31 | Trabajo por tareas, sin fechas; registro del tiempo real durante las 2 primeras semanas | [Diego] Provisional | No hay disponibilidad semanal aprobada |
| 2026-10-31 | Presupuesto de 0 € estricto, sin pruebas que se conviertan en pago | [Diego] Provisional | La suscripción de Perplexity queda aparte |
| 2026-10-31 | Prioridades de aprendizaje: requisitos → arquitectura y datos → backend Java → Docker y CI/CD; frontend con menos profundidad; Kubernetes tras el MVP | [Diego] Provisional | El ciclo completo es obligatorio |
| 2026-10-31 | Público principal A y secundario B; diferenciadores A ("qué ha cambiado") y D (evolución); C como apoyo | [Diego] Hipótesis | Por validar |
| 2026-10-31 | Validación con participantes reales primero; hipótesis apoyadas, cuestionadas o pendientes | [Diego] Provisional | Sin personajes ficticios como evidencia |
| 2026-10-31 | Prioridad local; demo privada opcional y condicionada; datos ficticios identificados si hace falta | [Diego] Provisional | Ningún alojamiento aprobado |
| 2026-10-31 | Candidatos al MVP (ver `PROYECTO_CONTEXTO.md` §5) | [Diego] Candidatos | No son compromisos |
| 2026-10-31 | Datos reales primero, con comprobación temprana técnica y de condiciones de uso; nba_api como opción por probar | [Diego] Provisional | Datos ficticios solo como apoyo |
| 2026-10-31 | Stack elegido: Java + Spring Boot (aplicación única modular), PostgreSQL, React + TypeScript; Docker Compose y GitHub Actions como aprendizaje pronto | [Diego] Provisional | Versiones pendientes |
| 2026-10-31 | Fuera del alcance actual: JWT, microservicios, dos proveedores, PostgreSQL en Kubernetes | [Diego] Provisional | Sin descarte permanente |

## Hecho

- [x] Definir la idea inicial, las zonas de usuario y los bloques de funcionalidades (v1; ahora son ideas, no requisitos).
- [x] Investigación inicial de fuentes y riesgos (v1, parcial; sin revisar los términos de uso).
- [x] Elegir el nombre: Boxscore.
- [x] Crear el repo privado `boxscore` en GitHub.
- [ ] Instalar y configurar Git, VS Code y GitHub Desktop: información heredada de la versión 1, pendiente de confirmación por Diego.
- [x] Clonar el repo y abrirlo en VS Code.
- [x] Redactar `PROYECTO_CONTEXTO.md` y `ESTADO_PROYECTO.md`.
- [x] Subir los dos `.md` a `/docs` (commit `d7895e2`, 2026-10-31).
- [x] Crear el Project de Perplexity "Boxscore" (evidencia: el Project existe y tiene instrucciones, comprobado el 2026-10-31).
- [x] Generar con IA los borradores `VIABILIDAD_DATOS.md` y `PLAN_MAESTRO.md` (2026-10-31). Son borradores sin aprobar y **todavía no están disponibles en el repo**.
- [x] Tomar las decisiones provisionales de planificación (tabla anterior).

## En curso

- [ ] Revisar los textos de U1 (este archivo), U2 (`PROYECTO_CONTEXTO.md`) y U3 (descripción e instrucciones del Project de Perplexity).

## Pendiente (orden propuesto, sin aprobar)

1. [ ] Aprobar o corregir U1-U3 y aplicarlos.
2. [ ] U4: revisar qué archivos tiene el Project de Perplexity, qué contienen y si están conservados en GitHub. **No se borra nada sin autorización.**
3. [ ] Decidir si `VIABILIDAD_DATOS.md` y `PLAN_MAESTRO.md` se guardan en `/docs` como borradores.
4. [ ] Revisar una a una las correcciones C1-C18 y E1-E7, sin aplicarlas en bloque.
5. [ ] Revisar la forma de trabajar propuesta (issues, Projects, campo de horas, cambios de alcance, uso de IA).
6. [ ] Corregir el README del repo (dice "con cuentas de usuario (proyecto académico)").
7. [ ] Guion de entrevista y búsqueda de participantes.
8. [ ] Comprobación temprana de datos reales: viabilidad técnica y condiciones de uso. Será la primera tarea de ejecución.
9. [ ] Visión, requisitos, UX, arquitectura, seguridad, pruebas, presupuesto y operación (según la hoja de ruta, pendiente de aprobar).

## Problemas abiertos / preguntas

- Condiciones de uso de NBA.com: si se pueden almacenar y mostrar los datos en local o en una demo privada (ver `PROYECTO_CONTEXTO.md` §7.3).
- nba_api: no se ha probado desde el PC de Diego. La prueba desde la nube falló y no es concluyente (evidencia: `registro_pruebas.json`, todavía no disponible en el repo).
- Número de participantes reales disponibles.
- Disponibilidad real de tiempo (se medirá).
- Versiones concretas (Java 21 o 25, entre otras) y alojamiento de la demo.

## Correcciones reflejadas parcialmente

> Ninguna corrección C o E está resuelta del todo. Esta tabla solo indica dónde toca U1-U2 su tema; cada una sigue **pendiente de revisión individual**.

| Corrección | Dónde se refleja parcialmente | Qué queda pendiente |
|---|---|---|
| C1-C7 (fuentes de datos) | `PROYECTO_CONTEXTO.md` §7 | Revisar cada punto; no hay fuente de datos elegida |
| C8-C10 (lesionados, CSV/PDF, récords) | `PROYECTO_CONTEXTO.md` §5 y Anexo A.6 | Confirmar el tratamiento de cada idea |
| C11 (actualización tras cada partido) | `PROYECTO_CONTEXTO.md` Anexo A.1 (sin cambios) | Todo |
| C12-C15 (versiones, ingestor, JWT, Kubernetes) | `PROYECTO_CONTEXTO.md` §8-§9 | Versiones concretas; forma de integrar los datos |
| C16 ("que no falle") | `PROYECTO_CONTEXTO.md` §2 | Definir un requisito no funcional medible |
| C17-C18 (flujo con Perplexity, checklist) | `PROYECTO_CONTEXTO.md` Anexo A.3-A.4 (sin cambios) | Todo |
| E1 (decisión de datos) | Este archivo, sección "Decisiones" | Confirmar la redacción |
| E2-E4 (estado de las tareas) | Este archivo, sección "Hecho" | Confirmar la redacción |
| E5-E7 (registro, próximo paso, orden) | Este archivo, secciones "Resumen", "Pendiente" y "Registro" | Revisar el orden de trabajo |

## Registro de sesiones

| Fecha | Qué se hizo | Resultado |
|---|---|---|
| 2026-10-31 | Elección de idea, fuentes de datos, stack y nombre; repo creado y clonado | Documento maestro y entorno listos |
| 2026-10-31 | Análisis de viabilidad de datos y plan maestro (IA); 3 pruebas con nba_api desde un sandbox en la nube | Borradores sin aprobar. Pruebas fallidas y no concluyentes (evidencia: `registro_pruebas.json`, 2026-10-31 22:14 UTC; **todavía no disponible en el repo**) |
| 2026-10-31 | Decisiones provisionales de marco, público, validación, alcance, exposición, datos y tecnologías | Resumen consolidado aceptado como borrador de referencia; U1-U3 preparados para revisión |
