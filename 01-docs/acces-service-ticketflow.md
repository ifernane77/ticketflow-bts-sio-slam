# Fiche d’accès au service — TicketFlow

## 1. Objectif

Ce document décrit les conditions d’accès à l’application TicketFlow dans le cadre du projet BTS SIO option SLAM.

L’objectif est d’expliquer comment les utilisateurs peuvent accéder au service, quelles sont les contraintes réseau et quelles règles d’accès sont prévues.

## 2. Contexte d’accès

TicketFlow est une application web de gestion de tickets informatiques destinée à l’entreprise fictive NovaTech Services.

Dans le cadre du développement, l’application est exécutée en local sur mon poste à l’aide de Laragon.

Dans un contexte professionnel, l’application pourrait être hébergée sur un serveur interne de l’entreprise afin d’être accessible depuis le réseau local.

## 3. URL d’accès prévue

### En environnement de développement

L’application pourra être accessible localement via une URL de type :

`http://ticketflow.test`

ou :

`http://localhost/ticketflow`

### En environnement professionnel simulé

Dans l’entreprise NovaTech Services, l’application pourrait être accessible depuis le réseau interne via une URL de type :

`http://ticketflow.novatech.local`

Cette URL serait réservée aux utilisateurs connectés au réseau interne de l’entreprise.

## 4. Utilisateurs concernés

| Profil | Accès prévu |
|---|---|
| Salarié | Créer un ticket et suivre ses demandes |
| Technicien | Consulter les tickets attribués et mettre à jour leur statut |
| Administrateur | Gérer les utilisateurs, les tickets et les attributions |
| Responsable informatique | Consulter les indicateurs et superviser l’activité |

## 5. Conditions d’accès

L’accès à TicketFlow nécessite :

- un navigateur web récent ;
- une connexion au réseau interne de l’entreprise ou à l’environnement local ;
- un compte utilisateur ;
- un identifiant et un mot de passe ;
- des droits adaptés au rôle de l’utilisateur.

## 6. Contraintes réseau

Dans un contexte professionnel, les contraintes suivantes sont à prendre en compte :

- l’application doit être accessible depuis les postes du réseau interne ;
- le serveur web doit être disponible pendant les horaires de travail ;
- les utilisateurs doivent pouvoir accéder à l’application depuis leur navigateur ;
- l’accès doit être limité aux utilisateurs autorisés ;
- les données doivent être stockées dans une base MySQL accessible par l’application.

## 7. Sécurité d’accès prévue

Pour sécuriser l’accès au service, les règles suivantes sont prévues :

- authentification obligatoire ;
- mot de passe stocké sous forme hachée ;
- contrôle des rôles ;
- restriction des pages selon le profil de l’utilisateur ;
- validation des données saisies dans les formulaires ;
- protection contre les accès directs non autorisés.

## 8. Disponibilité du service

En environnement local, la disponibilité dépend du lancement de Laragon.

En environnement professionnel, l’application devrait être hébergée sur un serveur interne afin d’être disponible pour les salariés de NovaTech Services.

## 9. Conclusion

Cette fiche permet de définir clairement les conditions d’accès à TicketFlow.

Elle complète le cahier des charges en précisant comment le service sera consulté, par qui, et dans quelles conditions techniques.