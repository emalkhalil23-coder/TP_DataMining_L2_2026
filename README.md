# 📊 TP Data Mining - Pipeline d'Acquisition KDD

## 👤 Informations Personnelles
- **Nom :** Mariem med hanenne
- **Filière :** DAII
- **Encadrant :** Pr. EL BENANY Mohamed Mahmoud
- **Année :** 2025-2026

---

## 🎯 Objectif du Projet
L'objectif de ce travail est de mettre en place la première étape du processus **KDD** (Knowledge Discovery in Databases) : la **Collecte de Données multi-sources**. Ce projet démontre la capacité à consolider des informations provenant de supports hétérogènes dans un seul environnement d'analyse.

## 🛠️ Bibliothèques utilisées
Pour réaliser ce pipeline, les dépendances suivantes ont été installées :
* 🐼 **Pandas & Numpy** : Pour la manipulation et l'analyse des données.
* 🌐 **Requests** : Pour la consommation de l'API REST.
* 🗄️ **SQLAlchemy & SQLite3** : Pour l'extraction depuis la base de données.
* 📈 **Openpyxl** : Pour la gestion des fichiers Excel.

## 📂 Description des Sources de Données
Le projet fusionne quatre sources distinctes :
1. **Fichier CSV** : `student-mat.csv` (Données scolaires).
2. **Base de données SQL** : `tp_data_mining.db`.
3. **API Web** : Récupération de posts via `JSONPlaceholder`.
4. **Fichier Excel** : `donnees_test.xlsx` (Données de test créées manuellement).

## 🚀 Résultat Final
Le script produit un **DataFrame unique** fusionnant toutes ces sources. 
> **Note :** Le pipeline inclut également une étape de **Web Scraping** pour extraire des titres depuis le site `books.toscrape.com`.

---
*Ce projet a été réalisé dans le cadre du module Data Mining.*