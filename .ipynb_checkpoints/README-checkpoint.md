# MachineLearning propose quelques notebook Jupyter en Python

A partir d'Onyxia : 

git clone https://github.com/jmbernabotto/MachineLearning

puis 
git remote add upstream https://github.com/jmbernabotto/MachineLearning.git pour mettre en upstream

vérification : 
git remote -v 
normalement deux flux : origin qui pointe sur mon fork et upstream qui pointe sur le dépot de projet

puis : 
git pull upstream master pour synchroniser la branche master d'oirigin vers le upstream

Il faut ensuite créer sa branche poour éviter de faire des bétises dans la branche master 
git checkout -b NOUVELLE_BRANCHE

vérification avec : 
git branch
pour voir si on a bien basculé dans NOUVELLE_BRANCHE

on créé alors les fichiers nouveaux ou les transformations de fichiers existants dans Jupyter
par exemple :
nouveau_notebook.ipynb ou nouveau_markdown.md

git add -A
pour sauvegarder ces changements puis
git commit -m "description du changement pour savoir ce qui a été modifié, c'est mieux !"

retour dans github.com

Compare & Pull Requests

Create Pull Requests

Commits pour les voir

et à la fin on peut dézinguer la branche créée