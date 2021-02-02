![git_original_wordmark_logo_icon_146510](https://icon-icons.com/icons2/2406/PNG/128/github_git_icon_145985.png)
		
<h3>Comandos Básicos</h3>
	     	 
<h6><b>Iniciar Repositório Local</b></h6>

> git init

<h6><b>Deletar Repositório Local</b></h6>

> rm -rf .git
      	   	         
<h6><b>Adicionar Origem/Destino do Host</b></h6>

> git add remote origin URL 
	        
<h6><b>Fazer uma cópia do repositório Remoto no repositório local.</b></h6>  
		
> git clone URL
	
<h6><b>Verificar em que fase de versionamento está o diretório local</b></h6>

> git status 
	      
<h6><b>Adicionar os novos arquivos a staging area</b></h6> 	        
	
> git add (nome)/ git add .
	
<h6><b>Criar um commit dos novos dados e adicionar a eles uma mensagem
de identifição</b></h6>		
	
> git commit -m  "mensagem"
         	
<h6><b>Mostrar a linha do tempo dos commits já feitos</b></h6>
		
> git log 
	
<h6><b>Enviar os arquivos do git directory para o repositório remoto</b></h6>	
	
> git push 

	
<h3>Commits</h3>

<h6><b>Alterar mensagem do ultimo commit realizado</b></h6>

> git --amend -m "nova menagem"
		
		
		
<h3>Branches</h3>

<h6><b>Listar Branches Existentes</b></h6>

> git branch

<h6><b>Criar nova branch</b></h6>

> git branch (nome da nova branch)

<h6><b>Criar uma nova branch no repositório local, adicionando assim os asrquivos que já
foram commitados a mesma</b></h6>

> git checkout -b (nome da nova branch)
	
<h6><b>Navegar entre uma branch e outra</b></h6>        	
	
> git checkout (nome da branch)
		
<h6><b>Além de criar uma branch correspondente a atual no repositório remoto, envia os arquivos nela</b></h6>	

> git push --set-upstream origin (nome)
	
<h6><b>Deletar uma branch do diretório local</b></h6>		
	
> git branch -d (nome)
	
<h6><b>Deletar uma branch do origin(Github) do projeto</b></h6>	
	        
> git push origin --delete (nome)

		
<h3>Trabalho em Equipe</h3>
		
Para trabalhar em equipe é necessário seguir os passos adiante:

<ol>		
<li>Crie um repositório local para ser seu diretório de trabalho;</li>

<li>Clone o projeto;</li>		

<li>Crie uma nova branch no diretório de trabalho (Com seu nome ou identificador);</li>

<li>Use o comando git push --set-upstream origin (nome) para criar um origin da sua branch no GitHub;</li>
		
</ol>

E pronto, você pode trabalhar na sua branch e enviar as atualizações para ela periodicamente.
