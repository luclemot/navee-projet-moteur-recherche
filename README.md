# Projet Navee - Moteur de recherche d'images inversé

## Objectif du projet :

Ce travail est un moteur de recherche d'images inversées, c'est-à-dire qu'à partir d'une image, il vous renvoie les images les plus proches qu'il possède dans la base de données.
La base de données en question est une base d'oeuvres d'arts.

## Présentation de l'approche :
Il est divisé en trois grandes parties :
- la gestion de la base de données,
- la formation du modèle
- et un serveur web pour mettre le tout en place.

## Structure des fichiers :

### Data
- Le dossier [data](./data) gère la base de données et le fichier data.py contient le principam des fonctions pour travailler avec la base de données en sql.
- Le fichier [Data_Gen.py](./data/Data_Gen.py) sert à créer un générateur de données keras pour pouvoir gérer la base de données plus efficacement.

### Modèle
- Le dossier [web](./web) contient la page HTML créée.

## Utilisation du modèle :

- Téléchargement de la donnée :
Il suffit d'exécuter le fichier [setup.py](/setup.py) pour que les fichiers nécessaires soient telechargés (comme par exemple les poids des modèles).

- Initialisation du serveur web :
Le serveur web peut être initialisé à l'aide de [index.py](/index.py).