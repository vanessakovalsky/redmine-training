# Installation de Redmine

# Objectifs

Cet exercice a pour objectifs d'avoir une installation fonctionnelle de Redmine


## Sur un serveur préparé

* Sur un serveur dédié, vous pouvez suivre les instructions d'installation : https://www.redmine.org/projects/redmine/wiki/FrRedmineInstall

## Avec docker en local

* Une fois docker et docker compose installé
* Récupérer le fichier docker-compose.yml qui est dans le dossier docker
* Dans une console lancer la commande (en étant dans le dossier ou se trouve le fichier):
```
docker-compose up -d
```
* Votre redmine est accessible au bout de quelques instant à l'adresse http://localhost:8080 
Login : admin
Password : admin
