##### **1. ¿Qué es Git y para qué se utiliza?** 

###### Es un sistema de control de versiones que nos ayuda a tener control sobre los cambios en un proyecto mediante el uso de comandos Git.
##### **2. ¿Qué diferencia hay entre Git y GitHub?**

###### Git es el que nos permite controlar las versiones del proyecto y GitHub es una plataforma web donde podemos gurdar nuestros proyectos Git
##### **3. Explica en tus palabras qué es un repositorio.**

######  Es como archivo que permite ver informacion mas detallada sobre todos los cambios que se hicieron dentro de ella.
##### **4. ¿Qué significa hacer un commit en Git?**

###### Es un comentario de un nuevo cambio que se quiere guadar
##### **5. Investiga y explica brevemente los siguientes comandos de Git:**

    git config --local user.name "<GitHub user name>"

Se usa para configurar el nombre que se vera en algun cambio que se haga en un repositorio.

    git config --local user.email "<GitHub email>"
Se usa para configurar el correo electronico que se vera en algun cambio que se haga en un repositorio.

    git init

Se usa para inicializar el control de versiones de Git en un proyecto .

    git add

Se usa para escoger todos lo archivos con cambios que se quiere guardar en un proximo commit.

    git commit

Se usa para poner un comentario a un nuevo cambio que se quiere guardar, el cual abre un editor de texto para detallar de mejor manera el comentario.

    git push

Se usa para subir algun archivo o un cambio nuevo a un repositorio remoto como GitHub.

    git clone

Utilizado para poder clonar un repositorio remoto a un equipo de forma local.

    git init --initial-branch=main

Se utiliza para inicializar un proyecto git poniendo main como nombre a la rama principal.

    git remote add origin https://github.com/    <user-name>/tarea-git-github.git
Se utiliza para poder vincular un proyecto git local con un repositorio remoto y asi poder subir cambios a ese repositorio.

    git add .
Se utiliza para poder agregar todos lo archivos nuevos o archivos que tengan algun cambio y los prepara para luego guradarlos con un commit y asi tener control de esa version.

    git commit -m "Initial commit"

Se usa par poder hacer un comentario de un cambio que se quiere guardar,pero no abre un editor de texto y es mas util para descripciones mas sencillos o breves.

    git push --set-upstream origin main

Se usa para subir algun cambio o archivo a un repositorio remoto por primera vez, en el cual se detalla que desde ahora la rama main sera a la que se suban todos los cambio futuros cuando hagamos push y no tener que decir cada vez a que rama se quiere subir.

##### **6. ¿Qué es un archivo README.md y por qué es importante?**
Es un documento que describe de que trata el repositorio, su funcionamiento y que recursos se usaron en este repositorio, para que cuando otro usuario visite ese repositorio pueda tener contexto de lo que se puede encontrar en su interior antes de revisarlo con mas detalle.