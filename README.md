

# Projet Spring Boot - Adil El Houdaigui

## Description du Projet

Ce projet est une application Spring Boot développée par Adil El Houdaigui. Il fournit une structure complète pour un système de portail étudiant, offrant diverses fonctionnalités pour gérer les informations des étudiants et d'autres fonctionnalités associées.

## Fonctionnalités

- **Gestion des étudiants** : Ajouter, mettre à jour, supprimer et consulter les informations des étudiants.
- **Gestion des cours** : Gérer les cours, inscrire des étudiants et suivre leur progression.
- **Authentification et Autorisation** : Connexion sécurisée et contrôle d'accès pour différents rôles (par exemple, Administrateur, Étudiant, Enseignant).
- **Points de terminaison API** : Exposer des points de terminaison API RESTful pour interagir avec le système.

## Structure du Projet

Le projet est structuré comme suit :

- `.mvn/` : Fichiers de wrapper Maven
- `logs/` : Répertoire pour les fichiers de log
- `mvnw` & `mvnw.cmd` : Scripts de wrapper Maven pour Unix et Windows
- `pom.xml` : Fichier Project Object Model contenant les dépendances et configurations du projet
- `src/` : Répertoire du code source
  - `main/` : Fichiers sources principaux de l'application
  - `test/` : Fichiers de test
- `StudentPortal.iml` : Fichier de module IntelliJ IDEA
- `target/` : Répertoire pour la sortie compilée

## Instructions d'Installation

Pour configurer et exécuter ce projet sur votre machine locale, suivez ces étapes :

1. **Cloner le dépôt** :
    ```bash
    git clone https://github.com/Adilos-dev/Projet-SpringBoot.git
    cd Projet-SpringBoot
    ```

2. **Construire le projet en utilisant Maven** :
    ```bash
    ./mvnw clean install
    ```

3. **Exécuter l'application** :
    ```bash
    ./mvnw spring-boot:run
    ```

## Utilisation

Une fois l'application en cours d'exécution, vous pouvez y accéder via le port par défaut (généralement `8080`). Vous pouvez tester les différentes fonctionnalités en interagissant avec les points de terminaison API ou en utilisant une interface web si elle est fournie.

## Dépendances

- **Spring Boot** : Framework pour construire des applications Java
- **Maven** : Outil d'automatisation de la construction
- **Autres dépendances** : Listées dans `pom.xml`

## Contribution

Si vous souhaitez contribuer à ce projet, veuillez suivre ces étapes :

1. Forker le dépôt
2. Créer une nouvelle branche (`git checkout -b feature-branch`)
3. Apporter vos modifications et les commettre (`git commit -m 'Ajouter une fonctionnalité'`)
4. Pousser vers la branche (`git push origin feature-branch`)
5. Créer une pull request
