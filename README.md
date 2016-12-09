# MonoPollY - Gestion de sondages

## Introduction

Cette application a pour but de permettre à différents utilisateurs de créer et de participer à différents questionnaires et de voir différentes statistiques à propos de ceux-ci

Voici la liste des principales caractéristiques demandés :

- En tant qu'enquêteur, je peux poser des questions à une audience.
- En tant qu'auditeur, je peux répondre aux questions.
- En tant que participant, je peux voir les réponses de l'audience.
- En tant qu'invité je peux créer un compte et m'enregistrer.
- En tant qu'utilisateur enregistré je peux me connecter ou me déconnecter.
- En tant qu'auditeur je peux m'inscrire dans une salle (audience).
- En tant qu'enquêteur je peux créer une salle.
- En tant qu'enquêteur je peux créer des questions dans ma salle.

Voici le flux de navigation attendu pour cette application :

![Navigation flow](ressources/User Flow.png)

Les pages suivantes sont accessible lorsque l'utilisateur n'est pas authentifié :

  - Index
  - Login
  - Register

Les pages suivantes ne sont accessible que lorsque l'utilisateur est authentifié :

  - Polls
  - Statistics

Un utilisateur est définit par :

  - Un nom d'utilisateur
  - Un mot de passe

## Pour déployer l'application

### Prérequis

Pour lancer l'application il vous faut :

- node 4.6.1

Pour construire le projet il vous faut :

- npm 2.15.9

### Déploiment

1. Il vous faut cloner le répertoire
2. Ouvrir un terminal dans le répertoire cloné
3. Lancer les commandes suivantes :

  ```bash
  $> npm install
  $> node app.js
  ```
4. Ouvrir votre navigateur
5. Aller à l'adresse `localhost:3000` 

## Utilisation

1. Vous pouvez soit : 
- Déployer l'application vous même
- Ouvrir votre navigateur et vous rendre sur https://monopollytweb2016.herokuapp.com/ 
2. Connectez-vous.
3. Profitez ! 

**Remarque**: Vous ne pouvez pour le moment pas utiliser l'application, celle-ci est encore en cours de construction/mise-à-jour/maintenance jusqu'au 20 janvier.

## Technologies 
Pour ce projet nous utilisons les technologies suivantes :
 - Angular2
 - MySQL
 - Node.js
 - Express.js

## Pour plus d'informations

Visitez notre page de présentation :

 - https://ornidon.github.io/MonoPollY/

## Auteurs
Ioannis Noukakis & Thbaut Loiseau
