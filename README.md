# Projeto de Aplicação Web com Laravel e Redis

## Descrição

Este projeto é uma aplicação web desenvolvida com o framework Laravel e utiliza o Redis como sistema de armazenamento de dados em cache. O objetivo do projeto é demonstrar como utilizar o Redis para melhorar a performance da aplicação e reduzir a carga no banco de dados MySQL.

## Funcionalidades

* Utilização do Redis como sistema de armazenamento de dados em cache
* Implementação de cache para reduzir a carga no banco de dados
* Utilização do Laravel como framework para desenvolvimento da aplicação
* Implementação de rotas e controladores para gerenciar as requisições e respostas da aplicação

## Configuração do Redis

* O Redis é configurado no arquivo `config/database.php` como um sistema de armazenamento de dados em cache
* A conexão com o Redis é estabelecida utilizando o driver `predis`

## Utilização do Cache

* O cache é utilizado para armazenar os resultados das consultas ao banco de dados
* O cache é configurado para expirar após um período de tempo definido

## Rotas e Controladores

* As rotas são definidas no arquivo `routes/web.php` e são utilizadas para gerenciar as requisições e respostas da aplicação
* Os controladores são utilizados para processar as requisições e retornar as respostas

## Modelos

* Os modelos são utilizados para representar as tabelas do banco de dados
* Os modelos são definidos no diretório `app/Models`

## Exemplos de Uso

* A rota `/noticia` é utilizada para exibir as notícias armazenadas no cache

## Requisitos

* PHP 7.4 ou superior
* Laravel 8.x ou superior
* MySQL 8.x ou superior
* Redis 6.x ou superior

## Instalação

1. Clone o repositório do projeto
2. Execute o comando `composer install` para instalar as dependências
3. Configure o arquivo `env` com as informações de conexão com o banco de dados e o Redis
4. Execute o comando `php artisan migrate` para criar as tabelas do banco de dados
5. Execute o comando `php artisan cache:clear` para limpar o cache

## Contribuição

* Contribuições são bem-vindas!
* Por favor, abra uma issue para discutir as mudanças antes de fazer um pull request.
