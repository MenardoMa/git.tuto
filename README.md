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

## Bonne pratique de commit

```bash

    - Un commit doit rencontrer une histoire

    A Noté si tu te trompe sur un commit est que tu veux faire un retour en arriere
    Tu peux utiliser la commande : 
        - git restore --staged ...nom du fichier...
        Ex: git restore --staged README.md
            Cela doit etre fait avant le faire un push.
    
    Un Commit doit avoir : 
    1. Un titre
    2. L'explication de changement

    Ex: Ajout de procedures
        Explication de comment rediger un commit.

```