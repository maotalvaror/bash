# Comando touch

El comando **touch** actualiza la fecha de acceso y modificación de cada FICHERO a la hora actual.
Adicionalmente, se puede crear ficheros con este comando.


1. Cambia solamente la fecha de acceso
    ``` bash
      # touch -a <file>

      touch -a Pruebas.txt
    ```

2. Examina y utiliza CADENA en lugar de la fecha actual
    ``` bash
      # touch -d, --date=CADENA

      touch --date="2021-11-12" Prueba.txt 
      touch --date="2020-07-21 14:19:13.489392193 +0530"   Prueba.txt
    ```

3. Cambia solamente la fecha de modificacion
    ``` bash
      # touch -m <file>

      touch -m Prueba.txt
    ```

4. Modificar un archivo unicamente si este existe
    ``` bash
    
    touch no_crear.txt --no-create
    ```