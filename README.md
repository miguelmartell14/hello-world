# hello-world

# Primera prueba github

Bienvenido al primer curso de Progración en C. En primera instancia, se trabajará todo desde linux, 
en específico en la distribución Ubuntu 20.04.

En esta primera sección se abarcara un breve explicación de los comandos básicos en terminal, así como un pequeño
tutorial de Github, para que quien este interesado pueda ir subiendo sus progresos en su propio repositorio y si desea
mandar alguna correción que encuentren en este repositorio ir sugiriendo cambios.

Shorcut para abrir terminal: Control + Alt + T 

De manera más normal se puede dar Inicio y escribir Terminal. Inicio -> Terminal.
Ya que tenemos nuestra terminal vamos a mostrar los comandos mas sencillos y útiles en terminal.

## Comandos:


**ls**: Muestra los archivos y carpetas que se encuentran en la ruta actual

**ls -a**: Muestra los archivos y carpetas incluidos archivos ocultos en la ruta actual.

** cd**: Nos lleva a la ruta raiz

**cd ..**:Nos lleva una carpeta atras

**cd . **:Nos mantiene en la misma carpeta

**cd ~/carpeta/subcarpeta/ **: Nos mueve entre carpetas

**mv archivo nuevaruta**: Nos ayuda a mover un archivo de una carpeta a otra

**mv archivo nuevonombre**: Esta misma función tambien puede ser usada para cambiar el nombre del archivo

**cp archivo**:
**pwd**: Imprime la ruta actual

**rm archivo**: Borra un archivo, (nota: Tener mucho cuidado con esta función) [Checar](http://linuxcommand.org/lc3_man_pages/rm1.html)

**cat**: Te muestra la visualización de un archivo.

**zip archivo **: Sirve para comprimir archivos en formato zip

**unzip archivo**: Sirve para descomprimir un archivo en formato zip

**Nota**: Para escribir un espacio en ruta usar "\ ".Pe. "~/carpeta/sub\ carpeta/"

**nano**: Editor de texto básico util para escribir archivos muy sencillos.

**vim**: Editor de texto mas avanzado con más utilidades, que en lo personal estaré usando durante para hacer todo este repositorio.

Dentro de linux se encuentran otro variedad de terminaciones de archivos comprimidos,
Los comandos mas utiles para comprimir son *tar* y *gzip*. Cada uno con sus respectivos de compresión

Donde tar usa banderas que va seguidas después de un comando p.e. *tar -c*. Hay diferentes tipos de bandera y 
cada una le da instrucción específica al comando en este caso las mas comunes son:

**-c**: Indica a tar que cree un archivo(es decir, que va comprimir)

**-v**: Va mostrando los archivos a comprimir o descomprimir(verbose)

**-f**: sirve para indicar el nombre del archivo a descomprimir

**-x**: Indica a tar que va a abrir un archivo(es decir, que va a descomprimir)

**-t**: Lista el contenido del archivo .tar

**-z**: Se usa para aclarar que usa compresión gzip

**-j**: Para hacer un archivo muy comprimido(formato *.tar.bz2*)

## Ejemplo 1
 si queremos ver la lista de elementos de un archivo sin descomprimirlo tenemos:

'''tar -tf archivo.tar'''

## Ejemplo 2
Si queremos descomprimir un archivo .tar.gz

'''tar -xzvf archivo.tar.gz'''

## Ejemplo 3
Para comprimir un archivo en formato .tar.gz
'''tar -czvf ruta/sub\ carpeta/archivo'''

### gzip

Sirve para archivos con terminación **.gz**. Tiene dos banderas básicas:

**-9 **: para comprimir con mayor nivel compresión

**-d**: para descomprimir

Se recomienda hacer ejercicios de prueba, intentando comprimir archivos y descomprimiendolos para asegurarse que se aprendió
lo básico de compresión.

Existen muchísimos comando pero considero que son los comandos más basicos que nos pueden servir para iniciar a usar la terminal,
conforme se vaya avanzando en el repositorio se iran viendo posiblemente mas comando, y será habitual su uso.

Dejo al final una lista con los mas comunes, [aquí](https://courses.cs.washington.edu/courses/cse390a/14au/bash.html)


Existen muchos 
Use la pagina :

https://linuxhint.com/git_tutorial_beginners/

para entender como modificar archivos.
