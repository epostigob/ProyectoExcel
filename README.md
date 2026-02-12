# ProyectoExcel

Desarrollo de proyecto de excel de registro de actividades de ocio



#### **Instrucciones para subida a git**



Primera subida



**Inicializa git en el equipo, primero es necesario tener instalado git desde https://git-scm.com/install/windows**

git init



**Añade el archivo README.md si no existe**

git add README.md



**Agrega todos los archivos al commit, si en lugar de todo solo se quiere añadir un archivo concreto o una carpeta se añade en lugar del .**

git add .



**Creación del commit**

git commit -m "Primera subida"



**Si no está realizada la autentificación hay que modificar las variables globales de usuario y email**

&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



**Mueve a la rama principal**

git branch -M main



**Conecta con el repositorio online**

git remote add origin https://github.com/usuario/ProyectoExcel.git



**Subimos los cambios**

git push -u origin main



**En caso de error se realiza la siguiente llamada y acto seguido se llama al comando anterior**

git pull --rebase origin main



