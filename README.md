# Proyecto línea de comandos

En este proyecto vermos algunos de los comandos básicos de la consola de linux.

## Comandos mas utilizados:

1. cd: Comando para moverse entre archivos. Ej: cd ./Esto/te-lleva/a-este-directorio/
    - .. para acceder al directorio padre del actual Ej: cd ..
  
2. ls: Lista los archivos y directorios (no ocultos) que se encuentren en el directorio deseado. Si no se especifia ruta se referirá al directorio actual. Ej: ls ./listar/archivos-y-directorios/de-este-directorio/
    - -a Lista también los archivos y directorios ocultos.
    - -l lista mas detallada de archivos y directorios.
    - -R lista recursiva de todos los archivos y directorios a partir del directorio a listar.

3. cp: Copia archivo o directorio a directorio objetivo. Si se cambia el nombre del archivo final se copiará con dicho nombre. Ej: cp ./copiar/este-archivo.txt ./en/este-directorio/con-este-nombre.txt
4. mv: Similar a cp, pero mueve el archivo en vez de copiarlo. Ej: mv ./mueve/este-archivo.txt ./a/este-directorio/con-este-nombre.txt
5. rm: Elimina el contenido de un directorio (pero no el directorio). Ej: rm ./Elimina este directorio
    - -r elimina también el directorio (ciudado!!).
6. mkdir: Crea un nuevo directorio en la dirección deseada. Ej: mkdir creame-este-directorio
7. rmdir: Remueve un directorio vacío. (No elimina directorios con contenido!!). Ej: rmdir elimina-este-directorio

## Otros comandos importantes:

1. find: Encuentra el archivo o directorio deseado. Ej: find -name "busca-este-archivo.txt"
    - . Busca en todo el directorio padre. Ej find . -name "...."
    - -type f Busca por tipo (archivo).
2. cat: muestra el contenido de un archivo. Ej cat "este-archivo.txt"


  

     



