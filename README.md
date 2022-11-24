# Ejercicio 4. Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:

- Haz que tu directorio de trabajo actual sea el directorio padre de tu directorio de
inicio
~~~
cd /home
~~~
listamos 
~~~
ls
~~~
- Visualiza la ruta de tu directorio de trabajo actual.
Para visualizar la ruta absoluta del directorio de trabajo actual usamos el comando:
~~~
pwd
~~~
- Obtén un listado de todos los ficheros/directorios que cuelgan de tu directorio de
trabajo actual.

Para mostrar el listado de los ficheros directorios que cuelgan del directorio actual usamos el comando:
~~~
ls
~~~
- Realiza un listado recursivo de tu directorio de inicio.

Usamos el comando:
~~~
ls -R
~~~
- Obtén la ayuda del comando passwd.

Para obtener la ayuda del comando passwd:
~~~
passwd -h o passwd --help
~~~
- Obtén la fecha y la hora del sistema.

Para obtener la fecha y la hora usamos el comando:
~~~
date
~~~
- Usando un solo comando posiciónate en tu directorio de inicio.

Usamos el comando:
~~~
cd
~~~
- Crea un fichero materias que contenga el nombre de las materias en las que te has
matriculado (cada una en una línea distinta).

~~~
cat > materias
FOL
SI
ED
PRO
LM
BD
~~~
Para salir del fichero usamos ctrl+D
- Con un solo comando, crea dos directorios grado y lru.
~~~
mkdir grado lru
~~~
- Usando un solo comando, mueve tu fichero materias para que cuelgue de tudirectorio grado pero con el nombre asignaturas.
~~~~
mv materias grado/asignaturas
~~~~
- Visualiza los ficheros/directorios de tu directorio de trabajo actual y responde a la
siguiente cuestión: ¿dónde está tu fichero materias?

Para visualizar los ficheros/directorios de mi directorio de trabajo actual:
~~~
ls -l
~~~
El fichero materias está en:
~~~
users/Pablo
~~~
- Posiciónate en tu directorio grado.
~~~
cd grado
~~~
-Elimina el fichero asignaturas 
~~~
rm asignaturas
~~~
- Sube al directorio de inicio.

Nos volvemos a mover al directorio de inicio:
~~~
cd
~~~

- Con un solo comando elimina los directorios creados en el paso i). 
~~~
rm grado lru
~~~
