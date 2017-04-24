# Précis de commande Git

Auteur : **Jérémie Pivot**

Job : _Ingénieur Logiciel à Capgemini_

## Précis de `markdown`

`#` : titre

backtick (altGr + 7) : Code inline

`** content**` : gras

`_ content _` : Italique

## Précis de bash

`cd` : change directory

```bash
cd path/to/directory
```

```bash
# crée un fichier myFile.ext
touch myFile.ext
```

## Précis de Git

`git init` : initialisation d'un dossier Git

`git add`: créer/modifier ==> passage à l'état stagged

`git rm path/to/file` : supprimer un fichier du commit

`git mv` modification du nom d'un fichier

`git status` :avoir le statut

`git commit` : stagged ==> unmodified

`git commit --amen`: permet de supprimer le dernier commit

`git log` : historique des opérations

`git log --pretty=oneline` : raccourcie du git log

`git branch testing` : créer une branche "testing"

`git checkout testing` : déplace la tête de lecture sur "testing"

`git merge testing` :permet de fusionner les branches
