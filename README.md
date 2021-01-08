# Progression Git

Application Web pour évaluer la progression des étudiants selon leur dépôt Git.

## Stage H2021

### Objectifs

* Gestion de dépôt Git pour plusieurs cours

* Tableau de bord du prof
    * importation de liste de classe via CSV de ColNet
    * création de un dépôt par
    * pour chaque cours:
        * un dépôt git pour le prof
        * en particulier, le script de validation à lancer pour tester
          la remise d'un étudiant
            * p.ex. une tâche Gradle
* Exploration du dépôt Git (via p.ex. le git-web par défaut)

* Tableau de bord de l'étudiant
    * liste de dépôts et accès aux indicateurs
    * configurer et valider mon courriel
    * ré-envoyer ma clé par courriel

* Se baser sur https://github.com/mathieu-bergeron/aquiletour pour:
    * importation d'une liste de classe vis CSV ColNet
    * le code Web de base
    * la connexion par courriel
    * le code de tableau de bord


### Technologies

Comme `aquiletour`:

* HTML 
* Typescript
* Apache comme serveur de fichiers
* Serveur de données en Java
* WebSocket pour la communication client/serveur
* Base de données SQLite pour commencer

### Échéancier

* 15 semaines: 25 janvier 2021 au 7 mai 2021
* Sprints de deux semaines

### Échéancier détaillé

NOTE: cet échéancier est sujet à changement

* Semaine 01:
    * installation
    * analyse des objectifs
    * familiarisation avec la librairie JGit (https://www.eclipse.org/jgit)

* Semaines 02-03:
    * exploration d'un dépôt Git ave git-web

* Semaines 03-04:
    * conception de la DB
    * affichage d'une liste de dépôts selon la DB

* Semaines 05-06:
    * script pour ajouter de l'info à la DB lors d'un push

* Semaines 07-08:
    * créations de dépôts git
    * génération de clés SSH

* Semaines 09-10:
    * tableau de bord d'un étudiant

* Semaines 11-12:
    * graphe de progression selon un dépôt Git
    * envoi de courriel lors de retard

* Semaines 13-14:
    * automatisation des tests
    * automatisation de la détection de plagiat

* Semaine 15:
    * finition

