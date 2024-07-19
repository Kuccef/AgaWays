# AgaWays
A platform to improve public transport user experience in Agadir with real-time schedules and notifications.

# Modules à Développer

 ## Interface Utilisateur Conviviale
 
   - Pages d'accueil, de planification, de consultation des horaires

   - Gestion des notifications

   - Authentification et gestion des profils utilisateurs

 ## Suivi en Temps Réel (Tracking Bus)

   - Intégration avec les APIs de suivi des bus en temps réel

   - Affichage des positions des bus sur une carte

 ## Horaires et Itinéraires

   - Consultation des horaires en temps réel

   - Planification des trajets

 ## Notifications et Alertes

   - Envoi et gestion des notifications en temps réel
  
   - Paramètres de notification utilisateur

# Liste de Fonctionnalités par Module

 ## Interface Utilisateur Conviviale

   ### Page d'Accueil

   - Présentation générale de la plateforme

   - Accès rapide aux principales fonctionnalités

   ### Page de Planification de Trajet

   - Sélection du point de départ et de destination
     
   - Calcul et affichage des itinéraires

   ### Page de Consultation des Horaires

   - Affichage des horaires en temps réel
     
   - Recherche par ligne et arrêt

   ### Gestion des Notifications

   - Affichage des notifications en temps réel
     
   - Paramètres de notification utilisateur

   ### Authentification et Profil Utilisateur

   - Inscription, connexion, déconnexion

   - Gestion du profil utilisateur

   ## Suivi en Temps Réel (Tracking Bus)
   
   #### Intégration avec API de Suivi

   - Connexion aux services de suivi en temps réel des bus
     
   - Gestion des données de suivi

   #### Affichage sur Carte

   - Visualisation des bus en temps réel sur une carte interactive

   - Mise à jour en temps réel des positions
 
  ## Horaires et Itinéraires

   #### Consultation des Horaires

   - Récupération des horaires en temps réel via API
       
   - Affichage des horaires pour les lignes et arrêts sélectionnés

   ### Planification des Trajets

   - Calcul des itinéraires optimaux
       
   - Affichage des trajets possibles avec horaires et correspondances

## Notifications et Alertes
     
   ### Envoi de Notifications

   - Configuration de Firebase Cloud Messaging
          
   - Envoi de notifications en temps réel aux utilisateurs

   ### Paramètres de Notifications

   - Gestion des préférences de notification utilisateur
          
   - Envoi d'alertes en cas de perturbations ou d'annulations

# Liste des Tâches par Fonctionnalité

  ## Interface Utilisateur Conviviale

   ### Page d'Accueil

   - Conception UI/UX

   - Implémentation HTML/CSS

   - Intégration des Composants React

   ### Page de Planification de Trajet

   - Conception UI/UX

   - Développement de l'interface de planification

   - Intégration avec l'API de calcul d'itinéraire

   ### Page de Consultation des Horaires

   - Conception UI/UX

   - Développement de l'interface de consultation

   - Intégration avec l'API des horaires en temps réel

   ### Gestion des Notifications

   - Configuration de Firebase Cloud Messaging

   - Développement de l'interface de gestion des notifications

   - Intégration des notifications push

   ### Authentification et Profil Utilisateur

   - Développement des formulaires d'inscription et de connexion

   - Implémentation de l'authentification avec JWT

   - Gestion du profil utilisateur

   ### Suivi en Temps Réel (Tracking Bus)
   ### Intégration avec API de Suivi

   - Recherche et sélection d'API de suivi en temps réel
     
   - Implémentation de la connexion à l'API
     
   - Gestion des données de suivi (parsing, mise à jour)

   ### Affichage sur Carte

   - Sélection et intégration de librairie de cartes (e.g., Leaflet, Google, Maps)

   - Développement de l'interface de suivi sur carte

   - Mise à jour en temps réel des positions des bus

   ### Horaires et Itinéraires
   ### Consultation des Horaires

   - Recherche et intégration d'API de données horaires

   - Développement des endpoints pour récupérer les horaires

   - Affichage des horaires sur l'interface utilisateur

   ### Planification des Trajets

   - Développement de l'algorithme de calcul d'itinéraire

   - Intégration des données horaires pour calcul d'itinéraire

   - Affichage des itinéraires sur l'interface utilisateur

   ### Notifications et Alertes
   ### Envoi de Notifications

   - Configuration de Firebase Cloud Messaging

   - Développement des endpoints pour envoyer des notifications

   - Gestion de l'envoi des notifications en temps réel

   ### Paramètres de Notifications

   - Développement de l'interface utilisateur pour les paramètres de notification

   - Gestion des préférences de notification dans la base de données
     
   - Envoi d'alertes en fonction des préférences utilisateur

# API Externes

   - API des Transports en Commun d'Agadir (ou autre source de données en temps réel)
     
   - Firebase Cloud Messaging pour les notifications push
