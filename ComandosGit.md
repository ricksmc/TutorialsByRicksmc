# Working with Git/GitHub on Linux CLI

Before create the local repository, verify if git is installed on your PC. If you don't have git, use this command below:

	$ sudo apt install git

After installation, proceed with SSH generation for utilize on GitHub

### Steps to generate SSH Keys

 - on Linux CLI use the command -  $ ssh-keygen -t ed25519 -C "youremail@example.com"
 - Initialize the SSH Agent using the following command - $ eval "$(ssh-agent -s)"
 - Copy the SHA1 Public Key stored in .ssh directory (utilize the command $ cat idxxxx.pub to view the key and copy the text)
 - Access your GitHub and settings find the option SSH and GPG Keys, Press the New SSH Ke buttom, add a name in tittle, e.g MyPC and in Key box paste the SHA1
copyed.
 - add the private key on ssh-agent using the following command ($ ssh-add ~/.ssh/id_ed25519)  
 
## Step by step to create local repository

<ol>

 <li> On Linux terminal use the folowwing command to create a local repository

	$ sudo mkdir FolderName
 </li>
 <li> Configure the folder where your project is stored with permissions to execute the VSCode using this coomand:

	$ sudo chown -R ricksmc GitHub/
 </li>
 <li> Inicialize the git and configure the user that will work on the project with the commands below: 
	$ git init
	$ git config --global user.email "myemail@examplecom"
	$ git config --global user.name GithubNickname

 <li> Clone the repository from GitHub using the following command:

	$ git clone SSH Key Code
 </li>
 <li> To open the project over VSCode directly on the CLI Linux, access the directory where the project is localized and use the command "code ./"</li>
</ol>
<em><strong>P.S - Inside the direcory where do you are storage your project, example: /home/ricksmc/GitHub<em><strong>

If you've made changes to your project and are no longer going to work for theday, it's recommended to "push" it to GitHub. To do this, use the following command
described below:

 - <b>$</b><em>git add *</em>
 - <b>$</b><em>git commit -m "DescribeHereTheChanges"</em>
 - <b>$</b><em>git push origin</em> 




