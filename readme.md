Essai GIT
===

SSH
---
- Création d'un clef SSH
- Ajout de la clef SSH dans l'IHM GIT

Repo
---
- Création d'un repository dans l'IHM GIT ou via git init
- clone sur le client

1er fichier
---
- Ajout d'un fichier (celui-ci)
- git status
- git remote -v
- git add readme.md
- git commit -m "Message"

- git config --global user.name Gildas
- git config --global user.email g.noel@ackwa.fr

- git branch pour lister branches dont la courante

- git remote add …. pour déclarer la cible

- Création --> add -> commit --> push
                |
  Modification -+
  
- Attention si git commit -m "message" -a vs add/commit
- Attention à l'usage de git rm
- Deux cas de suppressions : 

    - Local & distant     git rm xxx
    - Distant seulement   git rm --cached xxx 

- le rm nécessite un commit et un push
- git log pour l'historique
- git diff (xxx)

- git checkout pour revenir en arrière sur un code ou un commit
- A ne pas utiliser si poussé !?

- Le checkout va créer une branche
- Si checkout pour retrouver log alors : git log master

A voir
===
- Changement passphrase
- Localisation config
- PHPStorm
- git revert

Documentation GIT
===
Create a new repository on the command line : 
