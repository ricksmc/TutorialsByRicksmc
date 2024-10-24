# Step-by-step to update GLPI

<ol>
 <li> Passo 1 - GARANTIR UM PONTO DE RESTAURACAO<li><br>
<h3>estando em modo "sudo", navega ate a pasta /var/www/glpiPortela/files/_dumps e digitar o seguinte comando:<br>
<code>mysql -e "show databases"<code><br>Este comando [e utilizado para
verificar o nome do banco de dados ao qual deseja fazer backup antes de iniciar a atualizacao.
	
	 
