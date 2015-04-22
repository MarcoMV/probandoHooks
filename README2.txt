En .git/hooks/
Creo el archivo → touch post-commit
Edito el archivo → vim pist-commit
 	!#/bin/sh
	git push origin master
Sales del editor

Tienes que dar permiso de la siguiente manera para que tu máquina local lo pueda ejecutar: 
chmod +x post-commit
Con esto ya está autorizado

Regreso a mi carpeta donde está mi archivo del cual haré commit. 
Hago el commit de manera clásica y listo, el archivo debió subirse. 
