# TP Git - Exo 1

## Création d'un dépôt

    $ touch .gitignore
    $ git init
    $ git add README.md
    $ git commit -m “First commit”
    $ git branch -M main
    $ git remote add origin https://github.com/MFranckFR/gitExo
    $ git push -u origin main

## Annulation d'un commit
    Modifier le fichier
    $ git commit -a -m "Un commit à annuler"
    $ git log
    $ git reset HEAD^1  # annulation du dernier commit
    


