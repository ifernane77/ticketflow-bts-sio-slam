# Procédure d’installation — TicketFlow

## 1. Présentation

Ce document explique comment installer l’environnement nécessaire pour développer et exécuter le projet TicketFlow en local.

TicketFlow est une application web de gestion de tickets informatiques développée en PHP/MySQL dans le cadre du BTS SIO option SLAM.

## 2. Prérequis techniques

Avant de lancer le projet, les outils suivants doivent être installés :

| Outil | Utilité |
|---|---|
| Laragon | Serveur local Apache/PHP/MySQL |
| PHP | Langage utilisé pour développer l’application |
| MySQL | Système de gestion de base de données |
| phpMyAdmin ou Adminer | Interface de gestion de la base de données |
| Visual Studio Code | Éditeur de code |
| Git | Versionnage du projet |
| GitHub | Hébergement du dépôt distant |

## 3. Versions utilisées sur mon poste

| Élément | Version / information |
|---|---|
| Système d’exploitation | Windows |
| PHP | PHP 8.3.16 via Laragon |
| MySQL | MySQL 8.4.3 via Laragon |
| Serveur local | Laragon |
| Éditeur | Visual Studio Code |
| Versionnage | Git / GitHub |

## 4. Vérification de PHP

La présence de PHP peut être vérifiée avec la commande suivante :

```powershell
php -v