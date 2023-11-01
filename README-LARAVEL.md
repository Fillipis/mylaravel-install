## mylaravelapp --install
Criando um passo a passo de instação do Laravel via localhost.

## pré-requisitos
Github ou Gitbash instalados e o Composer.

## acessar a página da documentação do framework
<pre>https://laravel.com/docs/10.x/installation</pre>

## comandos via composer laravel - passo 01:
Entrar no seu diretório local, exemplo:
<pre>C:\xampp\htdocs\mylaravelapp\</pre>

## comandos via composer - passo 02:
Executar via cmd/terminal o comando:
<pre>composer create-project laravel/laravel mylaravelapp</pre>

## comandos - passo 03:
Após concluir a instalação do laravel, a estrutura [raíz] do projeto se modifica, ficando assim:
<pre>C:\xampp\htdocs\mylaravelapp\app</pre>

## comandos via php::artisan laravel - passo 04:
Com o XAMPP já inicializado, entro no meu diretório [../mylaravelapp/app] via terminal inicializo o servidor [artisan]:
<pre>php artisan serve</pre>

## comandos via composer laravel - passo 05:
Pronto, a página inicial do framework laravel deve ser exibida em [localhost], no meu exemplo:
<pre>http://127.0.0.1:8000/mylaravelapp/app/public</pre>
