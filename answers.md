# Answers of Nicolas Begert nico-219

## Basics
### Task 1
Les changements ont été faits, mais ils n'ont pas été commit ni push. 

### Task 2
- Le message proposé en exemple signifie que les données personnelles ont été modifiées dans le fichiers answers.md 
- Il est impossible de créer un commit sans message
- Le fichier modifié est enregistré dans l'historique, ainsi que les données de l'auteur. 
- Non car le fichier n'a pas encore été push sur Github.

### Task 3
- Nous avons désormais deux unstaged file, et lorsque l'on clique sur le dépot actuel, il y a maintenant un untracked file.

### Task 4
- Quand on revient au commit « Initial commit », on voit le projet tel qu’il était au tout début : seuls les premiers fichiers sont présents. On est en mode "détaché". En revenant au dernier commit (par exemple via main), on retrouve l’état actuel complet du projet, avec tous les fichiers et modifications, et on revient sur la branche principale.

### Task 5
- Dépot local : Sur notre ordinateur (par exemple dans le dossier du projet). C’est la copie complète du projet Git, contenant le code, l'historique de commits, les branches, etc. On y travaille directement.

- Dépot distant : Sur un serveur en ligne (exemple Github). C’est la version “centrale” du projet, utilisée pour partager le code avec d’autres ou sauvegarder notre travail.

- Si on supprime le dépot local : On perd les fichiers de travail et tout l’historique Git local (commits, branches locales, etc.). Mais si on avait push les commits avant la suppression, le dépot distant resterait intact, on pourrait recloner le dépot distant pour tout récupérer en local. 

### Task 6
- Non, le dépot originel qui à été forké n'a pas été modifié car toutes les modifications sont faites uniquement sur ma copie (mon fork) et mon dépot local.
Tant que je ne fais pas de pull request et qu'elle n'est pas acceptée, le dépot originel reste identique à sa version initiale.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)