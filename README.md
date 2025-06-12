# TP Docker Compose - WordPress

Ce projet déploie WordPress avec sa base de données MySQL en utilisant Docker Compose.

## Services

- **db** : MySQL, base de données WordPress
- **wordpress** : CMS WordPress, accessible sur le port 8080

## Fichier docker-compose.yaml

Il contient deux services :
- `db` : base de données MySQL
- `wordpress` : application WordPress connectée à la base de donnée

## Volumes

Les données sont persistées dans des volumes Docker pour ne pas perdre les données lors d'un arrêt.

## Lancement

1. Cloner le projet `git clone <url-du-repo>`
2. Déplacez vous dans le dossier docker-wordpress `cd <chemin-vers-docker-compose>`
2. Lancer `docker-compose up -d`
3. Accéder à WordPress via http://localhost:8080

## Auteur

Berni ✌🏽