# ZOO ARCADIA
Arcadia est un project scolaire full stack d'application complète pour un Zoo fictif.

# Environnement de travail

Plusieurs pré-recquis pouvoir faire fonctionner le projet en local (partie backend).

# IDE

Ce projet a été réalisé avec l'IDE *Visual Studio Code* [(lien de téléchargement)](https://code.visualstudio.com/download).

# GITHUB

Installer Git sur sa machine : [lien de téléchargement](https://git-scm.com/downloads).

CLONER LE DÉPÔT DU PROJET:
    - rendez-vous dans un terminal de l'IDE de votre choix.
    - vérifier le chemin de dossier de votre machine pour cloner le dépôt où vous le désirez.
    - écrivez cette commande dans votre terminal 
    ```git clone https://github.com/Daniel-Gros/arcadiabackend.git```


# BACKEND SYMFONY

**PRÉREQUIS**

**PHP**

Il vous faudra avoir la version 8.2.12 de *PHP* installée sur votre machine. 
Vous devrez pour cela installer le serveur local *XAMPP* que vous pouvez télécharger en [cliquant ici](https://www.apachefriends.org/fr/download.html).
*XAMPP* installera sur votre machine automatique la version 8.2.12 de PHP ainsi que *MySQL* dont vous aurez besoin pour la gestion des bases de données.

**SYMFONY**

Il vous faudra télécharger *Composer* qui est un gestionnaire de dépendances PHP. 
Vous pouvez le télécharger en [cliquant ici](https://getcomposer.org/download/).
Une fois *Composer* installé sur votre machine , vous pouvez passer à l'étape suivante

*CLI Symfony*

Pour installer le CLI vous devrez vous rendre [sur ce lien](https://symfony.com/download) et suivre les instructions. 
    Télécharger *Scoop*
    Télécharger le *Symfony CLI* avec la commande dans votre terminal: ```scoop install symfony-cli```


*IMPORTANT*

Vous n'avez pas besoin de cloner le dépôt dans le dossier du serveur local associé (htdocs pour XAMPP, www pour WAMP).
Ce projet étant réalisé avec Symfony, vous devrez juste écrire la commande ```symfony server:start```
cela ouvrira votre navigateur avec le projet partie frontend à l'adresse [http://localhost:8000]
