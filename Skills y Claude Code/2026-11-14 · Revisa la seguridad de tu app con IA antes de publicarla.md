# Revisa la seguridad de tu app con IA antes de publicarla

14/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN85BLMKL/)

## De qué va

Utiliza la skill gratuita de Cloudflare para Claude Code y un prompt específico para que analice la seguridad de tu aplicación y sugiera soluciones.

## Ideas

- Implementar la skill de Cloudflare para realizar auditorías de seguridad automáticas en proyectos de IA.
- Ejecutar la revisión de seguridad varias veces para maximizar la detección de fallos, según las recomendaciones de Cloudflare.

## Lo que dice el vídeo

Antes de publicar, Claude Code revisa la seguridad de tu app. Si has creado una web o una app con IA, antes de publicarla haz esto, porque que funcione no significa que sea segura. Hay una skill gratis de Cloudflare, la empresa que protege gran parte de internet, llamada security-audit. Esta skill convierte a Claude en un experto de seguridad.

Te voy a enseñar cómo la uso yo con un ejemplo real. Primero te vas a la skill en GitHub y copias la URL. Después abres Claude Code en la carpeta del proyecto. Yo, en mi caso, la voy a hacer con un proyecto que tengo de un CRM que me estoy creando para mí. Le pegas la URL y le dices que revise la seguridad utilizando esa skill. El prompt que yo utilizo es un poco más largo, pero al final te digo cómo conseguir tanto la skill como el prompt.

Y aquí está lo bueno: pone varios agentes a buscar fallos, y cada fallo que encuentra se lo pasa a otro agente para asegurarse de que es un fallo real. Así no te llena de falsas alarmas. En mi CRM ha encontrado todos estos fallos, y me explica qué podría pasar si publico esto así y cómo solucionarlo. Le digo que lo arregle y pase una segunda auditoría de seguridad para asegurarnos de que todo está bien, y se encarga de todo.

Y este es un truco que te doy: dile que haga la revisión de seguridad varias veces, ya que la propia Cloudflare dice que en la primera revisión de seguridad encuentra más o menos la mitad de los fallos. Así que, si quieres estar seguro de verdad, pásala varias veces. Y dale al me gusta si este vídeo te ha ayudado. Te dejo la skill y el prompt en la descripción.

## En pantalla

- Skill `security-audit`, gratis, de Cloudflare.
- Proyecto de ejemplo: `mi-crm` (CRM de prueba).
- 3 agentes buscando fallos; cada fallo lo comprueba otro agente (descarta falsas alarmas).
- Qué podría pasar: «Cualquiera lee, cambia o borra tus clientes»; cómo se arregla: login + base de datos protegida.
- Según Cloudflare: 1.ª pasada 33 % de los fallos; 50 % de los fallos en la revisión (más seguro con 2.ª y 3.ª pasada).

## Notas

- Etiquetas: seguridad, ia, desarrollo, cloudfare, claude-code
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-14_023303_revisa-la-seguridad-de-tu-app-con-ia-antes-de-publicarla_8d2ecd.md`

**Revisar antes de usar:** El término 'skill' se refiere a una extensión o funcionalidad añadida a la herramienta principal Claude Code. La fuente de la skill es GitHub.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
- "Claude Code" → posible: "Claude Code". Motivo: Nombre de herramienta de IA específica, se asume correcto.
- "SKILL security-audit" → posible: "skill security-audit". Motivo: Nombre de la skill, se asume correcto.
