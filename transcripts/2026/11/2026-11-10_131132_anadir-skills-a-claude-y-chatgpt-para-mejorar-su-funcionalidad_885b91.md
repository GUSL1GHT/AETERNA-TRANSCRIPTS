# Añadir Skills a Claude y ChatGPT para mejorar su funcionalidad

## Metadatos

- Fecha: 2026-11-10T13:11:32.693Z
- Plataforma: TikTok
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: source.mp4
- URL original: https://vm.tiktok.com/ZN8PkJrdG/
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: ia, chatgpt, claude, skills, programacion, desarrollo-web

## Auditoría técnica de términos

Los términos 'Claude' y 'ChatGPT' se refieren a modelos de lenguaje grandes y sus interfaces asociadas. 'SKILL.md' es un formato de archivo para definir habilidades para agentes de IA.

### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.

## Resumen automático

Se presentan tres 'skills' (archivos SKILL.md) que amplían las capacidades de modelos de IA como Claude y ChatGPT: un tutor socrático, un revisor de código colaborativo y una herramienta para dar a las webs un aspecto menos artificial.

## Ideas detectadas

- Implementar la skill 'socratic-tutor' para repasar temas complejos de forma interactiva.
- Utilizar la skill 'council' para obtener revisiones de código por múltiples modelos de IA antes de fusionar cambios.
- Aplicar la skill 'Unslop' para mejorar la estética y profesionalidad de las páginas web.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

[00:00] Las mejores
[00:01] 3 SKILLS
[00:01] 01 ? 02 ? 03 ?
[00:01] tres skills que le puedes meter a Claude y ChatGPT.
[00:02] Claude ChatGPT
[00:03] QUÉ ES UNA SKILL
[00:03] SKILL.md
name: revisar-codigo
description: Revisa un cambio
y avisa de los fallos
1. Lee el cambio entero
2. Busca fallos y riesgos
3. Resume en tres líneas
[00:03] Una skill es un archivo que le enseña a tu inteligencia artificial
[00:05] LE ENSEÑA A TU IA
[00:06] CLAUDE CODE + CHATGPT
[00:07] a hacer
[00:07] a hacer algo concreto. Aprender con IA suele ser leer una respuesta
[00:08] APRENDER CON IA
[00:09] RESPUESTA DE LA IA
Los intereses compuestos funcionan así:
cada periodo, el interés que ganas se
suma al capital, y el siguiente interés
ya se calcula sobre ese total mayor.
Por eso el dinero crece cada vez más
rápido: primero poco, luego mucho más,
y la clave es el tiempo que lo dejas.
[00:09] y olvidarla al día siguiente.
[00:10] CALENDARIO HOY OLVIDARLA
[00:11] MAÑANA SIGUIENTE
[00:11] Por eso Jane Street,
[00:11] JANE STREET - SOCRATIC-TUTOR
[00:12] 01 Jane Street
[00:12] una de las mayores empresas
[00:13] UNA DE LAS MAYORES EMPRESAS
[00:13] de trading
[00:13] TRADING
[00:14] de Wall Street,
[00:14] WALL STREET
[00:14] ha sacado una skill que convierte a tu IA en un profesor particular.
[00:15] janestreet / agent_skills
< > Code Issues Pull requests Actions
@ agent_skills Public
[00:15] Agent skills from Jane Street
A collection of skills for AI agents and chatbots. Each skill is a directory
the agent.
• socratic-tutor — turns an LLM into a strict personal tutor that teac
method: a diagnostic, a skill map with levels 0-5, one question a
How to use
With a coding agent that supports the common SKILL.md format, copy
folder, then ask the agent to use it ("teach me X").
[00:16] CONVIERTE A TU IA EN UN PROFESOR PARTICULAR
[00:18] SOCRATIC-TUTOR + LA SESIÓN
[00:18] Te examina,
[00:18] DIAGNÓSTICO • NIVEL 0-5
0 1 2 3 4 5
[00:19] NIVEL 2
[00:19] te pregunta una cosa cada vez hasta que lo razonas tú y vuelve a lo que fallaste.
[00:19] TUTOR • PREGUNTA 1
Si lanzas una moneda 3 veces y sale cara
las 3, ¿qué probabilidad hay de cara en la
cuarta?
[00:21] TÚ
50 %. Cada tirada es
independiente.
[00:21] REPASO
[00:22] VUELVE
[00:22] Y funciona hasta pegándola en ChatGPT.
[00:23] ChatGPT
[00:23] SKILL.md
name: socratic-tutor
description: Structured Socratic tutoring
when the user explicitly asks to be taught,
quizzed, or drilled to mastery on a topic...
[00:24] pegándola
[00:24] La segunda
[00:25] SEGUNDA
[00:25] es de Theo, un programador
[00:26] CONOCIDÍSIMO
[00:26] conocidísimo en YouTube.
[00:27] SKILL 02 • COUNCIL
[00:27] @ t3dotgg
Say What it does
"full send" Takes a change to a merged PR with nobody watching: proves it, revi
files it, babysits it, merges it.
"full stop" Same as full-send, but stops when the PR is ready for you to merge
"council" Gets review from three models from different providers, and loops un
they agree.
"sol loop" Reviews a change with GPT Sol in a loop until both agents agree.
[00:27] YOUTUBE
[00:27] ⭐ 3.310
[00:28] Como un modelo no ve sus propios fallos, su skill Council pone a Claude, GPT y Gemini a revisar tu código.
[00:28] UN MODELO NO VE SUS FALLOS
[00:29] def withdraw(user, amount):
user.balance -= amount
save(user)
notify(user)
return user.balance
[00:29] BUG
[00:30] DE ACUERDO
[00:31] CLAUDE GPT GEMINI
[00:32] REVISAR
[00:33] RONDA 1
[00:33] Cada uno le pone nota y no para de arreglarlo hasta que los tres están de acuerdo.
[00:34] CLAUDE 7/10 GPT 8/10 GEMINI 7/10
[00:35] def withdraw(user, amount):
assert user.balance >= amount
save(user)
notify(user)
return user.balance
[00:35] OK
[00:35] RONDA 2
[00:36] CLAUDE ✅ 9/10 GPT ✅ 10/10 GEMINI ✅ 9/10
[00:36] DE ACUERDO
[00:37] Eso sí, necesitas pagar los tres.
[00:37] NECESITAS PAGAR LOS TRES
[00:37] Claude SUSCRIPCIÓN
[00:38] ChatGPT Gemini
[00:38] Y la tercera es la que más ha petado,
[00:39] SKILL 03
[00:39] Notifications Fork 700 Star 12.5k
[00:40] ⭐ 6.232
[00:40] 12.000 estrellas en GitHub en 11 días.
[00:41] ⭐ 12.483 ESTRELLAS EN GITHUB
[00:42] Se llama Unslop,
[00:42] UNSLOP
[00:42] tuweb.com ANTES
[00:43] /unslop
[00:43] le quita a tu web la cara de hecha con IA.
[00:44] HECHO CON IA
[00:45] 1 - AUDITA
[00:45] Te señala los degradados morados y los emojis,
[00:46] DEGRADADO
[00:46] EMOJI
[00:47] 2 - ESTILO
[00:47] elige un estilo para tu producto y lo arregla como un diseñador.
[00:48] 3 - ARREGLA
[00:48] PRODUCTO
[00:49] DESPUÉS
[00:49] COMO UN DISEÑADOR ARREGLA
[00:50] Para mí es la más útil, porque hoy cualquiera saca una web en 10 minutos y lo difícil es que no lo parezca.
[00:51] ÚTIL
[00:52] CUALQUIERA
[00:54] DIFÍCIL
[00:55] ¿Cuál te instalas primero?
[00:56] PRIMERO?
