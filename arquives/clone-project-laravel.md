## O que fazer após clonar o projeto do github 

Quando você precisa baixar o seu projeto laravel novamente do github você tem que ter o composer instalado e o php instalado com as bibliotecas utilizadas pelo composer
  
1. selecione o caminho do projeto laravel no prompt de comandos
   
4. ainda no prompt de comando digite: `composer install` , após isso o diretório vendor vai ser criado dentro do projeto

5. no projeto você tem criar um arquivo `.env` 

6. copiar as informações do  `.env.example` no `.env`

7. dentro do diretorio  digite comando:
~~~
php artisan key:generate
~~~
após isso será gerado a senha para `.env` no `APP_KEY`

9. depois digite outro comando para limpar o cache:
~~~
php artisan config:cache
~~~
