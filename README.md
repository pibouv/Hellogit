# hellogit

Ressource sur Git : https://github.com/progit/progit2-fr (https://git-scm.com/book/en/v2) https://openclassrooms.com/courses/gerer-son-code-avec-git-et-github

Étape pour faire un nouveau commit d'un projet existant :

- faire des modifications dans un fichier / dossier
- vérifier que les modifications ont bien été "tracked" => faire un git status
si un fichier apparaît en "untracked" il faut l'ajouter à l'index => git add nomDuFichier
il est alors possible de faire un commit => git -m "Description de la modification"
si tous les fichiers était déjà indexer possibilité de faire : => git commit -a -m "Description de la modification" l'option -a demande à Git de mettre à jour les fichiers déjà existant dans son index.
