# Version de Git  2.47.1

# Taller Desarrollo colaborativo con Git y GitHub

#Integrantes:
* María Castro
* Danna Guzmán


# 1. Estructura base del repositorio
* Se crean las carpetas desde la terminal de almalinux 9

![Captura 1](../img/1.png)

* Uso de la herramienta Cursor IA, donde se debe conectar con el WSL: Almalinux-9 y abrir un proyecto con las carpetas creadas anteriormente
![Captura 2](../img/2.png)


# 2. Creación del repositorio

# Comandos para crear el repositorio
* git init
* git commit -m "Primer commit"
* git branch -M main
* git remote add origin https://github.com/Dxguz/GestorRecetas_DM.git
*git push -u origin main

* La estudiante 1 creó un repositorio en github y subió los archivos, con la estructura solicitada, por medio de la ejecución de comandos en la terminal.
![Captura 3](../img/3.png)


# 3. Clonación del repositorio

# Comandos para crear el repositorio
* git init
* git clone https://github.com/Dxguz/GestorRecetas_DM.git

* La estudiante 2 aceptó la invitación de colaboradora en el repositorio, y lo clonó en la ruta que se ve en la imagen.
![Captura 4](../img/4.png)


# 4. Creación de ramas

# 4.1. Rama feature/recetas-colombianas (Integrante Danna Guzmán)
![Captura 5](../img/5.png)
![Captura 5.1](../img/5.1.png)

* Commit 1 en rama feature/recetas-colombianas
![Captura 6](../img/6.png)

* Commit 2 en rama feature/recetas-colombianas
![Captura 7](../img/7.png)

* Commit 3 en rama feature/recetas-colombianas
![Captura 8](../img/8.png)


# 4.2. Rama feature/recetas-mexicanas (Integrante Danna Guzmán)
![Captura 9](../img/9.png)

* Commit 1 en rama feature/recetas-mexicanas
![Captura 9.1](../img/9.1.png)

* Commit 2 en rama feature/recetas-mexicanas
![Captura 10](../img/10.png)

* Commit 3 en rama feature/recetas-mexicanas
![Captura 11](../img/11.png)



# 4.3. Rama feature/recetas-italianas (Integrante María Castro)
![Captura 12](../img/12.png)

* Primer commit en la rama feature/recetas-italiana
![Captura 13](../img/13.png)

* Segundo Commit en la rama feature/recetas-italiana
![Captura 14](../img/14.png)
 
* Tercer Commit en la rama feature/recetas-italiana
![Captura 15](../img/15.png)
![Captura 15.1](../img/15.1.png)


# 5. Fusión mediante pull request (PR) en GitHub.

# Crear pull request 

* Seleccionar la opción Compare & pull request 
![Captura 16](../img/16.png)

* Dar un nombre para el pull request y en la opción de reviewers seleccionar al otro integrante para que este pueda aprobar los cambios generados y así fusionarlos en la rama main.
![Captura 17](../img/17.png)

* Registro de la solicitud de revisión
![Captura 18](../img/18.png)

# Aprobar pull request
![Captura 19](../img/18.png)



# 6. Conflicto intencional en el archivo recetas/colombianas.md y resolverlo correctamente. 

* Integrante 1 (Danna Guzmán)
* En la rama feature/recetas-colombianas se agrega texto en la línea 20 y se sube el cambio a github con su respectivo commit.
![Captura 20](../img/20.png)

* Integrante 2 (Maria Castro)
*En la rama feature/recetas-colombianas se agrega texto también en la línea 20 y se sube el cambio a github con su respectivo commit, y así se evidencia el error ya que anteriormente se han hecho cambios en esta sección.
![Captura 21](../img/21.png)

* Para resolver el conflicto, se hace un git pull y luego se edita el archivo manualmente, eliminando los marcadores de conflicto y manteniendo la información que sea realmente necesaria.
![Captura 22](../img/22.png)

* También se puede solucionar el conflicto desde GitHub.
![Captura 23](../img/23.png)

* Una vez eliminada la información innecesaria, se genera un último commit con los cambios finales.
![Captura 24](../img/24.png)


# 7. Usar .gitignore para excluir algún archivo temporal

* En el archivo .gitignore se debe anotar el nombre de los archivos que no deben subirse al repositorio, en este caso es server.log. Al aparecer sombreado levemente se indica que este archivo no estará en el repositorio.
![Captura 25](../img/25.png)



# 8. Crear un tag v1.0.0 sobre el commit final.  

* Lista de commits hechos en el proyecto
![Captura 26](../img/26.png)

* Verificar que el tag aparece en el repositorio
![Captura 27](../img/27.png)

# Fin de la documentación