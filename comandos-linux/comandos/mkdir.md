## Comandos mkdir 

El comando **mkdir** crea directorios con el nombre especificado, crea cada nombre de directorio en el orden dado. Informa de un error si el nombre ya existe.
  
1. Forma en la que se crean directorios.

    ``` bash
    mkdir [option]… name…
    ```

**Opciones (Option)**

1. Normalmente el directorio tiene los bits (**Un bit es, entonces, la unidad mínima empleada en informática, se utilizan números binarios y aritmética lógica (operaciones aritméticas (suma, resta)).** de modo de archivo deseados en el momento en que se crea.
  
    ``` bash
    # Esta opción se utiliza para establecer los modos de archivo, es decir, permisos, etc. para los directorios creados.
    # -m, --mode = mode
    # mkdir -m a=rwx [directories]

    mkdir -m a=rwx home
    mkdir -m a =r home
    ```

    Las sintaxis anterior especifica que los directorios creados dan acceso a todos los usuarios para leer, escribir y ejecutar el contenido de los directorios creados. 
    Puede usar 'a =r' para permitir que solo todos los usuarios lean desde los directorios, etc.


2. Hace que falten directorios primarios para cada argumento, estableciendo sus bits de permiso de archivo en '=rwx,u+wx', es decir, Ignora los directorios primarios existentes y no cambie sus bits de permiso de archivo. Si también se da la opción -m, no afecta a los bits de permiso de los directorios primarios recién creados.


    ```bash
    # Un indicador que permite al comando crear directorios primarios según sea necesario. 
    # Si los directorios existen, no se especifica ningún error.
    # -p, --parents
    
    mkdir -p [directories]
    mkdir -p first/second/third
    ```

    Si el primer y segundo directorio no existen, mkdir creará estos directorios. Si no especificamos la opción -p, y solicitamos la creación de directorios. 
    Aparece la siguiente salida
    
    ```
    'first/second/third': No such file or directory  
    ==  'primero/segundo/tercero': No existe tal archivo o directorio
    ```

3. Imprime un mensaje por cada directorio creado (con -v).

    ``` bash
    # mkdir -v <nombre_nuevo>

    mkdir -v NuevoDirectorio
    ```
    
    El mensaje que aparece es : 
    
    ```
    mkdir: created directory 'NuevoDirectorio'
    ```
