# Cómo obtener el prompt de cualquier proyecto de GitHub con GitReverse

10/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8PycXK5/)

## De qué va

Descubre cómo usar GitReverse para obtener el prompt que generó un proyecto de GitHub o una web, y úsalo en herramientas como Cursor o Claude para replicarlo.

## Ideas

- Analizar proyectos open source para entender su lógica de desarrollo.
- Replicar la funcionalidad de proyectos existentes para aprender o mejorar.

## Lo que dice el vídeo

Hacemos un trato. Yo te enseño cómo sacarle a cualquier repo de GitHub el prompt que lo construyó, gratis y cambiando una palabra. A cambio, me das like y me sigues.

Paso número uno. Coges la URL de cualquier repositorio de GitHub y en la barra del navegador cambias «hub» por «reverse». GitHub.com se convierte en gitreverse.com. Le das a Enter y ya lo tienes, sin instalar ni tocar el terminal. Y en unos segundos te escupe el prompt que alguien había utilizado para crear eso.

Así que, como el paso uno ha sido muy fácil, vamos con el paso número dos. Pero antes, ya sabes, dale a like, sígueme.

Aquí viene lo bueno. Ese prompt lo llevas a Cursor, a Claude, se lo pegas tal cual y te construye tu versión desde cero. Ya no tienes que leerte 40 archivos para entender cómo está montado. Fijaos en este ejemplo: le he montado el repo entero de Next.js. Lo que acabáis de ver ha tardado menos que en abrir el Redmi.

Inciso, no lee todo el código. Lee el README y partes del código y a partir de ahí te genera un prompt. Y esto no va solo con los repos: también le puedes meter una URL y te devuelve el prompt para construirla. Incluso tiene una librería con prompts que ya ha sacado otra gente para cotillear. Y si entras con tu cuenta, te guarda un historial.

El proyecto es open source y ya tiene 1800 estrellas en GitHub. Por supuesto, lo puedes montar en tu propio servidor. Y un consejo: antes de lanzarlo, pide a tu agente que adapte el prompt a tu stack. Y ya tienes el plano de cualquier repositorio de GitHub. A partir de ahí, a copiar con cabeza. Sígueme para más.

## En pantalla

- Truco: `https://github.com/vercel/next.js` → `https://gitrevers.com/vercel/next.js` (gitreverse.com); cambiar «hub» por «reverse».
- gitreverse.com: "Reverse into a prompt - Reverse engineer any codebase or website into a prompt." Pestañas Codebase / Website; botón Get Prompt; ejemplos: Next.js, TailwindCSS, React, SvelteKit, Linux, Vercel. "This service does not store any GitHub URLs."
- Prompt generado para `gitreverse.com/vercel/next.js` (Reverse engineered prompt): "I want to create a framework for building websites and web apps with React. The goal is to make it easy for developers to build full-stack applications, where they can write both the frontend user interface and the backend server code in the same project. Performance is the most important thing. It should be blazing fast for developers, with near-instant build times and hot reloading. This could probably use something low-level like Rust for the JavaScript tooling to make this happen. For end-users, the sites it produces should be incredibly fast. It should also be flexible enough to handle different kinds of pages - for developers create static, pre-rendered pages for things like blogs and marketing sites, but also have dynamic, server-rendered pages for user dashboards or e-commerce. Make it production-ready and scalable enough for major companies to use." Sugerencia en la web: "Make sure you review the code using codemod."
- Pegar el prompt en Cursor, Claude, Codex; sin leerte 40 archivos.
- De dónde saca el prompt: el README y el árbol de archivos, no el código entero.
- Repositorio: `github.com/filiksyos/gitreverse` (filiksyos/gitreverse): 1800 stars, 288 forks, 138 commits, 1 branch, 0 packages; carpetas .github, .vscode, app, assets, commands, config, components, db, public, scripts, utils, game; archivos .env.example, .gitignore, AGENTS.md, CLAUDE.md, README.md; último merge: pull request #130 from filiksyos/game (hace 2 meses).
- Consejo: "adapta este prompt a mi stack".
- Versión del servicio: Merge prompt integration (v1.0); ejemplo de URL vacío `https://github.com/?`.

## Notas

- Etiquetas: github, prompt, ia, desarrollo, codigo
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-10_214317_como-obtener-el-prompt-de-cualquier-proyecto-de-github-con-gitreverse_fcf123.md`

**Revisar antes de usar:** El término 'reverse' se utiliza consistentemente como parte de la herramienta GitReverse, y la pronunciación o transcripción es clara. Las herramientas de IA mencionadas (Cursor, Claude) parecen ser aplicaciones estándar en el ámbito de desarrollo con IA.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Cursor" → posible: "Cursor (IDE)". Motivo: Mencionado como una herramienta para pegar prompts y construir código.
- "Claude" → posible: "Claude (chatbot de IA)". Motivo: Mencionado como una herramienta para pegar prompts y construir código.
- "Codex" → posible: "Codex (modelo de IA de OpenAI)". Motivo: Mencionado brevemente, pero su rol exacto en el flujo no queda del todo claro en la transcripción.
