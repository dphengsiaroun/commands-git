# Utilisation de Git 

Ce projet regroupe toutes les commandes utiles sur Git.

## Les commandes pour créer ou ajouter un dépôt Git
### Create a new repository
````
$ git clone git@git.estiam.com:dany.phengsiaroun/test.git
$ cd test
$ touch README.md
$ git add README.md
$ git commit -m "add README"
$ git push -u origin master
````

### Ajouter un dépôt distant
````
$ cd existing_folder
$ git init
$ git remote add origin git@git.estiam.com:dany.phengsiaroun/test.git
$ git add .
$ git commit -m "Initial commit"
$ git push -u origin master
````

### Dépôt déjà existant
````
$ cd existing_repo
$ git remote add origin git@git.estiam.com:dany.phengsiaroun/test.git
$ git push -u origin --all
$ git push -u origin --tags
````

## Les commandes basiques
### Faire un commit
````
$ git commit -m "Initial commit"
````

### Pousser le commit
````
$ git push -u origin master
````

### Récupérer la dernière version
````
$ git pull
````

## Les commandes pour l'utilisation des branches
### Créer une nouvelle branche
````
$ git branch v1
````

### Basculer entre les branches
````
$ git checkout master
````

