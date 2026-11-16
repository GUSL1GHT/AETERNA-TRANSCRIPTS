# Detecta la degradación de Claude con la técnica del canario

16/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN85sxRPx/)

## De qué va

Aprende a usar la técnica del 'canario' para detectar cuándo la sesión de Claude se está degradando, antes de que aparezcan alucinaciones graves.

## Ideas

- Implementa una instrucción simple en Claude.md para que use tu nombre al inicio de cada respuesta.
- Utiliza esta señal objetiva para medir la degradación de la IA, en lugar de basarte en la intuición.
- Si el 'canario' deja de aparecer, reinicia tu sesión de Claude para evitar problemas mayores.

## Lo que dice el vídeo

Si Claude no dice tu nombre en cada respuesta, significa que tu sesión ya ha empezado a degradarse.
Cómo un agente de IA se degrada a lo largo de una sesión
El canario desaparece. El agente empieza a ignorar las características secundarias de las instrucciones
Ventana de advertencia temprana
Comienzan las alucinaciones. Se inventan archivos, API incorrecta, más errores, espera más falla
Peter Steinberg, el creador de Open Claude, habla de usar canarios. Un canario es simplemente una señal que te avisa cuando algo no está funcionando como debería.
La forma de aplicarlo es en tu archivo Claude.md añades una instrucción pequeña, como que Claude empiece cada respuesta usando tu nombre.
Ese va a ser tu canario.
Así, cuando Claude empieza a alucinar, le detectas mucho antes.
Porque Claude normalmente no pasa de funcionar perfectamente a alucinar de golpe.
Primero empieza ignorando una instrucción pequeña, como por ejemplo usar tu nombre, y después, de repente, empieza a hacer suposiciones completamente disparatadas.
Si tu canario muere, probablemente sea el momento de abrir una sesión nueva.
Si quieres la guía paso a paso para implementarlo, tenemos una bóveda donde compartimos configuraciones como esta todas las semanas.
Ve al link de la bio y encuentra el acceso.

## En pantalla

- Claude.md
- Open Claude

## Descripción del creador

Publicado por [revolutia.ai](https://www.tiktok.com/@revolutia.ai).

> Si Claude ha dejado de decir tu nombre, tu sesión ya se está degradando. Y todavía no te has dado cuenta. Peter Steinberg, el creador de OpenClaude, lo llama poner un canario. Una señal pequeña que te avisa de que algo va mal antes de que el problema sea evidente. Se monta en tu archivo Claude.md. Añades una instrucción mínima: que Claude empiece cada respuesta usando tu nombre. Eso es todo. Ese es el canario. Porque Claude casi nunca pasa de funcionar perfecto a alucinar de golpe. Primero se salta una instrucción pequeña, la más fácil de cumplir. Y un rato después está haciendo suposiciones disparatadas sobre tu código. Si el canario muere, abre sesión nueva. Lo que más me gusta de esto no es el truco. Es la idea de fondo: dejar de juzgar a la IA por si la respuesta te suena bien y empezar a medirla con una señal objetiva. Confiar en tu intuición para detectar degradación es justo lo que no funciona, porque el texto sigue sonando igual de seguro mientras se cae. Es la diferencia entre trabajar con una herramienta y montarte un sistema alrededor de ella.

## Notas

- Etiquetas: claude, ia, prompts, contexto, degradacion
- Calidad de la transcripción automática: alta
- Procesado por AETERNA en segundo plano con gemini-3.6-flash.
