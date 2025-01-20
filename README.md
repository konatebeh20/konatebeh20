# Hi there (Salut a vous) 👋
# Bienvenue sur mon profil GitHub professionnel 👔

Ce dépôt contient mon CV, mes projets réalisés ainsi que des détails sur mes compétences et mon parcours professionnel.

## 🧑‍💻 À propos de moi 💼

Je suis un développeur junior avec une passion pour le développement d'applications web et mobiles, ainsi qu'un intérêt pour les solutions innovantes dans le domaine des données et de l'informatique. J'ai travaillé avec des technologies comme **Angular**, **Flask**, **Ionic**, **React**, **Laravel**, **WordPress**, et d'autres. Mon expertise repose sur l'utilisation de **frameworks modernes** pour créer des solutions efficaces et évolutives, tout en cherchant constamment à intégrer des solutions innovantes dans un contexte professionnel.

## 🌟 Technologies utilisées

- Angular, Flask, Ionic, React, Laravel
- HTML, Bootstrap
- Trello pour la gestion de projet

## 📄 Mon CV

Voici un lien vers mon **CV** : [CV.pdf](assets/CV.pdf)<br><br>
Tu peux aussi consulter une version de mon CV au format de fichier markdown comme (`CV.md`).<br>
Voici un lien vers mon **CV** : [CV.md](assets/CV.md)

# 💼 Portfolio 💼

## 💼 Projets en entreprise

### Projet 1: **PowerCalc**
**PowerCalc** est une application web et mobile développée avec Ionic pour le frontend et Flask pour le backend. L'objectif principal de l'application est de permettre une gestion optimisée des utilisateurs et des propriétés en analysant leur consommation énergétique.

---

## 📋 Fonctionnalités principales :
  1. Gestion des utilisateurs :
      - Ajout, modification et suppression des utilisateurs.
      - Stockage des informations comme le nom, l'email, l'adresse, le numéro de téléphone, et les identifiants uniques.
      - Gestion des dates de création et de mise à jour des données.

  2. Gestion des propriétés :
      - Prise en charge de plusieurs types de propriétés :
          + Magasins : Analyse des équipements électriques pour calculer leur consommation.
          + Maisons : Suivi de la consommation énergétique quotidienne et mensuelle.
          + Agences et entreprises : Évaluation globale de la consommation énergétique par poste.
      - Enregistrement des caractéristiques énergétiques de chaque propriété :
          + Ampérage : Capacité des équipements.
          + Wattage : Consommation énergétique des appareils.
          + Temps et jours d'utilisation : Durée moyenne d'utilisation pour chaque équipement.

  3. Analyse énergétique :
    - Collecte et traitement des données pour aider les propriétaires à optimiser leur consommation.
    - Exportation des données sous forme de rapports (optionnel).

---

## 🛠️ Technologies utilisées :

  - Frontend : Ionic (framework mobile et web multiplateforme)
  - Backend : Flask (Python) avec SQLAlchemy pour la gestion des bases de données.
  - Base de données : MySQL (via PyMySQL).

---

## 🚀 Points forts du projet :

  - Architecture robuste grâce à une séparation claire entre le frontend et le backend.
  - Modélisation extensible avec des classes pour chaque type d'entité (User, Store, House, Agency, Company).
  - Support multiplateforme grâce à Ionic, permettant une expérience utilisateur homogène sur web et mobile.

---

## 🔗 Lien vers le projet :
Voici un lien vers le **projet PowerCalc** : [PowerCalc](https://github.com/foleyKant01/PowerCalc)

---

## 📸 Capture d'image :
![Screenshot du projet PowerCalc](assets/images/projets/PowerCalc/login.png)  



##





### Projet 2: **Cashier**
**Cashier** est une application développée avec Flask pour le backend et Angular pour le frontend. Elle est conçue pour gérer efficacement des caisses enregistreuses et faciliter les transactions commerciales. L'application offre également des fonctionnalités de gestion des utilisateurs, des articles et des transactions.

---

## 📋 Fonctionnalités principales :
1. Gestion des administrateurs et utilisateurs :
   - Ajout, modification et suppression des administrateurs et utilisateurs.
   - Stockage sécurisé des informations personnelles (nom, email, numéro de téléphone, adresse, identifiants, etc.).
   - Gestion des dates de création et de mise à jour pour un suivi complet.

2. Gestion des articles :
   - Enregistrement des articles avec leurs caractéristiques :
      + Nom : Nom de l'article.
      + Description : Informations détaillées sur le produit.
      + Prix : Prix de vente de l'article.
      + Marque : Fabricant ou fournisseur de l'article.
      + Code-barres : Identification unique pour chaque produit.
      + Stock et seuil de réapprovisionnement : Suivi des niveaux de stock et alertes pour les faibles stocks.

3. Gestion des transactions :
    - Support pour les formulaires d'achat (FormBuying) pour enregistrer et suivre les transactions effectuées par les utilisateurs.
    - Attribution unique d'identifiants de transaction pour simplifier le suivi des ventes.
4. Transcription en Selenium
    - Automatisation et transcription des opérations de caisse en utilisant Selenium, pour une gestion des données fluide et rapide.

---

## 🛠️ Technologies utilisées :
 - Frontend : Angular (interfaces interactives et réactives).
 - Backend : Flask avec SQLAlchemy pour la gestion des bases de données.
 - Automatisation : Selenium pour automatiser certaines tâches et générer des rapports.
 - Base de données : MySQL (via PyMySQL).

---

## 🚀 Points forts du projet :
 - Interface utilisateur réactive grâce à Angular.
 - Gestion complète des utilisateurs et articles avec des fonctionnalités d'alerte pour le réapprovisionnement.
 - Automatisation via Selenium pour réduire les erreurs humaines et améliorer la productivité.
 - Système modulaire permettant une extension future.

---

## 🔗 Lien vers le projet :
Voici un lien vers le **projet Cashier** : [Cashier](https://github.com/foleyKant01/Cashier)

---

## 📸 Capture d'image :
![Screenshot du projet Cashier](assets/images/projets/Cashier/login.png)  



##





### Projet 3: **goparadize_mobile (application mobile d'rbnb)**
**goparadize_mobile** est une application mobile innovante développée avec **_Flask_** pour le backend et **_Ionic Angular_** pour le frontend, pour offrir des services similaires à ceux de Rbnb, avec des fonctionnalités avancées pour la réservation de chambres, la gestion des utilisateurs et des notifications. Ce projet utilise Flask pour le backend et des technologies mobiles modernes pour le frontend.

## 📋 Fonctionnalités principales
- Gestion des utilisateurs :
  - Ajout, modification et suppression d'utilisateurs avec des données sécurisées.
  - Informations stockées : nom, prénom, email, pays, ville, et image de profil.
  - Suivi des statuts (utilisateur actif/inactif) et des tokens de connexion pour une sécurité accrue.
  - Gestion des identifiants uniques (UUID) pour chaque utilisateur.
- Gestion des catégories, chambres, et hôtels :
- Catégories : Organisation des chambres en catégories (standard, luxe, etc.).
  - Chambres :
    + Gestion des capacités, des équipements et des prix.
    + Gestion des promotions et des périodes spécifiques (début et fin des promotions).
    + Suivi de la disponibilité des chambres.
 - Hôtels :
    + Enregistrement des hôtels avec des informations détaillées (adresse, description, équipements, géolocalisation).
    + Gestion des chambres associées à chaque hôtel.
- Réservations et paiements :
  - Gestion complète des réservations avec les détails :
      + Dates de réservation (début/fin), nombre de chambres, et statuts de réservation.
  - Paiements intégrés :
      + Paiement via mobile money et autres méthodes.
      + Gestion des taxes, des coupons de réduction, et des prix totaux.
- Notifications et contact :
  - Système de notifications automatisées pour les utilisateurs :
    - Notifications sur les nouvelles offres, mises à jour de réservation, etc.
  - Formulaire de contact pour permettre aux utilisateurs de soumettre des demandes directement via l'application.
- Automatisation et gestion des données :
  - Suivi des opérations via des identifiants uniques (UUID).
  - Gestion des tokens d'appareils pour l'envoi de notifications ciblées.

## 🛠️ Technologies utilisées
  - Backend : Flask (gestion de la logique métier et des API REST).
  - Frontend : Technologie mobile pour le développement multiplateforme (ajoute la technologie exacte si connue, ex. Ionic ou React Native).
  - Base de données : SQL avec SQLAlchemy (intégration PostgreSQL ou MySQL).
  - Services tiers : Intégration de systèmes de paiement mobile.

## 🚀 Points forts du projet
  - Interface intuitive pour les utilisateurs, facilitant les réservations et la navigation.
  - Sécurité avancée grâce à la gestion des tokens et des statuts utilisateurs.
  - Fonctionnalités de promotion et de personnalisation des services pour les hôtels.
  - Notifications en temps réel pour une meilleure expérience utilisateur.

## 🔗 Lien vers le projet
Voici un lien vers le **projet goparadize_mobile** : [goparadize_mobile](https://github.com/TORNIXTECH/goparadize-mobile)

## 📸 Capture d'écran
![Screenshot du projet goparadize_mobile](assets/images/projets/goparadize_mobile/login.png)  



##




### Projet 4: **goparadize_admin (Dashboard web de l'application mobile : _**goparadize_mobile**_ d'rbnb)**
**goparadize_admin** est une application web développée avec **_Flask_** pour le backend et **_Angular_** pour le frontend. Elle sert de tableau de bord pour l'application mobile _**goparadize_mobile**_, permettant aux administrateurs de gérer les utilisateurs, les hôtels, les chambres, et les réservations via une interface web intuitive.

## 📋 Fonctionnalités principales
 - Gestion des utilisateurs :
   - Ajouter, modifier ou supprimer les utilisateurs avec des données sécurisées.
   - Informations gérées : identifiants uniques (UUID), nom, prénom, email, pays, ville, et image de profil.
   - Gestion des statuts (actif/inactif) et des connexions des utilisateurs.
 - Gestion des hôtels :
   - Enregistrer des hôtels avec des informations complètes :
      - Nom : Titre de l’hôtel.
      - Description : Informations détaillées sur les services et les équipements.
      - Emplacement : Géolocalisation avec longitude et latitude.
      - Chambres associées : Quantité, types, et équipements disponibles.
   - Gestion des catégories et des tags associés aux hôtels.
- Gestion des chambres :
   - Créer, modifier et supprimer des chambres :
      - Capacité maximale, équipements disponibles, prix, et promotions.
      - Suivi de la disponibilité des chambres et des statuts (occupé, disponible, etc.).
   - Gestion des types de chambres et des taxes associées.
- Gestion des réservations et des commandes :
   - Suivi des réservations :
      - Détails des clients (nombre d’adultes/enfants, période de réservation, etc.).
      - Paiements associés, incluant les taxes et les réductions.
   - Gestion des statuts des réservations (en attente, confirmée, annulée).
- Notifications et contact :
   - Envoi de notifications ciblées aux utilisateurs (promotions, mises à jour, etc.).
   - Gestion des demandes via un formulaire de contact intégré.
 
## 🛠️ Technologies utilisées
  - Frontend : Angular pour le développement du tableau de bord interactif.
  - Backend : Flask pour la gestion de la logique métier et des API REST.
  - Base de données : SQL avec SQLAlchemy (intégration PostgreSQL ou MySQL).
  - Système de tokens : Gestion des appareils via des tokens sécurisés.

## 🚀 Points forts du projet
  - Tableau de bord réactif et intuitif permettant une gestion complète des données de l'application mobile.
  - Sécurité avancée avec une gestion des tokens pour les utilisateurs et les notifications.
  - Architecture modulaire facilitant l'ajout de nouvelles fonctionnalités.
  - Intégration d'une gestion complète des taxes et des promotions.

## 🔗 Lien vers le projet
Voici un lien vers le **projet goparadize_admin** : [goparadize_admin](https://github.com/TORNIXTECH/goparadize_admin)

## 📸 Capture d'écran
![Screenshot du projet goparadize_admin](assets/images/projets/goparadize_admin/login.png)  



##





# Projet 5: **flotys_mobile** 

**flotys_mobile** est une application mobile innovante conçue pour la gestion de flottes de véhicules. Elle permet de suivre, gérer et optimiser les opérations liées aux véhicules, conducteurs, trajets et maintenance. Développée avec **Flask** pour le backend et une technologie mobile moderne (par exemple, **Ionic** ou **React Native**) pour le frontend, cette application est idéale pour les entreprises souhaitant améliorer leur efficacité opérationnelle.

---

## 📋 Fonctionnalités principales

### Gestion des véhicules :
- Enregistrement des véhicules avec des caractéristiques complètes :  
  - **Plaque d'immatriculation**, modèle, fabricant, année, et couleur.  
  - Type de moteur, type de carburant, transmission, et capacité de sièges.  
  - Suivi des valeurs d'achat et actuelles, kilométrage et date d'achat.  
- Suivi des appareils connectés pour chaque véhicule (type et ID de l'appareil).  

### Gestion des conducteurs :
- Création, modification et suppression des profils des conducteurs.  
- Informations suivies : nom, email, numéro de téléphone, numéro de permis et date d'expiration.  
- Attribution des véhicules aux conducteurs avec un historique des missions.  

### Suivi des trajets et localisations :
- Suivi en temps réel des trajets effectués par les véhicules.  
- Gestion des points de départ et d'arrivée avec des coordonnées géographiques précises.  
- Calcul des distances, durées et vitesse moyenne pour chaque trajet.  
- Historique des localisations des véhicules.  

### Gestion de la maintenance :
- Enregistrement des historiques de maintenance :  
  - Date, description, coût et statut de la maintenance.  
- Planification des maintenances périodiques (basées sur le kilométrage ou le temps).  

### Gestion des rapports et données analytiques :
- Génération de rapports détaillés sur les performances des véhicules et des conducteurs :  
  - Kilomètres parcourus, incidents, consommation de carburant, et coûts de maintenance.  
- Prévisions (forecasting) basées sur les données collectées pour optimiser les coûts et la gestion des ressources.  
- Suivi des émissions de CO2 pour chaque trajet.  

### Notifications et conformité :
- Gestion des alertes pour les maintenances à venir, renouvellement de permis, et autres échéances importantes.  
- Suivi des conformités réglementaires et génération de journaux de conformité.  

### Paiements et abonnements :
- Gestion des plans d'abonnement pour les utilisateurs (par exemple, Basic, Premium, Pro).  
- Suivi des paiements liés aux abonnements et des factures.  

---

## 🛠️ Technologies utilisées
- **Frontend** : Technologie mobile moderne (ajoute la technologie exacte, ex. Ionic ou React Native).  
- **Backend** : Flask pour la gestion des API et de la logique métier.  
- **Base de données** : MySQL avec SQLAlchemy pour la gestion des données.  
- **Suivi GPS** : Utilisation de données géographiques (latitude/longitude) pour le suivi des véhicules.  

---

## 🚀 Points forts du projet
- Interface intuitive pour la gestion complète des véhicules et conducteurs.  
- Génération automatique de rapports analytiques et prévisions basées sur les données collectées.  
- Système de notifications pour garantir la conformité et optimiser les opérations.  
- Architecture modulaire et évolutive pour intégrer de nouvelles fonctionnalités.  

---

## 🔗 Lien vers le projet
Voici un lien vers le **projet flotys_mobile** : [flotys_mobile](https://github.com/TORNIXTECH/flotys_mobile)

---

## 📸 Capture d'écran
![Screenshot du projet flotys_mobile](assets/images/projets/Flotyshub/flotys_mobile/login.png)  

---


##




### Projet 6: **Korifinances (Gestion de log et création de pages)**
**Korifinances** est une application web robuste, innovant développée pour le domaine des services financiers. L'objectif principal de **Korifinances**, est : La proposition des solutions pour des transferts d'argent rapides et sécurisés de faciliter la gestion des utilisateurs, des crédits, des commissions et des limites de transaction, tout en respectant les exigences réglementaires et sécuritaires. Ce projet est realiser en **Angular** pour le frontend et **Flask** pour le backend.

## 📋 Fonctionnalités principales

Gestion des utilisateurs :
  - Création, modification et suppression des utilisateurs avec des informations sécurisées :
    - Informations générales : Nom, prénom, email, numéro de téléphone, adresse IP, rôle, privilèges, etc.
    - Sécurité avancée : Gestion des OTP (One-Time Passwords), des heures de connexion, et des restrictions liées aux pays et week-ends.
    - Suivi des connexions avec des adresses MAC et tokens sécurisés.
  <!--
  - ff
  -->
  
Gestion des crédits :
  - Attribution des crédits : Suivi des crédits assignés à des utilisateurs, agences ou pays.
  - Gestion des statuts des crédits : Actif, suspendu ou en attente.
  - Rapports détaillés : Suivi des montants attribués, des assignations et des mises à jour.
Gestion des commissions :
  - Calcul automatique des commissions sur les transactions :
    - Commissions pour les agences, agents, et sièges sociaux.
    - Suivi des commissions via des taux et limites définis.
  - Gestion des taxes (premier, deuxième, et troisième niveau) et calcul des montants nets à payer.
Gestion des limites de crédit :
  - Définition des limites par :
    - Pays : Transactions, limites journalières, mensuelles et annuelles.
    - Agences : Gestion des plafonds de crédit par agence.
    - Zones géographiques : Limites spécifiques basées sur les zones géographiques.
  - Messages d’alerte automatiques en cas de dépassement des limites.
Création de pages et gestion des logs :
  - Génération de pages administratives et rapportées aux opérations financières.
  - Enregistrement des activités des utilisateurs et journaux (logs) pour audit.

- **Espèces à espèces** : Un vaste réseau d'agences et de points de vente indépendants.
- **Espèces au compte** : Transfert d'argent directement vers un compte bancaire.
- **Espèces vers mobile** : Effectuer des opérations depuis ou vers un mobile.

## 🛠️ Technologies utilisées
  - Backend : Flask avec SQLAlchemy pour la gestion des bases de données et des API REST.
  - Base de données : MySQL (support SQL avancé avec modèles relationnels).
  - Sécurité : Gestion des OTP, restrictions géographiques, et authentification avancée.


## 🚀 Points forts du projet
Interface sécurisée et intuitive pour la gestion des opérations financières.
Automatisation complète des calculs de commission et des limites de transaction.
Notifications avancées pour alerter en cas de dépassement de limites ou d'anomalies.
Architecture extensible pour intégrer de nouvelles fonctionnalités futures.

## 🔗 Lien vers le projet
Voici un lien vers le **projet Korifinances** : [Korifinances](https://github.com/TORNIXTECH/Korifinances)

## 📸 Capture d'écran
![Screenshot du projet **Korifinances_webapp**](assets/images/projets/Korifinances/webapp/login.png)  


##



Dans ce projet, j'ai principalement travaillé sur **_Korifinances_webapp_**:

- **Création de pages dynamiques et gestion du chargement des données** : Développement de pages interactives en Angular avec l'intégration d'un skeleton loader. Ce dernier
  s'affiche lors du changement de page, créant une maquette de la page avec des éléments en forme de "squelette" pendant que les données sont chargées, offrant ainsi une
  expérience utilisateur fluide et moderne tout en minimisant l'attente visible.




<!--
### Projet 7: **goparadize-api (gestion des favorie sur application mobile de rbnb)**

![Screenshot du projet 1](images/screenshot1.jpg)  
Description courte du projet...
-->






<!--
### Projet 8: **Flotyshub_app ()**

![Screenshot du projet 1](images/screenshot1.jpg)  
Description courte du projet...
-->





<!--
### Projet 9: **Tornixtech ()**

![Screenshot du projet 1](images/screenshot1.jpg)  
Description courte du projet...
-->

##💼 Projets personnels


## 📫 Me contacter

- **Email** : [konatebeh20@gmail.com](mailto:konatebeh20@gmail.com)
- **LinkedIn** : [Beh Konaté - LinkedIn](https://linkedin.com/in/beh-konaté-8804b7220)



<!--
**konatebeh20/konatebeh20** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
