# Añadir Skills a Claude y ChatGPT para mejorar su funcionalidad

10/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8PkJrdG/)

## De qué va

Se presentan tres 'skills' (archivos SKILL.md) que amplían las capacidades de modelos de IA como Claude y ChatGPT: un tutor socrático, un revisor de código colaborativo y una herramienta para dar a las webs un aspecto menos artificial.

## Ideas

- Implementar la skill 'socratic-tutor' para repasar temas complejos de forma interactiva.
- Utilizar la skill 'council' para obtener revisiones de código por múltiples modelos de IA antes de fusionar cambios.
- Aplicar la skill 'Unslop' para mejorar la estética y profesionalidad de las páginas web.

## Lo que dice el vídeo

Las mejores tres skills que le puedes meter a Claude y ChatGPT. Una skill es un archivo que le enseña a tu inteligencia artificial a hacer algo concreto. Aprender con IA suele ser leer una respuesta y olvidarla al día siguiente.

Por eso Jane Street, una de las mayores empresas de trading de Wall Street, ha sacado una skill que convierte a tu IA en un profesor particular: socratic-tutor. Te examina, te pregunta una cosa cada vez hasta que lo razonas tú y vuelve a lo que fallaste. Y funciona hasta pegándola en ChatGPT.

La segunda es de Theo, un programador conocidísimo en YouTube. Como un modelo no ve sus propios fallos, su skill Council pone a Claude, GPT y Gemini a revisar tu código. Cada uno le pone nota y no para de arreglarlo hasta que los tres están de acuerdo. Eso sí, necesitas pagar los tres.

Y la tercera es la que más ha petado: 12.000 estrellas en GitHub en 11 días. Se llama Unslop y le quita a tu web la cara de hecha con IA. Primero audita: te señala los degradados morados y los emojis. Después elige un estilo para tu producto y lo arregla como un diseñador. Para mí es la más útil, porque hoy cualquiera saca una web en 10 minutos y lo difícil es que no lo parezca. ¿Cuál te instalas primero?

## En pantalla

- Ejemplo de `SKILL.md`: `name: revisar-codigo`, `description: Revisa un cambio y avisa de los fallos`; pasos: 1. Lee el cambio entero, 2. Busca fallos y riesgos, 3. Resume en tres líneas. Funciona con Claude Code y ChatGPT.
- Skill 01: Jane Street, repositorio `janestreet/agent_skills` ("Agent skills from Jane Street"): `socratic-tutor`, tutor estricto con diagnóstico, mapa de habilidades con niveles 0-5 y una pregunta cada vez. Uso: copiar la carpeta a un agente que soporte el formato `SKILL.md` y pedir "teach me X". Ejemplo de la sesión: nivel 2; pregunta sobre lanzar una moneda 3 veces y probabilidad de cara en la cuarta (respuesta: 50 %, cada tirada es independiente); repaso. En ChatGPT: `name: socratic-tutor`, `description: Structured Socratic tutoring when the user explicitly asks to be taught, quizzed, or drilled to mastery on a topic...`.
- Skill 02: `t3dotgg` (Theo), 3.310 estrellas. Comandos: "full send" (lleva un cambio hasta un PR fusionado sin nadie mirando: lo prueba, revisa, archiva, vigila, fusiona), "full stop" (igual, pero se detiene cuando el PR está listo para que lo fusiones), "council" (revisión de tres modelos de distintos proveedores en bucle hasta que coinciden), "sol loop" (revisa un cambio con GPT Sol en bucle hasta que ambos agentes coinciden). Ejemplo: Ronda 1: Claude 7/10, GPT 8/10, Gemini 7/10 (bug en `withdraw`, se añade `assert user.balance >= amount`); Ronda 2: Claude 9/10, GPT 10/10, Gemini 9/10, de acuerdo. Hay que pagar la suscripción de Claude, ChatGPT y Gemini.
- Skill 03: Unslop, comando `/unslop`; 6.232 estrellas (captura), 12.483 estrellas en GitHub, Fork 700, Star 12.5k. Pasos: 1 Audita, 2 Estilo, 3 Arregla.

## Notas

- Etiquetas: ia, chatgpt, claude, skills, programacion, desarrollo-web
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-10_131132_anadir-skills-a-claude-y-chatgpt-para-mejorar-su-funcionalidad_885b91.md`

**Revisar antes de usar:** Los términos 'Claude' y 'ChatGPT' se refieren a modelos de lenguaje grandes y sus interfaces asociadas. 'SKILL.md' es un formato de archivo para definir habilidades para agentes de IA.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
