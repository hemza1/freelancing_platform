# Codify

Bienvenue dans la documentation du projet de fin d'études réalisé pour l'obtention du DUT en 2022. Ce projet consiste en une plateforme de services freelance, offrant une interface pour les clients et les freelancers afin de faciliter la collaboration et la réalisation de divers projets.

## Description du Projet
Ce projet vise à créer une plateforme web permettant aux utilisateurs de trouver des freelancers pour divers besoins, tels que le développement web, le design graphique, la rédaction, etc. Les freelancers peuvent créer des profils détaillés présentant leurs compétences, leur expérience et leurs tarifs, tandis que les clients peuvent publier des projets et engager des freelancers pour les réaliser.

## Fonctionnalités Principales
Inscription et Profilage: Les utilisateurs peuvent s'inscrire en tant que client ou freelancer et compléter leurs profils avec des informations pertinentes.
Publication de Projets: Les clients peuvent publier des descriptions détaillées de leurs projets, y compris les exigences, les délais et les budgets.
Recherche et Filtrage: Les utilisateurs peuvent rechercher des freelancers en fonction de critères spécifiques tels que les compétences, les avis clients et les tarifs.
Messagerie Intégrée: Une messagerie interne permet aux clients et aux freelancers de communiquer facilement pour discuter des détails du projet.
Gestion des Projets: Les clients peuvent suivre l'avancement de leurs projets, échanger des fichiers et valider les livrables.
Système de Paiement: Intégration d'un système de paiement sécurisé pour faciliter les transactions entre les clients et les freelancers.


## Installation et Configuration

### Cloner le Répertoire: Clonez ce dépôt sur votre machine locale en utilisant la commande suivante :
bash
Copy code
git clone https://github.com/votre_utilisateur/nom_du_projet.git

### Configuration de la Base de Données: Configurez les paramètres de la base de données dans le fichier config/database.php.

### Installation des Dépendances: Exécutez la commande suivante pour installer les dépendances nécessaires :

Copy code
composer install
### Migration de la Base de Données: Exécutez les migrations pour créer les tables requises dans la base de données :

Copy code
php artisan migrate
### Lancement du Serveur: Lancez le serveur en utilisant la commande suivante :

Copy code
php artisan serve
