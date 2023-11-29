Inicializo el repositorio, obviamente en la rama main

creo el archivo status.js con toucho status.js

lo agrego al repositorio y hago el commit Inicial

--- Dejando todo preparado para cuando tenga que borrarlo en el siguiente paso.

Luego creo la rama custom-navbar

creo cualquier archivo, como por ejemplo navbar.html para agregarla al repositorio 
y antes de hacer el commit, pausarlo con git stash

para ir a la Rama main y eliminar el archivo status.js


Me cambio a la rama main usando git checkout main
---- Ya en la rama main, procedo a eliminar el archivo status.js usando git rm status.js


Una vez eliminado el archivo status.js

Creo la Rama front-react con git branch front-react y accedo a ella con
git checkout front-react


--- Ahora en la Rama main hago un git merge front-react
para traer todos los cambios a la rama main
=======

---Ahora, una vez creada la rama front-react y accedido a ella

Trabajo sobre el proyecto React.js
lo agrego al repositorio y hago el commit correspondiente

-----------------------

Genere un conflicto de mergin a proposito
Ahora que lo arregle, hago el commit final del README.md

----------------- Listo.! Todo resuelto

Ahora que ya arregle todo y mergie a la rama main el proyecto de React, voy a 
subir el repositorio a GitHub
(Recordemos que la rama custom-navbar quedo en pausa y no esta mergiada a la rama main, 
no se pidio en este esjercicio)

Acabo de crear un repo en GitHub y voy a usar estos comandos para subirlo:
	git remote add origin https://github.com/Drako01/Entrega-1---2911---ej2.git
	git branch -M main
	git push -u origin main

Con esto termino el ejercicio.!!

  