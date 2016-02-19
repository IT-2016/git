## COURS GIT

[GIT SCM](https://git-scm.com/)

[Emulateur de commande pour Windows](http://cmder.net/) (Download full)

## Indique la version de git installé sur le poste et si GIT est reconnu par le poste
`git --version`

## Configure l'auteur des commits 
`git config --global user.name "name"`

## Configure l'adresse email de l'auteur des commits 
`git config --global user.email "email@email.com"`
	
Fichier de configuration git : `$HOME/.gitconfig`

## Initialise un dépot git (Création d'une zone Git dépot vide)
`git init`

## Indique le status du dépot
`git status`

## Ajoute les fichiers à suivre pour en faire le commit après
`git add <file>`
`git add *`

## Mise en place de la liaison entre un dépot git local et celui distant
`git remote add origin <url>`

## Sauvegarde les modifications dans un commit en local avec un message
`git commit -am 'Commentaire pour le commit'`

## Envoie tous les commits du dépot local sur le distant
`git push -u origin master`

## Clone le dépot distant sur le local
`git clone <url>`

## Récupére les nouveaux commits du distant
`git pull`

### Process Habituel
Au commencement : `git clone <url>`
A chaque nouveau fichier : `git add *`
A chaque modification de fichier : `git commit -am 'Commentaire pour le commit'`
A la fin de la journée : `git push`



