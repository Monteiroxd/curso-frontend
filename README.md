# curso-frontend

# GIT
## Conceitos de versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua

 Arquivo A  | Versão 1 | Versão 2
 Arquivo B  | Versão 1 | Versão 2

 ## Instalação do Git
https://git-scm.com/

- Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git

 ## Criar conta no GitHub

 ## Clonar o projeto
 git clone https://github.com/cavalcantemmarcelo/curso-frontend.git

 ## Commits
 Informação de alteração
 - após testado todo seu código
 -git add *
 -git commit -m 'mensagem'
 -git push (enviar para repositório)
 -git pull (puxar / trazer alterações do GITHUB para minha maquina)


 

 > git add *
 > git commit -m "mensagem"
 > git push (enviar alterações para o repositório GitHub)
 > git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

### Branch
São ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: Critério de aceite
- versonamento 1.0.0

git checkou -b (cria uma branch)
git checkout master (muda de branch)


### merge
Mescla de branch
você pode precisar resolver conflitos manualmente

git merge main 

### pull requests
mescla de branchs no repositório
permite code review
O repositório resolve os conflitos automaticamente

## configurar o GITflow
git flow init
git flow feature start {nome-da-feature}

