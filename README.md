1- Clonar el repositorio:
	git clone https://github.com/dacomo2021daw2/prjava02.git

5- Cambiar a la rama main:
	git checkout main

6- No verás la línea añadida en branca00 porque main aún no tiene esos cambios.

7- Cambiar a la rama branca00 y comprobar cambios:
	git checkout branca00

7- Ahora sí se ve la línea añadida porque estoy en branca00.

10b- Hacer merge de branca00 a main:
	git checkout main
	git merge branca00

12- Hacer push de main a GitHub:
	git push origin main

12c- Porque no hemos hecho push de branca00.

14a- Hacer push de branca01 a GitHub:
	git push origin branca01

14c- branca01 está 1 commit por delante de main.