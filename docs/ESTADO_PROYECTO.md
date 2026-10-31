# ESTADO_PROYECTO - Historico de avance (Boxscore)

> Se actualiza al final de cada sesion. Una IA nueva debe leerlo junto a PROYECTO_CONTEXTO.md.

## Resumen actual
- Fase actual: 0 - Preparacion del entorno
- Ultima sesion: 2026-10-31
- Proximo paso: crear el Project de Perplexity y subir estos dos archivos; luego prueba de concepto de datos

## Decisiones tomadas
| Fecha | Decision | Motivo |
|---|---|---|
| 2026-10-31 | Portal informativo de baloncesto (no fantasy ni juego) | Interes personal, buen alcance academico |
| 2026-10-31 | Nombre: Boxscore (repo `boxscore`) | Simple, en ingles, sin marcas NBA |
| 2026-10-31 | Docs en GitHub (/docs, Markdown + Mermaid); planificacion en GitHub Projects | Docs-as-code, versionado |
| 2026-10-31 | Herramientas: VS Code + GitHub Desktop (sin terminal) | Poca experiencia, preferencia por interfaz grafica |
| 2026-10-31 | Datos: balldontlie (principal) + nba_api (complemento) con BD propia como fuente de verdad | Robustez y riqueza de datos |
| 2026-10-31 | Ingestor en Python, backend en Java/Spring Boot | Usar nba_api sin cambiar el backend |

## Hecho
- [x] Definir idea, zonas de usuario y bloques de funcionalidades
- [x] Investigar fuentes de datos y riesgos
- [x] Elegir nombre: Boxscore
- [x] Crear repo privado `boxscore` en GitHub
- [x] Instalar y configurar Git, VS Code y GitHub Desktop
- [x] Clonar el repo y abrirlo en VS Code
- [x] Redactar PROYECTO_CONTEXTO.md y ESTADO_PROYECTO.md

## En curso
- [ ] Subir los dos .md a /docs (primer commit)

## Pendiente (por orden)
- [ ] Project de Perplexity "Boxscore" con instrucciones y los dos archivos
- [ ] GitHub Project (tablero) vinculado al repo
- [ ] Prueba de concepto de datos (balldontlie + nba_api)
- [ ] 00 vision.md
- [ ] 01 guion de entrevista y entrevistas (3 aficionados)
- [ ] 02 requisitos (RF/RNF, MoSCoW)
- [ ] 03 presupuesto y planificacion
- [ ] 04 wireframes y mockups
- [ ] 05 arquitectura (C4, E-R, secuencia, OpenAPI, ADRs)
- [ ] 06 seguridad (STRIDE, OWASP, RGPD)
- [ ] 07 implementacion MVP
- [ ] 08 Docker, Kubernetes, CI

## Problemas abiertos / preguntas
- Cliente real (amigos aficionados) o ficticio: por decidir
- Fecha limite y horas semanales: por decidir
- Terminos de uso de las APIs: por revisar si se publica

## Registro de sesiones
| Fecha | Que se hizo | Resultado |
|---|---|---|
| 2026-10-31 | Eleccion de idea, fuentes de datos, stack, nombre; repo creado y clonado | Documento maestro y entorno listos |
