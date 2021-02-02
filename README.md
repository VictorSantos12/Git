#VERSIONAMENTO DE PROJETOS COM GIT
		
<h1>Comandos Básicos<h1>
	     	 
Iniciar Repositório Local

git init

Deletar Repositório Local

rm -rf .git
      	   	         
Adicionar Origem/Destino do Host

git add remote origin URL 
	        
Fazer uma cópia do repositório Remoto no repositório local.
Ação muito importante no inicio de um novo projeto, ou na criação
de uma nova branch	  
		
git clone URL
	
Verificar em que fase de versionamento está o diretório local

git status 
	      
Adicionar os novos arquivos a staging area 	        
	
git add (nome)/ git add .
	
Criar um commit dos novos dados e adicionar a eles uma mensagem
de identifição		
	
git commit -m  "mensagem"
         	
Mostrar a linha do tempo dos commits já feitos
		
git log 
	
Enviar os arquivos do git directory para o repositório remoto	
	
git push 
	
COMMITS


		
BRANCHES

Criar uma nova branch no repositório local, adicionando assim os asrquivos que já
foram commitados a mesma

git checkout -b (nome da nova branch)
	
Navegar entre uma branch e outra;        	
	
git checkout (nome da branch)
		
Além de criar uma branch correspondente a atual no 
repositório remoto, envia os arquivos nela presentes para o repositório remoto;	

git push --set-upstream origin (nome)
	
Deletar uma branch do diretório local;		
	
git branch -d (nome)
	
Deletar uma branch do origin(Github) do projeto;	
	        
git push origin --delete (nome)
	
		
		
TRABALHANDO EM EQUIPE
	
Para trabalhar em equipe é necessário seguir os passos adiante:
	
Crie um repositório local para ser seu diretório de trabalho;

Clone o projeto;		

Crie uma nova branch no diretório de trabalho (Com seu nome ou identificador);

Use o comando git push --set-upstream origin (nome) para criar um origin
da sua branch no GitHub;
		
E pronto, você pode trabalhar na sua branch e enviar as atualizações para ela	periodicamente.
	
	
	
