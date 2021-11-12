## Comandos rm

El comando **rm** elimina cada archivo dado, Si se da la opción -i o --interactive=option, y hay más de tres archivos o se dan -r, -R o --recursive, rm pregunta al usuario si debe continuar con toda la operación. Si la respuesta es no, se anula todo el comando. De lo contrario, si un contiene -f o --force, o se da la opción -i o --interactive=always, rm solicita al usuario si desea eliminar el archivo. Si la respuesta es no, se omite el archivo.

1. Ignora los archivos inexistentes y los operandos que faltan, y nunca pregunta al usuario. Ignora cualquier opción

    ```bash
    #(-f , --force)

    fuerza para eliminar ese archivo aun asi tenga contenido

    ```



2. Pregunta si desea quitar cada archivo. Si la respuesta es no, se omite el archivo. (-i) (--interactive)

    ```bash

    ```

3. Imprime el nombre del archivo antes de eliminarlo, ademas de eso si existe un archivo que comienza con " - " (la función getopt para analizar sus argumentos, le permite usar la opción '--' ) para indicar que todos los argumentos siguientes no son opciones (rm -- -f o rm ./-f).  (-v) (--verbose)

    ```bash

    ```