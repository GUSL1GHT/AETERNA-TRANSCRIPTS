# Mejora la calidad de tu código con herramientas anti-IA genérica

15/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN85xQacp/)

## De qué va

Se presentan dos herramientas, Skill Anti-Slop y Thermos, para detectar y eliminar patrones de código genérico y de baja calidad, especialmente los generados por IA.

## Ideas

- Utilizar Skill Anti-Slop para identificar y corregir frases, variables o diseños genéricos en el código y texto.
- Implementar Thermos para realizar auditorías profundas de código, incluyendo seguridad y mantenibilidad, coordinando agentes especializados.

## Lo que dice el vídeo

Que tu app funcione no significa que esté bien construida. Puede pasar las pruebas y seguir teniendo código duplicado o difícil de modificar. Y pedirle a Claude "revísalo" puede quedarse corto. Hay dos herramientas que ayudan con esto.

La primera es Anti-slop. Añade reglas automáticas para código JavaScript y Typescript. Si detecta ciertos patrones problemáticos, la comprobación falla. Puedes configurar ese control como requisito antes de aceptar los cambios.

La segunda es Thermos de Cursor. Coordina agentes que buscan errores, problemas de seguridad y código difícil de mantener, por ejemplo archivos que crecen demasiado o lógica duplicada. Después puedes pedirle a Claude que corrija lo detectado.

Para mí lo útil es tener ciertos criterios concretos para revisar lo que construyes, especialmente cuando la aplicación empieza a crecer.

## En pantalla

- Skill Anti-Slop (HABILIDADES.md): detectar y eliminar patrones genéricos generados por IA ("slop") en lenguaje natural, código y diseño.
  - Texto: frases usadas en exceso como "delve into", palabras de moda, metacomentarios. Código: nombres de variables genéricos, comentarios obvios, abstracción innecesaria. Diseño: diseños estandarizados, degradados genéricos, patrones visuales usados en exceso.
  - Cuándo usarla: revisar contenido generado por IA antes de la entrega, crear contenido original, limpiar contenido que parece genérico, establecer estándares de calidad, cuando el usuario pide detección o limpieza de slop.
  - Flujo: 1) Detectar: `python scripts/detect_slop.py <file> --verbose` (puntuación de slop 0-100, cuanto más alta peor; hallazgos de patrones; recomendaciones). Detección manual con `references/text-patterns.md` (patrones de lenguaje natural) y `references/code-patterns.md` (patrones de código). 2) Limpiar (solo texto): `python scripts/clean_slop.py <file>` (vista previa), `python scripts/clean_slop.py <file> --save` (aplica, crea copia de seguridad), `python scripts/clean_slop.py <file> --save --aggressive` (puede cambiar ligeramente el significado).
  - Objetivos de texto: "delve into" -> eliminar o reemplazar con "examinar"; "navegar por las complejidades" -> "manejar" o eliminar; "en el acelerado mundo actual" -> eliminar; metacomentario sobre el documento; simplificar frases largas ("debido a que" -> "porque", "tiene la capacidad de" -> "puede"); reemplazar palabras de moda.
  - Objetivos de código: renombrar variables genéricas (`data`, `result`, `temp`, `item`), eliminar comentarios obvios (por ejemplo `# Create a user` sobre `user = User()`), simplificar código sobrecargado.
  - Ejemplo de texto en la demo: "Our tool helps you publish a working page in an afternoon." ("Our tool helps you" sigue sonando genérico; empezar con lo que hace el lector: "Publish your draft."). Ejemplo de diseño: portfolio "Studio / Portfolio, FORM / SPACE. Spaces worth living in. Thoughtful homes. Natural materials. Room to breathe. Selected work 2024 - 2026. Courtyard house."
- Thermos / claude-thermos (creado por Cursor): revisión thermo-nuclear de ramas, con auditorías profundas de corrección y seguridad, rúbricas duras de calidad de código, subagentes en paralelo y orquestación.
  - Skills: `thermo-nuclear-review` (auditoría profunda de sucursales: errores, roturas, seguridad, devex, fugas en la puerta de funciones); `thermo-nuclear-code-quality-review` (auditoría estricta de mantenibilidad: code-judo, regla de línea 1k, espagueti, límites); `thermos` (ejecuta ambos subagentes de revisión en paralelo y sintetiza los hallazgos).
  - Agentes: `thermo-nuclear-review-subagent` y `thermo-nuclear-code-quality-review-subagent` (subagentes de tarea de alcance diferencial). Uso típico: doble reseña (thermos).
  - Cómo funciona claude-thermos: lanza Claude Code detrás de un pequeño proxy inverso local (apunta `ANTHROPIC_BASE_URL` a un puerto de bucle invertido; todo el tráfico sigue yendo a la API real de Anthropic). 1) Observar el tráfico `/v1/messages` y agruparlo en sesiones y linajes (un linaje es un prefijo de caché: modelo + conjunto de herramientas + texto del sistema); el primer linaje con herramientas es el agente principal, el resto son subagentes. 2) Detectar la ventana de peligro: el linaje principal queda inactivo mientras un subagente se ejecuta y el prefijo corre el riesgo de expirar. 3) Calentar en un intervalo inferior al TTL de 5 minutos, reproduciendo la última solicitud real del agente principal como solicitud cálida; las solicitudes cálidas van directas a la API, nunca por el proxy. 4) Resultado: al terminar el subagente, la caché del agente principal sigue caliente. Cada calentamiento cuesta una lectura (0.01s) y una escritura (0.1s); cada reescritura que evita habría costado una escritura (1.25s).
- Interfaz de Claude con pestañas Chat, Cowork, Code.

## Notas

- Etiquetas: calidad-de-codigo, ia-generativa, desarrollo-de-software, automatizacion, python
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-15_042615_mejora-la-calidad-de-tu-codigo-con-herramientas-anti-ia-generica_47cd60.md`

**Revisar antes de usar:** Se mencionan varias herramientas y conceptos técnicos relacionados con el desarrollo de IA y la mejora de código, como 'devex', 'fugas en la puerta de funciones', 'código-judo', 'regla de línea 1k' y 'espaguetis', que podrían requerir investigación adicional para su comprensión completa en el contexto.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "claude-thermos" → posible: "Claude Thermos". Motivo: Parece ser el nombre de una herramienta o sistema combinado.
- "Claude Code" → posible: "Claude Code". Motivo: Posiblemente una funcionalidad o componente de Claude relacionado con el código.
- "ANTHROPIC_BASE_URL" → posible: "ANTHROPIC_BASE_URL". Motivo: Variable de entorno común para configurar APIs.
