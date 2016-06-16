#Readme.md

- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
    Comando : git reset --hard HEAD~1
    Motivo  : volvemos al commit anterior y con la opción hard perdemos los cambios.
    
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
    Comando : git reflog para obtener el commit y git reset a dicho commit
    
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
    Comando : git merge master
    Conflicto : already update por que no habia nada que mezclar
    
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
    Causo conflicto por que habiamos editado el mismo fichero en dos ramas distintas
    
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
    No hubo conflicto y se realizo un merge fast forward
    
- ¿Qué comando o comandos utilizaste en el paso 25?
    Comando : git log --graph --decorate --pretty=oneline
    
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
    no por que vienen de branch diferentes
- ¿Qué comando o comandos utilizaste en el paso 27?
    Comando : git reset al commit buscado desde un reflog
- ¿Qué comando o comandos utilizaste en el paso 28?
    Comando : git stash
- ¿Qué comando o comandos utilizaste en el paso 29?
    Comando : git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
    Comando : git reset al commit buscado desde un reflog
- ¿Qué comando o comandos usaste en el paso 32?
    Comando : git checkout a initial localizado con reflog
- ¿Qué comando o comandos usaste en el punto 33?
    Comando : git checkout a commit localizado con reflog