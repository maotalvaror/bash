# Comando ls


1. Listar contenido del directorio actual
  ``` bash
  ls
  ```

2. Ver ayuda en consola del comando **ls**
  ```bash
  # Ver ayuda del comando

  ls --help
  ```

3. Ejemplos
  ``` bash
  # ls <directorio>
  # ls /home/<usuario>

  ls /home
  ls /home/maria

  # -a, para listar todo el contenido del directorio, incluyendo carpetas o archivos ocultos 
  ls -a /home

  # -A, para listar todo su contenido excluyendo los directorios . y ..
  ls -A /home 

  # -l, listar contenido con metadata
  ls -l /home

  # Combinaciones -al o -Al
  ls -al /home
  ls -Al /home
  ``` 
