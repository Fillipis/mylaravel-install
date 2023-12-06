# mylaravelapp
Projeto público de estudos com o framework [Laravel].

# minhas configurações de máquina
Editor de texto VS Code, Xampp (3.3.0), MariaDB (15.1), Gitbash e Composer instalados.

# política de versionamento (github)
Passo 1: entrar no seu diretório local, exemplo:
<pre>C:\xampp\htdocs\</pre>

Passo 2: clonar o projeto [MYLARAVELAPP]:
<pre>git clone git@github.com:Fillipis/mylaravelapp.git</pre>

# metodologia de versionamento (gitflow)
Passo 1: entrar no diretório do projeto clonado:
<pre>C:\xampp\htdocs\mylaravelapp\</pre>

Passo 2: iniciar o gitflow:
<pre>git flow init</pre>

Passo 3: deixar as branch's por padrão/opcional do gitflow:
<pre>[master] e [develop]</pre>

Passo 4: deixar os prefixos por padrão/opcional do gitflow:
<pre>[feature], [hotfix] e [...]</pre>

# instalando o LARAVEL
Criando um passo a passo de instalação do Laravel via localhost.

## pré-requisitos
Github ou Gitbash instalados e o Composer.

## acessar a página da documentação do framework
<pre>https://laravel.com/docs/10.x/installation</pre>

## comandos via composer laravel - passo 01:
Entrar no seu diretório local, exemplo:
<pre>C:\xampp\htdocs\mylaravelapp\</pre>

## comandos via composer - passo 02:
Agora, vamos importar para nosso projeto em [localhost] todas as dependencias do framework Laravel.
Execute via cmd/terminal o comando abaixo:
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
