# Commande GIT

## Fichier Hello.txt

`` git clone https://github.com/Baptise-lm/mds_test_git.git ``
<br>
`` git status ``
<br>
``git add .``
<br>
``git commit -m "commit txt"``
<br>
``git push``
<br>

## Creation d'une Erreur

``git add .``
<br>
``git commit -m "erreur 1"``
<br>
``git log``
<br>
``git commit --amend``
<br>
``git reset HEAD^``

## Creation Conflit

``git pull``
<br>
``git add .``
<br>
``git commit -m "Plus de Conflit"``
<br>
``git push``
<br>

## Creation de Branche

``git branch``
<br>
``git branch uneidee``
<br>
``git checkout uneidee``
<br>
``git checkout main``
<br>
``git branch -d uneidee``
<br>

## Creation de Tag

``git log``
<br>
``git tag v1.0 24e187a2cc9a7034b3446d98b17127afd42b2d68``
<br>
``git push --tags``
<br>
``git tag -d v1.0``
<br>

## Recherche

``git grep "piou"``
<br>
