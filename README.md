Vue d'ensemble

Ce projet démontre comment intégrer des processus d'intégration continue (CI) et de déploiement continu (CD) en utilisant GitHub Actions, FastAPI et Docker. Il inclut des workflows automatisés pour tester, exécuter et déployer automatiquement l'application après chaque modification du code.
Configuration du projet
Prérequis

    Python 3.7+
    FastAPI
    Uvicorn
    Docker
    GitHub

    Application FastAPI

Le fichier principal de l'application est main.py dans le dossier app. Voici un extrait du code de l'application :


Workflows GitHub Actions

Les workflows GitHub Actions se trouvent dans le dossier .github/workflows/. Voici un aperçu des workflows configurés :
Workflow d'exécution (run.yml)

Ce workflow est déclenché à chaque push ou pull request sur la branche main et permet d'installer les dépendances et de démarrer le serveur.
