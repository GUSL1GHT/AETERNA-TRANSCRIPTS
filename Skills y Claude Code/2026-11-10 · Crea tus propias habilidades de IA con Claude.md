# Crea tus propias habilidades de IA con Claude

10/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8PyVWsV/)

## De qué va

Aprende a crear y activar habilidades personalizadas en Claude para predecir resultados deportivos o cualquier otra tarea.

## Ideas

- Utiliza la habilidad Skill Creator para automatizar la predicción de resultados deportivos basándote en datos específicos.
- Diseña tus propias habilidades en Claude para analizar información compleja y generar resúmenes o predicciones personalizadas.

## Lo que dice el vídeo

México 2 - Sudáfrica 0. Predice resultados con IA. Con esta skill de Claude acerté el resultado del partido México y Sudáfrica. Te muestro cómo hacerlo muy fácil y rápido. Primero entras a Claude y vas al menú de Customize. Entras a Habilidades y confirmas que la skill llamada Skill Creator esté descargada y activa. Si no lo está, la activas con un solo clic.

Ahora, abres un chat nuevo y simplemente le pides a Claude que la cree con las indicaciones que necesites. Yo, por ejemplo, le voy a pedir esto: «Crea una skill que analice los partidos del mundial 2026, que use el ranking fifa, historial entre selecciones, estadísticas relevantes, forma reciente para darte un marcador probable y además usa el sistema matemático de predicción de Joachim Klemment que predijo el ganador de los 3 últimos mundiales. Dame los resultados de los partidos cuando te los pida.»

Ya con este listo, solo le preguntas quién gana determinado partido. Claude lee el SKILL.md del skill creator para entender cómo crear skills correctamente, busca en la web y crea la skill completa. Dice: «La skill está lista. Ahora hagamos una prueba en vivo — dime un partido del Mundial 2026 y te doy el análisis completo usando el método.» Después, con el ranking FIFA actualizado al 11 de junio de 2026, actualiza el archivo de referencia con los datos reales y presenta la skill.

La skill Mundial 2026 Predictor está lista. Método Klement integrado: las 5 variables del modelo econométrico que predijo los 3 últimos campeones: PIB per cápita, población (escala logarítmica), temperatura (óptimo 14°C), ranking FIFA y ventaja de sede. Datos reales actualizados, con el ranking FIFA oficial del 11 de junio de 2026: Argentina, Francia, Brasil, Marruecos #7 (gran sorpresa) y Países Bajos #8. Protocolo de análisis: para cada partido calcula un Índice Klement de Partido (IKP) combinando las variables estructurales con la forma reciente de los últimos 6 juegos, luego lo convierte a probabilidades y marcador estimado con alternativas. Pronóstico Klement 2026: campeón Países Bajos (final vs Portugal). ¿Quieres que analice un partido ahora? Puede ser el partido inaugural (México vs Sudáfrica del 11 de junio), Argentina, Colombia, o cualquier cruce que te interese.

La skill te da el marcador, la probabilidad y el análisis. Partido inaugural del Mundial, 11 de junio a las 19:00 (hora de México), en el Estadio Azteca, CDMX: México (FIFA #13, sede) contra Sudáfrica (FIFA #61), marcador probable 2 - 0. Ventaja Klement para México (sede). Historial en mundiales: 2010, 1-1. Altitud de CDMX: 2,240 m, ventaja local. Probabilidades: 62 % México, 22 % empate, 16 % Sudáfrica. México gana: juega en casa, ranking superior, altitud a su favor y buena forma reciente. Sudáfrica no llega al Mundial desde Qatar 2022. Ochoa se convierte en el primer jugador en disputar 6 Mundiales. México tiene marca perfecta contra selecciones asiáticas/africanas en grupos. Confianza alta.

Otro ejemplo, el 11 de junio a las 20:00 (hora de México), en el Estadio Guadalajara (Akron): Corea del Sur (FIFA #22) contra República Checa (FIFA #44), marcador probable 1 - 1. Ventaja para Corea (ranking). Sin historial en mundiales; en amistosos, Checa 1-2 Corea (2016). Probabilidades: 44 % Corea, 30 % empate, 26 % Checa. Empate probable: rivales parejos; Corea llega mejor en ranking, pero Checa es sólida y determinantemente organizada, partido de bajo margen. El estadio Guadalajara hace su debut mundialista; Guadalajara será la 2.ª ciudad en albergar 3 Mundiales (1970, 1986 y 2026), aunque en estadio diferente. Confianza media.

No estás adivinando el futuro ni tendrás 100 % de precisión, pero sí suficiente información para tomar mejores decisiones en todas las quinielas que tengas con tus amigos. Si quieres aprender más de IA y de cómo usarla en el mundial, entra ya a platzi.com.

## En pantalla

- Interfaz de Claude (plan gratuito): «¡Bienvenido, Dani CN!», menú Chat, Cowork, Code, New chat, Projects, Artifacts, Customize; modelos Sonnet 4.6 Bajo y Sonnet 4.6 Medio.
- Lista de habilidades (Anthropic) con usos: `/mcp-builder` 551.7K, `/theme-factory` 539.6K, `/brand-guidelines` 493.7K, `/doc-coauthoring` 478.1K, `/internal-comms` 369.8K, `/algorithmic-art` 280.0K, `/slack-gif-creator` 247.0K, `/learn` 214.7K, `/skill-creator` 93.7K.
- Skill Creator (agregado por Anthropic, actividad: comando slash + auto): carpeta `skill-creator` con `SKILL.md`, `agents`, `eval-viewer`, `scripts`, `references`, `LICENSE.TXT`; usa el script `/eval-viewer/generate_review.py`; proceso: decidir qué hace, escribir borrador, crear prompts de prueba, evaluar resultados, reescribir y repetir.
- Tabla «Men's World Ranking - Top 10» (datos ilustrativos): 1 Argentina, 2 France, 3 Brazil, 4 England, 5 Belgium, 6 Croatia, 7 Netherlands, 8 Portugal, 9 Spain, 10 USA (puntos mostrados: 357.0, 3500, 3313, 3302, 3013, 3050, 3070, 2083, 2953, 2422, 2663, 2871, 2433, 280, 2008, 258, 2056, 226, 105, 170).
- Skill creada: `mundial-2026-predictor`.
- Descripción de `/slack-gif-creator`: conocimiento y utilidades para crear GIFs animados optimizados para Slack. En las tarjetas de partido aparece H2H (historial) de mundiales y de amistosos.

## Notas

- Etiquetas: ia, claude, habilidades, personalizacion, prediccion
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-10_222627_crea-tus-propias-habilidades-de-ia-con-claude_6bd962.md`

**Revisar antes de usar:** La transcripción menciona varios nombres de 'skills' o herramientas dentro de la plataforma Claude, como 'Skill Creator', 'MCP Builder', 'Theme Factory', etc. Se asume que son nombres propios de la plataforma.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "mcp-builder" → posible: "MCP Builder". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "theme-factory" → posible: "Theme Factory". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "brand-guidelines" → posible: "Brand Guidelines". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "doc-coauthoring" → posible: "Doc Co-authoring". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "internal-comms" → posible: "Internal Comms". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "algorithmic-art" → posible: "Algorithmic Art". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "slack-gif-creator" → posible: "Slack GIF Creator". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "learn" → posible: "Learn". Motivo: Probable nombre de una habilidad o herramienta dentro de Claude.
- "skill-creator" → posible: "Skill Creator". Motivo: Nombre de una habilidad dentro de Claude mencionada explícitamente.
