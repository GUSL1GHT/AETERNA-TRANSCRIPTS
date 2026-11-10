# Crea tus propias habilidades de IA con Claude

## Metadatos

- Fecha: 2026-11-10T22:26:27.654Z
- Plataforma: TikTok
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: source.mp4
- URL original: https://vm.tiktok.com/ZN8PyVWsV/
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: ia, claude, habilidades, personalizacion, prediccion

## Auditoría técnica de términos

La transcripción menciona varios nombres de 'skills' o herramientas dentro de la plataforma Claude, como 'Skill Creator', 'MCP Builder', 'Theme Factory', etc. Se asume que son nombres propios de la plataforma.

### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "mcp-builder" → posible: "MCP Builder". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "theme-factory" → posible: "Theme Factory". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "brand-guidelines" → posible: "Brand Guidelines". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "doc-coauthoring" → posible: "Doc Co-authoring". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "internal-comms" → posible: "Internal Comms". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "algorithmic-art" → posible: "Algorithmic Art". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "slack-gif-creator" → posible: "Slack GIF Creator". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "learn" → posible: "Learn". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "skill-creator" → posible: "Skill Creator". Motivo: Nombre de una habilidad dentro de Claude mencionada explícitamente.

## Resumen automático

Aprende a crear y activar habilidades personalizadas en Claude para predecir resultados deportivos o cualquier otra tarea.

## Ideas detectadas

- Utiliza la habilidad Skill Creator para automatizar la predicción de resultados deportivos basándote en datos específicos.
- Diseña tus propias habilidades en Claude para analizar información compleja y generar resúmenes o predicciones personalizadas.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

[00:00] Claude
[00:00] MÉXICO 2 - SUDÁFRICA 0
[00:00] Predice resultados con IA
Con esta skill de Claude acerté el resultado del partido México y Sudáfrica. Te muestro cómo hacerlo muy fácil y rápido. Primero entras a Claude y vas al menú de Customize. [00:06] ¡Bienvenido, Dani CN!
[00:06] ¿Cómo puedo ayudarle hoy?
[00:06] Escribir
[00:06] Aprender
[00:06] Código
[00:06] Vida personal
[00:06] Selección de Claude
[00:06] Plan gratuito
[00:06] Actualizar
[00:06] Chat
[00:06] Cowork
[00:06] Code
[00:06] New chat
[00:06] Projects
[00:06] Artifacts
[00:06] Customize
[00:06] Reciente
[00:06] Variantes de copy para campaña
Entras a Habilidades y confirmas que la skill llamada Skill Creator esté descargada y activa. [00:09] ← Customize
[00:09] Habilidades
[00:09] Selecciona una habilidad para ver los detalles
[00:12] /mcp-builder
[00:12] Anthropic
[00:12] 551.7K
[00:12] Guide for creating high-quality MCP (Model Context Protocol) servers.
[00:12] /theme-factory
[00:12] Anthropic
[00:12] 539.6K
[00:12] Toolkit for styling artifacts, themes, etc. Use when users want to create a theme, or apply a theme to an artifact.
[00:12] /brand-guidelines
[00:12] Anthropic
[00:12] 493.7K
[00:12] A guide for creating brand guidelines.
[00:12] /doc-coauthoring
[00:12] Anthropic
[00:12] 478.1K
[00:12] Guide users through a co-authoring workflow for co-authors.
[00:12] /internal-comms
[00:12] Anthropic
[00:12] 369.8K
[00:12] Create all kinds of internal communication.
[00:12] /algorithmic-art
[00:12] Anthropic
[00:12] 280.0K
[00:12] Guide users through a co-authoring workflow for co-authors.
[00:12] /slack-gif-creator
[00:12] Anthropic
[00:12] 247.0K
[00:12] Knowledge and utilities for creating animated GIFs optimized for Slack.
[00:12] /learn
[00:12] Anthropic
[00:12] 214.7K
[00:12] Use this skill when the user wants to learn about a new topic, or improve their intellectual understanding.
[00:12] /skill-creator
[00:12] Anthropic
[00:12] 93.7K
[00:12] Create new skills, modify and improve existing skills, and measur...
Si no lo está, la activas con un solo clic. [00:14] Habilidades personales
[00:14] skill-creator
[00:14] SKILL.md
[00:14] agents
[00:14] eval-viewer
[00:14] scripts
[00:14] references
[00:14] LICENSE.TXT
[00:14] Agregado por Anthropic
[00:14] Actividad: Comando slash + auto
[00:14] Skill Creator
[00:14] A skill for creating new skills and iteratively improving them.
[00:14] At a high level, the process of creating a skill goes like this:
[00:14] Decide what you want the skill to do and roughly how it should do it.
[00:14] Write a draft of the skill
[00:14] Create a few test prompts and run Claude-with-access-to-the-skill on them
[00:14] Help the user evaluate the results both qualitatively and quantitatively
[00:14] While the runs happen in the background, draft some quantitative evals if there aren't any (if these are some, you can either use as is or modify if you feel something needs to change about them), then explain them to the user (or if they already existed, explain the ones that already exist)
[00:14] Use the /eval-viewer/generate_review.py script to show the user the results for them to look at, and also let them look at the quantitative metrics
[00:14] Rewrite the skill based on feedback from the user's evaluation of the results (and also if there are any glaring flaws that become apparent from the quantitative benchmarks)
[00:14] Repeat until you're satisfied
[00:14] Expand the test set and try again at larger scale
[00:14] Your job when using this skill is to figure out where the user is in this process and then jump in and help them progress through the stages. So for instance, maybe they're like "I want to make a skill for X". You can help narrow down what they mean, write a draft, write the test cases, figure out how they want to evaluate, run the tests and show the results.
Ahora, abres un chat nuevo y simplemente le pides a Claude que la cree con las indicaciones que necesites. [00:16] Chat eliminado
[00:16] ¡Bienvenido, Dani CN!
[00:16] ¿Cómo puedo ayudarle hoy?
[00:16] Sonnet 4.6 Bajo
[00:16] Escribir
[00:16] Aprender
[00:16] Código
[00:16] Vida personal
[00:16] Selección de Claude
[00:16] Plan gratuito
[00:16] Actualizar
Yo, por ejemplo, le voy a pedir esto: [00:18] Crea una skill que analice los partidos del mundial 2026, que use el ranking fifa, historial entre selecciones, estadísticas relevantes, forma reciente para darte un marcador probable y además usa el sistema matemático de predicción de Joachim Klemment que predijo el ganador de los 3 últimos mundiales.
[00:27] MEN'S WORLD RANKING - TOP 10
[00:27] CLASIFICACIÓN MUNDIAL MASCULINA - TOP 10
[00:27] Pos.
[00:27] Selección
[00:27] Puntos Totales
[00:27] Puntos Anteriores
[00:27] +/-
[00:27] 1
[00:27] ARGENTINA
[00:27] 357.0
[00:27] 3500
[00:27] 2
[00:27] FRANCE
[00:27] 3313
[00:27] 3302
[00:27] 3
[00:27] BRAZIL
[00:27] 3013
[00:27] 3050
[00:27] 4
[00:27] ENGLAND
[00:27] 3070
[00:27] 2083
[00:27] 5
[00:27] BELGIUM
[00:27] 2953
[00:27] 2422
[00:27] 6
[00:27] CROATIA
[00:27] 2663
[00:27] 2871
[00:27] 7
[00:27] NETHERLANDS
[00:27] 2433
[00:27] 280
[00:27] 8
[00:27] PORTUGAL
[00:27] 2008
[00:27] 258
[00:27] 9
[00:27] SPAIN
[00:27] 2056
[00:27] 226
[00:27] 10
[00:27] USA
[00:27] 105
[00:27] 170
[00:27] *Datos ilustrativos. Para consultar el ranking oficial completo, visita el sitio web oficial de la organización pertinente.
[00:39] ¡Bienvenido, Dani CN!
[00:39] Crea una skill que analice los partidos del mundial 2026, que use el ranking fifa, historial entre selecciones, estadísticas relevantes, forma reciente para darte un marcador probable y además usa el sistema matemático de predicción de Joachim Klemment que predijo el ganador de los 3 últimos mundiales. Dame los resultados de los partidos cuando te los pida.
[00:39] Sonnet 4.6 Medio
Ya con este listo, solo le preguntas quién gana determinado partido. [00:41] the skill creator SKILL.md to understand how to create skills properly
[00:41] Se buscó en la web
[00:41] Tengo toda la información que necesito. Ahora creo la skill completa:
[00:41] La skill está lista. Ahora hagamos una prueba en vivo — dime un partido del Mundial 2026 y te doy el análisis completo usando el método.
[00:41] Primero déjame mostrarte un ejemplo para que veas el formato:
[00:41] Se buscó en la web
[00:41] Perfecto, ya tengo el ranking FIFA actualizado al 11 de junio de 2026. Actualizo el archivo de referencia con los datos reales y presento la skill:
[00:41] Se ejecutaron 2 comandos, editó un archivo, archivo leído
[00:41] La skill Mundial 2026 Predictor está lista. Aquí un resumen de lo que contiene:
[00:41] Método Klement integrado — Las 5 variables del modelo econométrico que predijo los 3 últimos campeones: PIB per cápita, población (escala logarítmica), temperatura (óptimo 14°C), ranking FIFA y ventaja de sede.
[00:41] Datos reales actualizados — Ranking FIFA oficial del 11 de junio de 2026:
[00:41] Argentina (ranking) → Francia → Brasil → Marruecos #7 (gran sorpresa) → Países Bajos #8
[00:41] Protocolo de análisis — Para cada partido calcula un Índice Klement de Partido (IKP) combinando las variables estructurales + forma reciente de los últimos 6 juegos, luego lo convierte a probabilidades y marcador estimado con alternativas.
[00:41] Pronóstico Klement 2026 → Campeón: Países Bajos (final vs Portugal)
[00:41] ¿Quieres que analice un partido ahora? Solo dime cuál: puede ser el partido inaugural (México vs Sudáfrica del 11 de junio), Argentina, Colombia, o cualquier cruce que te interese.
[00:41] mundial-2026-predictor
[00:41] Habilidad
Te da el marcador, probabilidad y análisis. [00:43] Partido Inaugural del Mundial
[00:43] 11 Jun - 19:00 MX
[00:43] Estadio Azteca, CDMX
[00:43] MÉXICO
[00:43] FIFA #13 - sede
[00:43] 2 - 0
[00:43] marcador probable
[00:43] SUDÁFRICA
[00:43] FIFA #61
[00:43] Ventaja Klement
[00:43] México (sede)
[00:43] Historial mundiales
[00:43] 2010: 1-1
[00:43] Altitud CDMX
[00:43] 2,240 m - ventaja local
[00:43] 62% MX
[00:43] 22% E
[00:43] 16% SA
[00:43] México gana — Juega en casa, ranking superior, altitud a su favor y buena forma reciente. Sudáfrica no llega al Mundial desde Qatar 2022.
[00:43] Ochoa se convierte en el primer jugador en disputar 6 Mundiales. México tiene marca perfecta vs. selecciones asiáticas/africanas en grupos.
[00:43] Alta
[00:43] 11 Jun - 20:00 MX
[00:43] Estadio Guadalajara (Akron)
[00:43] COREA DEL SUR
[00:43] FIFA #22
[00:43] 1 - 1
[00:43] marcador probable
[00:43] REP. CHECA
[00:43] FIFA #44
[00:43] Ventaja Klement
[00:43] Corea (ranking)
[00:43] H2H mundiales
[00:43] Sin historial
[00:43] H2H amistosos
[00:43] Checa 1-2 Corea (2016)
[00:43] 44% KOR
[00:43] 30% E
[00:43] 26% CZE
[00:43] Empate probable — Rivales parejos. Corea llega mejor en ranking, pero Checa es sólida y determinantemente organizada. Partido de bajo margen.
[00:43] El estadio Guadalajara hace su debut mundialista. Guadalajara será la 2ª ciudad en albergar 3 Mundiales (1970, 1986 y 2026), aunque en estadio diferente.
[00:43] Medio
No estás adivinando el futuro ni tendrás 100% de precisión, pero sí suficiente información para tomar mejores decisiones en todas las quinielas que tengas con tus amigos. [00:54] Entra ya a platzi.com
Si quieres aprender más de IA y de cómo usarla en el mundial, entra ya a platzi.com.
