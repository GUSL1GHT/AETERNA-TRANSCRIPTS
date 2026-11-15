# Convierte HTML en vídeos con IA usando Hyperframes

26/10/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8Dp6AVq/)

## De qué va

Hyperframes es una herramienta de código abierto que permite a agentes de IA crear motion graphics y vídeos a partir de descripciones en HTML.

## Ideas

- Crear introducciones animadas para productos o proyectos de forma automática.
- Generar clips promocionales cortos especificando el guion, duración y estilo visual.

## Lo que dice el vídeo

Alguien lo subió a GitHub: un repo que convierte HTML en video. Y los agentes de IA ya hacen motion graphics completos con él. Se llama Hyperframes. Es open source, tiene 58 mil estrellas y funciona con Claude Code, Codex, Cursor y Gemini.

Paso uno: instalas el plugin. Paso dos: escribes /hyperframes y le pides el video: de qué, cuánto dura y cómo se ve. Paso tres: el agente escribe el HTML, lo revisa y renderiza un MP4.

El truco está en lo que le pides. No digas: «hazme un video bonito». Dale el guion exacto, los datos reales y una referencia visual. Entre más específico, mejor queda.

Guarda los comandos y sigue a IADeGuardia.

## En pantalla

- Repo `github.com/heygen-com/hyperframes` (`heygen-com/hyperframes`): «Escribe HTML. Renderiza video. Hecho para agentes.» Public, licencia Apache-2.0 (open source), 58k estrellas (se ve también 53k).
- Ejemplo de `index.html`: `<div data-composition-id="intro">`, `<h1 id="title">HOLA</h1>`, `const tl = gsap.timeline();`, `tl.from("#title", { y: 40 });`; salida MP4.
- Paso 1, instala: `claude plugin marketplace add heygen-com/hyperframes` y `claude plugin install hyperframes@hyperframes`. Otro agente: `npx skills add heygen-com/hyperframes`.
- Paso 2, pide: `/hyperframes` con tema, duración y estilo. Ejemplo del README: `/hyperframes crea una intro de producto de 10 segundos con un título en fade-in, un video de fondo y música de fondo sutil.` (tema: intro de producto; duración: 10 segundos; estilo: título en fade-in, música sutil).
- Paso 3, render: `npx hyperframes lint` y `npx hyperframes render`, salida `video.mp4`.
- Mejor dale: guion exacto palabra por palabra, datos reales (cifras y nombres), referencia visual (un video o un estilo). Lo que no hay que decir: «hazme un video bonito».
- Resumen guardable: tema • duración • estilo; guion + datos + referencia. Cuenta @IADeGuardia.

## Notas

- Etiquetas: html, video, ia, motion-graphics, desarrollo-web
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-10-26_223243_convierte-html-en-videos-con-ia-usando-hyperframes_f58ce1.md`

**Revisar antes de usar:** Los términos 'Claude Code', 'CODEX', 'Cursor' y 'Gemini' se mencionan como agentes de IA que pueden interactuar con la herramienta. 'GSAP' es una librería de animación muy conocida.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "gsap" → posible: "GSAP". Motivo: Abreviatura común para GreenSock Animation Platform, una librería de JavaScript para animaciones.
- "Claude Code" → posible: "Claude". Motivo: Parece referirse a un modelo de lenguaje o agente de IA, mencionado junto a otros como Cursor y Gemini.
- "CODEX" → posible: "Codex". Motivo: Se refiere a un modelo de lenguaje de OpenAI para generación de código, pero en este contexto parece ser otro agente de IA.
- "Cursor" → posible: "Cursor". Motivo: Un editor de código con IA integrada que puede actuar como agente.
- "Gemini" → posible: "Gemini". Motivo: Un modelo de lenguaje de Google.
