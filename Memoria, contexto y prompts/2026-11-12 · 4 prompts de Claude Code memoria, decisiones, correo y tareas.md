# 4 prompts de Claude Code: memoria, decisiones, correo y tareas

12/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8P7mCmE/)

## De qué va

Carrusel de @esmejorconia con cuatro prompts para Claude Code: memoria persistente en archivos, registro de decisiones con revisión periódica, gestión automática de la bandeja de Gmail con borradores y un panel de tareas que el agente ejecuta solo con un cron.

## Ideas

- Crear una carpeta de memoria por categorías (decisiones, personas, preferencias, usuario) y pedir en CLAUDE.md que se lea al empezar y se actualice al terminar.
- Llevar un registro de decisiones con fecha, razonamiento, resultado esperado y revisión a 30 días.
- Clasificar el correo y preparar borradores sin enviar nunca nada solo (requiere acceso a Gmail: revisar riesgos).
- Panel de tareas que un agente ejecuta solo cada hora (desaconsejado sin supervisión).

## Lo que dice el vídeo

Nada hablado en el texto en bruto (solo contenido en pantalla).

## En pantalla

- Título: 4 Prompts de Claude Code que lo hacen un súper-empleado. Cuenta @esmejorconia ("guárdalo para después"; cierre: "Nunca vas a volver a ver esta cuenta, a menos que nos sigas @esmejorconia").
- Tu Claude Code nunca volverá a olvidar. Mándale este mensaje a Claude: «Crea un sistema de memoria persistente para ti mismo. Haz un directorio /memory con archivos organizados por categoría: decisions.md, people.md, preferences.md y user.md. Escribe un CLAUDE.md que te indique leer estos archivos al inicio de cada sesión y actualizarlos al final.»
- Hazte responsable. Prueba este: «Crea un sistema de registro de decisiones. Cada vez que te describa una decisión que estoy tomando, regístrala en decisions.csv con: fecha, decisión, razonamiento, resultado esperado y una fecha de revisión a 30 días. Configura un cron job que revise a diario si alguna decisión llegó a su fecha de revisión y le agregue la marca "REVISIÓN PENDIENTE". Crea un script review.sh que muestre solo esos elementos marcados.»
- Limpia tu bandeja de entrada. Esto lo cambia todo: «Crea un cron job cada hora que revise mi bandeja de Gmail, clasifique los correos nuevos en URGENTE / REQUIERE RESPUESTA / FYI / BASURA, los etiquete automáticamente con mis etiquetas actuales (deduce su significado por el historial) y guarde borradores de respuesta para los correos URGENTE y REQUIERE RESPUESTA, con el tono de mis últimos 20 correos enviados. Nunca envíes nada solo. Ya tienes acceso al Google Workspace CLI y a mi Skill de Workspace CLI (de Tyler Germain) de AI Innovators. Guarda el estado en emails_processed.json. Registra todo en inbox_manager.log.»
- Dashboard de tareas: «Crea un dashboard de tareas con una interfaz web local. Puedo agregar, editar y eliminar tareas con niveles de prioridad. Configura un cron job cada hora: si la lista de tareas no está vacía, trabaja en las tareas de forma autónoma empezando por la de mayor prioridad, registra lo que hiciste y márcala como completada. Guarda las tareas en tasks.json. Registra toda la actividad en tasks.log.»

## Notas

- Etiquetas: aeterna, transcripcion
- Calidad de la transcripción automática: media
- Archivo original de AETERNA: `2026-11-12_130704_guardalo-para-despues_8184b9.md`

**Revisar antes de usar:** Fuente útil, pero revisar nombres propios de herramientas antes de convertirla en guía o tarea.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
