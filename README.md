
# exercice_git

git commit : crée une sauvegarde a un moment du projet
git branch : visualise les branches
git log : liste l'historique des commits
git init: transforme le dossier courant en repo git
git add : ajoute un fichier dans le commit

# exercice_git

## Notes de Arnaud

* L'utilisation de git fait appel aux commandes suivantes (notamment mais pas que):
  * **git switch** `<nom de la branche>`: Pour changer de branche.
    Cette commande est très pratique aussi pour créer une branceh à la volée et s'y placer immédiatement, elle s'écrit de la façon suivante: **git switch -c** `<nom nouvelle branche>`
  * **git push** : pour mettre à jour le **repository** distant, une fois que le repository local est clean.
  * **git log** : pour avoir un apperçu des commit effectué



# exercice_git
git init: Initialise un nouveau dépôt Git dans un répertoire. Cela crée un dossier .git caché qui contient tous les métadonnées nécessaires pour suivre les modifications de votre projet.

git add <fichier>: Ajoute des fichiers à l'index de suivi de Git. Cela signale à Git que vous souhaitez inclure les modifications apportées à ces fichiers dans votre prochain commit. Vous pouvez également utiliser git add . pour ajouter tous les fichiers modifiés.

git commit -m "Message de commit": Crée un nouveau commit avec les modifications enregistrées dans l'index. Le message fourni avec l'option -m sert à expliquer brièvement les changements apportés dans ce commit.

git pull: Met à jour votre répertoire de travail local avec les modifications de la branche distante. Cela récupère les dernières modifications du dépôt distant (comme GitHub) et les fusionne avec votre branche actuelle.

git push: Envoie vos commits locaux vers le dépôt distant. Cela met à jour le dépôt distant avec vos modifications locales. Avant de pousser, assurez-vous d'avoir d'abord récupéré les derniers changements avec git pull pour éviter les conflits de fusion.

  
# exercice_git
#Les 5 meilleures commandes git : git add, git commit. Git branch et git switch. git push