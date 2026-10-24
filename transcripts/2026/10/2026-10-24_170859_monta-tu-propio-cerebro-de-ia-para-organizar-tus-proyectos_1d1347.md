# Monta tu propio 'cerebro' de IA para organizar tus proyectos

## Metadatos

- Fecha: 2026-10-24T17:08:59.607Z
- Plataforma: YouTube
- Proyecto relacionado: Sin proyecto asignado
- Archivo original: YouTube
- URL original: https://youtu.be/1T5b47WEcQs?is=QVCWNDhCaoiLLTfN
- Modelo de transcripción: gemini-2.5-flash
- Estado: pendiente
- Confianza técnica: alta
- Etiquetas: ia, gestion-de-proyectos, organizacion, claude, chatgpt, tutorial

## Auditoría técnica de términos

El término 'Claude Code' se usa a lo largo de la transcripción para referirse a la herramienta de Anthropic. 'Codex' se menciona como la contraparte de ChatGPT.

### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude Code" → posible: "Claude". Motivo: Se refiere a la herramienta de Anthropic, 'Code' podría ser una confusión o parte del nombre de la herramienta específica.
- "Claude.md" → posible: "Claude.md". Motivo: Parece ser un archivo de configuración específico para la IA Claude.
- "Codex" → posible: "Codex (o ChatGPT)". Motivo: Se menciona como una alternativa a Claude, y se asocia con ChatGPT, sugiriendo que puede ser el nombre del modelo o una herramienta de OpenAI.
- "agents.md" → posible: "agents.md". Motivo: Parece ser un archivo de configuración específico para la IA Codex/ChatGPT.

## Resumen automático

Tutorial para crear un sistema de gestión de proyectos personal utilizando Claude Code y ChatGPT, donde la IA accede a la información de tus proyectos a través de fichas de texto.

## Ideas detectadas

- Crear un sistema centralizado de información para cada proyecto.
- Utilizar fichas de texto sencillas para que cualquier IA pueda procesarlas.

## Uso previsto

Fuente capturada con AETERNA para revisión posterior, auditoría de ideas, generación de guías o posible conversión en tareas de proyecto.

## Transcripción literal

[ 00:00 ] Buenas, yo soy NotFound.
[ 00:01 ] Y supongo que estás aquí por el vídeo que has visto en TikTok.
[ 00:04 ] El del cerebro.
[ 00:06 ] Ese en el que Claude y ChatGPT comparten la misma memoria dentro de mi ordenador.
[ 00:11 ] Muchos me pedisteis el tutorial, así que aquí lo tienes.
[ 00:14 ] En este vídeo te voy a enseñar a montar tu propio cerebro desde cero, paso a paso y sin saltarme nada.
[ 00:20 ] No hace falta saber programar.
[ 00:21 ] Y todos los prompts que uso te los dejo en la descripción, para que solo tengas que copiar y pegar.
[ 00:27 ] Así que, al lío.
[ 00:29 ] Primero mira lo que vas a tener al acabar.
[ 00:31 ] Abro Claude Code y le pregunto cómo va un proyecto.
[ 00:34 ] No le doy ninguna pista y fíjate.
[ 00:36 ] No se pone a buscar por todo el disco.
[ 00:38 ] Abre mi cerebro, lee una ficha y me contesta.
[ 00:40 ] Eso es lo que vamos a montar hoy.
[ 00:43 ] ¿Y qué es el cerebro?
[ 00:44 ] Es más sencillo de lo que parece.
[ 00:46 ] Es una carpeta.
[ 00:47 ] Dentro hay una ficha por cada proyecto que tienes.
[ 00:50 ] Y cada ficha dice tres cosas.
[ 00:52 ] Qué es, cómo va y dónde están sus archivos.
[ 00:55 ] No copia nada, solo apunta.
[ 00:57 ] Arriba del todo hay un índice con una línea por ficha.
[ 01:00 ] Claude lee ese índice, que es cortísimo, y abre solo la ficha que necesita.
[ 01:04 ] Por eso gasta muy pocos tokens.
[ 01:06 ] Y como todos son archivos de texto, lo puede leer cualquier IA.
[ 01:10 ] Para seguir el vídeo solo necesitas dos cosas.
[ 01:13 ] La primera, tener Claude Code instalado.
[ 01:15 ] La segunda, saber en qué carpeta guardas tus proyectos.
[ 01:18 ] Si ya tienes Claude Code, salta al siguiente capítulo.
[ 01:21 ] Si no, es un minuto.
[ 01:22 ] Abre PowerShell si estás en Windows o la terminal si estás en Mac.
[ 01:26 ] Pega el comando de instalación, que lo tienes en la descripción, y pulsa intro.
[ 01:30 ] Cuando termine, escribe Claude y vuelve a pulsar intro.
[ 01:33 ] La primera vez se te abre el navegador para iniciar sesión.
[ 01:37 ] Y ojo con esto, Claude Code necesita un plan de pago.
[ 01:40 ] Con el plan gratis no entra.
[ 01:41 ] Si la terminal te da respeto, también existe la aplicación de escritorio, y funciona igual.
[ 01:47 ] Vamos con el paso uno, crear el cerebro.
[ 01:49 ] Abre Claude Code en tu carpeta de usuario y pega el primer prompt de la descripción.
[ 01:54 ] Te lo leo por encima para que sepas qué hace.
[ 01:56 ] Le pide que cree una carpeta llamada cerebro.
[ 01:59 ] Que te pregunte dónde guardas tus proyectos y en qué áreas se divide tu trabajo.
[ 02:03 ] Y que cree una ficha por cada proyecto.
[ 02:05 ] Pulsas intro y Claude te hace las preguntas.
[ 02:08 ] Yo le digo que mis proyectos están en Documentos.
[ 02:11 ] Y que mis áreas son cuatro: web, vídeos, clientes y proyectos.
[ 02:14 ] Ahora te pide permiso para crear archivos.
[ 02:16 ] Dile que sí.
[ 02:17 ] Y en un minuto tienes esto.
[ 02:19 ] Una carpeta por cada área, que yo llamo ramas.
[ 02:22 ] Dentro de cada rama, una ficha por proyecto.
[ 02:24 ] Y arriba, el índice.
[ 02:26 ] Paso dos.
[ 02:27 ] Vamos a abrir una ficha para que veas cómo es por dentro.
[ 02:30 ] Esta es la de un cliente.
[ 02:32 ] Arriba tienes la cabecera.
[ 02:33 ] Su nombre dentro del cerebro, su estado y los alias, que son las otras formas en que tú lo llamas.
[ 02:38 ] Después, una línea que dice qué es.
[ 02:41 ] Y luego viene la parte más importante.
[ 02:43 ] Se llama cuándo entrar aquí.
[ 02:45 ] Ahí pones en qué casos esta ficha es la respuesta.
[ 02:47 ] Sin eso, la IA no sabe que tiene que abrirla.
[ 02:50 ] Debajo está el estado, que es cómo va hoy.
[ 02:53 ] Y al final dónde está, las rutas de sus archivos.
[ 02:56 ] Fíjate en una cosa.
[ 02:58 ] La ficha entera cabe en una pantalla.
[ 03:00 ] Si una ficha crece demasiado, deja de servir.
[ 03:02 ] Así que repásalas una vez.
[ 03:03 ] Y lo que esté mal se lo dices a Claude y lo corrige.
[ 03:06 ] Paso tres.
[ 03:07 ] Ahora mismo el cerebro existe, pero Claude no sabe que tiene que mirarlo.
[ 03:11 ] Para eso está el archivo Claude.md.
[ 03:13 ] Son unas instrucciones que Claude Code lee al empezar cada sesión.
[ 03:17 ] El tuyo vive en tu carpeta de usuario dentro de la carpeta .Claude.
[ 03:21 ] Pega el segundo prompt de la descripción.
[ 03:24 ] Le pide que añada tres normas.
[ 03:25 ] Una, antes de buscar en el disco, mira el cerebro.
[ 03:28 ] Dos, si te cuento algo nuevo, apúntalo en su ficha sin que te lo pida.
[ 03:32 ] Y tres, el estado se sobrescribe, las fichas no crecen.
[ 03:35 ] Además lleva una norma de seguridad.
[ 03:37 ] Nunca contraseñas ni datos del banco.
[ 03:39 ] Cuando acabe, abre el archivo y comprueba que está.
[ 03:43 ] Paso cuatro, la prueba.
[ 03:45 ] Cierra Claude Code y ábrelo de nuevo, para empezar con una sesión limpia.
[ 03:49 ] Pregúntale por un proyecto sin darle ninguna pista.
[ 03:52 ] Y mira lo que hace.
[ 03:53 ] Lee el índice, abre una sola ficha y contesta.
[ 03:56 ] Ahora vamos a hacerlo al revés.
[ 03:58 ] Cuéntale algo nuevo.
[ 03:59 ] Yo le digo que el taller ha aceptado el presupuesto.
[ 04:02 ] No le pido que lo apunte, lo apunta solo.
[ 04:04 ] Abro la ficha y el estado ha cambiado.
[ 04:07 ] Si algún día se le olvida mirarlo, se lo recuerdas.
[ 04:10 ] Mira el cerebro.
[ 04:11 ] Y listo.
[ 04:12 ] Paso cinco, y esto es lo que más me gusta.
[ 04:14 ] El cerebro no es de Claude, es tuyo.
[ 04:16 ] Si usas Codex, que es el de ChatGPT, tiene su propio archivo de instrucciones.
[ 04:21 ] Se llama agents.md y vive en la carpeta .codex.
[ 04:24 ] Pega ahí las mismas normas.
[ 04:26 ] Ahora las dos leen lo mismo.
[ 04:28 ] Si a una se le acaba la cuota, la otra sigue justo donde lo dejó.
[ 04:31 ] Y si mañana cambias de IA, tu cerebro se muda contigo.
[ 04:35 ] Ya lo tienes montado.
[ 04:37 ] Ahora para que no se te pudra, tres reglas.
[ 04:39 ] Una, cada dato, en un solo sitio.
[ 04:41 ] Dos, lo que se acaba, se archiva.
[ 04:43 ] Crea una rama llamada archivo y mándalo ahí.
[ 04:45 ] Y tres, una vez al mes, pídele a Claude que lo revise.
[ 04:48 ] Que busque fichas viejas, rutas rotas y fichas demasiado largas.
[ 04:52 ] Ese prompt también lo tienes en la descripción.
[ 04:55 ] Una última cosa.
[ 04:57 ] Con esto te sobra hasta unas cien fichas.
[ 04:59 ] El mío ya tiene casi doscientas, y por eso le añadí un buscador.
[ 05:02 ] Es un programa pequeño que encuentra la ficha por palabras, sin leer ni el índice.
[ 05:07 ] No lo necesitas hoy.
[ 05:08 ] Pero si lo quieres, el prompt para que Claude te lo construya está en la descripción.
[ 05:13 ] Y hasta aquí el tutorial.
[ 05:15 ] Ya tienes tu cerebro.
[ 05:16 ] A partir de hoy no le explicas nada dos veces.
[ 05:19 ] Si te ha servido, suscríbete, porque este canal acaba de empezar y aquí voy a subir los tutoriales largos que no caben en TikTok.
[ 05:26 ] Cuéntame en los comentarios cómo te ha quedado o en qué paso te has atascado y te echo una mano.
[ 05:31 ] Y si quieres que enseñe el buscador en otro vídeo, dímelo ahí.
[ 05:34 ] Yo soy NotFound.
[ 05:35 ] Nos vemos en el siguiente.
