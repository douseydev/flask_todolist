# Projet : Application de Todo List avec Flask

## Objectif du Projet

Le projet vise à développer une application de gestion de tâches (Todo List) permettant aux utilisateurs de gérer leurs tâches de manière efficace et organisée.

## Technologies Utilisées

- **Flask** : Framework web minimaliste en Python.
- **Flask-SQLAlchemy** : Extension pour l’intégration d’une base de données SQLAlchemy.
- **Flask-Migrate** : Extension pour la gestion des migrations de base de données.
- **Flask-Login** : Extension pour la gestion de l’authentification des utilisateurs.
- **SQLite** : Système de gestion de base de données relationnelle pour la gestion des tâches.
- **Bootstrap** : Framework CSS pour un design réactif et moderne.

## Fonctionnalités de l’Application

1. **Inscription et Connexion des Utilisateurs**
    - **Inscription** : Création de compte avec un nom d’utilisateur, une adresse e-mail et un mot de passe.
    - **Connexion** : Accès à l’application avec des informations d’identification.
    - **Mot de Passe Oublié** : Réinitialisation du mot de passe via un email de récupération.

2. **Gestion des Tâches**
    - **Ajout de Tâches** : Création de nouvelles tâches avec titre, description, date d’échéance et état (à faire, en cours, terminée).
    - **Liste des Tâches** : Affichage des tâches existantes avec possibilité de filtrer par état.
    - **Modification des Tâches** : Possibilité de modifier les détails d’une tâche existante.
    - **Suppression des Tâches** : Suppression de tâches non nécessaires.

3. **Authentification et Autorisation**
    - **Accès Restreint** : Seuls les utilisateurs connectés peuvent accéder à leurs listes de tâches.
    - **Permissions** : Chaque utilisateur ne peut gérer que ses propres tâches.

4. **Gestion des Utilisateurs**
    - **Profil Utilisateur** : Mise à jour des informations personnelles par l’utilisateur.

5. **Administration**
    - **Interface Administrateur** : Gestion des utilisateurs et des tâches pour les administrateurs.

## Structure du Projet

Prérequis : Assurez-vous d’avoir Flask et ses extensions installés et configurés.

### Organisation du Code :

- **app.py** : Contient le code logique de l’application Flask, y compris les modèles de données, les routes et les contrôleurs.
- **templates/** : Répertoire pour les templates HTML de l’interface utilisateur.
- **static/** : Répertoire pour les fichiers CSS, JavaScript et autres ressources statiques.
- **migrations/** : Répertoire pour les scripts de migration de base de données.

