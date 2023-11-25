# GIT## Acessar 
>Chrome git-scm.com

## Realizar Donwload do GIT, versão atual 2.43.0

## Instalar o GIT, seguindo o padrão do instalador (Next-Next)

## Verificar versão instalada
> git -v
> 
    //git version 2.43.0.windows.1

## Criar ou escolher um diretorio para configurar o repositório do git
> mkdir projeto 

## Acesse o diretório
> cd projeto 

## inicializar o armazenamento em repositório git
> git init
        //Initialized empty git repository in projeto/.git/

## configurações de dados de usuário 
> git config --local user.name "Usuário"
> git config --local user.email "usuario2007@gmail.com"


## Verificar mudanças
> git status 

## Preparar as mudanças para serem salvas 

## Para preparar apenas um arquivo
> git add file
> #### Para preparar todos os arquivos (quando queremos todos os aquivos)
> git add .


## Salvar as mudanças (commit)
> git commit -m "Mensagem do Commit"
>
    O Parametro "-m" define que estamos informando uma mensagem referentes aos códigos que estamos salvando. 


## Remover Login GIT do Terminal


git config --global --unset user.name

git config --global --unset user.email

git config --unset-all credential.helper


## Clonar um projeto (Baixar projeto)
> git clone https://github.com/Rickpadilha/projeto.git
> 
"usuario" nome do usuario git;

"proejto" projeto que sera baixado;

## Apos a conclusão do download // Acessar o diretorio do projeto clonado 

> cd projeto 


## Para visualizar no editor vscode
> code .
