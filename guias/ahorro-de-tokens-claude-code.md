# Ahorro de tokens en Claude Code

Evaluación de las herramientas que aparecen en las transcripciones de `temas/` (más Caveman, que se añade como comparación). Las estrellas y licencias se consultaron en GitHub el 2026-11-11; las cifras de ahorro son las que publica cada proyecto y no se han medido aquí.

## Dónde se van los tokens

1. **Contexto fijo de cada sesión**: CLAUDE.md, memorias, instrucciones de servidores MCP y la lista de skills y plugins (nombre y descripción de cada una). Se paga en cada sesión y en cada `/clear`.
2. **Lectura de código**: abrir archivos enteros o releerlos, y salidas largas de comandos.
3. **Conversaciones largas**: el historial entero viaja en cada turno y la calidad cae (*context rot*).
4. **Código y respuestas de más**: abstracciones, dependencias y resúmenes que nadie pidió.

## Veredicto por herramienta

| Herramienta | Repositorio | Licencia | Qué hace | Veredicto |
| --- | --- | --- | --- | --- |
| Codebase Memory | [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) · ~48 k★ | MIT | Grafo local del código consultable por MCP: el agente pregunta en vez de leer archivo por archivo. | **Usar.** Mayor ahorro en proyectos grandes. Si Codex y Claude Code lo abren a la vez, el daemon puede quedarse bloqueado: cierra una de las sesiones y vuelve a abrir la otra. |
| Graphify | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) · ~146 k★ | Apache-2.0 | Grafo de conocimiento del repositorio (código, documentación, esquemas, PDF). | **No añadir** si ya usas Codebase Memory: resuelve lo mismo y duplicaría el índice. Alternativa válida si Codebase Memory no te convence. |
| Ponytail | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) · ~189 k★ | MIT | Skill «senior vago»: el cambio más pequeño que resuelve la tarea completa, sin recortar validación ni seguridad. Su benchmark declara −45 % de tokens. | **Usar solo el SKILL.md** (`skills/ponytail/SKILL.md`, v5.3.3) como skill de usuario. El plugin completo añade hooks que se ejecutan en cada turno, una barra de estado y un registro CSV que no hacen falta para ahorrar. |
| Caveman | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) · ~119 k★ | Apache-2.0 | Respuestas telegráficas para gastar menos tokens de salida. | **Descartado.** El ahorro de salida es pequeño frente al de entrada y empeora la claridad de las explicaciones en español. |
| claude-mem | [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem) | — | Memoria persistente con observaciones automáticas por cada herramienta usada. | **Con cuidado.** Inyecta instrucciones, ~30 skills y hasta 50 observaciones en cada sesión, y resume cada acción con otro modelo (consume plan). En Windows necesita Bun; sin él, el worker no arranca, aunque el contexto fijo se sigue cargando. Si lo usas, baja `CLAUDE_MEM_CONTEXT_OBSERVATIONS`. |
| Free Claude Code | [Alishahryar1/free-claude-code](https://github.com/Alishahryar1/free-claude-code) · ~69 k★ | otra (revisar) | Proxy que redirige Claude Code a proveedores gratuitos. | **Descartado por seguridad.** Tu código y tus claves pasan por terceros, la calidad depende del modelo que toque y puede incumplir condiciones de uso. |
| FreeLLMAPI / OmniRoute | [tashfeenahmed/freellmapi](https://github.com/tashfeenahmed/freellmapi) · [cheaper-inference/OmniRoute](https://github.com/cheaper-inference/OmniRoute) | MIT | Pasarelas que agregan los planes gratuitos de decenas de proveedores. | **Solo para proyectos propios** (p. ej. un asistente tipo Jarvis), nunca como sustituto de Claude Code con código privado. |
| SkillSpector | [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) · ~25 k★ | Apache-2.0 | Analiza skills en busca de patrones maliciosos antes de instalarlas. | **Recomendado** antes de instalar skills de terceros que incluyan scripts o hooks. |
| Stop Slop | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) · ~19 k★ | MIT | Skill para quitar muletillas de IA en textos. | Calidad de redacción, no ahorro. Opcional. |
| GitReverse | [filiksyos/gitreverse](https://github.com/filiksyos/gitreverse) · ~2 k★ | MIT | Deduce un prompt a partir del README y el árbol de un repositorio. | Útil para estudiar un repositorio sin leerlo entero; no lee el código completo. |

## Hábitos que ahorran más que cualquier herramienta

- Empieza cada tarea sin relación con la anterior con `/clear`; usa `/compact` o un resumen de traspaso cuando la conversación se alargue.
- Pide búsquedas concretas (Grep/Glob) y lectura por rangos; delega las búsquedas amplias en un subagente que devuelva solo la conclusión.
- Mantén CLAUDE.md corto: se carga en todas las sesiones.
- Desactiva plugins, servidores MCP y skills que no uses: su descripción ocupa contexto aunque no se invoquen.
- Usa modos de esfuerzo o modelos más ligeros para tareas mecánicas.

## Procedencia

| Herramienta | Tema y fuente |
| --- | --- |
| Graphify | [Memoria, contexto, tokens y prompts · 7](../temas/ia-memoria-contexto-y-prompts.md#7-fuente) |
| Codebase Memory | [Memoria, contexto, tokens y prompts · 2](../temas/ia-memoria-contexto-y-prompts.md#2-fuente) |
| Context rot | [Memoria, contexto, tokens y prompts · 1](../temas/ia-memoria-contexto-y-prompts.md#1-fuente) |
| Ponytail, FreeLLMAPI, SkillSpector | [Skills, plugins y Claude Code · 12](../temas/ia-skills-plugins-y-programacion.md#12-fuente) |
| Stop Slop | [Skills, plugins y Claude Code · 14](../temas/ia-skills-plugins-y-programacion.md#14-fuente) |
| Free Claude Code, OmniRoute | [IA gratis, local y alternativas · 2 y 7](../temas/ia-gratis-local-y-alternativas.md#7-fuente) |
| claude-mem | [Repositorios de GitHub destacados](../temas/repositorios-github-destacados.md) |
| GitReverse | [Ingeniería inversa y clonado de apps · 5](../temas/ingenieria-inversa-y-clonado-de-apps.md#5-fuente) |
