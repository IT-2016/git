## COURS GIT

### Indique la version de git installé sur le poste
`git --version`

### Configure l'auteur des commits 
`git config --global user.name "name"`

### Configure l'adresse email de l'auteur des commits 
`git config --global user.email "email@email.com"`
	
Fichier de configuration git : `$HOME/.gitconfig`

### Initialise un dépot git (Création d'une zone Git dépot vide)
`git init`

### Indique le status du dépot
`git status`

### Ajoute les fichiers à suivre pour en faire le commit après
`git add *`

### Mise en place de la liaison entre un dépot git local et celui distant
`git remote add origin <url>`

### Sauvegarde les modifications dans un commit en local avec le message first commit
`git commit -m "first commit"`

### Envoie tous les commits du dépot local sur le distant
`git push -u origin master`
