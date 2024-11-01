# Spotify API Project

Ce projet utilise l'API de Spotify pour récupérer des informations sur les morceaux et les artistes, et crée des visualisations pour analyser les données.

## Pré-requis

- Python 3.8 (ou version supérieure)
- Compte Spotify Developer pour obtenir des identifiants d'API

## Installation

1. Clonez ce projet :

   ```bash
   git clone https://github.com/nathanaela-doriana/spotify_api_project.git
   cd spotify_api_project

2. Installez les dépendances :
   pip install -r requirements.txt

<<<<<<< HEAD
3. Configuration des identifiants API
Un fichier .env est inclus temporairement dans ce dépôt pour faciliter l'évaluation de l'exercice. Ce fichier contient les identifiants d'API nécessaires pour se connecter à l'API Spotify. Ces identifiants seront supprimés après l'évaluation.
=======
3. Configurez vos identifiants API en créant un fichier .env avec les informations suivantes :

    SPOTIPY_CLIENT_ID="votre_client_id"
   
    SPOTIPY_CLIENT_SECRET="votre_client_secret"
   
    SPOTIPY_REDIRECT_URL="votre_redirect_url"
>>>>>>> 7a714633e8b620ebd66f9cd336d2b47766b48398


5. Lancer le notebook Jupyter pour analyser et visualiser les données :
   jupyter notebook notebooks/spotify_analysis.ipynb

## Utilisation
Dans le notebook spotify_analysis.ipynb, vous trouverez des étapes pour :
 - Authentifier votre compte Spotify : En utilisant les identifiants API, le notebook vous permettra d'accéder à votre compte Spotify et de récupérer des informations sur les morceaux.
- Extraire les données des playlists Spotify : Le code extrait des informations sur les morceaux et artistes à partir des playlists spécifiées.
- Nettoyer et transformer les données : Des étapes de traitement de données sont incluses pour préparer les données pour l'analyse.
- Créer des visualisations : Génère des graphiques pour analyser la popularité des morceaux et des genres musicaux au fil des années.

## Structure du projet
- notebooks/spotify_analysis.ipynb : Notebook principal contenant le code d’analyse de données.
- data/ : Dossier pour stocker les données téléchargées.
- .env : Fichier contenant les identifiants de l'API Spotify (ne doit pas être partagé).
- requirements.txt : Liste des bibliothèques Python nécessaires pour exécuter ce projet.
- .gitignore : Fichier pour ignorer .env et d'autres fichiers temporaires lors de l'utilisation de Git.

## Exemple de visualisations
Ce projet crée des visualisations pour :
- Distribution de la popularité des morceaux : Montre comment la popularité des morceaux est répartie dans les playlists.
- Évolution des genres les plus écoutés : Visualise l'évolution des genres les plus populaires sur Spotify entre 2019 et 2023.
- Artistes les plus populaires : Affiche les artistes les plus populaires en fonction de la popularité moyenne de leurs morceaux.

## Exécution et conseils
Assurez-vous d'avoir les identifiants Spotify API en créant une application sur le Spotify Developer Dashboard.

Exécutez chaque cellule du notebook dans l'ordre pour garantir le bon fonctionnement de l'analyse et des visualisations.

Utilisez requirements.txt pour installer toutes les dépendances nécessaires avec la commande suivante, si ce n'est pas déjà fait :
 pip install -r requirements.txt

## Contribution
Les contributions sont les bienvenues ! N'hésitez pas à créer des issues ou à soumettre des pull requests pour améliorer ce projet.

