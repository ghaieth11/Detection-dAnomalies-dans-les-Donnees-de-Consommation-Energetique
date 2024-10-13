# Détection d'Anomalies dans les Données de Consommation Énergétique

## Description du Projet

Ce projet vise à détecter des anomalies dans les données de consommation énergétique d'une entreprise en utilisant des algorithmes d'apprentissage automatique, notamment **Isolation Forest** et **One-Class SVM**. L'objectif est d'identifier des comportements inhabituels de consommation qui pourraient indiquer des inefficacités, des problèmes techniques ou des événements exceptionnels.

## Contexte

Dans un contexte où la consommation d'énergie est en constante augmentation, il est essentiel pour les entreprises et les collectivités de surveiller leur consommation afin de détecter rapidement toute anomalie. Ces anomalies peuvent être dues à :

- Des pannes d'équipement
- Des comportements inhabituels des utilisateurs
- Des variations saisonnières imprévues
- Des erreurs de mesure ou de saisie

La détection précoce des anomalies permet de minimiser les coûts d'exploitation et d'optimiser la consommation énergétique.

## Objectifs

- **Analyser et prétraiter les données** de consommation énergétique.
- **Visualiser** les tendances de consommation pour comprendre les comportements normaux.
- **Appliquer des algorithmes de détection d'anomalies** pour identifier les points de données inhabituels.
- **Interpréter les résultats** et proposer des recommandations.

## Jeu de Données

Le jeu de données utilisé, `Energy_consumption.csv`, comprend les variables suivantes :

- `Timestamp` : Date et heure de l'enregistrement.
- `Temperature` : Température ambiante au moment de la mesure.
- `Humidity` : Taux d'humidité.
- `SquareFootage` : Surface en pieds carrés.
- `Occupancy` : Nombre de personnes présentes.
- `HVACUsage` : Utilisation du système de chauffage, ventilation et climatisation (On/Off).
- `LightingUsage` : Utilisation de l'éclairage (On/Off).
- `RenewableEnergy` : Quantité d'énergie renouvelable produite.
- `DayOfWeek` : Jour de la semaine.
- `Holiday` : Indique si c'est un jour férié (Yes/No).
- `EnergyConsumption` : Consommation énergétique en kilowattheures (kWh).

## Prérequis

- **Python 3.x**
- Bibliothèques Python :
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

## Installation

1. **Cloner le dépôt** :

   ```bash
   git clone https://github.com/votre-utilisateur/Detection-dAnomalies-dans-les-Donnees-de-Consommation-Energetique.git


## Auteur

Ce projet a été réalisé par **ALOUI Ghaieth**, étudiant en **Mathématiques Appliquées et Modélisation** à **POLYTECH Nice Sophia** – **Université Côte d'Azur**
