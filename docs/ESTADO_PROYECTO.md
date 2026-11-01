# Boxscore — Estado del proyecto

| Control | Valor |
|---|---|
| Fecha | 01/11/2026 |
| Revisión | Cierre agrupado de preparación inicial y paso a ejecución |
| Responsable | Diego Gómez Sánchez — responsable del proyecto y desarrollador |

Leer con contexto, requisitos, UX, diseño técnico y viabilidad de datos.

## 1. Resumen actual

Preparación inicial documentada: requisitos funcionales y diseño de interacción confirmados; estructura técnica, rutas, contrato base, errores y primeras pruebas acordados. No hay aplicación implementada acreditada.

Revisión técnica de datos: evidencia exploratoria local útil, limitada. Revisión pública de condiciones: no concluye autorización; FAQ oficial restrictiva y alcance de uso no aclarado. Ninguna fuente, biblioteca de acceso, proveedor o alojamiento aprobado.

Siguiente paso: comprobar Java y herramientas disponibles, elegir versiones compatibles y preparar el backend. Primeras pruebas con datos ficticios identificados, sin integración NBA real hasta aclaración y aprobación específica. No se contrata ni instala nada mediante este commit.

## 2. Evidencia de avance

| Elemento | Evidencia y límites |
|---|---|
| Requisitos 1.0 | Commit `5a8ce5498349058df0dce05dac7a66eeaffaaf53`, `docs/REQUISITOS.md`. |
| UX 1.1 | Commit `3d86ef73c87f8d0329996aca83910b96e28c590b`, `docs/DISENO_UX.md`. |
| Diseño técnico 1.0 | Commit `23702e677a20820c0183101bea35091a46067030`, `docs/DISENO_TECNICO.md`. |
| Issue #1 | Lectura actual de GitHub: closed, completed. Cierre documental de requisitos, no de implementación. |
| Pruebas exploratorias | TXT adjunto y salidas de terminal aportadas en conversación; revisadas, no ejecutadas independientemente ni archivadas como originales en este commit. |
| Entorno Python actual | Salida aportada: Python 3.13.14, nba_api 1.12.0; sin extrapolación retrospectiva al TXT. |
| Tablero | Creación en captura; configuración e In Progress comunicados. No verificada posición actual de tarjeta. |
| Condiciones públicas | Lectura el 01/11/2026 de términos NBA.com, FAQ Stats y README de nba_api; detalle en viabilidad. No autorización jurídica o contractual. |

## 3. Resultado de esta actualización

README actualizado e índice completo; contexto 7 y estado conciliados; `VIABILIDAD_DATOS.md` nuevo con revisión técnica, condiciones, límites y consulta preparada. No se modifican requisitos, UX o diseño técnico en este commit.

No se sube el TXT original ni se copian rutas de usuario. No se envían correos, crean issues o cambian estados de Projects. Los borradores de seguimiento anteriores son instantáneas de preparación, no nuevas tareas pendientes de ejecutar automáticamente.

Se da por completada la preparación documental inicial necesaria para pasar al entorno. No se da por terminada la aplicación, la validación externa, la evaluación completa de datos ni las pruebas.

## 4. Ejecución siguiente

| Orden | Trabajo | Resultado comprobable |
|---|---|---|
| 1 | Comprobar entorno Java/herramientas; elegir versiones compatibles. | Versiones y decisión registradas, sin asumir instalaciones. |
| 2 | Crear backend Spring Boot mínimo. | Arranque y prueba inicial ejecutados, con resultado. |
| 3 | Concretar DTO, servicio e interfaz interna con casos ficticios. | Contrato y reglas de fechas/errores probados; fixtures identificados. |
| 4 | Introducir Docker Compose y GitHub Actions progresivamente. | Configuración ejecutada y resultado de CI, no solo archivos creados. |
| 5 | Preparar React y conectar las dos pantallas al contrato. | Recorrido comprobado con origen de datos identificado. |
| 6 | Evaluar/aprobar e implementar fuente real cuando se aclare. | Evidencia de uso compatible y cobertura, sin asumir permiso por respuesta técnica. |

El orden es una guía operativa ajustable, no calendario ni estimación cerrada. La aclaración de condiciones puede tramitarse en paralelo con el backend, con autorización específica para comunicaciones. Los detalles de código se documentarán junto a cambios y pruebas, sin nuevas rondas por cada campo.

## 5. Pendientes que no se cierran

- NBA Stats: compatibilidad de descarga/consulta bajo demanda, visualización privada, demo, caché/almacenamiento y condiciones de endpoints.
- Cobertura real: prórrogas, no participación explícita/motivos, otras fases, agrupación diaria española y búsqueda inicial limitada.
- Integración, formato completo del detalle y traducciones revisadas; modelo y persistencia por justificar.
- Versiones, implementación, pruebas, accesibilidad y rendimiento.
- Entrevistas, utilidad contrastada y privacidad antes de recoger datos personales.
- Coste económico de 0 euros, registro de esfuerzo y mantenimiento/operación proporcionados.
- Revisión individual C1–C18/E1–E7 y originales externos; no se cierran grupos en bloque.

No repetir las consultas ya aportadas salvo necesidad. No realizar nuevas consultas NBA para el producto mientras el uso siga sin aclarar. No se afirma que todo uso sea ilegal: se mantiene la integración sin aprobar por falta de base suficiente y señal restrictiva expresa.

## 6. Comprobaciones de cierre del incremento

Persisten los criterios de terminado de requisitos: recorrido correcto, casos excepcionales, teclado/foco, pruebas registradas, documentación conforme a implementación e integración real aprobada para declarar completado con datos reales. Fixtures ficticios no acreditan esa integración.

No se presume cumplimiento WCAG o RGPD. Requisitos y medidas no equivalen a verificación de su ejecución.

## 7. Copias, sincronización e histórico

Las copias de contexto y estado del Project quedan desactualizadas respecto a este commit; no se sustituyen sin autorización expresa. No se da por realizado el nuevo pull local. Preservar cambios locales ante conflictos.

Estado anterior íntegro: commit `23702e677a20820c0183101bea35091a46067030`, ruta `docs/ESTADO_PROYECTO.md`. Referencias históricas conservadas por Git. El commit que incluye esta revisión es la evidencia de su publicación, no de futuras instalaciones o pruebas.

## 8. Asistencia

Asistencia de IA para consolidación y redacción; revisión y aprobación del responsable. No sustituye ejecución, evidencia o autorización externa.
