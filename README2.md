# Simulacro de exámen

## Repositorio masterpidgey-simulacion
- Creo un repositorio vacio en mi perfil de GitHub llamado masterpidgey-simulacion:
![1](/imagenes/1.png)
- A continuación clonamos este repositorio en local con el comando "git clone" seguido del enlace del repositorio:
![2](/imagenes/2.png)

## README
- Creamos un archivo README con algun contenido en su interior. Usamos el comando nano para crear y modificar dicho archivo:
![3](/imagenes/3.png)
![4](/imagenes/4.png)

## Commit inicial
- Ahora vamos a hacer el primer commit. Para ello debemos añadir los ficheros modificados con el comando "git add" seguido de los archivos modificados o tambien podemos usar "git add ." para agregar todos los ficheros modificados de una vez. Una vez agregados todos los ficheros podemos procedir a hacer el commit, para ello debemos usar el comando "git commit -m" seguido del mensaje de dicho commit:
![5](/imagenes/5.png)

## Push inicial
- El siguiente paso consiste en realizar un push del repositorio. Usaremos el comando "git push nombre_de_la_rama". En este caso la rama a la que debemos hacer push el la rama main:
![6](/imagenes/6.png)

- Si vamos a nuestro repositorio de GitHub podemos ver que los cambios se han subido correctamente:
![7](/imagenes/7.png)

## Ignorar archivos
- Creamos en el repositorio local un fichero llamado privado.txt con el comando "touch".
![8](/imagenes/8.png)
- Creamos en el repositorio local una carpeta llamada privada con el comando "mkdir".
![9](/imagenes/9.png)
- Para que tanto el archivo como la carpeta sean ignorados por git debemos crear un archivo ".gitignore" y dentro de el debemos introducir el nombre del archivo y el nombre de la carpeta.
![10](/imagenes/10.png)
![11](/imagenes/11.png)

## Añadir fichero 1.txt
- Creamos en el repositorio local un fichero llamado 1.txt con el comando "touch".
![12](/imagenes/12.png)

## Crear el tag v0.1
- Para crear un tag debemos usar el comando "git tag" seguido del nombre del tag:
![13](/imagenes/13.png)

## Subir el tag v0.1
- Para subir la rama con el tag v0.1 debemos utilizar los comandos mencionados antiriormente (git add, git commit y git push) seguido de "origin v0.1":
![14](/imagenes/14.png)

## Crear una tabla
- Creamos una tabla en el README.md:
![15](/imagenes/15.png)

## Colaboradores
- Debemos agregar a Máximo como colaborador del repositorio. Debemos entrar en dicho repositorio - Setting - Collaborators - Add people:
![16](/imagenes/16.png)

# Primeras Contribuciones
### Fork
- Realizar un fork del repositorio first-contributions:
![17](/imagenes/17.png)
### Clone
- Clonamos el repositorio en local:
![18](/imagenes/18.png)
### Branch
- Nos ubicamos en el repositorio clonado y creamos una nueva rama con el comando "git checkout -b nombre-rama". Gracia a este comando nos ubicamos dentro de la rama creada.
![19](/imagenes/19.png)
### Cambios y Commit
- Creamos un md con nuestro nombre y después realizamos los pasos necesarios para realizar un commit:
![20](/imagenes/20.png)
### Push
- Realizamos un push del repositorio con el comando "git push origin nombre-rama":
![21](/imagenes/21.png)
### Submit
- Vamos al repositorio de GitHub y clicamos en "Compare and pull request":
![22](/imagenes/22.png)
- Por último clicamos en "Create pull request":
![23](/imagenes/23.png)
![24](/imagenes/24.png)