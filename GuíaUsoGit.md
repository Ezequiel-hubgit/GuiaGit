# Guía básica del uso Git
![logotipo de Git](https://imgs.search.brave.com/R-cvEl8_gLFrgtnUfcTIwCcKWVaZuLAETrS_fgpuQ-g/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9pbWFn/ZXMuaWNvbi1pY29u/cy5jb20vMjQxNS9Q/TkcvOTYvZ2l0X3Bs/YWluX3dvcmRtYXJr/X2xvZ29faWNvbl8x/NDY1MDgucG5n)<br>
***¿Qué es Git?***<br>
Git es un sistema de control de versiones libre y de código abierto. Se trata de un sistema de control de versiones distribuido capaz de albergar proyectos de gran envergadura de forma ágil y eficiente.

***¿Qué es GitHub?***<br>
Es una plataforma de desarrollo colaborativo que permite a los desarrolladores alojar, compartir y trabajar en proyectos de código fuente utilizado el sistema de control de versiones Git.

***¿Qué necesitamos para usar GitHub en nuestros proyectos?***<br>
Para usar GitHub en tus proyectos, necesitas seguir varios pasos y tener ciertos elementos preparados:

Cuenta en GitHub: <br>
🥇:Primero, necesitas registrarte en GitHub creando una cuenta de usuario gratuita.<br>
🥇:Configuración de Git: Asegúrate de tener instalado Git en tu computadora y configúralo con tu nombre de usuario y correo electrónico.<br>
🥇Creación de Repositorio: Crea un nuevo repositorio en GitHub para alojar tu proyecto.<br>
🥇Clonar Repositorio: Clona el repositorio en tu máquina local para comenzar a trabajar en tu proyecto.<br>
🥇Realizar Cambios: Modifica archivos y realiza cambios en tu código en tu máquina local.<br>
🥇Confirmar Cambios: Usa git commit para confirmar tus cambios localmente, escribiendo un mensaje de confirmación conciso que describa lo que has hecho.<br>
🥇Enviar Cambios: Envía tus cambios de vuelta al repositorio de GitHub usando git push.<br>
🥇Solicitudes de Extracción (Pull Request): Una vez que tus cambios estén listos, crea una solicitud de extracción para proponer fusionarlos en la rama principal.<br>
🥇Revisión y Fusión: Aborda cualquier comentario, realiza los cambios necesarios, y una vez aprobado, fusiona la solicitud de extracción.<br>
🥇Estos pasos te permiten gestionar y colaborar eficientemente en tus proyectos de código usando GitHub.<br>

 ***Alta GitHub, Git Bash (terminal), carpeta en disco local*** <br> 
Acceder a una carpeta específica: Usa el comando cd seguido de la ruta de la carpeta que deseas entrar. Por ejemplo, si quieres entrar a la carpeta del escritorio, puedes usar cd desktop o cd ~/Desktop para navegar a la carpeta de escritorio en tu carpeta de usuario.<br>
Listar el contenido de una carpeta: Utiliza el comando ls para listar los archivos y carpetas dentro de la carpeta actual.<br>
Navegar a otro disco duro: Para navegar a otro disco duro, puedes usar el comando cd seguido de la letra del disco y la ruta de la carpeta. Por ejemplo, si tu disco duro está en la letra D, puedes usar cd /d/ seguido de la ruta de la carpeta que deseas entrar.<br>

***Comandos habituales para trabajar con repositorios remotos***
Para trabajar con repositorios remotos, algunos comandos habituales incluyen:

🥈git clone: Este comando clona un repositorio remoto en tu máquina local. Por ejemplo, git clone ```URL_repositorio.``` <br>
🥈git fetch: Descarga todas las confirmaciones realizadas en el repositorio remoto hacia tu repositorio local. Este comando no fusiona los cambios automáticamente, sino que los coloca en una rama oculta llamada ```FETCH_HEAD.``` <br>
🥈git pull: Este comando obtiene los cambios realizados en el repositorio remoto y los fusiona con tu repositorio local. Es equivalente a ejecutar git fetch seguido de git merge. <br>
🥈git push: Envía los cambios realizados en tu repositorio local a la rama especificada en el repositorio remoto. Por ejemplo, ```git push nombre_repositorio nombre_rama.```<br>
🥈git remote add: Este comando añade un nuevo repositorio remoto. Por ejemplo, git remote add origin https://github.com/OWNER/REPOSITORY.git.<br>
🥈git remote show origin: Este comando muestra información sobre el repositorio remoto, incluyendo las URLs de lectura y escritura, y las ramas locales y remotas.<br>
Estos comandos te permiten gestionar eficazmente tus repositorios tanto locales como remotos.

***Git init, git status,  git remote, git add . , git commit, git push***  <br>
🉑Git init <br>
crear un nuevo repositorio de Git.  <br>
🉑Git status  <br>
muestra el estado actual del directorio de trabajo y la área de ensayo en un repositorio Git.  <br>
🉑Git remote  <br>
 Se utiliza para administrar las conexiones a otros repositorios remotos. <br>
🉑Git add. <br>
 Se utiliza para agregar todos los archivos modificados en el directorio actual y sus subdirectorios al área de preparación (staging area) de Git.  <br>
🉑Git commit <br>
Fija en la historia del proyecto un snapshot del estado actual, es decir, una versión "segura" o relevante del mismo proyecto. <br>
🉑Git push  <br>
 ***Se utiliza para subir los cambios hechos en tu repositorio local a un repositorio remoto.*** <br>
***Clonar un repositorio *** <br>
Clonar un repositorio en Git significa hacer una copia completa del mismo en tu ordenador, incluyendo toda la historia del proyecto y permitiéndote navegar por sus cambios a lo largo del tiempo. <br>
Hacer Fork de un repositorio existente <br>
Para hacer un fork de un repositorio existente en GitHub, primero debes navegar a la página principal del repositorio que deseas clonar y luego presionar el botón "Fork" para crear una copia independiente de ese repositorio en tu cuenta de GitHub. <br>

