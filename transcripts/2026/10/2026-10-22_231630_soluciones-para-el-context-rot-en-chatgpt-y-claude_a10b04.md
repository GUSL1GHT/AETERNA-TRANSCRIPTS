# Soluciones para el 'Context Rot' en ChatGPT y Claude

## Metadatos

- Fecha: 2026-10-22T23:16:30.505Z
- Plataforma: TikTok
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: source.mp4
- URL original: https://vm.tiktok.com/ZN8A36gTu/
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: inteligencia-artificial, chatgpt, claude, context-rot, prompts

## Auditoría técnica de términos

El término 'Context Rot' es un nombre acuñado por Anthropic, empresa creadora de Claude, para describir el fenómeno de deterioro del contexto en las conversaciones con IA.

### Términos dudosos detectados

- No se han detectado dudas técnicas evidentes automáticamente.

## Resumen automático

Investigadores de Microsoft descubren que los modelos de IA como ChatGPT y Claude empeoran su rendimiento en conversaciones largas, un fenómeno llamado 'Context Rot'. Se proponen dos prompts para mitigar este problema creando nuevos chats y asegurando la transferencia completa de información.

## Ideas detectadas

- Implementar un prompt para resumir y copiar conversaciones largas a chats nuevos para reiniciar el contexto.
- Utilizar un prompt posterior para que la IA solicite toda la información necesaria al inicio de un nuevo chat, evitando suposiciones.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

Los rumores eran ciertos. ChatGPT y Claude se vuelven más tontos cuanto más hablas con ellos. Seguro que te ha pasado. Llevas un rato en el mismo chat y empieza a ir lento de repente, a olvidarse de cosas o directamente a fallar mucho en lo que te responde. Y no es casualidad. Investigadores de Microsoft probaron 15 modelos de inteligencia artificial y descubrieron que rinden de media un 39% peor cuando la tarea se va construyendo a lo largo de la conversación que cuando se la das toda de golpe. Hasta Anthropic, la empresa que creó Claude, le ha puesto nombre: Context Rot, el deterioro del contexto. Cuanto más se llena el chat, peor recuerda lo que hay dentro. Claude de por sí lo soluciona prácticamente solo porque empieza a compactarlo. Y ChatGPT está empezando a implementarlo, pero yo te voy a enseñar también otra solución. Vamos a meterle este prompt para que cuando notes que la inteligencia artificial empieza a perderse, escríbele esto: "Resume esta conversación en un único bloque para pegarlo en un chat nuevo, con objetivos, decisiones, tareas pendientes, personas, enlaces y archivos. Que no se pierda nada importante y que pueda traspasarlo." Así te va a devolver un único bloque de texto, lo copias, abres un chat nuevo y lo pegas. Así partimos de cero. Y aquí viene el segundo. Justo después, en ese nuevo chat, después de pegarle eso, le escribes: "Antes de seguir, hazme todas las preguntas que necesites para tener la información completa. No respondas hasta tenerla." Así la inteligencia artificial no da nada por supuesto, tiene todo de golpe desde el primer mensaje y sigues exactamente donde lo dejaste, pero con ella otra vez fresca. Tendrás los prompts que te comentaba en la descripción.
