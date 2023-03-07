# Existen tres estados en git
1: untraked(U) = git no sabe de la existencia de los archivos
2: unstaged(A) = git sabe de la existencia de los archivos pero no de sus nuevas modificaciones
3: staged = git sabe de la existencia y modificaciones de los archivos
4: tracked = git guarda por completo el proyecto

para cambiar un estado de git y volver al anterios se utiliza:
new file:   BlocDeNotas.txt esta en unstage
y cambia con "git reset (nombre del archivo que se quiere revertir)"

Si se quiere add todos los archivos a git se escribe "git add ." y se guardan los no guardados

Comandos Git
git init: inicializa git
git status: muestra los archivos en que estado estan
Si se quiere add todos los archivos a git se escribe "git add ." y se guardan los no guardados