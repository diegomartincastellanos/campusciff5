# campusciff5
Ejercicios GIT, GITHUB y MARKDOWN

A continuación se muestran los resultados de los ejercicios realizados:

# 2.1 Crear un repositorio campusciff5

![picture alt](https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Creacion%20Repositorio%20campusciff5.png?raw=true)

# 2.2 Clonar repositorio campusciff5 en local

![picture alt](https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Clonar%20Repositorio.png?raw=true)

# 2.3 Crear en repositorio local el documento README.md

Completado

# 2.4 Añadir al README.md los comandos utilizados y realizar un commit

git add README.md

git commit -m "Añadir commit inicial"

![picture alt](https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Añadir%20Commit%20Inicial.png?raw=true)

# 2.5 Subir cambios al repositorio remoto

git push git@github.com:diegomartincastellanos/campusciff5.git

![picture alt](https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Push%20SSH.png?raw=true)

Si hemos modificado en remoto un archivo, por ejemplo README.md, y queremos hacer un PUSH desde local es necesario antes realizar un PULL para dejar constancia de las modificaciones de remoto en local y evitar problemas. Al realizar el PULL se produce una MERGE. El sistema nos pide añadir un mensaje para el commit.

# 2.6 Crear archivo privado.txt y carpeta privada

touch privado.txt

mkdir privada

# 2.7 Ignorar archivo privado.txt y carpeta privada

![picture alt](https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Gitignore.png?raw=true)

# 2.8 Añadir fichero 1.txt al repositorio local

touch 1.txt

git add 1.txt

git commit -m "Añadir 1.txt"

![picture alt] (https://raw.githubusercontent.com/diegomartincastellanos/campusciff5/8443ae1ee8d9e5a92662e85e6a52c2ee8c9a265a/img/Añadir%201.png)

# 2.9 Crear un tag v0.1

git tag -a v0.1 -m "Tag v0.1"

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Crear%20tag%20v02.png?raw=true)

# 2.10 Subir los cambios al repositorio remoto

git push git@github.com:diegomartincastellanos/campusciff5.git

# 2.11 Crear una rama v0.2

git branch v0.2

git checkout v0.2

git branch

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Crear%20Rama%20v02.png?raw=true)

# 2.12 Añadir un fichero 2.txt en rama v0.2

touch 2.txt

git add 2.txt

git commit -m "Añadir 2.txt en rama v0.2"

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Añadir%202%20en%20v02.png?raw=true)

# 2.13 Subir los cambios al repositorio remoto

git push git@github.com:diegomartincastellanos/campusciff5.git v0.2

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Github%20Subir%20cambios%20rama%20v02.png?raw=true)

# 2.14 Posicionarse en la rama master y hacer un merge de la rama v0.2

git checkout master

git merge v0.2

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Fusionar%20master%20v02.png?raw=true)

# 2.15 En la rama master poner Hola en 1.txt

git checkout master

echo "Hola" > 1.txt

git add 1.txt

git commit -m "Añadir Hola en 1.txt"

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Añadir%20Hola.png?raw=true)

# 2.16 En la rama v0.2 poner Adios en 1.txt

git checkout v0.2

echo "Adios" > 1.txt

git add 1.txt

git commit -m "Añadir Hola en 1.txt en la rama v0.2"

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Añadir%20Adios.png?raw=true)

# 2.17 Posicionarse en la rama master y hacer un merge con la rama v0.2

git checkout master

git merge v0.2


# 2.18 Lista ramas merged y not merged

git branch --merged

git branch --no-merged


# 2.19 Arreglar el conflicto

Mientras no resuelvas el conflicto no es posible cambiar de rama

git add 1.txt

git commit -m "Resolver conflicto Hola y Adios"

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Merge%20resuelto.png?raw=true)

# 2.20 Crear un tag v0.2 y borrar la rama v0.2

git tag -a v0.2 -m "Tag v0.2"

git branch -d v0.2

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Crear%20tag%20v02.png?raw=true)

# 2.21 Listar los distintos commits, tags y ramas

git list

![picture alt] (https://github.com/diegomartincastellanos/campusciff5/blob/master/img/Commit%20Ramas%20Tags.png?raw=true)

# 2.22 Poner foto de perfil y doble faltor de autentificación


# 2.23 Preguntar los nombres de usuario de GitHub. Seguir los repositorios campusciff del resto de tus compañeros y añadir una estrella 



# 2.24 Crear una tabla de este estilo en el fichero README.md con la información de varios de tus compañeros de clase

| NOMBRE | GITHUB |
| ------ | ------ |
| Sergio Torres |  https://github.com/sergiotorrespalomino |
| Ulises Ojeda |  http://github.com/ulisesojeda |


























