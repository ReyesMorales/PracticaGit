- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Git reset –hard HEAD~1, porque queremos borrar lo que tenemos en el working copy, si lo quisieramos mantener lo ejecutaríamos sin el –hard.
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Git reset <hash> del commit que queria rehacer y ademas git restore para recuperar los cambios que habiamos realizado en git-nuestro.md.
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
Git merge master, no causó ningun conflicto
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Primero usamos git checkout styled, para movernos a la rama que absorbe y luego ejecutamos git merge htmlify. Nos causa un conflicto en git-nuestro.md, nos insta a resovler el conflicto y a crear un commit con el resultado.
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
En primer lugar, nos movemos a la rama master (git checkout master), git merge styled y realiza el merge sin ningun conflicto
- ¿Qué comando o comandos utilizaste en el paso 25?
Git log –graph
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
No, para no perder acceso al contenido que tiene master, pues se moveria a title y perderia los otros commits
- ¿Qué comando o comandos utilizaste en el paso 27?
Git reset <hash> usando el hash del commit anterior o git reset HEAD~1
- ¿Qué comando o comandos utilizaste en el paso 28?
Git restore 
- ¿Qué comando o comandos utilizaste en el paso 29?
Git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
Git reset <hash> del commit donde se realizo el merge non fast forward
- ¿Qué comando o comandos usaste en el paso 32?
Git reset <hash> del primer commit
- ¿Qué comando o comandos usaste en el punto 33?
Git reset <hash> del commit donde añadimos titulo