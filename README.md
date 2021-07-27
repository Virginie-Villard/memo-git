# memo-git

pwd : afficher chemin du répertoire actuel

Markdown (.md) façon d'écrire du code

repository (repo) = dépôt git
répertoire initialisé
le repo distant = remote

git remote affiche tous les repo avec -v (vew)

git commit = équivelent d'un enveloppe, on peut mettre plein de choses dedans (le mieux c'est de faire un commit même s'il y a très peu de changement tant que c'est significatif et que ça a une action définie)

git status = indique s'il y a des changements ou pas à faire (si "clean" pas de changement)

git log = liste les commits faits et en cours
donne : les anciens commits avec l'ID de chaque commit / l'auteur / la date / le message du commit
q pour quitter le log

git add = ajoute des fichiers à commiter, add permet de prendre en compte un changement sur le fichier en question, il peut même s'agir d'un delete (du coup on add un delete)

git diff = différence entre l'état actuel et le dernier commit (affiche juste le changement).

(S'il y en a, le mieux c'est ignorer les fichiers desktop.ini grace au fichier .gitignore (attention au .txt)).

~ = home

mv = moove

man = manuel

git push -u (ou --set-upstream (= "en amont")) pour se souvenir de chemin du push pour tout le projet
git push origin(fichier) master(branche)

git pull = comporte git fetch (télécharge le distant en local) et git merge
git fetch est utile pour travailler en local en attente d'un merge (soit pour travailler en hors connexion soit pour gérer les conflits plus tard)

git clone (= créer le repo et le pull)
git init

ls liste des fichiers du dossier en cours

git log --oneline(les commit se suivent plus condensés) --decorate --graph (visualiser les différentes branches le long des commits)
branches (= univers parrallèle) pour bosser en local avant de pouvoir revenir merge sur le distant

dans github "issues" : nom-du-commit fix #(ID de l'issue)

fork (voir la capture d'écran)

