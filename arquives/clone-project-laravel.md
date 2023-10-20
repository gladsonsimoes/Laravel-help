## O que fazer após clonar o projeto do github 

Quando você precisa baixar o seu projeto laravel novamente do github
você precisa instalar o composer novamente com as
configurações do <b>composer.json</b> .

1. <a href="configure-php-composer.md"> ter habilitado a extension fileinfo do php </a>
   
3. selecione o caminho do projeto laravel no prompt de comandos
   
4. ainda no prompt de comando digite: <b>composer install</b>, após isso o diretório vendor vai ser criado dentro do projeto

5. no projeto criar um arquivo <b> .env </b>

6. copiar as informações do  <b> .env.example </b> no <b> .env </b>

7. dentro do diretorio  digite comando: <b> php artisan key:generate </b>;
após isso será gerado a senha para <b> .env </b> no <b> APP_KEY </b>

8. depois digite outro comando para limpar o cache: <b> php artisan config:cache </b>
