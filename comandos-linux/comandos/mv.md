## Comandos mv

El comando **mv** Es para mover o renombrar archivos e igualmente directorios, por si se dan dos nombres de archivo iguales, mv mueve el primer archivo al segundo, install es similar a cp, pero le permite controlar los atributos de los archivos de destino.

1. No le pregunta al usuario antes de quitar el archivo de destino, si este especifica (**-f, -i, o -n**) si no que, lo elimina inmediatamente

    ```bash

    # -f , --force        = No pregunta al usuario antes de quitar un archivo de destino si este verifica con el atributo (-f O --force).
    # -i , --interactive  = Pregunta si se desea sobreescribir el archivo y si la respuesta es no, se omite inmediatamente
    # -n , --no-clobber   = No sobreescribe ningun archivo existente

    #Ejemplos 

    git push -f origin main
    
    mv -i <archivo>
    mv --interactive <archivo>

    mv -n <archivo>
    mv --no-clobber <archivo> 
    ```

2. Mover un archivo a un directorio especifico con la opcion -t, --target-directory

    ``` bash 
    mv --target-directory=. ./maria/Pruebas2

    mv ./maria/Pruebas2 .
    ```

3. Renombrar un archivo o reubicarlo

    ```bash
    # mv <source> <dest>
    # mv <archivo> <archivo_nuevo>
    # mv <ruta>/<archivo> <ruta2>/<archivo2>

    mv ~/Documentos/Pruebas ~/Escritorio/Pruebas
    mv Pruebas Pruebas2
    mv /home/usuario/archivo ~/plantillas/archivo_nuevo_nombre
    ```

