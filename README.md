# Practica4.2
## En esta práctica hay 3 ejercicios a desarollar

## Ejercicio 1 (crear una nueva rama de un repositorio ya creado)
1. Para empezar debemos colnar un repositorio nuestro con el comando : git clone https://github.com/owner/repo.git
2. Debemos dirigirnos al repositorio que hemos clonado con el comando : cd nombre/repo
3. Creamon una nueva rama en el repositorio que tendrá de nombre "my-branch"con el comando : git branch my-branch 
4. Nos metemos dentro de la rama que hemos creado : git checkout my-branch
5. Ahora editaremos uno de los archivos que tenemos, en mi caso editaré el README.md 
6. Una vez editado el archivo realizamos un : git add README.md
7. Realizamos el commit : git commit -m "my snapshot"
8. Para finalizar realizamos el push para que se suba a nuestro github: git push --set-upstream origin my-branch

### Ahora una fotos de como me ha salido a mi

![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/1aFoto.png) 
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/2aFoto.png)
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/3aFoto.png)

## Ejercicio 2 (crear un nuevo repositorio y subirlo a github)
1. Creamos el repositorio en nuestra máquina con el nombre de "my-repo" con el codigo : git init my-repo
2. Cambiamos al directori my-repo (el reposiotio que acabamos de crear) : cd my-repo
3. Creamos los archivos que queramos subir al repositorio : touch README.md
4. Realizamos un : git add README.md 
5. Hacemos un commit : git commit -m "add README to initial commit"
6. Unimos los repositorios (el de nuestra máquina y el que subimos al github) : git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git
7. Realizamos un push para subir el repositoio con el comando : git push -u origin main

### Fotos del ejercicio 

![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/1aFotoej2.png)
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/2aFotoej2.png)

## Ejericio 3

1. Nos dirigimos a un repositorio que tengamos ya creado con el comando: cd nombre/repo
2. Como lo tenemos subidoal github realizamos un :git pull 
3. Creamos una nueva rama para trabajar con ella : git branch feature-a
4. Cambiamos a la rama que hemos creado con el comando : git checkout feature-a
5. Editamos algun archivo existente en el repositorio en mi caso el README.md: nano README.md
6. Realizamos un git add para confirmar los cambios : git add README.md
7. Realizamos un commit : git commit -m "edit file1"
8. Para subir los cambio hacemos un :git push --set-upstream origin feature-a

## Fotos del ejercicio
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/1aFotoej3.png)
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/2aFotoej3.png)
![commit changes](https://github.com/marloibz/Practica4.2/blob/219838653005067882408472da09037df90ebd1a/3aFotoej3.png)



