## Despliegue de apps Spring Boots en Heroku

Crear el arcrhivo `system.properties` en el proyecto

```
java.runtime.version = 17
```

1. Crear cuenta en heroku.com y github.com
2. Tener congfigurado git en el ordenado
    1. git config --global user.name "xXXXx"
   2. git config --global user.email zzzz@gmail.co
3. Suibr el proyecto a Github desde inteliJ desde la opcion : VCS > share to Github
4. Desde Heroku, c rear app yu elegir el método Github y buscar el repositorio subido 
5. Habilitar el Deploy automatico
6. Apretar Botn de Deploy

# 1 Ejercicio 

* P¨robar empaquetar la aplicacion de maven package desde IntelliJ 
* Desde terminal en IntelliJ verificar que se ejecuta correctamente con el comando :
```
java -jar target/OB-Spring-Dejloy.jar
```

*Crear un perfil para dev y oto para test con una propiedad nueva que carguemos en el contyrolador

## Ejercicio 2

* Desplegar la aplicacion de Laptops en hEROKU y probarla con POSTMAN

### pROVEEDORES cloud

* HEROKU -- JAVA, Spring, PostgreSQL
* Netlify -- Frontend (React, Angular, ...)
* Vercel -- Frontend (Reac, Angulas, ...)