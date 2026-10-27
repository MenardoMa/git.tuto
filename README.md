# Les bases de git
## Git pour les nuls

```bash

git init permet d'initialiser le dossier et creer un dossier masqué .git
qui va contenir l'ensemble de nos modifications. 

La connexion d'envoie et de reception est faite en ssh
git remote add origin git@github.com:MenardoMa/git.tuto.git

```

## Configuration de git

```bash 
Pour configurer git sur ta machine nous pouvons faire :
    - git config --global user.name "your name"
    - git config --global user.email your mail

    pour afficher les informations : 
        - git config --global user.name
        - git config --global user.email
```

## Trancer l'evolution d'un projet avec git

```bash 
Pour tracer l'evolution d'un projet avec git ou verifier toutes les modifications
qu'on a eu à faire avec git nous avons plusieur commandes : 

    -git log:
    La commande affiche l'evolution de tout nos changement.
    La commande va lister toutes nos commit, heure etc...
    pour quitté on va taper : shift + q

    -git show
    Affiche toutes les modifications un peut comme git log mais git 'show'
    le fait de maniere un peu pouser parce que la commande affiche et le fichier modifier
    le modification etc..
    en gros 'git show' affiche les détails d’un commit : ses modifications, les fichiers 
    concernés et les différences de code.

    Ex: git show ...id d'un commit...
        => git show 04b82fc330d9039f568241ea6329b5a00c28be1f 

```