# Projet E-commerce H3HITEMA

Ce projet est une application e-commerce complète développée dans le cadre de la formation de H3HITEMA. Il comprend un frontend en React et un backend en Symfony.

## Structure du projet

*   **E-Airneis-ReactV1/** : Contient le code source frontend React.
*   **E-Airneis/** : Contient le code source backend Symfony.

## Configuration

1.  **Prérequis** : Assurez-vous d'avoir Node.js, npm (ou yarn), PHP, Composer et Symfony CLI installés sur votre machine.
2.  **Démarrage du backend** :
    *   Naviguez vers le dossier `E-Airneis` : `cd E-Airneis`
    *   Installez les dépendances : `composer install`
    *   Créez la base de données : `php bin/console doctrine:database:create`
    *   Exécutez les migrations : `php bin/console doctrine:migrations:migrate`
    *   Lancez le serveur : `symfony server:start`
3.  **Démarrage du frontend** :
    *   Naviguez vers le dossier `client` : `cd client`
    *   Installez les dépendances : `npm install` (ou `yarn install`)
    *   Lancez le serveur de développement : `npm start` (ou `yarn start`)

## Documentation

*   **API Backend** : La documentation de l'API se trouve dans le dossier `E-Airneis/public/api-docs`.
*   **Frontend** : Des informations supplémentaires sur le frontend sont disponibles dans le fichier README.md du dossier `client`.

