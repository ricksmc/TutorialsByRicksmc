# Passo a passo para atualizar o GLPI


* GARANTIR UM PONTO DE RESTAURACAO<br>
Estando em modo "sudo", navega ate a pasta /var/www/glpiPortela/files/_dumps e digita o seguinte comando:<br><br>
`mysql -e "show databases"`<br><br>Este comando é utilizado para verificar o nome do banco de dados ao qual deseja fazer backup antes de iniciar a atualização.<br>
Sabendo o nome do banco executa o seguinte comando:<br><br> `mysqldump **nome_do_banco** > anomesdia.sql`<br><br>Para saber se o backup foi realizado com sucesso, basta dar o
seguinte comando:<br><br>`tail -1 anomesdia.sql`<br><br>Se aparecer a mensagem **dump completed** significa que o backup está íntegro, podendo então passar para o próximo passo.
	
	 
