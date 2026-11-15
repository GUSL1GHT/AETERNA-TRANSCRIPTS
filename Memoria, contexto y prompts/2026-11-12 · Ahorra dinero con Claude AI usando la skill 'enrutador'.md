# Ahorra dinero con Claude AI usando la skill 'enrutador'

12/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8Pn4196/)

## De qué va

Optimiza el uso de tus modelos de Claude AI para reducir costes mediante la skill 'enrutador', que distribuye las tareas entre los modelos más económicos según su capacidad.

## Ideas

- Utiliza la skill 'enrutador' para asignar tareas a los modelos de Claude más baratos (Haiku, Sonnet) en lugar del más caro (Opus) cuando sea posible.
- Implementa la 'enrutador' para tareas largas como resúmenes extensos o traducciones de documentos y haz que Opus revise el resultado final para asegurar la calidad.

## Lo que dice el vídeo

¿Se te funde el límite? Se te funde el límite de Claude antes del finde. Mira esto. Si pagas el Claude de 20 € y no quieres pasarte al de 100, instálate esta skill. Se llama enrutador.

Muchas veces estarás gastando tu modelo más potente en tareas que podría hacer el más pequeño, por ejemplo «¿cómo se dice gracias en inglés?». Con Claude usarás principalmente tres modelos, del más barato al más caro: Haiku, Sonnet y Opus. Opus es el más listo, pero también el que más gasta. Y Haiku es el más barato: cuesta hasta 40 veces menos. Y lo curioso es que para muchas tareas ni siquiera notarás la diferencia.

Así que con esta skill Opus hace de jefe. Lee lo que le estás pidiendo y decide quién lo hace. Distribuye el trabajo según quién tenga la capacidad para hacer cada cosa. Y cuando el modelo barato ha terminado, el modelo grande revisa el resultado. Una vez te da la respuesta, en la primera línea te dice qué ha hecho cada modelo.

¿Cuándo te recomiendo usar esta skill? Cuando le pases tareas muy largas; por ejemplo, resumir un PDF de muchísimas páginas, traducir un documento entero o hacer un análisis muy extenso. En las pruebas que yo he hecho con este tipo de tareas muy largas, el ahorro es de hasta el 40 %. Si es para preguntas sencillas o dudas concretas, no te recomiendo usarla, ya que ahí el ahorro es prácticamente cero. Te dejo la skill y una guía para poder instalarla y usarla en la descripción.

## En pantalla

- Límites de uso: semana actual 76 %; límite semanal 100 %. Tu plan: 20 al mes; plan grande: 100 al mes.
- Precio por millón de tokens de entrada (API de Anthropic): Opus 4 $; Haiku 0,10 $ (x 40 más barato).
- Ejemplo en Claude Code: `/enrutador Resume la ley de alquileres en 12 puntos` -> Agente haiku, partes 1 a 3 de 3; resultado: «Haiku leyó la ley entera (3 ayudantes en paralelo) - Opus comprobó y contesta»; punto 1: «Duración mínima de 5 años (art. 9.1)».
- Tareas recomendadas: resumir un PDF largo (Haiku), traducir un documento (Haiku), un análisis extenso (Sonnet).
- Ahorro medio de 26 pruebas con leyes del BOE (precio de API, con y sin la skill): Resumir (Haiku) -20 %, Traducir (Haiku) -40 %, Analizar (Sonnet) -10 %.
- Preguntas sencillas, p. ej. «¿Qué oferta de trabajo acepto?»: no hace falta.

## Notas

- Etiquetas: claude-ai, openai, ahorro, productividad, ia
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-12_110959_ahorra-dinero-con-claude-ai-usando-la-skill-enrutador_b12419.md`

**Revisar antes de usar:** Se asume que 'Claude' se refiere a los modelos de lenguaje de Anthropic, y 'skill' a una funcionalidad o herramienta adicional.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude" → posible: "Claude AI". Motivo: Se refiere al modelo de lenguaje de Anthropic, a menudo nombrado como Claude AI.
- "enrutador" → posible: "router". Motivo: El término 'enrutador' parece ser una traducción literal de 'router', que se utiliza para dirigir el tráfico o las tareas.
- "skill" → posible: "herramienta". Motivo: En este contexto, 'skill' se refiere a una herramienta o funcionalidad adicional para Claude AI.
