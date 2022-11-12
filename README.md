## Despliegue de apps de Spring Boot en Heroku

1. Crear archivo 'system.properties' en el proyecto con el contenido:
   java.runtine.version=19 (o la que sea)
2. Crear cuenta en heroku.com y github
3. Tener configurado git en el ordenador. La primera vez que se instala github
   1. git config --global user.name "Gabriel"
   2. git config --global user.email tuemail
4. Subir el proyecto a Github desde IntelliJ IDEA desde la opción: VCS > Share project on Github
5. Desde Heroku, crear app  y elegir método Github y buscar el repositorio subido.
6. Habitilar deploy automático y ejecutar el Deploy