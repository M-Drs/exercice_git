# exercice_git
git init: Initialise un nouveau dépôt Git dans un répertoire. Cela crée un dossier .git caché qui contient tous les métadonnées nécessaires pour suivre les modifications de votre projet.

git add <fichier>: Ajoute des fichiers à l'index de suivi de Git. Cela signale à Git que vous souhaitez inclure les modifications apportées à ces fichiers dans votre prochain commit. Vous pouvez également utiliser git add . pour ajouter tous les fichiers modifiés.

git commit -m "Message de commit": Crée un nouveau commit avec les modifications enregistrées dans l'index. Le message fourni avec l'option -m sert à expliquer brièvement les changements apportés dans ce commit.

git pull: Met à jour votre répertoire de travail local avec les modifications de la branche distante. Cela récupère les dernières modifications du dépôt distant (comme GitHub) et les fusionne avec votre branche actuelle.

git push: Envoie vos commits locaux vers le dépôt distant. Cela met à jour le dépôt distant avec vos modifications locales. Avant de pousser, assurez-vous d'avoir d'abord récupéré les derniers changements avec git pull pour éviter les conflits de fusion.