# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

---

Antes de realizar esta práctica, tenía un conocimiento básico sobre Docker, especialmente sobre lo que es un contenedor y una imagen.
A través de la práctica, aprendí cómo descargar imágenes, crear y gestionar contenedores. El uso de comandos como **docker pull, docker run, y docker ps** me permitió explorar el ciclo de vida completo de un contenedor.

El proceso de inspeccionar imágenes y contenedores con **docker inspect** fue especialmente útil para entender cómo Docker maneja los identificadores y la configuración interna de los contenedores. También aprendí sobre el uso del **algoritmo SHA-256** para generar los identificadores únicos.

Uno de los puntos clave de la práctica del mapeo de puertos, antes de la práctica, no estaba claro cómo interactuarían los contenedores con la red del host. Ahora entiendo cómo hacer que los servicios dentro de un contenedor, como Nginx, sean accesibles desde mi máquina, lo cual sera importante para desarrollar y desplegar aplicaciones web.

Tuve un problema cuando ejecuté Nginx en primer plano, lo que bloqueó el terminal. Aprendí que al agregar el flag **-d**, el contenedor se ejecuta en segundo plano, permitiéndome continuar trabajando sin interrumpir el servidor.
