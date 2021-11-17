# Ejercicios Daniel

**1. Debemos actualizar el sistema operativo Ubuntu**\
	 - Sincronizar la base de datos local y el repositorio: sudo apt update\
	 - Visualizar los programas a actualizar: sudo apt list --upgradable\
	 - Actualizar nuestro sistema operativo: sudo apt list upgrade\
**2. Determinar con un comando cuál es nuestra posición en el árbol del usuario**\
pwd tree\
/home/anadelarue\
**3. Visualizar con un comando el árbol del usuario desde /home/nuestroUsuario/**\
tree\
**4. Crear en /home/nuestroUsuario/ un folder llamado "ejercicios"**\
mkdir ejercicios\
**5. Verificar que lo hemos creado en el lugar correcto y su posición en el árbol**\
tree\
**6. Movernos a la carpeta "ejercicios" y verificar con el comando que estamos ahí**\
cd ejercicios\
pwd\
/home/anadelarue/ejercicios\
**7. Creamos un archivo de texto dentro del folder "ejercicios", escribimos texto y lo salvamos adecuadamente con el nombre parte_1**\
nano parte_1\
**8. Retrocedemos a /home/nombreUsuario/ utilizando el comando de retroceso o bien el comando de path absoluto. Verificamos con un comando nuestra posición**\
cd o cd ../ o cd /home/anadelarue\
**9. Con el comando y los parámetros adecuados generamos un listado**\
ls -l\
**10. Con el comando anterior agregamos otro parámetro y visualizamos los archivos ocultos también**\
ls -l -a\
**11. Desde /home/nuestroUsuario/ creamos otro archivo de texto llamado "parte_2", escribimos un texto, lo salvamos**\
nano parte_2\
**12. Desde la raiz del usuario creamos un folder llamado "trabajos"**\
mkdir trabajos\
**13. Desde la raíz del usuario creamos un archivo de texto plano llamado "parte_3", lo salvamos, salimos y verificamos que esté en lugar adecuado**\
nano parte_3\
ls\
**14. Desde la raíz del usuario abrimos los tres archivos creados, agregamos en cada uno de ellos nuestro nombre al final del texto, lo salvamos y salimos del editor**\
nano parte_2\
nano /home/anadelarue/ejercicios/parte_1\
nano parte_3\
cat parte_2 parte_3 /home/anadelarue/ejercicios/parte_1\
Ana\
Ana\
Ana\
**15. Nos dirigimos al folder donde esta ubicado el archivo "parte_3". Verificamos la ubicación con el comando adecuado**\
cd /home\
pwd\
/home\
**16. Con el comando adecuado copiamos el archivo "parte_3" en el folder donde están los otros dos archivos y verificamos con el comando "tree"**\
sudo mv parte_3 /home/anadelarue/ejercicios/\
ls\
**17. Desde la actual posición en el árbol nos movemos al folder dónde están los tres archivos recien creados (ejercicios). Verificamos nuestra posición**\
cd ejercicios/\
ls\
**18. Con el comando adecuado listamos los archivos del folder donde estamos ubicados**\
ls -l\
**19. utilizamos el comando adecuado para leer los tres archivos simultáneamente, los visualizaremos sus textos en líneas separadas (en el terminal)**\
cat -n parte_1 parte_2 parte_3\
	1. Ana
	2. Ana
	3. Ana\
**20. concatenamos los tres archivos y al nuevo archivo lo llamamos "textoTotal"**\
cat parte_1 parte_2 parte_3 >> textoTotal\
**21. listamos los archivos del folder y verificamos si esta "textoTotal"**\
ls\
**22. Con el editor abrimos "textoTotal" y escribimos "trabajo finalizado". Lo salvamos y salimos**\
nano textoTotal\
cat textoTotal\
Ana\
Ana\
Ana\
Trabajo finalizado\
**23. Ahora borramos o removemos el folder "trabajos"**\
rmdir /home/anadelarue/trabajos/\
**24. Nos movemos desde nuestra posición actual a /home/nuestroUsuario/**\
cd\
**25. desde la raíz del usuario creamos un folder llamado "final"**\
mkdir final\
**26. Copiamos el archivo "textoTotal", de donde esta dicho archivo, al folder "final", utilizamos el path absoluto**\
cp /home/anadelarue/ejercicios/textoTotal /home/anadelarue/final/\
**27. Finalmente borramos el folder "ejercicios"**\
rm -r ejercicios/\
**28. Utilizamos el comando: man cat y leemos las definiciones del comando y los diferentes parámetros. Salimos de este editor de man con la "q"**\
**29. Practicamos diferentes comandos: cal, whoami y ping**\
cal\
whoami\
ping google.com
## Final del ejercicio





 







