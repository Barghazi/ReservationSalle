# Système de Réservation de Salles

Ce projet a pour objectif de créer une application web permettant la réservation de salles (réunion, classe, terrain, bureau, etc.) via des créneaux horaires définis.

## Structure du projet

- **backend-laravel/** : Gère l'authentification, l'inscription, la connexion et les rôles (utilisateur/gestionnaire).
- **backend-node/** : Contient trois microservices :
  - **room-service/** : Gestion des salles (CRUD, équipements, disponibilité)
  - **booking-service/** : Gestion des réservations (prise, annulation, mise à jour)
  - **notification-service/** : Notifications de confirmation ou d'annulation
- **frontend-react/** : Application React pour l'interface utilisateur
## Technologies utilisées

- Laravel 9 + MySQL (Authentification)
- Node.js + Express + MongoDB (Microservices)
- React.js (Frontend)
- JWT pour la sécurité
- RabbitMQ pour la communication entre microservices

## Auteurs

Projet réalisé par une équipe de 3 personnes.
"