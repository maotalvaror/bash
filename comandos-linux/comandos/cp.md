# Comando cp

El comando **cp** sirve para copiar archivos a otros destinos.

1. Comando para copiar un archivo especificado por el usuario

  ``` bash
  # cp [Archivo para copiar] [En donde se va a copiar]
  
  cp [Origen] [Destino]
  ```

2. Copiar un archivo en una ruta relativa

 ``` bash
  # cp texto.txt /home/maria/comandos-linux
  
  cp texto.txt /home/usuario/LaCarpetaLaCualEsDirigida
  ```

3. Copiar archivos en rutas diferentes a la ruta de trabajo
  ``` bash
  # copiando archvvos desde la raiz /
  # ~ Es equivalente a la carpeta del usuario. ~ = /home/<usuario>

  cp ~/Documentos/Maria/bash/README.md ~/Escritorio/
  ```