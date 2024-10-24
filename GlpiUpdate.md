# Passo a passo para atualizar o GLPI


* GARANTIR UM PONTO DE RESTAURACAO<br>
Estando em modo "sudo", navega ate a pasta /var/www/glpiPortela/files/_dumps e digita o seguinte comando:<br>
`mysql -e "show databases"`
<h6>Este comando é utilizado para verificar o nome do banco de dados ao qual deseja fazer backup antes de iniciar a atualização.</h6>
	
	 
