# Examen Laravel

Este proyecto fue generado con [Laravel 8](https://laravel.com/docs/8.x)

## Instalar aplicación Laravel

El backend se encuentra desarrollado en Laravel 8, el cual provee mediante API Rest al Front en Angular

Para instalar el Backend ejecute las siguientes instrucciones:

1. Descargar repositorio `git clone https://github.com/sivegm77/laravel.git`
2. Instalar dependencias `composer update`
3. Ejecutar `php artisan serve` para desplegar el servidor de desarrollo `http://127.0.0.1:8000//`. La aplicación se cargará automáticamente.

##### Usuario Prededterminado
User: sivegm@gmail.com
Pass: 123456

##### APIS
* Para REGISTRO de usuario `http://127.0.0.1:8000/api/register`
**Method**: POST
**Form Data**: name(string), email(string), password(string), password_confirmation(string)
**Response**: user(array)
* Para LOGIN de usuario `http://127.0.0.1:8000/api/login`
**Method**: POST
**Form Data**: name(string), email(string), password(string)
**Response**: user(array), token(string)
* Para LOGOUT de usuario `http://127.0.0.1:8000/api/logout`
**Method**: POST
**Authorization**: token(string)
**Response**: message(string)


## Instalar aplicación Angular
El FrontEnd se encuentra desarrollado en Angular 11, consume servicios de API Rest desde un backend construido en Laravel 8
1. Descargar repositorio `git clone https://github.com/sivegm77/angular.git`
2. Instalar paquetes `npm install`
3. Ejecutar `ng serve -o` para desplegar el servidor de desarrollo `http://localhost:4200/`. La aplicación se cargará automáticamente.





