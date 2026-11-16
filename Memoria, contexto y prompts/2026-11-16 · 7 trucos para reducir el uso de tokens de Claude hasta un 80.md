# 7 trucos para reducir el uso de tokens de Claude hasta un 80

16/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8aeYu9D/)

## De qué va

Este vídeo presenta siete trucos para optimizar el uso de tokens en Claude, reduciendo el gasto y mejorando la eficiencia de las interacciones.

## Ideas

- Utilizar prompts específicos para que Claude responda de forma concisa.
- Convertir el código en un mapa estructurado con Code Review Graph.
- Seleccionar el modelo de Claude (Opus, Sonnet, Haiku) según la complejidad de la tarea.
- Evitar subir PDFs directamente a Claude; procesarlos primero con ChatGPT.

## Lo que dice el vídeo

7 Trucos Para Bajar El Uso De Tokens De Claude Un 80%
Que Claude No Llegue Al Límite Tan Rápido

Truco #1
EL Método "Cavernícola"
Haz que Claude hable como un cavernícola.
Sin relleno. Sin rodeos. Respuestas directas.
Usa este prompt exacto
"A partir de ahora, elimina todas las palabras de
relleno. Nada de 'el', 'la', 'es', 'son'. Solo
respuesta directa. Usa frases cortas de 3 a 6 palabras.
Ejecuta las herramientas primero, muestra el resultado
y detente. No narres. Ejemplo: en vez de 'La solución
es usar async', di 'Usa async'."
Esto ahorra ~40% de tokens por respuesta.

¿Qué cambia?
Mira La Diferencia:
X N CAVERNÍCOLA:
"¡Con gusto te ayudo con eso! El mejor enfoque
sería implementar una función async. También
querrás asegurarte de usar un manejo de errores
adecuado..."
[127 tokens]
✓ N CAVERNÍCOLA:
"Usa función async. Agrega bloque try-catch.
Maneja errores con .catch() o await."
[32 tokens]
Misma info, pero 75% menos tokens.

Truco #2
Usa Code Review Graph
Deja de hacer que Claude lea todo tu código una
y otra vez.
Míralo aquí:
/github.com/tirth8205/code-review-graph
Público
Convierte tu código en un mapa estructurado.
Claude ve la estructura, no cada línea.
Ahorra 60-70% de tokens en proyectos de código.

Truco #3
¡No Uses Opus Para Todo!
Opus gasta 5x más tokens que Sonnet.
A SONNET PARA:
•Implementar código • Análisis de datos
•Preguntas generales • Resúmenes de documentos
A OPUS PARA:
•Decisiones complejas de arquitectura
•Bugs críticos • Escritura con matices
A HAIKU PARA:
•Respuestas rápidas • Tareas no lógicas
•Tareas diarias simples

Truco #4
Nunca Subas PDFs
Directo A Claude
Los PDFs pueden consumir 80% de tu sesión.
Así que haz esto en su lugar:
1 Sube el PDF a ChatGPT primero
2 Usa este prompt:
"Lee este documento a fondo. Elimina todas las palabras de
relleno, el texto extra y el formato. Extrae la
información clave. Devuélvela como texto plano condensado
con los puntos clave."
3 Copia la respuesta de ChatGPT
4 Pégala en Claude

Truco #5
El Truco Del Horario
Tu ventana de 5 horas empieza con tu PRIMER mensaje. Así que sigue este truco:
// Envía un mensaje básico 2-3 horas antes de que de verdad necesites a Claude. Por ejemplo:
6:00 AM - Envía algo como "hola"
9:00 AM - Empieza el trabajo real
11:00 AM - Tu ventana se reinicia a mitad del trabajo
* Asignación nueva justo cuando más la necesitas.

Truco #6
Crea Una Skill "Compact"
* Los chats largos gastan tokens sin parar.
* Pero cambiar de chat = perder contexto.
Usa este prompt exacto
"Crea esta skill: cuando diga 'COMPACT', resume toda nuestra conversación en 5-7 viñetas clave con todo el contexto crítico, decisiones y fragmentos de código. Dale formato para copiar y pegar fácil en un chat nuevo"
* Esto crea una Skill de Conversación Compacta.

Truco #7
Evita Las Horas Pico
Horas pico = gasto de tokens más rápido.
ORES HORARIOS:
•Entre semana 5am-11am PT
•O sea, 1pm-7pm GMT
JORES HORAS PARA USAR CLAUDE:
•Fines de semana
•Noches entre semana
•Madrugada / muy temprano

IA
Nunca vas a volver a ver esta cuenta, a menos que nos sigas @esmejorconia

## En pantalla

- 7 Trucos Para Bajar
- El Uso De Tokens
- De Claude Un 80%
- Que Claude No Llegue Al Límite Tan Rápido
- >IA Es Mejor con IA
- @esmejorconia
- Desliza
- Truco #1
- EL Método "Cavernícola"
- Haz que Claude hable como un cavernícola.
- Sin relleno. Sin rodeos. Respuestas directas.
- Usa este prompt exacto
- "A partir de ahora, elimina todas las palabras de
- relleno. Nada de 'el', 'la', 'es', 'son'. Solo
- respuesta directa. Usa frases cortas de 3 a 6 palabras.
- Ejecuta las herramientas primero, muestra el resultado
- y detente. No narres. Ejemplo: en vez de 'La solución
- es usar async', di 'Usa async'."
- Esto ahorra ~40% de tokens por respuesta.
- ¿Qué cambia?
- Mira La Diferencia:
- X N CAVERNÍCOLA:
- "¡Con gusto te ayudo con eso! El mejor enfoque
- sería implementar una función async. También
- querrás asegurarte de usar un manejo de errores
- adecuado..."
- [127 tokens]
- ✓ N CAVERNÍCOLA:
- "Usa función async. Agrega bloque try-catch.
- Maneja errores con .catch() o await."
- [32 tokens]
- Misma info, pero 75% menos tokens.
- Truco #2
- Usa Code Review Graph
- Deja de hacer que Claude lea todo tu código una
- y otra vez.
- Míralo aquí:
- `/github.com/tirth8205/code-review-graph`
- Público
- Convierte tu código en un mapa estructurado.
- Claude ve la estructura, no cada línea.
- Ahorra 60-70% de tokens en proyectos de código.
- Truco #3
- ¡No Uses Opus Para Todo!
- Opus gasta 5x más tokens que Sonnet.
- A SONNET PARA:
- •Implementar código • Análisis de datos
- •Preguntas generales • Resúmenes de documentos
- A OPUS PARA:
- •Decisiones complejas de arquitectura
- •Bugs críticos • Escritura con matices
- A HAIKU PARA:
- •Respuestas rápidas • Tareas no lógicas
- •Tareas diarias simples
- Truco #4
- Nunca Subas PDFs
- Directo A Claude
- Los PDFs pueden consumir 80% de tu sesión.
- Así que haz esto en su lugar:
- 1 Sube el PDF a ChatGPT primero
- 2 Usa este prompt:
- "Lee este documento a fondo. Elimina todas las palabras de
- relleno, el texto extra y el formato. Extrae la
- información clave. Devuélvela como texto plano condensado
- con los puntos clave."
- 3 Copia la respuesta de ChatGPT
- 4 Pégala en Claude
- Truco #5
- El Truco Del Horario
- Tu ventana de 5 horas empieza con tu PRIMER mensaje. Así que sigue este truco:
- // Envía un mensaje básico 2-3 horas antes de que de verdad necesites a Claude. Por ejemplo:
- 6:00 AM - Envía algo como "hola"
- 9:00 AM - Empieza el trabajo real
- 11:00 AM - Tu ventana se reinicia a mitad del trabajo
- * Asignación nueva justo cuando más la necesitas.
- Truco #6
- Crea Una Skill "Compact"
- * Los chats largos gastan tokens sin parar.
- * Pero cambiar de chat = perder contexto.
- Usa este prompt exacto
- "Crea esta skill: cuando diga 'COMPACT', resume toda nuestra conversación en 5-7 viñetas clave con todo el contexto crítico, decisiones y fragmentos de código. Dale formato para copiar y pegar fácil en un chat nuevo"
- * Esto crea una Skill de Conversación Compacta.
- Truco #7
- Evita Las Horas Pico
- Horas pico = gasto de tokens más rápido.
- ORES HORARIOS:
- •Entre semana 5am-11am PT
- •O sea, 1pm-7pm GMT
- JORES HORAS PARA USAR CLAUDE:
- •Fines de semana
- •Noches entre semana
- •Madrugada / muy temprano
- >IA
- Nunca vas a volver a ver esta cuenta, a menos que nos sigas @esmejorconia

## Notas

- Etiquetas: claude, tokens, ia, prompt engineering, ahorro
- Calidad de la transcripción automática: alta
- Procesado por AETERNA en segundo plano con gemini-2.5-flash.
