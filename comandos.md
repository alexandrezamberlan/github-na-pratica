# Comandos Git para terminal

## clonar repositório

    git clone endereço-github

## criar nova branch e ir para ela
    git checkout -b nome-nova-branch

## criar nova branch e permanecer na main ou em branch
    git branch nome-nova-branch

## mostrar as branchs criadas e a ativa
    git branch

## analisar o status do repositório/branch
    git status

## para começar a enviar arquivos para o servidor github
    <!-- para enviar todos os arquivos criados ou alterados -->
    git add . 

    <!-- para enviar somente o arquivo .gitignore -->
    git add .gitignore

    <!-- para criar um 'envelope de envio' com dados de quem esta fazendo o envio -->
    git commit -m "texto explicativo do que esta indo para o github"

    Atenção!! Na primeira vez, o git instalado na máquina vai precisar autorizar
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"

    <!-- para enviar as alterações locais ao servidor github na branch ativa -->
    git push