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
    

## Création d'une nouvelle branche
    $ git branch dev  # création de la nouvelle branche
    $ git branch  # visualisation des branches avec indication de la branche courante
    $ git checkout dev  # changement de branche
    $ git commit -m "Creation d'un branche de dev"
    $ git push -u origin dev
    # git branch --set-upstream-to=repository/branche_distante ma_branche_locale # Permet de suivre le lien entre une branche local et distante. Syntaxe depuis git 1.8 avec "ma_brancheè_locale" en option.

## Fusion d'une branche sur l'autre
__merge__ : fusionne 2 historiques
__rebase__: concerve les deux historiques... ?
    $ git merge dev

## Notes supplémentaires


# Notes
## Pratiques
Faire un **pull avant tout push** sur des projets en équipe puisque le dépot peut avoir été modifié avant sa dernier version du dépot.
