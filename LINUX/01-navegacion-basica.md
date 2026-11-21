# Navegación básica en Linux

## Comandos usados

- `pwd`: Muestra en que carpeta estoy parado.
- `ls`: lista los archivos y carpetas del directorio actual.
- `cd`: me mueve a otra carpeta.

 ## Práctica

 Al ejecutar `pwd` en mi usuario, el resultado fue: /home/kali
 Con `ls` vi las carpetas típicas del usuario (Desktop, Documents, Downloads, Music, Pictures, Public, Templates, Videos) y un archivo `cookies. txt`.
 Después me moví con `cd /var/log`, y al confirmar con `pwd` el resultado fue: /var/log
 Ahí, `ls` mostró carpetas de distintos servicios y archivos de registro del sistema (por ejemplo auth.log, apache2, mysql), que en Blue Team se usan para investigar que pasó en un sistema.

 ## Aprendizaje

 Entendí que `pwd`, `ls` y `cd` son la base para moverme con confianza por la terminal antes de analizar cualquier archivo o configuración.
