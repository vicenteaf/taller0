# Glosario Git

* __Control de versiones (VC):__
Sistema que registra los cambios hechos a un conjunto de archivos con el objetivo de tener un historial de todas las versiones.
_Fuente:_ https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

* __Control de versiones distribuido (DVC):__
Es un control de versiones en el cual el servidor guarda todas las versiones, y el cliente al hacer un clone copia todo el historial de versiones. De esta manera, en caso de un fallo del servidor, este puede copiar el repositorio de un cliente.
_Fuente:_ https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

* __Repositorio remoto y Repositorio local:__
Un repositorio remoto son conjuntos de archivos, y sus multiples versiones, almacenados en Internet. En cambio el rpositorio local, tal como su nombre lo dice, está almacenado de manera local, es decir, en el cliente.
_Fuente:_ https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos

* __Copia de trabajo / Working Copy:__
Es una copia completa del repositorio ubicada localmente. El objetivo la copia de trabajo es ser modificada para generar una nueva versión.
_Fuente:_ https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms

* __Área de Preparación / Staging Area:__
Archivo en el cual hay información sobre que se incluye en la siguiente versión.
_Fuente:_ https://git-scm.com/book/es/v1/Empezando-Fundamentos-de-Git

* __Preparar Cambios / Stage Changes:__
Al preparar los cambios se seleccionan los archivos que están listos para ser incluidos en el siguiente commit.
_Fuente:_ https://softwareengineering.stackexchange.com/questions/119782/what-does-stage-mean-in-git

* __Confirmar cambios / Commit Changes:__
Se crea una nueva versión con los cambios preparados.
_Fuente:_ https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio

* __Commit:__
Comando para guardar los cambios prepardos en el repositorio.
_Fuente:_ https://git-scm.com/docs/git-commit

* __clone:__
Comando que hace una copia del repositorio en una carpeta, generalmente local.
_Fuente:_ https://git-scm.com/docs/git-clone

* __pull:__
Comando que incorpora los datos guardados en un repositorio remoto con los de la rama actual, generalmente local.
_Fuente:_ https://git-scm.com/docs/git-pull

* __push:__
Comando que envía los cambios al repositorio remoto.
_Fuente:_ http://rogerdudler.github.io/git-guide/index.es.html

* __fetch:__
Comando que descarga los cambios en otra rama. Similar al comando pull, solo que este une la rama creada y la actual.
_Fuente:_ https://es.stackoverflow.com/questions/245/cu%C3%A1l-es-la-diferencia-entre-pull-y-fetch-en-git

* __merge:__
Comando que une los cambios de dos o más commits y los incorpora a la rama actual.
_Fuente:_ https://git-scm.com/docs/git-merge

* __status:__
Comando que muestra el estado de los archivos, ya sea rastreado o modificado.
_Fuente:_ https://git-scm.com/book/es/v2/Fundamentos-de-Git-Guardando-cambios-en-el-Repositorio

* __log:__ 
Comando que muestra la información histórica de los commit. 
_Fuente:_ https://git-scm.com/book/es/v1/Fundamentos-de-Git-Viendo-el-hist%C3%B3rico-de-confirmaciones

* __checkout:__
Comando que cambia la copia de trabajo a otra rama seleccionada.
_Fuente:_ https://git-scm.com/docs/git-checkout

* __Rama / Branch:__ 
Es una secuancia histórica de commits a partir del HEAD.
_Fuente:_ https://git-scm.com/book/es/v1/Ramificaciones-en-Git-%C2%BFQu%C3%A9-es-una-rama%3F

* __Etiqueta / Tag:__
Sirven para marcar puntos específicos en el historial del repositorio.
_Fuente:_ https://git-scm.com/book/en/v2/Git-Basics-Tagging
