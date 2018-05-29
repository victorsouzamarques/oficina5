# oficina5
<p>Primeiramente extrair o arquivo que se encontra dentro do projeto "oficina5..." e depois executar os comandos no cmd, na pasta pai do projeto.</p>
<p>composer dump-autoload</p>
<p>composer update</p>

<p>Depois crie um banco com o nome "oficina5"!</p>

<p>Abrir o cmd e digitar o comando: php -i |find /i "Configuration File"
O comando mostrará o arquivo de configurações e o caminho em que ele se encontra.
Copiar o caminho que se encontra em Loaded "Configuration File" após a seta.
Apertar "Windows + E" e digitar na barra de busca o caminho copiado.
Um arquivo de texto se abrirá. Apertar "Ctrl + F" e buscar pela seguinte linha: extension=php_pdo_mysql.dll
Se a linha não for encontrada, colá-la na ultima linha do arquivo de texto.
Reiniciar o xampp.</p>

<p>após criar faça o comando php artisan migrate e logo após php artisan serve</p>
