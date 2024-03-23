# mylaravel-install
Projeto público com passo a passo de instalação do framework [Laravel].

## instalando o LARAVEL
Criando um passo a passo de instalação do Laravel via localhost.

## pré-requisitos
Composer, PHP (server imbutido ou XAMPP) e um SGBD (MySql) instalado.

## acessar a página da documentação do framework

<pre>https://laravel.com/docs/10.x/installation</pre>

## passo 01: comandos via composer laravel:
Entrar no seu diretório local, exemplo:

<pre>C:\xampp\htdocs\</pre>

## passo 02: comandos via composer:
Agora, vamos importar para nosso projeto em [localhost] todas as dependencias do framework Laravel.
Execute via cmd/terminal o comando abaixo:

<pre>composer create-project laravel/laravel lara10</pre>

## passo 03: comandos:
Após concluir a instalação do laravel, a estrutura [raíz] do projeto se modifica, ficando assim:
<pre>C:\xampp\htdocs\lara10\app</pre>

## passo 04: comandos via php::artisan laravel:
Com o (PHP server imbutodo ou XAMPP) inicializado, entro no meu diretório [C:\xampp\htdocs\lara10\app] e via terminal inicializo o servidor [artisan]:

<pre>php artisan serve</pre>

## raíz do framework Laravel
Pronto, a página inicial do framework laravel deve ser exibida em [localhost], exemplo:

<pre>http://127.0.0.1:8000</pre>
