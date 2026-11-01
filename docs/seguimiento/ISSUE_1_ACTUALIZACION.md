# Texto preparado para actualizar la issue #1

Destino: `DiegoGSUJA/boxscore`, issue #1, «Concretar y aprobar los requisitos del primer incremento».

Estado de este archivo: propuesta de cuerpo completo. Guardarlo en el repositorio no modifica la issue, su estado ni el tablero. No cerrar todavía: persisten ratificaciones funcionales.

---

## Objetivo

Consolidar los requisitos aprobados del primer incremento y separar las decisiones técnicas y de viabilidad todavía abiertas.

## Núcleo confirmado

Listado diario de partidos finalizados de la temporada actual, selección de fecha y detalle con resultado, parciales y estadísticas individuales de ambos equipos para el partido completo.

## Decisiones confirmadas el 01/11/2026

- [x] Competiciones: temporada regular, NBA Cup incluida su final, play-in y playoffs incluidas las Finales. Fuera: pretemporada, All-Star, Summer League y temporadas anteriores. Sin duplicar un encuentro por etiquetas solapadas.
- [x] Parciales: cuatro cuartos, PR1, PR2 y sucesivas según prórrogas disputadas, y Total. Parcial ausente como No disponible.
- [x] No participación solo si está explícita en la fuente; motivos traducidos con correspondencia revisada, sin inferir causas. Distinguir cero, ausencia y jugador no recibido.
- [x] Carga, día vacío, error con reintento y detalle incompleto diferenciados.
- [x] Fecha por inicio en España peninsular; apertura en último día con finalizados; conservar selección y no buscar temporadas anteriores.
- [x] Criterios de terminado: recorrido, casos excepcionales, teclado y foco, pruebas registradas, documentación e integración real aprobada tras revisión técnica y de condiciones.

Las marcas anteriores reflejan decisiones confirmadas, no pruebas superadas. La evidencia de aprobación es la conversación de la sesión, consolidada en la documentación.

## Antes del cierre

- [ ] Ratificar los campos individuales concretos de RF-07.
- [ ] Ratificar RF-03, RF-06 y RF-08 y los criterios de calidad que permanecen propuestos.
- [ ] Verificar la publicación de requisitos 0.5 y su coherencia con contexto y estado.
- [ ] Registrar o trasladar pendientes técnicos sin presentarlos como resueltos.

## Pendientes técnicos separados

Fuente e integración; cobertura de fases; estados e identificadores; temporada y límite de búsqueda; traducciones y categorías; caché y persistencia; rendimiento y accesibilidad detallada. No deben cerrarse por aprobar el producto.

## Documentación

- [Requisitos](../REQUISITOS.md).
- [Contexto](../PROYECTO_CONTEXTO.md).
- [Estado](../ESTADO_PROYECTO.md).

Para pegar este cuerpo en GitHub, sustituir únicamente esos tres enlaces relativos por los enlaces de repositorio correspondientes antes de solicitar autorización de escritura de la issue.

## Condición de cierre

Decisiones aceptadas identificadas y aprobadas expresamente, documentación publicada y ratificaciones restantes resueltas o explícitamente diferidas con su efecto en el alcance. No requiere implementación ni aprueba fuente, biblioteca, proveedor o alojamiento.
