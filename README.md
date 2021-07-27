# Glossaire Git et Git-Hub

- git init

- git statusGlossaire Git

- git config --global user.name "iulian"
- git config --global user.email "iulian@....campus.fr"
- git init "Nom du dossier" = c'est pour dire que ça c'est un dossier Git
- git remote add origin "Lien GitHub" = pour lier son dossier PC à GitHub (au main)
- git remote add fork "Lien GitHub" = pour lier sa branche GitHub à son dossier PC
- git remote -v = pour voir le listing des remotes
- git branch "NomDeLaBranche" = créer une branche
  Faire git branch -a pour afficher la liste des branches sur le serveur
- git pull origin main = mise à jour de notre version locale du code avec les dernières modifications d'un repo de GitHub.
- git pull origin "Nom de la branche" = pour tirer sur son PC les dossiers et fichiers de GitHub
- git add . = ajouter toutes les modifs qu'on a fait dans une boîte (on peut également - git add "Nom du fichier" si on veut seulement ajouter un fichier)
- git commit -m "Nom du commit" = créer un commit avec le message correspondant
- git push = envoyer nos commits (modifications) sur le repository GitHub
- git push fork main = pour pousser le contenu de sa boite (ses modifs) vers GitHub
- git push --set-upstream origin {prenom-nom} = Dit à Github qu'il doit créer ma branche également sur github.com et pas seulement en local
- git checkout main "ou" nom de la branche = aller sur la branche nommée
- git merge {prénom-nom} = --> Applique les changements de la branche vers la branche "main"
  git-clone = Cloner un dépôt dans un nouveau répertoire.

- git pull = git fetch plus git merge

- repository ou remote = le lieu où sont stockés tous les fichiers sources du projet. Le dépôt peut être un répertoire local sur la machine ou un répertoire distant sur un serveur git.

- git log --oneline --decorate --graph
  il affiche le statut actuel
