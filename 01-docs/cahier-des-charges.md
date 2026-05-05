# Cahier des charges — TicketFlow

## 1. Présentation du projet

TicketFlow est une application web de gestion de tickets informatiques développée pour l’entreprise fictive NovaTech Services.

L’objectif est de centraliser les demandes d’assistance informatique afin d’améliorer leur suivi, leur priorisation et leur traitement.

## 2. Contexte

NovaTech Services compte environ 80 salariés. Les demandes informatiques sont actuellement transmises par mail, téléphone ou oralement.

Cette méthode entraîne des oublis, un manque de suivi et une difficulté à connaître l’état réel des incidents.

## 3. Besoin métier

Le service informatique souhaite disposer d’un outil unique permettant de gérer les demandes d’assistance.

L’application doit permettre de créer un ticket, suivre son état, l’attribuer à un technicien et conserver un historique des échanges.

## 4. Utilisateurs de l’application

### Salarié

Le salarié peut :

- se connecter ;
- créer un ticket ;
- consulter ses tickets ;
- ajouter un commentaire ;
- suivre l’état de ses demandes.

### Technicien

Le technicien peut :

- consulter les tickets qui lui sont attribués ;
- modifier le statut d’un ticket ;
- ajouter des commentaires ;
- indiquer la résolution d’un problème.

### Administrateur

L’administrateur peut :

- consulter tous les tickets ;
- attribuer un ticket à un technicien ;
- gérer les utilisateurs ;
- accéder à un tableau de bord.

## 5. Fonctionnalités attendues

| Fonctionnalité | Priorité |
|---|---|
| Connexion / déconnexion | Obligatoire |
| Gestion des rôles | Obligatoire |
| Création d’un ticket | Obligatoire |
| Liste des tickets | Obligatoire |
| Modification du statut | Obligatoire |
| Attribution à un technicien | Obligatoire |
| Commentaires sur un ticket | Obligatoire |
| Tableau de bord simple | Important |
| Recherche et filtres | Important |
| Export CSV | Bonus |
| Notification e-mail simulée | Bonus |

## 6. Contraintes techniques

Le projet sera développé avec les technologies suivantes :

- PHP ;
- MySQL ;
- HTML ;
- CSS ;
- JavaScript simple ;
- Bootstrap ;
- Git et GitHub ;
- Laragon pour l’environnement local.

## 7. Contraintes de sécurité

L’application devra prévoir :

- un système d’authentification ;
- des mots de passe sécurisés avec un hash ;
- un contrôle des rôles ;
- une protection contre les accès non autorisés ;
- une validation des données saisies dans les formulaires.

## 8. Livrables prévus

Les livrables du projet seront :

- cahier des charges ;
- contexte métier ;
- modèle de base de données ;
- script SQL ;
- code source ;
- documentation technique ;
- documentation utilisateur ;
- plan de tests ;
- captures d’écran ;
- dépôt GitHub ;
- journal de bord.