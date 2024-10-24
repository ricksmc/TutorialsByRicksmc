# Passo a passo para atualizar o GLPI


* GARANTIR UM PONTO DE RESTAURACAO
Estando em modo "sudo", navega ate a pasta /var/www/glpiPortela/files/_dumps e digitar o seguinte comando:
				`mysql -e "show databases"`
>Este comando é utilizado para verificar o nome do banco de dados ao qual deseja fazer backup antes de iniciar a atualização.
	
	 
