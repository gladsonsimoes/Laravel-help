## habilitando o extension fileinfo do php.ini , para instalar as dependências do php :
Atenção!!! faça depois da instalação do composer!

### Habilitar a extensão fileinfo no arquivo php.ini:

#### 1. Abra o arquivo <b> php.ini </b> localizado:
-   Windows: <b> C:/php/php.ini </b> 
-   Linux: <b> etc/php/<versão do php>/cli/php.ini </b>
#### 2. Procure pela linha que contém <b> ;extension=fileinfo </b>
(pode estar comentada com um ponto e vírgula no início).
#### 3. Remova o ponto e vírgula para descomentar a linha, ficando apenas <b> extension=fileinfo </b>.
#### 4. Salve as alterações e reinicie o servidor PHP.

---
b. Ignorar a verificação da extensão fileinfo:

- Abra o terminal ou prompt de comando.
- Navegue até o diretório onde o Composer está instalado.
- Execute o comando <b> composer  --ignore-platform-req=ext-fileinfo install</b> .
- Essa opção informa ao Composer para ignorar temporariamente a verificação da extensão fileinfo.
