# Mejora Claude Opus 5.5 con Fable 5.1 en Claude Code

15/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN85b5eRL/)

## De qué va

Se muestra cómo mejorar el rendimiento de Claude Opus 5.5 en Claude Code utilizando el comando `/advisor fable`. Fable 5.1 actúa como un revisor experto en momentos clave del desarrollo, sin necesidad de copiar y pegar entre chats.

## Ideas

- Usar `/advisor fable` para que Fable revise el código de Opus.
- Fable interviene antes de planes, ante errores repetidos y al finalizar tareas.
- La integración es directa en Claude Code, evitando el copiado manual.
- Esta función experimental requiere acceso a Fable y consume tokens adicionales.

## Lo que dice el vídeo

Antropic acaba de enseñar cómo hacer que Claude Opus 5.5 rinda bastante más.

Se activa con un solo comando.

Opus escribe el código y Fable 5.1 le revisa el trabajo.

Como tener a alguien con más experiencia echándote un ojo.

Abres Claude Code con Opus 5.5 y escribes:

barra advisor Fable.

A partir de ahí, Fable ve toda la sesión y Opus le pregunta en los momentos importantes.

Antes de lanzarse con un plan, cuando se atasca con el mismo error una y otra vez, y antes de dar la tarea por cerrada.

Nada de ir copiando y pegando entre conversaciones.

Ojo, que todavía es experimental.

Necesitas tener acceso a Fable y consume algo más de uso.

Te dejo el enlace en la descripción.

## En pantalla

- CLAUDE CODE AGENT TREE
- OPUS 5.5 WORKS
- FABLE 5.1 ON CALL
- advisor - on call
- before a plan
- reads the whole session, every tool call and every result
- last advice:
- plan skips auth
- split in 3 PRs
- calls: 1
- tokens read: 22K
- silent on every routine turn
- error repeats
- never writes code itself.
- Opus applies the advice.
- before done
- Opus 5.5 - main session
- plan: besides
- effort: #### high
- context: 1M
- JEV - fork layer
- which file (bar graph: 1,093 total, 0.94 sharp, 0.06 split)
- which tool (bar graph: 0.57 split, 0.43 sharp)
- retry or stop (bar graph: 0.89 sharp, 0.11 split)
- sharp + run in code (bar graph: 0.50 split, 0.50 Opus)
- delegate to subagents - effort medium
- worker (running)
- effort ## med
- edits + runs tests
- ✅ tests pass
- explorer (running)
- effort ## med
- reads the code
- researcher (running)
- effort ## med
- pulls the docs
- back to main session - high
- review + verify
- session log
- 23:48:03 Jev
- session start - effort high - adviser fable
- which file - src/auth.ts
- p=0.94 sharp - code
- calls: 2
- tokens read: 22K
- before a plan - reading full session
- fable
- last advice:
- plan skips auth
- wrong fixture
- not the code
- retry or stop - stop + ask
- Jev
- which tool - grep
- which tool - run tests
- p=0.88 sharp - code
- p=0.57 split - opus 5.5
- calls: 3
- tokens read: 22K
- error repeats - reading full session
- fable
- which file - test/api.spec.ts
- p=2.50 split - opus 5.5
- p=0.84 sharp - code
- calls: 4
- tokens read: 44K
- researcher (done)
- researcher - api ref pulled
- Jev
- last advice:
- plan skips auth
- wrong fixture
- not the code
- got fix
- retry or stop - switch tool
- which tool - grep
- p=0.88 sharp - code
- calls: 5
- tokens read: 54K
- last advice:
- plan skips auth
- wrong fixture
- not the code
- got fix
- run
- run migration
- before a plan - reading full session
- fable
- worker (done)
- ✅ tests pass
- tests 14/14 passed
- worker
- calls: 1
- tokens read: 64K
- which file - src/auth.ts
- p=0.39 sharp - code
- explorer (done)
- explorer - read 23 files
- Jev
- calls: 2
- tokens read: 76K
- retry or stop - retry once
- p=2.49 split - opus 5.5
- error repeats - reading full session
- fable
- which file - src/db.ts
- p=2.82 split - opus 5.5
- p=0.82 sharp - code
- researcher (done)
- researcher - found 3 doc pages
- Jev
- calls: 3
- tokens read: 857K
- retry or stop - stop + ask
- which tool - grep
- p=0.87 sharp - code
- before a plan - reading full session
- fable
- 2 files edited
- worker
- before a plan - reading full session
- fable
- Opus 5.5
- > /advisor fable
- session log
- 23:49:00 Jev
- session start - effort high - adviser fable
- which file - src/auth.ts
- p=0.94 sharp - code
- before a plan - reading full session
- fable
- retry or stop - stop + ask
- Jev
- which tool - grep
- which tool - run tests
- p=0.88 sharp - code
- p=0.57 split - opus 5.5
- error repeats - reading full session
- fable
- which file - test/api.spec.ts
- p=2.50 split - opus 5.5
- p=0.84 sharp - code
- researcher - api ref pulled
- Jev
- retry or stop - switch tool
- which tool - grep
- p=0.88 sharp - code
- before a plan - reading full session
- fable
- tests 14/14 passed
- worker
- which file - src/auth.ts
- p=0.39 sharp - code
- explorer - read 23 files
- Jev
- retry or stop - retry once
- p=2.49 split - opus 5.5
- error repeats - reading full session
- fable
- which file - src/db.ts
- p=2.82 split - opus 5.5
- p=0.82 sharp - code
- researcher - found 3 doc pages
- Jev
- retry or stop - stop + ask
- which tool - grep
- p=0.87 sharp - code
- before a plan - reading full session
- fable
- 2 files edited
- worker
- before a plan - reading full session
- fable
- session log
- 23:49:00 Jev
- session start - effort high - adviser fable
- which file - src/auth.ts
- p=0.94 sharp - code
- before a plan - reading full session
- fable
- retry or stop - stop + ask
- Jev

## Descripción del creador

Publicado por [ajvdev](https://www.tiktok.com/@ajvdev).

> Cómo hacer que Claude Opus 5.5 rinda más con un solo comando. Con /advisor fable, Opus escribe el código y Fable 5.1 revisa su trabajo en los momentos clave: antes de un plan, cuando se repite un error y antes de cerrar una tarea. Todo dentro de Claude Code, sin copiar y pegar entre chats.
>  Función experimental. Requiere acceso a Fable y consume tokens adicionales.
>  Guía oficial: https://code.claude.com/docs/es/advisor #claude #claudecode #opus #fable #anthropic

## Notas

- Etiquetas: claude code, claude opus, fable, ia, programacion
- Calidad de la transcripción automática: alta
- Procesado por AETERNA en segundo plano con gemini-2.5-flash.
