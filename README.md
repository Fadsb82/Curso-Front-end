# Curso-front-end


## GiT
## Conceitos de versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua

 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

 ## Instalação do Git
 https://git-scn.com/

 - Windows: https:/git-scn.com/download/win
 - Linux (apt-get): sudo apt-get install git
 - Mac (brew): brew install git

 ## Criar uma conta no GitHub

 ## Clonar o projeto

 ## Commits
 Informação de alteração
 - após testado todo seu código
 - git add *
 - git commit -m "mensagem"
 - git push (Enviar informações para o repositório GitHub)
 - git pull (Puxar trazer alterações do Github para sua máquina)
 
 ## GitFlow
 Fluxo do Git

 ### branchs
 São ramificações / Versões paralelas

 - main / master (vai para produção, quando o projeto é publicado)
 - develop
 - DOD Definicion of done: Critérios de aceite
 - versionamento 1.0.1

 git checkout -b dev (Cria uma branch)
 dit checkout master (Mudar de branch)

 ### Merge
 Mescla de brenchs
 você pode precisar resolver os manualmente

 git merge main

 ### pull Requests
 Mescla de branchs no repositório
 permite code review
 o repositório resolve os conflitos automaticamente

 ### Configura o GitFlow
 git flow init
 git flow feature start {nome-da-feature}
