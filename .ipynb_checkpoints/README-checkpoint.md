# MachineLearning propose quelques notebook Jupyter en Python

1. A partir d'Onyxia : 

git clone https://github.com/jmbernabotto/MachineLearning

2. puis 
git remote add upstream https://github.com/jmbernabotto/MachineLearning.git pour mettre en upstream

3. vérification : 
git remote -v 
normalement deux flux : origin qui pointe sur mon fork et upstream qui pointe sur le dépot de projet

4. puis : 
git pull upstream master pour synchroniser la branche master d'oirigin vers le upstream

5. Il faut ensuite créer sa branche poour éviter de faire des bétises dans la branche master 
git checkout -b NOUVELLE_BRANCHE

6. vérification avec : 
git branch
pour voir si on a bien basculé dans NOUVELLE_BRANCHE

on créé alors les fichiers nouveaux ou les transformations de fichiers existants dans Jupyter
par exemple :
nouveau_notebook.ipynb ou nouveau_markdown.md

7. puis pour sauvegarder ces changements
git add -A

8. puis pour commenter les changements 
git commit -m "description du changement pour savoir ce qui a été modifié, c'est mieux !"

9. puis pour tout pousser dans github
git push origin NOUVELLE_BRANCHE 

10. retour dans github.com

11. Compare & Pull Requests

12. Create Pull Requests

13. Commits pour les voir

si on doit refaire des modifs, il suffit de faire les étapes 7. à 13.

et à la fin on peut dézinguer la branche créée dans github