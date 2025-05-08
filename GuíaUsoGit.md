# Guía básica del uso Git

¿Qué es Git?
Git es un sistema de control de versiones libre y de código abierto. Se trata de un sistema de control de versiones distribuido capaz de albergar proyectos de gran envergadura de forma ágil y eficiente.

¿Qué es GitHub?
Es una plataforma de desarrollo colaborativo que permite a los desarrolladores alojar, compartir y trabajar en proyectos de código fuente utilizado el sistema de control de versiones Git.

¿Qué necesitamos para usar GitHub en nuestros proyectos?
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

Alta GitHub, Git Bash (terminal), carpeta en disco local

Comandos habituales para trabajar con repositorios remotos 
Para trabajar con repositorios remotos, algunos comandos habituales incluyen:

git clone: Este comando clona un repositorio remoto en tu máquina local. Por ejemplo, git clone ```URL_repositorio.```
git fetch: Descarga todas las confirmaciones realizadas en el repositorio remoto hacia tu repositorio local. Este comando no fusiona los cambios automáticamente, sino que los coloca en una rama oculta llamada ```FETCH_HEAD.```
git pull: Este comando obtiene los cambios realizados en el repositorio remoto y los fusiona con tu repositorio local. Es equivalente a ejecutar git fetch seguido de git merge.
git push: Envía los cambios realizados en tu repositorio local a la rama especificada en el repositorio remoto. Por ejemplo, ```git push nombre_repositorio nombre_rama.```
git remote add: Este comando añade un nuevo repositorio remoto. Por ejemplo, git remote add origin https://github.com/OWNER/REPOSITORY.git.
git remote show origin: Este comando muestra información sobre el repositorio remoto, incluyendo las URLs de lectura y escritura, y las ramas locales y remotas.
Estos comandos te permiten gestionar eficazmente tus repositorios tanto locales como remotos.

Git init, git status,  git remote, git add . , git commit, git push

Clonar un repositorio


Hacer For de un repositorio existente
