
![git_original_wordmark_logo_icon_146510](https://cdn.icon-icons.com/icons2/2157/PNG/512/github_git_hub_logo_icon_132878.png)
		
<h1>Comandos Básicos</h1>
	     	 
<b>Iniciar Repositório Local</b>

> git init

<b>Deletar Repositório Local</b>

> rm -rf .git
      	   	         
<b>Adicionar Origem/Destino do Host</b>

> git add remote origin URL 
	        
<b>Fazer uma cópia do repositório Remoto no repositório local.
Ação muito importante no inicio de um novo projeto, ou na criação
de uma nova branch</b>	  
		
> git clone URL
	
<b>Verificar em que fase de versionamento está o diretório local</b>

> git status 
	      
<b>Adicionar os novos arquivos a staging area</b> 	        
	
> git add (nome)/ git add .
	
<b>Criar um commit dos novos dados e adicionar a eles uma mensagem
de identifição</b>		
	
> git commit -m  "mensagem"
         	
<b>Mostrar a linha do tempo dos commits já feitos</b>
		
> git log 
	
<b>Enviar os arquivos do git directory para o repositório remoto</b>	
	
> git push 
	
<h1>COMMITS</h1>

<b>Alterar mensagem do ultimo commit realizado</b>

> git --amend -m "nova menagem"
		
		
		
<h1>BRANCHES</h1>

<b>Criar nova branch</b>

> git branch (nome da nova branch)

<b>Criar uma nova branch no repositório local, adicionando assim os asrquivos que já
foram commitados a mesma</b>

> git checkout -b (nome da nova branch)
	
<b>Navegar entre uma branch e outra</b>        	
	
> git checkout (nome da branch)
		
<b>Além de criar uma branch correspondente a atual no 
repositório remoto, envia os arquivos nela presentes para o repositório remoto</b>	

> git push --set-upstream origin (nome)
	
<b>Deletar uma branch do diretório local</b>		
	
> git branch -d (nome)
	
<b>Deletar uma branch do origin(Github) do projeto</b>	
	        
> git push origin --delete (nome)
	
		
<h1>TRABALHANDO EM EQUIPE</h1>
		
Para trabalhar em equipe é necessário seguir os passos adiante:

<ol>		
<li>Crie um repositório local para ser seu diretório de trabalho;</li>

<li>Clone o projeto;</li>		

<li>Crie uma nova branch no diretório de trabalho (Com seu nome ou identificador);</li>

<li>Use o comando git push --set-upstream origin (nome) para criar um origin da sua branch no GitHub;</li>
		
<li>E pronto, você pode trabalhar na sua branch e enviar as atualizações para ela periodicamente.</li>
	
</ol>	
	
