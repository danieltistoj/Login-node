## Login 
### Inicio 
>Con esto creamos el package.json que es un archivo con informacion del proyecto
>npm init --yes
## Modulos 
- express: para escribir el codigo del servidor de forma resumida 
- mongoose: biblioteca que permite conectar node.js a mongodb. Se debe de tener instalado la base de datos de mongo instalado antes, ya que mongoose es solo un driver que permite conectarnos
- ejs-mate: motor de plantilla 
- connect-flash: nos permite enviar mensajes entre multiples paginas
- morgan: nos permite ver las peticiones 
- passport: permite hacer la autenticación. Tambien tiene funcionalidades para hacer autenticaciones con servicios de terceros, como google, GitHub, etc. 
- passport-local: para hacer autenticaciones de manera local
- bcryptjs: permite cifrar la contraseña

>npm i express mongoose ejs-mate connect-flash morgan passport passport-local bcrypt-nodejs
- bcrypt-nodejs puede estar obsoleta, asi que instalar alguna de las sugerencias que nos de el instalador 
## Dependencias de desarrollo 
- nodemon: Es para no tener que reiniciar el servidor a mano, esto no es un modulo en si, sino una dependencia. Osea que el proyecto puede funcionar sin esto, pero esto nos ayudara a hacer tareas repetitivas


