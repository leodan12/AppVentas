# AppVentas
## ctrlFOOD

Sistema para la venta de comidas y bebidas.

- Registro de usuarios
- CRUD producto
- CRUD clientes
- Registro de ventas
- Lista de ventas realizadas
- Reportes económicos
- Reportes estadísticos

Orientado a restaurants, fondas, pollerias, pensiones, franquicias de comida rápida, etc.

## Instalación

`git clone https://github.com/leodan12/AppVentas.git`

`cd AppVentas`

`composer install`

`cp .env.example .env`

`php artisan key:generate`

Registrar las credenciales de la base de datos, reconpilar, y luego ejecuar las migraciones

`php artisan cache:clear`

`php artisan config:cache`

`php artisan migrate:fresh --seed`

Ejecutar la aplicación web

`php artisan serv`

