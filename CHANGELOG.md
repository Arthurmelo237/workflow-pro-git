# Etapes de ma creation Workflow

- Etape1: Creation d'un depot local 

- Etape2: Creation d'un depot Github

- Etape3: Relier mon depot local et mon depot Github
Voici en gros à quoi ces commandes servent. 



1. echo "# jknjnu" >> README.md

    Crée un fichier README.md avec le contenu "# jknjnu"

    >> ajoute le texte au fichier (le crée s'il n'existe pas)

    Le # crée un titre en format Markdown

2. git init

    Initialise un nouveau dépôt Git dans le dossier courant

    Crée le dossier caché .git qui contient toute l'historique

3. git add README.md

    Ajoute le fichier README.md à la zone de staging (préparation pour commit)

    Git commence à tracker les modifications de ce fichier

4. git commit -m "first commit"

    Crée un premier commit avec le message "first commit"

    Sauvegarde l'état actuel des fichiers dans l'historique Git

5. git branch -M main

    Renomme la branche par défaut de "master" à "main"

    -M force le renommage (move)

6. git remote add origin 

    Ajoute une connexion vers le dépôt distant sur GitHub

    origin est le nom conventionnel pour le dépôt principal

7. git push -u origin main

    Pousse les commits locaux vers GitHub

    -u définit la branche main comme upstream (par défaut pour les futurs push)

- Etape4: Nous sommes passer a la Creation des branches
# feature
# develop
# test
# fix

- Etape5: Passer d'un branche a une autre puis ajoute certaines fonctionalite a chaqu'une d'elle

- Etape6: Fusionner c'est branches
Fusionner feature → develop
Fusionner fix → develop
Fusionner develop → test
Fusionner test → main