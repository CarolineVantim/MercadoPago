<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://t.ctcdn.com.br/O0pPRUGzK7iq8p2fZn7WDI5YKkk=/69x23:1332x733/768x432/smart/i364249.png" width="400" alt="Laravel Logo"></a></p>

## About the project

This project aims to make checkout with the Mercado Pago payment tool.

## How to start the project?

Project developed with Laravel. We are using Sail, Breeze and Tailwind.

Firstly, you can clone this project using the following command:
```shell
$ git clone https://github.com/CarolineVantim/MercadoPago.git
```
After that, you can add an alias to make sail easier to use. The command is:
```shell
$ alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'
```
Now, you can run the migrations using the command:
```shell
$ sail artisan migrate
```
