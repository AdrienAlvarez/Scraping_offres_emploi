# Scraping_offres_emploi

Ce repository contient un notebook pour scraper des offres d'emploi à partir du site [Welcome to the Jungle](https://www.welcometothejungle.com/) en utilisant la bibliothèque Selenium en Python.

## Contenu
- `Notebook_Scraping.ipynb`: Notebook principal contenant le code pour scraper les offres d'emploi.

## Prérequis
Pour exécuter le notebook, vous devez installer les dépendances suivantes :
```bash
pip install selenium pandas nltk joblib

## Fonctionnement
Le script utilise Selenium pour naviguer sur le site et extraire les détails des offres d'emploi. Après le scraping, le script nettoie et traite les données, puis les enregistre dans un fichier Excel pour une analyse ultérieure.

## Détails du code
Installation et importation des bibliothèques nécessaires.
Initialisation du webdriver Chrome avec des options spécifiques.
Navigue vers la page des offres d'emploi avec des filtres spécifiques.
Scraping des détails des offres d'emploi.
Nettoyage et prétraitement des données textuelles.
Chargement d'un modèle préentrainé pour une prédiction basée sur les titres des offres d'emploi.
Enregistrement des données dans un fichier Excel.
Résultats
Une fois le script exécuté, un fichier Excel contenant les détails des offres d'emploi est généré. Le chemin par défaut pour le fichier est /content/drive/My Drive/Rocket4Sales/jobs_offers.xlsx.

## Note
Assurez-vous d'avoir le bon chemin pour le modèle et le vectoriseur, et assurez-vous également d'avoir les bonnes permissions pour écrire dans le répertoire spécifié.

