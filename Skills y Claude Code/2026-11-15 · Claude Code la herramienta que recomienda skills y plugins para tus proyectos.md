# Claude Code la herramienta que recomienda skills y plugins para tus proyectos

15/11/2026 · TikTok · [Ver el vídeo](https://www.tiktok.com/@danimarote/video/7686528396951702806?is_from_webapp=1&sender_device=pc)

## De qué va

Anthropic ha lanzado Claude Code, una herramienta que analiza tus proyectos y recomienda las skills, plugins y herramientas necesarias para automatizar tareas y mejorar flujos de trabajo.

## Ideas

- Utiliza el comando `/plugin install claude-code-setup@claude-plugins-official` para que Claude analice tu proyecto.
- Claude Code recomienda skills como `xlsx` o `Finance:variance-analysis` para tareas específicas.
- Conecta Claude Code con herramientas como Google Drive, Gmail o Notion a través de servidores MCP.
- Emplea comandos como `/REVIEW` o `/EXPLAIN` para obtener revisiones de código y explicaciones detalladas.

## Lo que dice el vídeo

Todos los que usamos Claude para construir proyectos hemos pensado lo mismo alguna vez: ¿Y si hubiera una herramienta que me dijera exactamente qué skills, plugins o herramientas necesita mi proyecto?

Pues Anthropic acaba de sacar justo eso. Un comando que analiza tu proyecto y te recomienda qué le hace falta.

Buenos días, Usuario. Le pegas este comando, /plugin install claude-code-setup@claude-plugins-official, le dices que analice tu proyecto y empieza a trabajar.

Por favor, revisa mi proyecto, es un archivo .xlsx. Excelente, formulas y resultados parecen correctos. ¿Quieres que te dé un resumen ejecutivo de los hallazgos? ¿O solo cuánto cambió cada partida, no solo cuánto?

Así de simple. Diseño simulación interactiva de hooks para validación de fórmulas. Caso: hook PostToolUse sobre ediciones a .xlsx. Te recomienda hooks para automatizar las tareas que más repites.

Armando la línea de tiempo del hook. Recibió tu tarea. Detectó que involucra un archivo .xlsx. Escaneó las skills disponibles. Comparó cada descripción contra tarea. Encontró coincidencias. 2 skills aplican a este caso. Cargó cada SKILL.md. Aplicó la guía combinada. Skills para añadir nuevas capacidades dentro de Claude.

Así funciona el sistema de skills conmigo: cuando llega una tarea, comparo su descripción contra las skills disponibles y cargo las que apliquen antes de tocar el archivo. Para tu caso como te leí el balance de Coca-Cola FEMSA, las relevantes ya las tengo disponibles: xlsx para no romper fórmulas al leer/editar, y del lado financiero Finance:financial-statements y Finance:variance-analysis para comparar periodos y explicar por qué cambió cada partida, no solo cuánto.

Skills disponibles: xlsx. Lee/editar el archivo sin romper fórmulas ni nada. Finance:financial-statements. Lee estados financieros y marca variaciones relevantes en base de conocimiento. Finance:variance-analysis. Explica por qué cambió cada partida, no solo cuánto.

desde diseño hasta planificación y también servidores MCP.

Si me dices qué otras tareas repites (conciliaciones, asientos contables, cierre mensual, papeles de trabajo), te muestro las opciones de skills que tengo: Finance:reconciliations.

Busca en tu directorio de conectores. Te muestro las opciones. 2 conectores aplican. Ejecuta con el conector elegido. Guarda el archivo o envía el mensaje.

que son los que conectan Claude con herramientas como Notion, Figma o cualquier app que utilices.

Conectado. Envía un correo con el resumen ejecutivo. Documenta el hallazgo en tu base de conocimiento.

Así es como funciona con los servidores MCP: cuando tu tarea implica algo fuera del chat (guardar, enviar, documentar), busco en tu directorio de conectores, te muestro las opciones que aplican, y tú eliges - nunca elijo un conector por ti sin que lo pidas.

Ahora mismo tienes conectados: Google Drive, Gmail, Notion, Canva y Supabase. Para tu flujo de análisis financiero, los más útiles serían: Google Drive - guardar y compartir el archivo de estados financieros con tu equipo. Gmail - mandar un resumen ejecutivo por correo. Notion - documentar hallazgos de cada [ilegible] en una base de conocimiento.

Si detecta que algo puede mejorar tu flujo de trabajo, te lo recomienda automáticamente.

Además, cuando el proyecto ya empieza a ponerse serio, también puede sugerirte agentes especializados para seguridad, arquitectura o tareas mucho más específicas.

Revisa este PR antes de hacer commit. Detecta cambios en el código. Revisa token auth, API key y dependencias. No es una revisión de estilo normal. Identifica riesgo de seguridad. Delega al subagente security-reviewer. Contexto: aliado, solo herramientas de solo lectura. Escanea el diff. Secretos expuestos, inyección, dependencias vulnerables. Devuelve hallazgos al agente principal. Con severidad y línea exacta.

Secret-scanner. Detecta claves, tokens y credenciales expuestas en el diff. code-auditor. Busca vulnerabilidades de SQL, XSS y dependencias con CVEs conocidos. access-control-reviewer. Verifica que los cambios no rompan reglas de permisos.

Y no solo eso, porque también trae comandos rápidos como /REVIEW o /EXPLAIN /variance-analysis /EXPLAIN para revisar, probarlas y entender exactamente por qué Claude está haciendo lo que está haciendo.

Descompone varianzas info-driven con explicaciones y waterfall analysis. Usa cuando tengas budget vs actuals, period over period changes, revenue or expense variances, o preparando variaciones de inventario para leadership. Plugin: Finance.

Es el balance consolidado (Estado de Situación Financiera) de Coca-Cola FEMSA (KOFI) al cierre de junio 2023, comparando contra diciembre 2022. Aquí está el resumen: Activos - Total: Ps. 334,389 millones (+6.9% vs Dic-22). Efectivo y equivalentes: Ps. 43,020 millones (+32.3%) - el mayor motor del crecimiento. Cuentas por cobrar: Ps. 116,974 millones (-1.9%). Inventarios: Ps. 111,627 millones (+4.4%). Activos no circulantes: Propiedad, planta y equipo, neto: Ps. 121,236 millones (+5.9%). Activos intangibles: Ps. 10,000 millones (+1.0%). Activos por derecho de uso: Ps. 17,000 millones (+2.0%). ¿Quieres que te dé un resumen ejecutivo de los hallazgos?

Y aquí está la mejor parte: no toca tu código, solo analiza el proyecto, entiende cómo trabajas y te recomienda herramientas para hacer todo mucho más eficiente.

Let's get started.

Choose the text style that looks best with your terminal. 1. Dark mode 2. Light mode 3. Light mode (colorblind-friendly) 4. Light mode (colorblind-friendly) 5. Light mode (ANSI colors only)

function greet() { console.log("Hello, world!"); }

function greet() { console.log("Hello, Claude!"); }

Syntax theme: Monokai Extended (ctrl-t to disable) Sprites theme: github (ctrl-t to disable)

Welcome to Claude Code v2.1.70. Claude Code can be used with your Claude subscription or billed based on API usage through your Console account.

Select login method: 1. Claude account with subscription - Pro, Max, Team, or Enterprise 2. Anthropic Console account - API usage billing 3. 3rd-party platform - Amazon Bedrock, Microsoft Foundry, or Vertex AI

Ahí tú decides si lo instalas o no lo instalas.

Guarda este vídeo para que no se te pierda y comenta la palabra Claude y te envío una guía completa para que te conviertas en un Superhumano.

## En pantalla

- ANTHROP/C
- /plugin install claude-code-setup@claude-plugins-official
- That /plugin install -command but Claude Code/dash command - it works inside Claude Code's CLI dashboard, not in a chat. Don't install in manage plugins from this chat.
- Buenos días, Usuario
- /plugin install claude-code-setup@claude-plugins-official
- Por favor, revisa mi proyecto, es un archivo .xlsx
- Excelente, formulas y resultados parecen correctos. ¿Quieres que te dé un resumen ejecutivo de los hallazgos? ¿O solo cuánto cambió cada partida, no solo cuánto?
- Diseño simulación interactiva de hooks para validación de fórmulas
- Caso: hook PostToolUse sobre ediciones a .xlsx
- claude-settings.json
- "hooks": [ { "PostToolUse": { "name": "recalc", "command": "python3 script_recalc.py $CLAUDE_FILE_PATH" } } ]
- Armando la línea de tiempo del hook
- Recibió tu tarea
- Detectó que involucra un archivo .xlsx
- Escaneó las skills disponibles
- Comparó cada descripción contra tarea
- Encontró coincidencias
- 2 skills aplican a este caso
- Cargó cada SKILL.md
- Aplicó la guía combinada
- Skills para añadir nuevas capacidades dentro de Claude
- xlsx
- Lee/editar el archivo sin romper fórmulas ni nada
- Finance:financial-statements
- Lee estados financieros y marca variaciones relevantes en base de conocimiento
- Finance:variance-analysis
- Explica por qué cambió cada partida, no solo cuánto
- Finance:reconciliations
- Busca en tu directorio de conectores
- Te muestro las opciones
- 2 conectores aplican
- Ejecuta con el conector elegido
- Guarda el archivo o envía el mensaje
- Google Drive
- Conectado
- Gmail
- Envía un correo con el resumen ejecutivo
- Notion
- Documenta el hallazgo en tu base de conocimiento
- Google Drive, Gmail, Notion, Canva y Supabase
- Google Drive - guardar y compartir el archivo de estados financieros con tu equipo
- Gmail - mandar un resumen ejecutivo por correo
- Notion - documentar hallazgos de cada [ilegible] en una base de conocimiento
- Revisa este PR antes de hacer commit
- Detecta cambios en el código
- Revisa token auth, API key y dependencias
- No es una revisión de estilo normal
- Identifica riesgo de seguridad
- Delega al subagente security-reviewer
- Contexto: aliado, solo herramientas de solo lectura
- Escanea el diff
- Secretos expuestos, inyección, dependencias vulnerables
- Devuelve hallazgos al agente principal
- Con severidad y línea exacta
- Secret-scanner
- Detecta claves, tokens y credenciales expuestas en el diff
- code-auditor
- Busca vulnerabilidades de SQL, XSS y dependencias con CVEs conocidos
- access-control-reviewer
- Verifica que los cambios no rompan reglas de permisos
- /REVIEW
- /EXPLAIN
- /variance-analysis
- /EXPLAIN
- Descompone varianzas info-driven con explicaciones y waterfall analysis. Usa cuando tengas budget vs actuals, period over period changes, revenue or expense variances, o preparando variaciones de inventario para leadership.
- Plugin: Finance
- Es el balance consolidado (Estado de Situación Financiera) de Coca-Cola FEMSA (KOFI) al cierre de junio 2023, comparando contra diciembre 2022. Aquí está el resumen:
- Activos - Total: Ps. 334,389 millones (+6.9% vs Dic-22)
- Efectivo y equivalentes: Ps. 43,020 millones (+32.3%) - el mayor motor del crecimiento
- Cuentas por cobrar: Ps. 116,974 millones (-1.9%)
- Inventarios: Ps. 111,627 millones (+4.4%)
- Activos no circulantes:
- Propiedad, planta y equipo, neto: Ps. 121,236 millones (+5.9%)
- Activos intangibles: Ps. 10,000 millones (+1.0%)
- Activos por derecho de uso: Ps. 17,000 millones (+2.0%)
- ¿Quieres que te dé un resumen ejecutivo de los hallazgos?
- Let's get started.
- Choose the text style that looks best with your terminal.
- 1. Dark mode
- 2. Light mode
- 3. Light mode (colorblind-friendly)
- 4. Light mode (colorblind-friendly)
- 5. Light mode (ANSI colors only)
- function greet() { console.log("Hello, world!"); }
- function greet() { console.log("Hello, Claude!"); }
- Syntax theme: Monokai Extended (ctrl-t to disable)
- Sprites theme: github (ctrl-t to disable)
- Welcome to Claude Code v2.1.70
- Claude Code can be used with your Claude subscription or billed based on API usage through your Console account.
- Select login method:
- 1. Claude account with subscription - Pro, Max, Team, or Enterprise
- 2. Anthropic Console account - API usage billing
- 3. 3rd-party platform - Amazon Bedrock, Microsoft Foundry, or Vertex AI

## Descripción del creador

Publicado por [danimarote](https://www.tiktok.com/@danimarote).

> Comenta la palabra CLAUDE y te envío una guía completa para que te conviertas en un superhumano 💪

## Notas

- Etiquetas: claude code, anthropic, ia, programacion, plugins, skills
- Calidad de la transcripción automática: alta
- Procesado por AETERNA en segundo plano con gemini-2.5-flash.

Posibles errores de transcripción:

- "ANTHROP/C" → posible: "Anthropic". Motivo: Es el nombre de la empresa creadora de Claude.
- "MCP" → posible: "Módulos de Conexión de Plataforma". Motivo: Se refiere a conectores que permiten a Claude interactuar con otras aplicaciones.
