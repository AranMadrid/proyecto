# proyecto
EJERCICIO 1
Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de comandos sobre el mismo para posteriormente subir el repositorio a Github.
Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:

¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1
Se podría utilizar git reset HEAD~1, pero he optado por utilizar –hard,para poder perder los cambios realizados en el working copy 

¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog—para poder ver el identificador
git reset --hard 8b62a5b para volver a ese punto con todos los cambios.

El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Si, tuve que realizar un commit para solventarlo 

El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
No, en este caso, hice el commit y no hubo problema 

El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, no hubo conflicto ya que fue fast foward.

¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --pretty=oneline

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, se podría realizar  

¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1 para no perder los cambios del working copy

¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard HEAD~1 para volver al punto con todos sus commits

¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?
git reflog para comprobar el identificador
git reset --hard 8b62a5b

¿Qué comando o comandos usaste en el paso 32?
git reflog
git reset --hard 9a9c0b0

¿Qué comando o comandos usaste en el punto 33?
git reflog
git reset --hard 8b62a5b
