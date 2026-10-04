# Mi primer proyecto

Esta es una breve descripción de lo que es el uso de GIT.

##Segunda Sección

Los comandos más importantes de Git permiten inicializar, gestionar, sincronizar y controlar versiones de código de forma eficiente.
Configuración inicial
• git config: Configura tu nombre de usuario y correo electrónico globales.
	• Ejemplo: git config --global user.name "Tu Nombre"
Crear y clonar repositorios
• git init: Crea un nuevo repositorio local de Git en una carpeta.
• git clone: Descarga una copia completa de un repositorio remoto existente.
Registrar cambios (Flujo de trabajo básico)
• git status: Muestra el estado actual del directorio de trabajo y los archivos modificados.
• git add : Prepara los cambios (los mueve al área de preparación o staging area).
• git commit -m "mensaje": Guarda una instantánea permanente de los cambios preparados en el historial local.
• git diff: Muestra las diferencias exactas en el código que aún no se han preparado o guardado.
Trabajar con ramas (Branches)
• git branch: Muestra las ramas disponibles o crea una nueva rama.
• git checkout [nombre-rama] o git switch [nombre-rama]: Cambia de una rama a otra.
• git checkout -b [nombre-rama]: Crea una nueva rama y se cambia a ella de inmediato.
• git merge [nombre-rama]: Une el historial de otra rama con la rama en la que estás actualmente.
Sincronizar con repositorios remotos
• git push: Sube tus confirmaciones (commits) locales al servidor remoto.
• git pull: Descarga los cambios más recientes del servidor remoto y los fusiona en tu rama actual.
• git fetch: Descarga los cambios del servidor remoto sin fusionarlos automáticamente en tu código.
Historial y revisión
• git log: Muestra el registro histórico de las confirmaciones (commits) realizadas.
• git reset: Deshace cambios moviendo el puntero actual a un estado anterior.