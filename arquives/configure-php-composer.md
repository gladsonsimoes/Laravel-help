## habilitando o extension fileinfo do php.ini , para instalar as dependências do php :

a. Habilitar a extensão fileinfo no arquivo php.ini:

- Abra o arquivo <b> php.ini </b> localizado no windows em <b> C:\php\php.ini </b>  ou no linux <b> etc/php/<versão do php>/cli/php.ini </b> , no seu editor de texto preferido.
- Procure pela linha que contém <b> ;extension=fileinfo </b>
(pode estar comentada com um ponto e vírgula no início).
- Remova o ponto e vírgula para descomentar a linha, ficando apenas <b> extension=fileinfo </b>.
- Salve as alterações e reinicie o servidor PHP.


b. Ignorar a verificação da extensão fileinfo:

- Abra o terminal ou prompt de comando.
- Navegue até o diretório onde o Composer está instalado.
- Execute o comando <b> composer  --ignore-platform-req=ext-fileinfo install</b> .
- Essa opção informa ao Composer para ignorar temporariamente a verificação da extensão fileinfo.
