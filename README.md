![git_original_wordmark_logo_icon_146510](https://icon-icons.com/icons2/2699/PNG/128/git_scm_logo_icon_170096.png) 
![git_original_wordmark_logo_icon_146510](https://icon-icons.com/icons2/2648/PNG/128/dev_git_icon_160763.png) 
		
<h2>Comandos Básicos</h2>
	     	 
><h6><b>Iniciar Repositório Local</b></h6>
> git init

><h6><b>Deletar Repositório Local</b></h6>
> rm -rf .git
      	   	         
><h6><b>Adicionar Origem/Destino do Host</b></h6>
> git add remote origin URL 
	        
><h6><b>Fazer uma cópia do repositório Remoto no repositório local.</b></h6>  		
> git clone URL
	
><h6><b>Verificar em que fase de versionamento está o diretório local</b></h6>
> git status 
	      
><h6><b>Adicionar os novos arquivos a staging area</b></h6> 	        	
> git add (nome)/ git add .
	
><h6><b>Criar um commit dos novos dados e adicionar a eles uma mensagem
>de identifição</b></h6>			
> git commit -m  "mensagem"
         
	
><h6><b>Enviar os arquivos do git directory para o repositório remoto</b></h6>		
> git push 

	
<h2>Commits</h2>

><h6><b>Mostrar a linha do tempo dos commits já feitos</b></h6>		
> git log 

><h6><b>Alterar mensagem do ultimo commit realizado</b></h6>
> git commit --amend -m "nova menagem"

><h6>Mostrar ordem cronológica dos commits + as alterações neles feitas.</h6>
>git log -p 
		
<h2>Clonig</h2>

><h6><b>Alterar mensagem do ultimo commit realizado</b></h6>
> git git clone url

<h6>
  <b>
    Obs: Ao clonar um projeto que utiliza as bibliotecas do node execute na pasta referente ao mesmo:
  </b>
</h6>
	
> npm install 

<h6>
  <b>
    Esse comando irá disponibilizar todos os módulos acessiveis no node_modules
  </b>
</h6>
		
<h2>Branches</h2>

><h6><b>Listar Branches Existentes</b></h6>
> git branch

><h6><b>Criar nova branch</b></h6>
> git branch (nome da nova branch)

><h6><b>Criar uma nova branch no repositório local, adicionando assim os asrquivos que já
>foram commitados a mesma</b></h6>
> git checkout -b (nome da nova branch)
	
><h6><b>Navegar entre uma branch e outra</b></h6>        		
> git checkout (nome da branch)

><h6><b>Fazer uma busca por atualizações na branch</b></h6>
>git fetch
		
><h6><b>Criar uma branch correspondente a atual no repositório remoto e enviar os arquivos nela presentes</b></h6>	
> git push --set-upstream origin (nome)
	
><h6><b>Deletar uma branch do diretório local</b></h6>			
> git branch -d (nome)
	
><h6><b>Deletar uma branch do origin(Github) do projeto</b></h6>		        
> git push origin --delete (nome)

		
<h2>Trabalho em Equipe </h2>

Ao ingressar em projeto de grade porte é necessário dobrar o cuidado quanto a criação, manutenção<br>
e exclusão de branches. Para evitar a sobreposição dde arquivos e a perda de projetos, é preciso<br>
seguir algumas boas práticas quanto a ordem de comandos e a lógica por tras de todo o processo de<br>
versionamento.

<h4>Ordem de comandos e Detalhes para se ater</h4>

<ol>
<li>Crie um repositório remoto</li>
<li>Crie uma pasta isolada, correspondente ao diretório local, onde poderá iniciar com<br>
    o comando git init.<br>
	
  Obs: Projetos que conteam uma cli própria serão instalados aqui,<br>
  as demais branchs terão como base o projeto iniciado na master, <br>
  e a navegação entre branches só poderá ser feita ao fim do primeiro<br>
  push...
  
  Outro detalhe a se ater se refere a instalação de dependências; Projetos<br>
  que contém uma cli própria criam uma nova pasta correspondete ao projeto,<br>
  tendo ela suas próprias configurações. É nessa nova pasta que serão instaladas<br>
  novas dependências e onde serão dados comandos referentes a cli do projeto
  </li>
	
<h4>Criando Conexão</h4>

<li>Conecte o diretório local ao repositório remoto com o git remote add origon + url;</li>

<li>Caso o trabalho não demande a criação de uma nova branch, siga com os comandos<br>
    básicos:<br>
    
   git status, git add, git commit -m e git push. As atualizações serão direcionadas para<br>
   a branch master;</li>
    
<h4>Criando uma Nova Branch</h4>

<li>Para criar uma nova branch, use o comando git banch + nome ou git checkout -b + nome.<br>
    Essa branch irá conter uma cópia de tudo o que já sofreu um commit na branch master;</li>
    
<li>Para navegar entre uma branch e outra, use o comando git checkout + o nome da branch;</li>

<li>Para criar um correspondente a nova branch no repositório remoto use o comando:<br>
    git push --set-upstream origin + o nome da branch a ser criada;</li>
</ol>

Casos em que sua contribuição corresponde a uma parte isolada do projeto, onde um de seus superiores<br>
será responsável por fazer o merger com as demais partes, siga os comandos abaixo:

<ol>		
<li>Crie um repositório local para ser seu diretório de trabalho;</li>

<li>Por precaução adicione um origin;</li>

<li>Clone o projeto;</li>		

<li>Crie uma nova branch no diretório de trabalho (Com seu nome ou identificador);</li>

<li>Use o comando git push --set-upstream origin (nome) para criar um origin da sua branch no GitHub;</li>
		
</ol>

E pronto, você pode trabalhar na sua branch e enviar as atualizações para ela periodicamente.<br><br>


![git_original_wordmark_logo_icon_146510](https://cmder.net/img/logo.svg) 

		
<h2>Comandos Básicos</h2>

><h6><b>Criar um novo diretório</b></h6>		        
> md (nome)

><h6><b>Criar multiplos diretórios</b></h6>		        
> md nome1\nome2\nome3

><h6><b>Renomear Diretório</b></h6>		        
> move (nome atual) (novo nome)

><h6><b>Entrar em um diterório</b></h6>		        
> cd (nome)

><h6><b>Sair de um diterório</b></h6>		        
> cd .. (nome)

><h6><b>Listar todos os arquivos dentro do diretório atual</b></h6>	
> ls

><h6><b>Listar todos diretórios com data e hora de criação</b></h6>		        
> dir


<h2>Arquivos</h2>

><h6><b>Cria um arquivo de tipo específico</b></h6>		        
> touch (nome) + terminação 

```ex: touch index.html```
```ex: touch style.css```
```ex: touch index.js```

<h2>Comandos de Delete</h2>

><h6><b>Deletar Pastas de um diterório</b></h6>		        
> rm (nome)

><h6><b>Deletar um diterório vazio</b></h6>		        
> rmdir (nome)

><h6><b>Deletar um arquivo específico</b></h6>		        
> del (nome)

><h6><b>Deletar um diterório e seu conteúdo</b></h6>		        
> del (nome)/s



