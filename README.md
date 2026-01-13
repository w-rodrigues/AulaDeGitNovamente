## Aprendendo novamente Git

Aqui vou deixar anotações de comandos e algumas explicações. 

# Na pasta: 

Click com o botão direito e selecione Open Git Bash Here

# Arq readme.md 
Vai ser instruções e apresentação do projeto.

# Comandos: 

Git init - Inicia o reposiitório vazio

Git Add + nome do Arq - Manda os arq para a area de "stage"
Pense que voce vai se apresentar, mas tem que aguardar a saida do pessoal que ja esta no palco... o Git Add é o sinal que mostra que logo voce vai entrar em cena. 

Git Status - Nos mostra o que esta acontecendo no momento 

Commits são versões da nossa "história" o palco do nosso Cód. 

Git commit -m "..." - Dessa forma criamos o commit e dentro das " " colocamos o titulo do nosso commit. 

Git branch -M "Main": Altera a nomenclatura de Master para Main. 

To desconfiando que se quisermos escrever qualquer coisa tem que adicionar o -M antes HEHE 

Para adicionar o repositório do seu PC para o GitHub. Clique no botãozão verde para adicionar um novo repositório. 
Coloque o nome do repositório igual o do seu projeto ou pasta do projeto, importante por uma descrição para se orientar.

Feito isso o proprio GitHub vai te passar um passo a passo do que fazer em seguida.

Primeiro passo: 
Git remote add origin - Git (remote) Conexão (add) Adiconar (origin) Nome do Repositórito + Link 

Segundo passo: 
Git push -u origin main - Onde estamos dando o "empurrão" dos commits do repositório local para o repositório remoto. Origin (nome) Main (branch)

PRONTO, VINCULAMOS NO GITHUB.

Clear - Comando que limpa a bash