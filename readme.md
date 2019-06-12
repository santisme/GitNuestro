- ¿Qué comando utilizaste en el paso 11?
	git reset --hard HEAD~1.
  ¿Por qué?
	Con reset situo el puntero HEAD en el commit anterior. Con el parametro --hard indico que restaure los ficheros.

- ¿Qué comando o comandos utilizaste en el paso 12?
	git reset --hard f56b1e0
  ¿Por qué?
	Con reset situo el puntero HEAD en el commit que hemos desecho. Con el parametro --hard indico que restaure los ficheros.

- El merge del paso 13, ¿Causó algún conflicto?
	No.
  ¿Por qué? 
	Porque no en master no se ha modificado el fichero git-nuestro.md.

- El merge del paso 19, ¿Causó algún conflicto?
	Si.
  ¿Por qué? 
	Porque se el fichero git-nuestro.md se ha modificado en styled y htmlify.

- El merge del paso 21, ¿Causó algún conflicto?
	No.
  ¿Por qué? 
	Porque en master no se ha modificado el fichero git-nuestro.md.

- ¿Qué comando o comandos utilizaste en el paso 25?
	git log --graph --decorate --pretty=oneline

- El merge del paso 26, ¿Podría ser fast forward?
	Si.
  ¿Por qué? 
	Porque desde master no se ha hecho un nuevo commit desde la creación de la rama title.

- ¿Qué comando o comandos utilizaste en el paso 27? 
	git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28? 
	git reset --hard 895e88aac5ce7b9d0c3977ca65d1a7714e78ef7d

- ¿Qué comando o comandos utilizaste en el paso 29? 
	git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30? 
	git reset --hard a192775

- ¿Qué comando o comandos usaste en el paso 32? 
	git reset --hard e7c0d92fe8541e6e54bc775a3a9ab23bf6f749bd

- ¿Qué comando o comandos usaste en el punto 33? 
	git reset --hard a192775
