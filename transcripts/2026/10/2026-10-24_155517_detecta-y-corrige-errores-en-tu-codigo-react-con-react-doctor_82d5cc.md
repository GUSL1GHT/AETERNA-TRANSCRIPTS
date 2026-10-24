# Detecta y corrige errores en tu código React con React Doctor

## Metadatos

- Fecha: 2026-10-24T15:55:17.215Z
- Plataforma: TikTok
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: source.mp4
- URL original: https://vm.tiktok.com/ZN8DMX1B2/
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: react, javascript, programacion, desarrollo-web, errores

## Auditoría técnica de términos

Se mencionan varios modelos de IA como Claude Code, Codex, Grok, y Cursor. La transcripción es clara en cuanto a los comandos de `npm` y la herramienta `react-doctor`.

### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.

## Resumen automático

Aprende a usar React Doctor para escanear tu proyecto, identificar errores y vulnerabilidades, y mejorar el rendimiento de tu aplicación React.

## Ideas detectadas

- Utilizar `npx react-doctor@latest` para un escaneo inicial del código.
- Instalar la skill de React Doctor en tu agente de IA con `npx react-doctor@latest install` para que corrija errores automáticamente.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

Hacemos un trato y yo te enseño cómo pillar todo el código malo que genera tu IA como un senior, gratis y en dos pasos. Y tú, me dejas un like y me sigues.
[00:10] Paso uno.
[00:11] ~mi-proyecto
$ npx react-doctor@latest
Abrimos el terminal desde la carpeta dentro de nuestro proyecto.
[00:14] $ npx -y react-doctor@latest
Escribimos npx espacio
[00:16] src/components/Header.tsx 1 error
src/components/Footer.tsx 1 error
src/components/NavBar.tsx 1 error
src/components/Avatar.tsx 1 error
Scan for React issues
react-doctor arroba latest y
[00:19] 42 / 100 Critical
le damos a enter.
[00:21] REACT-DOCTOR
x instalar nada
x pagar
x registrarse
No hay que instalar nada, ni
[00:23] REACT-DOCTOR
x instalar nada
x pagar
x registrarse
pagar, ni registrarse.
[00:24] src/components/NavBar.tsx 1 error
src/components/Avatar.tsx 1 error
src/components/Tooltip.tsx 1 error
src/components/Dropdown.tsx 1 error
src/components/Table.tsx 1 error
Scan for React issues
Él solo escanea todo el código
[00:26] src/pages/Login.tsx 1 error 1 warning
src/pages/Register.tsx 2 errors 1 warning
src/pages/NotFound.tsx 1 error
src/pages/Dashboard.tsx 1 error
src/pages/Checkout.tsx 1 error
src/actions/deleteUser.ts 1 error
src/actions/updateProfile.ts 1 error
src/actions/createPost.ts 1 error
src/actions/uploadFile.ts 1 error
src/actions/sendEmail.ts 1 error
src/utils/debounce.ts 1 error
src/utils/throttle.ts 1 error
Scan for React issues
y te saca un informe.
[00:27] 42 / 100 Critical
Errores de estado, de rendimiento,
[00:28] 22 errors across 18 files in 2.1s
x Derived state computed in useEffect, compute during render instead [5]
x Server action "deleteUser" missing authentication check [2]
x Array index used as key, causes bugs when items are reordered [12]
x Component "UserCard" inside "Dashboard", destroys state every render [4]
x Data fetched in useEffect without cleanup, causes race conditions [8]
x useState initialized from prop, derive during render instead of syncing [3]
x Missing prefers-reduced-motion check for animations [2]
Fix with coding agent
de seguridad, de accesibilidad,
[00:31] 22 errors across 18 files in 2.1s
x Derived state computed in useEffect, compute during render instead [5]
x Server action "deleteUser" missing authentication check [2]
x Array index used as key, causes bugs when items are reordered [12]
x Component "UserCard" inside "Dashboard", destroys state every render [4]
x Data fetched in useEffect without cleanup, causes race conditions [8]
x useState initialized from prop, derive during render instead of syncing [3]
x Missing prefers-reduced-motion check for animations [2]
Fix with coding agent
con el archivo y la línea
[00:32] 42 / 100 Critical
exacta.
Así que como el paso uno ha sido muy fácil, vamos con el paso número dos.
[00:37] Like + sígueme
Pero antes recuerda, dale a like, sígueme.
[00:39] $ npx react-doctor@latest install
añade la skill a tu agente
Ahora escribimos npx react-doctor@latest install.
[00:44] FUNCIONA CON
Claude Code
Esto le mete una skill
[00:46] FUNCIONA CON
Claude Code
Codex
independientemente de que uses Claude
[00:48] FUNCIONA CON
Claude Code
Codex
Cursor
Code, Codex, Grok 4.6,
[00:50] FUNCIONA CON
Claude Code
Codex
Cursor
OpenCode
el que sea.
[00:51] 22 errors across 18 files in 2.1s
x Derived state computed in useEffect, compute during render instead [5]
x Server action "deleteUser" missing authentication check [2]
x Array index used as key, causes bugs when items are reordered [12]
x Component "UserCard" inside "Dashboard", destroys state every render [4]
x Data fetched in useEffect without cleanup, causes race conditions [8]
x useState initialized from prop, derive during render instead of syncing [3]
x Missing prefers-reduced-motion check for animations [2]
Y a partir de ahí, tu
[00:53] 22 errors across 18 files in 2.1s
x Derived state computed in useEffect, compute during render instead [5]
x Server action "deleteUser" missing authentication check [2]
x Array index used as key, causes bugs when items are reordered [12]
x Component "UserCard" inside "Dashboard", destroys state every render [4]
x Data fetched in useEffect without cleanup, causes race conditions [8]
x useState initialized from prop, derive during render instead of syncing [3]
x Missing prefers-reduced-motion check for animations [2]
IA ya no solo ve código,
[00:54] 22 errors across 18 files in 2.1s
x Derived state computed in useEffect, compute during render instead [5]
x Server action "deleteUser" missing authentication check [2]
x Array index used as key, causes bugs when items are reordered [12]
x Component "UserCard" inside "Dashboard", destroys state every render [4]
x Data fetched in useEffect without cleanup, causes race conditions [8]
x useState initialized from prop, derive during render instead of syncing [3]
x Missing prefers-reduced-motion check for animations [2]
Fix with coding agent
los sabe arreglar
[00:57] 100 / 100 Great
deja de repetirlos.
[00:58] ANTES
11 FPS
FRAME DROPS DETECTED
vídeo de @aidenybai react.doctor
Fijaos en este juego,
[01:00] DESPUÉS
118 FPS
100 / 100 Great
vídeo de @aidenybai react.doctor
lo que acabáis de ver ahora
[01:01] DESPUÉS
121 FPS
100 / 100 Great
vídeo de @aidenybai react.doctor
es el mismo código después
[01:02] DESPUÉS
121 FPS
100 / 100 Great
vídeo de @aidenybai react.doctor
de pasarle doctor.
[01:04] Ojo a la primera vez
Inciso, la primera vez que lo lancéis, como tiene que escanear todo el código, va a tardar un poco.
[01:09] Se lanza solo
Desde ese momento, tu agente lo lanza solo cada vez que toca un componente.
[01:13] $ npx skills add
react-doctor --skill improve-threejs
es el 3D, con npx skills add,
[01:15] $ npx skills add
react-doctor --skill improve-threejs
le metes las skills
[01:18] $ npx skills add
react-doctor --skill improve-threejs
three.js que sacó ahí del creador.
[01:20] $ npx react-doctor@latest
scan http://localhost:3000
traza de rendimiento en Chrome
También puedes usar el React Doctor
[01:22] $ npx react-doctor@latest
scan http://localhost:3000
traza de rendimiento en Chrome
en local.
[01:23] $ npx react-doctor@latest
scan http://localhost:3000
traza de rendimiento en Chrome
Te abre Chrome, te graba la pantalla,
[01:26] $ npx react-doctor@latest
scan http://localhost:3000
traza de rendimiento en Chrome
marca en morado cada componente
[01:28] $ npx react-doctor@latest
scan http://localhost:3000
traza de rendimiento en Chrome
que se renderiza además.
[01:29] $ npx react-doctor@latest
ci install
revisa cada pull request
y con CI Install revisa cada
[01:31] $ npx react-doctor@latest
ci install
revisa cada pull request
pull request
[01:33] $ npx react-doctor@latest
ci install
revisa cada pull request
y solo te canta errores nuevos,
[01:34] $ npx react-doctor@latest
ci install
revisa cada pull request
no el marrón que ya tenías.
[01:35] Un senior gratis
Y ya está, ya tienes un senior revisando todo el código de manera gratuita.
[01:40] A partir de ahí, a Bytecodear
A partir de ahí, a Bytecodear sin miedo.
[01:41] Sígueme para más
