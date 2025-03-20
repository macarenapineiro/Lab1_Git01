# Laboratorio 1 - Git 101

### Introducción:
En primer lugar, se va a diferenciar lo que es Git de GitHub. 
Git es una herramienta que sirve para gestionar cambios realizados en un código fuente utilizando una serie de comandos que realizan diferentes acciones. Mientras que GitHub es una plataforma en donde se encuentran y administran los diferentes repositorios creados.

El objetivo de este laboratorio es poder ponernos en contacto con Git y GitHub, refrescar la memoria con el uso de los comandos y familiarizarnos con las diferentes funciones como los repositorios locales y remotos. 

### Desarrollo:
Se creó una carpeta en mi caso con el nombre sistemas_operativos, para luego en la terminal acceder a la carpeta y ejecutar el comando `git init` para crear un repositorio local.
Se crea un archivo .md con el nombre README que en primer lugar se puso como descripción el siguiente texto: 

![image](https://github.com/user-attachments/assets/bde7bfe7-6554-4c96-a39a-1160e917b6ca)

Luego se ejecuta el comando `git status`, el cual va a aparecer el nuevo archivo que se tiene que agregar, ejecutandose en la terminal `git add README.md` para agregarlo al repositorio y `git commit -m ""` para subir el cambio realizado.

![image](https://github.com/user-attachments/assets/8401d8f1-af70-495e-b067-dcef09cd2e56)

Para crear una nueva rama en el repositorio se utiliza el comando `git branch develope` y `git checkout develope` para cambiar a esa rama. Se realiza un cambio en el README.md agregando una nueva descripción. 

![image](https://github.com/user-attachments/assets/4bb1af00-bf6a-433a-855f-02d27378e796)
Por consiguiente se ejecuta en la terminal los comandos anteriormente utilizados `git add` y `git commit -m ""` para subir los cambios a la rama.
Como siguiente paso se cambia a la rama master `git checkout master` y se agregan los cambios realizados en develope con el comando `git merge develope`.
En GitHub se crea este repositorio remoto y se conecta con el repositorio local utilizando en la terminal `git remote add <nombre> <URL>`, se suben los cambios al repositorio remoto con `git push --set-upstream <Nombre>`

### Conclusiones: 
Durante este laboratorio aprendí a crear un repositorio local, ya que desde siempre trabaje con un repositorio remoto clonandolo para trabajarlo de forma local, pero en esta instancia se realizó de forma opuesta trabajando de forma local para luego crearlo de forma remota. Además de la forma de crear el README.md fue nueva para mi ya que al crear un archivo de forma local para luego subirla al repositorio fue algo que no lo he realizado antes. 
Me resulto complicado comprender en primer lugar el como crear el README.md para luego agregarlo al repositorio ya que como he comentado anteriormente no lo realicé antes. Sin embargo el resto de los comandos y acciones a realizar fueron algo que yo ya he realizado con anterioridad y me encontraba familiarizada.

