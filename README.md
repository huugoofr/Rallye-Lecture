Rallye Lecture
Travail réalisé en PPE, 2ème année de BTS SIO
Le contexte du Rallye Lecture


Code Igniter

Pour réaliser le site du Rallye Lecture, nous utiliserons le framework CodeIgniter. Celui-ci propose au programmeur une bibliothèque de classes permettant la programmation sous PHP. Le patron de conception Modèle Vue Contrôleur (MCD) est aussi utiliser dans ce projet.

La base de données
Le projet nécessite le stockage de nombreuses informations (livres, auteurs, élèves, enseignants...). Pour réaliser la base de données, nous utiliserons le SGBDR MySQL. Celle-ci sera accessible en localhost.


La bibliothèque Aauth permet la gestion des autorisations des utilisateurs. Celle-ci est destinée à simplifier les opérations telles que la gestion des permissions, la création d'utilisateurs... Au delà de ces fonctionnalités assez simples, la bibliothèque propose aussi des fonctionnalités un peu plus avancées comme la gestion de groupes et l'envoi de messages privés entre utilisateurs. Le bon fonctionnement de cette bibliothèque nécessite la création de tables supplémentaires dans la base de données du projet RallyeLecture. L'execution du script (SQL) de création, fourni avec la bibliothèque, crée des tables.


L'état initial du Rallye Lecture
Le code du Rallye Lecture nous a été remis dans son état initial. Le but est de mettre en place des évolutions :

Ajout de la pagination
Modification du nombre de livres par pages (10 livres maximum)
Upload d'un fichier
Mise en place d'une barre de recherche pour les livres
Création d'un utilisateur
