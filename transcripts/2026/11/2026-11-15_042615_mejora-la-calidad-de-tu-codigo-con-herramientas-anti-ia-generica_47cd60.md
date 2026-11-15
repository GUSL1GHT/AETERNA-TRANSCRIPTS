# Mejora la calidad de tu código con herramientas anti-IA genérica

## Metadatos

- Fecha: 2026-11-15T04:26:15.344Z
- Plataforma: TikTok
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: source.mp4
- URL original: https://vm.tiktok.com/ZN85xQacp/
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: calidad-de-codigo, ia-generativa, desarrollo-de-software, automatizacion, python

## Auditoría técnica de términos

Se mencionan varias herramientas y conceptos técnicos relacionados con el desarrollo de IA y la mejora de código, como 'devex', 'fugas en la puerta de funciones', 'código-judo', 'regla de línea 1k' y 'espaguetis', que podrían requerir investigación adicional para su comprensión completa en el contexto.

### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "claude-thermos" → posible: "Claude Thermos". Motivo: Parece ser el nombre de una herramienta o sistema combinado.
- "Claude Code" → posible: "Claude Code". Motivo: Posiblemente una funcionalidad o componente de Claude relacionado con el código.
- "ANTHROPIC_BASE_URL" → posible: "ANTHROPIC_BASE_URL". Motivo: Variable de entorno común para configurar APIs.

## Resumen automático

Se presentan dos herramientas, Skill Anti-Slop y Thermos, para detectar y eliminar patrones de código genérico y de baja calidad, especialmente los generados por IA.

## Ideas detectadas

- Utilizar Skill Anti-Slop para identificar y corregir frases, variables o diseños genéricos en el código y texto.
- Implementar Thermos para realizar auditorías profundas de código, incluyendo seguridad y mantenibilidad, coordinando agentes especializados.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

[00:00] que tu app funcione
[00:01] NO SIGNIFICA
[00:01] no significa que esté bien construida.
[00:03] puede pasar
[00:03] Puede pasar las pruebas
[00:05] duplicado
[00:05] y seguir teniendo código duplicado
[00:06] o difícil de modificar
[00:07] o difícil de modificar.
[00:07] y pedirle a Claude: revísalo
[00:07] Y pedirle a Claude: revísalo,
[00:09] puede quedarse corto
[00:09] puede quedarse corto.
[00:10] Skill Anti-Slop. Detectar y eliminar patrones genéricos generados por IA ("slop") en lenguaje natural, código y diseño. claude-thermos. HAY 2 HERRAMIENTAS
[00:10] Hay dos herramientas que ayudan con esto.
[00:12] 1º. Skill Anti-Slop. Anti-slop
[00:12] La primera es Anti-slop.
[00:13] HABILIDADES.md. Skill Anti-Slop. Detectar y eliminar patrones genéricos generados por IA ("slop") en lenguaje natural, código y diseño. ¿Qué es AI Slop? La pendiente de IA se refiere a patrones reveladores que señalan contenido genérico generado por IA de baja calidad: • Texto: Frases usadas en exceso como "delve into", palabras de moda excesivas, metacommentarios. • Código: Nombres de variables genéricos, comentarios obvios, abstracción innecesaria. • Diseño: diseños estandarizados, degradados genéricos, patrones visuales usados en exceso. Esta habilidad ayuda a identificar y eliminar estos patrones para crear contenido auténtico y de alta calidad. añade
[00:14] Añade reglas automáticas
[00:15] Cuándo utilizar esta habilidad. Aplicar técnicas anti-slop cuando: • Revisión de contenido generado por IA antes de la entrega. • Creando contenido original y quiero evitar patrones genéricos. • Limpiar contenido existente que parece genérico. • Establecer estándares de calidad para un proyecto. • El usuario solicita explícitamente la detección o limpieza de lodos. • El contenido tiene signos reveladores de la generación genérica de IA. Flujo de trabajo principal. 1. Detectar pendiente. Pentru fișieri de text: python scripts/detect_slop.py <file> --verbose. JavaScript
[00:16] para código JavaScript
[00:17] Typescript
[00:17] y Typescript.
[00:17] Esto evalúa y proporciona: • Puntuación de pendiente (0-100, cuanto más alta, peor). • Hallazgos de patrones específicos. • Recomendaciones prácticas. Detección manual: Lea el archivo de referencia apropiado para obtener patrones detallados. • references/text-patterns.md - Patrones de caída del lenguaje natural. • references/code-patterns.md - Programación de patrones de pendiente. si detecta ciertos
[00:18] Si detecta ciertos patrones
[00:19] 2. Limpiar pendiente. Limpieza automatizada (solo texto): # Preview changes python scripts/clean_slop.py <file> # Apply changes (creates backup) python scripts/clean_slop.py <file> --save # Aggressive mode (may slightly change meaning) python scripts/clean_slop.py <file> --save --aggressive. Limpieza manual: Aplicar estrategias de los archivos de referencia en función de los patrones detectados. problemáticos
[00:19] problemáticos, la comprobación
[00:20] Detección y limpieza de espacios de texto. Objetivos de alta prioridad. Eliminar inmediatamente: • "delve into" → eliminar o reemplazar con "examinar". • "navegar por las complejidades" → "manejar" o eliminar. • "en el acelerado mundo actual" → "eliminar". • Metacomentario sobre el documento en sí. Simplifica frases con palabras: • "para" → "para". • "debido a que" → "porque". • "tiene la capacidad de" → "puede". Reemplazar palabras de moda: falla.
[00:20] falla. Puedes configurar ese
[00:21] puedes configurar ese control
[00:22] control como requisito antes
[00:22] como requisito antes de aceptar cambios.
[00:23] de aceptar los cambios.
[00:23] 2º. Thermos. Inicie sesión para agregar. Revisión de la rama termonuclear: auditorías profundas de corrección y seguridad, además de duras rúbricas de calidad de código, subagentes paralelos, orquestación térmica y flujos opcionales listos para fusión de toma del volante y FSD. Creado por Cursor. Thermos
[00:24] La segunda es Thermos de Cursor.
[00:25] de cursor. Archivos. principal. plugins. termo. Habilidades. Habilidad. Descripción. thermo-nuclear-review. Auditoría profunda de sucursales (errores, roturas, seguridad, devex, fugas en la puerta de funciones). thermo-nuclear-code-quality-review. Estricta auditoría de mantenibilidad (código-judo, regla de línea 1k, espaguetis, límites). thermos. Ejecute ambos subagentes de revisión en paralelo y sintetice los hallazgos. coordina a agentes
[00:26] Coordina a agentes que buscan errores,
[00:27] Agentes. Agente. Descripción. thermo-nuclear-review-subagent. Subagente de tarea para rúbrica de revisión profunda (de alcance diferencial). thermo-nuclear-code-quality-review-subagent. Subagente de tarea para rúbrica de calidad de código (de alcance diferencial). Uso típico. Doble reseña (thermos). problemas de seguridad y
[00:28] problemas de seguridad y código difícil de
[00:29] código difícil de mantener.
[00:30] por ejemplo
[00:30] Por ejemplo, archivos que crecen
[00:31] archivos que crecen demasiado o lógica duplicada.
[00:32] demasiado o lógica duplicada.
[00:33] Chat. Cowork. Code. Our tool helps you publish a working page in an afternoon. "Our tool helps you" still feels generic. Start with what the reader does. Publish your draft. después puedes pedirle
[00:33] Después puedes pedirle a Claude que corrija
[00:35] Claude que corrija lo detectado.
[00:36] momentos antes. Cómo funciona. Claude-thermos lanza Claude Code detrás de un pequeño proxy inverso local (apunta a ANTHROPIC_BASE_URL, un puerto de bucle invertido todo el tráfico sigue yendo a la API real de Anthropic). 1. Observar. El proxy observa el /v1/messages tráfico y lo agrupa en sesiones y linajes, siendo un linaje un prefijo de caché, codificado por modelo + conjunto de herramientas + texto del sistema. El primer linaje portador de herramientas es el agente principal, el resto son subagentes. 2. Detectar la ventana de peligro. Cuando el linaje principal queda inactivo y un subagente se ejecuta activamente, el prefijo principal corre el riesgo de expirar. 3. Cálido. En un intervalo inferior al TTL de 5 minutos, reproduce la última solicitud real del agente principal como una solicitud cálida: prefijo almacenable en caché atómico, pero sin agente. Si el subagente termina, el agente principal devuelve el punto en el que se quedó y actualiza el prefijo completo almacenado en caché. Las solicitudes cálidas van directamente a la API, nunca a través del proxy, por lo que no pueden perturbar el tráfico real. 4. Resultado. Cuando el subagente termina, el caché del agente principal todavía está caliente. Se trata de una lectura que evita la reescritura completa. Cada calentamiento cuesta una lectura (0.01s) y una escritura (0.1s); cada reescritura que evita habría costado una escritura (1.25s) si el caché fuera grande, por lo que el intercambio para mí lo
[00:36] Para mí lo útil es tener
[00:37] ciertos criterios concretos para revisar lo que construyes.
[00:38] ciertos criterios concretos para revisar lo que construyes,
[00:39] Descripción general. Objetivos de alta prioridad. Cambiar el nombre de las variables genéricas: • data → nombra qué datos representa. • result → nombra lo que contiene el resultado. • temp → nombra lo que estás almacenando temporalmente. • item → nombra qué tipo de artículo. Elimina los comentarios obvios: # Bad Create a user user = User() # Better Let code speak user = User() Simplifique el código sobrecargado: especialmente cuando la aplicación
[00:41] especialmente cuando la aplicación empieza a crecer.
[00:42] Studio / Portfolio. FORM / SPACE. Work. About. Spaces worth living in. Thoughtful homes. Natural materials. Room to breathe. Selected work. 2024 - 2026. Courtyard house. empieza a crecer.
