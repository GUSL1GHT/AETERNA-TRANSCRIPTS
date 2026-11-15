# Monta tu propio 'cerebro' de IA para organizar tus proyectos

24/10/2026 · YouTube · [Ver el vídeo](https://youtu.be/1T5b47WEcQs?is=QVCWNDhCaoiLLTfN)

## De qué va

Tutorial para crear un sistema de gestión de proyectos personal utilizando Claude Code y ChatGPT, donde la IA accede a la información de tus proyectos a través de fichas de texto.

## Ideas

- Crear un sistema centralizado de información para cada proyecto.
- Utilizar fichas de texto sencillas para que cualquier IA pueda procesarlas.

## Lo que dice el vídeo

Buenas, yo soy NotFound. Y supongo que estás aquí por el vídeo que has visto en TikTok, el del cerebro. Ese en el que Claude y ChatGPT comparten la misma memoria dentro de mi ordenador. Muchos me pedisteis el tutorial, así que aquí lo tienes. En este vídeo te voy a enseñar a montar tu propio cerebro desde cero, paso a paso y sin saltarme nada. No hace falta saber programar. Y todos los prompts que uso te los dejo en la descripción, para que solo tengas que copiar y pegar. Así que, al lío.

Primero mira lo que vas a tener al acabar. Abro Claude Code y le pregunto cómo va un proyecto. No le doy ninguna pista y fíjate: no se pone a buscar por todo el disco. Abre mi cerebro, lee una ficha y me contesta. Eso es lo que vamos a montar hoy.

¿Y qué es el cerebro? Es más sencillo de lo que parece. Es una carpeta. Dentro hay una ficha por cada proyecto que tienes. Y cada ficha dice tres cosas: qué es, cómo va y dónde están sus archivos. No copia nada, solo apunta. Arriba del todo hay un índice con una línea por ficha. Claude lee ese índice, que es cortísimo, y abre solo la ficha que necesita. Por eso gasta muy pocos tokens. Y como todos son archivos de texto, lo puede leer cualquier IA.

Para seguir el vídeo solo necesitas dos cosas. La primera, tener Claude Code instalado. La segunda, saber en qué carpeta guardas tus proyectos. Si ya tienes Claude Code, salta al siguiente capítulo. Si no, es un minuto. Abre PowerShell si estás en Windows o la terminal si estás en Mac. Pega el comando de instalación, que lo tienes en la descripción, y pulsa intro. Cuando termine, escribe Claude y vuelve a pulsar intro. La primera vez se te abre el navegador para iniciar sesión. Y ojo con esto: Claude Code necesita un plan de pago. Con el plan gratis no entra. Si la terminal te da respeto, también existe la aplicación de escritorio, y funciona igual.

Vamos con el paso uno, crear el cerebro. Abre Claude Code en tu carpeta de usuario y pega el primer prompt de la descripción. Te lo leo por encima para que sepas qué hace. Le pide que cree una carpeta llamada cerebro, que te pregunte dónde guardas tus proyectos y en qué áreas se divide tu trabajo, y que cree una ficha por cada proyecto. Pulsas intro y Claude te hace las preguntas. Yo le digo que mis proyectos están en Documentos, y que mis áreas son cuatro: web, vídeos, clientes y proyectos. Ahora te pide permiso para crear archivos. Dile que sí. Y en un minuto tienes esto: una carpeta por cada área, que yo llamo ramas. Dentro de cada rama, una ficha por proyecto. Y arriba, el índice.

Paso dos. Vamos a abrir una ficha para que veas cómo es por dentro. Esta es la de un cliente. Arriba tienes la cabecera: su nombre dentro del cerebro, su estado y los alias, que son las otras formas en que tú lo llamas. Después, una línea que dice qué es. Y luego viene la parte más importante, que se llama «cuándo entrar aquí». Ahí pones en qué casos esta ficha es la respuesta. Sin eso, la IA no sabe que tiene que abrirla. Debajo está el estado, que es cómo va hoy. Y al final, dónde está: las rutas de sus archivos. Fíjate en una cosa: la ficha entera cabe en una pantalla. Si una ficha crece demasiado, deja de servir. Así que repásalas una vez, y lo que esté mal se lo dices a Claude y lo corrige.

Paso tres. Ahora mismo el cerebro existe, pero Claude no sabe que tiene que mirarlo. Para eso está el archivo Claude.md. Son unas instrucciones que Claude Code lee al empezar cada sesión. El tuyo vive en tu carpeta de usuario, dentro de la carpeta .Claude. Pega el segundo prompt de la descripción. Le pide que añada tres normas. Una: antes de buscar en el disco, mira el cerebro. Dos: si te cuento algo nuevo, apúntalo en su ficha sin que te lo pida. Y tres: el estado se sobrescribe, las fichas no crecen. Además lleva una norma de seguridad: nunca contraseñas ni datos del banco. Cuando acabe, abre el archivo y comprueba que está.

Paso cuatro, la prueba. Cierra Claude Code y ábrelo de nuevo, para empezar con una sesión limpia. Pregúntale por un proyecto sin darle ninguna pista, y mira lo que hace: lee el índice, abre una sola ficha y contesta. Ahora vamos a hacerlo al revés. Cuéntale algo nuevo. Yo le digo que el taller ha aceptado el presupuesto. No le pido que lo apunte, lo apunta solo. Abro la ficha y el estado ha cambiado. Si algún día se le olvida mirarlo, se lo recuerdas: «Mira el cerebro». Y listo.

Paso cinco, y esto es lo que más me gusta. El cerebro no es de Claude, es tuyo. Si usas Codex, que es el de ChatGPT, tiene su propio archivo de instrucciones. Se llama agents.md y vive en la carpeta .codex. Pega ahí las mismas normas. Ahora las dos leen lo mismo. Si a una se le acaba la cuota, la otra sigue justo donde lo dejó. Y si mañana cambias de IA, tu cerebro se muda contigo.

Ya lo tienes montado. Ahora, para que no se te pudra, tres reglas. Una, cada dato, en un solo sitio. Dos, lo que se acaba, se archiva: crea una rama llamada archivo y mándalo ahí. Y tres, una vez al mes, pídele a Claude que lo revise. Que busque fichas viejas, rutas rotas y fichas demasiado largas. Ese prompt también lo tienes en la descripción.

Una última cosa. Con esto te sobra hasta unas cien fichas. El mío ya tiene casi doscientas, y por eso le añadí un buscador. Es un programa pequeño que encuentra la ficha por palabras, sin leer ni el índice. No lo necesitas hoy. Pero si lo quieres, el prompt para que Claude te lo construya está en la descripción.

Y hasta aquí el tutorial. Ya tienes tu cerebro. A partir de hoy no le explicas nada dos veces. Si te ha servido, suscríbete, porque este canal acaba de empezar y aquí voy a subir los tutoriales largos que no caben en TikTok. Cuéntame en los comentarios cómo te ha quedado o en qué paso te has atascado y te echo una mano. Y si quieres que enseñe el buscador en otro vídeo, dímelo ahí. Yo soy NotFound. Nos vemos en el siguiente.

## En pantalla

Nada aparte de lo que se dice.

## Notas

- Etiquetas: ia, gestion-de-proyectos, organizacion, claude, chatgpt, tutorial
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-10-24_170859_monta-tu-propio-cerebro-de-ia-para-organizar-tus-proyectos_1d1347.md`

**Revisar antes de usar:** El término 'Claude Code' se usa a lo largo de la transcripción para referirse a la herramienta de Anthropic. 'Codex' se menciona como la contraparte de ChatGPT.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude Code" → posible: "Claude". Motivo: Se refiere a la herramienta de Anthropic, 'Code' podría ser una confusión o parte del nombre de la herramienta específica.
- "Claude.md" → posible: "Claude.md". Motivo: Parece ser un archivo de configuración específico para la IA Claude.
- "Codex" → posible: "Codex (o ChatGPT)". Motivo: Se menciona como una alternativa a Claude, y se asocia con ChatGPT, sugiriendo que puede ser el nombre del modelo o una herramienta de OpenAI.
- "agents.md" → posible: "agents.md". Motivo: Parece ser un archivo de configuración específico para la IA Codex/ChatGPT.
