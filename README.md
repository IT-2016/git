# COURS GIT

## Logiciel

[GIT SCM](https://git-scm.com/)

[Emulateur de commande pour Windows](http://cmder.net/) (Download full)

## Vérification
- Disponnibilité et version de git sur le poste : `git --version`

## Configuration
- Fichier de configuration de git : `$HOME/.gitconfig`
- Configure l'auteur des commits : `git config --global user.name "name"`
- Configure l'adresse email de l'auteur des commits : `git config --global user.email "email@email.com"`

## Initialisation
- En local
  - Initialise un dépot git __local__ : `git init`
  - Mise en place de la liaison entre un dépot git local et celui distant : `git remote add origin <url>`
- Depuis le distant
  - Clone le dépot distant sur le local : `git clone <url>`

## Commande usuel
- Ajoute les fichiers à suivre : `git add <file>` et `git add *`
- Sauvegarde les modifications dans un commit en local avec un message : `git commit -am 'Commentaire'`
- Envoie tous les commits du dépot local sur le distant : `git push -u origin master`
- Récupére les nouveaux commits du distant : `git pull`

## Commande supplémentaire
- Indique le status du dépot : `git status`

### Process Habituel
- Création du dépot sur Github.
- Au commencement : `git clone <url>`
- A chaque nouveau fichier : `git add *`
- A chaque modification de fichier : `git commit -am 'Commentaire pour le commit'`
- A la fin de la journée : `git push`



