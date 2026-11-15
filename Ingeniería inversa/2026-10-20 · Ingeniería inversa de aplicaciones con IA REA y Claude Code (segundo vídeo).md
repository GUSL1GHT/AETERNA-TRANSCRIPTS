# Ingeniería inversa de aplicaciones con IA: REA y Claude Code (segundo vídeo)

20/10/2026 · YouTube · [Ver el vídeo](https://www.youtube.com/watch?v=4YkdCVzHpbc)

## De qué va

Explora cómo REA y la IA como Claude Code permiten la ingeniería inversa de aplicaciones para análisis y aprendizaje, sin necesidad de saber programar.

## Ideas

- Utilizar REA y Claude Code para analizar el funcionamiento interno de aplicaciones existentes.
- Recrear aplicaciones para uso propio y optimizar flujos de trabajo personales o empresariales.

## Lo que dice el vídeo

Imagina por un momento poder recrear cualquier aplicación sin tener su código y sin saber programar. Eso es lo que promete REA, reverse engineer anything, el repo de GitHub del momento, esta semana, que ya ha acumulado más de 130.000 estrellas en GitHub. Y en redes sociales ya se empieza a leer de todo: que el software está acabado, que pronto todo será gratis y de código abierto. Tranquilidad. Hoy te explico qué es de verdad. Lo instalaremos juntos en Claude Code, paso a paso, y trataremos de replicar una app en directo. Y al final te cuento qué significa esto para tu negocio, si tienes uno o quieres montarlo, no donde te lo cuentan en redes sociales, porque ahí es donde está lo interesante.

¿Sabes cuando pruebas un plato en un restaurante y en casa intentas sacar la receta para hacerlo tú porque te ha gustado mucho? Básicamente eso es ingeniería inversa: del resultado a la receta. La aplicación que instalas en tu ordenador o móvil ya viene, entre comillas, cocinada: ceros y unos. El código de sus programadores se convierte en ceros y unos para que tu ordenador pueda leerlo. La receta no viene en una caja bonita. Para leer esos ceros y unos existen herramientas desde hace muchísimos años, como por ejemplo IDA, desde los años 90; Ghidra, que publicó la NSA, la Agencia de Seguridad de Estados Unidos, en 2019; y Hopper, en Mac. Pero estas aplicaciones eran cosa de expertos en ciberseguridad y de personas tremendamente técnicas.

REA es un MCP, que básicamente es un enchufe entre tu agente de inteligencia artificial, como por ejemplo Claude Code, Codex o incluso Cursor, e IDA, Ghidra, Hopper y esas herramientas. Tú le pides en lenguaje normal que te replique una aplicación concreta y el agente recibe tres cosas. Una, una descripción de lo que hace el programa por dentro, que se llama pseudocódigo; no es el código original, esto es importante que lo entendamos. Dos, las pruebas de dónde lo ha sacado. Y tres, lo que todavía no sabe o le falta por aprender. Con eso escribe su propia versión, la prueba y vuelve a preguntar si es lo que le gusta, hasta que funciona. Básicamente lo que estamos haciendo es iterar, en este caso con Claude Code, hasta tener la aplicación replicada perfecta. Y no solo funciona para aplicaciones de ordenador, también para aplicaciones hechas con tecnología web, como Notion o Slack, para recrear páginas web y aplicaciones de Android, por ponerte un ejemplo, entre otras muchas más cosas. Literalmente se puede recrear cualquier cosa.

Pero mucho ojo con dos cosas que quiero que todo el mundo tenga en cuenta. Uno: REA, este repositorio, no inventa nada nuevo, ninguna técnica novedosa. Junta herramientas que ya existían, y el proyecto está en GitHub desde abril. Lo nuevo ahora es que se ha hecho viral. Y dos: inspirarte de cómo funciona algo para hacer tu propia versión es una cosa; copiar su código o saltarte su licencia es otra muy distinta, y no. El propio proyecto lo dice: es para analizar software tuyo o que tienes permiso para examinar. REA is for lawful research, education, interoperability, software preservation, and analysis of software you own or are authorized to examine. Para investigar y para aprender. Las leyes cambian según el país en el que te encuentras y yo no soy abogado. Si vas a vender algo clonado con ingeniería inversa, asegúrate bien antes.

La realidad es que la oportunidad no está en vender cosas recreadas, sino en recrear para ti y ahorrar tiempo, además de poder integrarlo en ecosistemas que puedes crear y vender a empresas. De cómo empezar a vender diagnósticos a empresas hablo en este vídeo que te voy a dejar justo por aquí arriba: Claude hace estos diagnósticos y yo los vendo a $72/hora. Ábrelo en el navegador y cuando termines de ver este vídeo, ve a estudiarlo, te va a gustar un montón. Y si este tipo de contenido te ayuda, suscríbete a mi canal de YouTube y activa la campanita, ya que este es el único canal de habla hispana centrado en mostrar casos prácticos reales de IA aplicada a negocio. Aprovecha todo el material y te agradezco mucho la suscripción.

Muy bien, lo primero que vamos a hacer es irnos a Google y buscar GitHub REA, y vamos a llegar al repositorio de Morluto, que es el desarrollador que ha lanzado esto. Ya te digo, no es nuevo, está desde abril de 2026, pero si bajamos aquí abajo, justo aquí tenemos una gráfica del crecimiento de las estrellas, de la valoración del repositorio, y a final de 2026 ha pegado un boom. ¿A qué se debe? A que la gente se está dando cuenta de que el SaaS, el software en general, está cada vez más acabado, y ahora cualquier persona con unos conocimientos intermedios en inteligencia artificial y tecnología puede literalmente replicar cualquier software, que es lo que vamos a hacer ahora.

¿Cómo lo utilizamos? Muy fácil. Antes de abrir Visual Studio Code, voy a copiar la URL del repositorio de GitHub. Una vez dentro de Visual Studio Code, voy a abrir mi Claude Code. Antes, arriba a la izquierda en Archivo, Open Folder, abrir nueva carpeta, y voy a crearme en mi universo una nueva carpeta que se va a llamar Test REA, para probarlo y ver qué tal funciona delante de todos vosotros. Este repositorio, hasta hace unos días, nadie sabía absolutamente nada de él; ahora se ha hecho superviral. Yo he utilizado anteriormente ingeniería inversa para mi trabajo, para el departamento de I+D de Visual Project, que es a día de hoy donde tengo más trabajo. Si no entiendes Visual Studio Code o Claude Code, te voy a dejar justo por aquí arriba un curso completo y gratuito que subí a mi canal de YouTube hace unos cuantos días, en el que te explico paso a paso cómo utilizar Claude Code de manera profesional usando Visual Studio Code, que es exactamente lo que estás viendo ahora en pantalla.

A mi Claude Code le voy a decir simplemente: instala este repo y vamos a probar qué tal funciona y qué tal replica apps. Le pego el enlace de GitHub, se lo envío y esperamos unos segunditos a que termine de instalarlo. Muy bien, ya ha terminado de clonar todo el repositorio; ya lo tenemos en local, todo listo para empezar a clonar o a estudiar posibles aplicaciones. De hecho, como estoy utilizando el modelo Opus 5.5 en el modo extra high, que es como ir a tope, se había puesto directamente ya a clonar la propia aplicación de Claude. Es una locura. Yo estoy utilizando Claude en Visual Studio Code, pero también tengo la aplicación de Claude en el escritorio y se había puesto a clonarla, sin consultar a nadie, por hacer una primera prueba. Le he dicho: ¿pero qué estás haciendo? ¿Estás clonando una app? Me dice que instaló e intentó conectarla a Claude Code, e hizo una prueba de análisis sobre Claude.app, que la eligió él sin preguntarme. Le he dicho que pare y que vamos ahora a replicar OBS, y es lo que está haciendo ahora. OBS es la herramienta que estoy utilizando para grabar este vídeo. Es una herramienta open source que está muy bien, pero la realidad es que se puede optimizar mucho más.

De esta manera es como realmente se le saca el máximo provecho a la ingeniería inversa dentro del sector de la tecnología, y no es para copiar, clonar y vender exactamente lo mismo por menor precio. De hecho, eso, como hemos comentado antes, puede llegar a ser ilegal, depende del país. La oportunidad está en herramientas que tú utilices en tu día a día y que estés pagando o que sean gratuitas: poder analizarlas, recrearlas y adaptarlas al 100 % a tu flujo de trabajo. Y esto también es lo que se puede llegar a vender y a monetizar, que a fin de cuentas es donde está la oportunidad. Ser un fanático de la inteligencia artificial y hacer muchas cosas, pero no facturar nada, está bien si quieres tener la IA como hobby, pero bajo mi punto de vista lo ideal es utilizar todo este conocimiento y tratar de monetizarlo lo antes posible. De todo eso también te estoy hablando y formando en mi canal de YouTube, por lo que si no lo has hecho todavía, suscríbete, porque estos días se viene contenido muy interesante. Soy Juanpe Navarro, CEO y fundador de Divisual Project, y ha sido un placer aportar mi granito de arena a tu conocimiento. Chao, chao.

## En pantalla

- Repositorio: `morluto/rea` (GitHub - Morluto/REA, Oct 2026); texto del proyecto: «REA is for lawful research, education, interoperability, software preservation, and analysis of software you own or are authorized to examine.»
- Herramientas de ingeniería inversa: IDA (años 90), Ghidra (NSA, 2019), Hopper (Mac); REA es un MCP para Claude Code, Codex, Cursor.
- Más de 130.000 estrellas; en GitHub desde abril (2026).
- Ejemplos de apps replicables: Notion, Slack, páginas web, apps de Android.
- Vídeo recomendado: «Vende esto por $72/hora. Claude hace estos diagnósticos y yo los vendo a $72/hora.» (Juan Pe Navarro | IA y Automatización).
- Carpeta de prueba: Test REA; modelo Opus 5.5 en modo extra high; pruebas con Claude.app y OBS.

## Notas

- Etiquetas: ingenieria-inversa, ia, rea, claude-code, programacion
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-10-20_132326_ingenieria-inversa-de-aplicaciones-con-ia-rea-y-claude-code_8de357.md`

**Revisar antes de usar:** Los nombres de herramientas como IDA, Ghidra y Hopper son correctos. La mención de 'Claude Code' parece referirse al uso de Claude con capacidades de codificación, no a un producto separado. Las fechas de 2026 parecen ser errores tipográficos.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude Code" → posible: "Claude". Motivo: Claude Code parece ser una mención específica o error, el agente principal es Claude.
- "GitHub - Oct 2026" → posible: "Octubre 2024". Motivo: La fecha de 2026 parece ser un error tipográfico, ya que se menciona que el proyecto lleva en GitHub desde abril y el crecimiento viral es reciente. Considerando el contexto temporal, 2024 es más probable.
- "GitHub - Morluto/REA - Oct 2026" → posible: "GitHub - Morluto/REA - Octubre 2024". Motivo: Similar al anterior, la fecha de 2026 es un error.
- "2026" → posible: "2024". Motivo: Múltiples menciones de 2026 parecen ser errores tipográficos, el contexto sugiere 2024.
