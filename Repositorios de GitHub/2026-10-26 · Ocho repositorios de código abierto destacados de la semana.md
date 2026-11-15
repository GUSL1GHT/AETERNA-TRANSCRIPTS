# Ocho repositorios de código abierto destacados de la semana

26/10/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8Da7gbY/)

## De qué va

Presentación de ocho repositorios de GitHub que han ganado popularidad esta semana, cubriendo diversas funcionalidades como análisis de aplicaciones, generación de voz, búsqueda de empleo, emulación de consolas y creación de contenido visual.

## Ideas

- Explorar y descargar los repositorios presentados para probar sus funcionalidades en proyectos personales.
- Utilizar las herramientas descritas para mejorar flujos de trabajo en desarrollo, seguridad o creación de contenido.

## Lo que dice el vídeo

Carrusel de LUA TECH, "repos gratis de la semana": ocho repos gratis que explotaron esta semana (qué hace cada uno, cómo instalarlo, qué requiere).

1. morluto/rea: desarma cualquier app y entiende cómo funciona por dentro. Tu agente de IA analiza apps web, móviles y binarios nativos. Se conecta a Ghidra, Hopper y MCP para decompilar y mapear. Pensado para auditorías de seguridad e interoperabilidad. Para devs, pentesters e investigadores de seguridad. Requiere Node.js + npm y un agente (Claude Code, Codex...).

2. debpalash/VoiceStudio: tu propio ElevenLabs, local, sin API key y gratis. Clona una voz con un audio corto o diseña voces nuevas. Dobla vídeos a otros idiomas conservando al hablante. Transcribe, dicta y crea audiolibros en 646 idiomas. Para creadores, editores de vídeo y podcasters. Requiere 8 GB de RAM y 10 GB de disco; GPU opcional.

3. MadsLorentzen/ai-job-search: busca trabajo con un agente que adapta tu CV a cada oferta. Rastrea portales de empleo y ordena vacantes según tu perfil. Evalúa el encaje y redacta CV y carta a medida. Un agente revisor critica y pule cada postulación. Para cualquier persona en búsqueda de empleo. Requiere: repo gratis; Claude Code es de pago (Pro/Max o API); Python, Bun y Latex.

4. boykopovar/AnyPS5: ejecutables de PS5, nativos en Linux y Windows, sin emulador. Un relinker convierte el ejecutable al formato de tu sistema. Reimplementa librerías del sistema para enlace dinámico. Recompila shaders a Vulkan y mapea mandos vía SDL. Para preservación, investigación y compatibilidad. Requiere tus propios archivos; no incluye juegos, firmware ni claves.

5. storytold/artcraft: dirige tus imágenes de IA como si fuera un set de rodaje. Monta la escena en 3D: actores, props, cámara y profundidad. Posa personajes y fija su identidad antes de generar. Pasa de prompt a imagen y de imagen a vídeo en un lienzo. Para artistas, diseñadores y filmmakers. Requiere Windows o macOS (Linux compilando); los modelos de IA que conectes pueden tener costo.

6. stablyai/orca (aparece en la lista y en el resumen final).

7. NationalSecurityAgency/ghidra: la herramienta de la NSA para leer el código de cualquier programa. Decompila binarios a pseudocódigo C legible. Soporta múltiples arquitecturas y formatos de ejecutable. Es el motor detrás de herramientas como rea. Para seguridad, análisis de malware e ingeniería inversa. Requiere JDK 25 de 64 bits.

8. heygen-com/hyperframes: escribe HTML, exporta video MP4. Convierte HTML, CSS y animaciones en video, frame a frame. Funciona con GSAP, Lottie y Three.js, sin React ni build. Tu agente de IA puede escribir los videos por ti. Para motion designers, devs y creadores de contenido. Requiere Node.js 22+ y FFmpeg; render local, sin pagar por render.

¿Cuál vas a clonar primero? Te leo en comentarios. Guárdalo y comparte con quien lo necesite. Sigue a Lua tech para el resumen de la próxima semana.

## En pantalla

- Estrellas ganadas del 15 al 21 de oct (fuente: GitHub trending semanal, 15-21 oct 2026): morluto/rea +157.6k; debpalash/VoiceStudio +17.1k; MadsLorentzen/ai-job-search +12.8k; boykopovar/AnyPS5 +11.2k; storytold/artcraft +10.3k; stablyai/orca +8.2k; NSA/ghidra +6.2k; heygen-com/hyperframes +6.0k.
- Estrellas totales y licencia/lenguaje: rea 357.9k, MIT, TypeScript; VoiceStudio 88.4k, AGPL-3.0, Python; ai-job-search 62.9k, MIT, Python; AnyPS5 45.0k, GPL-2.0, C++; artcraft 35.2k, MIT / Apache-2.0, Rust; ghidra (NationalSecurityAgency/ghidra) +6.2K esta semana, 92.5K, Apache-2.0, Java; hyperframes +6.0K, 69.2K, Apache-2.0, TypeScript.
- rea: `npx rea-agents setup` (configura rea dentro de tu agente) o `npm install --global rea-agents`; github.com/morluto/rea.
- VoiceStudio: `curl -fsSL https://voicestudio.sh/install | sh` (macOS / Linux) o app de escritorio en voicestudio.sh; github.com/debpalash/VoiceStudio.
- ai-job-search: `gh repo fork MadsLorentzen/ai-job-search --clone`, `cd ai-job-search`, `python3 tools/install_portal_clis.py`, `claude` y luego `/setup`; github.com/MadsLorentzen/ai-job-search.
- AnyPS5: conversor web boykopovar.github.io/AnyPS5 (tus archivos no salen de tu equipo) o compilar con `git clone https://github.com/boykopovar/AnyPS5`.
- artcraft: app en getartcraft.com (en el resumen final aparece escrito "getantcraft.com") o `git clone https://github.com/storytold/artcraft`.
- orca: `brew install --cask stablyai/orca/orca`.
- ghidra: 1) instalar JDK 25 (adoptium.net); 2) descargar y descomprimir el release oficial en github.com/NationalSecurityAgency/ghidra/releases; 3) lanzar con `./ghidraRun`.
- hyperframes: `npx hyperframes init my-video`, `cd my-video`, `npx hyperframes preview` (vista previa en vivo), `npx hyperframes render` (exporta MP4); github.com/heygen-com/hyperframes.

## Notas

- Etiquetas: github, open-source, desarrollo, tecnologia, repositorios
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-10-26_070904_ocho-repositorios-de-codigo-abierto-destacados-de-la-semana_104ad2.md`

**Revisar antes de usar:** Los nombres de los repositorios (ej. 'morluto/rea') a menudo indican el nombre de usuario seguido del nombre del proyecto. Los términos como Claude Code, Codex, Bun, GSAP, Lottie, Three.js y FFmpeg son herramientas o librerías técnicas reconocidas.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "morluto/rea" → posible: "rea". Motivo: Es probable que 'rea' sea el nombre del repositorio o una herramienta principal, mientras que 'morluto' es el usuario.
- "debpalash/VoiceStudio" → posible: "VoiceStudio". Motivo: Similar a 'rea', 'VoiceStudio' es probablemente el nombre de la herramienta o proyecto.
- "MadsLorentzen/ai-job-search" → posible: "ai-job-search". Motivo: 'ai-job-search' parece ser el nombre del proyecto.
- "boykopovar/AnyPS5" → posible: "AnyPS5". Motivo: 'AnyPS5' es probablemente el nombre del proyecto.
- "storytold/artcraft" → posible: "artcraft". Motivo: 'artcraft' es probablemente el nombre del proyecto.
- "stablyai/orca" → posible: "orca". Motivo: 'orca' es probablemente el nombre del proyecto.
- "NSA/ghidra" → posible: "ghidra". Motivo: 'ghidra' es el nombre de la herramienta de la NSA.
- "heygen-com/hyperframes" → posible: "hyperframes". Motivo: 'hyperframes' es probablemente el nombre del proyecto.
- "Claude Code" → posible: "Claude". Motivo: Se refiere a un modelo de lenguaje, probablemente 'Claude' de Anthropic.
