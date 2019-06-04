# enrutados-app
Enrutados App | Universidad EIA ![logo eia](https://github.com/EIA-University/LogosEIA/blob/master/assets/png/logo-eia-icon.png?raw=true)

Enrutados es la estrategia liderada por la oficina de Bienestar Institucional para ofrecer más facilidades de transporte a los estudiantes y empleados.


## Descripción:
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip. 

## Comenzando :rocket:
### Requerimientos
* requerimiento 1
* requerimiento 2


### Importar Un Proyecto
para correr el proyecto:

1. bajar las dependecias de php con composer
    ```
    composer install
    ```
2. bajar las depedencias de frontend con npm 
    ```
    npm install
    ```
4. crear sus variables de entorno 
    ```
    cp .env.example .env
    ```
5. Generar la llave de encritapción 
    ```
    php artisan key:generate
    ```
6. Configurar la BD local acorde a su entorno de desarrollo (En el archico .env  cambiar las variables de entorno)
    ```
    .....

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=homestead
    DB_USERNAME=root
    DB_PASSWORD=secret
    
    ....

    ```

7. Migrar la base de datos y popular sus tablas
    ```
    php artisan migrate --seed
    ```

## Instrucciones de uso:
 para correr el servidor: 


## Recursos
* recurso 1
* recurso 2

## Contribuyendo:
Por favor lee el [CONTRIBUTING.md]() para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.
## Licencia:
Este proyecto está licenciado bajo la Licencia Apache License 2.0  - vea el archivo [LICENSE.md]() para más detalles



