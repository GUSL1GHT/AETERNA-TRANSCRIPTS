# Libera RAM en Windows deshabilitando procesos innecesarios y usando RAMMap

10/11/2026 · TikTok · [Ver el vídeo](https://vm.tiktok.com/ZN8PkLhaJ/)

## De qué va

Este tutorial enseña cómo liberar memoria RAM en Windows 10 y 11 desactivando la telemetría, la optimización de distribución y utilizando la herramienta RAMMap de Microsoft.

## Ideas

- Desactivar 'Experiencias del usuario y telemetría asociada' desde services.msc.
- Desactivar 'Optimización de distribución' en Configuración > Windows Update > Opciones avanzadas.
- Usar la herramienta RAMMap de Microsoft para vaciar la lista de espera de memoria.

## Lo que dice el vídeo

Quiero que mires tu PC ahora mismo. Tenemos un parásito oculto dentro de Windows 10 y Windows 11, que por supuesto está devorando tu memoria RAM sin que te des cuenta. Muchísimas de las veces pensamos que nuestro PC comienza a ir lento porque hay programas que son pesados, pero la realidad es que Windows tiene algunos procesos activos por defecto que no te dan ningún beneficio y que por supuesto están consumiendo recursos. Así que hoy vamos a localizar ese parásito, lo vamos a aniquilar y por supuesto te voy a enseñar cómo liberar gigas de RAM con una herramienta oficial. Comenzamos.

Lo primero que vamos a hacer es darle en el teclado a Windows R y nos saldrá la ventanita de ejecutar. Escribiremos `services.msc`. Esto te lo dejaré en la descripción para que puedas copiarlo enseguida. Y le daremos a Aceptar. Ahora, en esta lista que nos sale, tenemos que buscar algo llamado «Experiencias del usuario y telemetría asociada». Tendremos que ir más o menos a un cuarto de la lista para encontrarlo, y aquí lo tenemos. Este proceso es un parásito, solo sirve para recolectar datos de cómo usamos nuestro PC y enviarlos al fabricante. Y por supuesto, no quiero que nadie me vigile y mucho menos que use mi RAM para hacerlo. Así que le daremos clic derecho y le diremos que queremos Detener. Ahora cargará la pantalla y detendrá este proceso. Pero aquí no hemos terminado, porque volveremos a darle clic derecho y nos iremos a sus Propiedades. Si nos damos cuenta, nos dice que el tipo de inicio es Automático. Vamos a darle clic al desplegable y le daremos a Deshabilitado. Aplicamos y aceptamos. Primer parásito, fuera. Este es el primer paso para desactivar de tres pasos que te enseño en este vídeo. Así que continúa viendo porque vamos a liberar muchísima RAM.

Lo que nos lleva al paso número dos. Hay otro ajuste que viene activo por defecto y está usando tu procesador y tu internet para ayudar a otros. Se llama la optimización de entrega. Para acceder aquí nos iremos al inicio, le daremos clic derecho con el ratón y entraremos en Configuración. Ahora entraremos en Windows Update. Bajaremos hasta encontrar Opciones avanzadas y entraremos. Una vez en esta ventana, bajaremos hasta encontrar Optimización de distribución, y desactivaremos «Permitir descargas de otros dispositivos». Si utilizas Windows 10 es algo diferente: irás al inicio, entrarás en Configuración, volverás a entrar a Actualización y seguridad, tendrás que hacer clic en Optimización de entrega y desactivar. Pero ¿por qué hacemos esto? Porque Windows utiliza tu PC para enviar trozos de actualizaciones a desconocidos en internet. Esto lo que hace es quitarte ancho de banda y también ralentiza tu sistema. Así que lo apagamos.

Ahora vamos al paso número tres, la liberación total con RAMMap. Este será el truco final para limpiar tu memoria RAM por completo. Para esto utilizaremos una herramienta que puedes encontrar en tu navegador. Simplemente escribes RAMMap y te la descargas desde la propia página de Microsoft. Una vez descargada, simplemente la extraes y la instalas. Mira esto: si abro el Administrador de tareas, veo que tengo muchísima memoria en caché. Lo que tenemos que hacer es abrir la aplicación que te he enseñado anteriormente, la de RAMMap. Una vez dentro de esta herramienta, tenemos que irnos arriba donde pone Empty. Le daremos un clic y nos iremos a donde pone Empty Standby List, y le daremos un clic. Y solamente tienes que ver esto: de tener gigas ocupando, acabamos de liberar casi todo al instante. Ahora esa RAM la tienes para jugar o para usar cualquier programa.

Si esto te ha servido, suscríbete y déjame un like, porque este canal acaba de empezar. Adiós.

## En pantalla

- Comando en Ejecutar (Windows + R): `services.msc`.
- Paso 1: servicio «Experiencias del usuario y telemetría asociada» (Equipo local): Detener; Propiedades; Tipo de inicio: Automático cambiado a Deshabilitado.
- Paso 2: Windows 11: Inicio, Configuración, Windows Update, Opciones avanzadas, Optimización de distribución, «Permitir descargas de otros dispositivos» desactivado. Windows 10: Configuración, Actualización y seguridad, Optimización de entrega.
- Paso 3: RAMMap (Sysinternals, de Microsoft): menú Empty, Empty Standby List.
- Administrador de tareas, Rendimiento, Memoria. Antes: en uso (comprimido) 12,7 GB (44,9 MB), disponible 17,6 GB, en caché 18,3/33,9 GB, 1,7 GB. Después: en uso (comprimido) 4,7 GB (482 MB), disponible 27,2 GB, en caché 17,4/34,8 GB, 677 MB.

## Notas

- Etiquetas: windows, ram, optimizacion, tutorial, recursos
- Calidad de la transcripción automática: alta
- Archivo original de AETERNA: `2026-11-10_131524_libera-ram-en-windows-deshabilitando-procesos-innecesarios-y-usando-rammap_6ffc28.md`

**Revisar antes de usar:** Los nombres de los servicios y las opciones de configuración de Windows son precisos y corresponden a versiones actuales del sistema operativo.

Posibles errores de transcripción:

- "Nombres propios técnicos" → posible: "Revisión manual". Motivo: El contenido menciona software/herramientas; revisar posibles nombres propios antes de convertirlo en guía o tarea.
