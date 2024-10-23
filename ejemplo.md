# 2DO METODO PARA CREAR Y ACTUALIZAR UN REPOSITORIO POR PRIMERA VEZ

1. Creamos el directorio
2. Generamos nuestros archivos o codigo. En nuestro podemos editar un archivo llamado ejemplo.md.
3. Utilizamos el comando git init
4. Luego el comando que vincula el link con el repositorio:
    *  git remote add origin https://github.com/sebastianVP/git_23102024_test.git

5. Para verificar el estado: git status
6. Luego, para añadir al area de stagging: git add ejemplo.md
7. Para agregar al respositorio de manera local y añadir un identificado usamos el comando:
git commit -m "1er Comentario"
8. Luego el comando git status para verificar el estado.
9. Luego para subir nuestros cambios: git push
10. Aqui se genera un mensaje de error y esto solo ocurre una vez, por ser la primera vez debemos colocar el siguiente comando.
 git push --set-upstream origin master

11. Cualquier cambio en adelante solo seguiremos la secuencia:

    * git status

    * git add nombre_del_archivo(ejemplo.md)

    * git commit -m "Nombre de la actualizacion"

    * git push


