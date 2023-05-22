<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Instalação do Sistema

#### No terminal siga a lista de comandos abaixo:

- git clone https://github.com/Fillipe-Albuquerque-Moreira-Dos-Santos/LaravelEventos
- cd sistema-eventos-laravel
- composer install
- cp .env.example .env
- Configurar o arquivo .env com as informações de conexão da base de dados.
- php artisan migrate

Agora tudo pronto, basta usar o "php artisan serve" e acessar o endereço http://localhost:8000

Estarei disponibilizando o .sql para facilitar a instalação

Foi utilizado uma estrutura de base de dados simples com a tabela de usuarios do proprio laravel, 
uma tabela para persistir os eventos e uma ultima tabela para a compra do ingresso onde ficam salvos o evento, 
quantidade e o usuário.

Qualquer duvida fico a disposição no email "fillipefff@gmail.com"

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
