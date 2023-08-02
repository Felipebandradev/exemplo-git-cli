# Exemplos de operações básicas para git via ClI

## Comandos de uso Geral da Cli

- Criar pasta: mkdir nomepasta
- Lista conteudo : dir
- Limpar tela: cls
- Entrar na pasta: cd nomepasta

## Comandos pricipais do Git

- Verificar usuario/email:

   `git config user.name`  e  `git config user.email`

- Mudar de usuario e e-mail de forma global:

    `git config --global user.name "Seu nome como quiser` <br>
    `git config --global user.email "seuemail@provedor.com`

- Inicializar um repositorio (Executado dentro da pasta):

   `git init`

- renomear a branchs: 

    `git branch nome-branch-atual novo-nome-para-branch` <br>
    para renomear a branch de **master** para **main** (novo padrão),usaríamos: `git branch master main`

- Verificar status atual do repositorio:

  `git status`

- Adicionar (tornar arquivo rastreavel) ao monitoramento do git:

    `git add nomedoarquivo` ou `git add .`

- Fazer commit das alterações(salvar no historico) :

    `git commit -m "Texto da menssagem sobre está alteração"`

- Adicionar/conectar o repositorio remoto ao local:

    `git remote add origin endereco-do-repositorio.git`

- Copiando/baixando um repositório para a máquina remota:

    `git clone endereço-do-repositorio.git`

- Enviar as mudanças para o github(Push):

    `git push origin main`