# TRAVAUX PRATIQUE A DISTANCE AVEC GIT

Quelques commandes GIT pratique.

## Configuration

```git
$ git config --global user.name "Your Name Comes Here"
```
```git
$ git config --global user.email you@yourdomain.example.com
```

## Importer un projet
```git
$ tar xzf project.tar.gz
```
```git
$ cd project
```
```git
$ git init
```
```git
$ git add .
```
```git
$ git commit
```

## Ou cloner simplement le projet
```git
$ git clone /url/alice/project project
```
## Faire des modifications
```git
$ git add file1 file2 file3
```
```git
$ git status
```
```git
$ git commit -a
```
## Voir l'historique
```git
$ git log
```

## Gérer des branches
```git
$ git branch experimental
$ git branch (liste toutes les branches existantes)
$ git checkout experimental
(edit file)
$ git commit -a
$ git checkout master
(edit file)
$ git commit -a
$ git merge experimental
$ git diff (to see conflict)
(edit file to resolve conflict)
$ git commit -a
$ git branch -d experimental (ensure that the changes are in the current branch)
```

## Récupérer le projet
```git
git pull /url/bob/project master
```







