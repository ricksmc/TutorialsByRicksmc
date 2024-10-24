# Passo a passo para atualizar o GLPI


* GARANTIR UM PONTO DE RESTAURACAO
Estando em modo "sudo", navega ate a pasta /var/www/glpiPortela/files/_dumps e digitar o seguinte comando:
<h3>`mysql -e "show databases"`</h3>
<h3>Este comando é utilizado para verificar o nome do banco de dados ao qual deseja fazer backup antes de iniciar a atualização.</h3>
	
	 
