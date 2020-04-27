# GIT

## Getting started
1. git clone [**adresse du repo**][1]
2. git checkout [front] ou [back] (pour se déplacer sur la branche à partir de laquelle travailler)
3. git checkout -b [my-branch-name] (crée la branche et se déplace dessus)

## Travailler sur sa branche
1. pour ajouter au suivi de fichier => git add [nom du fichier] ou git add -e pour valider chaque fichier
2. pour commit => git commit -m "message de commit" (F - header[my-branch-name] - Menu création)
3. pour push => git push 

## Rapatrier sur la branche principale
1. git rebase => replanter la branche avec la dernière position du tronc dont elle est issue
1. faire une pull request sur github ; nom de la branche dans le message
2. attendre la réponse
3. se déplacer sur le tronc et git merge [my-branch-name]

Faut juste vous dire que vous allez jamais faire des merges tout seul, dixit Valentin le sénateur










[1]: github.com
