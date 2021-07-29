# Qu'est-ce que WSL ?
WSL Vous permet d'éxécuter et d'utiliser un environnement Linux sous windows sans avoir la contrainte d'utiliser une machine virtuel.

# Installation WSL
## Configuration requise
* Vous devez posséder une version de windows 10 Home, Pro ou Entreprise en 64bits
* Vous devez posséder au minimum la mise à jour 2004 de windows

## Activer les fonctionnalité windows
Pour installer WSL, nous avons d'abord besoins d'activer quelques fonctionalités présente dans windows, pour cela :
* Ouvrez le menu démarrer de windows
* Ouvrez le panneau de configuration
* Rendez-vous dans ["Programmes"](https://i.imgur.com/kmeVfLA.png "Programmes") puis ["Programmes et fonctionnalités"](https://i.imgur.com/SYEXIwa.png "Programmes et fonctionalités")
* Cliquez sur l'onglet ["Activer ou désactiver des fonctionnalité Windows"](https://i.imgur.com/DgWPyYk.png "Activer ou désactiver des fonctionnalités Windows") sur la gauche de votre fenêtre
* Cochez les options "Sous système Windows pour Linux" ainsi que "Plateforme d'ordinateur virtuel"
* Redémarrez votre ordinateur

## Téléchargement de votre distribution Linux
* Rendez-vous dans le microsoft store
* Dans la barre de recherche, tapez "WSL"
* Séléctionnez la distribution "Débian" et téléchargez la
* Démmarrez Débian
* Ajoutez un nom d'utilisateur comme demandé (**en minuscule**)
* Ajoutez votre mot de passe
* Fermez Debian

## Migration vers WSL2
* Téléchargez et installez ce [package](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)
* Ouvrez une invite de commande Windows
* Entrez la commande "wsl -l", cette commande vous permet de voir les distributions installer sur votre ordinateur
* Entrez ensuite la commande "wsl --set-version Débian 2
* Si vous obtenez l'erreur "assurez-vous que la virtualisation est activée dans le BIOS" allez dans le BIOS de votre ordinateur et activez la virtualisation

Félicitation ! Vous avez installé WSL 2.
