# Git-Nuestro
- ¿Qué comando utilizaste en el paso 11?
- git reset  --hard HEAD~1para deshacer el commit y el working copy,
- ¿Por qué?
- porque asi vuelvo al estado anterior y elimino  todos los cambios.

¿Qué comando o comandos utilizaste en el paso 12?
git reflog y git reset --hard (sha) 
¿Por qué?
git reflog para inspecionar a donde a estado apuntando head y localizar el identificador que necesito y git reset --hard (identificador) para volver a este.

El merge del paso 13, ¿Causó algún conflicto?
no 
¿Por qué? 
porque no han habido cambios en main

El merge del paso 19, ¿Causó algún conflicto?
Claro
¿Por qué?
porque en stlyled esta con estilos y en html esta con formato html el archivo git-nuestro y lo pisaria

El merge del paso 21, ¿Causó algún conflicto?
nop 
¿Por qué? 
es Fast-forward

¿Qué comando o comandos utilizaste en el paso 25?
primero git log --graph
despues use el alias que le puse git graph que ejecuta git log --graph --oneline para verlo mas limpio

El merge del paso 26, ¿Podría ser fast forward?
si
¿Por qué?
porque title esta creada en un commit posterior y estan conectadas las ramas , title ya tenia conectado main

¿Qué comando o comandos utilizaste en el paso 27?
git reset --soft HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?
git restore --staged git-nuestro.md y despues git restore git-nuestro.md para limpiar working copy y staged area

 ¿Qué comando o comandos utilizaste en el paso 29?
 git branch -D title
 
¿Qué comando o comandos utilizaste en el paso 30?
git reflog para localizar el id y git reset --hard (identificador)

 ¿Qué comando o comandos usaste en el paso 32? 
 git checkout (identificador que tiene el primer commit)
 
 ¿Qué comando o comandos usaste en el punto 33?
 git reflog y git reset --hard (ide commit donde añado titulo )

