# Traefik pour les conteneurs Docker de swafe.app

Description...

## Installation

1. Clonez le repo : `git clone [URL_DU_REPO]`
2. Créer le network Docker : `docker network create traefik-proxy`
3. Créez le fichier qui contiendra les certificats SSL et définissez les permissions : `touch acme.json && chmod 600 acme.json`

## Lancement

Exécutez `docker-compose up -d` pour démarrer les conteneurs.

## Environnement

Renommez `.env.example` en `.env` et modifiez les valeurs selon vos besoins.
