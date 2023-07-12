# Curso Terminal

Date Created: 8 de julio de 2023 12:50
Status: Done 🙌

# Alternativas de Terminal para Windows

Alternativa 1. 

Buscar “cmd” en windows. Esta es la terminal de windows. No se recomienda pues la arquitectura de windows no es compatibles con las de Linux o Apple.

Alternativa 2.

PowerShell:  Es una temrinal potente orientada al desarrollo. Pero conserva la arquitectura de Windows pero no es totalmente compatible con Linux y Apple

Alternativa 3.

Subsistema de Linux WSL: Es una versión de Linux en Windows. Se considera como buena opción para W10 o superior.

Alternativa 4.

Gitbash: Se pueden usar los mismos comandos de Linux o Apple

# Diferencias entre CLIs y GUIs

CLI: Comand Line Interface. Es la ruta donde se está pero indicado por la línea en código

GUI: Graphic User Interface. Es la ruta donde se está pero mediante interfaz gráfica

# PWD Print Work Directory

PDW devuelve el directorio en donde se está

![PWD.png](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/PWD.png)

# WHOIAM

WHOIAMWH devuelve el usuario del que se está trabajando

![Untitled](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/Untitled.png)

# HELP

Comando de ayuda. Se pueden combinar con otros comandos. Es decir $help pdw nos va a dar opciones de ayuda para el comando. Se puede usar $help pwd; $pwd - -help

![Untitled](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/Untitled%201.png)

# Manejo de Historial de Comandos

Se buscan los últimos 20 comandos con la flecha del teclado hacía arriba

# Clear. Limpia historial de comandos

Se Limpia el historial de comandos

# Comando ls

Muestra los contenidos de la ubicación. Lista el contenido de un directorio

ls -l: También muestra detalles de los archivos

ls -a: Muestra archivos ocultos y no ocultos

ls -la: Muetsra archivos ocultos y no ocultos con detalles

# Comando cd (change directory)

Cambia la ubicación $cd “nombre de la carpeta o ubicacipón”

$cd desktop me ubica en la ubicación desktop

![Untitled](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/Untitled%202.png)

Si las carpetas tienen espacios deberá buscarse entre comillas $cd “Archivos del Programa”

ATAJOS:

$cd (primera letra de la carpeta)+tab me identifica carpetas con que inician con esa letra 

$cd (se puede arrastrar la carpeta de la GUI)

$cd ~ me lleva al directorio original (home)

$cd .. me muestra el directorio padre de la ubicación actual

$cd / es la dirección principal del disco duro

$cd - regresa a la ubicación anterior

# Comando TOUCH

Crea archivos nuevos

$touch nuevo-archivo.txt (Crea en la ubiación en donde se está un nuevo archivo de nombre nuevo-archivo con extensión .txt)

# Comando ECHO

Crea archivo nuevo e incluye su contenido

$echo “Hola mi nombre es Carlos”>hola.txt crea un archivo .txt en la carpeta actual de nombre hola y su contenido es “Hola mi nombre es Carlos”

# Comando CAT

Muestra el contenido de un archivo

$cat hola.txt

# Comando MKDIR

Crea una nueva carpeta o dirección

$mkdir assets Crea una carpeta en la ubiación actual llamada assets

# Comando RMDIR

Elimina Carpetas si la carta está vacía

$rmdir (nombre de la carpeta)

# Comando RM

Elimina archivos 

$rm hola.txt 

$rm -r assts elimina las carpetas con su contenido

# Comando MV

Mueve archivos

$mv hola.txt perro Mueve el archivo hola.txt a la carpeta perro

Para renombrar archivos, se mueve el archivo a la misma carpeta pero se le cambia en nombre

$mv hola.txt chao.txt cambia el nombre del archivo hola a chao

# Comando CP

Copia Archivos

$cp hola.txt ../ Copia el archivo un nivel arriba

$cp hola.txt ../chao.txt copia y pega el archivo en un nivel arriba y le cambia el nombre

$cp -r js css copia la carpeta js y su contenido a una carpeta llamada css

# Comando FIND

Busca archivos

$find hola.txt busca el archivo hola.txt desde la carpeta en la estoy hasta todas sus subcarpetas

$find h* busca todos los archivos que comiencen por h

# Comando PS

Lista procesos activos de la computadora

![Untitled](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/Untitled%203.png)

# Comando KILL

Elimina un proceso (Cuidado)

$KILL 24772 Elimina el proceso con ID 24772

# Comando para abrir editores de código

$code abre una ventana de visualstudio code y así con diferentes editores de código

$code /c/…. abre un archivo visualstudiocode en la ubicación descrita

# Comando ALIAS/UNALIAS

Se crean comandos personalizados. Si creo un alias llamado hi=”$hola.txt”. Cada vez que ingrese hi, creará un archivo txt

$alias hi=”$touch hola.txt”

Para eliminar un alias, $unalias hi

![Untitled](Curso%20Terminal%20e5aa1dac51af405da7554ecd1b60463a/Untitled%204.png)