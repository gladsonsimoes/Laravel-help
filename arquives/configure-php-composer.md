## habilitando o extension fileinfo do php.ini , para instalar as dependências do php :
Atenção!!! faça depois da instalação do composer!

### Habilitar a extensão fileinfo no arquivo php.ini:

#### 1. Abra o arquivo <b> php.ini </b> localizado:
-   Windows: `C:/php/php.ini` 
-   Linux: `etc/php/<versão do php>/cli/php.ini`
#### 2. Procure pela linha que contém `;extension=fileinfo` 
#### 3. Remova o ponto e vírgula para descomentar a linha, ficando apenas `extension=fileinfo` .
#### 4. Salve as alterações e reinicie o servidor PHP.

---
b. Ignorar a verificação da extensão fileinfo:

- Abra o terminal ou prompt de comando.
- Navegue até o diretório onde o Composer está instalado.
- Execute o comando `composer --ignore-platform-req=ext-fileinfo install`.
- Essa opção informa ao Composer para ignorar temporariamente a verificação da extensão fileinfo.
