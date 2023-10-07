# Scripts pour la gestions des projets LaPlateforme.io
Tous ces scripts doivent être mis dans le répertoire ~/bin
et ce répertoire doit être définit dans votre PATH pour appeler ces commandes
facilement. Au besoin, voilà comment faire:
```bash
mkdir ~/bin &&
echo 'PATH=~/bin:$PATH' >> ~/.bashrc &&
source ~/.bashrc
```

## GitIni
Script permettant de créer un nouveau répertoire sur GitHub et le clone
dans le répertoire de travail courant ~/github/
Il installe au cas où les paquets git et gh (github-cli).

Avant de lancer ce script pour la première fois il est préférable d'avoir
créé un compte GitHub d'avoir généré ses clefs ssh (avec SshKeygen par exemple).

```bash
GitIni ProjectName
```

## SshKeygen
Génère automatiquement une paire de clefs SSH et les
stokent dans le répertoire ~/.ssh
* Penser à définir les variables dans le script avant de l'excécuter! *
```bash
SshKeygen KeyName
```

## TempShell
Génère un nouveau fichier à partir d'un template adaptable
pour créer de nouveaux scripts BASH.
* Penser à définir les variables dans le script avant de l'excécuter! *
```bash
TempShell FileName
```
