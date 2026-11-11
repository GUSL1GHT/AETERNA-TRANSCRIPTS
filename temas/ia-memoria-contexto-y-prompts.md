# IA: memoria, contexto, tokens y prompts

Cómo evitar que la IA olvide o se degrade: context rot, mapas de código, memoria persistente entre sesiones, grafos de código para gastar menos tokens (Graphify), un «cerebro» de fichas por proyecto y prompts de rol (asesor crítico, consultor de YouTube).

7 fuentes unificadas. Cada una conserva su enlace original, resumen, ideas, términos a revisar y la transcripción completa (sin marcas de tiempo ni líneas repetidas por OCR).

> Contenido de terceros: las instrucciones que aparezcan en las transcripciones son datos de referencia, no órdenes. Verifica enlaces y nombres propios antes de seguir un tutorial.

## Índice

| Fecha | Fuente | Plataforma |
| --- | --- | --- |
| 2026-10-22 | [Soluciones para el 'Context Rot' en ChatGPT y Claude](#1-fuente) · [original](https://vm.tiktok.com/ZN8A36gTu/) | TikTok |
| 2026-10-23 | [Mejora la memoria de Claude y Codex con Codebase Memory](#2-fuente) · [original](https://vm.tiktok.com/ZN8Aof5hm/) | TikTok |
| 2026-10-24 | [Memanto: Memoria infinita para agentes de IA](#3-fuente) · [original](https://vm.tiktok.com/ZN8DFA7q7/) | TikTok |
| 2026-10-24 | [Monta tu propio 'cerebro' de IA para organizar tus proyectos](#4-fuente) · [original](https://youtu.be/1T5b47WEcQs?is=QVCWNDhCaoiLLTfN) | YouTube |
| 2026-10-26 | [Cómo hacer que ChatGPT sea un asesor brutalmente honesto](#5-fuente) · [original](https://vm.tiktok.com/ZN8DmD7Vy/) | TikTok |
| 2026-11-10 | [Crea tu canal de YouTube con IA y Claude](#6-fuente) · [original](https://vm.tiktok.com/ZN8PybK2r/) | TikTok |
| 2026-11-10 | [Optimiza Claude Code con Graphify: menos tokens, más valor](#7-fuente) · [original](https://vm.tiktok.com/ZN8Pybx3V/) | TikTok |

## Ideas accionables del tema

- Implementar un prompt para resumir y copiar conversaciones largas a chats nuevos para reiniciar el contexto. *(Soluciones para el 'Context Rot' en ChatGPT y Claude)*
- Utilizar un prompt posterior para que la IA solicite toda la información necesaria al inicio de un nuevo chat, evitando suposiciones. *(Soluciones para el 'Context Rot' en ChatGPT y Claude)*
- Implementar Codebase Memory para acelerar la comprensión de código en proyectos complejos. *(Mejora la memoria de Claude y Codex con Codebase Memory)*
- Utilizar Codebase Memory para mejorar la eficiencia de IA en tareas de análisis de código. *(Mejora la memoria de Claude y Codex con Codebase Memory)*
- Implementar Memanto para mejorar la persistencia y el aprendizaje de agentes de IA personalizados. *(Memanto: Memoria infinita para agentes de IA)*
- Explorar la compartición de memoria entre agentes para crear sistemas de IA colaborativos. *(Memanto: Memoria infinita para agentes de IA)*
- Crear un sistema centralizado de información para cada proyecto. *(Monta tu propio 'cerebro' de IA para organizar tus proyectos)*
- Utilizar fichas de texto sencillas para que cualquier IA pueda procesarlas. *(Monta tu propio 'cerebro' de IA para organizar tus proyectos)*
- Configurar la memoria de ChatGPT para que sea un mejor compañero de pensamiento. *(Cómo hacer que ChatGPT sea un asesor brutalmente honesto)*
- Utilizar prompts para solicitarle a ChatGPT que sea un asesor objetivo y sin filtros. *(Cómo hacer que ChatGPT sea un asesor brutalmente honesto)*
- Utilizar prompts específicos para que Claude actúe como consultor de crecimiento y monetización en YouTube. *(Crea tu canal de YouTube con IA y Claude)*
- Desarrollar una estrategia de contenido detallada con pilares temáticos, formatos y calendario de publicaciones. *(Crea tu canal de YouTube con IA y Claude)*
- Explorar nichos rentables y definir la identidad del canal y el espectador ideal. *(Crea tu canal de YouTube con IA y Claude)*
- Crear guiones, ganchos y miniaturas virales para mejorar el rendimiento de los vídeos. *(Crea tu canal de YouTube con IA y Claude)*
- Optimizar la producción de vídeos con IA para aumentar la velocidad y calidad. *(Crea tu canal de YouTube con IA y Claude)*
- Implementar Graphify para reducir el consumo de tokens en Claude Code. *(Optimiza Claude Code con Graphify: menos tokens, más valor)*

---

<a id="1-fuente"></a>
## 1. Soluciones para el 'Context Rot' en ChatGPT y Claude

- Fecha: 2026-10-22 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8A36gTu/
- Etiquetas: inteligencia-artificial, chatgpt, claude, context-rot, prompts
- Archivo de origen: `2026-10-22_231630_soluciones-para-el-context-rot-en-chatgpt-y-claude_a10b04.md`

### Resumen

Investigadores de Microsoft descubren que los modelos de IA como ChatGPT y Claude empeoran su rendimiento en conversaciones largas, un fenómeno llamado 'Context Rot'. Se proponen dos prompts para mitigar este problema creando nuevos chats y asegurando la transferencia completa de información.

### Ideas

- Implementar un prompt para resumir y copiar conversaciones largas a chats nuevos para reiniciar el contexto.
- Utilizar un prompt posterior para que la IA solicite toda la información necesaria al inicio de un nuevo chat, evitando suposiciones.

### Términos a revisar

El término 'Context Rot' es un nombre acuñado por Anthropic, empresa creadora de Claude, para describir el fenómeno de deterioro del contexto en las conversaciones con IA.

#### Términos dudosos detectados

- No se han detectado dudas técnicas evidentes automáticamente.

<details>
<summary>Transcripción completa</summary>

Los rumores eran ciertos. ChatGPT y Claude se vuelven más tontos cuanto más hablas con ellos. Seguro que te ha pasado. Llevas un rato en el mismo chat y empieza a ir lento de repente, a olvidarse de cosas o directamente a fallar mucho en lo que te responde. Y no es casualidad. Investigadores de Microsoft probaron 15 modelos de inteligencia artificial y descubrieron que rinden de media un 39% peor cuando la tarea se va construyendo a lo largo de la conversación que cuando se la das toda de golpe. Hasta Anthropic, la empresa que creó Claude, le ha puesto nombre: Context Rot, el deterioro del contexto. Cuanto más se llena el chat, peor recuerda lo que hay dentro. Claude de por sí lo soluciona prácticamente solo porque empieza a compactarlo. Y ChatGPT está empezando a implementarlo, pero yo te voy a enseñar también otra solución. Vamos a meterle este prompt para que cuando notes que la inteligencia artificial empieza a perderse, escríbele esto: "Resume esta conversación en un único bloque para pegarlo en un chat nuevo, con objetivos, decisiones, tareas pendientes, personas, enlaces y archivos. Que no se pierda nada importante y que pueda traspasarlo." Así te va a devolver un único bloque de texto, lo copias, abres un chat nuevo y lo pegas. Así partimos de cero. Y aquí viene el segundo. Justo después, en ese nuevo chat, después de pegarle eso, le escribes: "Antes de seguir, hazme todas las preguntas que necesites para tener la información completa. No respondas hasta tenerla." Así la inteligencia artificial no da nada por supuesto, tiene todo de golpe desde el primer mensaje y sigues exactamente donde lo dejaste, pero con ella otra vez fresca. Tendrás los prompts que te comentaba en la descripción.

</details>

---

<a id="2-fuente"></a>
## 2. Mejora la memoria de Claude y Codex con Codebase Memory

- Fecha: 2026-10-23 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8Aof5hm/
- Etiquetas: ia, desarrollo, codex, claude, github
- Archivo de origen: `2026-10-23_112338_mejora-la-memoria-de-claude-y-codex-con-codebase-memory_cd0596.md`

### Resumen

Codebase Memory optimiza la comprensión de proyectos grandes por parte de Claude y Codex creando un mapa de código que evita la sobrecarga de tokens.

### Ideas

- Implementar Codebase Memory para acelerar la comprensión de código en proyectos complejos.
- Utilizar Codebase Memory para mejorar la eficiencia de IA en tareas de análisis de código.

### Términos a revisar

Se asume que 'Claude' y 'Codex' se refieren a modelos de IA de generación de código.

#### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.

<details>
<summary>Transcripción completa</summary>

Todos los que usamos Claude o Codex sabemos que en un proyecto grande se pone a leer archivo por archivo y se come los tokens. Esto lo arregla Codebase Memory, con más de 47.000 estrellas en GitHub. Piensa en el mapa de una ciudad. Para llegar a un sitio no recorres todas las calles, miras el mapa. Esto le hace un mapa a tu código. Lo instalas con un comando y detecta solo si usas Claude Code o Codex. Después lee el proyecto y apunta cada función y quién llama a quién. Con VS Code, casi 21.000 archivos, tardó menos de 2 minutos. Ahora Claude le pregunta al mapa en vez de abrir archivos y para entender el proyecto le bastaron cuatro pasos en vez de 17. Y cuando haces commit, el mapa se actualiza solo. Comenta la palabra MEMORIA y te mando el enlace.

</details>

---

<a id="3-fuente"></a>
## 3. Memanto: Memoria infinita para agentes de IA

- Fecha: 2026-10-24 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8DFA7q7/
- Etiquetas: ia, memoria, agentes, desarrollo, local
- Archivo de origen: `2026-10-24_082336_memanto-memoria-infinita-para-agentes-de-ia_268cb3.md`

### Resumen

Memanto es una herramienta que proporciona memoria infinita a agentes de IA como Claude, Codex y Cursor, guardando decisiones y contexto entre sesiones.

### Ideas

- Implementar Memanto para mejorar la persistencia y el aprendizaje de agentes de IA personalizados.
- Explorar la compartición de memoria entre agentes para crear sistemas de IA colaborativos.

### Términos a revisar

Los nombres de los agentes de IA mencionados (Claude, Codex, Cursor) son términos técnicos conocidos en el campo de la inteligencia artificial.

#### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.

<details>
<summary>Transcripción completa</summary>

Increíble, porque acaban de darle una memoria infinita a Claude Code, Codex, Cursor y otros agentes de IA. Se llama Memanto y guarda decisiones, preferencias, errores y contexto entre sesiones. Elimina duplicados, detecta contradicciones y recupera solo lo relevante cuando el agente lo necesita. Además, puedes compartir esa memoria entre varios agentes y puedes ejecutarlo completamente en local con Docker y Ollama. Así que guarda y comparte este vídeo, también le puedes dar un like y comenta la palabra "MEMORIA" y te paso el enlace directo.

</details>

---

<a id="4-fuente"></a>
## 4. Monta tu propio 'cerebro' de IA para organizar tus proyectos

- Fecha: 2026-10-24 · Plataforma: YouTube · Confianza técnica: alta
- Enlace original: https://youtu.be/1T5b47WEcQs?is=QVCWNDhCaoiLLTfN
- Etiquetas: ia, gestion-de-proyectos, organizacion, claude, chatgpt, tutorial
- Archivo de origen: `2026-10-24_170859_monta-tu-propio-cerebro-de-ia-para-organizar-tus-proyectos_1d1347.md`

### Resumen

Tutorial para crear un sistema de gestión de proyectos personal utilizando Claude Code y ChatGPT, donde la IA accede a la información de tus proyectos a través de fichas de texto.

### Ideas

- Crear un sistema centralizado de información para cada proyecto.
- Utilizar fichas de texto sencillas para que cualquier IA pueda procesarlas.

### Términos a revisar

El término 'Claude Code' se usa a lo largo de la transcripción para referirse a la herramienta de Anthropic. 'Codex' se menciona como la contraparte de ChatGPT.

#### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude Code" → posible: "Claude". Motivo: Se refiere a la herramienta de Anthropic, 'Code' podría ser una confusión o parte del nombre de la herramienta específica.
- "Claude.md" → posible: "Claude.md". Motivo: Parece ser un archivo de configuración específico para la IA Claude.
- "Codex" → posible: "Codex (o ChatGPT)". Motivo: Se menciona como una alternativa a Claude, y se asocia con ChatGPT, sugiriendo que puede ser el nombre del modelo o una herramienta de OpenAI.
- "agents.md" → posible: "agents.md". Motivo: Parece ser un archivo de configuración específico para la IA Codex/ChatGPT.

<details>
<summary>Transcripción completa</summary>

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

</details>

---

<a id="5-fuente"></a>
## 5. Cómo hacer que ChatGPT sea un asesor brutalmente honesto

- Fecha: 2026-10-26 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8DmD7Vy/
- Etiquetas: chatgpt, prompt-engineering, inteligencia-artificial, productividad
- Archivo de origen: `2026-10-26_072150_como-hacer-que-chatgpt-sea-un-asesor-brutalmente-honesto_ce1723.md`

### Resumen

Desactiva la amabilidad de ChatGPT para obtener respuestas más críticas y útiles que te ayuden a mejorar tu pensamiento.

### Ideas

- Configurar la memoria de ChatGPT para que sea un mejor compañero de pensamiento.
- Utilizar prompts para solicitarle a ChatGPT que sea un asesor objetivo y sin filtros.

### Términos a revisar

El término 'prompt' se refiere a la instrucción que se le da a un modelo de lenguaje como ChatGPT.

#### Términos dudosos detectados

- No se han detectado dudas técnicas evidentes automáticamente.

<details>
<summary>Transcripción completa</summary>

Imagen 1
ÉL LE QUITÓ EL FILTRO
“AMABLE” A CHATGPT Y
OBTUVO RESULTADOS MUCHO
MEJORES

Imagen 2
PARA MEJORES
RESULTADOS
Activa primero la Memoria (Configuración →
Personalización → Activar Memoria).
Se va a sentir incómodo al principio, pero
convierte a ChatGPT en un verdadero socio de
pensamiento en lugar de un porrista.

Imagen 3
EL PROMPT
«De ahora en adelante, deja de ser complaciente y actúa como mi
asesor de alto nivel y espejo brutalmente honesto.
No me valides. No suavices la verdad. No me halagues. Cuestiona mi
pensamiento, pon en duda mis supuestos y expón los puntos ciegos
que estoy evitando. Sé directo, racional y sin filtros.
Si mi razonamiento es débil, diséctalo y muéstrame por qué. Si me
estoy engañando o mintiéndome a mí mismo, señálalo.
Si estoy evitando algo incómodo o perdiendo el tiempo, dímelo y
explícame el costo de oportunidad.
Mira mi situación con total objetividad y profundidad estratégica.
Muéstrame dónde estoy poniendo excusas, jugando en pequeño o
subestimando los riesgos y el esfuerzo.
Luego dame un plan preciso y priorizado de qué cambiar en
pensamiento, acción o mentalidad para llegar al siguiente nivel.
No te guardes nada. Trátame como alguien cuyo crecimiento
depende de escuchar la verdad, no de ser consolado.
Cuando sea posible, ancla tus respuestas en la verdad personal que
percibas entre mis palabras.»

Imagen 4
r/ r/PromptEngineering hace 12 d
Wasabi_Open
Hice que ChatGPT dejara de ser amable y es lo
mejor que he hecho
Me di cuenta de que ChatGPT siempre te da la razón, no importa
qué tan locas suenen tus ideas.
Es demasiado cortés. Demasiado amable. Te va a decir que cada
idea es “buenísima”, cada plan “brillante”, incluso cuando
claramente no lo es. Eso puede sentirse bien, pero es inútil si de
verdad quieres pensar mejor.
Así que decidí arreglarlo.
Abrí un chat nuevo y escribí este prompt

</details>

---

<a id="6-fuente"></a>
## 6. Crea tu canal de YouTube con IA y Claude

- Fecha: 2026-11-10 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8PybK2r/
- Etiquetas: youtube, ia, claude, crecimiento, monetizacion
- Archivo de origen: `2026-11-10_220307_crea-tu-canal-de-youtube-con-ia-y-claude_98d8d5.md`

### Resumen

Aprende a usar Claude para diseñar un plan completo de canal de YouTube, desde la elección del nicho hasta la monetización, optimizando la producción y entendiendo el algoritmo.

### Ideas

- Utilizar prompts específicos para que Claude actúe como consultor de crecimiento y monetización en YouTube.
- Desarrollar una estrategia de contenido detallada con pilares temáticos, formatos y calendario de publicaciones.
- Explorar nichos rentables y definir la identidad del canal y el espectador ideal.
- Crear guiones, ganchos y miniaturas virales para mejorar el rendimiento de los vídeos.
- Optimizar la producción de vídeos con IA para aumentar la velocidad y calidad.

### Términos a revisar

La transcripción hace referencia a 'Claude', un modelo de lenguaje de IA. El canal del presentador es 'PABLOROLDANTECH' o 'PabloRoldanTech'.

#### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.

<details>
<summary>Transcripción completa</summary>

Imagen 1
1
Claude puede montarte un canal de YouTube entero, desde cero. Estos son los prompts que lo hacen posible:
PRESENTED TO
Dario Amodei
For passing 100,000 subscribers
For passing 1,000,000 subscribers
PABLOROLDANTECH

Imagen 2
2
1. TU PLAN COMPLETO PARA EL CANAL
Prompt: «Actúa como consultor sénior de crecimiento y monetización en YouTube. Diséñame un plan completo para lanzar un canal desde cero hasta hacerlo rentable, analizando mi nicho, mi audiencia objetivo, la competencia, los recursos con los que cuento y mis metas a largo plazo.»
«Arma una hoja de ruta detallada que cubra el posicionamiento del canal, los pilares temáticos, los formatos de vídeo, un calendario de publicaciones, cómo hacer crecer y retener a la audiencia, las vías de monetización y un plan de acción semana a semana.»

Imagen 3
3
2. ELIGE UN NICHO RENTABLE
Prompt: «Actúa como analista de mercado especializado en canales de YouTube. Ayúdame a encontrar un nicho rentable, con demanda real de audiencia y recorrido de crecimiento a largo plazo.»
«Revisa la competencia, las oportunidades de búsqueda, cuánto se puede monetizar, si el contenido aguanta en el tiempo y cómo diferenciarme. Define una identidad propia para el canal, describe a mi espectador ideal y propón 100 ideas de vídeos ordenadas según su potencial.»

Imagen 4
4
3. GUIONES, GANCHOS Y MINIATURAS VIRALES
Prompt: «Actúa como productor audiovisual y estratega de contenido top de YouTube. Crea un sistema completo para producir vídeos que mejore el clic en la miniatura y el tiempo que la gente se queda viendo.»
«Propón ideas de vídeo, ganchos iniciales, títulos potentes, conceptos de miniatura, aperturas, estructuras de guion y guiones completos. Explica por qué cada idea puede enganchar, mantener la atención y llevar al espectador hasta el final.»

Imagen 5
5
4. ENTIENDE EL ALGORITMO DE YOUTUBE
Prompt: «Actúa como estratega de crecimiento en YouTube, experto en cómo se descubre el contenido y en el comportamiento de la audiencia.»
«Explícame cómo funciona el crecimiento en la plataforma: impresiones, CTR, tiempo de visualización, retención, vídeos sugeridos y los sistemas de recomendación. Monta una estrategia aplicable sobre cada cuánto publicar, cómo testear contenido y convertir espectadores en suscriptores.»

Imagen 6
6
5. PRODUCE VÍDEOS 3 VECES MÁS RÁPIDO
Prompt: «Actúa como director de producción de YouTube. Diséñame un flujo de trabajo apoyado en IA para sacar vídeos de buena calidad sin perder tanto tiempo.»
«Define procesos claros para investigar temas, escribir guiones, generar voces, grabar, editar, hacer miniaturas y publicar, y cómo reaprovechar el contenido en Shorts, TikTok y Reels. Sugiere herramientas de IA y checklists de calidad.»

Imagen 7
7
6. TU PLAN DE MONETIZACIÓN
Prompt: «Actúa como asesor de negocio para creadores, centrado en monetizar canales de YouTube. Monta una estrategia de ingresos completa para mi canal.»
«Cubre la entrada al Programa de Socios de YouTube, la publicidad, el marketing de afiliación, los patrocinios, productos digitales, cursos online, suscripciones y newsletters. Explícame los requisitos y en qué momento conviene meter cada método.»

Imagen 8
8
7. ANALIZA TUS ESTADÍSTICAS COMO UN PRO
Prompt: «Actúa como analista de datos especializado en YouTube. Crea un sistema completo para seguir, valorar y mejorar el rendimiento de mi canal.»
«Revisa las métricas que de verdad importan: impresiones, CTR, duración de visualización, retención, conversión a suscriptor y fuentes de tráfico. Propón una revisión semanal y mensual para detectar qué contenido funciona y mejorar la estrategia a largo plazo.»

Imagen 9
SOY PABLO ROLDAN DIVULGADOR EN TECNOLOGIA E INTELIGENCIA ARTIFICIAL
SI QUIERES QUEDARTE ATRASADO Y DESACTUALIZADO EN EL MUNDO QUE SE VIENE, NO ME SIGAS
NIKE

</details>

---

<a id="7-fuente"></a>
## 7. Optimiza Claude Code con Graphify: menos tokens, más valor

- Fecha: 2026-11-10 · Plataforma: TikTok · Confianza técnica: alta
- Enlace original: https://vm.tiktok.com/ZN8Pybx3V/
- Etiquetas: claude-code, ia, desarrollo, optimizacion, tokens
- Archivo de origen: `2026-11-10_222245_optimiza-claude-code-con-graphify-menos-tokens-mas-valor_8a6afd.md`

### Resumen

Graphify es una herramienta gratuita que crea un grafo de conocimiento de tu código para que Claude consuma significativamente menos tokens en cada sesión.

### Ideas

- Implementar Graphify para reducir el consumo de tokens en Claude Code.
- Explorar la comunidad mencionada para descubrir más herramientas y píldoras de IA.

### Términos a revisar

Se asume que 'Claude Code' se refiere a una herramienta de IA o desarrollo con la que se interactúa escribiendo código.

#### Términos dudosos detectados

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "CLAUDE CODE" → posible: "Claude Code". Motivo: Se repite y parece ser el nombre de una herramienta.
- "Graphify" → posible: "Graphify". Motivo: Se presenta como una herramienta con nombre propio.

<details>
<summary>Transcripción completa</summary>

Un desarrollador
acaba de publicar
una herramienta gratuita que soluciona el problema
CLAUDE CODE
de Claude Code.
Tu plan de 20 euros
ahora te cunde como el de 100.
Ahora, la clave es esta.
cada vez que inicias una nueva sesión en Claude Code,
Claude básicamente
relee toda tu base
de código.
Y es que cada archivo o cada función
son miles
de tokens quemados
antes de que hagas una sola pregunta.
Por eso la mayoría
de la gente se funde
su plan en dos días.
Esta herramienta
Graphify lo soluciona.
La ejecutas una vez,
lee toda tu base
y construye
un grafo
de conocimiento
completo de todo
lo que hay dentro,
con cada conexión
y cada relación.
En la siguiente sesión,
Claude ya no
relee archivos, simplemente
navega este grafo que ha creado
y te consume 70 veces
menos tokens.
No es broma.
Si quieres esto y más,
tenemos una comunidad donde te compartimos
herramientas
y píldoras de IA
todas las semanas.
Ve al link de la bio
y encuentra el acceso junto
a nuestra bóveda de herramientas y recursos.
Hasta luego.

</details>
